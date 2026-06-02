---
title: "ColorPaletteHelper"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Hilfsklasse zur Manipulation von Farbpaletten."
type: docs
weight: 29
url: /de/java/com.aspose.imaging/colorpalettehelper/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Hilfsklasse zur Manipulation von Farbpaletten.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMonochrome()](#createMonochrome--) | Erstellt eine monochrome Farbpalette, die nur 2 Farben enthält. |
| [create4Bit()](#create4Bit--) | Erstellt die 4‑Bit‑Farbpalette. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Erstellt die 4‑Bit‑Graustufenpalette. |
| [create8Bit()](#create8Bit--) | Erstellt die 8‑Bit‑Farbpalette. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Erstellt die 8‑Bit‑Graustufenpalette. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getCloseTransparentImagePalette(RasterImage image, int entriesCount)](#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.imaging.RasterImage-) | Erhalte eine einheitliche 256‑Farben‑Palette. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.imaging.RasterImage-) | Erhalte eine 256‑Farben‑Palette, die aus den oberen Bits der ursprünglichen Bildfarbwerte besteht. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.imaging.IColorPalette-) | Bestimmt, ob die angegebene Palette transparente Farben enthält. |
| [createGrayscale(int bits)](#createGrayscale-int-) | Ermittelt die Graustufenpalette der angegebenen Bitanzahl. |
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Erstellt eine monochrome Farbpalette, die nur 2 Farben enthält.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Color palette for monochrome images.
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


Erstellt die 4‑Bit‑Farbpalette.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Erstellt die 4‑Bit‑Graustufenpalette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| minIsWhite | boolean | Wenn auf `true` gesetzt, beginnt die Palette mit Weiß, andernfalls beginnt sie mit Schwarz. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Erstellt die 8‑Bit‑Farbpalette.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Erstellt die 8‑Bit‑Graustufenpalette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| minIsWhite | boolean | Wenn auf `true` gesetzt, beginnt die Palette mit Weiß, andernfalls beginnt sie mit Schwarz. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8 bit grayscale palette.

**Example: The following example creates a palettized grayscale BMP image and then saves it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.BmpOptions createOptions = new com.aspose.imaging.imageoptions.BmpOptions();

// In einer Datei speichern.
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.palette8bit.bmp", false));

// Verwende 8 Bit pro Pixel, um die Größe des Ausgabebildes zu reduzieren.
createOptions.setBitsPerPixel(8);

// Setze die Standard‑8‑Bit‑Graustufen‑Farbpalette, die alle Graustufen abdeckt.
// Wenn das verarbeitete Bild nur Graustufen enthält, dann ist seine palettisierte Version
// visuell nicht von einer nicht palettisierten zu unterscheiden.
createOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

// Ohne Kompression speichern.
// Sie können auch RLE‑8‑Kompression verwenden, um die Größe des Ausgabebildes zu reduzieren.
createOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

// Setze die horizontale und vertikale Auflösung auf 96 dpi.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

// Erstelle ein BMP‑Bild von 100 × 100 px und speichere es in einer Datei.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlack(),
            com.aspose.imaging.Color.getWhite());

    // Fülle das Bild mit einem Graustufen‑Verlauf
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


Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |
| entriesCount | int | Die gewünschte Eintragsanzahl. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Erstelle ein BMP-Bild mit 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fülle das gesamte Bild mit dem linearen Farbverlaufs-Pinsel.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Erhalte die nächstgelegene 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, sodass ein palettisiertes Bild
    // fast visuell nicht von einem nicht palettierten Bild zu unterscheiden ist.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // Eine 8-Bit-Palette enthält höchstens 256 Farben.
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

// Die Ausgabe sieht folgendermaßen aus:
// Die palettierte Bildgröße beträgt 11078 Bytes.
// Die nicht-palettierte Bildgröße beträgt 40054 Bytes.
```

### getCloseTransparentImagePalette(RasterImage image, int entriesCount) {#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseTransparentImagePalette(RasterImage image, int entriesCount)
```


Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |
| entriesCount | int | Die gewünschte Eintragsanzahl. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)
```


Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Die Palette wird optimiert, um eine bessere indizierte Bildqualität zu erzielen, oder wird "AS IS" übernommen, wenn PaletteMiningMethod.UseCurrentPalette verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |
| entriesCount | int | Die gewünschte Eintragsanzahl. |
| paletteMiningMethod | int | Die Palette-Mining-Methode. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Lädt PNG-Bild
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Indizierten Farbtyp verwenden
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Maximale Kompression verwenden
    options.setCompressionLevel(9);
    // Erhalte die nächstgelegene 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, sodass ein palettisiertes Bild
    // fast visuell nicht von einem nicht palettierten Bild zu unterscheiden ist.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Die Größe der Ausgabedatei sollte deutlich reduziert werden
```

### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen des Zielbildes. |
| entriesCount | int | Die gewünschte Eintragsanzahl. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen des Zielbildes. |
| entriesCount | int | Die gewünschte Eintragsanzahl. |
| useImagePalette | boolean | Wenn gesetzt, wird es seine eigene Bildpalette verwenden, falls verfügbar |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)
```


Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen des Zielbildes. |
| entriesCount | int | Die gewünschte Eintragsanzahl. |
| useImagePalette | boolean | Wenn gesetzt, wird es seine eigene Bildpalette verwenden, falls verfügbar |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Die Farbe, die als Hintergrundfarbe für halbtransparente Alpha-Ersetzung verwendet werden soll. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)
```


Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen des Zielbildes. |
| entriesCount | int | Die gewünschte Eintragsanzahl. |
| useImagePalette | boolean | Wenn gesetzt, wird es seine eigene Bildpalette verwenden, falls verfügbar |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Die Farbe, die als Hintergrundfarbe für halbtransparente Alpha-Ersetzung verwendet werden soll. |
| keepTransparency | boolean | Wenn gesetzt, werden die Alpha-Kanal-Bits der Bildfarben berücksichtigt. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Erhalte eine einheitliche 256‑Farben‑Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Erhalte eine 256‑Farben‑Palette, die aus den oberen Bits der ursprünglichen Bildfarbwerte besteht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.imaging.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Bestimmt, ob die angegebene Palette transparente Farben enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Palette. |

**Returns:**
boolesch - `true`, wenn die angegebene Palette transparente Farben enthält; andernfalls `false`.
### createGrayscale(int bits) {#createGrayscale-int-}
```
public static IColorPalette createGrayscale(int bits)
```


Liest die Graustufenpalette der angegebenen Bitanzahl. Erlaubte Bitwerte sind 1, 2, 4, 8.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bits | int | Die Bitanzahl. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Grayscale palette.
