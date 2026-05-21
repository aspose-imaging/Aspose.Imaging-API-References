---
title: "PdfOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options PDF."
type: docs
weight: 36
url: /fr/java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

Les options PDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initialise une nouvelle instance de la classe [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | Obtient une valeur indiquant d'utiliser la résolution DPI d'origine de l'image |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | Définit une valeur indiquant d'utiliser la résolution DPI d'origine de l'image |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | Obtient ou définit les métadonnées du document. |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | Obtient ou définit les métadonnées du document. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | Les options de base du PDF |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | Les options de base du PDF |
| [getPageSize()](#getPageSize--) | Obtient la taille de la page. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Définit la taille de la page. |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | Obtient une valeur indiquant d'utiliser la résolution DPI d'origine de l'image |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | Définit une valeur indiquant d'utiliser la résolution DPI d'origine de l'image SERA SUPPRIMÉE DEPUIS la version 25.3 |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportez uniquement les deux premières pages vers les pages correspondantes du document PDF de sortie.
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


Initialise une nouvelle instance de la classe [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions).

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


Obtient une valeur indiquant d'utiliser la résolution DPI d'origine de l'image

Valeur : Indicateur d'utilisation de la résolution DPI d'origine de l'image

**Returns:**
booléen - une valeur indiquant d'utiliser la résolution DPI d'origine de l'image
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


Définit une valeur indiquant d'utiliser la résolution DPI d'origine de l'image

Valeur : Indicateur d'utilisation de la résolution DPI d'origine de l'image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant d'utiliser la résolution DPI d'origine de l'image |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


Obtient ou définit les métadonnées du document.

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


Obtient ou définit les métadonnées du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


Les options de base du PDF

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


Les options de base du PDF

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


Obtient la taille de la page.

Valeur : La taille de la page.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


Définit la taille de la page.

Valeur : La taille de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | la taille de la page. |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


Obtient une valeur indiquant d'utiliser la résolution DPI d'origine de l'image

Valeur : Indicateur d'utilisation de la résolution DPI d'origine de l'image

**Returns:**
booléen - une valeur indiquant d'utiliser la résolution DPI d'origine de l'image
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


Définit une valeur indiquant d'utiliser la résolution DPI d'origine de l'image SERA SUPPRIMÉE DEPUIS la version 25.3

Valeur : Indicateur d'utilisation de la résolution DPI d'origine de l'image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| useOriginalImageSize | boolean | une valeur indiquant d'utiliser la résolution DPI d'origine de l'image |

