---
title: "SvgOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Crea file immagine SVG (Scalar Vector Graphics) con la nostra API utilizzando opzioni versatili per i tipi di colore e i livelli di compressione."
type: docs
weight: 45
url: /it/java/com.aspose.imaging.imageoptions/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public class SvgOptions extends ImageOptionsBase implements ICompressOptions
```

Crea file immagine Scalar Vector Graphics (SVG) con la nostra API, utilizzando opzioni versatili per i tipi di colore e i livelli di compressione. Personalizza senza sforzo le tue immagini SVG con precisione, garantendo qualità ottimale e compatibilità per le tue esigenze di progettazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SvgOptions()](#SvgOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorType()](#getColorType--) | Ottiene o imposta il tipo di colore per l'immagine SVG. |
| [setColorType(int value)](#setColorType-int-) | Ottiene o imposta il tipo di colore per l'immagine SVG. |
| [getTextAsShapes()](#getTextAsShapes--) | Restituisce un valore che indica se il testo deve essere renderizzato come forme. |
| [setTextAsShapes(boolean value)](#setTextAsShapes-boolean-) | Imposta un valore che indica se il testo deve essere renderizzato come forme. |
| [getCallback()](#getCallback--) | Restituisce la strategia di memorizzazione per le risorse incorporate di [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) come font e raster nidificati. |
| [setCallback(ISvgResourceKeeperCallback value)](#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-) | Imposta la strategia di memorizzazione per le risorse incorporate di [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) come font e raster nidificati. |
| [getCompress()](#getCompress--) | Ottiene un valore che indica se l'immagine di output deve essere compressa. |
| [setCompress(boolean value)](#setCompress-boolean-) | Imposta un valore che indica se l'immagine di output deve essere compressa. |

## Example: The following example shows how to convert a multipage vector image to SVG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.svg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.SvgOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. In realtà, verrà convertita una sola pagina perché SVG non è un formato multipagina.
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


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgOptions() {#SvgOptions--}
```
public SvgOptions()
```


### getColorType() {#getColorType--}
```
public int getColorType()
```


Ottiene o imposta il tipo di colore per l'immagine SVG.

**Returns:**
int - Il tipo di colore dell'immagine SVG.
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Ottiene o imposta il tipo di colore per l'immagine SVG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il tipo di colore dell'immagine SVG. |

### getTextAsShapes() {#getTextAsShapes--}
```
public boolean getTextAsShapes()
```


Restituisce un valore che indica se il testo deve essere renderizzato come forme.

Valore: `true` se tutto il testo viene trasformato in forme SVG durante la conversione; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se il testo deve essere renderizzato come forme.
### setTextAsShapes(boolean value) {#setTextAsShapes-boolean-}
```
public void setTextAsShapes(boolean value)
```


Imposta un valore che indica se il testo deve essere renderizzato come forme.

Valore: `true` se tutto il testo viene trasformato in forme SVG durante la conversione; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se il testo deve essere renderizzato come forme. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Il testo verrà convertito in forme.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Il colore di sfondo della superficie di disegno.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La dimensione della pagina.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Se esiste un emf incorporato, renderizza emf; altrimenti renderizza wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Il testo verrà convertito in forme.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Il colore di sfondo della superficie di disegno.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La dimensione della pagina.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Se esiste un emf incorporato, renderizza emf; altrimenti renderizza wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Imposta il margine orizzontale
    rasterizationOptions.setBorderX(50);

    // Imposta il margine verticale
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getCallback() {#getCallback--}
```
public ISvgResourceKeeperCallback getCallback()
```


Restituisce la strategia di memorizzazione per le risorse incorporate di [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) come font e raster nidificati.

**Returns:**
[ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) - the storing strategy for embedded resources of [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) such as fonts, nested rasters.
### setCallback(ISvgResourceKeeperCallback value) {#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-}
```
public void setCallback(ISvgResourceKeeperCallback value)
```


Imposta la strategia di memorizzazione per le risorse incorporate di [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) come font e raster nidificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) | la strategia di memorizzazione per le risorse incorporate di [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) come font e raster nidificati. |

### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Ottiene un valore che indica se l'immagine di output deve essere compressa.

**Returns:**
boolean - un valore che indica se l'immagine di output deve essere compressa.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Imposta un valore che indica se l'immagine di output deve essere compressa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se l'immagine di output deve essere compressa. |


**Example: The following example shows how to convert a svg images to svgz format**

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

