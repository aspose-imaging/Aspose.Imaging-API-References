---
title: "RasterCachedImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une image raster prenant en charge les opérations graphiques raster."
type: docs
weight: 89
url: /fr/java/com.aspose.imaging/rastercachedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

Représente une image raster prenant en charge les opérations graphiques raster. Cette image met en cache les données de pixels lorsque cela est nécessaire.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isCached()](#isCached--) | Obtient une valeur indiquant si les données d'image sont actuellement mises en cache. |
| [cacheData()](#cacheData--) | Met en cache les données et garantit qu'aucun chargement supplémentaire ne sera effectué à partir du `DataStreamSupporter.DataStreamContainer` sous-jacent. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mélange cette instance d'image avec l'image `overlay`. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne l'image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Fait pivoter, retourner, ou pivoter et retourner l'image. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Faire pivoter l'image autour du centre. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadrage de l'image. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Effectue le tramage sur l'image actuelle. |
| [grayscale()](#grayscale--) | Transformation d'une image en sa représentation en niveaux de gris |
| [normalizeHistogram()](#normalizeHistogram--) | Normalise l'histogramme de l'image \\u2014 ajuste les valeurs des pixels pour utiliser toute la plage disponible. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Effectue une normalisation automatique adaptative de la luminosité et du contraste pour l'ensemble de l'image. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisation d'une image avec un seuil prédéfini |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisation d'une image avec le seuillage d'Otsu |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajustement de la luminosité d'une image. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contraste d'image |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correction gamma d'une image. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correction gamma d'une image. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Intégrer une signature numérique basée sur le mot de passe fourni dans l'image en utilisant la stéganographie. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Calcule le pourcentage de similarité entre les données extraites et le mot de passe original. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Effectue une vérification rapide pour déterminer si l'image est signée numériquement, en utilisant le mot de passe fourni et le seuil. |

## Example: The following example transforms a colored raster cached image to its grayscale representation.
L'exemple suivant transforme une image raster couleur mise en cache en sa représentation en niveaux de gris. Les images en niveaux de gris sont composées exclusivement de nuances de gris et ne contiennent que des informations d'intensité.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### isCached() {#isCached--}
```
public boolean isCached()
```


Obtient une valeur indiquant si les données d'image sont actuellement mises en cache.

**Returns:**
booléen - `true` si les données de l'image sont mises en cache ; sinon, `false`.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Met en cache les données et garantit qu'aucun chargement supplémentaire ne sera effectué à partir du `DataStreamSupporter.DataStreamContainer` sous-jacent.


**Example: The following example shows how raster image caching affects performance.**
L'exemple suivant montre comment la mise en cache d'images raster affecte les performances. Dans le cas général, la lecture des données mises en cache est plus rapide que la lecture des données non mises en cache.
``` java
String dir = "c:\\temp\\";

// Chargez une image à partir d'un fichier PNG.
com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Mettez en cache toutes les données de pixels afin qu'aucun chargement supplémentaire ne soit effectué à partir du flux de données sous-jacent
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Lire tous les pixels est assez rapide.
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// Charger une image à partir d'un fichier PNG
image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Lire tous les pixels n'est pas aussi rapide qu'avec la mise en cache
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
//La lecture de tous les pixels mis en cache a pris 2923 ms.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//at com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:54)
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Mélange cette instance d'image avec l'image `overlay`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine du mélange de l'image d'arrière-plan. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image de superposition. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | La zone de superposition. |
| overlayAlpha | byte | L'alpha de superposition. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |


**Example: This example loads a raster cached image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement. |


**Example: This example loads a raster cached image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// L'algorithme adaptatif basé sur une fonction rationnelle pondérée et mélangée et l'interpolation lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Le petit filtre rectangulaire
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Le nombre de couleurs dans la palette.
resizeSettings.setEntriesCount(256);

// La quantification des couleurs n'est pas utilisée
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// La méthode euclidienne
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Réduisez de 2 fois en utilisant le rééchantillonnage adaptatif.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Fait pivoter, retourner, ou pivoter et retourner l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de retournement rotatif. |


**Example: This example loads a raster cached image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Ceci est une classe d'assistance.
class LocalHelper {
    // Obtient une représentation sous forme de chaîne du type de retournement rotatif.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// Voici l'exemple principal
int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

LocalHelper localHelper = new LocalHelper();
for (int rotateFlipType : rotateFlipTypes) {
    // Faites pivoter, retournez et enregistrez dans le fichier de sortie.
    com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + localHelper.rotateFlipTypeToString(rotateFlipType) + ".bmp");
    } finally {
        image.dispose();
    }
}
```

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Faire pivoter l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resizeProportionally | boolean | si défini sur `true`, la taille de votre image sera modifiée selon les projections du rectangle pivoté (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul le contenu interne de l'image est pivoté. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadrage de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |


**Example: The following example crops a raster cached image.**
L'exemple suivant recadre une image mise en cache raster. La zone de recadrage doit être spécifiée via com.aspose.imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Recadrez l'image. La zone de recadrage est la zone centrale rectangulaire de l'image.
    int width = rasterImage.getWidth();
    int height = rasterImage.getHeight();
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(width / 4, height / 4, width / 2, height / 2);
    rasterImage.crop(area);

    // Enregistrez l'image recadrée au format PNG
    rasterImage.save(dir + "sample.Crop.png");
} finally {
    image.dispose();
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Effectue le tramage sur l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personnalisée pour le tramage. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation d'une image en sa représentation en niveaux de gris


**Example: The following example transforms a colored raster cached image to its grayscale representation.**
L'exemple suivant transforme une image raster couleur mise en cache en sa représentation en niveaux de gris. Les images en niveaux de gris sont composées exclusivement de nuances de gris et ne contiennent que des informations d'intensité.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Normalise l'histogramme de l'image \\u2014 ajuste les valeurs des pixels pour utiliser toute la plage disponible.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


Effectue une normalisation automatique adaptative de la luminosité et du contraste pour l'ensemble de l'image.

--------------------

> ```
> // Example usage in image pre-processing:
>  image.AutoBrightnessContrast();
> ```

--------------------

Cette méthode applique un pipeline de filtres adaptatifs avancés (CLAHE, étirement blanc adaptatif et balance des blancs automatique) pour améliorer la qualité visuelle de l'image en renforçant le contraste, la luminosité locale et la fidélité des couleurs.

`**Filter pipeline:**`

1.  Égalisation d'histogramme adaptative à contraste limité (CLAHE) \u2013 améliore le contraste local et renforce les détails faibles.
2.  Étirement blanc adaptatif \u2013 augmente le niveau blanc effectif tout en protégeant les zones sombres.
3.  Balance des blancs automatique \u2013 corrige les dominantes de couleur en équilibrant les histogrammes des canaux.

`**Note:**`

 *  
 *  

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisation d'une image avec un seuil prédéfini

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |


**Example: The following example binarizes a raster cached image with the predefined threshold.**
L'exemple suivant binarise une image mise en cache raster avec le seuil prédéfini. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binarisez l'image avec une valeur de seuil de 127.
    // Si la valeur de gris correspondante d'un pixel est supérieure à 127, une valeur de 255 lui sera attribuée, sinon 0.
    rasterImage.binarizeFixed((byte) 127);
    rasterImage.save(dir + "sample.BinarizeFixed.png");
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisation d'une image avec le seuillage d'Otsu


**Example: The following example binarizes a raster cached image with Otsu thresholding.**
L'exemple suivant binarise une image raster mise en cache avec le seuillage d'Otsu. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binarisez l'image avec le seuillage d'Otsu.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |
| windowSize | int | La taille de la fenêtre de s × s pixels centrée sur ce pixel |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm with the specified window size.**
L'exemple suivant binarise une image raster mise en cache avec l'algorithme de seuillage adaptatif de Bradley avec la taille de fenêtre spécifiée. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binarisez l'image avec une différence de luminosité de 5.
    // La luminosité est une différence entre un pixel et la moyenne d'une fenêtre de 10 × 10 pixels centrée sur ce pixel.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm.**
L'exemple suivant binarise une image raster mise en cache avec l'algorithme de seuillage adaptatif de Bradley. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binarisez l'image avec une différence de luminosité de 5.
    // La luminosité est une différence entre un pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel.
    // La taille de la fenêtre sera calibrée automatiquement.
    rasterImage.binarizeBradley(5);
    rasterImage.save(dir + "sample.BinarizeBradley5.png");
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajustement de la luminosité d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | int | Valeur de luminosité. |


**Example: The following example performs brightness correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Définissez la valeur de luminosité. Les valeurs acceptées de luminosité sont dans la plage [-255, 255].
    rasterImage.adjustBrightness(50);
    rasterImage.save(dir + "sample.AdjustBrightness.png");
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Contraste d'image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contrast | float | Valeur de contraste (dans la plage [-100 ; 100]) |


**Example: The following example performs contrast correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Définissez la valeur de contraste. Les valeurs acceptées de contraste sont dans la plage [-100f, 100f].
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Correction gamma d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gammaRed | float | Coefficient gamma pour le canal rouge |
| gammaGreen | float | Coefficient gamma pour le canal vert |
| gammaBlue | float | Gamma pour le coefficient du canal bleu |


**Example: The following example performs gamma-correction of a raster cached image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Définir les coefficients gamma individuels pour les canaux rouge, vert et bleu.
    rasterImage.adjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Correction gamma d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |


**Example: The following example performs gamma-correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Définir le coefficient gamma pour les canaux rouge, vert et bleu.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Intégrer une signature numérique basée sur le mot de passe fourni dans l'image en utilisant la stéganographie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | java.lang.String | Le mot de passe utilisé pour générer les données de signature numérique |


**Example: The example shows how to embed digital signature based on provided password into image pixel data.**

``` java
String imageFilePath = "ball.png";
String password = "veryStr0ngPassword";
try (Image image = Image.load(imageFilePath))
{
    image.embedDigitalSignature(password);
    image.save(outputPath);
}
```

### analyzePercentageDigitalSignature(String password) {#analyzePercentageDigitalSignature-java.lang.String-}
```
public int analyzePercentageDigitalSignature(String password)
```


Calcule le pourcentage de similarité entre les données extraites et le mot de passe original.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | java.lang.String | Le mot de passe utilisé pour extraire les données incorporées. |

**Returns:**
int - La valeur de pourcentage de similarité.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Effectue une vérification rapide pour déterminer si l'image est signée numériquement, en utilisant le mot de passe fourni et le seuil.

--------------------

Cette méthode fournit la détection la plus rapide en utilisant `GetSignPercentage`. Une fois que les données extraites atteignent le seuil spécifié, les étapes d'extraction supplémentaires visant à améliorer la précision de la détection sont ignorées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | java.lang.String | Le mot de passe pour vérifier la signature. |
| percentageThreshold | int | Le seuil (en pourcentage)[0-100] qui détermine si l'image est considérée comme signée. Si non spécifié, un seuil par défaut (`75`) sera appliqué. |

**Returns:**
boolean - Vrai si l'image est signée, sinon faux.
