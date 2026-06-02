---
title: "CdrImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "CorelDRAW CDR 矢量图像格式支持的 API 是面向矢量图形开发者的必备工具包。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

CorelDRAW CDR 矢量图像格式支持的 API 是面向矢量图形开发者的必备工具包。该 API 能够无缝处理 CDR 文件，支持对文本、线条、形状、图像、颜色和效果等多种元素的存储和操作。凭借其完整的功能，开发者可以高效地处理图像内容的矢量表示，确保在以编程方式创建和编辑 CorelDRAW 矢量图形时的精确性和灵活性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | 通过使用流和 loadOptions 参数初始化新实例，轻松开始使用 [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) 类。 |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | 通过使用流和 loadOptions 参数初始化新实例，轻松开始使用 [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) 类。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | 使用此用户友好的属性，轻松获取图像的默认页面。 |
| [isCached()](#isCached--) | 轻松判断对象的数据是否已缓存，省去读取数据的需求。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 使用此用户友好的属性，轻松获取图像的位深度。 |
| [getPageCount()](#getPageCount--) | 使用此直观属性，轻松获取或更新图像的总页数。 |
| [getPages()](#getPages--) | 使用此直观的属性，流畅获取图像的页面。 |
| [getCdrDocument()](#getCdrDocument--) | 使用此直观属性，轻松获取或更新 CDR 文档。 |
| [getFileFormat()](#getFileFormat--) | 使用此直观属性，轻松获取图像的文件格式。 |
| [getWidth()](#getWidth--) | 获取图像宽度。 |
| [getHeight()](#getHeight--) | 获取图像高度。 |
| [cacheData()](#cacheData--) | 使用此用户友好方法，轻松缓存数据，以防止从底层源再次加载。 |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | 使用此直观的方法自定义图像的颜色调色板。 |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// 从 CDR 文件加载图像。
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // 此调用仅缓存默认页面。
    image.cacheData();

    // 缓存所有页面，以便不再从底层数据流加载额外数据。
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


通过使用流和 loadOptions 参数初始化新实例，轻松开始使用 [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) 类。非常适合希望以便捷方式从各种数据源加载 CDR 图像并根据需要自定义加载过程的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


通过使用流和 loadOptions 参数初始化新实例，轻松开始使用 [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) 类。非常适合希望以便捷方式从各种数据源加载 CDR 图像并根据需要自定义加载过程的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.ms.System.IO.Stream | 流。 |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | 加载选项。 |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


使用此用户友好的属性，轻松获取图像的默认页面。非常适合希望快速访问图像主页面、确保高效导航和管理的开发者。

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


轻松判断对象的数据是否已缓存，省去读取数据的需求。非常适合希望通过高效利用缓存数据来优化性能、确保更快访问信息的开发者。

**Returns:**
布尔值 - 如果对象的数据已缓存则为 `true`；否则为 `false`。
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


使用此用户友好的属性，轻松获取图像的位深度。适用于希望确定图像细节级别或颜色深度、确保准确处理和操作的开发者。

**Returns:**
int - 图像每像素位数。
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


使用此直观属性，轻松获取或更新图像的总页数。非常适合希望动态管理多页图像、确保高效导航和操作图像内容的开发者。

**Returns:**
int - 页数。
### getPages() {#getPages--}
```
public final Image[] getPages()
```


使用此直观属性无缝检索图像的页面。适用于希望访问和操作多页图像中各个页面的开发者，确保高效的导航和处理。

**Returns:**
com.aspose.imaging.Image[] - 页面。

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


使用此直观属性，轻松获取或更新 CDR 文档。非常适合希望访问或修改 CDR 文档、在应用中实现灵活高效的开发者。

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


使用此直观属性，轻松获取图像的文件格式。非常适合希望动态确定图像格式、确保在应用中兼容性和准确处理的开发者。

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像宽度。

值：图像宽度。

**Returns:**
int - 图像宽度。
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像高度。

值：图像高度。

**Returns:**
int - 图像高度。
### cacheData() {#cacheData--}
```
public void cacheData()
```


使用此用户友好方法，轻松缓存数据，以防止从底层源再次加载。非常适合希望通过预加载数据来优化性能、确保在应用中更快访问和更流畅操作的开发者。`DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// 从 CDR 文件加载图像。
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // 此调用仅缓存默认页面。
    image.cacheData();

    // 缓存所有页面，以便不再从底层数据流加载额外数据。
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


使用此直观方法自定义图像的调色板。适用于希望动态应用特定配色方案或调整的开发者，确保对图像视觉外观的精确控制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 要设置的调色板。 |
| updateColors | boolean | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

