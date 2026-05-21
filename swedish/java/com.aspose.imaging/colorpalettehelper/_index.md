---
title: "ColorPaletteHelper"
second_title: "Aspose.Imaging för Java API-referens"
description: "Hjälparklass för färgpalettmanipulering."
type: docs
weight: 29
url: /sv/java/com.aspose.imaging/colorpalettehelper/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Hjälparklass för färgpalettmanipulering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMonochrome()](#createMonochrome--) | Skapar en monokrom färgpalett som endast innehåller 2 färger. |
| [create4Bit()](#create4Bit--) | Skapar 4-bitars färgpaletten. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Skapar 4-bitars gråskala-palatset. |
| [create8Bit()](#create8Bit--) | Skapar 8-bitars färgpaletten. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Skapar 8-bitars gråskala-palatset. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getCloseTransparentImagePalette(RasterImage image, int entriesCount)](#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.imaging.RasterImage-) | Hämta enhetlig 256-färgspalett. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.imaging.RasterImage-) | Hämta 256-färgspalett, sammansatt av de övre bitarna i bildens ursprungliga färgvärden. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.imaging.IColorPalette-) | Avgör om den angivna paletten har transparenta färger. |
| [createGrayscale(int bits)](#createGrayscale-int-) | Hämtar gråskalepaletten för angivet antal bitar. |
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Skapar en monokrom färgpalett som endast innehåller 2 färger.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Color palette for monochrome images.
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


Skapar 4-bitars färgpaletten.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Skapar 4-bitars gråskala-palatset.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| minIsWhite | boolean | om den är satt till `true` börjar paletten med vit färg, annars börjar den med svart färg. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Skapar 8-bitars färgpaletten.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Skapar 8-bitars gråskala-palatset.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| minIsWhite | boolean | om den är satt till `true` börjar paletten med vit färg, annars börjar den med svart färg. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8 bit grayscale palette.

**Example: The following example creates a palettized grayscale BMP image and then saves it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.BmpOptions createOptions = new com.aspose.imaging.imageoptions.BmpOptions();

// Spara till en fil
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.palette8bit.bmp", false));

// Använd 8 bitar per pixel för att minska storleken på den genererade bilden.
createOptions.setBitsPerPixel(8);

// Ställ in den standard 8-bitars gråskala-färgpaletten som täcker alla gråskalefärger.
// Om den bearbetade bilden endast innehåller gråskalefärger, så är dess palettiserade version
// visuellt omöjlig att skilja från en icke-palettiserad.
createOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

// Spara utan komprimering.
// Du kan också använda RLE-8-komprimering för att minska storleken på den genererade bilden.
createOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

// Ställ in horisontell och vertikal upplösning till 96 dpi.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

// Skapa en BMP-bild på 100 x 100 px och spara den till en fil.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlack(),
            com.aspose.imaging.Color.getWhite());

    // Fyll bilden med ett gråskaleförlopp
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


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |
| entriesCount | int | Det önskade antalet poster. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Skapa en BMP-bild 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Den linjära gradienten från bildens övre vänstra till nedre högra hörn.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fyll hela bilden med den linjära gradientpenseln.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Hämta den närmaste 8-bitars färgpaletten som täcker så många pixlar som möjligt, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palettiserad.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // 8-bitars palett innehåller högst 256 färger.
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

// Utdata ser ut så här:
// Den palettiserade bildstorleken är 11078 byte.
// Den icke-palettiserade bildstorleken är 40054 byte.
```

### getCloseTransparentImagePalette(RasterImage image, int entriesCount) {#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseTransparentImagePalette(RasterImage image, int entriesCount)
```


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |
| entriesCount | int | Det önskade antalet poster. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)
```


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Paletten kommer att optimeras för bättre indexerad bildkvalitet eller tas "AS IS" när PaletteMiningMethod.UseCurrentPalette används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |
| entriesCount | int | Det önskade antalet poster. |
| paletteMiningMethod | int | Palettutvinningsmetoden. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Läser in png-bild        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Använd indexerad färgtyp
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Använd maximal kompression
    options.setCompressionLevel(9);
    // Hämta den närmaste 8-bitars färgpaletten som täcker så många pixlar som möjligt, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palettiserad.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Utdatafilens storlek bör minskas avsevärt
```

### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Målbildernas gränser. |
| entriesCount | int | Det önskade antalet poster. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Målbildernas gränser. |
| entriesCount | int | Det önskade antalet poster. |
| useImagePalette | boolean | Om den är satt kommer den att använda sin egen bildpalett om den finns tillgänglig |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)
```


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Målbildernas gränser. |
| entriesCount | int | Det önskade antalet poster. |
| useImagePalette | boolean | Om den är satt kommer den att använda sin egen bildpalett om den finns tillgänglig |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Färgen som ska användas som bakgrundsfärg för halvtransparent alfa‑ersättning. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)
```


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Målbildernas gränser. |
| entriesCount | int | Det önskade antalet poster. |
| useImagePalette | boolean | Om den är satt kommer den att använda sin egen bildpalett om den finns tillgänglig |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Färgen som ska användas som bakgrundsfärg för halvtransparent alfa‑ersättning. |
| keepTransparency | boolean | Om den är satt kommer den att beakta alfakanalens bitar i bildens färger. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Hämta enhetlig 256-färgspalett.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Hämta 256-färgspalett, sammansatt av de övre bitarna i bildens ursprungliga färgvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.imaging.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Avgör om den angivna paletten har transparenta färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten. |

**Returns:**
boolean - `true` om den angivna paletten har transparenta färger; annars `false`.
### createGrayscale(int bits) {#createGrayscale-int-}
```
public static IColorPalette createGrayscale(int bits)
```


Hämtar gråskalepaletten för angivet antal bitar. Tillåtna bitvärden är 1, 2, 4, 8.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bits | int | Antalet bitar. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Grayscale palette.
