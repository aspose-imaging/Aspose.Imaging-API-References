---
title: "WebPImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Manipulez les images raster WebP avec notre API en utilisant ses fonctionnalités modernes pour la compression sans perte et avec perte, garantissant une qualité d'image optimale avec des tailles de fichier réduites."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Manipulez les images raster WebP avec notre API, en utilisant ses fonctionnalités modernes pour la compression sans perte et avec perte, garantissant une qualité d'image optimale avec des tailles de fichier réduites. Gérez sans effort les formats de fichiers étendus, les animations et les canaux alpha, tout en mettant facilement à jour les dimensions, en redimensionnant proportionnellement, en recadrant, en faisant pivoter, en appliquant des filtres, en ajustant les paramètres d'image et en convertissant vers d'autres formats d'image pour une optimisation polyvalente des images web.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | Instanciez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisée à partir d'un flux fourni. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Créez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) en utilisant un flux et des options de chargement spécifiées, facilitant la gestion polyvalente des données d'image WebP. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | Instanciez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisée à partir d'un fichier fourni. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | Créez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) en utilisant un fichier et des options de chargement spécifiées, facilitant la gestion flexible des données d'image WebP. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | Instanciez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisée à partir d'un objet rasterImage fourni. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | Créez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) en utilisant un objet rasterImage et des options de chargement spécifiées, permettant une gestion flexible des données d'image. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | Instanciez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) avec une image vide aux dimensions de largeur et de hauteur spécifiées. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | Créez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) avec une image vide et des options de chargement spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOptions()](#getOptions--) | Récupérez ou modifiez les options associées à la propriété spécifiée, permettant une personnalisation fine du comportement et des paramètres. |
| [getPages()](#getPages--) | Accédez aux blocs WebP de l'image, permettant un examen détaillé ou une manipulation de la structure de blocs sous-jacente. |
| [getPageCount()](#getPageCount--) | Récupérez le nombre total de pages du document spécifié, facilitant une navigation efficace et la gestion du contenu multipage. |
| [getFileFormat()](#getFileFormat--) | Accédez à la valeur du format de fichier associée à l'image, fournissant des informations sur le format dans lequel l'image est stockée. |
| [hasAlpha()](#hasAlpha--) | Récupérez si l'image contient un canal alpha, indiquant la présence d'informations de transparence. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Ajoutez une nouvelle page à l'image, élargissant son contenu et accueillant des éléments visuels supplémentaires. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Incorporez un nouveau bloc WebP dans l'image, enrichissant son contenu et facilitant une manipulation avancée de l'image. |
| [clearBlocks()](#clearBlocks--) | Effacez tous les blocs WebP existants de l'image, offrant une base propre pour les modifications ou ajouts ultérieurs. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | Insérez un nouveau bloc WebP à l'index spécifié dans l'image, permettant un contrôle précis de la séquence des blocs. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Supprimez le bloc WebP spécifié de l'image, facilitant une gestion efficace de la structure des données d'image. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options basées sur les paramètres du fichier original. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Faites pivoter l'image autour de son centre d'un angle spécifié, tout en la redimensionnant proportionnellement et en appliquant les paramètres de couleur d'arrière-plan spécifiés. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionnez l'image, en ajustant ses dimensions tout en préservant le rapport d'aspect. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ajustez proportionnellement la largeur de l'image tout en maintenant son rapport d'aspect. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ajustez la hauteur de l'image proportionnellement, tout en préservant son rapport d'aspect pour un redimensionnement cohérent. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Appliquez une rotation, un retournement ou les deux opérations exclusivement à la trame active de l'image. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Effectuez un dithering sur l'image actuelle pour réduire le banding des couleurs et améliorer la qualité visuelle. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadrez l'image en utilisant une région rectangulaire spécifiée, en supprimant les parties indésirables tout en conservant le contenu souhaité. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Recadrez l'image en appliquant des déplacements à gauche, à droite, en haut et en bas, sélectionnant ainsi efficacement une région d'intérêt dans l'image. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Effectuez une binarisation de l'image en utilisant une valeur de seuil prédéfinie, la convertissant en une image binaire où les pixels sont classés comme premier plan ou arrière-plan en fonction de leur intensité par rapport au seuil. |
| [binarizeOtsu()](#binarizeOtsu--) | Effectuez une binarisation de l'image en utilisant la méthode de seuillage d'Otsu, déterminant automatiquement la valeur de seuil optimale à partir de l'histogramme de l'image. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Appliquez une binarisation à l'image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale. |
| [grayscale()](#grayscale--) | Appliquez une binarisation à l'image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Appliquez une correction gamma à l'image, ajustant les intensités des pixels pour obtenir la luminosité et la balance des couleurs souhaitées. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Effectuez une correction gamma sur l'image en utilisant des coefficients individuels pour les canaux rouge, vert et bleu, permettant des ajustements fins de la balance des couleurs et du contraste. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Mettez en œuvre le réglage de `brightness` pour l'image, permettant la modification des niveaux de luminance globaux. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Améliorez le contraste de l'[Image](../../com.aspose.imaging/image), amplifiant les différences entre les zones claires et sombres. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtrez le contenu à l'intérieur du rectangle spécifié, en appliquant un filtre de traitement d'image désigné pour améliorer ou modifier la région sélectionnée. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionnez l'image selon les paramètres spécifiés, permettant un contrôle précis des dimensions, du rapport d'aspect et du comportement de mise à l'échelle. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Chargez une image WebP à partir d'un fichier.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // Enregistrer au format PNG
    // Notez que seul le cadre actif sera enregistré au format PNG, car le PNG n'est pas un format multi-pages.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


Instanciez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisée à partir d'une source de flux fournie. Utilisez ce constructeur pour créer de manière transparente des objets d'image WebP directement à partir de flux, permettant une gestion et une manipulation efficaces des données d'image WebP dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | L'image WebP du flux. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


Créez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) en utilisant un flux et des options de chargement spécifiées, facilitant la gestion polyvalente des données d'image WebP. Intégrez ce constructeur pour initialiser de manière transparente des objets d'image WebP à partir de flux tout en personnalisant les paramètres de chargement selon les besoins de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | L'image WebP du flux. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


Instanciez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisée à partir d'une source de fichier fournie. Utilisez ce constructeur pour créer de manière transparente des objets d'image WebP directement à partir de fichiers, simplifiant le processus de chargement et de manipulation des données d'image WebP dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin vers le fichier d'image WebP |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


Créez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) en utilisant un fichier et des options de chargement spécifiées, facilitant la gestion flexible des données d'image WebP. Utilisez ce constructeur pour initialiser de manière transparente des objets d'image WebP à partir de fichiers tout en personnalisant les paramètres de chargement selon les exigences de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin vers le fichier d'image WebP |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


Instanciez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisée à partir d'un objet rasterImage fourni. Ce constructeur permet une conversion transparente des images raster au format WebP, permettant une gestion et une manipulation efficaces des données d'image dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


Créez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) en utilisant un objet rasterImage et des options de chargement spécifiées, permettant une gestion flexible des données d'image. Utilisez ce constructeur pour initialiser de manière transparente des objets d'image WebP à partir d'images raster tout en personnalisant les paramètres de chargement selon les exigences de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image raster. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


Instanciez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) avec une image vide aux dimensions de largeur et de hauteur spécifiées. Ce constructeur permet la création d'images WebP vierges, offrant une base pour les manipulations d'image ultérieures et la génération de contenu dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image |
| height | int | La hauteur de l'image. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Les options. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


Créez une nouvelle instance de la classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) avec une image vide et des options de chargement spécifiées. Ce constructeur permet l'initialisation d'images WebP avec des paramètres de chargement personnalisables, offrant une flexibilité dans la création et la manipulation d'images dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image |
| height | int | La hauteur de l'image. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Les options. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


Récupérez ou modifiez les options associées à la propriété spécifiée, permettant une personnalisation fine du comportement et des paramètres. Utilisez cette propriété pour accéder et manipuler de manière transparente les paramètres configurables, facilitant un contrôle polyvalent et une optimisation au sein de la fonctionnalité de votre application.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accédez aux blocs WebP de l'image, permettant un examen détaillé ou une manipulation de la structure de blocs sous-jacente. Utilisez cette propriété pour analyser ou modifier les blocs individuels des données d'image WebP, facilitant des techniques avancées de traitement d'image dans votre application.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Récupérez le nombre total de pages du document spécifié, facilitant une navigation efficace et la gestion de contenu multipage. Intégrez cette fonctionnalité pour améliorer l'expérience utilisateur, permettant un accès fluide à des structures de documents complètes.

**Returns:**
int - le nombre de pages.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accédez à la valeur du format de fichier associée à l'image, fournissant des informations sur le format dans lequel l'image est stockée. Utilisez cette propriété pour déterminer le format de fichier de l'image, facilitant les vérifications de compatibilité et le traitement spécifique au format dans votre application.

**Returns:**
long - une valeur du format de fichier
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Déterminez si l'image contient un canal alpha, indiquant la présence d'informations de transparence. Utilisez cette propriété pour savoir si l'image inclut de la transparence, permettant une gestion et un traitement appropriés des opérations liées à l'alpha dans votre application.

**Returns:**
boolean - `true` s'il y a un canal alpha.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Si la trame TIFF active possède un canal alpha, alors l'ensemble de l'image TIFF est considéré comme ayant un canal alpha.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// ImageFile=c:\\temp\\sample.webp, FileFormat=RgbIndexed1Bpp, canaux utilisés : 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, canaux utilisés : 1, HasAlpha=False
```

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Ajoutez une nouvelle page à l'image, élargissant son contenu et accueillant des éléments visuels supplémentaires. Intégrez cette méthode pour faciliter la gestion dynamique des pages dans votre application, permettant une création et une augmentation transparentes de documents ou d'images multipages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La page à ajouter. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


Incorporez un nouveau bloc WebP dans l'image, enrichissant son contenu et facilitant la manipulation avancée d'images. Intégrez cette méthode pour améliorer dynamiquement la structure et la complexité des données d'image WebP au sein de votre application, permettant un contrôle précis et une optimisation du rendu d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Le bloc Webp à ajouter. |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// Le cadre par défaut plus 36 + 36 cadres supplémentaires.
createOptions.setAnimLoopCount(36 + 36 + 1);

// Créez une image WebP de 100x100 px.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // Le premier cercle est rouge
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Le deuxième cercle est noir
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Augmentez progressivement l'angle de la forme d'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // Augmentez progressivement l'angle de l'arc noir et effacez l'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // Enregistrez dans un fichier WebP
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Supprimez tous les blocs WebP existants de l'image, facilitant une base propre pour les modifications ou ajouts ultérieurs. Utilisez cette méthode pour réinitialiser efficacement la structure des blocs dans les données d'image WebP, assurant une gestion et une organisation optimales du contenu de l'image au sein de votre application.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


Insérez un nouveau bloc WebP à l'index spécifié dans l'image, permettant un contrôle précis de la séquence des blocs. Intégrez cette méthode pour incorporer sans effort des blocs WebP supplémentaires dans la structure des données d'image, facilitant le traitement avancé d'images et l'optimisation au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'élément indexé à zéro, où `block` sera inséré. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Le bloc Webp à ajouter. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


Supprimez le bloc WebP spécifié de l'image, facilitant une gestion efficace de la structure des données d'image. Utilisez cette méthode pour rationaliser les flux de travail de traitement d'images en éliminant les blocs ou composants inutiles au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Le bloc à supprimer. |

--------------------

Remarque : n'oubliez pas de disposer le `block` si vous ne l'ajoutez pas à un autre WebPImage. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) , une image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Faites pivoter l'image autour de son centre d'un angle spécifié, tout en la redimensionnant proportionnellement et en appliquant les paramètres de couleur d'arrière-plan spécifiés. Intégrez cette méthode dans votre flux de traitement d'images pour obtenir des transformations précises avec des couleurs d'arrière-plan personnalisables, assurant une présentation visuelle optimale au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resizeProportionally | boolean | si défini sur `true` vous verrez la taille de votre image modifiée selon les projections du rectangle tourné (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul `` le contenu de l'image est tourné. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensionnez l'image, ajustant ses dimensions tout en préservant le rapport d'aspect. Intégrez cette méthode dans votre flux de traitement d'images pour mettre à l'échelle dynamiquement les images afin de répondre à diverses exigences d'affichage ou de stockage au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ajustez proportionnellement la largeur de l'image tout en maintenant son rapport d'aspect. Intégrez cette méthode dans votre flux de traitement d'images pour redimensionner dynamiquement les images avec des proportions cohérentes, assurant un affichage ou un stockage optimal au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| resizeType | int | Type de redimensionnement. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ajustez proportionnellement la hauteur de l'image, tout en préservant son rapport d'aspect pour un redimensionnement cohérent. Intégrez cette méthode dans votre flux de traitement d'images pour redimensionner dynamiquement les images avec des proportions uniformes, assurant un affichage ou un stockage optimal au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Type de redimensionnement. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Appliquez une rotation, un retournement ou les deux opérations exclusivement à la trame active de l'image. Intégrez cette méthode dans votre flux de traitement d'images pour obtenir une manipulation précise des trames individuelles, améliorant la flexibilité et le contrôle des transformations de trames au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de rotation/retournement. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Effectuez un dithering sur l'image actuelle pour réduire le banding des couleurs et améliorer la qualité visuelle. Intégrez cette méthode dans votre flux de traitement d'images afin d'obtenir des transitions plus fluides entre les couleurs et d'améliorer l'apparence globale de l'image au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personnalisée pour le tramage. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadrez l'image en utilisant une région rectangulaire spécifiée, en supprimant les parties indésirables tout en conservant le contenu souhaité. Intégrez cette méthode dans votre flux de traitement d'images pour extraire et cibler précisément des zones d'intérêt spécifiques dans l'image, améliorant la clarté et la composition pour diverses applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Recadrez l'image en appliquant des déplacements à gauche, à droite, en haut et en bas, sélectionnant ainsi efficacement une région d'intérêt dans l'image. Utilisez cette méthode pour extraire dynamiquement les portions souhaitées de l'image tout en ajustant sa composition et son focus selon les exigences de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftShift | int | Le décalage gauche. |
| rightShift | int | Le décalage droit. |
| topShift | int | Le décalage supérieur. |
| bottomShift | int | Le décalage inférieur. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Effectuez une binarisation de l'image en utilisant une valeur de seuil prédéfinie, la convertissant en une image binaire où les pixels sont classés comme premier plan ou arrière-plan en fonction de leur intensité par rapport au seuil. Intégrez cette méthode dans votre flux de traitement d'images pour faciliter les tâches de segmentation et d'extraction de caractéristiques, améliorant la précision et l'efficacité des analyses ultérieures au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de (byte)255 lui sera attribuée, sinon 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Effectuez la binarisation de l'image en utilisant la méthode de seuillage d'Otsu, déterminant automatiquement la valeur de seuil optimale à partir de l'histogramme de l'image. Intégrez cette méthode dans votre flux de traitement d'image pour obtenir une segmentation efficace et une extraction de caractéristiques, améliorant la précision et la fiabilité des tâches d'analyse d'image au sein de votre application.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Appliquez la binarisation à l'image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale. Cette méthode calcule dynamiquement des seuils locaux en fonction du voisinage de l'image, améliorant l'adaptabilité aux variations d'éclairage et garantissant une segmentation robuste pour les tâches de traitement ultérieures au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |
| windowSize | int | La taille de la fenêtre de s × s pixels centrée sur ce pixel |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Appliquez la binarisation à l'image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale. Cette méthode calcule dynamiquement des seuils locaux en fonction du voisinage de l'image, améliorant l'adaptabilité aux variations d'éclairage et garantissant une segmentation robuste pour les tâches de traitement ultérieures au sein de votre application.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Appliquez une correction gamma à l'image, ajustant les intensités des pixels pour obtenir la luminosité et la balance des couleurs souhaitées. Intégrez cette méthode dans votre flux de traitement d'image afin d'améliorer la qualité visuelle et d'accroître la précision des analyses ou affichages ultérieurs au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Effectuez une correction gamma sur l'image en utilisant des coefficients individuels pour les canaux rouge, vert et bleu, permettant des ajustements fins de la balance des couleurs et du contraste. Intégrez cette méthode dans votre pipeline de traitement d'image pour obtenir un contrôle précis du rendu des couleurs et améliorer la fidélité visuelle au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gammaRed | float | Coefficient gamma pour le canal rouge |
| gammaGreen | float | Coefficient gamma pour le canal vert |
| gammaBlue | float | Gamma pour le coefficient du canal bleu |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Mettez en œuvre l'ajustement de `brightness` pour l'image, permettant la modification des niveaux de luminance globaux. Intégrez cette méthode dans votre flux de traitement d'images pour améliorer la visibilité et la qualité visuelle des images dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | int | Valeur de luminosité. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Améliorez le contraste de l'[Image](../../com.aspose.imaging/image), amplifiant les différences entre les zones claires et sombres. Intégrez cette méthode dans votre flux de traitement d'image pour améliorer la clarté visuelle et la qualité globale de l'image au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contrast | float | Valeur de contraste (dans la plage [-100 ; 100]) |

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


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Appliquez un filtre médian avec une taille de rectangle de 5 à l'ensemble de l'image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'ensemble de l'image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'ensemble de l'image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'ensemble de l'image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionnez l'image selon les paramètres spécifiés, permettant un contrôle précis des dimensions, du rapport d'aspect et du comportement de mise à l'échelle. Intégrez cette méthode dans votre flux de traitement d'image pour réaliser des opérations de redimensionnement personnalisées adaptées aux exigences spécifiques de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement. |

