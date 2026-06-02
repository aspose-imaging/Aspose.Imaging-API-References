---
title: "PaletteMiningMethod"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il metodo di estrazione della tavolozza dell'immagine"
type: docs
weight: 79
url: /it/java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

Il metodo di estrazione della tavolozza dell'immagine
## Campi

| Campo | Descrizione |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | Usa la tavolozza esistente dell'immagine |
| [ColorClustering](#ColorClustering) | Il metodo di clustering dei colori |
| [Histogram](#Histogram) | Il metodo dell'istogramma |

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

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


Usa la tavolozza esistente dell'immagine

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


Il metodo di clustering dei colori

### Histogram {#Histogram}
```
public static final int Histogram
```


Il metodo dell'istogramma

