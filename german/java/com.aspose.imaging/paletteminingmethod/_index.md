---
title: "PaletteMiningMethod"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Bildpaletten-Abbaumethode"
type: docs
weight: 79
url: /de/java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

Die Bildpaletten-Abbaumethode
## Felder

| Feld | Beschreibung |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | Verwende die vorhandene Palette des Bildes |
| [ColorClustering](#ColorClustering) | Die Farb‑Cluster‑Methode |
| [Histogram](#Histogram) | Die Histogramm‑Methode |

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

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


Verwende die vorhandene Palette des Bildes

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


Die Farb‑Cluster‑Methode

### Histogram {#Histogram}
```
public static final int Histogram
```


Die Histogramm‑Methode

