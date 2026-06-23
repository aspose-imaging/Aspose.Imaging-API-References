---
title: "PdfOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "PDF 选项。"
type: docs
weight: 36
url: /zh/java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

PDF 选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | 初始化 [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | 获取指示使用原始图像 DPI 分辨率的值 |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | 设置指示使用原始图像 DPI 分辨率的值 |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | 获取或设置文档的元数据。 |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | 获取或设置文档的元数据。 |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | PDF 核心选项 |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | PDF 核心选项 |
| [getPageSize()](#getPageSize--) | 获取页面的大小。 |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | 设置页面的大小。 |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | 获取指示使用原始图像 DPI 分辨率的值 |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | 设置指示使用原始图像 DPI 分辨率的值（自 25.3 版起将被移除） |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅将前两页导出到输出 PDF 文档的相应页面。
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

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


初始化 [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions) 类的新实例。

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


获取指示使用原始图像 DPI 分辨率的值

值：指示使用原始图像 DPI 分辨率

**Returns:**
布尔 - 指示使用原始图像 DPI 分辨率的值
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


设置指示使用原始图像 DPI 分辨率的值

值：指示使用原始图像 DPI 分辨率

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示使用原始图像 DPI 分辨率的值 |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


获取或设置文档的元数据。

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


获取或设置文档的元数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


PDF 核心选项

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


PDF 核心选项

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


获取页面的大小。

值：页面的大小。

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


设置页面的大小。

值：页面的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | 页面的大小。 |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


获取指示使用原始图像 DPI 分辨率的值

值：指示使用原始图像 DPI 分辨率

**Returns:**
布尔 - 指示使用原始图像 DPI 分辨率的值
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


设置指示使用原始图像 DPI 分辨率的值（自 25.3 版起将被移除）

值：指示使用原始图像 DPI 分辨率

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| useOriginalImageSize | boolean | 指示使用原始图像 DPI 分辨率的值 |

