---
title: "BmpImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Puoi gestire senza sforzo i file Bitmap BMP e Device Independent Bitmap DIB, facilitando una manipolazione ed elaborazione efficienti delle immagini raster."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

Puoi gestire senza sforzo i file Bitmap (BMP) e Device Independent Bitmap (DIB), facilitando una manipolazione ed elaborazione efficienti delle immagini raster. Eseguendo varie operazioni sulle immagini, questa API semplifica il flusso di lavoro, offrendo agli sviluppatori un toolkit affidabile per lavorare con i formati BMP e DIB nelle loro applicazioni software.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | Inizia a utilizzare la classe BmpImage senza sforzo con questo costruttore che inizializza una nuova istanza. |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | Crea senza sforzo una nuova istanza della classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con questo costruttore, utilizzando parametri specificati come percorso, bitsPerPixel e compressione. |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | Inizia a utilizzare la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza sforzo inizializzando una nuova istanza con questo costruttore, usando uno stream come input. |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | Inizia a lavorare con la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza interruzioni creando una nuova istanza usando uno stream, insieme a parametri specificati come bitsPerPixel e compressione. |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | Crea senza sforzo una nuova istanza della classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) inizializzandola con un oggetto RasterImage. |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | Inizia a lavorare con la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza interruzioni creando una nuova istanza usando un rasterImage insieme a parametri specificati come bitsPerPixel e compressione. |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | Inizia a utilizzare la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza sforzo creando una nuova istanza con parametri di larghezza e altezza specificati. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | Inizia a utilizzare la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza interruzioni inizializzando una nuova istanza con parametri come larghezza, altezza, profondità di bit e palette. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | Crea senza sforzo una nuova istanza della classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con questo costruttore, specificando parametri come larghezza, altezza, bitsPerPixel e palette. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | Accedi rapidamente ai dettagli essenziali della tua immagine bitmap con questa funzione semplice. |
| [getFileFormat()](#getFileFormat--) | Recupera facilmente il valore del formato file con questa proprietà intuitiva. |
| [getRawDataFormat()](#getRawDataFormat--) | Ottieni facilmente il formato dei tuoi dati grezzi con questa funzione intuitiva. |
| [getRawLineSize()](#getRawLineSize--) | Accedi rapidamente alla dimensione di ogni riga grezza in byte con questa proprietà semplice. |
| [getCompression()](#getCompression--) | Recupera senza sforzo il tipo di compressione utilizzato per l'immagine con questa proprietà. |
| [getWidth()](#getWidth--) | Accedi facilmente alla larghezza dell'immagine con questa proprietà. |
| [getHeight()](#getHeight--) | Recupera senza sforzo l'altezza dell'immagine con questa proprietà. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Accedi al numero di bit per pixel dell'immagine con facilità usando questa proprietà. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Questa proprietà ti consente di ottenere o impostare facilmente la risoluzione orizzontale, misurata in pixel per pollice, dell'oggetto [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Questa proprietà ti consente di ottenere o impostare facilmente la risoluzione orizzontale, misurata in pixel per pollice, dell'oggetto [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getVerticalResolution()](#getVerticalResolution--) | Recupera o imposta facilmente la risoluzione verticale, misurata in pixel per pollice, di questo oggetto [RasterImage](../../com.aspose.imaging/rasterimage) con questa proprietà. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Recupera o imposta facilmente la risoluzione verticale, misurata in pixel per pollice, di questo oggetto [RasterImage](../../com.aspose.imaging/rasterimage) con questa proprietà. |
| [hasAlpha()](#hasAlpha--) | Ottiene un valore che indica se questa istanza ha alfa. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Regola senza sforzo la risoluzione del tuo [RasterImage](../../com.aspose.imaging/rasterimage) con questo metodo intuitivo. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Recupera senza sforzo le opzioni predefinite con questo metodo semplice. |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// Crea un'immagine BMP 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Riempie l'immagine con un semplice gradiente lineare rosso-nero.
    int width = bmpImage.getWidth();
    int height = bmpImage.getHeight();
    for (int y = 0; y < height; y++) {
        for (int x = 0; x < width; x++) {
            int hue = (255 * x) / width;
            bmpImage.setPixel(x, y, com.aspose.imaging.Color.fromArgb(255, hue, 0, 0));
        }
    }

    java.io.OutputStream stream = new java.io.FileOutputStream(dir + "output.bmp");
    try {
        bmpImage.save(stream);
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}
```


## Example: Compress BMP image using DXT1 compression algorithm.

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


## Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```


## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

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


## Example: The example shows how to export a BmpImage with the Rgb compression type.

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


## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### BmpImage(String path) {#BmpImage-java.lang.String-}
```
public BmpImage(String path)
```


Inizia a utilizzare la classe BmpImage senza sforzo con questo costruttore che inizializza una nuova istanza. Perfetto per gli sviluppatori che desiderano avviare rapidamente e in modo efficiente gli oggetti [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Crea senza sforzo una nuova istanza della classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con questo costruttore, usando parametri specifici come percorso, bitsPerPixel e compressione. Ideale per gli sviluppatori che desiderano inizializzare rapidamente e in modo efficiente gli oggetti BmpImage, con un controllo preciso sulle caratteristiche dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |
| bitsPerPixel | int | I bit per pixel. |
| compressione | long | La compressione da utilizzare. |
| horizontalResolution | double | La risoluzione orizzontale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |
| verticalResolution | double | La risoluzione verticale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


Inizia a utilizzare la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza sforzo inizializzando una nuova istanza con questo costruttore, usando uno stream come input. Perfetto per gli sviluppatori che cercano un modo comodo per lavorare con gli oggetti BmpImage provenienti da varie fonti di dati, garantendo flessibilità e facilità di integrazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Inizia a lavorare con la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza interruzioni creando una nuova istanza usando uno stream, insieme a parametri specifici come bitsPerPixel e compressione. Perfetto per gli sviluppatori che cercano un modo diretto per gestire gli oggetti BmpImage, garantendo flessibilità ed efficienza nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |
| bitsPerPixel | int | I bit per pixel. |
| compressione | long | La compressione da utilizzare. |
| horizontalResolution | double | La risoluzione orizzontale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |
| verticalResolution | double | La risoluzione verticale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


Crea senza sforzo una nuova istanza della classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) inizializzandola con un oggetto RasterImage. Perfetto per gli sviluppatori che desiderano convertire senza problemi le immagini raster esistenti nel formato BmpImage, garantendo compatibilità e facilità di integrazione nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine con cui inizializzare i dati dei pixel e della palette. |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Inizia a lavorare con la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza interruzioni creando una nuova istanza usando un rasterImage insieme a parametri specifici come bitsPerPixel e compressione. Perfetto per gli sviluppatori che cercano un modo diretto per gestire gli oggetti BmpImage, garantendo flessibilità ed efficienza nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine con cui inizializzare i dati dei pixel e della palette. |
| bitsPerPixel | int | I bit per pixel. |
| compressione | long | La compressione da utilizzare. |
| horizontalResolution | double | La risoluzione orizzontale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |
| verticalResolution | double | La risoluzione verticale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


Inizia a utilizzare la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza sforzo creando una nuova istanza con parametri di larghezza e altezza specificati. Ideale per gli sviluppatori che cercano un modo comodo per generare oggetti BmpImage con dimensioni personalizzate, garantendo flessibilità e facilità di integrazione nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine. |
| height | int | L'altezza dell'immagine. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


Inizia a utilizzare la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) senza problemi inizializzando una nuova istanza con parametri come larghezza, altezza, profondità di bit e palette. Ideale per gli sviluppatori che cercano un modo semplice per creare oggetti BmpImage con dimensioni personalizzate e configurazioni di colore, garantendo flessibilità ed efficienza nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine. |
| height | int | L'altezza dell'immagine. |
| bitsPerPixel | int | I bit per pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza dei colori. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


Crea senza sforzo una nuova istanza della classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con questo costruttore, specificando parametri come larghezza, altezza, bitsPerPixel e palette. Ideale per gli sviluppatori che cercano un modo comodo per generare oggetti BmpImage con dimensioni personalizzate e configurazioni di colore, garantendo flessibilità e facilità di integrazione nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine. |
| height | int | L'altezza dell'immagine. |
| bitsPerPixel | int | I bit per pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza dei colori. |
| compressione | long | La compressione da utilizzare. |
| horizontalResolution | double | La risoluzione orizzontale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |
| verticalResolution | double | La risoluzione verticale. Nota: a causa dell'arrotondamento la risoluzione risultante potrebbe differire leggermente da quella fornita. |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


Accedi rapidamente a dettagli essenziali della tua immagine bitmap con questa funzione semplice. Ideale per gli sviluppatori che hanno bisogno di recuperare le informazioni dell'intestazione per le loro immagini.

**Returns:**
[BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader) - The bitmap information header.

**Example: The following example gets the information from the BMP header and prints it to the console.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    com.aspose.imaging.fileformats.bmp.BitmapInfoHeader header = bmpImage.getBitmapInfoHeader();

    System.out.println("The number of palette colors that are required for displaying the bitmap: " + header.getBitmapColorsImportant());
    System.out.println("The number of palette colors used in the bitmap: " + header.getBitmapColorsUsed());
    System.out.println("The bitmap compression: " + header.getBitmapCompression());
    System.out.println("The bitmap height: " + header.getBitmapHeight());
    System.out.println("The bitmap width: " + header.getBitmapWidth());
    System.out.println("The bitmap raw data size in bytes: " + header.getBitmapImageSize());
    System.out.println("The number of planes: " + header.getBitmapPlanes());
    System.out.println("The horizontal resolution of the bitmap, in pixels-per-meter: " + header.getBitmapXPelsPerMeter());
    System.out.println("The vertical resolution of the bitmap, in pixels-per-meter: " + header.getBitmapYPelsPerMeter());
    System.out.println("The number of bits per pixel: " + header.getBitsPerPixel());
    System.out.println("The extra bits masks: " + header.getExtraBitMasks());
    System.out.println("The header size in bytes: " + header.getHeaderSize());
} finally {
    image.dispose();
}

//L'output potrebbe apparire così:
//Il numero di colori della palette richiesti per visualizzare il bitmap: 0
//Il numero di colori della palette utilizzati nel bitmap: 0
//La compressione del bitmap: 0
//L'altezza del bitmap: 100
//La larghezza del bitmap: 100
//La dimensione dei dati grezzi del bitmap in byte: 40000
//Il numero di piani: 1
//La risoluzione orizzontale del bitmap, in pixel per metro: 0
//La risoluzione verticale del bitmap, in pixel per metro: 0
//Il numero di bit per pixel: 32
//Le maschere dei bit extra: null
//La dimensione dell'intestazione in byte: 40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera facilmente il valore del formato file con questa proprietà intuitiva. Ideale per gli sviluppatori che cercano un accesso rapido alle informazioni sul formato file.

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// La classe helper utilizzata nell'esempio principale di seguito.
class Utils {
    // Il metodo helper per ottenere una rappresentazione stringa del formato file.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Ecco l'esempio principale
Utils utils = new Utils();

// Crea un'immagine BMP a 32 bpp di 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 32, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// Crea un'immagine BMP a 24 bpp di 100 x 100 px.
bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 24, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// Nella maggior parte dei casi BMP non supporta il canale alfa, quindi l'output probabilmente avrà questo aspetto:
// FileFormat=BMP, RawDataFormat=Rgb32Bpp, used channels: 8,8,8,8, HasAlpha=false
// FileFormat=BMP, RawDataFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Ottieni facilmente il formato dei tuoi dati grezzi con questa funzione intuitiva. Ideale per gli sviluppatori che desiderano accedere rapidamente a informazioni cruciali sul formato dei loro dati.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//L'output potrebbe apparire così:
//Il formato pixel: Rgb24Bpp, canali usati: 8,8,8
//La dimensione della riga grezza in byte: 1500
//La compressione del bitmap: 0
//La larghezza del bitmap: 500
//L'altezza del bitmap: 500
//Il numero di bit per pixel: 24
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
//Imposta i valori di risoluzione a 96 dpi
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Accedi rapidamente alla dimensione di ogni riga grezza in byte con questa proprietà semplice. Ideale per gli sviluppatori che hanno bisogno di gestire efficientemente dati immagine grezzi.

**Returns:**
int - La dimensione della riga grezza in byte.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//L'output potrebbe apparire così:
//Il formato pixel: Rgb24Bpp, canali usati: 8,8,8
//La dimensione della riga grezza in byte: 1500
//La compressione del bitmap: 0
//La larghezza del bitmap: 500
//L'altezza del bitmap: 500
//Il numero di bit per pixel: 24
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
//Imposta i valori di risoluzione a 96 dpi
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Recupera facilmente il tipo di compressione usato per l'immagine con questa proprietà. Perfetto per gli sviluppatori che hanno bisogno di accedere rapidamente alle informazioni sulla compressione dell'immagine.

**Returns:**
long - La compressione dell'immagine [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression).

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// La classe helper utilizzata nell'esempio principale di seguito.
class Utils {
    // Il metodo helper per ottenere una rappresentazione stringa del formato file.
    public String getBitmapCompressionString(long bitmapCompression) {
        if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb) {
            return "RGB";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8) {
            return "RLE8";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle4) {
            return "RLE4";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Bitfields) {
            return "BITFIELDS";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Jpeg) {
            return "JPEG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Png) {
            return "PNG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.AlphaBitfields) {
            return "ALPHA_BITFIELDS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Ecco l'esempio principale
Utils utils = new Utils();

long[] compressions = new long[]
        {
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb,
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8,
        };

com.aspose.imaging.Color[] paletterColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
        };

// Crea una palette monocromatica che contiene solo i colori rosso e verde.
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // Crea un'immagine BMP a 8 bpp di 100 x 100 px.
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // Riempire l'intera immagine di rosso.
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // Salva l'immagine in uno stream per ottenere la dimensione dell'immagine di output.
        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            bmpImage.save(stream);

            System.out.printf("---------------------------------------------\r\n");
            System.out.printf("The compression=%s\r\n", utils.getBitmapCompressionString(bmpImage.getCompression()));
            System.out.printf("The number of bits per pixel=%s\r\n", bmpImage.getBitsPerPixel());
            System.out.printf("The image dimensions=%s x %s\r\n", bmpImage.getWidth(), bmpImage.getHeight());
            System.out.printf("The raw line size=%s\r\n", bmpImage.getRawLineSize());
            System.out.printf("The output size in bytes=%s\r\n", stream.size());
        } finally {
            stream.close();
        }
    } finally {
        bmpImage.dispose();
    }
}

// L'output potrebbe apparire così:
// La compressione=RGB
// Il numero di bit per pixel=8
// Le dimensioni dell'immagine=100 x 100
// La dimensione della linea grezza=100
// La dimensione di output in byte=11078
// ---------------------------------------------
// La compressione=RLE8
// Il numero di bit per pixel=8
// Le dimensioni dell'immagine=100 x 100
// La dimensione della linea grezza=100
// La dimensione di output in byte=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


Accedi facilmente alla larghezza dell'immagine con questa proprietà. Ideale per gli sviluppatori che cercano informazioni rapide sulle dimensioni dell'immagine.

**Returns:**
int - La larghezza dell'immagine in pixel.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//L'output potrebbe apparire così:
//Il formato pixel: Rgb24Bpp, canali usati: 8,8,8
//La dimensione della riga grezza in byte: 1500
//La compressione del bitmap: 0
//La larghezza del bitmap: 500
//L'altezza del bitmap: 500
//Il numero di bit per pixel: 24
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
//Imposta i valori di risoluzione a 96 dpi
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Recupera facilmente l'altezza dell'immagine con questa proprietà. Ideale per gli sviluppatori che hanno bisogno di un accesso rapido alle informazioni sulle dimensioni dell'immagine.

**Returns:**
int - L'altezza dell'immagine in pixel.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//L'output potrebbe apparire così:
//Il formato pixel: Rgb24Bpp, canali usati: 8,8,8
//La dimensione della riga grezza in byte: 1500
//La compressione del bitmap: 0
//La larghezza del bitmap: 500
//L'altezza del bitmap: 500
//Il numero di bit per pixel: 24
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
//Imposta i valori di risoluzione a 96 dpi
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Accedi al numero di bit per pixel dell'immagine con facilità usando questa proprietà. Perfetto per gli sviluppatori che cercano informazioni rapide sulla qualità e profondità dell'immagine.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//L'output potrebbe apparire così:
//Il formato pixel: Rgb24Bpp, canali usati: 8,8,8
//La dimensione della riga grezza in byte: 1500
//La compressione del bitmap: 0
//La larghezza del bitmap: 500
//L'altezza del bitmap: 500
//Il numero di bit per pixel: 24
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
//Imposta i valori di risoluzione a 96 dpi
//La risoluzione orizzontale, in pixel per pollice: 96.012
//La risoluzione verticale, in pixel per pollice: 96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Questa proprietà consente di ottenere o impostare facilmente la risoluzione orizzontale, misurata in pixel per pollice, dell'oggetto [RasterImage](../../com.aspose.imaging/rasterimage). Ideale per gli sviluppatori che necessitano di un controllo preciso sulla risoluzione dell'immagine per le loro applicazioni.

**Returns:**
double - La risoluzione orizzontale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo \#setResolution(double, double).setResolution(double, double) per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Ottieni la risoluzione orizzontale e verticale del BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 0.0
// La risoluzione verticale, in pixel per pollice: 0.0
// Imposta i valori di risoluzione a 96 dpi
// La risoluzione orizzontale, in pixel per pollice: 96.012
// La risoluzione verticale, in pixel per pollice: 96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Questa proprietà consente di ottenere o impostare facilmente la risoluzione orizzontale, misurata in pixel per pollice, dell'oggetto [RasterImage](../../com.aspose.imaging/rasterimage). Ideale per gli sviluppatori che necessitano di un controllo preciso sulla risoluzione dell'immagine per le loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione orizzontale. |

--------------------

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo \#setResolution(double, double).setResolution(double, double) per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Recupera o imposta facilmente la risoluzione verticale, misurata in pixel per pollice, di questo oggetto [RasterImage](../../com.aspose.imaging/rasterimage) con questa proprietà. Perfetto per gli sviluppatori che richiedono un controllo preciso sulla risoluzione dell'immagine nelle loro applicazioni.

**Returns:**
double - La risoluzione verticale.

--------------------

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo \#setResolution(double, double).setResolution(double, double) per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Ottieni la risoluzione orizzontale e verticale del BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 0.0
// La risoluzione verticale, in pixel per pollice: 0.0
// Imposta i valori di risoluzione a 96 dpi
// La risoluzione orizzontale, in pixel per pollice: 96.012
// La risoluzione verticale, in pixel per pollice: 96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Recupera o imposta facilmente la risoluzione verticale, misurata in pixel per pollice, di questo oggetto [RasterImage](../../com.aspose.imaging/rasterimage) con questa proprietà. Perfetto per gli sviluppatori che richiedono un controllo preciso sulla risoluzione dell'immagine nelle loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione verticale. |

--------------------

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo \#setResolution(double, double).setResolution(double, double) per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Ottiene un valore che indica se questa istanza ha alfa.

**Returns:**
boolean - un valore che indica se questa istanza ha alfa.
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Regola la risoluzione del tuo [RasterImage](../../com.aspose.imaging/rasterimage) senza sforzo con questo metodo intuitivo. Perfetto per gli sviluppatori che cercano un controllo preciso sulla risoluzione dell'immagine nelle loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpiX | double | La risoluzione orizzontale, in punti per pollice, del [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | La risoluzione verticale, in punti per pollice, del [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Ottieni la risoluzione orizzontale e verticale del BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 0.0
// La risoluzione verticale, in pixel per pollice: 0.0
// Imposta i valori di risoluzione a 96 dpi
// La risoluzione orizzontale, in pixel per pollice: 96.012
// La risoluzione verticale, in pixel per pollice: 96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Recupera le opzioni predefinite senza sforzo con questo metodo semplice. Ideale per gli sviluppatori che desiderano un accesso rapido alle impostazioni o configurazioni predefinite dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | java.lang.Object[] | Gli argomenti. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
