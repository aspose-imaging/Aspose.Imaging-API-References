---
title: "PdfOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de PDF."
type: docs
weight: 36
url: /es/java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

Las opciones de PDF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Inicializa una nueva instancia de la clase [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | Obtiene un valor que indica usar la resolución DPI original de la imagen |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | Establece un valor que indica usar la resolución DPI original de la imagen |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | Obtiene o establece los metadatos del documento. |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | Obtiene o establece los metadatos del documento. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | Las opciones principales del PDF |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | Las opciones principales del PDF |
| [getPageSize()](#getPageSize--) | Obtiene el tamaño de la página. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Establece el tamaño de la página. |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | Obtiene un valor que indica usar la resolución DPI original de la imagen |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | Establece un valor que indica usar la resolución DPI original de la imagen SERÁ ELIMINADO DESDE 25.3 |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exporta solo las dos primeras páginas a las páginas correspondientes del documento PDF de salida.
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


Inicializa una nueva instancia de la clase [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions).

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


Obtiene un valor que indica usar la resolución DPI original de la imagen

Valor: Indicador para usar la resolución DPI original de la imagen

**Returns:**
boolean - un valor que indica usar la resolución DPI original de la imagen
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


Establece un valor que indica usar la resolución DPI original de la imagen

Valor: Indicador para usar la resolución DPI original de la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica usar la resolución DPI original de la imagen |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


Obtiene o establece los metadatos del documento.

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


Obtiene o establece los metadatos del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


Las opciones principales del PDF

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


Las opciones principales del PDF

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


Obtiene el tamaño de la página.

Valor: El tamaño de la página.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


Establece el tamaño de la página.

Valor: El tamaño de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | el tamaño de la página. |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


Obtiene un valor que indica usar la resolución DPI original de la imagen

Valor: Indicador para usar la resolución DPI original de la imagen

**Returns:**
boolean - un valor que indica usar la resolución DPI original de la imagen
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


Establece un valor que indica usar la resolución DPI original de la imagen SERÁ ELIMINADO DESDE 25.3

Valor: Indicador para usar la resolución DPI original de la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| useOriginalImageSize | boolean | un valor que indica usar la resolución DPI original de la imagen |

