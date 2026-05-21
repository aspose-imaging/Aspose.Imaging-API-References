---
title: "JpegOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Crea immagini JPEG di alta qualità senza sforzo con la nostra API che offre livelli di compressione regolabili per ottimizzare le dimensioni di archiviazione senza compromettere la qualità dell'immagine."
type: docs
weight: 26
url: /it/java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

Crea immagini JPEG di alta qualità senza sforzo con la nostra API, offrendo livelli di compressione regolabili per ottimizzare le dimensioni di archiviazione senza compromettere la qualità dell'immagine. Approfitta del supporto per vari tipi di compressione, codifica quasi senza perdita, profili colore RGB e CMYK, così come dati immagine EXIF, JFIF e contenitori XMP, garantendo opzioni versatili e personalizzabili per le tue esigenze di creazione di immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Inizializza una nuova istanza della classe `JpegOptions`. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | Inizializza una nuova istanza della classe `JpegOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Ottiene il limite predefinito di allocazione della memoria. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Imposta il limite predefinito di allocazione della memoria. |
| [getJfif()](#getJfif--) | Ottiene il jfif. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Imposta il jfif. |
| [getComment()](#getComment--) | Ottiene il commento del file jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | Imposta il commento del file jpeg. |
| [getExifData()](#getExifData--) | Ottiene il contenitore dei dati Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Imposta i dati Exif. |
| [getJpegExifData()](#getJpegExifData--) | Ottieni il contenitore dei dati Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Ottieni o imposta il contenitore dei dati exif. |
| [getCompressionType()](#getCompressionType--) | Ottiene il tipo di compressione. |
| [setCompressionType(int value)](#setCompressionType-int-) | Imposta il tipo di compressione. |
| [getColorType()](#getColorType--) | Ottiene il tipo di colore per l'immagine jpeg. |
| [setColorType(int value)](#setColorType-int-) | Imposta il tipo di colore per l'immagine jpeg. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Ottiene i bit per canale per l'immagine jpeg senza perdita. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Imposta i bit per canale per l'immagine jpeg senza perdita. |
| [getQuality()](#getQuality--) | Ottiene la qualità dell'immagine. |
| [setQuality(int value)](#setQuality-int-) | Imposta la qualità dell'immagine. |
| [getScaledQuality()](#getScaledQuality--) | La qualità scalata. |
| [getRdOptSettings()](#getRdOptSettings--) | Ottiene le impostazioni dell'ottimizzatore RD. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | Imposta le impostazioni dell'ottimizzatore RD. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Il profilo colore RGB di destinazione per le immagini jpeg CMYK. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Il profilo colore RGB di destinazione per le immagini jpeg CMYK. |
| [getCmykColorProfile()](#getCmykColorProfile--) | Il profilo colore CMYK di destinazione per le immagini jpeg CMYK. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Il profilo colore CMYK di destinazione per le immagini jpeg CMYK. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Ottiene il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS). |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Imposta il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Ottiene la modalità di interlacciamento JPEG-LS. |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Imposta la modalità di interlacciamento JPEG-LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Ottiene i parametri predefiniti JPEG-LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | Imposta i parametri predefiniti JPEG-LS. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Ottiene i campionamenti orizzontali per ogni componente. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Imposta i campionamenti orizzontali per ogni componente. |
| [getVerticalSampling()](#getVerticalSampling--) | Ottiene i campionamenti verticali per ogni componente. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Imposta i campionamenti verticali per ogni componente. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Ottiene la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Ottiene un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Imposta un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa. |
| [getResolutionUnit()](#getResolutionUnit--) | Ottiene l'unità di risoluzione. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Imposta l'unità di risoluzione. |

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


## Example: The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.jpeg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.JpegOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. In realtà, verrà rasterizzata solo una pagina perché JPEG non è un formato multi-pagina.
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

### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Inizializza una nuova istanza della classe `JpegOptions`.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Inizializza una nuova istanza della classe `JpegOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Le opzioni JPEG. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Ottiene il limite predefinito di allocazione della memoria.

**Returns:**
int - Il limite predefinito di allocazione della memoria.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Imposta il limite predefinito di allocazione della memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il limite predefinito di allocazione della memoria. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Ottiene il jfif.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Imposta il jfif.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getComment() {#getComment--}
```
public String getComment()
```


Ottiene il commento del file jpeg.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Imposta il commento del file jpeg.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Ottiene il contenitore dei dati Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


Imposta i dati Exif.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Dati Exif. |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


Ottieni il contenitore dei dati Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Ottieni o imposta il contenitore dei dati exif.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Ottiene il tipo di compressione.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Imposta il tipo di compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine JPEG di 100x100 px.
// Utilizza opzioni aggiuntive per specificare i parametri desiderati dell'immagine.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Il numero di bit per canale è 8, 8, 8 per i componenti Y, Cr, Cb rispettivamente.
createOptions.setBitsPerChannel((byte) 8);

// Imposta il tipo di compressione progressiva.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
createOptions.setQuality(100);

// Imposta la risoluzione orizzontale/verticale a 96 punti per pollice.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Questa è un'opzione standard per le immagini JPEG.
// Due componenti di crominanza (Cb e Cr) possono essere ridotti in larghezza di banda, sottocampionati, compressi.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Riempire l'immagine con un gradiente in scala di grigi
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Salva su un file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


Ottiene il tipo di colore per l'immagine jpeg.

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine JPEG di 100x100 px.
// Utilizza opzioni aggiuntive per specificare i parametri desiderati dell'immagine.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Il numero di bit per canale è 8, 8, 8 per i componenti Y, Cr, Cb rispettivamente.
createOptions.setBitsPerChannel((byte) 8);

// Imposta il tipo di compressione progressiva.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
createOptions.setQuality(100);

// Imposta la risoluzione orizzontale/verticale a 96 punti per pollice.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Questa è un'opzione standard per le immagini JPEG.
// Due componenti di crominanza (Cb e Cr) possono essere ridotti in larghezza di banda, sottocampionati, compressi.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Riempire l'immagine con un gradiente in scala di grigi
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Salva su un file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Imposta il tipo di colore per l'immagine jpeg.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine BMP da un file.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Esegui qualche elaborazione dell'immagine.

    // Utilizza opzioni aggiuntive per specificare i parametri desiderati dell'immagine.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Il numero di bit per canale è 8.
    // Quando viene utilizzata una palette, l'indice di colore è memorizzato nei dati dell'immagine invece del colore stesso.
    saveOptions.setBitsPerChannel((byte) 8);

    // Imposta il tipo di compressione progressiva.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
    saveOptions.setQuality(100);

    // Imposta la risoluzione orizzontale/verticale a 96 punti per pollice.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Se l'immagine di origine è a colori, verrà convertita in scala di grigi.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Utilizza una palette per ridurre la dimensione dell'output.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Ottiene i bit per canale per l'immagine JPEG senza perdita. Ora supportiamo da 2 a 8 bit per canale.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Imposta i bit per canale per l'immagine JPEG senza perdita. Ora supportiamo da 2 a 8 bit per canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine JPEG di 100x100 px.
// Utilizza opzioni aggiuntive per specificare i parametri desiderati dell'immagine.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Il numero di bit per canale è 8, 8, 8 per i componenti Y, Cr, Cb rispettivamente.
createOptions.setBitsPerChannel((byte) 8);

// Imposta il tipo di compressione progressiva.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
createOptions.setQuality(100);

// Imposta la risoluzione orizzontale/verticale a 96 punti per pollice.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Questa è un'opzione standard per le immagini JPEG.
// Due componenti di crominanza (Cb e Cr) possono essere ridotti in larghezza di banda, sottocampionati, compressi.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Riempire l'immagine con un gradiente in scala di grigi
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Salva su un file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


Ottiene la qualità dell'immagine.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Imposta la qualità dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine JPEG di 100x100 px.
// Utilizza opzioni aggiuntive per specificare i parametri desiderati dell'immagine.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Il numero di bit per canale è 8, 8, 8 per i componenti Y, Cr, Cb rispettivamente.
createOptions.setBitsPerChannel((byte) 8);

// Imposta il tipo di compressione progressiva.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
createOptions.setQuality(100);

// Imposta la risoluzione orizzontale/verticale a 96 punti per pollice.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Questa è un'opzione standard per le immagini JPEG.
// Due componenti di crominanza (Cb e Cr) possono essere ridotti in larghezza di banda, sottocampionati, compressi.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Riempire l'immagine con un gradiente in scala di grigi
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Salva su un file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


La qualità scalata.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Ottiene le impostazioni dell'ottimizzatore RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Imposta le impostazioni dell'ottimizzatore RD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | Le impostazioni dell'ottimizzatore RD. |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Il profilo colore RGB di destinazione per le immagini JPEG CMYK. Da utilizzare per salvare le immagini. Deve essere associato a CMYKColorProfile per una corretta conversione dei colori.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Il profilo colore RGB di destinazione per le immagini JPEG CMYK. Da utilizzare per salvare le immagini. Deve essere associato a CMYKColorProfile per una corretta conversione dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
L'esempio seguente carica un PNG e lo salva in JPEG CMYK utilizzando un profilo ICC personalizzato. Successivamente carica il JPEG CMYK e lo salva nuovamente in PNG. La conversione del colore da RGB a CMYK e da CMYK a RGB viene eseguita utilizzando profili ICC personalizzati.
``` java
String dir = "c:\\temp\\";

// Carica PNG e salvalo in JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Usa profili ICC personalizzati
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Carica JPEG CMYK e salvalo in PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Usa profili ICC personalizzati
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Il profilo colore CMYK di destinazione per le immagini JPEG CMYK. Da utilizzare per salvare le immagini. Deve essere associato a RGBColorProfile per una corretta conversione dei colori.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Il profilo colore CMYK di destinazione per le immagini JPEG CMYK. Da utilizzare per salvare le immagini. Deve essere associato a RGBColorProfile per una corretta conversione dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
L'esempio seguente carica un PNG e lo salva in JPEG CMYK utilizzando un profilo ICC personalizzato. Successivamente carica il JPEG CMYK e lo salva nuovamente in PNG. La conversione del colore da RGB a CMYK e da CMYK a RGB viene eseguita utilizzando profili ICC personalizzati.
``` java
String dir = "c:\\temp\\";

// Carica PNG e salvalo in JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Usa profili ICC personalizzati
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Carica JPEG CMYK e salvalo in PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Usa profili ICC personalizzati
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Ottiene il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS).

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Imposta il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Ottiene la modalità di interlacciamento JPEG-LS.

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Imposta la modalità di interlacciamento JPEG-LS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Ottiene i parametri predefiniti JPEG-LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Imposta i parametri predefiniti JPEG-LS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Ottiene i campionamenti orizzontali per ogni componente.

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Imposta i campionamenti orizzontali per ogni componente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Ottiene i campionamenti verticali per ogni componente.

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Imposta i campionamenti verticali per ogni componente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Ottiene la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit. `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit. `P:JpegOptions.BitsPerChannel`

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Ottiene un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa.

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Imposta un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Ottiene l'unità di risoluzione.

**Returns:**
byte - l'unità di risoluzione.

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine JPEG di 100x100 px.
// Utilizza opzioni aggiuntive per specificare i parametri desiderati dell'immagine.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Il numero di bit per canale è 8, 8, 8 per i componenti Y, Cr, Cb rispettivamente.
createOptions.setBitsPerChannel((byte) 8);

// Imposta il tipo di compressione progressiva.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
createOptions.setQuality(100);

// Imposta la risoluzione orizzontale/verticale a 96 punti per pollice.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Questa è un'opzione standard per le immagini JPEG.
// Due componenti di crominanza (Cb e Cr) possono essere ridotti in larghezza di banda, sottocampionati, compressi.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Riempire l'immagine con un gradiente in scala di grigi
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Salva su un file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Imposta l'unità di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | l'unità di risoluzione. |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine BMP da un file.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Esegui qualche elaborazione dell'immagine.

    // Utilizza opzioni aggiuntive per specificare i parametri desiderati dell'immagine.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Il numero di bit per canale è 8.
    // Quando viene utilizzata una palette, l'indice di colore è memorizzato nei dati dell'immagine invece del colore stesso.
    saveOptions.setBitsPerChannel((byte) 8);

    // Imposta il tipo di compressione progressiva.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
    saveOptions.setQuality(100);

    // Imposta la risoluzione orizzontale/verticale a 96 punti per pollice.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Se l'immagine di origine è a colori, verrà convertita in scala di grigi.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Utilizza una palette per ridurre la dimensione dell'output.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

