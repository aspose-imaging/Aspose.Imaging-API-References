---
title: "EmfImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "增强型图元文件格式（EMF）矢量图像格式支持的 API 是一个用于以设备无关方式处理图形图像并保留其原始属性的综合工具。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object，[com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)，[com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter)，[com.aspose.imaging.Image](../../com.aspose.imaging/image)，[com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)，[com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

增强型图元文件格式（EMF）矢量图像格式支持的 API 是一个用于以设备无关方式处理图形图像并保留其原始属性的综合工具。该 API 旨在保持比例、尺寸、颜色等图形属性，支持 EMF Plus 格式，并提供裁剪区域、调整画布和图像大小、旋转、翻转、设置图像调色板、导出和导入到 APS 设备上下文、压缩以及将 EMF 转换为其他格式的功能，确保对 EMF 图像进行多样化操作并在各应用程序中实现无缝集成。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfImage()](#EmfImage--) | 通过初始化 [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) 类的新实例，开始使用 EMF 图像。 |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | 通过指定宽度和高度参数，创建 [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeader()](#getHeader--) | 使用此属性检索 EMF 元文件头记录。 |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | 使用此属性修改 EMF 元文件头记录。 |
| [isCached()](#isCached--) | 访问一个值，以指示对象的数据当前是否已缓存，从而消除额外读取数据的需求。 |
| [getRecords()](#getRecords--) | 检索或修改与对象关联的记录。 |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | 修改与对象关联的记录。 |
| [getFileFormat()](#getFileFormat--) | 访问与对象关联的文件格式值。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 检索特定于光栅图像的每像素位数计数，因为此参数不适用于矢量图像。 |
| [getWidthF()](#getWidthF--) | 获取图像的宽度，为精确渲染和处理提供必要信息。 |
| [getHeightF()](#getHeightF--) | 检索图像的高度，以便实现精确的渲染和布局调整。 |
| [cacheData()](#cacheData--) | 使用此方法，可高效缓存数据并防止从底层 `DataStreamSupporter.DataStreamContainer`（[DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)）重复加载。 |
| [getUsedFonts()](#getUsedFonts--) | 使用此方法检索元文件中使用的字体列表。 |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | 使用此函数轻松调整画布大小。 |
| [getOriginalOptions()](#getOriginalOptions--) | 获取原始图像选项。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | 设置图像调色板。 |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 EMF 在内的所有类型图像的统一方式。
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // 文本将被转换为形状。
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // 页面尺寸。
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // 设置水平边距
    rasterizationOptions.setBorderX(50);

    // 设置垂直边距
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```


## Example: The following example shows how to convert a compressed images (*.
以下示例展示了如何将压缩图像（*.emz、*.wmz、*.svgz）转换为栅格格式。
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


通过初始化 [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) 类的新实例，开始使用 EMF 图像。非常适合轻松高效地将 EMF 图像快速集成到您的项目中。

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


通过指定宽度和高度参数，创建 [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) 类的新实例。此构造函数简化了使用特定尺寸初始化 EMF 图像的过程，提高了开发工作流的效率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


使用此属性检索 EMF 元文件头记录。非常适合在应用程序中高效管理元文件数据。通过简化对元文件头信息的访问，提升工作流效率。

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


使用此属性修改 EMF 元文件头记录。非常适合在应用程序中高效管理元文件数据。通过简化对元文件头信息的访问，提升工作流效率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


访问一个值，以指示对象的数据当前是否已缓存，从而消除额外读取数据的需求。通过快速判断缓存数据是否可立即访问来提升效率。通过简化的数据检索流程优化工作流。

**Returns:**
布尔值 - 如果对象的数据已缓存则为 `true`；否则为 `false`。
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


检索或修改与对象关联的记录。高效访问和管理记录集合，以提升数据操作和处理。通过无缝交互对象的记录来优化工作流。

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


修改与对象关联的记录。高效访问和管理记录集合，以提升数据操作和处理。通过无缝交互对象的记录来优化工作流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | 记录。 |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


访问与对象关联的文件格式值。轻松确定对象关联文件的格式，以实现流畅的处理和兼容性检查。通过轻松检索文件格式信息简化工作流。

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


检索光栅图像特有的每像素位数，因为该参数不适用于矢量图像。快速确定光栅图像的像素深度，以进行精确分析和操作，确保图像数据的准确处理。

**Returns:**
int - 图像每像素位数。
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


获取图像的宽度，提供精确渲染和处理所需的关键信息。快速检索图像宽度，以确保在各种应用和平台中的兼容性和正确布局。

**Returns:**
float - 图像宽度（像素）。
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


检索图像的高度，帮助实现精确渲染和布局调整。访问高度属性可确保在不同平台和应用之间的兼容性和无缝集成。

**Returns:**
float - 图像高度（像素）。
### cacheData() {#cacheData--}
```
public void cacheData()
```


使用此方法高效缓存数据并防止从底层 `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) 进行冗余加载。提升性能并简化应用中的数据访问，优化资源利用以提高响应速度。


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // 缓存数据以加载所有记录。
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // 键是记录类型，值是该类型在 WMF 图像中的记录数量。
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // 收集统计信息
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // 打印统计信息
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // 使用空格对齐输出
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//输出可能如下所示：
//记录总数：1188
//记录类型                              数量
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


使用此方法检索元文件中使用的字体列表。深入了解字体使用情况，帮助高效管理和优化字体资源，以提升渲染和显示的保真度。

**Returns:**
java.lang.String[] - 字体列表
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


使用此函数轻松调整画布大小。非常适合在不改变内容的情况下调整图像的整体尺寸。提升展示效果并轻松为各种显示尺寸准备图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 新的矩形。 |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


获取原始图像选项。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


设置图像调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

