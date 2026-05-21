---
title: "RasterCachedMultipageImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'image raster multipage"
type: docs
weight: 90
url: /fr/java/com.aspose.imaging/rastercachedmultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class RasterCachedMultipageImage extends RasterCachedImage implements IMultipageImage
```

L'image raster multipage
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [isCached()](#isCached--) | Obtient une valeur indiquant si les données d'image sont actuellement mises en cache. |
| [hasAlpha()](#hasAlpha--) | Obtient une valeur indiquant si cette instance possède de l'alpha. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| [getImageOpacity()](#getImageOpacity--) | Obtient l'opacité de cette image. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient une valeur pour la couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Définit une valeur pour la couleur d'arrière-plan. |
| [getMetadata()](#getMetadata--) | Obtient les données XMP de la trame. |
| [getPageExportingAction()](#getPageExportingAction--) | Obtient l'action d'exportation de la page. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Définit l'action d'exportation de la page. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajustement de la `brightness` d'une image. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) contrastant |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correction gamma d'une image. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correction gamma d'une image. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mélange cette instance d'image avec l'image `overlay`. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Intègre une signature numérique basée sur le mot de passe fourni dans chaque page de l'image. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Calcule le pourcentage de similarité entre les données extraites et le mot de passe original. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Effectue une vérification rapide pour déterminer si l'image est signée numériquement, en utilisant le mot de passe fourni et le seuil. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisation d'une image avec un seuil prédéfini |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisation d'une image avec le seuillage d'Otsu |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadrage de l'image. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Recadre l'image avec des décalages. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Effectue le tramage sur l'image actuelle. |
| [grayscale()](#grayscale--) | Transformation d'une image en sa représentation en niveaux de gris |
| [normalizeHistogram()](#normalizeHistogram--) | Normalise l'histogramme de l'image \\u2014 ajuste les valeurs des pixels pour utiliser toute la plage disponible. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` l'image autour du centre. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Fait pivoter, retourner ou faire pivoter et retourner toutes les pages. |
| [rotateFlipAll(int rotateFlip)](#rotateFlipAll-int-) | Fait pivoter le retournement de tout. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne l'image. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Redimensionne la largeur proportionnellement. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Redimensionne la largeur proportionnellement. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtre le rectangle spécifié. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normalise l'angle. |
| [cacheData()](#cacheData--) | Met en cache les données privées. |

## Example: The following example shows batch conversion before saving (exporting) Tiff images.

``` java
String fileName = "10MB_Tif.tif";
String inputFileName = fileName;

String outputFileNameTif = "output.tif";

//La possibilité de conversion par lots avant l'enregistrement (exportation) des images Tiff est implémentée.

try(com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(inputFileName))
{
    // Définit l'opération par lots pour les pages
    tiffImage.setPageExportingAction(new PageExportingAction()
    {
        @Override
        public void invoke(int pageIndex, Image page)
        {
            // Déclenche la collecte des déchets pour éviter le stockage inutile de déchets provenant des pages précédentes
            System.gc();

            ((com.aspose.imaging.RasterImage) page).rotate(90);
        }
    });

    tiffImage.save(outputFileNameTif);

    /* Attention! In batch mode all pages will be released in this line!
     If you want to further perform operations on the original image, you should reload it from the source to another instance. */
}
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de l'image.

Valeur : la hauteur de l'image.

**Returns:**
int - la hauteur de l'image.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de l'image.

Valeur : la largeur de l'image.

**Returns:**
int - la largeur de l'image.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

Valeur : le nombre de bits par pixel de l'image.

**Returns:**
int - le nombre de bits par pixel de l'image.
### isCached() {#isCached--}
```
public boolean isCached()
```


Obtient une valeur indiquant si les données d'image sont actuellement mises en cache.

Valeur : `true` si les données de l'image sont en cache ; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si les données de l'image sont actuellement en cache.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtient une valeur indiquant si cette instance possède de l'alpha.

Valeur : `true` si cette instance possède un canal alpha ; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si cette instance possède un canal alpha.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtient une valeur indiquant si l'image possède une couleur transparente.

--------------------

Cette implémentation vérifie la valeur `RasterImage.HasTransparentColor`([RasterImage.hasTransparentColor](../../com.aspose.imaging/rasterimage\#hasTransparentColor)/[RasterImage.setTransparentColor(boolean)](../../com.aspose.imaging/rasterimage\#setTransparentColor-boolean-)) de la `DefaultPage`(\#getDefaultPage\_internalized.getDefaultPage\_internalized).

**Returns:**
booléen - une valeur indiquant si l'image possède une couleur transparente.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Obtient l'opacité de cette image.

Valeur : la valeur d'opacité entre 0,0 (totalement transparent) et 1,0 (totalement opaque).

**Returns:**
float - opacité de cette image.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient une valeur pour la couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Définit une valeur pour la couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | une valeur pour la couleur d'arrière-plan. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Obtient les données XMP de la trame.

Valeur : enveloppe de données du paquet XMP

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - XMP data from frame.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Obtient l'action d'exportation de la page. Veuillez noter que la définition de cette méthode libérera automatiquement les ressources de la page après son exécution. Elle sera exécutée juste avant que chaque page ne soit enregistrée.

Valeur : l'action d'exportation de la page.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Définit l'action d'exportation de la page. Veuillez noter que la définition de cette méthode libérera automatiquement les ressources de la page après son exécution. Elle sera exécutée juste avant que chaque page ne soit enregistrée.

Valeur : l'action d'exportation de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | l'action d'exportation de la page. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajustement de la `brightness` d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | int | Valeur de luminosité. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contrast | float | Valeur de contraste (dans la plage [-100 ; 100]) |

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

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Correction gamma d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |

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

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Intègre une signature numérique basée sur le mot de passe fourni dans chaque page de l'image.

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

--------------------

En raison des images multipages, le résultat représente le `MIDDLE AVERAGED signing percentage` calculé

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

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | java.lang.String | Le mot de passe pour vérifier la signature. |
|  | percentageThreshold | int | Le seuil (en pourcentage)[0-100] qui détermine si l'image est considérée comme signée. Si non spécifié, un seuil par défaut (`75`) sera appliqué. |

--------------------

Cette méthode fournit la détection la plus rapide en utilisant `GetSignPercentage`. Une fois que les données extraites atteignent le seuil spécifié, les étapes d'extraction supplémentaires visant à améliorer la précision de la détection sont ignorées.

Le résultat est `true` uniquement si toutes les pages de l'image multipage sont reconnues comme signées ; sinon, l'image est considérée comme non signée. |

**Returns:**
boolean - Vrai si l'image est signée, sinon faux.
### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisation d'une image avec un seuil prédéfini

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |

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

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisation d'une image avec le seuillage d'Otsu

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadrage de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Recadre l'image avec des décalages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftShift | int | Le décalage gauche. |
| rightShift | int | Le décalage droit. |
| topShift | int | Le décalage supérieur. |
| bottomShift | int | Le décalage inférieur. |

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

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Normalise l'histogramme de l'image \\u2014 ajuste les valeurs des pixels pour utiliser toute la plage disponible.

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`RasterCachedMultipageImage.rotate` l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resizeProportionally | boolean | si défini sur `true` vous verrez la taille de votre image modifiée selon les projections du rectangle tourné (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul `` le contenu de l'image est tourné. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Fait pivoter, retourner ou faire pivoter et retourner toutes les pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de rotation/retournement. |

### rotateFlipAll(int rotateFlip) {#rotateFlipAll-int-}
```
public void rotateFlipAll(int rotateFlip)
```


Fait pivoter le retournement de tout.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlip | int | Le retournement de rotation. |

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

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Redimensionne la largeur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| resizeType | int | Type de redimensionnement. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Redimensionne la largeur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Type de redimensionnement. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldColorArgb | int | Valeur ARGB de l'ancienne couleur à remplacer. |
| oldColorDiff | byte | Différence autorisée dans l'ancienne couleur pour pouvoir élargir la teinte de couleur remplacée. |
| newColorArgb | int | Nouvelle valeur ARGB de couleur pour remplacer l'ancienne couleur. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Remplace toutes les couleurs non transparentes par la nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorArgb | int | Nouvelle valeur ARGB de couleur pour remplacer les couleurs non transparentes. |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtre le rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Les options. |

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation inclinée. Cette méthode utilise les méthodes [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) et [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resizeProportionally | boolean | si défini sur `true`, la taille de votre image sera modifiée selon les projections du rectangle pivoté (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul le contenu interne de l'image est pivoté. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Met en cache les données privées.

