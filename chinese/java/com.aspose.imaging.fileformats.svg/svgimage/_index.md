---
title: "SvgImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "使用我们的 API 操作标量矢量图形（SVG）图像文件，利用基于 XML 的文本格式的强大功能，实现无缝的自定义和可扩展性。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

使用我们的 API 操作标量矢量图形（SVG）图像文件，利用基于 XML 的文本格式的强大功能，实现无缝的自定义和可扩展性。轻松加载 SVG 图像、栅格化矢量元素并转换为其他格式，同时控制压缩级别，以优化项目的文件大小和质量。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | 实例化一个新的 [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) 类对象，使用指定的路径定位并加载图像。 |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | 创建一个新的 [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) 类实例，从提供的流中加载图像。 |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | 实例化一个新的 [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) 对象，使用指定的宽度和高度。 |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | 创建一个新的 [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) 类实例，使用指定的 SVG 选项、图像宽度和高度参数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isCached()](#isCached--) | 检索一个布尔值，指示对象的数据当前是否已缓存，从而消除额外的数据读取操作的需求。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 检索图像的每像素位数。 |
| [getFileFormat()](#getFileFormat--) | 检索图像的文件格式，提供用于处理和兼容性检查的关键元数据。 |
| [cacheData()](#cacheData--) | 缓存数据并保证不再从底层 `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) 加载数据。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 调整图像大小以适应指定的尺寸，同时保持其宽高比。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 裁剪指定的矩形。 |
| [rotate(float angle)](#rotate-float-) | 围绕中心旋转图像。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | 对图像应用指定的调色板，支持出于美观或功能目的的颜色方案定制。 |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// 从文件流加载 SVG 图像。
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // 为了栅格化 SVG，我们需要指定栅格化选项。
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
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


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


实例化一个新的 [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) 类对象，使用指定的路径定位并加载图像。此构造函数便于从外部文件创建 SVG 图像实例，实现与软件系统和工作流的无缝集成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 加载图像的路径以及用于初始化像素和调色板数据的路径。 |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


创建一个新的 [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) 类实例，从提供的流中加载图像。此构造函数支持直接从流加载 SVG 图像，提升在软件应用中处理图像资源的灵活性和效率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的流以及用于初始化像素和调色板数据的流。 |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


实例化一个新的 [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) 对象，使用指定的宽度和高度。此构造函数允许开发者创建具有预定义尺寸的 SVG 图像，便于在初始化期间精确控制图像大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


创建一个新的 [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) 类实例，使用指定的 SVG 选项、图像宽度和高度参数。此构造函数使开发者能够使用自定义选项和尺寸初始化 SVG 图像，提供在管理 SVG 内容和布局方面的灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | 该 SVG 选项。 |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |

### isCached() {#isCached--}
```
public boolean isCached()
```


检索一个布尔值，指示对象的数据当前是否已缓存，从而消除额外的数据读取操作的需求。此属性提供对当前缓存状态的洞察，优化数据检索和处理工作流，以提升性能和效率。

**Returns:**
布尔值 - 如果对象的数据已缓存则为 `true`；否则为 `false`。
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


检索图像的每像素位数。需要注意的是，此参数不适用于矢量图像，因为矢量图像不以像素计量。此属性提供有关图像颜色深度的关键信息，有助于处理和操作任务。

**Returns:**
int - 图像每像素位数。
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


检索图像的文件格式，提供用于处理和兼容性检查的关键元数据。此属性对于确定适当的解码和编码策略以在不同系统和应用中有效处理图像数据至关重要。

**Returns:**
long - 文件格式
### cacheData() {#cacheData--}
```
public void cacheData()
```


缓存数据并确保不再从底层 `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\\#getDataStreamContainer)) 加载数据。此优化通过消除冗余的数据检索操作提升性能，特别适用于需要频繁访问图像数据的场景。

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


将图像调整为适合指定尺寸，同时保持其宽高比。此方法提供了一种便捷的方式来在不失真图像比例的情况下调整图像大小，确保根据所需尺寸实现最佳显示或存储。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


裁剪指定的矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


围绕中心旋转图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


将指定的调色板应用于图像，允许为美观或功能目的自定义配色方案。此方法在管理颜色调色板以满足各种设计或应用需求方面提供了灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

