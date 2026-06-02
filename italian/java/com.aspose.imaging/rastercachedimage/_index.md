---
title: "RasterCachedImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta un'immagine raster che supporta operazioni grafiche raster."
type: docs
weight: 89
url: /it/java/com.aspose.imaging/rastercachedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

Rappresenta un'immagine raster che supporta operazioni grafiche raster. Questa immagine memorizza nella cache i dati dei pixel quando necessario.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isCached()](#isCached--) | Restituisce un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [cacheData()](#cacheData--) | Memorizza nella cache i dati e garantisce che non venga eseguito alcun ulteriore caricamento dei dati dal sottostante `DataStreamSupporter.DataStreamContainer`. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mescola questa istanza di immagine con l'immagine `overlay`. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ridimensiona l'immagine. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ridimensiona l'immagine. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Ruota l'immagine attorno al centro. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia l'immagine. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Esegue il dithering sull'immagine corrente. |
| [grayscale()](#grayscale--) | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [normalizeHistogram()](#normalizeHistogram--) | Normalizza l'istogramma dell'immagine \\u2014 regola i valori dei pixel per utilizzare l'intera gamma disponibile. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Esegue la normalizzazione automatica adattiva di luminosità e contrasto per l'intera immagine. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarizzazione di un'immagine con soglia predefinita |
| [binarizeOtsu()](#binarizeOtsu--) | Binarizzazione di un'immagine con soglia di Otsu |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Regola la luminosità dell'immagine. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contrasto dell'immagine |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correzione gamma di un'immagine. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correzione gamma di un'immagine. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Incorpora una firma digitale basata sulla password fornita nell'immagine usando la steganografia. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Calcola la percentuale di somiglianza tra i dati estratti e la password originale. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Esegue un controllo rapido per determinare se l'immagine è firmata digitalmente, usando la password fornita e la soglia. |

## Example: The following example transforms a colored raster cached image to its grayscale representation.
Il seguente esempio trasforma un'immagine raster a colori memorizzata nella cache nella sua rappresentazione in scala di grigi. Le immagini in scala di grigi sono composte esclusivamente da sfumature di grigio e contengono solo informazioni di intensità.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### isCached() {#isCached--}
```
public boolean isCached()
```


Restituisce un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache.

**Returns:**
boolean - `true` se i dati dell'immagine sono nella cache; altrimenti, `false`.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Memorizza nella cache i dati e garantisce che non venga eseguito alcun ulteriore caricamento dei dati dal sottostante `DataStreamSupporter.DataStreamContainer`.


**Example: The following example shows how raster image caching affects performance.**
Il seguente esempio mostra come la memorizzazione nella cache delle immagini raster influisce sulle prestazioni. In generale, la lettura dei dati nella cache è più veloce rispetto alla lettura dei dati non memorizzati nella cache.
``` java
String dir = "c:\\temp\\";

// Carica un'immagine da un file PNG.
com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Memorizza nella cache tutti i dati dei pixel in modo che non venga eseguito alcun ulteriore caricamento dei dati dal flusso di dati sottostante
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // La lettura di tutti i pixel è abbastanza veloce.
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// Carica un'immagine da un file PNG
image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // La lettura di tutti i pixel non è veloce come quando si utilizza la cache
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
//La lettura di tutti i pixel nella cache ha impiegato 2923 ms.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//at com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:54)
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Mescola questa istanza di immagine con l'immagine `overlay`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine della fusione dell'immagine di sfondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine di sovrapposizione. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | L'area di sovrapposizione. |
| overlayAlpha | byte | L'alpha di sovrapposizione. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ridimensiona l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |


**Example: This example loads a raster cached image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Riduci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ridimensiona l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Le impostazioni di ridimensionamento. |


**Example: This example loads a raster cached image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// L'algoritmo adattivo basato su funzione razionale ponderata e mescolata e interpolazione lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Il piccolo filtro rettangolare
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Il numero di colori nella tavolozza.
resizeSettings.setEntriesCount(256);

// La quantizzazione del colore non è utilizzata
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Il metodo euclideo
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Riduci di 2 volte usando il ricampionamento adattivo.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Ruota, capovolge o ruota e capovolge l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Il tipo di rotazione e capovolgimento. |


**Example: This example loads a raster cached image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Questa è una classe di supporto.
class LocalHelper {
    // Restituisce una rappresentazione stringa del tipo di rotazione e capovolgimento.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// Ecco l'esempio principale
int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

LocalHelper localHelper = new LocalHelper();
for (int rotateFlipType : rotateFlipTypes) {
    // Ruota, capovolgi e salva nel file di output.
    com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + localHelper.rotateFlipTypeToString(rotateFlipType) + ".bmp");
    } finally {
        image.dispose();
    }
}
```

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Ruota l'immagine attorno al centro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | boolean | se impostato su `true` le dimensioni dell'immagine verranno modificate in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Ritaglia l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |


**Example: The following example crops a raster cached image.**
Il seguente esempio ritaglia un'immagine raster memorizzata nella cache. L'area di ritaglio deve essere specificata tramite com.aspose.imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Ritaglia l'immagine. L'area di ritaglio è la zona rettangolare centrale dell'immagine.
    int width = rasterImage.getWidth();
    int height = rasterImage.getHeight();
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(width / 4, height / 4, width / 2, height / 2);
    rasterImage.crop(area);

    // Salva l'immagine ritagliata in PNG
    rasterImage.save(dir + "sample.Crop.png");
} finally {
    image.dispose();
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Esegue il dithering sull'immagine corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personalizzata per il dithering. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Trasformazione di un'immagine nella sua rappresentazione in scala di grigi


**Example: The following example transforms a colored raster cached image to its grayscale representation.**
Il seguente esempio trasforma un'immagine raster a colori memorizzata nella cache nella sua rappresentazione in scala di grigi. Le immagini in scala di grigi sono composte esclusivamente da sfumature di grigio e contengono solo informazioni di intensità.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Normalizza l'istogramma dell'immagine \\u2014 regola i valori dei pixel per utilizzare l'intera gamma disponibile.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


Esegue la normalizzazione automatica adattiva di luminosità e contrasto per l'intera immagine.

--------------------

> ```
> // Example usage in image pre-processing:
>  image.AutoBrightnessContrast();
> ```

--------------------

Questo metodo applica una pipeline di filtri adattivi avanzati (CLAHE, adaptive white stretch e auto white balance) per migliorare la qualità visiva dell'immagine migliorando contrasto, luminosità locale e fedeltà del colore.

`**Pipeline di filtro:**`

1.  Equalizzazione adattiva dell'istogramma limitata al contrasto (CLAHE) \u2013 migliora il contrasto locale e accentua i dettagli deboli.
2.  Adaptive White Stretch \u2013 aumenta il livello di bianco efficace proteggendo le caratteristiche scure.
3.  Auto White Balance \u2013 corregge le dominanti di colore bilanciando gli istogrammi dei canali.

`**Nota:**`

 *  
 *  

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarizzazione di un'immagine con soglia predefinita

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato il valore 255, altrimenti 0. |


**Example: The following example binarizes a raster cached image with the predefined threshold.**
Il seguente esempio binarizza un'immagine raster memorizzata nella cache con la soglia predefinita. Le immagini binarizzate contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binarizza l'immagine con un valore di soglia di 127.
    // Se il valore di grigio corrispondente di un pixel è maggiore di 127, gli verrà assegnato un valore di 255, altrimenti 0.
    rasterImage.binarizeFixed((byte) 127);
    rasterImage.save(dir + "sample.BinarizeFixed.png");
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarizzazione di un'immagine con soglia di Otsu


**Example: The following example binarizes a raster cached image with Otsu thresholding.**
Il seguente esempio binarizza un'immagine raster memorizzata nella cache con la sogliatura di Otsu. Le immagini binarizzate contengono solo 2 colori: nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binarizza l'immagine con la sogliatura di Otsu.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |
| windowSize | int | La dimensione della finestra s x s di pixel centrata su questo pixel. |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm with the specified window size.**
Il seguente esempio binarizza un'immagine raster memorizzata nella cache con l'algoritmo di sogliatura adattiva di Bradley con la dimensione della finestra specificata. Le immagini binarizzate contengono solo 2 colori: nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binarizza l'immagine con una differenza di luminosità di 5.
    // La luminosità è una differenza tra un pixel e la media di una finestra 10 x 10 di pixel centrata su questo pixel.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm.**
Il seguente esempio binarizza un'immagine raster memorizzata nella cache con l'algoritmo di sogliatura adattiva di Bradley. Le immagini binarizzate contengono solo 2 colori: nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binarizza l'immagine con una differenza di luminosità di 5.
    // La luminosità è una differenza tra un pixel e la media di una finestra s x s di pixel centrata su questo pixel.
    // La dimensione della finestra verrà calibrata automaticamente.
    rasterImage.binarizeBradley(5);
    rasterImage.save(dir + "sample.BinarizeBradley5.png");
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Regola la luminosità dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | int | Valore di luminosità. |


**Example: The following example performs brightness correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Imposta il valore di luminosità. I valori accettati per la luminosità sono nell'intervallo [-255, 255].
    rasterImage.adjustBrightness(50);
    rasterImage.save(dir + "sample.AdjustBrightness.png");
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Contrasto dell'immagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrast | float | Valore di contrasto (nell'intervallo [-100; 100]) |


**Example: The following example performs contrast correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Imposta il valore di contrasto. I valori accettati per il contrasto sono nell'intervallo [-100f, 100f].
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Correzione gamma di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gammaRed | float | Gamma per il coefficiente del canale rosso |
| gammaGreen | float | Gamma per il coefficiente del canale verde |
| gammaBlue | float | Coefficiente gamma per il canale blu |


**Example: The following example performs gamma-correction of a raster cached image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Imposta i coefficienti gamma individuali per i canali rosso, verde e blu.
    rasterImage.adjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Correzione gamma di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |


**Example: The following example performs gamma-correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Imposta il coefficiente gamma per i canali rosso, verde e blu.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Incorpora una firma digitale basata sulla password fornita nell'immagine usando la steganografia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password utilizzata per generare i dati della firma digitale |


**Example: The example shows how to embed digital signature based on provided password into image pixel data.**

``` java
String imageFilePath = "ball.png";
String password = "veryStr0ngPassword";
try (Image image = Image.load(imageFilePath))
{
    image.embedDigitalSignature(password);
    image.save(outputPath);
}
```

### analyzePercentageDigitalSignature(String password) {#analyzePercentageDigitalSignature-java.lang.String-}
```
public int analyzePercentageDigitalSignature(String password)
```


Calcola la percentuale di somiglianza tra i dati estratti e la password originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password utilizzata per estrarre i dati incorporati. |

**Returns:**
int - Il valore di percentuale di somiglianza.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Esegue un controllo rapido per determinare se l'immagine è firmata digitalmente, usando la password fornita e la soglia.

--------------------

Questo metodo fornisce la rilevazione più veloce sfruttando `GetSignPercentage`. Una volta che i dati estratti raggiungono la soglia specificata, i passaggi di estrazione successivi volti a migliorare la precisione della rilevazione vengono saltati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password per verificare la firma. |
| percentageThreshold | int | La soglia (in percentuale)[0-100] che determina se l'immagine è considerata firmata. Se non specificata, verrà applicata una soglia predefinita (`75`). |

**Returns:**
boolean - True se l'immagine è firmata, altrimenti false.
