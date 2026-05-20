---
title: "RasterImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une image raster prenant en charge les opérations graphiques raster."
type: docs
weight: 91
url: /fr/java/com.aspose.imaging/rasterimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver, [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver, IHasXmpData
```

Représente une image raster prenant en charge les opérations graphiques raster.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [getUseRawData()](#getUseRawData--) | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque le chargement de données brutes est disponible. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque le chargement de données brutes est disponible. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Obtient ou définit le convertisseur de couleur indexée |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Obtient ou définit le convertisseur de couleur indexée |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Obtient ou définit le convertisseur de couleur personnalisé |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-) | Obtient ou définit le convertisseur de couleur personnalisé |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [isUsePalette()](#isUsePalette--) | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| [getRawDataFormat()](#getRawDataFormat--) | Obtient le format des données brutes. |
| [getRawLineSize()](#getRawLineSize--) | Obtient la taille de ligne brute en octets. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Obtient une valeur indiquant si le chargement de données brutes est disponible. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | Obtient ou définit la résolution verticale, en pixels par pouce, de ce `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Obtient ou définit la résolution verticale, en pixels par pouce, de ce `RasterImage`. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient une valeur indiquant si cette instance de [RasterImage](../../com.aspose.imaging/rasterimage) possède une couleur transparente. |
| [hasAlpha()](#hasAlpha--) | Obtient une valeur indiquant si cette instance possède de l'alpha. |
| [getTransparentColor()](#getTransparentColor--) | Obtient la couleur transparente de l'image. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Définit une valeur indiquant si cette instance de [RasterImage](../../com.aspose.imaging/rasterimage) possède une couleur transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Obtient la couleur transparente de l'image. |
| [getImageOpacity()](#getImageOpacity--) | Obtient l'opacité de cette image. |
| [removeMetadata()](#removeMetadata--) | Supprime les métadonnées de cette instance d'image en définissant la valeur de `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) à `null`. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Récupère la date et l'heure auxquelles l'image de la ressource a subi sa dernière modification. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Effectue le tramage sur l'image actuelle. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Effectue le tramage sur l'image actuelle. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-) | Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Obtient le tableau de données brutes par défaut. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Obtient un pixel ARGB 32 bits d'image. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Obtient un pixel d'image. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Définit un pixel ARGB 32 bits d'image pour la position spécifiée. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.imaging.Color-) | Définit un pixel d'image pour la position spécifiée. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.imaging.Color---) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Charge partiellement les pixels ARGB 32 bits par paquets. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Charge les pixels partiellement par paquets. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.imaging.Rectangle-) | Charge les pixels ARGB 32 bits. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.imaging.Rectangle-) | Charge les pixels ARGB 64 bits. |
| [loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)](#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-) | Charge partiellement les pixels ARGB 64 bits par paquets. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.imaging.Rectangle-) | Charge les pixels. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.imaging.Rectangle-) | Charge les pixels au format CMYK. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.imaging.Rectangle-) | Charge les pixels au format CMYK. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Charge les données d'image brutes en utilisant le mécanisme de traitement partiel. |
| [loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Charge les données brutes. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Enregistre les données brutes. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---) | Enregistre les pixels ARGB 32 bits. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---) | Enregistre les pixels. |
| [toBitmap()](#toBitmap--) | Convertit l'image raster en bitmap. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---) | Enregistre les pixels. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---) | Enregistre les pixels. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Définit la résolution pour ce `RasterImage`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Définit la palette de l'image. |
| [autoRotate()](#autoRotate--) | Fait pivoter automatiquement l'image en fonction des données d'orientation extraites des métadonnées Exif. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne l'image avec des options étendues. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Faire pivoter l'image autour du centre. |
| [rotate(float angle)](#rotate-float-) | Faire pivoter l'image autour du centre. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisation d'une image avec un seuil prédéfini |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisation d'une image avec le seuillage d'Otsu |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-) | Mélange cette instance d'image avec l'image `overlay`. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mélange cette instance d'image avec l'image `overlay`. |
| [blend(Point origin, RasterImage overlay)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-) | Mélange cette instance d'image avec le `overlay` avec alpha == 255. |
| [blend(Point origin, RasterImage overlay, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-) | Mélange cette instance d'image avec le `overlay`. |
| [grayscale()](#grayscale--) | Transformation d'une image en sa représentation en niveaux de gris |
| [normalizeHistogram()](#normalizeHistogram--) | Normalise l'histogramme de l'image \\u2014 ajuste les valeurs des pixels pour utiliser toute la plage disponible. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Normalisation automatique adaptative de la luminosité et du contraste pour l'image entière. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajustement de la luminosité d'une image. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contraste d'image |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Intégrer une signature numérique basée sur le mot de passe fourni dans l'image en utilisant la stéganographie. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Calcule le pourcentage de similarité entre les données extraites et le mot de passe original. |
| [isDigitalSigned(String password)](#isDigitalSigned-java.lang.String-) | Effectue une vérification rapide pour déterminer si l'image est signée numériquement, en utilisant le mot de passe fourni et le seuil. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Effectue une vérification rapide pour déterminer si l'image est signée numériquement, en utilisant le mot de passe fourni et le seuil. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correction gamma d'une image. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correction gamma d'une image. |
| [getSkewAngle()](#getSkewAngle--) | Obtient l'angle d'inclinaison. |
| [normalizeAngle()](#normalizeAngle--) | Normalise l'angle. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normalise l'angle. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtre le rectangle spécifié. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.imaging.Color-) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. |

## Example: This example shows how to load pixel information in an array of colors, manipulates the array and set it back to the image.

``` java
String dir = "c:\\temp\\";

// Créez une instance de GifOptions et définissez ses différentes propriétés, y compris la propriété Source
com.aspose.imaging.imageoptions.GifOptions gifOptions = new com.aspose.imaging.imageoptions.GifOptions();
gifOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.gif", false));

// Créer une instance de Image
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(gifOptions, 500, 500);
try {
    // Obtenez les pixels de l'image en spécifiant la zone comme la frontière de l'image
    com.aspose.imaging.Color[] pixels = image.loadPixels(image.getBounds());

    // Parcourez le tableau et définissez la couleur du pixel indexé alternatif
    for (int index = 0; index < pixels.length; index++) {
        if (index % 2 == 0) {
            // Définissez la couleur du pixel indexé sur jaune
            pixels[index] = com.aspose.imaging.Color.getYellow();
        } else {
            // Définissez la couleur du pixel indexé sur bleu
            pixels[index] = com.aspose.imaging.Color.getBlue();
        }
    }

    // Appliquez les modifications de pixels à l'image
    image.savePixels(image.getBounds(), pixels);

    // Enregistrer toutes les modifications.
    image.save();
} finally {
    image.dispose();
}
```

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés.

**Returns:**
booléen - `true` si les composants de l'image doivent être prémultipliés ; sinon, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si les composants de l'image doivent être prémultipliés ; sinon, `false`. |


**Example: The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Enregistrer les pixels pour l'image entière.
    rasterImage.savePixels(rasterImage.getBounds(), colors);

    // Les pixels sont stockés dans l'image originale sous forme non prémultipliée.
    // Il faut spécifier explicitement l'option correspondante pour obtenir des composants couleur prémultipliés.
    // Les composants couleur prémultipliés sont calculés à l'aide des formules:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    rasterImage.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = rasterImage.loadPixels(rasterImage.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}
```

### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque le chargement de données brutes est disponible.

**Returns:**
booléen - `true` si le chargement de données brutes est utilisé lorsque le chargement de données brutes est disponible ; sinon, `false`.
### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque le chargement de données brutes est disponible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si le chargement de données brutes est utilisé lorsque le chargement de données brutes est disponible ; sinon, `false`. |

### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP.

**Returns:**
booléen - `true` si la métadonnée XMP est mise à jour ; sinon, `false`.
### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si la métadonnée XMP est mise à jour ; sinon, `false`. |

### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Obtient ou définit le convertisseur de couleur indexée

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Obtient ou définit le convertisseur de couleur indexée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Le convertisseur de couleur indexée |

### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Obtient ou définit le convertisseur de couleur personnalisé

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Obtient ou définit le convertisseur de couleur personnalisé

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Le convertisseur de couleur personnalisé |

### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites

**Returns:**
int - L'index de secours à utiliser lorsque l'index de la palette est hors limites
### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'index de secours à utiliser lorsque l'index de la palette est hors limites |

### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Obtient les paramètres actuels des données brutes. Notez que lors de l'utilisation de ces paramètres, les données sont chargées sans conversion.

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings)
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Obtient une valeur indiquant si la palette de l'image est utilisée.

Valeur : `true` si la palette est utilisée dans l'image ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si la palette d'image est utilisée.
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Obtient le format des données brutes.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Les fichiers image à charger.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// La sortie peut ressembler à ceci :
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, used channels: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, used channels: 8,8,8,8 HasAlpha=true
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Obtient la taille de ligne brute en octets.

**Returns:**
int - La taille brute de la ligne en octets.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Obtient une valeur indiquant si le chargement de données brutes est disponible.

**Returns:**
booléen - `true` si ce chargement de données brutes est disponible ; sinon, `false`.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Obtient ou définit la résolution horizontale, en pixels par pouce, de ce `RasterImage`.

**Returns:**
double - La résolution horizontale.

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtenez la résolution horizontale et verticale de l'image
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // La sortie peut ressembler à ceci :
    // La résolution horizontale, en pixels par pouce : 300.0
    // La résolution verticale, en pixels par pouce : 300.0
    // Définissez les valeurs de résolution à 96 dpi
    // La résolution horizontale, en pixels par pouce : 96.0
    // La résolution verticale, en pixels par pouce : 96.0
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Obtient ou définit la résolution horizontale, en pixels par pouce, de ce `RasterImage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution horizontale. |

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtient ou définit la résolution verticale, en pixels par pouce, de ce `RasterImage`.

**Returns:**
double - La résolution verticale.

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtenez la résolution horizontale et verticale de l'image
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // La sortie peut ressembler à ceci :
    // La résolution horizontale, en pixels par pouce : 300.0
    // La résolution verticale, en pixels par pouce : 300.0
    // Définissez les valeurs de résolution à 96 dpi
    // La résolution horizontale, en pixels par pouce : 96.0
    // La résolution verticale, en pixels par pouce : 96.0
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Obtient ou définit la résolution verticale, en pixels par pouce, de ce `RasterImage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution verticale. |

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtient une valeur indiquant si cette instance de [RasterImage](../../com.aspose.imaging/rasterimage) possède une couleur transparente.

--------------------

L'implémentation de base renvoie effectivement `` si elle n'est pas remplacée dans une implémentation spécifique qui prend en charge cette fonctionnalité. Cette propriété est principalement utilisée par [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) pour définir une couleur transparente si une image ne prend pas en charge la transparence via le canal alpha.

**Returns:**
boolean - une valeur indiquant si cette instance [RasterImage](../../com.aspose.imaging/rasterimage) possède une couleur transparente.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtient une valeur indiquant si cette instance possède de l'alpha.

**Returns:**
boolean - `true` si cette instance possède un canal alpha ; sinon, `false`.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Les fichiers image à charger.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// La sortie peut ressembler à ceci :
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, used channels: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, used channels: 8,8,8,8 HasAlpha=true
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Obtient la couleur transparente de l'image.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Définit une valeur indiquant si cette instance de [RasterImage](../../com.aspose.imaging/rasterimage) possède une couleur transparente.

--------------------

L'implémentation de base renvoie effectivement `` si elle n'est pas remplacée dans une implémentation spécifique qui prend en charge cette fonctionnalité. Cette propriété est principalement utilisée par [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) pour définir une couleur transparente si une image ne prend pas en charge la transparence via le canal alpha.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | une valeur indiquant si cette instance [RasterImage](../../com.aspose.imaging/rasterimage) possède une couleur transparente. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Obtient la couleur transparente de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Obtient l'opacité de cette image.

**Returns:**
float - La valeur d'opacité entre 0.0 (totalement transparent) et 1.0 (totalement opaque).
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Supprime les métadonnées de cette instance d'image en définissant la valeur de `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) à `null`.

### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Récupère la date et l'heure de la dernière modification de l'image de ressource. Cette méthode fournit des métadonnées précieuses, permettant aux utilisateurs de suivre et de gérer efficacement les mises à jour du fichier image. En accédant à ces informations, les utilisateurs peuvent garantir l'intégrité et l'actualité de leurs actifs d'image, facilitant ainsi une prise de décision éclairée concernant l'utilisation et la maintenance des images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| useDefault | boolean | si défini sur `true`, utilise les informations de FileInfo comme valeur par défaut. |

**Returns:**
java.util.Date - La date et l'heure auxquelles l'image de ressource a été modifiée pour la dernière fois.
### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Effectue le tramage sur l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |


**Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Effectuer un dithering par seuil en utilisant une palette de couleurs 4 bits contenant 16 couleurs.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Effectuer un dithering Floyd en utilisant une palette de couleurs 1 bit contenant uniquement 2 couleurs - noir et blanc.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.save(dir + "sample.FloydSteinbergDithering1.png");
} finally {
    image.dispose();
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Effectue le tramage sur l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personnalisée pour le tramage. |

### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle pour lequel obtenir les pixels. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Le chargeur de pixels partiel. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle pour lequel obtenir les pixels. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Le chargeur partiel de données brutes. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Les paramètres des données brutes. |

### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Obtient le tableau de pixels ARGB 32 bits par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle pour lequel obtenir les pixels. |

**Returns:**
int[] - Le tableau de pixels par défaut.
### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Obtient le tableau de données brutes par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle dont on veut obtenir les données brutes. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Les paramètres des données brutes. |

**Returns:**
byte[] - Le tableau de données brutes par défaut.
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Obtient un pixel ARGB 32 bits d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |

**Returns:**
int - Le pixel ARGB 32 bits pour l'emplacement spécifié.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtenez une représentation entière de la couleur du pixel supérieur gauche de l'image.
    int color = rasterImage.getArgb32Pixel(0, 0);

    // Pour obtenir les valeurs des composants de couleur individuels, décalez la valeur de couleur d'un nombre de bits correspondant.
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La couleur du pixel(0,0) est A=255,R=0,G=0,B=0
```

### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Obtient un pixel d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The pixel color for the specified location.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtenez la couleur du pixel supérieur gauche de l'image.
    com.aspose.imaging.Color color = rasterImage.getPixel(0, 0);

    // Obtenez les valeurs des composants de couleur individuels
    int alpha = color.getA();
    int red = color.getR();
    int green = color.getG();
    int blue = color.getB();

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}
```

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Définit un pixel ARGB 32 bits d'image pour la position spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |
| argb32Color | int | Le pixel ARGB 32 bits pour la position spécifiée. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Définit la couleur du pixel supérieur gauche.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Une autre façon consiste à passer directement une instance de com.aspose.imaging.Color
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.imaging.Color-}
```
public void setPixel(int x, int y, Color color)
```


Définit un pixel d'image pour la position spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |
| color | [Color](../../com.aspose.imaging/color) | La couleur du pixel pour la position spécifiée. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Définit la couleur du pixel supérieur gauche.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Une autre façon consiste à passer directement une instance de com.aspose.imaging.Color
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Indice basé sur zéro de la ligne de numérisation. |

**Returns:**
com.aspose.imaging.Color[] - Le tableau des valeurs de couleur des pixels de la ligne de numérisation.
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Indice basé sur zéro de la ligne de numérisation. |

**Returns:**
int[] - Le tableau des valeurs de couleur ARGB 32 bits de la ligne de numérisation.
### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.imaging.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Indice basé sur zéro de la ligne de numérisation. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Le tableau des couleurs de pixels à écrire. |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Indice basé sur zéro de la ligne de numérisation. |
| argb32Pixels | int[] | Le tableau des couleurs ARGB 32 bits à écrire. |

### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Charge partiellement les pixels ARGB 32 bits par paquets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle souhaité. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Le chargeur de pixels ARGB 32 bits. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
L'exemple suivant montre comment charger et traiter les pixels d'une image raster en utilisant votre propre processeur partiel. Par exemple, considérez un problème de comptage des pixels entièrement transparents d'une image. Afin de compter les pixels transparents en utilisant le mécanisme de chargement partiel, une classe séparée TransparentArgb32PixelCounter implémentant com.aspose.imaging.IPartialArgb32PixelLoader est introduite.
``` java

// Tout d'abord, implémentez com.aspose.imaging.IPartialArgb32PixelLoader pour compter tous les pixels entièrement transparents.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentArgb32PixelCounter implements com.aspose.imaging.IPartialArgb32PixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>                 *
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, int[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (int pixel : pixels) {
            int alpha = (pixel >> 24) & 0xff;
            if (alpha == 0) {
                this.count++;
            }
        }
    }
}

// Voici un exemple d'utilisation du compteur.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Créez une instance de com.aspose.imaging.IPartialArgb32PixelLoader et transmettez-la à com.aspose.imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // Chargez les pixels pour l'image entière. Toute partie rectangulaire de l'image peut être spécifiée comme premier paramètre de la méthode com.aspose.imaging.RasterImage.loadPartialArgb32Pixels.
    rasterImage.loadPartialArgb32Pixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// Le nombre de pixels entièrement transparents est de 55157
// Le nombre total de pixels est de 120400
```

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Charge les pixels partiellement par paquets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle souhaité. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | Le chargeur de pixels. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
L'exemple suivant montre comment charger et traiter les pixels d'une image raster en utilisant votre propre processeur partiel. Par exemple, considérez un problème de comptage des pixels entièrement transparents d'une image. Afin de compter les pixels transparents en utilisant le mécanisme de chargement partiel, une classe distincte TransparentPixelCounter implémentant com.aspose.imaging.IPartialPixelLoader est introduite.
``` java

// Tout d'abord, implémentez com.aspose.imaging.IPartialPixelLoader pour compter tous les pixels entièrement transparents.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelCounter implements com.aspose.imaging.IPartialPixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, com.aspose.imaging.Color[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (com.aspose.imaging.Color pixel : pixels) {
            if (pixel.getA() == 0) {
                this.count++;
            }
        }
    }
}

// Voici un exemple d'utilisation du compteur.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Créez une instance de com.aspose.imaging.IPartialPixelLoader et transmettez-la à com.aspose.imaging.RasterImage.loadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // Chargez les pixels pour l'image entière. Toute partie rectangulaire de l'image peut être spécifiée comme premier paramètre de la méthode com.aspose.imaging.RasterImage.loadPartialPixels.
    rasterImage.loadPartialPixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// Le nombre de pixels entièrement transparents est de 55157
// Le nombre total de pixels est de 120400
```

### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Charge les pixels ARGB 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns:**
int[] - Le tableau de pixels ARGB 32 bits chargé.

**Example: The following example shows how to load and process pixels of a raster image.**
L'exemple suivant montre comment charger et traiter les pixels d'une image raster. Les pixels sont représentés sous forme de valeurs entières 32 bits. Par exemple, considérez un problème de comptage des pixels entièrement transparents d'une image.
``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Chargez les pixels pour l'image entière. Toute partie rectangulaire de l'image peut être spécifiée comme paramètre de la méthode com.aspose.imaging.RasterImage.loadArgb32Pixels.
    int[] pixels = rasterImage.loadArgb32Pixels(rasterImage.getBounds());

    int count = 0;
    for (int pixel : pixels) {
        int alpha = (pixel >> 24) & 0xff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.imaging.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Charge les pixels ARGB 64 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns:**
long[] - Le tableau de pixels ARGB 64 bits chargé.

**Example: The following example shows how to load and process pixels of a raster image.**
L'exemple suivant montre comment charger et traiter les pixels d'une image raster. Les pixels sont représentés sous forme de valeurs entières 64 bits. Par exemple, considérez un problème de comptage des pixels entièrement transparents d'une image.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\16rgba.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Chargez les pixels pour l'image entière. Toute partie rectangulaire de l'image peut être spécifiée comme paramètre de la méthode com.aspose.imaging.RasterImage.loadArgb64Pixels.
    // Notez que l'image elle-même doit avoir 16 bits par échantillon, car com.aspose.imaging.RasterImage.loadArgb64Pixels ne fonctionne pas avec 8 bits par échantillon.
    // Pour travailler avec 8 bits par échantillon, veuillez utiliser la bonne vieille méthode com.aspose.imaging.RasterImage.loadArgb32Pixels.
    long[] pixels = rasterImage.loadArgb64Pixels(rasterImage.getBounds());

    int count = 0;
    for (long pixel : pixels) {
        // Notez que tous les composants de couleur, y compris l'alpha, sont représentés par des valeurs 16 bits, donc leurs valeurs autorisées sont dans la plage [0, 63535].
        long alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader) {#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-}
```
public final void loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)
```


Charge partiellement les pixels ARGB 64 bits par paquets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle souhaité. |
| partialPixelLoader | [IPartialArgb64PixelLoader](../../com.aspose.imaging/ipartialargb64pixelloader) | Le chargeur de pixels ARGB 64 bits. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.imaging.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Charge les pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns:**
com.aspose.imaging.Color[] - Le tableau de pixels chargé.

**Example: The following example shows how to load and process pixels of a raster image.**
L'exemple suivant montre comment charger et traiter les pixels d'une image raster. Par exemple, considérez un problème de comptage des pixels entièrement transparents d'une image.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Chargez les pixels pour l'image entière. Toute partie rectangulaire de l'image peut être spécifiée comme paramètre de la méthode Aspose.Imaging.RasterImage.LoadPixels.
    com.aspose.imaging.Color[] pixels = rasterImage.loadPixels(rasterImage.getBounds());

    int count = 0;
    for (com.aspose.imaging.Color pixel : pixels) {
        if (pixel.getA() == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.imaging.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Charge les pixels au format CMYK. Cette méthode est obsolète. Veuillez utiliser de manière plus efficace la méthode `loadCmyk32Pixels(Rectangle)`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns:**
com.aspose.imaging.CmykColor[] - Le tableau de pixels CMYK chargé.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Charge les pixels au format CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns:**
int[] - Les pixels CMYK chargés sont présentés sous forme de valeurs entières 32 bits.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Charge les données d'image brutes en utilisant le mécanisme de traitement partiel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | La zone rectangulaire souhaitée de l'image à partir de laquelle charger les données. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Les paramètres des données brutes. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Le chargeur de données brutes. |


**Example: The following example shows how to extract pixels from the raw image data using RawDataSettings.**
L'exemple suivant montre comment extraire les pixels des données d'image brutes à l'aide de RawDataSettings. Par exemple, considérez un problème de comptage des pixels totalement transparents d'une image.
``` java

// Tout d'abord, implémentez un compteur. Dans le cas de données brutes, le compteur peut ressembler à ceci :
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelRawDataCounter implements com.aspose.imaging.IPartialRawDataLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * The raw data settings of the loaded image.
     */
    private com.aspose.imaging.RawDataSettings rawDataSettings;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Initializes a new instance of the <see TransparentPixelRawDataCounter /> class.</p>
     *
     * @param settings The raw data settings allow to extract color components from raw data.
     */
    public TransparentPixelRawDataCounter(com.aspose.imaging.RawDataSettings settings) {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end)// throws java.lang.Exception
    {
        int[] channelBits = this.rawDataSettings.getPixelDataFormat().getChannelBits();

        // Seuls les formats simples sont pris en compte ici pour simplifier le code.
        // Considérons uniquement les images avec 8 bits par échantillon.
        for (int i = 0; i < channelBits.length; i++) {
            if (channelBits[i] != 8) {
                throw new java.lang.UnsupportedOperationException();
            }
        }

        switch (this.rawDataSettings.getPixelDataFormat().getPixelFormat()) {
            case com.aspose.imaging.PixelFormat.Rgb:
            case com.aspose.imaging.PixelFormat.Bgr: {
                if (channelBits.length == 4) {
                    // ARGB
                    for (int i = 0; i < data.length; i += 4) {
                        // Le canal alpha est stocké en dernier, après les composants de couleur.
                        if (data[i + 3] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            case com.aspose.imaging.PixelFormat.Grayscale: {
                if (channelBits.length == 2) {
                    // Grayscale Alpha
                    for (int i = 0; i < data.length; i += 2) {
                        // Le canal alpha est stocké en dernier, après les composants de couleur.
                        if (data[i + 1] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            default:
                throw new java.lang.IllegalArgumentException("PixelFormat");
        }
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>                 *
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     * @param loadOptions   The load options.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end, com.aspose.imaging.LoadOptions loadOptions) {
        this.process(dataRectangle, data, start, end);
    }
}

// Voici l'exemple principal d'utilisation du compteur
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    com.aspose.imaging.RawDataSettings settings = rasterImage.getRawDataSettings();

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Chargez les pixels pour l'image entière. Toute partie rectangulaire de l'image peut être spécifiée comme paramètre de la méthode Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.loadRawData(rasterImage.getBounds(), settings, rawDataLoader);

    System.out.println("The number of fully transparent pixels is " + rawDataLoader.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// Le nombre de pixels entièrement transparents est de 55157
// Le nombre total de pixels est de 120400
```

### loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Charge les données brutes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle à partir duquel charger les données brutes. |
| dstImageBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Les limites de l'image de destination. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Les paramètres des données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas dans le format spécifié, une conversion des données sera effectuée. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Le chargeur de données brutes. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Enregistre les données brutes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données brutes. |
| dataOffset | int | Le décalage de départ des données brutes. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle des données brutes. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Les paramètres des données brutes dans lesquelles les données se trouvent. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Enregistre les pixels ARGB 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Le tableau de pixels ARGB 32 bits. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
L'exemple suivant remplit la zone centrale d'une image raster avec des pixels noirs en utilisant la méthode com.aspose.imaging.RasterImage.saveArgb32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Le carré noir
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack().toArgb();
    }

    // Dessinez le carré noir au centre de l'image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveArgb32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveArgb32Pixels.png");
} finally {
    image.dispose();
}
```

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Enregistre les pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Le tableau de pixels. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
L'exemple suivant remplit la zone centrale d'une image raster avec des pixels noirs en utilisant la méthode com.aspose.imaging.RasterImage.savePixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Le carré noir
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack();
    }

    // Dessinez le carré noir au centre de l'image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.savePixels(area, pixels);

    rasterImage.save(dir + "sample.SavePixels.png");
} finally {
    image.dispose();
}
```

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Convertit l'image raster en bitmap.

**Returns:**
java.awt.image.BufferedImage - Le bitmap

**Example: The following example converts a BMP image to a native Java bitmap.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    java.awt.image.BufferedImage bitmap = bmpImage.toBitmap();

    // Traitez le bitmap Java natif.
} finally {
    image.dispose();
}
```

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Enregistre les pixels. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace `saveCmyk32Pixels(Rectangle, int[])`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Le tableau de pixels CMYK. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Enregistre les pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
L'exemple suivant remplit la zone centrale d'une image raster avec des pixels noirs en utilisant la méthode com.aspose.imaging.RasterImage.saveCmyk32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtenez une représentation entière du noir dans l'espace colorimétrique CMYK.
    int blackCmyk = com.aspose.imaging.CmykColorHelper.toCmyk(com.aspose.imaging.Color.getBlack());

    // Le carré noir.
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = blackCmyk;
    }

    // Dessinez le carré noir au centre de l'image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveCmyk32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveCmyk32Pixels.png");
} finally {
    image.dispose();
}
```

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Définit la résolution pour ce `RasterImage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpiX | double | La résolution horizontale, en points par pouce, du `RasterImage`. |
| dpiY | double | La résolution verticale, en points par pouce, du `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtenez la résolution horizontale et verticale de l'image
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // La sortie peut ressembler à ceci :
    // La résolution horizontale, en pixels par pouce : 300.0
    // La résolution verticale, en pixels par pouce : 300.0
    // Définissez les valeurs de résolution à 96 dpi
    // La résolution horizontale, en pixels par pouce : 96.0
    // La résolution verticale, en pixels par pouce : 96.0
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Définit la palette de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette à définir. |
| updateColors | boolean | si défini sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### autoRotate() {#autoRotate--}
```
public final void autoRotate()
```


Fait pivoter automatiquement l'image en fonction des données d'orientation extraites des métadonnées Exif. Cette méthode garantit que les images sont affichées dans la bonne orientation, améliore l'expérience utilisateur et élimine le besoin d'ajustements manuels. En analysant les informations Exif, l'image est pivotée en conséquence, offrant une expérience de visualisation fluide sur différentes plateformes et appareils. Ce processus de rotation automatisé simplifie la gestion des images et améliore la convivialité globale, notamment lors du traitement de gros lots d'images avec des orientations variées.

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionne l'image avec des options étendues.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Faire pivoter l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens des aiguilles d'une montre. |
| resizeProportionally | boolean | si défini sur `true`, la taille de votre image sera modifiée selon les projections du rectangle pivoté (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul le contenu interne de l'image est pivoté. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Faire pivoter l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens des aiguilles d'une montre. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisation d'une image avec un seuil prédéfini

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |


**Example: The following example binarizes a raster image with the predefined threshold.**
L'exemple suivant binarise une image raster avec le seuil prédéfini. Les images binarisées ne contiennent que 2 couleurs - le noir et le blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

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


**Example: The following example binarizes a raster image with Otsu thresholding.**
L'exemple suivant binarise une image raster avec le seuillage d'Otsu. Les images binarisées ne contiennent que 2 couleurs - le noir et le blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarisez l'image avec le seuillage d'Otsu.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
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


**Example: The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size.**
L'exemple suivant binarise une image raster avec l'algorithme de seuillage adaptatif de Bradley, avec la taille de fenêtre spécifiée. Les images binarisées ne contiennent que 2 couleurs - le noir et le blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarisez l'image avec une différence de luminosité de 5. La luminosité est une différence entre un pixel et la moyenne d'une fenêtre de 10 x 10 pixels centrée sur ce pixel.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-}
```
public final void blend(Point origin, RasterImage overlay, Rectangle overlayArea)
```


Mélange cette instance d'image avec l'image `overlay`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine du mélange de l'image d'arrière-plan. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image de superposition. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | La zone de superposition. |

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

### blend(Point origin, RasterImage overlay) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-}
```
public final void blend(Point origin, RasterImage overlay)
```


Mélange cette instance d'image avec le `overlay` avec alpha == 255.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine du mélange de l'image d'arrière-plan. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | La superposition. |

### blend(Point origin, RasterImage overlay, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-}
```
public final void blend(Point origin, RasterImage overlay, byte overlayAlpha)
```


Mélange cette instance d'image avec le `overlay`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine du mélange de l'image d'arrière-plan. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | La superposition. |
| overlayAlpha | byte | L'alpha de superposition. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation d'une image en sa représentation en niveaux de gris


**Example: The following example transforms a colored raster image to its grayscale representation.**
L'exemple suivant transforme une image raster couleur en sa représentation en niveaux de gris. Les images en niveaux de gris sont composées exclusivement de nuances de gris et ne contiennent que des informations d'intensité.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

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


Normalisation automatique adaptative de la luminosité et du contraste pour l'image entière.

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajustement de la luminosité d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | int | Valeur de luminosité. |


**Example: The following example performs brightness correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

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


**Example: The following example performs contrast correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Définissez la valeur de contraste. Les valeurs acceptées de contraste sont dans la plage [-100f, 100f].
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
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
### isDigitalSigned(String password) {#isDigitalSigned-java.lang.String-}
```
public boolean isDigitalSigned(String password)
```


Effectue une vérification rapide pour déterminer si l'image est signée numériquement, en utilisant le mot de passe fourni et le seuil.

--------------------

Cette méthode fournit la détection la plus rapide en utilisant `GetSignPercentage`. Une fois que les données extraites atteignent le seuil spécifié, les étapes d'extraction supplémentaires visant à améliorer la précision de la détection sont ignorées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | java.lang.String | Le mot de passe pour vérifier la signature. |

**Returns:**
boolean - Vrai si l'image est signée, sinon faux.
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


**Example: The following example performs gamma-correction of an image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

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


**Example: The following example performs gamma-correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Définir le coefficient gamma pour les canaux rouge, vert et bleu.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Obtient l'angle d'inclinaison. Cette méthode s'applique aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors de la numérisation.

**Returns:**
float - L'angle d'inclinaison, en degrés.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normalise l'angle. Cette méthode s'applique aux documents texte numérisés pour éliminer la numérisation inclinée. Cette méthode utilise \#getSkewAngle.getSkewAngle et les méthodes [Image.rotate(float)](../../com.aspose.imaging/image\#rotate-float-).

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalise l'angle. Cette méthode s'applique aux documents texte numérisés pour éliminer la numérisation inclinée. Cette méthode utilise \#getSkewAngle.getSkewAngle et les méthodes \#rotate(float, boolean, Color).rotate(float, boolean, Color).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resizeProportionally | boolean | si défini sur `true`, la taille de votre image sera modifiée selon les projections du rectangle pivoté (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul le contenu interne de l'image est pivoté. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |


**Example: Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle.**
Le biais est un artefact qui peut apparaître lors du processus de numérisation d'un document lorsque le texte/les images du document sont légèrement tournés. Il peut avoir diverses causes, mais la plus courante est que le papier soit mal positionné pendant la numérisation. Par conséquent, le deskew est le processus de détection et de correction de ce problème sur les fichiers numérisés (c.-à-d. bitmap) afin que les documents deskewed aient le texte/les images correctement et horizontalement ajustés.
``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";

String inputFilePath = dir + "skewed.png";
String outputFilePath = dir + "skewed.out.png";

// Éliminez la numérisation inclinée avec les paramètres par défaut
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(inputFilePath);
try {
    // Deskew
    image.normalizeAngle(false /*do not resize*/, com.aspose.imaging.Color.getLightGray() /*background color*/);
    image.save(outputFilePath);
} finally {
    image.close();
}
```

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


**Example: The following example applies various types of filters to a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre médian avec une taille de rectangle de 5 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.imaging/color) | Ancienne couleur à remplacer. |
| oldColorDiff | byte | Différence autorisée dans l'ancienne couleur pour pouvoir élargir la teinte de couleur remplacée. |
| newColor | [Color](../../com.aspose.imaging/color) | Nouvelle couleur avec laquelle remplacer l'ancienne couleur. |

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

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.imaging.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Remplace toutes les couleurs non transparentes par la nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.imaging/color) | Nouvelle couleur avec laquelle remplacer les couleurs non transparentes. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Remplace toutes les couleurs non transparentes par la nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorArgb | int | Nouvelle valeur ARGB de couleur pour remplacer les couleurs non transparentes. |

