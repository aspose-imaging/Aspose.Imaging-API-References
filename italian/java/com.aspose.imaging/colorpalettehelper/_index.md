---
title: "ColorPaletteHelper"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe di supporto per la manipolazione della tavolozza dei colori."
type: docs
weight: 29
url: /it/java/com.aspose.imaging/colorpalettehelper/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Classe di supporto per la manipolazione della tavolozza dei colori.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMonochrome()](#createMonochrome--) | Crea una tavolozza di colori monocromatica contenente solo 2 colori. |
| [create4Bit()](#create4Bit--) | Crea la tavolozza di colori a 4 bit. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Crea la tavolozza in scala di grigi a 4 bit. |
| [create8Bit()](#create8Bit--) | Crea la tavolozza di colori a 8 bit. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Crea la tavolozza in scala di grigi a 8 bit. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. |
| [getCloseTransparentImagePalette(RasterImage image, int entriesCount)](#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. |
| [getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.imaging.RasterImage-) | Ottieni una tavolozza uniforme di 256 colori. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.imaging.RasterImage-) | Ottieni una tavolozza di 256 colori, composta dai bit più alti dei valori di colore dell'immagine iniziale. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.imaging.IColorPalette-) | Determina se la tavolozza specificata contiene colori trasparenti. |
| [createGrayscale(int bits)](#createGrayscale-int-) | Ottiene la tavolozza in scala di grigi per il numero di bit specificato. |
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Crea una tavolozza di colori monocromatica contenente solo 2 colori.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Color palette for monochrome images.
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


Crea la tavolozza di colori a 4 bit.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Crea la tavolozza in scala di grigi a 4 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| minIsWhite | boolean | se impostato su `true` la tavolozza inizia con il colore bianco, altrimenti inizia con il colore nero. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Crea la tavolozza di colori a 8 bit.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Crea la tavolozza in scala di grigi a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| minIsWhite | boolean | se impostato su `true` la tavolozza inizia con il colore bianco, altrimenti inizia con il colore nero. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8 bit grayscale palette.

**Example: The following example creates a palettized grayscale BMP image and then saves it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.BmpOptions createOptions = new com.aspose.imaging.imageoptions.BmpOptions();

// Salva su un file
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.palette8bit.bmp", false));

// Usa 8 bit per pixel per ridurre le dimensioni dell'immagine di output.
createOptions.setBitsPerPixel(8);

// Imposta la tavolozza di colori in scala di grigi a 8 bit standard che copre tutti i colori in scala di grigi.
// Se l'immagine elaborata contiene solo colori in scala di grigi, allora la sua versione palettizzata
// è visivamente indistinguibile da una non palettizzata.
createOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

// Salva senza compressione.
// Puoi anche usare la compressione RLE-8 per ridurre le dimensioni dell'immagine di output.
createOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

// Imposta la risoluzione orizzontale e verticale a 96 dpi.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

// Crea un'immagine BMP di 100 x 100 px e salvala su un file.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlack(),
            com.aspose.imaging.Color.getWhite());

    // Riempire l'immagine con un gradiente in scala di grigi
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save();
} finally {
    image.dispose();
}
```

### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. Nel caso la tavolozza esista, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |
| entriesCount | int | Il conteggio delle voci desiderato. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Crea un'immagine BMP 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Il gradiente lineare dall'angolo in alto a sinistra a quello in basso a destra dell'immagine.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Riempie l'intera immagine con il pennello a gradiente lineare.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Ottieni la palette di colori a 8 bit più vicina che copra il maggior numero possibile di pixel, in modo che un'immagine paletteizzata
    // sia quasi indistinguibile visivamente da una non paletteizzata.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // La palette a 8 bit contiene al massimo 256 colori.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// L'output appare così:
// La dimensione dell'immagine a palette è 11078 byte.
// La dimensione dell'immagine non a palette è 40054 byte.
```

### getCloseTransparentImagePalette(RasterImage image, int entriesCount) {#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseTransparentImagePalette(RasterImage image, int entriesCount)
```


Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. Nel caso la tavolozza esista, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |
| entriesCount | int | Il conteggio delle voci desiderato. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)
```


Ottiene la tavolozza dei colori dall'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. La tavolozza verrà ottimizzata per una migliore qualità dell'immagine indicizzata o presa "AS IS" quando viene utilizzato PaletteMiningMethod.UseCurrentPalette.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |
| entriesCount | int | Il conteggio delle voci desiderato. |
| paletteMiningMethod | int | Il metodo di estrazione della tavolozza. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

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

### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. Nel caso la tavolozza esista, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | I limiti dell'immagine di destinazione. |
| entriesCount | int | Il conteggio delle voci desiderato. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. Nel caso la tavolozza esista, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | I limiti dell'immagine di destinazione. |
| entriesCount | int | Il conteggio delle voci desiderato. |
| useImagePalette | boolean | Se impostato, utilizzerà la propria tavolozza dell'immagine, se disponibile |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)
```


Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. Nel caso la tavolozza esista, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | I limiti dell'immagine di destinazione. |
| entriesCount | int | Il conteggio delle voci desiderato. |
| useImagePalette | boolean | Se impostato, utilizzerà la propria tavolozza dell'immagine, se disponibile |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Il colore da utilizzare come colore di sfondo per la sostituzione alfa semitrasparente. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)
```


Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso l'immagine non ne abbia una. Nel caso la tavolozza esista, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | I limiti dell'immagine di destinazione. |
| entriesCount | int | Il conteggio delle voci desiderato. |
| useImagePalette | boolean | Se impostato, utilizzerà la propria tavolozza dell'immagine, se disponibile |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Il colore da utilizzare come colore di sfondo per la sostituzione alfa semitrasparente. |
| keepTransparency | boolean | Se impostato, considererà i bit del canale alfa dei colori dell'immagine. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Ottieni una tavolozza uniforme di 256 colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Ottieni una tavolozza di 256 colori, composta dai bit più alti dei valori di colore dell'immagine iniziale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.imaging.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Determina se la tavolozza specificata contiene colori trasparenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza. |

**Returns:**
boolean - `true` se la tavolozza specificata ha colori trasparenti; altrimenti, `false`.
### createGrayscale(int bits) {#createGrayscale-int-}
```
public static IColorPalette createGrayscale(int bits)
```


Ottiene la tavolozza in scala di grigi per il conteggio di bit specificato. I valori di bit consentiti sono 1, 2, 4, 8.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bits | int | Il conteggio dei bit. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Grayscale palette.
