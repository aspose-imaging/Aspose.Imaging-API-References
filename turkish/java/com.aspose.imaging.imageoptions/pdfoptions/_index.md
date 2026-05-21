---
title: "PdfOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "PDF seçenekleri."
type: docs
weight: 36
url: /tr/java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

PDF seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | Orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değeri alır |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | Orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değeri ayarlar |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | Belge için üst veriyi alır veya ayarlar. |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | Belge için üst veriyi alır veya ayarlar. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | PDF çekirdek seçenekleri |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | PDF çekirdek seçenekleri |
| [getPageSize()](#getPageSize--) | Sayfanın boyutunu alır. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Sayfanın boyutunu ayarlar. |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | Orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değeri alır |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | Orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değeri ayarlar 25.3'ten itibaren KALDIRILACAKTIR |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Yalnızca ilk iki sayfayı çıktı PDF belgesinin ilgili sayfalarına dışa aktar.
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


[PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions) sınıfının yeni bir örneğini başlatır.

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


Orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değeri alır

Değer: Orijinal görüntü DPI çözünürlüğünün kullanılacağını gösteren belirteç

**Returns:**
boolean - orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değer
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


Orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değeri ayarlar

Değer: Orijinal görüntü DPI çözünürlüğünün kullanılacağını gösteren belirteç

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değer |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


Belge için üst veriyi alır veya ayarlar.

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


Belge için üst veriyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


PDF çekirdek seçenekleri

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


PDF çekirdek seçenekleri

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


Sayfanın boyutunu alır.

Değer: Sayfanın boyutu.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


Sayfanın boyutunu ayarlar.

Değer: Sayfanın boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | sayfanın boyutu. |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


Orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değeri alır

Değer: Orijinal görüntü DPI çözünürlüğünün kullanılacağını gösteren belirteç

**Returns:**
boolean - orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değer
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


Orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değeri ayarlar 25.3'ten itibaren KALDIRILACAKTIR

Değer: Orijinal görüntü DPI çözünürlüğünün kullanılacağını gösteren belirteç

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| useOriginalImageSize | boolean | orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değer |

