---
title: "JpegImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Manipola in modo efficiente le immagini raster JPEG con la nostra API, offrendo supporto per vari profili colore come RGB e CMYK, risoluzione personalizzabile in bit per pixel e elaborazione di contenitori di metadati EXIF, JFIF e XMP."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

Manipola in modo efficiente le immagini raster JPEG con la nostra API, offrendo supporto per vari profili colore come RGB e CMYK, risoluzione personalizzabile in bit per pixel e elaborazione di contenitori di metadati EXIF, JFIF e XMP. Approfitta della rotazione automatica basata sui dati di orientamento e scegli tra diversi livelli di compressione, inclusi JPEG senza perdita, per ottenere un equilibrio ottimale tra qualità dell'immagine e dimensione del file per i tuoi progetti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | La classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) si avvia senza sforzo invocando il suo costruttore con il parametro path specificato. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | Inizializza un oggetto immagine JPEG con la classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) utilizzando un parametro stream. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | Inizializza una nuova istanza della classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con un parametro immagine raster. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | Crea una nuova istanza della classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con i parametri di larghezza e altezza specificati. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | Inizializza un nuovo oggetto [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con le opzioni JPEG fornite. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupera il formato dell'immagine senza sforzo con questa proprietà. |
| [getJpegOptions()](#getJpegOptions--) | Accedi facilmente alle opzioni JPEG utilizzate durante la creazione o il caricamento di questa istanza di [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage). |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera la profondità di colore dell'immagine senza sforzo con questa proprietà, fornendo informazioni sulla ricchezza della rappresentazione a colori o in scala di grigi. |
| [getComment()](#getComment--) | Gestisci i commenti dei file JPEG con questa proprietà, consentendoti di aggiungere o recuperare annotazioni descrittive associate all'immagine. |
| [setComment(String value)](#setComment-java.lang.String-) | Gestisci i commenti dei file JPEG con questa proprietà, consentendoti di aggiungere o recuperare annotazioni descrittive associate all'immagine. |
| [getJpegExifData()](#getJpegExifData--) | Ottiene l'istanza Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Gestisci i dati EXIF con questa proprietà, consentendoti di aggiungere o recuperare i metadati associati all'immagine. |
| [getExifData()](#getExifData--) | Ottiene i dati Exif; |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Imposta i dati Exif; |
| [getHeight()](#getHeight--) | Recupera senza sforzo l'altezza dell'immagine con questa proprietà. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Questa proprietà ti consente di accedere alla risoluzione orizzontale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Questa proprietà ti consente di accedere alla risoluzione orizzontale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice. |
| [getJfif()](#getJfif--) | Questa proprietà ti permette di accedere o modificare i dati JFIF (JPEG File Interchange Format) associati all'immagine JPEG. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Questa proprietà ti permette di accedere o modificare i dati JFIF (JPEG File Interchange Format) associati all'immagine JPEG. |
| [getRawDataFormat()](#getRawDataFormat--) | Questa proprietà recupera il formato dei dati grezzi dell'immagine, che indica come i dati dell'immagine sono strutturati e codificati. |
| [getVerticalResolution()](#getVerticalResolution--) | Questa proprietà gestisce la risoluzione verticale, espressa in pixel per pollice, per il [RasterImage](../../com.aspose.imaging/rasterimage) associato. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Questa proprietà gestisce la risoluzione verticale, espressa in pixel per pollice, per il [RasterImage](../../com.aspose.imaging/rasterimage) associato. |
| [getWidth()](#getWidth--) | Questa proprietà recupera la larghezza dell'immagine, espressa in pixel. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Il profilo colore RGB per le immagini JPEG CMYK e YCCK garantisce una conversione e una rappresentazione del colore accurate. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Il profilo colore RGB per le immagini JPEG CMYK e YCCK garantisce una conversione e una rappresentazione del colore accurate. |
| [getCmykColorProfile()](#getCmykColorProfile--) | Il profilo colore CMYK associato alle immagini JPEG CMYK e YCCK garantisce una conversione del colore precisa e una fedeltà elevata. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Il profilo colore CMYK associato alle immagini JPEG CMYK e YCCK garantisce una conversione del colore precisa e una fedeltà elevata. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | Il RGBColorProfile è essenziale per una conversione accurata del colore delle immagini JPEG CMYK e YCCK durante il processo di salvataggio. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Il RGBColorProfile è essenziale per una conversione accurata del colore delle immagini JPEG CMYK e YCCK durante il processo di salvataggio. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | Il profilo colore CMYK è fondamentale per una conversione accurata del colore delle immagini JPEG CMYK e YCCK durante il processo di salvataggio. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Il profilo colore CMYK è fondamentale per una conversione accurata del colore delle immagini JPEG CMYK e YCCK durante il processo di salvataggio. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | Recupera o modifica il flag che indica se il profilo colore incorporato è ignorato. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | Recupera o modifica il flag che indica se il profilo colore incorporato è ignorato. |
| [getOriginalOptions()](#getOriginalOptions--) | Ottiene le opzioni originali dell'immagine di questa istanza di [Image](../../com.aspose.imaging/image). |
| [removeMetadata()](#removeMetadata--) | Rimuove i metadati di questa istanza di immagine impostando i valori di `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) e `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) a `null`. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Stabilisci la risoluzione per il [RasterImage](../../com.aspose.imaging/rasterimage) specificato, garantendo capacità di scala e stampa accurate. |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// Carica un'immagine JPEG da un file.
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // Esegui qualche elaborazione dell'immagine.
    // Salva in un altro file JPEG.
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


La classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) si avvia senza sforzo invocando il suo costruttore con il parametro di percorso specificato. Questo costruttore consente la creazione fluida di immagini JPEG, garantendo un'integrazione rapida nei tuoi progetti con facilità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


Inizializza un oggetto immagine JPEG con la classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) utilizzando un parametro stream. Questo costruttore semplifica il processo di lavoro con le immagini JPEG, offrendo un approccio diretto per integrare facilmente nei tuoi progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


Inizializza una nuova istanza della classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con un parametro immagine raster. Questo costruttore offre un modo comodo per creare immagini JPEG direttamente da immagini raster, semplificando il flusso di lavoro per l'utilizzo delle immagini JPEG nelle tue applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine con cui inizializzare i dati dei pixel e della palette. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


Crea una nuova istanza della classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con i parametri di larghezza e altezza specificati. Questo costruttore consente di creare immagini JPEG con dimensioni personalizzate, offrendoti flessibilità nella gestione delle dimensioni delle immagini nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine. |
| height | int | L'altezza dell'immagine. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


Inizializza un nuovo oggetto [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con le opzioni JPEG fornite. Questo costruttore ti permette di personalizzare varie impostazioni per l'immagine JPEG, come il livello di compressione, la qualità e parametri aggiuntivi, garantendo un controllo preciso sul formato dell'immagine risultante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Le opzioni JPEG. |
| width | int | Larghezza immagine. |
| height | int | Altezza immagine. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera facilmente il formato dell'immagine con questa proprietà. Fornisce informazioni preziose sul formato del file, facilitando l'integrazione senza soluzione di continuità e i controlli di compatibilità su varie piattaforme e applicazioni.

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


Accedi facilmente alle opzioni JPEG utilizzate durante la creazione o il caricamento di questa istanza di [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage). Questa proprietà offre dettagli preziosi sulle impostazioni specifiche impiegate, consentendo agli utenti di comprendere e replicare efficacemente i flussi di lavoro di elaborazione delle immagini. Che si tratti di livelli di compressione, impostazioni di qualità o altri parametri, questa proprietà fornisce informazioni essenziali per una manipolazione delle immagini senza soluzione di continuità.

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//L'output appare così:
//Il numero di bit per canale: 8
//La dimensione massima consentita per tutti i buffer interni: 0
//Il tipo di colore: YCbCr
//Il tipo di compressione: Baseline
//La qualità dell'immagine: 75
//Il campionamento per il componente 0: 1x1
//Il campionamento per il componente 1: 1x1
//Il campionamento per il componente 2: 1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupera facilmente la profondità dei pixel dell'immagine con questa proprietà, offrendo informazioni sulla ricchezza della rappresentazione a colori o in scala di grigi. Che si tratti di una fotografia vivace o di un'illustrazione monocromatica, questa proprietà fornisce informazioni cruciali sulla complessità visiva dell'immagine.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.
### getComment() {#getComment--}
```
public String getComment()
```


Gestisci i commenti dei file JPEG con questa proprietà, consentendo di aggiungere o recuperare annotazioni descrittive associate all'immagine. Che si tratti di etichettare le immagini con metadati o di aggiungere contesto aggiuntivo, questa proprietà offre flessibilità nell'organizzare e categorizzare i tuoi file JPEG.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Gestisci i commenti dei file JPEG con questa proprietà, consentendo di aggiungere o recuperare annotazioni descrittive associate all'immagine. Che si tratti di etichettare le immagini con metadati o di aggiungere contesto aggiuntivo, questa proprietà offre flessibilità nell'organizzare e categorizzare i tuoi file JPEG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


Ottiene l'istanza Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Gestisci i dati EXIF con questa proprietà, consentendo di aggiungere o recuperare i metadati associati all'immagine. Che si tratti di estrarre informazioni sulle impostazioni della fotocamera o di modificare i metadati esistenti, questa proprietà offre flessibilità nella gestione del contenitore dei dati EXIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Ottiene i dati Exif;

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//L'output appare così:
//I dati EXIF generali
//------------------------------------------
//La versione EXIF: [B@163e4e87
//Il numero di serie della fotocamera: 7100536
//Lo spazio colore: SRgb
//La luminosità:
//Il contrasto: Normale
//Il gamma:
//La nitidezza: 0
//L'apertura: 4.64(4643856 / 1000000)
//La modalità di esposizione: Manuale
//Il bias di esposizione: 0.67(4 / 6)
//Il tempo di esposizione: 0.01(1 / 160)
//La lunghezza focale: 145.00(1450 / 10)
//L'unità di risoluzione del piano focale: Cm
//Il modello dell'obiettivo: 70.0 - 200.0 mm f/ 4.0
//La velocità dell'otturatore: 7.32(7321928 / 1000000)
//I dati EXIF JPEG
//------------------------------------------
//Il produttore della fotocamera: NIKON CORPORATION
//Il modello della fotocamera: NIKON D5
//L'interpretazione fotometrica: 0
//L'artista:
//Il copyright:
//La descrizione dell'immagine:
//L'orientamento: TopLeft
//Il software: Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Imposta i dati Exif;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Dati Exif; |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Recupera l'altezza dell'immagine senza sforzo con questa proprietà. Fornisce un accesso rapido alla dimensione verticale dell'immagine, consentendoti di determinare in modo efficiente le sue dimensioni e il rapporto d'aspetto senza la necessità di calcoli complessi o metodi aggiuntivi.

**Returns:**
int - L'altezza dell'immagine in pixel.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Questa proprietà ti consente di accedere alla risoluzione orizzontale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice. Impostando o recuperando questo valore, puoi controllare con precisione la risoluzione dell'immagine, assicurandoti che soddisfi i tuoi requisiti specifici di qualità e chiarezza.

**Returns:**
double - La risoluzione orizzontale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Ottieni la risoluzione orizzontale e verticale del BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 300.0
// La risoluzione verticale, in pixel per pollice: 300.0
// Imposta i valori di risoluzione a 96 dpi
// La risoluzione orizzontale, in pixel per pollice: 96.0
// La risoluzione verticale, in pixel per pollice: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Questa proprietà ti consente di accedere alla risoluzione orizzontale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice. Impostando o recuperando questo valore, puoi controllare con precisione la risoluzione dell'immagine, assicurandoti che soddisfi i tuoi requisiti specifici di qualità e chiarezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione orizzontale. |

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo `setResolution` per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Questa proprietà ti consente di accedere o modificare i dati JFIF (JPEG File Interchange Format) associati all'immagine JPEG. JFIF è un formato standard per lo scambio di immagini JPEG compresse tra computer e altri dispositivi. Ottenendo o impostando questa proprietà, puoi interagire con i dati JFIF, che possono includere informazioni come la risoluzione dell'immagine, il rapporto d'aspetto e la miniatura.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Questa proprietà ti consente di accedere o modificare i dati JFIF (JPEG File Interchange Format) associati all'immagine JPEG. JFIF è un formato standard per lo scambio di immagini JPEG compresse tra computer e altri dispositivi. Ottenendo o impostando questa proprietà, puoi interagire con i dati JFIF, che possono includere informazioni come la risoluzione dell'immagine, il rapporto d'aspetto e la miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Questa proprietà recupera il formato dei dati grezzi dell'immagine, che indica come i dati dell'immagine sono strutturati e codificati. Comprendere il formato dei dati grezzi è essenziale per elaborare o manipolare efficacemente i dati dell'immagine. Fornisce approfondimenti sulla rappresentazione sottostante dell'immagine, ad esempio se è compressa, codificata in uno spazio colore specifico o memorizzata in un formato di file particolare. Accedere a questa proprietà ti consente di ottenere informazioni preziose sulla struttura dei dati dell'immagine, permettendoti di eseguire varie operazioni o ottimizzazioni adattate al suo formato specifico.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Questa proprietà gestisce la risoluzione verticale, espressa in pixel per pollice, per il [RasterImage](../../com.aspose.imaging/rasterimage) associato. Regolare questa risoluzione influisce sulla dimensione e sulla qualità dell'immagine quando stampata o visualizzata a una dimensione fisica fissa. Impostando questa proprietà, controlli la densità verticale dei pixel dell'immagine, influenzando la sua nitidezza e chiarezza complessive.

**Returns:**
double - La risoluzione verticale.

Nota: per impostazione predefinita questo valore è sempre 72 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. È possibile considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Ottieni la risoluzione orizzontale e verticale del BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 300.0
// La risoluzione verticale, in pixel per pollice: 300.0
// Imposta i valori di risoluzione a 96 dpi
// La risoluzione orizzontale, in pixel per pollice: 96.0
// La risoluzione verticale, in pixel per pollice: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Questa proprietà gestisce la risoluzione verticale, espressa in pixel per pollice, per il [RasterImage](../../com.aspose.imaging/rasterimage) associato. Regolare questa risoluzione influisce sulla dimensione e sulla qualità dell'immagine quando stampata o visualizzata a una dimensione fisica fissa. Impostando questa proprietà, controlli la densità verticale dei pixel dell'immagine, influenzando la sua nitidezza e chiarezza complessive.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione verticale. |

Nota: per impostazione predefinita questo valore è sempre 72 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. È possibile considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Questa proprietà recupera la larghezza dell'immagine, espressa in pixel. Fornisce informazioni essenziali sulle dimensioni dell'immagine, consentendo una resa, manipolazione o visualizzazione accurata dei dati dell'immagine.

**Returns:**
int - La larghezza dell'immagine in pixel.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Il profilo colore RGB per le immagini JPEG CMYK e YCCK garantisce una conversione e rappresentazione del colore accurate. Deve essere associato al CMYKColorProfile per mantenere coerenza e fedeltà nella resa del colore. Questa associazione è essenziale per le applicazioni che richiedono una gestione precisa del colore e la riproduzione delle immagini, assicurando che i dati RGB siano interpretati e visualizzati correttamente.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Il profilo colore RGB per le immagini JPEG CMYK e YCCK garantisce una conversione e rappresentazione del colore accurate. Deve essere associato al CMYKColorProfile per mantenere coerenza e fedeltà nella resa del colore. Questa associazione è essenziale per le applicazioni che richiedono una gestione precisa del colore e la riproduzione delle immagini, assicurando che i dati RGB siano interpretati e visualizzati correttamente.

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


Il profilo colore CMYK associato alle immagini JPEG CMYK e YCCK garantisce una conversione del colore precisa e fedeltà. Funziona in combinazione con l'RGBColorProfile per garantire una rappresentazione accurata del colore su vari dispositivi e applicazioni. Questa associazione è fondamentale per mantenere la coerenza nella resa del colore e ottenere una qualità ottimale dell'immagine.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Il profilo colore CMYK associato alle immagini JPEG CMYK e YCCK garantisce una conversione del colore precisa e fedeltà. Funziona in combinazione con l'RGBColorProfile per garantire una rappresentazione accurata del colore su vari dispositivi e applicazioni. Questa associazione è fondamentale per mantenere la coerenza nella resa del colore e ottenere una qualità ottimale dell'immagine.

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

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


L'RGBColorProfile è essenziale per la conversione accurata del colore delle immagini JPEG CMYK e YCCK durante il processo di salvataggio. Quando è associato al CMYKColorProfile, assicura che i colori vengano renderizzati correttamente e mantiene la coerenza su diversi dispositivi e applicazioni. Questa combinazione è cruciale per preservare la rappresentazione cromatica prevista e ottenere un'output di immagine di alta qualità.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


L'RGBColorProfile è essenziale per la conversione accurata del colore delle immagini JPEG CMYK e YCCK durante il processo di salvataggio. Quando è associato al CMYKColorProfile, assicura che i colori vengano renderizzati correttamente e mantiene la coerenza su diversi dispositivi e applicazioni. Questa combinazione è cruciale per preservare la rappresentazione cromatica prevista e ottenere un'output di immagine di alta qualità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


Il profilo colore CMYK è fondamentale per la conversione accurata del colore delle immagini JPEG CMYK e YCCK durante il processo di salvataggio. Lavora in tandem con l'RGBColorProfile per garantire una corretta rappresentazione del colore, mantenendo coerenza e qualità su diversi dispositivi e software. Questa sincronizzazione è cruciale per ottenere una resa del colore accurata e affidabile nelle immagini finali salvate.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


Il profilo colore CMYK è fondamentale per la conversione accurata del colore delle immagini JPEG CMYK e YCCK durante il processo di salvataggio. Lavora in tandem con l'RGBColorProfile per garantire una corretta rappresentazione del colore, mantenendo coerenza e qualità su diversi dispositivi e software. Questa sincronizzazione è cruciale per ottenere una resa del colore accurata e affidabile nelle immagini finali salvate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


Recupera o modifica il flag che indica se il profilo colore incorporato è ignorato. Impostando questo flag, gli utenti possono specificare se utilizzare il profilo colore predefinito al posto di quello incorporato. Questa opzione garantisce un maggiore controllo sulla gestione del colore, facilitando le regolazioni per coerenza e compatibilità su varie piattaforme e applicazioni.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


Recupera o modifica il flag che indica se il profilo colore incorporato è ignorato. Impostando questo flag, gli utenti possono specificare se utilizzare il profilo colore predefinito al posto di quello incorporato. Questa opzione garantisce un maggiore controllo sulla gestione del colore, facilitando le regolazioni per coerenza e compatibilità su varie piattaforme e applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ottiene le opzioni originali dell'immagine di questa istanza di [Image](../../com.aspose.imaging/image).

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Rimuove i metadati di questa istanza di immagine impostando i valori di `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) e `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) a `null`.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Stabilisce la risoluzione per il [RasterImage](../../com.aspose.imaging/rasterimage) specificato, garantendo una scalatura e capacità di stampa accurate. Questo metodo consente agli utenti di personalizzare la risoluzione dell'immagine per soddisfare i loro requisiti specifici, sia per la visualizzazione digitale che per la riproduzione fisica. Impostando la risoluzione, gli utenti possono ottimizzare la qualità dell'immagine e garantire la compatibilità con vari dispositivi di output e supporti, migliorando l'esperienza visiva complessiva e l'usabilità dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpiX | double | La risoluzione orizzontale, in punti per pollice, del `RasterImage`. |
| dpiY | double | La risoluzione verticale, in punti per pollice, del `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Ottieni la risoluzione orizzontale e verticale del BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 300.0
// La risoluzione verticale, in pixel per pollice: 300.0
// Imposta i valori di risoluzione a 96 dpi
// La risoluzione orizzontale, in pixel per pollice: 96.0
// La risoluzione verticale, in pixel per pollice: 96.0
```

