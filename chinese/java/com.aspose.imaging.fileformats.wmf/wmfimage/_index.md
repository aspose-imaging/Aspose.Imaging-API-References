---
title: "WmfImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "使用我们的 API 操作 Microsoft Windows Metafile WMF 图像，能够无缝处理存储在可变长度记录中的矢量和位图数据。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object，[com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)，[com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter)，[com.aspose.imaging.Image](../../com.aspose.imaging/image)，[com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)，[com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

使用我们的 API 操作 Microsoft Windows Metafile (WMF) 图像，能够无缝处理存储在可变长度记录中的矢量和位图数据。轻松对图像进行缩放、旋转和翻转，并可设置自定义图像调色板。将 WMF 文件转换为压缩的 WMZ 格式，或保存为栅格图像格式，以实现跨平台和应用的多种使用场景。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfImage()](#WmfImage--) | 创建 [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) 类的新实例，以便进一步操作和处理 Windows Metafile (WMF) 图像数据。 |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | 实例化 [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) 类的新对象，并可自定义宽度和高度参数，从而创建符合特定尺寸的空白 WMF 图像。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isCached()](#isCached--) | 获取一个布尔值，指示对象的数据当前是否已缓存，从而消除额外读取数据的操作需求。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像的每像素位数，表示颜色深度或颗粒度的水平。 |
| [getWidthF()](#getWidthF--) | 访问图像的宽度，表示水平轴上的像素数量。 |
| [getHeightF()](#getHeightF--) | 访问图像的高度，表示垂直轴上的像素数量。 |
| [getInch()](#getInch--) | 访问或修改 inch 属性，该属性表示一种通常用于在打印或显示环境中指定物理尺寸的计量单位。 |
| [setInch(int value)](#setInch-int-) | 访问或修改 inch 属性，该属性表示一种通常用于在打印或显示环境中指定物理尺寸的计量单位。 |
| [getFileFormat()](#getFileFormat--) | 访问与图像关联的文件格式值，提供图像存储格式的信息。 |
| [getFrameBounds()](#getFrameBounds--) | 访问帧的边界，指示其在图像中的位置和尺寸。 |
| [cacheData()](#cacheData--) | 高效缓存数据，消除从底层 `DataStreamSupporter.DataStreamContainer`（[DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)）额外加载的需求。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | 将指定的调色板应用于图像，实现颜色表示的自定义。 |
| [getUsedFonts()](#getUsedFonts--) | 获取元文件中使用的字体列表，提供对图像中所用字体资源的洞察。 |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | 调整图像的画布大小，在保持图像内容的同时修改其尺寸。 |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | 将指定的记录对象合并到图像中，使用额外的数据或元数据丰富其内容。 |
| [getPostScript()](#getPostScript--) | 访问与图像关联的 PostScript 数据，提供其结构或内容的详细信息。 |
| [getOriginalOptions()](#getOriginalOptions--) | 获取原始图像选项。 |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // 文本将被转换为形状。
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // 页面尺寸。
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
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


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


创建一个新的 [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) 类实例，以便进一步操作和处理 Windows Metafile (WMF) 图像数据。此构造函数提供了一个用于处理 WMF 图像的基础对象，使得在您的应用程序功能中无缝集成 WMF 图像处理能力。

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


实例化一个新的 [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) 类，并可自定义宽度和高度参数，以便创建符合特定尺寸的空白 WMF 图像。利用此构造函数可动态生成具有精确尺寸的 WMF 图像，实现应用程序中灵活的图像创建和操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |

### isCached() {#isCached--}
```
public boolean isCached()
```


检索一个布尔值，指示对象的数据当前是否已缓存，从而消除额外读取数据的需求。使用此属性可通过判断对象的数据是否已随时可用，来优化性能，避免在您的应用程序中进行昂贵的数据检索过程。

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


检索图像每像素位数的计数，指示颜色深度或颗粒度的水平。使用此属性可确定图像的颜色表示和精度，便于在您的应用程序中进行兼容性检查和与颜色相关的处理。

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


访问图像的宽度，指示水平轴上的像素数量。使用此属性可确定图像的空间尺寸和宽高比，从而在您的应用程序中实现精确的布局和渲染调整。

**Returns:**
float - 图像宽度（像素）。
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


访问图像的高度，表示垂直轴上的像素数量。使用此属性可确定图像的空间尺寸和宽高比，从而在您的应用程序中实现准确的布局和渲染调整。

**Returns:**
float - 图像高度（像素）。
### getInch() {#getInch--}
```
public int getInch()
```


访问或修改 inch 属性，代表通常用于在打印或显示环境中指定物理尺寸的度量单位。使用此属性可设定或获取与图像关联的英寸值，从而在您的应用程序中实现物理尺寸的准确表示。

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


访问或修改 inch 属性，代表通常用于在打印或显示环境中指定物理尺寸的度量单位。使用此属性可设定或获取与图像关联的英寸值，从而在您的应用程序中实现物理尺寸的准确表示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


访问与图像关联的文件格式值，提供图像存储格式的信息。使用此属性可确定图像的文件格式，便于在您的应用程序中进行兼容性检查和特定格式的处理。

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


访问帧的边界，指示其在图像中的位置和尺寸。使用此属性可检索帧的空间位置信息，从而在您的应用程序中实现精确的操作和渲染。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


高效地缓存数据，消除从底层 `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) 进行额外加载的需求。使用此方法可通过存储和访问本地数据缓存来优化性能并最小化资源使用。


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // 缓存数据以加载所有记录。
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // 键是记录类型，值是该类型在 WMF 图像中的记录数量。
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // 收集统计信息
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
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
    wmfImage.dispose();
}

//输出可能如下所示：
//记录总数：613
//记录类型                              数量
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


将指定的调色板应用于图像，以实现颜色表示的自定义。使用此方法可增强视觉渲染，并在您的应用程序中实现特定的颜色效果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


检索元文件中使用的字体列表，提供对图像中使用的字体资源的洞察。使用此方法分析字体使用情况，并确保在您的应用程序中进行渲染或进一步处理时字体可用。

**Returns:**
java.lang.String[] - 字体列表
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


调整图像的画布大小，在保持图像内容的同时修改其尺寸。使用此方法可在不更改内容的情况下改变画布大小，便于在您的应用程序中进行布局调整和构图更改。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 新的矩形。 |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


将指定的记录对象合并到图像中，为其内容添加额外的数据或元数据。使用此方法可无缝地将记录对象集成到图像中，促进在您的应用程序中进行全面的数据存储和组织。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | 记录。 |

**Returns:**
int - 记录数量。
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


访问与图像关联的 PostScript 数据，提供有关其结构或内容的详细信息。使用此方法检索 PostScript 数据，以便在您的应用程序中进行进一步分析或处理，实现与 PostScript 渲染或操作相关的高级功能。

**Returns:**
java.lang.String - PostScript 脚本
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


获取原始图像选项。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
