---
title: PdfOptions
second_title: Aspose.Imaging for Java API Reference
description: The PDF options.
type: docs
weight: 36
url: /java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

The PDF options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initializes a new instance of the [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | Gets a value indicating to use the original image DPI resolution |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | Sets a value indicating to use the original image DPI resolution |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | Gets or sets metadata for document. |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | Gets or sets metadata for document. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | The PDF core options |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | The PDF core options |
| [getPageSize()](#getPageSize--) | Gets the size of the page. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Sets the size of the page. |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | Gets a value indicating to use the original image DPI resolution |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | Sets a value indicating to use the original image DPI resolution WILL BE REMOVED SINCE 25.3 |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages to the corresponding pages of the output PDF document.
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


Initializes a new instance of the [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions) class.

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


Gets a value indicating to use the original image DPI resolution

Value: Indicator to use the original image DPI resolution

**Returns:**
boolean - a value indicating to use the original image DPI resolution
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


Sets a value indicating to use the original image DPI resolution

Value: Indicator to use the original image DPI resolution

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating to use the original image DPI resolution |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


Gets or sets metadata for document.

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


Gets or sets metadata for document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


The PDF core options

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


The PDF core options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


Gets the size of the page.

Value: The size of the page.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


Sets the size of the page.

Value: The size of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | the size of the page. |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


Gets a value indicating to use the original image DPI resolution

Value: Indicator to use the original image DPI resolution

**Returns:**
boolean - a value indicating to use the original image DPI resolution
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


Sets a value indicating to use the original image DPI resolution WILL BE REMOVED SINCE 25.3

Value: Indicator to use the original image DPI resolution

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| useOriginalImageSize | boolean | a value indicating to use the original image DPI resolution |

