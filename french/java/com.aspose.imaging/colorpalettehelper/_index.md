---
title: "ColorPaletteHelper"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe d'aide pour la manipulation de la palette de couleurs."
type: docs
weight: 29
url: /fr/java/com.aspose.imaging/colorpalettehelper/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Classe d'aide pour la manipulation de la palette de couleurs.
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMonochrome()](#createMonochrome--) | Crée une palette de couleurs monochrome contenant uniquement 2 couleurs. |
| [create4Bit()](#create4Bit--) | Crée la palette de couleurs 4 bits. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Crée la palette de niveaux de gris 4 bits. |
| [create8Bit()](#create8Bit--) | Crée la palette de couleurs 8 bits. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Crée la palette de niveaux de gris 8 bits. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-) | Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. |
| [getCloseTransparentImagePalette(RasterImage image, int entriesCount)](#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-) | Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. |
| [getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-) | Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-) | Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-) | Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-) | Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-) | Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.imaging.RasterImage-) | Obtenir une palette de couleurs uniforme de 256 couleurs. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.imaging.RasterImage-) | Obtenir une palette de 256 couleurs, composée des bits supérieurs des valeurs de couleur de l'image initiale. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.imaging.IColorPalette-) | Détermine si la palette spécifiée possède des couleurs transparentes. |
| [createGrayscale(int bits)](#createGrayscale-int-) | Obtient la palette de niveaux de gris du nombre de bits spécifié. |
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Crée une palette de couleurs monochrome contenant uniquement 2 couleurs.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Color palette for monochrome images.
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


Crée la palette de couleurs 4 bits.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Crée la palette de niveaux de gris 4 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| minIsWhite | boolean | si elle est définie sur `true`, la palette commence avec la couleur blanche, sinon elle commence avec la couleur noire. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Crée la palette de couleurs 8 bits.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Crée la palette de niveaux de gris 8 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| minIsWhite | boolean | si elle est définie sur `true`, la palette commence avec la couleur blanche, sinon elle commence avec la couleur noire. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8 bit grayscale palette.

**Example: The following example creates a palettized grayscale BMP image and then saves it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.BmpOptions createOptions = new com.aspose.imaging.imageoptions.BmpOptions();

// Enregistrer dans un fichier
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.palette8bit.bmp", false));

// Utilisez 8 bits par pixel pour réduire la taille de l'image de sortie.
createOptions.setBitsPerPixel(8);

// Définissez la palette de couleurs de niveaux de gris standard 8 bits qui couvre toutes les couleurs de gris.
// Si l'image traitée ne contient que des couleurs de gris, alors sa version palettisée
// est visuellement indiscernable d'une version non palettisée.
createOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

// Enregistrer sans compression.
// Vous pouvez également utiliser la compression RLE-8 pour réduire la taille de l'image de sortie.
createOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

// Définissez la résolution horizontale et verticale à 96 dpi.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

// Créez une image BMP de 100 x 100 px et enregistrez-la dans un fichier.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlack(),
            com.aspose.imaging.Color.getWhite());

    // Remplissez l'image avec un dégradé de gris
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


Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |
| entriesCount | int | Le nombre d'entrées souhaité. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Créer une image BMP de 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Remplir toute l'image avec le pinceau de dégradé linéaire.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Obtenir la palette de couleurs 8 bits la plus proche qui couvre le plus grand nombre de pixels possible, afin qu'une image palettisée
    // soit presque visuellement indiscernable d'une image non palettisée.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // Une palette 8 bits contient au maximum 256 couleurs.
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

// Le résultat ressemble à ceci :
// La taille de l'image palettisée est de 11078 octets.
// La taille de l'image non palettisée est de 40054 octets.
```

### getCloseTransparentImagePalette(RasterImage image, int entriesCount) {#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseTransparentImagePalette(RasterImage image, int entriesCount)
```


Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |
| entriesCount | int | Le nombre d'entrées souhaité. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)
```


Obtient la palette de couleurs à partir d'une image raster (palettise l'image) au cas où l'image n'en possède pas. La palette est sur le point d'être optimisée pour une meilleure qualité d'image indexée ou prise "AS IS" lorsque PaletteMiningMethod.UseCurrentPalette est utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |
| entriesCount | int | Le nombre d'entrées souhaité. |
| paletteMiningMethod | int | La méthode d'extraction de palette. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

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

### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'image de destination. |
| entriesCount | int | Le nombre d'entrées souhaité. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'image de destination. |
| entriesCount | int | Le nombre d'entrées souhaité. |
| useImagePalette | boolean | Si défini, il utilisera sa propre palette d'image si disponible |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)
```


Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'image de destination. |
| entriesCount | int | Le nombre d'entrées souhaité. |
| useImagePalette | boolean | Si défini, il utilisera sa propre palette d'image si disponible |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | La couleur qui doit être utilisée comme couleur d'arrière-plan pour le remplacement alpha semi-transparent. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)
```


Obtient la palette de couleurs à partir d'une image raster (palletise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'image de destination. |
| entriesCount | int | Le nombre d'entrées souhaité. |
| useImagePalette | boolean | Si défini, il utilisera sa propre palette d'image si disponible |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | La couleur qui doit être utilisée comme couleur d'arrière-plan pour le remplacement alpha semi-transparent. |
| keepTransparency | boolean | Si défini, il prendra en compte les bits du canal alpha des couleurs de l'image. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Obtenir une palette de couleurs uniforme de 256 couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Obtenir une palette de 256 couleurs, composée des bits supérieurs des valeurs de couleur de l'image initiale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.imaging.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Détermine si la palette spécifiée possède des couleurs transparentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette. |

**Returns:**
booléen - `true` si la palette spécifiée possède des couleurs transparentes ; sinon, `false`.
### createGrayscale(int bits) {#createGrayscale-int-}
```
public static IColorPalette createGrayscale(int bits)
```


Obtient la palette de niveaux de gris du nombre de bits spécifié. Les valeurs de bits autorisées sont 1, 2, 4, 8.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bits | int | Le nombre de bits. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Grayscale palette.
