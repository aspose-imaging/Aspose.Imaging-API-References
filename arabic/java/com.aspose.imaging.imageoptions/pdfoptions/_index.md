---
title: "PdfOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات PDF."
type: docs
weight: 36
url: /ar/java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

خيارات PDF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | يقوم بتهيئة نسخة جديدة من الفئة [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | يحصل على قيمة تشير إلى استخدام دقة DPI الأصلية للصورة |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | يضبط قيمة تشير إلى استخدام دقة DPI الأصلية للصورة |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | يحصل أو يضبط البيانات الوصفية للمستند. |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | يحصل أو يضبط البيانات الوصفية للمستند. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | خيارات النواة لملف PDF |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | خيارات النواة لملف PDF |
| [getPageSize()](#getPageSize--) | يحصل على حجم الصفحة. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | يضبط حجم الصفحة. |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | يحصل على قيمة تشير إلى استخدام دقة DPI الأصلية للصورة |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | يضبط قيمة تشير إلى استخدام دقة DPI الأصلية للصورة سَتُزال منذ الإصدار 25.3 |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليين فقط إلى الصفحات المقابلة في مستند PDF الناتج.
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


يقوم بتهيئة نسخة جديدة من الفئة [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions).

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


يحصل على قيمة تشير إلى استخدام دقة DPI الأصلية للصورة

القيمة: مؤشر لاستخدام دقة DPI الأصلية للصورة

**Returns:**
boolean - قيمة تشير إلى استخدام دقة DPI الأصلية للصورة
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


يضبط قيمة تشير إلى استخدام دقة DPI الأصلية للصورة

القيمة: مؤشر لاستخدام دقة DPI الأصلية للصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى استخدام دقة DPI الأصلية للصورة |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


يحصل أو يضبط البيانات الوصفية للمستند.

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


يحصل أو يضبط البيانات الوصفية للمستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


خيارات النواة لملف PDF

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


خيارات النواة لملف PDF

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


يحصل على حجم الصفحة.

القيمة: حجم الصفحة.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


يضبط حجم الصفحة.

القيمة: حجم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | حجم الصفحة. |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


يحصل على قيمة تشير إلى استخدام دقة DPI الأصلية للصورة

القيمة: مؤشر لاستخدام دقة DPI الأصلية للصورة

**Returns:**
boolean - قيمة تشير إلى استخدام دقة DPI الأصلية للصورة
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


يضبط قيمة تشير إلى استخدام دقة DPI الأصلية للصورة سَتُزال منذ الإصدار 25.3

القيمة: مؤشر لاستخدام دقة DPI الأصلية للصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| useOriginalImageSize | boolean | قيمة تشير إلى استخدام دقة DPI الأصلية للصورة |

