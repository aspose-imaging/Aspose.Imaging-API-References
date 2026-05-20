---
title: "GifOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API pour la création de fichiers d'image raster au format Graphical Interchange Format GIF offre aux développeurs des options complètes pour générer des images GIF avec un contrôle précis."
type: docs
weight: 22
url: /fr/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

L'API pour la création de fichiers d'image raster au format Graphical Interchange Format (GIF) offre aux développeurs des options complètes pour générer des images GIF avec un contrôle précis. Avec des fonctionnalités permettant de définir la couleur d'arrière-plan, la palette de couleurs, la résolution, le type entrelacé, la couleur transparente, le conteneur de métadonnées XMP et la compression d'image, cette API garantit flexibilité et efficacité dans la création de GIF optimisés et visuellement attrayants, adaptés aux exigences spécifiques des applications.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initialise une nouvelle instance de la classe `GifOptions`. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | Initialise une nouvelle instance de la classe `GifOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| [getLoopsCount()](#getLoopsCount--) | Obtient le nombre de boucles (1 boucle par défaut) |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Définit le nombre de boucles (1 boucle par défaut) |
| [getColorResolution()](#getColorResolution--) | Obtient ou définit la résolution couleur du GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Obtient ou définit la résolution couleur du GIF. |
| [isPaletteSorted()](#isPaletteSorted--) | Obtient ou définit une valeur indiquant si les entrées de palette sont triées. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Obtient ou définit une valeur indiquant si les entrées de palette sont triées. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Obtient ou définit le rapport d'aspect des pixels du GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Obtient ou définit le rapport d'aspect des pixels du GIF. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Obtient ou définit l'index de la couleur d'arrière-plan du GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Obtient ou définit l'index de la couleur d'arrière-plan du GIF. |
| [hasTrailer()](#hasTrailer--) | Obtient ou définit une valeur indiquant si le GIF possède un trailer. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Obtient ou définit une valeur indiquant si le GIF possède un trailer. |
| [getInterlaced()](#getInterlaced--) | Vrai si l'image doit être entrelacée. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Vrai si l'image doit être entrelacée. |
| [getMaxDiff()](#getMaxDiff--) | Obtient ou définit la différence maximale de pixels autorisée. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Obtient ou définit la différence maximale de pixels autorisée. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Définit la couleur d'arrière-plan. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient une valeur indiquant si une image GIF possède une couleur transparente. |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | Définit une valeur indiquant si une image GIF possède une couleur transparente. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Cet exemple montre l'utilisation de différentes classes du namespace SaveOptions à des fins d'exportation. Une image de type Gif est chargée dans une instance de Image, puis exportée vers plusieurs formats.
``` java
String dir = "c:\\temp\\";

//Chargez une image existante (de type Gif) dans une instance de la classe Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportez au format de fichier BMP en utilisant les options par défaut.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportez au format de fichier JPEG en utilisant les options par défaut.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportez au format de fichier PNG en utilisant les options par défaut.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportez au format de fichier TIFF en utilisant les options par défaut.
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportez uniquement les deux premières pages. Ces pages seront présentées comme des images animées dans le GIF de sortie.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Initialise une nouvelle instance de la classe `GifOptions`.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Initialise une nouvelle instance de la classe `GifOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | Les options GIF. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Obtient ou définit une valeur indiquant si la correction de palette est appliquée.

**Returns:**
booléen - `true` si la correction de palette est appliquée ; sinon, `false`.

La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source sont analysées afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options). Le processus d'analyse prend du temps, cependant l'image résultante disposera de la palette de couleurs la mieux adaptée et le résultat sera visuellement meilleur.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Obtient ou définit une valeur indiquant si la correction de palette est appliquée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | `true` si la correction de palette est appliquée ; sinon, `false`. |

La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source sont analysées afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options). Le processus d'analyse prend du temps, cependant l'image résultante disposera de la palette de couleurs la mieux adaptée et le résultat sera visuellement meilleur. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Remplissez l'intégralité de l'image avec le dégradé bleu-jaune.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Le nombre de bits nécessaires pour stocker une couleur, moins 1.
    saveOptions.setColorResolution((byte) 7);

    // La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source sont analysées
    // afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options)
    saveOptions.setDoPaletteCorrection(true);

    // Chargez une image GIF de manière progressive.
    // Un GIF entrelacé n'affiche pas ses lignes de balayage de façon linéaire de haut en bas, mais les réordonne
    // de sorte que le contenu du GIF devient visible même avant la fin du chargement.
    saveOptions.setInterlaced(true);

    // Enregistrez en tant que GIF sans perte.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Définissez la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée.
    // La valeur recommandée pour une compression avec perte optimale est 80. 30 correspond à une compression très légère, 200 à une compression lourde.
    saveOptions.setMaxDiff(80);

    // Enregistrez en tant que GIF avec perte.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//La sortie peut ressembler à ceci :
//Taille du GIF sans perte : 212 816 octets.
//Taille du GIF avec perte : 89 726 octets.
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


Obtient le nombre de boucles (1 boucle par défaut)

Valeur : le nombre de boucles.

**Returns:**
int - le nombre de boucles (Par défaut 1 boucle)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


Définit le nombre de boucles (1 boucle par défaut)

Valeur : le nombre de boucles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le nombre de boucles (Par défaut 1 boucle) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Obtient ou définit la résolution couleur du GIF.

**Returns:**
byte - La résolution des couleurs.

Résolution des couleurs - Nombre de bits par couleur primaire disponibles dans l'image d'origine, moins 1. Cette valeur représente la taille de toute la palette à partir de laquelle les couleurs du graphique ont été sélectionnées, et non le nombre de couleurs réellement utilisées dans le graphique. Par exemple, si la valeur de ce champ est 3, alors la palette de l'image d'origine disposait de 4 bits par couleur primaire pour créer l'image. Cette valeur doit être définie pour indiquer la richesse de la palette d'origine, même si toutes les couleurs de la palette complète ne sont pas disponibles sur la machine source.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Obtient ou définit la résolution couleur du GIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | byte | La résolution des couleurs. |

Résolution des couleurs - Nombre de bits par couleur primaire disponibles dans l'image d'origine, moins 1. Cette valeur représente la taille de toute la palette à partir de laquelle les couleurs du graphique ont été sélectionnées, et non le nombre de couleurs réellement utilisées dans le graphique. Par exemple, si la valeur de ce champ est 3, alors la palette de l'image d'origine disposait de 4 bits par couleur primaire pour créer l'image. Cette valeur doit être définie pour indiquer la richesse de la palette d'origine, même si toutes les couleurs de la palette complète ne sont pas disponibles sur la machine source. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Remplissez l'intégralité de l'image avec le dégradé bleu-jaune.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Le nombre de bits nécessaires pour stocker une couleur, moins 1.
    saveOptions.setColorResolution((byte) 7);

    // La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source sont analysées
    // afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options)
    saveOptions.setDoPaletteCorrection(true);

    // Chargez une image GIF de manière progressive.
    // Un GIF entrelacé n'affiche pas ses lignes de balayage de façon linéaire de haut en bas, mais les réordonne
    // de sorte que le contenu du GIF devient visible même avant la fin du chargement.
    saveOptions.setInterlaced(true);

    // Enregistrez en tant que GIF sans perte.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Définissez la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée.
    // La valeur recommandée pour une compression avec perte optimale est 80. 30 correspond à une compression très légère, 200 à une compression lourde.
    saveOptions.setMaxDiff(80);

    // Enregistrez en tant que GIF avec perte.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//La sortie peut ressembler à ceci :
//Taille du GIF sans perte : 212 816 octets.
//Taille du GIF avec perte : 89 726 octets.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Obtient ou définit une valeur indiquant si les entrées de palette sont triées.

**Returns:**
booléen - `true` si les entrées de la palette sont triées ; sinon, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Obtient ou définit une valeur indiquant si les entrées de palette sont triées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si les entrées de la palette sont triées ; sinon, `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Obtient ou définit le rapport d'aspect des pixels du GIF.

Pixel Aspect Ratio - Facteur utilisé pour calculer une approximation du rapport d'aspect du pixel dans l'image d'origine. Si la valeur du champ n'est pas 0, cette approximation du rapport d'aspect est calculée selon la formule : Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Le Pixel Aspect Ratio est défini comme le quotient de la largeur du pixel sur sa hauteur. La plage de valeurs de ce champ permet de spécifier le pixel le plus large de 4 :1 au pixel le plus haut de 1 :4 par incréments de 1/64. Valeurs : 0 - Aucune information de rapport d'aspect fournie. 1..255 - Valeur utilisée dans le calcul.

**Returns:**
byte - Le rapport d'aspect du pixel GIF.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Obtient ou définit le rapport d'aspect des pixels du GIF.

Pixel Aspect Ratio - Facteur utilisé pour calculer une approximation du rapport d'aspect du pixel dans l'image d'origine. Si la valeur du champ n'est pas 0, cette approximation du rapport d'aspect est calculée selon la formule : Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Le Pixel Aspect Ratio est défini comme le quotient de la largeur du pixel sur sa hauteur. La plage de valeurs de ce champ permet de spécifier le pixel le plus large de 4 :1 au pixel le plus haut de 1 :4 par incréments de 1/64. Valeurs : 0 - Aucune information de rapport d'aspect fournie. 1..255 - Valeur utilisée dans le calcul.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | Le rapport d'aspect du pixel GIF. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Obtient ou définit l'index de la couleur d'arrière-plan du GIF.

**Returns:**
byte - L'index de couleur d'arrière-plan GIF.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Obtient ou définit l'index de la couleur d'arrière-plan du GIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | L'index de couleur d'arrière-plan GIF. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Obtient ou définit une valeur indiquant si le GIF possède un trailer.

**Returns:**
booléen - `true` si le GIF a un trailer ; sinon, `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Obtient ou définit une valeur indiquant si le GIF possède un trailer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si le GIF a un trailer ; sinon, `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Vrai si l'image doit être entrelacée.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Vrai si l'image doit être entrelacée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Remplissez l'intégralité de l'image avec le dégradé bleu-jaune.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Le nombre de bits nécessaires pour stocker une couleur, moins 1.
    saveOptions.setColorResolution((byte) 7);

    // La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source sont analysées
    // afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options)
    saveOptions.setDoPaletteCorrection(true);

    // Chargez une image GIF de manière progressive.
    // Un GIF entrelacé n'affiche pas ses lignes de balayage de façon linéaire de haut en bas, mais les réordonne
    // de sorte que le contenu du GIF devient visible même avant la fin du chargement.
    saveOptions.setInterlaced(true);

    // Enregistrez en tant que GIF sans perte.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Définissez la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée.
    // La valeur recommandée pour une compression avec perte optimale est 80. 30 correspond à une compression très légère, 200 à une compression lourde.
    saveOptions.setMaxDiff(80);

    // Enregistrez en tant que GIF avec perte.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//La sortie peut ressembler à ceci :
//Taille du GIF sans perte : 212 816 octets.
//Taille du GIF avec perte : 89 726 octets.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Obtient ou définit la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée. La valeur recommandée pour une compression avec perte optimale est 80. 30 correspond à une compression très légère, 200 à une compression lourde. Elle fonctionne mieux lorsqu'une perte minime est introduite, et en raison des limites de l'algorithme de compression, des niveaux de perte très élevés n'apporteront pas autant de gain. La plage de valeurs autorisées est [0, 1000].

**Returns:**
int - La plage de valeurs autorisées.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Obtient ou définit la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée. La valeur recommandée pour une compression avec perte optimale est 80. 30 correspond à une compression très légère, 200 à une compression lourde. Elle fonctionne mieux lorsqu'une perte minime est introduite, et en raison des limites de l'algorithme de compression, des niveaux de perte très élevés n'apporteront pas autant de gain. La plage de valeurs autorisées est [0, 1000].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La plage de valeurs autorisées. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Remplissez l'intégralité de l'image avec le dégradé bleu-jaune.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Le nombre de bits nécessaires pour stocker une couleur, moins 1.
    saveOptions.setColorResolution((byte) 7);

    // La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source sont analysées
    // afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options)
    saveOptions.setDoPaletteCorrection(true);

    // Chargez une image GIF de manière progressive.
    // Un GIF entrelacé n'affiche pas ses lignes de balayage de façon linéaire de haut en bas, mais les réordonne
    // de sorte que le contenu du GIF devient visible même avant la fin du chargement.
    saveOptions.setInterlaced(true);

    // Enregistrez en tant que GIF sans perte.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Définissez la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée.
    // La valeur recommandée pour une compression avec perte optimale est 80. 30 correspond à une compression très légère, 200 à une compression lourde.
    saveOptions.setMaxDiff(80);

    // Enregistrez en tant que GIF avec perte.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//La sortie peut ressembler à ceci :
//Taille du GIF sans perte : 212 816 octets.
//Taille du GIF avec perte : 89 726 octets.
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Obtient la couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


Définit la couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | la couleur d'arrière-plan. |

### hasTransparentColor() {#hasTransparentColor--}
```
public final Boolean hasTransparentColor()
```


Obtient une valeur indiquant si une image GIF possède une couleur transparente. Si la valeur de retour est `null`, cette propriété est remplacée par le contexte de l'image source.

**Returns:**
java.lang.Boolean - une valeur indiquant si une image GIF possède une couleur transparente.
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


Définit une valeur indiquant si une image GIF possède une couleur transparente. Si la valeur de retour est `null`, cette propriété est remplacée par le contexte de l'image source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Boolean | une valeur indiquant si une image GIF possède une couleur transparente. |

