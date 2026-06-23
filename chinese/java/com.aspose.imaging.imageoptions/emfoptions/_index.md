---
title: "EmfOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "Emf 选项。"
type: docs
weight: 19
url: /zh/java/com.aspose.imaging.imageoptions/emfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.MetafileOptions](../../com.aspose.imaging.imageoptions/metafileoptions)
```
public class EmfOptions extends MetafileOptions
```

Emf 选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfOptions()](#EmfOptions--) |  |
| [EmfOptions(float dpiX, float dpiY)](#EmfOptions-float-float-) | 初始化 `EmfOptions` 类的新实例。 |
| [EmfOptions(float dpi)](#EmfOptions-float-) |  |
| [EmfOptions(EmfOptions emfOptions)](#EmfOptions-com.aspose.imaging.imageoptions.EmfOptions-) | 初始化 `EmfOptions` 类的新实例。 |

## Example: The following example shows how to convert a multipage vector image to EMF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.emf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.EmfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页。事实上，由于 EMF 不是多页格式，只会转换一页。
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
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

### EmfOptions() {#EmfOptions--}
```
public EmfOptions()
```


### EmfOptions(float dpiX, float dpiY) {#EmfOptions-float-float-}
```
public EmfOptions(float dpiX, float dpiY)
```


初始化 `EmfOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpiX | float |  |
| dpiY | float |  |

### EmfOptions(float dpi) {#EmfOptions-float-}
```
public EmfOptions(float dpi)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpi | float |  |

### EmfOptions(EmfOptions emfOptions) {#EmfOptions-com.aspose.imaging.imageoptions.EmfOptions-}
```
public EmfOptions(EmfOptions emfOptions)
```


初始化 `EmfOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| emfOptions | [EmfOptions](../../com.aspose.imaging.imageoptions/emfoptions) | EMF 选项。 |

