---
title: "PngOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Crea immagini raster Portable Network Graphics PNG di alta qualità senza sforzo con la nostra API, offrendo opzioni personalizzabili per i livelli di compressione, i bit per pixel, le profondità e i bit alfa."
type: docs
weight: 38
url: /it/java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

Crea immagini raster Portable Network Graphics (PNG) di alta qualità senza sforzo con la nostra API, offrendo opzioni personalizzabili per i livelli di compressione, i bit per pixel, le profondità e i bit alfa. Elabora senza problemi i contenitori di metadati XMP, garantendo una gestione completa dei metadati dell'immagine, e ti consente di personalizzare le immagini PNG secondo le tue specifiche esatte con facilità.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PngOptions()](#PngOptions--) | Inizializza una nuova istanza della classe `PngOptions`. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | Inizializza una nuova istanza della classe `PngOptions`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Il livello di compressione predefinito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorType()](#getColorType--) | Restituisce il tipo di colore. |
| [setColorType(int value)](#setColorType-int-) | Imposta il tipo di colore. |
| [getProgressive()](#getProgressive--) | Ottiene un valore che indica se un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è progressivo. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Imposta un valore che indica se un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è progressivo. |
| [getFilterType()](#getFilterType--) | Ottiene il tipo di filtro utilizzato durante il processo di salvataggio del file png. |
| [setFilterType(int value)](#setFilterType-int-) | Imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png. |
| [getCompressionLevel()](#getCompressionLevel--) | Ottiene il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Imposta il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getPngCompressionLevel()](#getPngCompressionLevel--) | Ottiene il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setPngCompressionLevel(int value)](#setPngCompressionLevel-int-) | Imposta il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getBitDepth()](#getBitDepth--) | Ottiene i valori di profondità di bit nell'intervallo 1, 2, 4, 8, 16. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Imposta i valori di profondità di bit nell'intervallo 1, 2, 4, 8, 16. |

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


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. In realtà, verrà rasterizzata solo una pagina perché PNG non è un formato multi-pagina.
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

### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Inizializza una nuova istanza della classe `PngOptions`.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Inizializza una nuova istanza della classe `PngOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Le opzioni PNG. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Il livello di compressione predefinito.

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Restituisce il tipo di colore.

Valore: Il tipo del colore.

**Returns:**
int - il tipo di colore.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Imposta il tipo di colore.

Valore: Il tipo del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il tipo di colore. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Carica immagine png        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Usa tipo di colore indicizzato
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Usa compressione massima
    options.setCompressionLevel(9);
    // Ottieni la palette di colori a 8 bit più vicina che copra il maggior numero possibile di pixel, in modo che un'immagine paletteizzata
    // sia quasi indistinguibile visivamente da una non paletteizzata.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// La dimensione del file di output dovrebbe essere notevolmente ridotta
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
// Puoi anche caricare un'immagine di qualsiasi formato supportato da un file o da uno stream.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Riempi l'immagine con il gradiente blu-trasparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Usa il caricamento progressivo.
    saveOptions.setProgressive(true);

    // Imposta la risoluzione orizzontale e verticale a 96 pixel per pollice.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Ogni pixel è una tripla (rosso, verde, blu) seguita da alfa.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Imposta il livello massimo di compressione.
    saveOptions.setCompressionLevel(9);

    // Questa è la compressione migliore, ma il tempo di esecuzione più lento.
    // Il filtraggio adattivo significa che il processo di salvataggio sceglierà il filtro più adatto per ogni riga di dati.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Il numero di bit per canale.
    saveOptions.setBitDepth((byte) 8);

    // Salva su un file.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


Ottiene un valore che indica se un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è progressivo.

Valore: `` se progressivo; altrimenti, ``.

**Returns:**
boolean - un valore che indica se un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è progressivo.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


Imposta un valore che indica se un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è progressivo.

Valore: `` se progressivo; altrimenti, ``.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | un valore che indica se un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è progressivo. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Carica immagine png        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Usa tipo di colore indicizzato
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Usa compressione massima
    options.setCompressionLevel(9);
    // Ottieni la palette di colori a 8 bit più vicina che copra il maggior numero possibile di pixel, in modo che un'immagine paletteizzata
    // sia quasi indistinguibile visivamente da una non paletteizzata.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// La dimensione del file di output dovrebbe essere notevolmente ridotta
```


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// Il numero di bit per canale colore
createOptions.setBitDepth((byte) 8);

// Ogni pixel è una tripla (rosso, verde, blu) seguita dal componente alfa.
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// Il livello massimo di compressione.
createOptions.setCompressionLevel(9);

// L'uso dei filtri consente di comprimere le immagini tonali continue in modo più efficace.
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// Usa il caricamento progressivo
createOptions.setProgressive(true);

// Crea un'immagine PNG con parametri personalizzati.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Riempire l'immagine con una sfumatura semitrasparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Salva su un file.
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


Ottiene il tipo di filtro utilizzato durante il processo di salvataggio del file png.

**Returns:**
int - il tipo di filtro utilizzato durante il processo di salvataggio del file png.
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


Imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il tipo di filtro utilizzato durante il processo di salvataggio del file png. |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// Classe di supporto
class Utils {
    public String getPngFilterTypeString(int filterType) {
        switch (filterType) {
            case com.aspose.imaging.fileformats.png.PngFilterType.None:
                return "None";

            case com.aspose.imaging.fileformats.png.PngFilterType.Up:
                return "Up";

            case com.aspose.imaging.fileformats.png.PngFilterType.Sub:
                return "Sub";

            case com.aspose.imaging.fileformats.png.PngFilterType.Paeth:
                return "Paeth";

            case com.aspose.imaging.fileformats.png.PngFilterType.Avg:
                return "Avg";

            case com.aspose.imaging.fileformats.png.PngFilterType.Adaptive:
                return "Adaptive";

            default:
                throw new IllegalArgumentException("filterType");
        }
    }
}

// Ecco l'esempio principale
Utils utils = new Utils();

int[] filterTypes = new int[]
        {
                com.aspose.imaging.fileformats.png.PngFilterType.None,
                com.aspose.imaging.fileformats.png.PngFilterType.Up,
                com.aspose.imaging.fileformats.png.PngFilterType.Sub,
                com.aspose.imaging.fileformats.png.PngFilterType.Paeth,
                com.aspose.imaging.fileformats.png.PngFilterType.Avg,
                com.aspose.imaging.fileformats.png.PngFilterType.Adaptive,
        };

for (int filterType : filterTypes) {
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
    try {
        // Imposta un tipo di filtro
        options.setFilterType(filterType);

        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            image.save(stream, options);
            System.out.printf("The filter type is %s, the output image size is %s bytes.", utils.getPngFilterTypeString(filterType), stream.size());
        } finally {
            stream.close();
        }
    } finally {
        image.dispose();
    }
}

//L'output potrebbe apparire così:
//Il tipo di filtro è None, la dimensione dell'immagine di output è 116845 byte.
//Il tipo di filtro è Up, la dimensione dell'immagine di output è 86360 byte.
//Il tipo di filtro è Sub, la dimensione dell'immagine di output è 94907 byte.
//Il tipo di filtro è Paeth, la dimensione dell'immagine di output è 86403 byte.
//Il tipo di filtro è Avg, la dimensione dell'immagine di output è 89956 byte.
//Il tipo di filtro è Adaptive, la dimensione dell'immagine di output è 97248 byte.
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Ottiene il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int - il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Imposta il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Carica immagine png        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Usa tipo di colore indicizzato
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Usa compressione massima
    options.setCompressionLevel(9);
    // Ottieni la palette di colori a 8 bit più vicina che copra il maggior numero possibile di pixel, in modo che un'immagine paletteizzata
    // sia quasi indistinguibile visivamente da una non paletteizzata.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// La dimensione del file di output dovrebbe essere notevolmente ridotta
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
// Puoi anche caricare un'immagine di qualsiasi formato supportato da un file o da uno stream.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Riempi l'immagine con il gradiente blu-trasparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Usa il caricamento progressivo.
    saveOptions.setProgressive(true);

    // Imposta la risoluzione orizzontale e verticale a 96 pixel per pollice.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Ogni pixel è una tripla (rosso, verde, blu) seguita da alfa.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Imposta il livello massimo di compressione.
    saveOptions.setCompressionLevel(9);

    // Questa è la compressione migliore, ma il tempo di esecuzione più lento.
    // Il filtraggio adattivo significa che il processo di salvataggio sceglierà il filtro più adatto per ogni riga di dati.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Il numero di bit per canale.
    saveOptions.setBitDepth((byte) 8);

    // Salva su un file.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getPngCompressionLevel() {#getPngCompressionLevel--}
```
public final int getPngCompressionLevel()
```


Ottiene il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int - il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setPngCompressionLevel(int value) {#setPngCompressionLevel-int-}
```
public final void setPngCompressionLevel(int value)
```


Imposta il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | il livello di compressione del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Ottiene i valori di profondità di bit nell'intervallo 1, 2, 4, 8, 16.

Considera i seguenti limiti:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte - i valori di profondità di bit nell'intervallo 1, 2, 4, 8, 16.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


Imposta i valori di profondità di bit nell'intervallo 1, 2, 4, 8, 16.

Considera i seguenti limiti:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | i valori di profondità di bit nell'intervallo 1, 2, 4, 8, 16. |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
// Puoi anche caricare un'immagine di qualsiasi formato supportato da un file o da uno stream.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Riempi l'immagine con il gradiente blu-trasparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Usa il caricamento progressivo.
    saveOptions.setProgressive(true);

    // Imposta la risoluzione orizzontale e verticale a 96 pixel per pollice.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Ogni pixel è una tripla (rosso, verde, blu) seguita da alfa.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Imposta il livello massimo di compressione.
    saveOptions.setCompressionLevel(9);

    // Questa è la compressione migliore, ma il tempo di esecuzione più lento.
    // Il filtraggio adattivo significa che il processo di salvataggio sceglierà il filtro più adatto per ogni riga di dati.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Il numero di bit per canale.
    saveOptions.setBitDepth((byte) 8);

    // Salva su un file.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

