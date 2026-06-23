---
title: "OdgImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "使用我们的 API 操作 OpenDocument Graphic ODG 矢量图像文件格式，该格式被 OpenOffice 和 LibreOffice Draw 应用广泛用于以矢量格式存储绘图元素。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

使用我们的 API 操作 OpenDocument Graphic (ODG) 矢量图像文件格式，该格式被 OpenOffice 和 LibreOffice Draw 应用广泛用于以矢量格式存储绘图元素。无缝解析文档、访问页面、调整图像大小和旋转，确保高效处理和定制 ODG 文件，以满足您的特定需求。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | 通过启动一个新的实例来创建 [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) 类对象。 |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | 为在软件解决方案中实现无缝集成而打造，[OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) 构造函数通过利用流容器来初始化新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 使用此用户友好的属性轻松检索文件格式值。 |
| [getPages()](#getPages--) | 检索页面集合，此属性使能够访问与图像关联的全部页面。 |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载图像的统一方式。
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // 转换为 OdgImage
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // 获取所有页面
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // 进行一些图像处理
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


通过启动一个新的实例来创建 [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) 类对象。利用流容器结合加载选项参数的潜力，保持多功能构造函数以无缝加载图像。此构造函数提升了高效的图像处理能力，提供可定制的加载配置，以在各种场景中实现更强的适应性和性能。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流。 |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项 |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


为实现与软件解决方案的无缝集成而精心打造，[OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) 构造函数通过利用流容器来初始化新实例。此方法确保在软件环境中高效处理 ODG 图像数据，优化资源利用并促进简化的图像处理工作流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流容器。 |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


使用此用户友好的属性即可轻松获取文件格式值。非常适合需要快速访问信息的开发者。

**Returns:**
long - 文件格式的值
### getPages() {#getPages--}
```
public Image[] getPages()
```


检索页面集合时，此属性使得能够访问与图像关联的全部页面。通过访问此属性，开发人员可以遍历各个页面、根据索引检索特定页面，或对整个集合执行批量操作。

**Returns:**
com.aspose.imaging.Image[] - 页面。
