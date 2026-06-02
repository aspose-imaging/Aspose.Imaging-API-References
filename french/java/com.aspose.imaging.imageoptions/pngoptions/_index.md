---
title: "PngOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Créez facilement des images raster PNG (Portable Network Graphics) de haute qualité avec notre API offrant des options personnalisables pour les niveaux de compression, les profondeurs de bits par pixel et les bits alpha."
type: docs
weight: 38
url: /fr/java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

Créez facilement des images raster Portable Network Graphics (PNG) de haute qualité avec notre API, offrant des options personnalisables pour les niveaux de compression, les profondeurs de bits par pixel et les bits alpha. Traitez sans effort les conteneurs de métadonnées XMP, garantissant une gestion complète des métadonnées d'image, et vous permettant d'adapter les images PNG à vos spécifications exactes avec aisance.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PngOptions()](#PngOptions--) | Initialise une nouvelle instance de la classe `PngOptions`. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | Initialise une nouvelle instance de la classe `PngOptions`. |
## Champs

| Champ | Description |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Le niveau de compression par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorType()](#getColorType--) | Obtient le type de la couleur. |
| [setColorType(int value)](#setColorType-int-) | Définit le type de la couleur. |
| [getProgressive()](#getProgressive--) | Obtient une valeur indiquant si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est progressif. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Définit une valeur indiquant si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est progressif. |
| [getFilterType()](#getFilterType--) | Obtient le type de filtre utilisé lors du processus d'enregistrement du fichier png. |
| [setFilterType(int value)](#setFilterType-int-) | Définit le type de filtre utilisé lors du processus d'enregistrement du fichier png. |
| [getCompressionLevel()](#getCompressionLevel--) | Obtient le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Définit le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getPngCompressionLevel()](#getPngCompressionLevel--) | Obtient le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setPngCompressionLevel(int value)](#setPngCompressionLevel-int-) | Définit le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getBitDepth()](#getBitDepth--) | Obtient les valeurs de profondeur de bits dans la plage de 1, 2, 4, 8, 16. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Définit les valeurs de profondeur de bits dans la plage de 1, 2, 4, 8, 16. |

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


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportez uniquement les deux premières pages. En fait, une seule page sera rasterisée car le PNG n'est pas un format multi-pages.
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

### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Initialise une nouvelle instance de la classe `PngOptions`.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Initialise une nouvelle instance de la classe `PngOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Les options PNG. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Le niveau de compression par défaut.

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Obtient le type de la couleur.

Valeur : le type de la couleur.

**Returns:**
int - le type de la couleur.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Définit le type de la couleur.

Valeur : le type de la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le type de la couleur. |


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


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Créez une image PNG de 100 × 100 px.
// Vous pouvez également charger une image de n'importe quel format pris en charge depuis un fichier ou un flux.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Remplissez l'image avec le dégradé bleu-transparent.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Utilisez le chargement progressif.
    saveOptions.setProgressive(true);

    // Définissez la résolution horizontale et verticale à 96 pixels par pouce.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Chaque pixel est un triplet (rouge, vert, bleu) suivi de l'alpha.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Définissez le niveau maximal de compression.
    saveOptions.setCompressionLevel(9);

    // C'est la meilleure compression, mais le temps d'exécution le plus lent.
    // Le filtrage adaptatif signifie que le processus d'enregistrement choisira le filtre le plus adapté pour chaque ligne de données.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Le nombre de bits par canal.
    saveOptions.setBitDepth((byte) 8);

    // Enregistrer dans un fichier.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


Obtient une valeur indiquant si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est progressif.

Valeur : `` si progressif; sinon, ``.

**Returns:**
booléen - une valeur indiquant si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est progressif.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


Définit une valeur indiquant si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est progressif.

Valeur : `` si progressif; sinon, ``.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | une valeur indiquant si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est progressif. |


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


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// Le nombre de bits par canal de couleur
createOptions.setBitDepth((byte) 8);

// Chaque pixel est un triplet (rouge, vert, bleu) suivi du composant alpha.
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// Le niveau maximal de compression.
createOptions.setCompressionLevel(9);

// L'utilisation des filtres permet de compresser les images tonales continues plus efficacement.
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// Utilisez le chargement progressif
createOptions.setProgressive(true);

// Créez une image PNG avec des paramètres personnalisés.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Remplissez l'image avec un dégradé semi-transparent.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Enregistrer dans un fichier.
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


Obtient le type de filtre utilisé lors du processus d'enregistrement du fichier png.

**Returns:**
int - le type de filtre utilisé lors du processus d'enregistrement du fichier png.
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


Définit le type de filtre utilisé lors du processus d'enregistrement du fichier png.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le type de filtre utilisé lors du processus d'enregistrement du fichier png. |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// Classe d'assistance
class Utils {
    public String getPngFilterTypeString(int filterType) {
        switch (filterType) {
            case com.aspose.imaging.fileformats.png.PngFilterType.None:
                return "None";

            case com.aspose.imaging.fileformats.png.PngFilterType.Up:
                return "Up";

            case com.aspose.imaging.fileformats.png.PngFilterType.Sub:
                return "Sub";

            case com.aspose.imaging.fileformats.png.PngFilterType.Paeth:
                return "Paeth";

            case com.aspose.imaging.fileformats.png.PngFilterType.Avg:
                return "Avg";

            case com.aspose.imaging.fileformats.png.PngFilterType.Adaptive:
                return "Adaptive";

            default:
                throw new IllegalArgumentException("filterType");
        }
    }
}

// Voici l'exemple principal
Utils utils = new Utils();

int[] filterTypes = new int[]
        {
                com.aspose.imaging.fileformats.png.PngFilterType.None,
                com.aspose.imaging.fileformats.png.PngFilterType.Up,
                com.aspose.imaging.fileformats.png.PngFilterType.Sub,
                com.aspose.imaging.fileformats.png.PngFilterType.Paeth,
                com.aspose.imaging.fileformats.png.PngFilterType.Avg,
                com.aspose.imaging.fileformats.png.PngFilterType.Adaptive,
        };

for (int filterType : filterTypes) {
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
    try {
        // Définissez un type de filtre
        options.setFilterType(filterType);

        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            image.save(stream, options);
            System.out.printf("The filter type is %s, the output image size is %s bytes.", utils.getPngFilterTypeString(filterType), stream.size());
        } finally {
            stream.close();
        }
    } finally {
        image.dispose();
    }
}

//La sortie peut ressembler à ceci :
//Le type de filtre est None, la taille de l'image résultante est de 116845 octets.
//Le type de filtre est Up, la taille de l'image résultante est de 86360 octets.
//Le type de filtre est Sub, la taille de l'image résultante est de 94907 octets.
//Le type de filtre est Paeth, la taille de l'image résultante est de 86403 octets.
//Le type de filtre est Avg, la taille de l'image résultante est de 89956 octets.
//Le type de filtre est Adaptive, la taille de l'image résultante est de 97248 octets.
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Obtient le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int - le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Définit le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |


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


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Créez une image PNG de 100 × 100 px.
// Vous pouvez également charger une image de n'importe quel format pris en charge depuis un fichier ou un flux.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Remplissez l'image avec le dégradé bleu-transparent.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Utilisez le chargement progressif.
    saveOptions.setProgressive(true);

    // Définissez la résolution horizontale et verticale à 96 pixels par pouce.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Chaque pixel est un triplet (rouge, vert, bleu) suivi de l'alpha.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Définissez le niveau maximal de compression.
    saveOptions.setCompressionLevel(9);

    // C'est la meilleure compression, mais le temps d'exécution le plus lent.
    // Le filtrage adaptatif signifie que le processus d'enregistrement choisira le filtre le plus adapté pour chaque ligne de données.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Le nombre de bits par canal.
    saveOptions.setBitDepth((byte) 8);

    // Enregistrer dans un fichier.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getPngCompressionLevel() {#getPngCompressionLevel--}
```
public final int getPngCompressionLevel()
```


Obtient le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int - le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setPngCompressionLevel(int value) {#setPngCompressionLevel-int-}
```
public final void setPngCompressionLevel(int value)
```


Définit le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | le niveau de compression du [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Obtient les valeurs de profondeur de bits dans la plage de 1, 2, 4, 8, 16.

Respectez les limites suivantes:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte - les valeurs de profondeur de bits dans la plage de 1, 2, 4, 8, 16.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


Définit les valeurs de profondeur de bits dans la plage de 1, 2, 4, 8, 16.

Respectez les limites suivantes:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | les valeurs de profondeur de bits dans la plage de 1, 2, 4, 8, 16. |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Créez une image PNG de 100 × 100 px.
// Vous pouvez également charger une image de n'importe quel format pris en charge depuis un fichier ou un flux.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Remplissez l'image avec le dégradé bleu-transparent.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Utilisez le chargement progressif.
    saveOptions.setProgressive(true);

    // Définissez la résolution horizontale et verticale à 96 pixels par pouce.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Chaque pixel est un triplet (rouge, vert, bleu) suivi de l'alpha.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Définissez le niveau maximal de compression.
    saveOptions.setCompressionLevel(9);

    // C'est la meilleure compression, mais le temps d'exécution le plus lent.
    // Le filtrage adaptatif signifie que le processus d'enregistrement choisira le filtre le plus adapté pour chaque ligne de données.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Le nombre de bits par canal.
    saveOptions.setBitDepth((byte) 8);

    // Enregistrer dans un fichier.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

