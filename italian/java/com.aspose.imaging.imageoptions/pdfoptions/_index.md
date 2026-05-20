---
title: "PdfOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni PDF."
type: docs
weight: 36
url: /it/java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

Le opzioni PDF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Inizializza una nuova istanza della classe [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | Restituisce un valore che indica di utilizzare la risoluzione DPI originale dell'immagine |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | Imposta un valore che indica di utilizzare la risoluzione DPI originale dell'immagine |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | Ottiene o imposta i metadati per il documento. |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | Ottiene o imposta i metadati per il documento. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | Le opzioni principali del PDF |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | Le opzioni principali del PDF |
| [getPageSize()](#getPageSize--) | Restituisce la dimensione della pagina. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Imposta la dimensione della pagina. |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | Restituisce un valore che indica di utilizzare la risoluzione DPI originale dell'immagine |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | Imposta un valore che indica di utilizzare la risoluzione DPI originale dell'immagine SARÀ RIMOSSO DALLA VERSIONE 25.3 |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine nelle pagine corrispondenti del documento PDF di output.
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


Inizializza una nuova istanza della classe [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions).

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


Restituisce un valore che indica di utilizzare la risoluzione DPI originale dell'immagine

Valore: Indicatore per utilizzare la risoluzione DPI originale dell'immagine

**Returns:**
boolean - un valore che indica di utilizzare la risoluzione DPI originale dell'immagine
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


Imposta un valore che indica di utilizzare la risoluzione DPI originale dell'immagine

Valore: Indicatore per utilizzare la risoluzione DPI originale dell'immagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica di utilizzare la risoluzione DPI originale dell'immagine |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


Ottiene o imposta i metadati per il documento.

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


Ottiene o imposta i metadati per il documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


Le opzioni principali del PDF

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


Le opzioni principali del PDF

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


Restituisce la dimensione della pagina.

Valore: La dimensione della pagina.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


Imposta la dimensione della pagina.

Valore: La dimensione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | la dimensione della pagina. |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


Restituisce un valore che indica di utilizzare la risoluzione DPI originale dell'immagine

Valore: Indicatore per utilizzare la risoluzione DPI originale dell'immagine

**Returns:**
boolean - un valore che indica di utilizzare la risoluzione DPI originale dell'immagine
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


Imposta un valore che indica di utilizzare la risoluzione DPI originale dell'immagine SARÀ RIMOSSO DALLA VERSIONE 25.3

Valore: Indicatore per utilizzare la risoluzione DPI originale dell'immagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| useOriginalImageSize | boolean | un valore che indica di utilizzare la risoluzione DPI originale dell'immagine |

