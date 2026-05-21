---
title: "PngColorType"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar PNG-bildens färgtyp."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

Representerar PNG-bildens färgtyp.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Grayscale](#Grayscale) | Representerar färgtypen där varje pixel är ett gråskaleprov. |
| [Truecolor](#Truecolor) | Representerar färgtypen där varje pixel är en R,G,B-trippel. |
| [IndexedColor](#IndexedColor) | Representerar färgtypen där varje pixel är ett palettindex; ett PLTE‑chunk ska förekomma. |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | Representerar färgtypen där varje pixel är ett gråskaleprov följt av ett alfablock. |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | Representerar färgtypen där varje pixel är en R,G,B-trippel följt av ett alfablock. |

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

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Representerar färgtypen där varje pixel är ett gråskaleprov.

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


Representerar färgtypen där varje pixel är en R,G,B-trippel.

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


Representerar färgtypen där varje pixel är ett palettindex; ett PLTE‑chunk ska förekomma.

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


Representerar färgtypen där varje pixel är ett gråskaleprov följt av ett alfablock.

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


Representerar färgtypen där varje pixel är en R,G,B-trippel följt av ett alfablock.

