---
title: "OtgImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "使用我们的 API 处理 OpenDocument 模板 OTG 绘图图像文件，利用 OpenDocument XML 格式和图形内容，实现无缝操作。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

使用我们的 API 处理 OpenDocument 模板 (OTG) 绘图图像文件，利用 OpenDocument XML 格式和图形内容实现无缝操作。轻松解析文档、定制背景颜色并调整页面尺寸，确保对您的 OTG 矢量图形项目拥有最佳的控制和灵活性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | 通过提供流容器和加载选项来初始化一个新的 [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) 对象。 |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | 通过提供流容器创建 [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) 类的新对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 此属性提供对 OTG 文件格式的访问，提供有关图像文件中封装数据类型的关键洞察。 |
| [getPages()](#getPages--) | 检索与图像关联的页面集合，使软件开发人员能够高效地访问和操作每个单独的页面。 |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


通过提供流容器和加载选项来初始化一个新的 [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) 对象。此构造函数使开发人员能够在指定自定义加载配置的同时，高效地从流中加载 OTG 图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


通过提供流容器创建 [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) 类的新对象。此构造函数使开发人员能够直接从流容器创建 OTG 图像，简化 OTG 图像数据的处理过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流容器。 |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


此属性提供对 OTG 文件格式的访问，提供有关图像文件中封装数据类型的关键洞察。它是软件开发人员的重要参考点，使他们能够在应用程序中有效处理 OTG 文件。通过使用此属性，您可以确定图像文件的具体格式，从而在软件系统中实现对 OTG 文件的无缝集成和操作。

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


检索与图像关联的页面集合，使软件开发人员能够高效地访问和操作每个单独的页面。此属性促进对页面的无缝遍历，以执行各种操作，提升图像处理应用程序的功能性和多样性。

**Returns:**
com.aspose.imaging.Image[] - 页面。
