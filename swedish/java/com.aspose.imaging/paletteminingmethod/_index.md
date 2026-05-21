---
title: "PaletteMiningMethod"
second_title: "Aspose.Imaging för Java API-referens"
description: "Metoden för bildpalettutvinning."
type: docs
weight: 79
url: /sv/java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

Metoden för bildpalettutvinning.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | Använd befintlig palett från bilden. |
| [ColorClustering](#ColorClustering) | Färgklustringsmetoden. |
| [Histogram](#Histogram) | Histogrammetoden. |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

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

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


Använd befintlig palett från bilden.

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


Färgklustringsmetoden.

### Histogram {#Histogram}
```
public static final int Histogram
```


Histogrammetoden.

