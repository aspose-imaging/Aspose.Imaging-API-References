---
title: "PaletteMiningMethod"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La méthode d'extraction de la palette d'images"
type: docs
weight: 79
url: /fr/java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

La méthode d'extraction de la palette d'images
## Champs

| Champ | Description |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | Utiliser la palette existante de l'image |
| [ColorClustering](#ColorClustering) | La méthode de regroupement de couleurs |
| [Histogram](#Histogram) | La méthode d'histogramme |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

``` java

// Charge l'image png        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Utiliser le type de couleur indexée
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Utiliser une compression maximale
    options.setCompressionLevel(9);
    // Obtenir la palette de couleurs 8 bits la plus proche qui couvre le plus grand nombre de pixels possible, afin qu'une image palettisée
    // soit presque visuellement indiscernable d'une image non palettisée.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// La taille du fichier de sortie devrait être considérablement réduite
```

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


Utiliser la palette existante de l'image

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


La méthode de regroupement de couleurs

### Histogram {#Histogram}
```
public static final int Histogram
```


La méthode d'histogramme

