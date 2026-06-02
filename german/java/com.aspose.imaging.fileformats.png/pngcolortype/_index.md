---
title: "PngColorType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt den PNG-Bildfarbtyp dar."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

Stellt den PNG-Bildfarbtyp dar.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Grayscale](#Grayscale) | Stellt den Farbtyp dar, bei dem jedes Pixel eine Graustufenprobe ist. |
| [Truecolor](#Truecolor) | Stellt den Farbtyp dar, bei dem jedes Pixel ein R,G,B‑Tripel ist. |
| [IndexedColor](#IndexedColor) | Stellt den Farbtyp dar, bei dem jedes Pixel ein Palettenindex ist; ein PLTE‑Chunk muss erscheinen. |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | Stellt den Farbtyp dar, bei dem jedes Pixel eine Graustufenprobe gefolgt von einer Alpha‑Probe ist. |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | Stellt den Farbtyp dar, bei dem jedes Pixel ein R,G,B‑Tripel gefolgt von einer Alpha‑Probe ist. |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

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

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Stellt den Farbtyp dar, bei dem jedes Pixel eine Graustufenprobe ist.

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


Stellt den Farbtyp dar, bei dem jedes Pixel ein R,G,B‑Tripel ist.

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


Stellt den Farbtyp dar, bei dem jedes Pixel ein Palettenindex ist; ein PLTE‑Chunk muss erscheinen.

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


Stellt den Farbtyp dar, bei dem jedes Pixel eine Graustufenprobe gefolgt von einer Alpha‑Probe ist.

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


Stellt den Farbtyp dar, bei dem jedes Pixel ein R,G,B‑Tripel gefolgt von einer Alpha‑Probe ist.

