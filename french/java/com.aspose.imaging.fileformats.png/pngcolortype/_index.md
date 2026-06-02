---
title: "PngColorType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente le type de couleur de l'image PNG."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

Représente le type de couleur de l'image PNG.
## Champs

| Champ | Description |
| --- | --- |
| [Grayscale](#Grayscale) | Représente le type de couleur où chaque pixel est un échantillon en niveaux de gris. |
| [Truecolor](#Truecolor) | Représente le type de couleur où chaque pixel est un triplet R,G,B. |
| [IndexedColor](#IndexedColor) | Représente le type de couleur où chaque pixel est un indice de palette ; un bloc PLTE doit apparaître. |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | Représente le type de couleur où chaque pixel est un échantillon en niveaux de gris suivi d'un échantillon alpha. |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | Représente le type de couleur où chaque pixel est un triplet R,G,B suivi d'un échantillon alpha. |

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

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Représente le type de couleur où chaque pixel est un échantillon en niveaux de gris.

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


Représente le type de couleur où chaque pixel est un triplet R,G,B.

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


Représente le type de couleur où chaque pixel est un indice de palette ; un bloc PLTE doit apparaître.

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


Représente le type de couleur où chaque pixel est un échantillon en niveaux de gris suivi d'un échantillon alpha.

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


Représente le type de couleur où chaque pixel est un triplet R,G,B suivi d'un échantillon alpha.

