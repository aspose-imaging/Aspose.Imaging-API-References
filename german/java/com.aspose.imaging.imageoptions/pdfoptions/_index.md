---
title: "PdfOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die PDF-Optionen."
type: docs
weight: 36
url: /de/java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

Die PDF-Optionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initialisiert eine neue Instanz der [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | Liefert einen Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden. |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | Setzt einen Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden. |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | Liefert oder setzt Metadaten für das Dokument. |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | Liefert oder setzt Metadaten für das Dokument. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | Die PDF-Kernoptionen |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | Die PDF-Kernoptionen |
| [getPageSize()](#getPageSize--) | Liefert die Größe der Seite. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Setzt die Größe der Seite. |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | Liefert einen Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden. |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | Setzt einen Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden. WIRD AB 25.3 ENTFERNT |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportiere nur die ersten beiden Seiten zu den entsprechenden Seiten des ausgegebenen PDF-Dokuments.
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


Initialisiert eine neue Instanz der [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions)-Klasse.

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


Liefert einen Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden.

Wert: Indikator, die ursprüngliche Bild-DPI-Auflösung zu verwenden

**Returns:**
boolean - ein Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


Setzt einen Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden.

Wert: Indikator, die ursprüngliche Bild-DPI-Auflösung zu verwenden

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


Liefert oder setzt Metadaten für das Dokument.

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


Liefert oder setzt Metadaten für das Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


Die PDF-Kernoptionen

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


Die PDF-Kernoptionen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


Liefert die Größe der Seite.

Wert: Die Größe der Seite.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


Setzt die Größe der Seite.

Wert: Die Größe der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | die Größe der Seite. |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


Liefert einen Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden.

Wert: Indikator, die ursprüngliche Bild-DPI-Auflösung zu verwenden

**Returns:**
boolean - ein Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


Setzt einen Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden. WIRD AB 25.3 ENTFERNT

Wert: Indikator, die ursprüngliche Bild-DPI-Auflösung zu verwenden

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| useOriginalImageSize | boolean | ein Wert, der angibt, die ursprüngliche Bild-DPI-Auflösung zu verwenden |

