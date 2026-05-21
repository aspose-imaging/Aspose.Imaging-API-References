---
title: "TiffImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Traitez les images raster au format Tagged Image File Format (TIFF) avec notre API offrant une prise en charge complète de diverses résolutions et des capacités d'édition avancées telles que la manipulation des données EXIF et les canaux alpha."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.tiff/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Traitez les images raster au format Tagged Image File Format (TIFF) avec notre API, offrant une prise en charge complète de diverses résolutions et des capacités d'édition avancées telles que la manipulation des données EXIF et les canaux alpha. Normalisez les angles des images numérisées, redimensionnez, convertissez en niveaux de gris et appliquez facilement des filtres, des corrections gamma et des ajustements des paramètres d'image. Gérez sans effort les fichiers TIFF multi‑cadres, créez des chemins graphiques, ajoutez des formes et enregistrez aisément les images dans différents formats.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffImage(TiffFrame frame)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Initialisez un nouvel objet de la classe [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), en spécifiant le paramètre de trame. |
| [TiffImage(TiffFrame[] frames)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Créez une nouvelle instance de la classe [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), en fournissant une liste de trames comme paramètre. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Récupérez la valeur du format de fichier associée à l'image. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Indiquez si les composants nécessitent une prémultiplication, assurant une gestion efficace des éléments visuels. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Indiquez si les composants nécessitent une prémultiplication, assurant une gestion efficace des éléments visuels. |
| [getByteOrder()](#getByteOrder--) | Basculez l'ordre des octets pour les fichiers TIFF de manière fluide, garantissant un contrôle précis de l'interprétation des données. |
| [setByteOrder(int value)](#setByteOrder-int-) | Basculez l'ordre des octets pour les fichiers TIFF de manière fluide, garantissant un contrôle précis de l'interprétation des données. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Récupérez la résolution horizontale de l'[Image](../../com.aspose.imaging/image) spécifiée en pixels par pouce, facilitant des ajustements précis et des capacités de rendu. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Modifie la résolution horizontale de l'[Image](../../com.aspose.imaging/image) spécifiée en pixels par pouce, facilitant des ajustements précis et des capacités de rendu. |
| [getVerticalResolution()](#getVerticalResolution--) | Accédez à la résolution verticale de l'[Image](../../com.aspose.imaging/image) désignée en pixels par pouce, permettant des ajustements précis et des optimisations de rendu. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Accédez à la résolution verticale de l'[Image](../../com.aspose.imaging/image) désignée en pixels par pouce, permettant des ajustements précis et des optimisations de rendu. |
| [getActiveFrame()](#getActiveFrame--) | Gérez la trame active de manière fluide, facilitant la navigation dynamique et la manipulation dans le contexte désigné. |
| [setActiveFrame(TiffFrame value)](#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Gérez la trame active de manière fluide, facilitant la navigation dynamique et la manipulation dans le contexte désigné. |
| [getFrames()](#getFrames--) | Récupérez un tableau d'instances de [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe), permettant un accès complet et la manipulation des trames individuelles au sein de l'image TIFF. |
| [getPageCount()](#getPageCount--) | Récupérez le nombre total de pages du document spécifié, facilitant une navigation efficace et la gestion du contenu multipage. |
| [getPages()](#getPages--) | Accédez aux pages du document de manière fluide, permettant une navigation dynamique et la manipulation au sein de la structure du contenu. |
| [hasAlpha()](#hasAlpha--) | Déterminez si l'image possède un canal alpha, fournissant des informations essentielles pour les opérations de rendu et de composition. |
| [removeMetadata()](#removeMetadata--) | Supprime les métadonnées de cette instance d'image en définissant la valeur de `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) à `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | Récupérez les options dérivées des paramètres du fichier original, facilitant la préservation fluide des paramètres clés tels que la profondeur de bits et d'autres attributs essentiels de l'image d'origine. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Intégrez une nouvelle page à l'image existante de manière fluide, élargissant son contenu et sa polyvalence. |
| [alignResolutions()](#alignResolutions--) | Implémentez la méthode d'assistance AlignResolutions pour synchroniser les résolutions horizontale et verticale, assurant l'uniformité des dimensions de l'image. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Définit la résolution pour le [RasterImage](../../com.aspose.imaging/rasterimage) spécifié, permettant un contrôle précis du rendu et des propriétés d'affichage de l'image. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Utilisez la méthode NormalizeAngle spécifiquement conçue pour les documents texte numérisés afin de rectifier les scans inclinés, garantissant un alignement précis. |
| [addFrame(TiffFrame frame)](#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Intégrez le cadre spécifié de manière fluide dans l'image, en élargissant son contenu et sa polyvalence. |
| [add(TiffImage image)](#add-com.aspose.imaging.fileformats.tiff.TiffImage-) | Ajoutez les cadres provenant de l'image spécifiée de manière fluide dans le cadre actuel, consolidant leur contenu et améliorant la flexibilité de composition. |
| [addFrames(TiffFrame[] frames)](#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Intégrez le tableau de cadres de manière fluide dans l'image, enrichissant son contenu et sa polyvalence. |
| [insertFrame(int index, TiffFrame frame)](#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Insérez le nouveau cadre à l'index spécifié dans la séquence de cadres, en assurant un contrôle précis de l'agencement des cadres. |
| [replaceFrame(int index, TiffFrame newFrame)](#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Remplacez le cadre à la position désignée par un autre cadre de manière fluide, facilitant la gestion dynamique des cadres au sein de la séquence d'images. |
| [removeFrame(int index)](#removeFrame-int-) | Éliminez sans effort le cadre identifié par son index de la séquence d'images, simplifiant la gestion des cadres dans votre application. |
| [removeFrame(TiffFrame frame)](#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Supprimez efficacement le cadre spécifié de la séquence d'images, facilitant une gestion simplifiée des cadres dans votre application. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Effectuez une opération de redimensionnement proportionnel sur l'image, en préservant son ratio d'aspect tout en ajustant ses dimensions. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ajustez la largeur de l'image tout en maintenant son ratio d'aspect, assurant un redimensionnement proportionnel pour une présentation visuelle optimale. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Effectuez un ajustement proportionnel de la hauteur de l'image, en préservant son ratio d'aspect pour une intégrité visuelle cohérente. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Effectuez une rotation, un retournement ou une combinaison des deux opérations exclusivement sur le cadre actif. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Exécutez le dithering sur l'image actuelle pour améliorer sa qualité visuelle et réduire les artefacts de bandes de couleur. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadrez l'image en utilisant une région rectangulaire spécifiée, permettant une sélection précise du contenu souhaité. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Effectuez un recadrage de l'image en spécifiant des déplacements vers la gauche, la droite, le haut et le bas. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Appliquez la binarisation à l'image en utilisant un seuil prédéfini, la convertissant en une image binaire avec des régions de premier plan et d'arrière-plan distinctes. |
| [binarizeOtsu()](#binarizeOtsu--) | Utilisez le seuillage d'Otsu pour réaliser la binarisation de l'image, déterminant automatiquement la valeur de seuil optimale basée sur l'histogramme de l'image. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Mettez en œuvre la binarisation de l'image en employant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale. |
| [grayscale()](#grayscale--) | Convertissez l'image en sa représentation en niveaux de gris, la transformant en une image à canal unique où chaque pixel représente l'intensité. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Appliquez la correction gamma à l'image, ajustant les intensités des pixels pour obtenir le rendu des couleurs souhaité. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Effectuez une correction gamma sur l'image en utilisant des coefficients individuels pour les canaux rouge, vert et bleu, permettant des ajustements fins du rendu des couleurs et du contraste. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Mettez en œuvre le réglage de `brightness` pour l'image, permettant la modification des niveaux de luminance globaux. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Améliorez le contraste de l'instance [Image](../../com.aspose.imaging/image), amplifiant les différences entre ses zones claires et sombres. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtrez le contenu à l'intérieur du rectangle spécifié, en appliquant un filtre de traitement d'image désigné pour améliorer ou modifier la région sélectionnée. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ajustez la taille de l'image en fonction des paramètres spécifiés, permettant un contrôle précis des dimensions, du ratio d'aspect et du comportement de mise à l'échelle. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Créer le GraphicsPath en utilisant PathResources à partir d'une image TIFF
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Dessiner une ligne rouge et enregistrer l'image
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // Créer une Figure rectangulaire pour GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Créer GraphicsPath en utilisant notre Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Définir PathResources en utilisant GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Enregistrer l'image
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### TiffImage(TiffFrame frame) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public TiffImage(TiffFrame frame)
```


Initialiser un nouvel objet de la classe [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), en spécifiant le paramètre de trame. Ce constructeur facilite la création d'une instance de TiffImage, permettant aux développeurs de spécifier la trame à charger ou à traiter, simplifiant les tâches de gestion d'images Tiff dans leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | La trame tiff avec laquelle initialiser l'image. |

### TiffImage(TiffFrame[] frames) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public TiffImage(TiffFrame[] frames)
```


Créer une nouvelle instance de la classe [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), en fournissant une liste de trames comme paramètre. Ce constructeur permet l'initialisation d'un objet TiffImage avec plusieurs trames, facilitant la gestion et le traitement efficaces des séquences d'images TIFF dans les applications logicielles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Les trames. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérer la valeur du format de fichier associée à l'image. Cette propriété constitue un aspect essentiel de la récupération des métadonnées d'image, permettant aux applications logicielles d'identifier et d'interpréter efficacement le format des données d'image.

**Returns:**
long - une valeur du format de fichier
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Indiquer si les composants nécessitent une prémultiplication, assurant une gestion efficace des éléments visuels. Améliorer les processus de rendu en activant ou désactivant cette propriété, rationalisant les flux de travail graphiques pour des performances optimisées.

**Returns:**
boolean - `true` si les composants doivent être prémultipliés ; sinon, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Indiquer si les composants nécessitent une prémultiplication, assurant une gestion efficace des éléments visuels. Améliorer les processus de rendu en activant ou désactivant cette propriété, rationalisant les flux de travail graphiques pour des performances optimisées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si les composants doivent être prémultipliés ; sinon, `false`. |


**Example: The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

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

com.aspose.imaging.imageoptions.TiffOptions createOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0]), true));

com.aspose.imaging.fileformats.tiff.TiffImage image =
        (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    // Enregistrer les pixels pour l'image entière.
    image.savePixels(image.getBounds(), colors);

    // Les pixels sont stockés dans l'image originale sous forme non prémultipliée.
    // Il faut spécifier explicitement l'option correspondante pour obtenir des composants couleur prémultipliés.
    // Les composants couleur prémultipliés sont calculés à l'aide des formules:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    image.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = image.loadPixels(image.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}

//La sortie sera comme suit :
//Couleur originale : Color [A=127, R=255, G=0, B=0]
//Couleur prémultipliée : Color [A=127, R=127, G=0, B=0]
//Couleur originale : Color [A=127, R=0, G=255, B=0]
//Couleur prémultipliée : Color [A=127, R=0, G=127, B=0]
//Couleur originale : Color [A=127, R=0, G=0, B=255]
//Couleur prémultipliée : Color [A=127, R=0, G=0, B=127]
//Couleur originale : Color [A=127, R=255, G=255, B=0]
//Couleur prémultipliée : Color [A=127, R=127, G=127, B=0]
//Couleur originale : Color [A=127, R=255, G=0, B=255]
//Couleur prémultipliée : Color [A=127, R=127, G=0, B=127]
//Couleur d'origine : Color [A=127, R=0, G=255, B=255]
//Couleur prémultipliée : Color [A=127, R=0, G=127, B=127]
```

### getByteOrder() {#getByteOrder--}
```
public final int getByteOrder()
```


Basculez l'ordre des octets pour les fichiers TIFF de manière fluide, en assurant un contrôle précis de l'interprétation des données. Donnez à vos applications la flexibilité de s'adapter à diverses spécifications de fichiers, améliorant la compatibilité et l'efficacité du traitement des données.

**Returns:**
int - L'ordre des octets TIFF.
### setByteOrder(int value) {#setByteOrder-int-}
```
public final void setByteOrder(int value)
```


Basculez l'ordre des octets pour les fichiers TIFF de manière fluide, en assurant un contrôle précis de l'interprétation des données. Donnez à vos applications la flexibilité de s'adapter à diverses spécifications de fichiers, améliorant la compatibilité et l'efficacité du traitement des données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'ordre des octets TIFF. |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Récupérez la résolution horizontale de l'[Image](../../com.aspose.imaging/image) spécifiée en pixels par pouce, facilitant un ajustement précis et des capacités de rendu. Accédez facilement aux métadonnées essentielles de l'image, permettant des flux de travail de traitement d'image rationalisés pour une expérience utilisateur améliorée.

**Returns:**
double - La résolution horizontale.

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Obtenez la résolution horizontale et verticale de l'image TIFF.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 96.0
// La résolution verticale, en pixels par pouce : 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Modifie la résolution horizontale de l'[Image](../../com.aspose.imaging/image) spécifiée en pixels par pouce, facilitant un ajustement précis et des capacités de rendu. Accédez facilement aux métadonnées essentielles de l'image, permettant des flux de travail de traitement d'image rationalisés pour une expérience utilisateur améliorée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution horizontale. |

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Accédez à la résolution verticale de l'[Image](../../com.aspose.imaging/image) désignée en pixels par pouce, permettant des ajustements précis et des optimisations de rendu. Utilisez facilement les données essentielles de l'image pour rationaliser les flux de travail de traitement d'image, garantissant une qualité et des performances supérieures dans vos applications.

**Returns:**
double - La résolution verticale.

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Obtenez la résolution horizontale et verticale de l'image TIFF.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 96.0
// La résolution verticale, en pixels par pouce : 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Accédez à la résolution verticale de l'[Image](../../com.aspose.imaging/image) désignée en pixels par pouce, permettant des ajustements précis et des optimisations de rendu. Utilisez facilement les données essentielles de l'image pour rationaliser les flux de travail de traitement d'image, garantissant une qualité et des performances supérieures dans vos applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution verticale. |

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel. |

### getActiveFrame() {#getActiveFrame--}
```
public final TiffFrame getActiveFrame()
```


Gérez la trame active de manière fluide, facilitant la navigation dynamique et la manipulation dans le contexte désigné. Permettez à votre application d'interagir efficacement avec le contenu multimédia, améliorant l'engagement et la productivité des utilisateurs.

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - Active frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Il s'agit de Font et Brush pour dessiner du texte sur des images individuelles.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Créer 5 cadres
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Créer une image PNG et y dessiner le numéro de page.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Créer un cadre basé sur l'image PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Ajouter le cadre à l'image TIFF.
        tiffImage.addFrame(frame);
    }

    // L'image a été créée avec un seul cadre par défaut. Supprimons‑le.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // N'oubliez pas de libérer le cadre si vous ne l'ajoutez pas à un autre TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### setActiveFrame(TiffFrame value) {#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void setActiveFrame(TiffFrame value)
```


Gérez la trame active de manière fluide, facilitant la navigation dynamique et la manipulation dans le contexte désigné. Permettez à votre application d'interagir efficacement avec le contenu multimédia, améliorant l'engagement et la productivité des utilisateurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Trame active. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Il s'agit de Font et Brush pour dessiner du texte sur des images individuelles.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Créer 5 cadres
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Créer une image PNG et y dessiner le numéro de page.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Créer un cadre basé sur l'image PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Ajouter le cadre à l'image TIFF.
        tiffImage.addFrame(frame);
    }

    // L'image a été créée avec un seul cadre par défaut. Supprimons‑le.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // N'oubliez pas de libérer le cadre si vous ne l'ajoutez pas à un autre TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getFrames() {#getFrames--}
```
public final TiffFrame[] getFrames()
```


Récupérez un tableau d'instances de [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe), permettant un accès complet et une manipulation des trames individuelles au sein de l'image TIFF. Exploitez la puissance de ce tableau pour rationaliser les flux de travail de traitement d'image, assurant un contrôle précis et une optimisation du contenu visuel.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame[] - le tableau de [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe).

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Il s'agit de Font et Brush pour dessiner du texte sur des images individuelles.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Créer 5 cadres
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Créer une image PNG et y dessiner le numéro de page.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Créer un cadre basé sur l'image PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Ajouter le cadre à l'image TIFF.
        tiffImage.addFrame(frame);
    }

    // L'image a été créée avec un seul cadre par défaut. Supprimons‑le.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // N'oubliez pas de libérer le cadre si vous ne l'ajoutez pas à un autre TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Récupérez le nombre total de pages du document spécifié, facilitant une navigation efficace et la gestion de contenu multipage. Intégrez cette fonctionnalité pour améliorer l'expérience utilisateur, permettant un accès fluide à des structures de documents complètes.

**Returns:**
int - le nombre de pages.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accédez aux pages du document de manière fluide, permettant une navigation dynamique et une manipulation au sein de la structure du contenu. Donnez à votre application un accès efficace aux pages individuelles, facilitant le traitement rationalisé des documents et une interaction utilisateur améliorée.

**Returns:**
com.aspose.imaging.Image[] - les pages.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Déterminez si l'image possède un canal alpha, fournissant des informations cruciales pour les opérations de rendu et de composition. Intégrez cette fonctionnalité pour optimiser les flux de travail de traitement visuel, garantissant une représentation précise et une manipulation des éléments transparents.

**Returns:**
boolean - `true` s'il y a un canal alpha.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Si la trame TIFF active possède un canal alpha, alors l'ensemble de l'image TIFF est considéré comme ayant un canal alpha.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Supprime les métadonnées de cette instance d'image en définissant la valeur de `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) à `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Récupérez les options dérivées des paramètres du fichier original, facilitant la préservation fluide des paramètres clés tels que la profondeur de bits et d'autres attributs essentiels de l'image d'origine. Utilisez cette méthode pour maintenir la fidélité et la cohérence dans les tâches de traitement d'image, garantissant des résultats optimaux sans altérations inutiles. Par exemple, si nous chargeons une image PNG noir‑blanc avec 1 bit par pixel puis l'enregistrons à l'aide de la méthode [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), une image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Intégrez une nouvelle page dans l'image existante de manière transparente, en élargissant son contenu et sa polyvalence. Utilisez cette méthode pour améliorer la composition et la gestion de documents, permettant une manipulation efficace des images multipages au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La page à ajouter. |

### alignResolutions() {#alignResolutions--}
```
public final void alignResolutions()
```


Implémentez la méthode d'assistance AlignResolutions pour synchroniser les résolutions horizontale et verticale, assurant l'uniformité des dimensions de l'image. Cette fonctionnalité facilite des flux de travail de traitement d'image rationalisés en harmonisant les paramètres de résolution, optimisant la qualité visuelle et la cohérence sur diverses plateformes et appareils.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Définit la résolution pour le [RasterImage](../../com.aspose.imaging/rasterimage) spécifié, permettant un contrôle précis du rendu et des propriétés d'affichage de l'image. Intégrez cette fonctionnalité pour optimiser la sortie visuelle et garantir la compatibilité avec divers appareils et plateformes de sortie, améliorant l'expérience utilisateur globale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpiX | double | La résolution horizontale, en points par pouce, du [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | La résolution verticale, en points par pouce, du [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Obtenez la résolution horizontale et verticale de l'image TIFF.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 96.0
// La résolution verticale, en pixels par pouce : 96.0
```

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Utilisez la méthode NormalizeAngle spécialement conçue pour les documents texte numérisés afin de rectifier les scans inclinés, garantissant un alignement précis. Intégrez de façon transparente cette fonctionnalité dans vos flux de traitement de texte pour améliorer la lisibilité et la qualité des documents, augmentant l'efficacité globale de la reconnaissance et de l'analyse de texte. Cette méthode utilise les méthodes [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) et [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resizeProportionally | boolean | si défini sur `true`, la taille de votre image sera modifiée selon les projections du rectangle pivoté (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul le contenu interne de l'image est pivoté. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

### addFrame(TiffFrame frame) {#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void addFrame(TiffFrame frame)
```


Intégrez la trame spécifiée de manière transparente dans l'image, en élargissant son contenu et sa polyvalence. Utilisez cette méthode pour améliorer la composition et la gestion d'images, permettant une manipulation efficace des images multi-trames au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | La trame à ajouter. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Il s'agit de Font et Brush pour dessiner du texte sur des images individuelles.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Créer 5 cadres
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Créer une image PNG et y dessiner le numéro de page.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Créer un cadre basé sur l'image PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Ajouter le cadre à l'image TIFF.
        tiffImage.addFrame(frame);
    }

    // L'image a été créée avec un seul cadre par défaut. Supprimons‑le.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // N'oubliez pas de libérer le cadre si vous ne l'ajoutez pas à un autre TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### add(TiffImage image) {#add-com.aspose.imaging.fileformats.tiff.TiffImage-}
```
public final void add(TiffImage image)
```


Ajoutez les trames de l'image spécifiée de manière transparente dans la trame actuelle, consolidant leur contenu et améliorant la flexibilité de composition. Intégrez cette méthode pour rationaliser la gestion et la manipulation des trames dans votre application, facilitant la manipulation efficace des images multi-trames.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) | L'image source. |

### addFrames(TiffFrame[] frames) {#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public final void addFrames(TiffFrame[] frames)
```


Intégrez le tableau de trames de façon transparente dans l'image, enrichissant son contenu et sa polyvalence. Utilisez cette méthode pour améliorer la composition et la gestion d'images, permettant une manipulation efficace des images multi-trames au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Le tableau de trames à ajouter |

### insertFrame(int index, TiffFrame frame) {#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void insertFrame(int index, TiffFrame frame)
```


Insérez la nouvelle trame à l'index spécifié dans la séquence de trames, assurant un contrôle précis de l'agencement des trames. Utilisez cette méthode pour gérer les séquences de trames efficacement, facilitant la manipulation dynamique et l'organisation du contenu d'image dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de `frame`. |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | La trame à insérer. |

### replaceFrame(int index, TiffFrame newFrame) {#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final TiffFrame replaceFrame(int index, TiffFrame newFrame)
```


Remplacez la trame à la position désignée par une autre trame de manière transparente, facilitant la gestion dynamique des trames au sein de la séquence d'images. Intégrez cette méthode pour améliorer la flexibilité et la précision de la manipulation des trames, assurant une organisation et une présentation optimales du contenu d'image dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | La position de la trame basée sur zéro. |
|  | newFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | La trame à remplacer. |

Remarque : n'oubliez pas de disposer/fermer la trame si vous ne l'ajoutez pas à un autre TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.
### removeFrame(int index) {#removeFrame-int-}
```
public final TiffFrame removeFrame(int index)
```


Supprimez sans effort la trame identifiée par son index de la séquence d'images, rationalisant la gestion des trames dans votre application. Intégrez cette fonctionnalité pour améliorer l'efficacité et la précision de la manipulation des trames, facilitant une organisation et une présentation transparentes du contenu d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | index | int | Index de la trame à supprimer. |

--------------------

Remarque : n'oubliez pas de disposer la trame si vous ne l'ajoutez pas à un autre TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Il s'agit de Font et Brush pour dessiner du texte sur des images individuelles.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Créer 5 cadres
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Créer une image PNG et y dessiner le numéro de page.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Créer un cadre basé sur l'image PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Ajouter le cadre à l'image TIFF.
        tiffImage.addFrame(frame);
    }

    // L'image a été créée avec un seul cadre par défaut. Supprimons‑le.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // N'oubliez pas de libérer le cadre si vous ne l'ajoutez pas à un autre TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### removeFrame(TiffFrame frame) {#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void removeFrame(TiffFrame frame)
```


Supprimez efficacement la trame spécifiée de la séquence d'images, facilitant une gestion rationalisée des trames dans votre application. Intégrez cette fonctionnalité pour améliorer la précision et la flexibilité de la manipulation des trames, assurant une organisation et une présentation transparentes du contenu d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | La trame à supprimer. |

--------------------

Remarque : n'oubliez pas de disposer la trame si vous ne l'ajoutez pas à un autre TiffImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public final void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Effectuez une opération de redimensionnement proportionnel sur l'image, en préservant son ratio d'aspect tout en ajustant ses dimensions. Utilisez cette méthode pour mettre à l'échelle dynamiquement les images dans votre application, garantissant une représentation visuelle cohérente de l'intégrité du contenu. Le redimensionnement proportionnel redimensionnera chaque trame selon le rapport `newWidth`/width et `newHeight`/height.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ajustez la largeur de l'image tout en conservant son ratio d'aspect, garantissant un redimensionnement proportionnel pour une présentation visuelle optimale. Utilisez cette méthode pour mettre à l'échelle dynamiquement les images dans votre application, facilitant un rendu cohérent et esthétiquement agréable sur divers contextes d'affichage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| resizeType | int | Type de redimensionnement. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Cet exemple charge une image TIFF et la redimensionne proportionnellement en utilisant diverses méthodes de redimensionnement. Seule la largeur est spécifiée, la hauteur est calculée automatiquement.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Effectuez un ajustement proportionnel de la hauteur de l'image, en conservant son ratio d'aspect pour une intégrité visuelle cohérente. Utilisez cette méthode pour redimensionner dynamiquement les images dans votre application, garantissant un affichage optimal sur diverses plateformes et appareils sans compromettre la qualité du contenu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Type de redimensionnement. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Cet exemple charge une image TIFF et la redimensionne proportionnellement en utilisant diverses méthodes de redimensionnement. Seule la hauteur est spécifiée, la largeur est calculée automatiquement.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Effectuez une rotation, un retournement ou une combinaison des deux opérations exclusivement sur la trame active. Cette méthode permet une manipulation précise des trames individuelles au sein de la séquence d'images, améliorant la flexibilité de l'édition et de la composition d'images dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de rotation et de retournement. |


**Example: This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Ceci est une classe d'assistance.
class Utils {
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
Utils utils = new Utils();

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Faites pivoter, retournez et enregistrez dans le fichier de sortie.
    com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.rotateFlipTypeToString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Exécutez le dithering sur l'image actuelle pour améliorer sa qualité visuelle et réduire les artefacts de bandes de couleur. Intégrez cette méthode dans votre flux de traitement d'images afin d'assurer des transitions plus fluides entre les couleurs, ce qui améliore l'apparence globale de l'image et sa clarté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personnalisée pour le tramage. |


**Example: The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Effectuer un dithering par seuil en utilisant une palette de couleurs 4 bits contenant 16 couleurs.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Effectuer un dithering Floyd en utilisant une palette de couleurs 1 bit contenant uniquement 2 couleurs - noir et blanc.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadrez l'image en utilisant une région rectangulaire spécifiée, permettant une sélection précise du contenu souhaité. Intégrez cette méthode dans votre flux de traitement d'images pour supprimer efficacement les zones indésirables et vous concentrer sur les détails essentiels, améliorant ainsi la clarté et la composition globales de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |


**Example: The following example crops a TIFF image.**
L'exemple suivant recadre une image TIFF. La zone de recadrage est spécifiée via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Recadrez l'image. La zone de recadrage est la zone centrale rectangulaire de l'image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            tiffImage.getWidth() / 4, tiffImage.getHeight() / 4, tiffImage.getWidth() / 2, tiffImage.getHeight() / 2);
    tiffImage.crop(area);

    // Enregistrez l'image recadrée au format PNG
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Effectuez le recadrage de l'image en spécifiant des déplacements vers la gauche, la droite, le haut et le bas. Cette méthode permet une sélection précise de la partie souhaitée de l'image, facilitant la suppression efficace des zones indésirables et la mise en avant du contenu essentiel. Intégrez cette fonctionnalité dans votre pipeline de traitement d'images pour améliorer la clarté et la composition selon les besoins de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftShift | int | Le décalage gauche. |
| rightShift | int | Le décalage droit. |
| topShift | int | Le décalage supérieur. |
| bottomShift | int | Le décalage inférieur. |


**Example: The following example crops a TIFF image.**
L'exemple suivant recadre une image TIFF. La zone de recadrage est spécifiée via les marges Gauche, Haut, Droite, Bas.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Recadrez à nouveau. Définissez une marge de 10 % de la taille de l'image.
    int horizontalMargin = tiffImage.getWidth() / 10;
    int verticalMargin = tiffImage.getHeight() / 10;
    tiffImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Enregistrez l'image recadrée au format PNG.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Appliquez la binarisation à l'image en utilisant un seuil prédéfini, la convertissant en une image binaire avec des régions de premier plan et d'arrière-plan distinctes. Intégrez cette méthode dans votre flux de traitement d'images pour faciliter les tâches de segmentation et d'extraction de caractéristiques, améliorant la précision et l'efficacité de l'analyse d'images dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |


**Example: The following example binarizes a TIFF image with the predefined threshold.**
L'exemple suivant binarise une image TIFF avec le seuil prédéfini. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarisez l'image avec une valeur de seuil de 127.
    // Si la valeur de gris correspondante d'un pixel est supérieure à 127, une valeur de 255 lui sera attribuée, sinon 0.
    tiffImage.binarizeFixed((byte) 127);
    tiffImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Utilisez le seuillage d'Otsu pour effectuer la binarisation de l'image, déterminant automatiquement la valeur de seuil optimale en fonction de l'histogramme de l'image. Intégrez cette méthode dans votre flux de traitement d'images pour obtenir une segmentation efficace et une extraction de caractéristiques, améliorant la précision et la fiabilité des tâches d'analyse d'images dans votre application.


**Example: The following example binarizes a TIFF image with Otsu thresholding.**
L'exemple suivant binarise une image TIFF avec le seuillage d'Otsu. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarisez l'image avec le seuillage d'Otsu.
    tiffImage.binarizeOtsu();
    tiffImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Mettez en œuvre la binarisation de l'image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale. Cette approche calcule dynamiquement des seuils locaux en fonction du voisinage de l'image, améliorant l'adaptabilité aux variations d'éclairage et assurant une segmentation robuste pour les tâches de traitement ultérieures dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |
| windowSize | int | La taille de la fenêtre de s × s pixels centrée sur ce pixel |


**Example: The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size.**
L'exemple suivant binarise une image TIFF avec l'algorithme de seuillage adaptatif de Bradley avec la taille de fenêtre spécifiée. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarisez l'image avec une différence de luminosité de 5. La luminosité est une différence entre un pixel et la moyenne d'une fenêtre de 10 x 10 pixels centrée sur ce pixel.
    tiffImage.binarizeBradley(5, 10);
    tiffImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Convertissez l'image en sa représentation en niveaux de gris, la transformant en une image à canal unique où chaque pixel représente l'intensité. Intégrez cette méthode dans votre pipeline de traitement d'images pour simplifier l'analyse et améliorer la compatibilité avec les algorithmes basés sur le niveau de gris, facilitant diverses tâches de vision par ordinateur et d'analyse d'images dans votre application.


**Example: The following example transforms a colored TIFF image to its grayscale representation.**
L'exemple suivant transforme une image TIFF couleur en sa représentation en niveaux de gris. Les images en niveaux de gris sont composées exclusivement de nuances de gris et ne contiennent que des informations d'intensité.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    tiffImage.grayscale();
    tiffImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Appliquez une correction gamma à l'image, ajustant les intensités des pixels pour obtenir le rendu des couleurs souhaité. Intégrez cette méthode dans votre flux de traitement d'images pour améliorer la qualité visuelle et la précision des analyses ou affichages ultérieurs dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |


**Example: The following example performs gamma-correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Définir le coefficient gamma pour les canaux rouge, vert et bleu.
    tiffImage.adjustGamma(2.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Effectuez une correction gamma sur l'image en utilisant des coefficients individuels pour les canaux rouge, vert et bleu, permettant des ajustements fins du rendu des couleurs et du contraste. Intégrez cette méthode dans votre pipeline de traitement d'images pour obtenir un contrôle précis du rendu des couleurs et améliorer la fidélité visuelle dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gammaRed | float | Coefficient gamma pour le canal rouge |
| gammaGreen | float | Coefficient gamma pour le canal vert |
| gammaBlue | float | Gamma pour le coefficient du canal bleu |


**Example: The following example performs gamma-correction of a TIFF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Définir les coefficients gamma individuels pour les canaux rouge, vert et bleu.
    tiffImage.adjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Mettez en œuvre l'ajustement de `brightness` pour l'image, permettant la modification des niveaux de luminance globaux. Intégrez cette méthode dans votre flux de traitement d'images pour améliorer la visibilité et la qualité visuelle des images dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | int | Valeur de luminosité. |


**Example: The following example performs brightness correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Définissez la valeur de luminosité. Les valeurs acceptées de luminosité sont dans la plage [-255, 255].
    tiffImage.adjustBrightness(50);
    tiffImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Améliorez le contraste de l'instance [Image](../../com.aspose.imaging/image), amplifiant les différences entre ses zones claires et sombres. Intégrez cette fonctionnalité pour améliorer la clarté visuelle et la qualité globale de l'image dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contrast | float | Valeur de contraste (dans la plage [-100 ; 100]) |


**Example: The following example performs contrast correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Définissez la valeur de contraste. Les valeurs acceptées de contraste sont dans la plage [-100f, 100f].
    tiffImage.adjustContrast(50f);
    tiffImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtrez le contenu à l'intérieur du rectangle spécifié, en appliquant un filtre de traitement d'image désigné pour améliorer ou modifier la région sélectionnée. Intégrez cette méthode dans votre flux de manipulation d'images pour réaliser des améliorations ou transformations ciblées dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Les options. |


**Example: The following example applies various types of filters to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Appliquez un filtre médian avec une taille de rectangle de 5 à l'ensemble de l'image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    tiffImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'ensemble de l'image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    tiffImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'ensemble de l'image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'ensemble de l'image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    tiffImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ajustez la taille de l'image en fonction des paramètres spécifiés, permettant un contrôle précis des dimensions, du rapport d'aspect et du comportement de mise à l'échelle. Intégrez cette méthode dans votre flux de traitement d'images pour réaliser des opérations de redimensionnement personnalisées adaptées aux exigences spécifiques de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement. |


**Example: This example loads a TIFF image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Réduisez de 2 fois en utilisant le rééchantillonnage adaptatif.
    tiffImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Enregistrer au format PNG
    tiffImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

