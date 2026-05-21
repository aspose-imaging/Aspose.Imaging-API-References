---
title: "PdfOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "PDF-alternativen."
type: docs
weight: 36
url: /sv/java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

PDF-alternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initierar en ny instans av klassen [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | Hämtar ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | Ställer in ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | Hämtar eller anger metadata för dokumentet. |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | Hämtar eller anger metadata för dokumentet. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | PDF:s kärnalternativ |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | PDF:s kärnalternativ |
| [getPageSize()](#getPageSize--) | Hämtar sidans storlek. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Ställer in sidans storlek. |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | Hämtar ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | Ställer in ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas. KOMMER ATT TAS BORT FRÅN OCH MED VERSION 25.3 |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna till motsvarande sidor i den resulterande PDF-dokumentet.
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


Initierar en ny instans av klassen [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions).

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


Hämtar ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas

Värde: Indikator för att använda den ursprungliga bildens DPI-upplösning

**Returns:**
boolean - ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


Ställer in ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas

Värde: Indikator för att använda den ursprungliga bildens DPI-upplösning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


Hämtar eller anger metadata för dokumentet.

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


Hämtar eller anger metadata för dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


PDF:s kärnalternativ

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


PDF:s kärnalternativ

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


Hämtar sidans storlek.

Värde: Sidans storlek.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


Ställer in sidans storlek.

Värde: Sidans storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | sidans storlek. |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


Hämtar ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas

Värde: Indikator för att använda den ursprungliga bildens DPI-upplösning

**Returns:**
boolean - ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


Ställer in ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas. KOMMER ATT TAS BORT FRÅN OCH MED VERSION 25.3

Värde: Indikator för att använda den ursprungliga bildens DPI-upplösning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| useOriginalImageSize | boolean | ett värde som indikerar att den ursprungliga bildens DPI-upplösning ska användas |

