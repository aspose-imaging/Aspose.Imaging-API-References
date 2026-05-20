---
title: "PngColorType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta il tipo di colore dell'immagine PNG."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

Rappresenta il tipo di colore dell'immagine PNG.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Grayscale](#Grayscale) | Rappresenta il tipo di colore in cui ogni pixel è un campione in scala di grigi. |
| [Truecolor](#Truecolor) | Rappresenta il tipo di colore in cui ogni pixel è una tripla R,G,B. |
| [IndexedColor](#IndexedColor) | Rappresenta il tipo di colore in cui ogni pixel è un indice di palette; deve comparire un blocco PLTE. |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | Rappresenta il tipo di colore in cui ogni pixel è un campione in scala di grigi seguito da un campione alfa. |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | Rappresenta il tipo di colore in cui ogni pixel è una tripla R,G,B seguita da un campione alfa. |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

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

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Rappresenta il tipo di colore in cui ogni pixel è un campione in scala di grigi.

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


Rappresenta il tipo di colore in cui ogni pixel è una tripla R,G,B.

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


Rappresenta il tipo di colore in cui ogni pixel è un indice di palette; deve comparire un blocco PLTE.

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


Rappresenta il tipo di colore in cui ogni pixel è un campione in scala di grigi seguito da un campione alfa.

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


Rappresenta il tipo di colore in cui ogni pixel è una tripla R,G,B seguita da un campione alfa.

