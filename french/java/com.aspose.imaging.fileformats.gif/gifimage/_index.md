---
title: "GifImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API pour le fichier image Graphical Interchange Format GIF fournit aux développeurs des outils polyvalents pour le traitement des images raster compressées et des GIF animés."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

L'API pour le fichier image Graphical Interchange Format (GIF) fournit aux développeurs des outils polyvalents pour le traitement des images raster compressées et des GIF animés. Elle offre des fonctionnalités telles que la gestion des métadonnées XMP, les réglages de la palette de couleurs, le contrôle du fond et de la couleur transparente, les réglages d'opacité, le redimensionnement, le recadrage, l'application de filtres, les corrections gamma, le réglage du contraste, la transformation en niveaux de gris, et la conversion vers d'autres formats. Cette API permet une manipulation et une amélioration fluides des images GIF pour un large éventail d'applications.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | Initialisez un nouvel objet [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) avec les paramètres spécifiés pour la première trame et la palette globale. |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Créer des images GIF devient facile avec le constructeur [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | Commencez facilement avec le constructeur [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Récupérez le format de fichier facilement avec cette propriété. |
| [hasTrailer()](#hasTrailer--) | Gérez la présence d'une bande-annonce dans vos fichiers GIF avec cette propriété. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Gérez la présence d'une bande-annonce dans vos fichiers GIF avec cette propriété. |
| [isPaletteSorted()](#isPaletteSorted--) | Contrôlez le tri de la palette dans vos images GIF en utilisant cette propriété. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Contrôlez le tri de la palette dans vos images GIF en utilisant cette propriété. |
| [getLoopsCount()](#getLoopsCount--) | Récupérez le nombre de boucles sans effort avec cette propriété. |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Récupérez le nombre de boucles sans effort avec cette propriété. |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | Gérez la résolution des couleurs de la palette de vos images GIF avec cette propriété. |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | Gérez la résolution des couleurs de la palette de vos images GIF avec cette propriété. |
| [getPageCount()](#getPageCount--) | Récupérez le nombre total de pages contenues dans l'image avec cette propriété simple. |
| [getPages()](#getPages--) | Accédez aux pages de l'image via cette propriété pratique, permettant une navigation fluide et la manipulation des pages individuelles selon les besoins. |
| [getBlocks()](#getBlocks--) | Accédez aux blocs GIF de manière fluide avec cette propriété, facilitant la récupération et la manipulation faciles des structures de données sous-jacentes de l'image. |
| [isInterlaced()](#isInterlaced--) | Détermine si l'image est entrelacée, affectant son affichage lors du chargement. |
| [getOriginalOptions()](#getOriginalOptions--) | Récupérez les options basées sur les paramètres du fichier original, essentielles pour maintenir la fidélité et la cohérence lors du traitement et de la manipulation d'images. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Intégrez une nouvelle page de manière fluide dans l'image existante, améliorant son contenu et élargissant sa portée. |
| [getActiveFrame()](#getActiveFrame--) | Gérez et manipulez les cadres avec cette propriété, permettant une navigation fluide et la modification du cadre actif dans l'image GIF. |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Gérez et manipulez les cadres avec cette propriété, permettant une navigation fluide et la modification du cadre actif dans l'image GIF. |
| [getBackgroundColor()](#getBackgroundColor--) | Gérez la couleur d'arrière-plan de l'image GIF avec cette propriété. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Gérez la couleur d'arrière-plan de l'image GIF avec cette propriété. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Contrôlez l'index de la couleur d'arrière-plan de l'image GIF en utilisant cette propriété. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Contrôlez l'index de la couleur d'arrière-plan de l'image GIF en utilisant cette propriété. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Gérez le rapport d'aspect des pixels de l'image GIF avec cette propriété. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Gérez le rapport d'aspect des pixels de l'image GIF avec cette propriété. |
| [hasTransparentColor()](#hasTransparentColor--) | Déterminez si le cadre actif de l'image GIF comprend une couleur transparente. |
| [getTransparentColor()](#getTransparentColor--) | Récupérez la couleur transparente du cadre actif dans l'image GIF. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Déterminez si le cadre actif de l'image GIF comprend une couleur transparente. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Cette propriété détermine si l'image GIF contient une couleur d'arrière-plan. |
| [getImageOpacity()](#getImageOpacity--) | Récupérez l'opacité du cadre actif dans l'image, offrant un aperçu de son niveau de transparence. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionne cette instance [Image](../../com.aspose.imaging/image). |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne cette instance [Image](../../com.aspose.imaging/image). |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | Redimensionnement de l'image en tenant compte de tous les cadres de chaque page dans un GIF, évitant ainsi l'apparition d'éventuels artefacts. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Effectuez une rotation, un retournement ou les deux sur le cadre actif uniquement. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Appliquez le tramage à l'image actuelle. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadrez l'image en utilisant une zone rectangulaire spécifiée. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Améliorez la qualité de l'image en appliquant une correction gamma. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Appliquez un filtre spécifique à la zone désignée de l'image, améliorant sa qualité visuelle ou modifiant son apparence selon vos souhaits. |
| [setFrameTime(int time)](#setFrameTime-int-) | Ajuste la durée de chaque image en millisecondes, garantissant une synchronisation constante tout au long de la séquence d'images. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajuste la luminosité de l'image selon le paramètre `brightness` spécifié. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Ajuste le contraste de l'image, augmentant ou réduisant la différence de luminosité entre les pixels. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | La correction gamma d'une image applique un ajustement non linéaire des valeurs des pixels, augmentant ou réduisant la luminosité en fonction des coefficients spécifiés pour les canaux rouge, vert et bleu. |
| [grayscale()](#grayscale--) | La transformation d'une image en sa représentation en niveaux de gris convertit l'image couleur en une version en niveaux de gris en supprimant les informations de couleur tout en préservant la luminance. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | La binarisation d'une image avec un seuil prédéfini convertit une image en niveaux de gris ou couleur en une image binaire, où chaque pixel est classé comme noir ou blanc en fonction de si sa valeur d'intensité dépasse un seuil spécifié. |
| [binarizeOtsu()](#binarizeOtsu--) | La binarisation d'une image avec le seuillage d'Otsu est une méthode utilisée pour déterminer automatiquement la valeur de seuil optimale afin de convertir une image en niveaux de gris en une image binaire. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | La binarisation d'une image utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale est une méthode pour convertir une image en niveaux de gris en une image binaire. |
| [orderBlocks()](#orderBlocks--) | L'ordre des blocs GIF selon la spécification GIF garantit une disposition correcte du GIF et la conformité à la norme. |
| [clearBlocks()](#clearBlocks--) | Effacer tous les blocs GIF supprime toutes les données existantes stockées dans l'image. |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | Insérer un nouveau bloc GIF vous permet d'ajouter des données personnalisées à une position spécifique dans l'image. |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Ajouter un nouveau bloc GIF vous permet d'inclure des données supplémentaires dans l'image. |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Supprimer un bloc GIF enlève des données spécifiques de l'image, offrant la possibilité de nettoyer ou de modifier la structure de l'image. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Le redimensionnement proportionnel maintient le rapport d'aspect de l'image tout en ajustant sa taille, garantissant que l'image ne semble pas étirée ou déformée. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Cette méthode fait pivoter l'image autour de son point central. |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// Créez un bloc de trame GIF de 100x100 px.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // Remplissez tout le bloc en rouge.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // Charger les trames
    RasterImage[] frames = loadFrames("Animation frames");

    // Créer une image GIF en utilisant la première trame
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Ajouter des trames à l'image GIF en utilisant la méthode AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Enregistrer l'image GIF
        image.save("Multipage.gif");
    }

    // libérer les ressources
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


Initiez un nouveau objet [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) avec les paramètres spécifiés pour la première trame et la palette globale. Commencez à gérer les images GIF rapidement, en assurant une représentation précise avec des paramètres personnalisables pour des résultats optimaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | La première trame avec laquelle initialiser l'image GIF. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette globale à utiliser. Notez que si `firstFrame` et `globalPalette` sont tous deux null, alors la palette globale par défaut est utilisée. |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


Créer des images GIF devient facile avec le constructeur [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). Avec simplement le paramètre firstFrame, vous entrez dans un monde de communication visuelle dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | La première trame avec laquelle initialiser l'image GIF. |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


Commencez facilement avec le constructeur [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). Avec cette méthode simple, vous pouvez vous lancer dans la création de GIF animés en toute simplicité. Il suffit de fournir les paramètres firstFrame, globalPalette, paletteColorResolution, aspectRatio et d'autres, et vous êtes prêt à donner vie à vos visuels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | La première trame avec laquelle initialiser l'image GIF. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette globale à utiliser. Notez que si `firstFrame` et `globalPalette` sont tous deux null, alors la palette globale par défaut est utilisée. |
| isPaletteSorted | boolean | si réglé sur `true`, la palette est triée. Notez que le paramètre est utilisé lorsque `globalPalette` n'est pas nul. |
| paletteColorResolution | byte | La résolution des couleurs de la palette. Notez que le paramètre est utilisé lorsque `globalPalette` n'est pas nul. |
| paletteBackgroundColorIndex | byte | L'index de couleur d'arrière-plan de la palette. |
| aspectRatio | byte | Le rapport d'aspect. |
| hasTrailer | boolean | si réglé sur `true`, l'image GIF possède un trailer, sinon aucun trailer n'est écrit à la fin du flux. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez le format de fichier facilement avec cette propriété. C'est votre source de référence pour identifier le format de vos fichiers. Intégrée de manière transparente à votre flux de travail, elle fournit des informations essentielles sans aucun effort.

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Gérez la présence d'un trailer dans vos fichiers GIF avec cette propriété. Que vous ayez besoin de vérifier si un trailer existe ou de définir sa présence, cette propriété simplifie le processus. Gardez vos fichiers GIF structurés et conformes grâce à cette fonctionnalité intuitive.

**Returns:**
booléen - `true` si le GIF a un trailer ; sinon, `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Gérez la présence d'un trailer dans vos fichiers GIF avec cette propriété. Que vous ayez besoin de vérifier si un trailer existe ou de définir sa présence, cette propriété simplifie le processus. Gardez vos fichiers GIF structurés et conformes grâce à cette fonctionnalité intuitive.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si le GIF a un trailer ; sinon, `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Contrôlez le tri de la palette dans vos images GIF à l'aide de cette propriété. Que vous ayez besoin de vérifier si la palette est triée ou de définir le comportement de tri, cette propriété offre une méthode simple pour gérer l'organisation de la palette dans vos fichiers GIF.

**Returns:**
booléen - `true` si la palette est triée ; sinon, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Contrôlez le tri de la palette dans vos images GIF à l'aide de cette propriété. Que vous ayez besoin de vérifier si la palette est triée ou de définir le comportement de tri, cette propriété offre une méthode simple pour gérer l'organisation de la palette dans vos fichiers GIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si la palette est triée ; sinon, `false`. |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


Récupérez le nombre de boucles facilement avec cette propriété. Si votre image GIF inclut des informations de boucle, cette propriété vous donne un accès rapide au nombre de boucles, vous permettant de gérer sans effort le comportement de boucle dans vos fichiers GIF.

**Returns:**
int - Le nombre de boucles ou 1 (valeur par défaut)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


Récupérez le nombre de boucles facilement avec cette propriété. Si votre image GIF inclut des informations de boucle, cette propriété vous donne un accès rapide au nombre de boucles, vous permettant de gérer sans effort le comportement de boucle dans vos fichiers GIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le nombre de boucles ou 1 (valeur par défaut) |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


Gérez la résolution des couleurs de la palette de vos images GIF avec cette propriété. Ajustez le nombre de bits utilisés pour représenter les couleurs dans la palette, offrant un contrôle précis sur la profondeur de couleur et la qualité de l'image.

**Returns:**
byte - Les bits de résolution des couleurs de la palette.
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


Gérez la résolution des couleurs de la palette de vos images GIF avec cette propriété. Ajustez le nombre de bits utilisés pour représenter les couleurs dans la palette, offrant un contrôle précis sur la profondeur de couleur et la qualité de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | Les bits de résolution des couleurs de la palette. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Récupérez le nombre total de pages contenues dans l'image avec cette propriété simple. Idéal pour évaluer rapidement l'étendue du contenu de l'image.

**Returns:**
int - le nombre de pages.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accédez aux pages de l'image via cette propriété pratique, permettant une navigation fluide et la manipulation des pages individuelles selon les besoins.

**Returns:**
com.aspose.imaging.Image[] - les pages.
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


Accédez aux blocs GIF de manière fluide avec cette propriété, facilitant la récupération et la manipulation faciles des structures de données sous-jacentes de l'image.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - les blocs GIF.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Détermine si l'image est entrelacée, ce qui affecte son affichage lors du chargement. Cette propriété offre un aperçu du comportement de rendu de l'image, essentiel pour optimiser les stratégies de chargement et améliorer l'expérience de visualisation globale.

**Returns:**
booléen - `true` si cette instance d'image est entrelacée ; sinon, `false`.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Récupérez les options basées sur les paramètres du fichier d'origine, essentielles pour maintenir la fidélité et la cohérence dans le traitement et la manipulation d'images. Cette méthode permet une intégration transparente des paramètres spécifiques au fichier dans les opérations ultérieures, garantissant une restitution précise et le respect des caractéristiques inhérentes de l'image. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir et blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\\#save-String-), l'image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et transmettez‑les à la méthode [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\\#save-String--ImageOptionsBase-) en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Incorporez une nouvelle page de manière transparente dans l'image existante, en améliorant son contenu et en élargissant sa portée. Cette méthode augmente les collections d'images avec du contenu supplémentaire, favorisant la créativité et la flexibilité dans la gestion et la composition d'images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La page à ajouter. |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // Charger les trames
    RasterImage[] frames = loadFrames("Animation frames");

    // Créer une image GIF en utilisant la première trame
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Ajouter des trames à l'image GIF en utilisant la méthode AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Enregistrer l'image GIF
        image.save("Multipage.gif");
    }

    // libérer les ressources
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


Gérez et manipulez les cadres avec cette propriété, permettant une navigation fluide et la modification du cadre actif dans l'image GIF.

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Le résultat ressemble à ceci :
// Taille de la trame active : { Width = 100, Height = 100}
// Effacer tous les blocs
// La trame active n'est pas définie
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


Gérez et manipulez les cadres avec cette propriété, permettant une navigation fluide et la modification du cadre actif dans l'image GIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | la trame active. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gérez la couleur d'arrière‑plan de l'image GIF avec cette propriété. Vous pouvez définir ou récupérer la couleur d'arrière‑plan pour assurer la cohérence et améliorer l'attrait visuel.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Gérez la couleur d'arrière‑plan de l'image GIF avec cette propriété. Vous pouvez définir ou récupérer la couleur d'arrière‑plan pour assurer la cohérence et améliorer l'attrait visuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | la couleur d'arrière-plan. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Contrôlez l'index de la couleur d'arrière‑plan de l'image GIF à l'aide de cette propriété. Définissez ou récupérez l'index pour maintenir la cohérence ou obtenir les effets visuels souhaités.

**Returns:**
octet - l'index de la couleur d'arrière‑plan.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Contrôlez l'index de la couleur d'arrière‑plan de l'image GIF à l'aide de cette propriété. Définissez ou récupérez l'index pour maintenir la cohérence ou obtenir les effets visuels souhaités.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | l'index de la couleur d'arrière‑plan. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Gérez le rapport d'aspect des pixels de l'image GIF avec cette propriété. Définissez ou récupérez le rapport d'aspect pour garantir un rendu précis et maintenir la fidélité visuelle.

**Returns:**
octet - le rapport d'aspect des pixels.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Gérez le rapport d'aspect des pixels de l'image GIF avec cette propriété. Définissez ou récupérez le rapport d'aspect pour garantir un rendu précis et maintenir la fidélité visuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | le rapport d'aspect des pixels. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Déterminez si la trame active de l'image GIF comprend une couleur transparente. Cette propriété offre un moyen pratique de vérifier la transparence dans l'image.

**Returns:**
booléen - une valeur indiquant si la trame active possède une couleur transparente.
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Récupérez la couleur transparente de la trame active dans l'image GIF. Cette propriété vous permet d'accéder à la couleur spécifique qui a été désignée comme transparente dans la trame actuellement active.

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Déterminez si la trame active de l'image GIF comprend une couleur transparente. Cette propriété offre un moyen pratique de vérifier la transparence dans l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si la trame active possède une couleur transparente. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Cette propriété détermine si l'image GIF contient une couleur d'arrière‑plan. Si vrai, elle indique que l'image inclut une couleur d'arrière‑plan.

**Returns:**
booléen - une valeur indiquant si l'image possède une couleur d'arrière‑plan.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Récupérez l'opacité de la trame active dans l'image, offrant un aperçu de son niveau de transparence. Cette propriété est particulièrement utile pour comprendre le degré de transparence ou d'opacité de la trame active dans l'image.

La valeur d'opacité entre 0,0 (totalement transparent) et 1,0 (totalement opaque).

**Returns:**
flottant - opacité de cette image (trame active).
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensionne cette instance [Image](../../com.aspose.imaging/image).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionne cette instance [Image](../../com.aspose.imaging/image).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres. |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Réduisez de 2 fois en utilisant le rééchantillonnage adaptatif.
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Enregistrer au format PNG
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


Redimensionnement de l'image en tenant compte de toutes les trames de chaque page d'un GIF, évitant ainsi l'apparition d'éventuels artefacts. Cette méthode est essentielle pour préserver l'intégrité et la qualité de l'image, en particulier lors du traitement de GIF animés ou de séquences de trames.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Effectuez une rotation, un retournement ou les deux sur la trame active uniquement. Cette opération applique des transformations uniquement à la trame actuellement active de l'image, en préservant l'intégrité des autres trames de la séquence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de rotation/retournement. |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// La classe d'assistance utilisée dans l'exemple principal ci-dessous.
class Utils {
    // La méthode d'assistance pour obtenir une représentation sous forme de chaîne du format de fichier.
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// Voici l'exemple principal
Utils utils = new Utils();

String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Faites pivoter, retournez et enregistrez dans le fichier de sortie.
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Appliquez le dithering à l'image actuelle. Ce processus améliore la qualité de l'image en réduisant le banding des couleurs et en améliorant les transitions de couleur, ce qui donne un aspect plus lisse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personnalisée pour le tramage. |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Effectuer un dithering par seuil en utilisant une palette de couleurs 4 bits contenant 16 couleurs.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Effectuer un dithering Floyd en utilisant une palette de couleurs 1 bit contenant uniquement 2 couleurs - noir et blanc.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadrez l'image en utilisant une zone rectangulaire spécifiée. Cette opération supprime la partie extérieure de l'image, ne laissant que la région sélectionnée définie par le rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |


**Example: The following example crops a GIF image.**
L'exemple suivant recadre une image GIF. La zone de recadrage est spécifiée via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Recadrez l'image. La zone de recadrage est la zone centrale rectangulaire de l'image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // Enregistrez l'image recadrée au format PNG
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Améliorez la qualité de l'image en appliquant une correction gamma. Cette méthode ajuste le gamma de couleur de l'image pour obtenir une clarté visuelle optimale. Elle modifie la valeur gamma de chaque pixel, ce qui améliore la restitution des couleurs et l'apparence générale de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Définir le coefficient gamma pour les canaux rouge, vert et bleu.
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Appliquez un filtre spécifique à la zone désignée de l'image, améliorant sa qualité visuelle ou modifiant son apparence selon vos besoins. Cette méthode traite sélectivement les pixels à l'intérieur du rectangle défini, permettant des ajustements ciblés tout en préservant l'intégrité des données d'image environnantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Les options. |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Appliquez un filtre médian avec une taille de rectangle de 5 à l'ensemble de l'image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'ensemble de l'image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'ensemble de l'image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'ensemble de l'image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


Ajuste la durée de chaque trame en millisecondes, garantissant un timing cohérent tout au long de la séquence d'images. Cette méthode définit uniformément le temps d'affichage de chaque trame, permettant un contrôle précis de la vitesse d'animation. Modifier cette valeur réinitialisera le délai pour toutes les trames.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| temps | int | Le temps de durée de la trame en millisecondes. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajuste la luminosité de l'image selon le paramètre `brightness` spécifié. Cette méthode modifie uniformément la luminosité de l'image entière, augmentant ou réduisant la luminance globale pour obtenir l'effet souhaité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | int | Valeur de luminosité. |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Définissez la valeur de luminosité. Les valeurs acceptées de luminosité sont dans la plage [-255, 255].
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Ajuste le contraste de l'image, augmentant ou réduisant la différence de luminosité entre les pixels. Cette méthode modifie la plage tonale globale de l'image, rendant les zones sombres plus sombres et les zones claires plus claires afin d'améliorer la clarté visuelle et les détails.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contrast | float | Valeur de contraste (dans la plage [-100 ; 100]) |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Définissez la valeur de contraste. Les valeurs acceptées de contraste sont dans la plage [-100f, 100f].
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


La correction gamma d'une image applique un ajustement non linéaire des valeurs des pixels, augmentant ou réduisant la luminosité en fonction des coefficients spécifiés pour les canaux rouge, vert et bleu. Cette méthode aide à affiner la balance des couleurs et la luminance de l'image, améliorant son apparence globale et sa qualité visuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gammaRed | float | Coefficient gamma pour le canal rouge |
| gammaGreen | float | Coefficient gamma pour le canal vert |
| gammaBlue | float | Gamma pour le coefficient du canal bleu |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Définir les coefficients gamma individuels pour les canaux rouge, vert et bleu.
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


La transformation d'une image en sa représentation en niveaux de gris convertit l'image couleur en une version en niveaux de gris en supprimant les informations de couleur tout en préservant la luminance. Ce processus simplifie l'image en nuances de gris, la rendant adaptée à diverses applications telles que l'impression, le traitement de documents et l'analyse en niveaux de gris.


**Example: The following example transforms a colored GIF image to its grayscale representation.**
L'exemple suivant transforme une image GIF couleur en sa représentation en niveaux de gris. Les images en niveaux de gris sont composées exclusivement de nuances de gris et ne contiennent que des informations d'intensité.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


La binarisation d'une image avec un seuil prédéfini convertit une image en niveaux de gris ou couleur en une image binaire, où chaque pixel est classé comme noir ou blanc en fonction de si sa valeur d'intensité dépasse un seuil spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |


**Example: The following example binarizes a GIF image with the predefined threshold.**
L'exemple suivant binarise une image GIF avec le seuil prédéfini. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binarisez l'image avec une valeur de seuil de 127.
    // Si la valeur de gris correspondante d'un pixel est supérieure à 127, une valeur de 255 lui sera attribuée, sinon 0.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


La binarisation d'une image avec le seuillage d'Otsu est une méthode utilisée pour déterminer automatiquement la valeur de seuil optimale afin de convertir une image en niveaux de gris en une image binaire. L'algorithme de seuillage d'Otsu calcule le seuil qui minimise la variance intra-classe des intensités des pixels dans les deux classes résultantes (premier plan et arrière-plan). Cette technique est particulièrement utile lorsque la valeur de seuil optimale est inconnue et doit être déterminée de manière adaptative en fonction de l'histogramme de l'image.


**Example: The following example binarizes a GIF image with Otsu thresholding.**
L'exemple suivant binarise une image GIF avec le seuillage d'Otsu. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binarisez l'image avec le seuillage d'Otsu.
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


La binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale est une méthode pour convertir une image en niveaux de gris en une image binaire. Cet algorithme calcule un seuil local pour chaque pixel en fonction de l'intensité moyenne des pixels environnants dans une fenêtre spécifiée. En ajustant de manière adaptative le seuil en fonction des intensités locales des pixels, la méthode de Bradley est efficace pour gérer les variations d'éclairage et de contraste à travers l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


Ordonner les blocs GIF selon la spécification GIF garantit une disposition correcte du GIF et la conformité au standard. Ce processus consiste à organiser les blocs dans la séquence correcte telle que définie par la spécification. De plus, il peut impliquer la suppression de certaines instances [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) qui ne sont pas nécessaires pour la disposition finale. En respectant la spécification GIF, l'image résultante sera correctement structurée et compatible avec les applications de visualisation GIF.

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Effacer tous les blocs GIF supprime toutes les données existantes stockées dans l'image. Cette opération réinitialise efficacement l'image à un état vide, en supprimant tous les blocs précédemment ajoutés. Utilisez cette méthode lorsque vous devez repartir de zéro avec une toile vierge pour créer ou modifier une image GIF.


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Le résultat ressemble à ceci :
// Taille de la trame active : { Width = 100, Height = 100}
// Effacer tous les blocs
// La trame active n'est pas définie
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


Insérer un nouveau bloc GIF vous permet d'ajouter des données personnalisées à une position spécifique dans l'image. Cette méthode vous permet de placer des blocs personnalisés à l'emplacement souhaité dans l'image GIF, offrant une flexibilité dans l'organisation et la structuration des données de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'élément indexé à partir de zéro, à l'endroit où le bloc sera inséré. |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Le bloc GIF à ajouter. |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


Ajouter un nouveau bloc GIF vous permet d'inclure des données supplémentaires dans l'image. Cette méthode vous permet d'ajouter des blocs personnalisés à l'image GIF, qui peuvent contenir divers types d'informations.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Le bloc GIF à ajouter. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// Créez une image GIF de 100 x 100 px.
// Le premier bloc est entièrement noir par défaut.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // Le premier cercle est rouge
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Le deuxième cercle est noir
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Augmentez progressivement l'angle de la forme d'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // Augmentez progressivement l'angle de l'arc noir et effacez l'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


La suppression d'un bloc GIF supprime des données spécifiques de l'image, offrant la possibilité de nettoyer ou de modifier la structure de l'image. Cette méthode vous permet de retirer les blocs indésirables ou inutiles, optimisant l'image GIF pour un stockage efficace. Utilisez cette fonctionnalité pour éliminer les informations obsolètes de l'image tout en préservant son intégrité et sa qualité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Le bloc à supprimer. |

--------------------

Remarque : n'oubliez pas de disposer le bloc si vous ne l'ajoutez pas à un autre GifImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Le redimensionnement proportionnel maintient le rapport d'aspect de l'image tout en ajustant sa taille, garantissant que l'image n'apparaisse pas étirée ou déformée. Cette méthode redimensionne l'image proportionnellement, en mettant à l'échelle à la fois la largeur et la hauteur par le même facteur. Le redimensionnement proportionnel redimensionnera chaque image selon le rapport de `newWidth`/width et `newHeight`/height.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Cette méthode fait pivoter l'image autour de son point central. En spécifiant l'angle de rotation, vous pouvez faire pivoter l'image dans le sens des aiguilles d'une montre ou dans le sens inverse pour obtenir l'orientation souhaitée. Cette rotation aide à ajuster la présentation ou l'alignement de l'image sans déformer son contenu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resizeProportionally | boolean | si défini sur `true` vous verrez la taille de votre image modifiée selon les projections du rectangle tourné (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul `` le contenu de l'image est tourné. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

