---
title: "BmpOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per le opzioni di creazione del formato immagine raster BMP e DIB fornisce agli sviluppatori un set di strumenti versatile per generare immagini Bitmap BMP e Device Independent Bitmap DIB personalizzate."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

L'API per le opzioni di creazione del formato immagine raster BMP e DIB fornisce agli sviluppatori un set di strumenti versatile per generare immagini Bitmap (BMP) e Device Independent Bitmap (DIB) personalizzate. Con questa API, è possibile definire con precisione le caratteristiche dell'immagine, come i bit per pixel, il livello di compressione e il tipo di compressione, adattando l'output per soddisfare requisiti specifici. Questa API ricca di funzionalità consente agli sviluppatori di creare immagini raster di alta qualità e personalizzate con facilità e flessibilità per diverse applicazioni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | Inizializza una nuova istanza della classe `BmpOptions`. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | Inizializza una nuova istanza della classe `BmpOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ottiene o imposta il conteggio dei bit per pixel dell'immagine. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Ottiene o imposta il conteggio dei bit per pixel dell'immagine. |
| [getCompression()](#getCompression--) | Ottiene il tipo di compressione. |
| [setCompression(long value)](#setCompression-long-) | Imposta il tipo di compressione. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Questo esempio dimostra l'uso di diverse classi dal namespace SaveOptions per scopi di esportazione. Un'immagine di tipo Gif viene caricata in un'istanza di Image e poi esportata in diversi formati.
``` java
String dir = "c:\\temp\\";

//Carica un'immagine esistente (di tipo Gif) in un'istanza della classe Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Esporta nel formato file BMP utilizzando le opzioni predefinite
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Esporta nel formato file JPEG utilizzando le opzioni predefinite
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Esporta nel formato file PNG utilizzando le opzioni predefinite
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Esporta nel formato file TIFF utilizzando le opzioni predefinite
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to BMP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.bmp");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.BmpOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. In realtà, verrà rasterizzata solo una pagina perché BMP non è un formato multi-pagina.
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

### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


Inizializza una nuova istanza della classe `BmpOptions`.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


Inizializza una nuova istanza della classe `BmpOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | Le opzioni BMP. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ottiene o imposta il conteggio dei bit per pixel dell'immagine.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Ottiene o imposta il conteggio dei bit per pixel dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il conteggio dei bit per pixel dell'immagine. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Crea BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Usa 8 bit per pixel per ridurre le dimensioni dell'immagine di output.
    saveOptions.setBitsPerPixel(8);

    // Imposta la palette di colori a 8 bit più vicina che copre il numero massimo di pixel dell'immagine, così da ottenere un'immagine palettizzata
    // sia quasi indistinguibile visivamente da una non paletteizzata.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Salva senza compressione.
    // Puoi anche usare la compressione RLE-8 per ridurre le dimensioni dell'immagine di output.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Imposta la risoluzione orizzontale e verticale a 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Ottiene il tipo di compressione. Il tipo di compressione predefinito è [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\\#Bitfields), che consente di salvare un [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con trasparenza.

Valore: Il tipo di compressione.

**Returns:**
long - il tipo di compressione.

**Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.**

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


Imposta il tipo di compressione. Il tipo di compressione predefinito è [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), che consente di salvare un [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con trasparenza.

Valore: Il tipo di compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | il tipo di compressione. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Crea BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Usa 8 bit per pixel per ridurre le dimensioni dell'immagine di output.
    saveOptions.setBitsPerPixel(8);

    // Imposta la palette di colori a 8 bit più vicina che copre il numero massimo di pixel dell'immagine, così da ottenere un'immagine palettizzata
    // sia quasi indistinguibile visivamente da una non paletteizzata.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Salva senza compressione.
    // Puoi anche usare la compressione RLE-8 per ridurre le dimensioni dell'immagine di output.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Imposta la risoluzione orizzontale e verticale a 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```


**Example: Compress BMP image using DXT1 compression algorithm.**

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


**Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.**

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Carica un'immagine PNG da un file.
try (Image pngImage = Image.load(sourcePath))
{
    // L'immagine BMP viene salvata con supporto della trasparenza per impostazione predefinita.
    // Se desideri specificare esplicitamente tale modalità, la proprietà Compression di BmpOptions deve essere impostata su BitmapCompression.Bitfields.
    // Il metodo di compressione BitmapCompression.Bitfields è il metodo di compressione predefinito in BmpOptions.
    // Quindi lo stesso risultato dell'esportazione di un'immagine Bmp con trasparenza può essere ottenuto in uno dei seguenti modi.
    // Con opzioni predefinite implicite:
    pngImage.save(outputPathPng);
    // Con opzioni predefinite esplicite:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Specificando il metodo di compressione BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Carica un'immagine PNG da un file.
try (Image pngImage = Image.load(sourcePath))
{
    // L'immagine BMP viene salvata con supporto della trasparenza per impostazione predefinita, ciò è ottenuto utilizzando il metodo di compressione BitmapCompression.Bitfields.
    // Per salvare un'immagine BMP con il metodo di compressione Rgb, è necessario specificare BmpOptions con la proprietà Compression impostata su BitmapCompression.Rgb.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

