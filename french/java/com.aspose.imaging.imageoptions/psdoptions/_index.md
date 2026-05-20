---
title: "PsdOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Créez des images Photoshop Document PSD avec notre API offrant des options polyvalentes avec différentes versions de format, méthodes de compression, modes couleur et nombre de bits par canal de couleur."
type: docs
weight: 40
url: /fr/java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Créez des images Photoshop Document (PSD) avec notre API, offrant des options polyvalentes avec différentes versions de format, méthodes de compression, modes couleur et nombre de bits par canal de couleur. Gérez sans effort les conteneurs de métadonnées XMP, garantissant un traitement d'image complet grâce aux fonctionnalités du format PSD telles que les calques d'image, les masques de calque et les informations de fichier pour la personnalisation et la créativité dans vos conceptions.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Initialise une nouvelle instance de la classe `PsdOptions`. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | Initialise une nouvelle instance de la classe `PsdOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Obtenir ou définir le conteneur de données XMP |
| [getVersion()](#getVersion--) | Obtient ou définit la version du fichier PSD. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit la version du fichier PSD. |
| [getCompressionMethod()](#getCompressionMethod--) | Obtient ou définit la méthode de compression du PSD. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Obtient ou définit la méthode de compression du PSD. |
| [getPsdVersion()](#getPsdVersion--) | Obtient la version du format de fichier. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Définit la version du format de fichier. |
| [getColorMode()](#getColorMode--) | Obtient ou définit le mode couleur du PSD. |
| [setColorMode(short value)](#setColorMode-short-) | Obtient ou définit le mode couleur du PSD. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Obtient ou définit le nombre de bits par canal de couleur. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Obtient ou définit le nombre de bits par canal de couleur. |
| [getChannelsCount()](#getChannelsCount--) | Obtient le nombre de canaux couleur. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Définit le nombre de canaux couleur. |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | Obtient une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après traitement (principalement lié aux calques de texte avec polices manquantes). |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après traitement (principalement lié aux calques de texte avec polices manquantes). |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | Obtient une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Définit une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD. |
| [getVectorizationOptions()](#getVectorizationOptions--) | Obtient les options de vectorisation du PSD. |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | Définit les options de vectorisation PSD. |

## Example: This example demonstrates the use of Aspose.
Cet exemple montre l'utilisation de l'API Aspose.Imaging for Java pour convertir des images au format PSD. Pour atteindre cet objectif, cet exemple charge une image existante puis la enregistre à nouveau au format PSD.
``` java

// Créez une instance de la classe image et initialisez‑la avec un fichier existant via le chemin du fichier.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Créez une instance de la classe PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Définissez la CompressionMethod sur RLE.
    // Remarque : une autre CompressionMethod prise en charge est CompressionMethod.RAW [Pas de compression].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Définissez le ColorMode sur GrayScale.
    // Remarque : d'autres ColorModes pris en charge sont ColorModes.Bitmap et ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Enregistrez l'image sur le disque avec les paramètres PsdOptions fournis.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportez uniquement les deux premières pages. Ces pages seront présentées comme des calques dans le PSD de sortie.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
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

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Initialise une nouvelle instance de la classe `PsdOptions`.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Initialise une nouvelle instance de la classe `PsdOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | Les options. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtenir ou définir le conteneur de données XMP

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient ou définit la version du fichier PSD.

Valeur : la version du fichier PSD.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtient ou définit la version du fichier PSD.

Valeur : la version du fichier PSD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Créez une image PNG de 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Définissez un dégradé linéaire bleu‑transparent.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Remplissez l'image PNG avec le dégradé linéaire bleu‑transparent.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Les options suivantes seront utilisées pour enregistrer l'image PNG au format PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Le nombre de bits par canal.
    saveOptions.setChannelBitsCount((byte) 8);

    // Le nombre de canaux. Un canal pour chaque composant couleur R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Le mode couleur
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Pas de compression.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // La version par défaut est 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // La compression RLE permet de réduire la taille de l'image de sortie.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // La sortie peut ressembler à ceci :
    // La taille de l'image PSD avec compression RAW : 40090.
    // La taille de l'image PSD avec compression RLE : 16185.
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


Obtient ou définit la méthode de compression du PSD.

Valeur : la méthode de compression.

**Returns:**
short
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


Obtient ou définit la méthode de compression du PSD.

Valeur : la méthode de compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |


**Example: This example demonstrates the use of Aspose.**
Cet exemple montre l'utilisation de l'API Aspose.Imaging for Java pour convertir des images au format PSD. Pour atteindre cet objectif, cet exemple charge une image existante puis la enregistre à nouveau au format PSD.
``` java

// Créez une instance de la classe image et initialisez‑la avec un fichier existant via le chemin du fichier.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Créez une instance de la classe PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Définissez la CompressionMethod sur RLE.
    // Remarque : une autre CompressionMethod prise en charge est CompressionMethod.RAW [Pas de compression].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Définissez le ColorMode sur GrayScale.
    // Remarque : d'autres ColorModes pris en charge sont ColorModes.Bitmap et ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Enregistrez l'image sur le disque avec les paramètres PsdOptions fournis.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Obtient la version du format de fichier. Elle peut être PSD ou PSB.

Valeur : la version du format de fichier.

**Returns:**
byte - la version du format de fichier.
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Définit la version du format de fichier. Elle peut être PSD ou PSB.

Valeur : la version du format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | la version du format de fichier. |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


Obtient ou définit le mode couleur du PSD.

Valeur : le mode couleur.

**Returns:**
short
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


Obtient ou définit le mode couleur du PSD.

Valeur : le mode couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |


**Example: This example demonstrates the use of Aspose.**
Cet exemple montre l'utilisation de l'API Aspose.Imaging for Java pour convertir des images au format PSD. Pour atteindre cet objectif, cet exemple charge une image existante puis la enregistre à nouveau au format PSD.
``` java

// Créez une instance de la classe image et initialisez‑la avec un fichier existant via le chemin du fichier.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Créez une instance de la classe PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Définissez la CompressionMethod sur RLE.
    // Remarque : une autre CompressionMethod prise en charge est CompressionMethod.RAW [Pas de compression].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Définissez le ColorMode sur GrayScale.
    // Remarque : d'autres ColorModes pris en charge sont ColorModes.Bitmap et ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Enregistrez l'image sur le disque avec les paramètres PsdOptions fournis.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


Obtient ou définit le nombre de bits par canal de couleur.

Valeur : Le nombre de bits par canal de couleur.

**Returns:**
short
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


Obtient ou définit le nombre de bits par canal de couleur.

Valeur : Le nombre de bits par canal de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Créez une image PNG de 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Définissez un dégradé linéaire bleu‑transparent.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Remplissez l'image PNG avec le dégradé linéaire bleu‑transparent.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Les options suivantes seront utilisées pour enregistrer l'image PNG au format PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Le nombre de bits par canal.
    saveOptions.setChannelBitsCount((byte) 8);

    // Le nombre de canaux. Un canal pour chaque composant couleur R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Le mode couleur
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Pas de compression.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // La version par défaut est 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // La compression RLE permet de réduire la taille de l'image de sortie.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // La sortie peut ressembler à ceci :
    // La taille de l'image PSD avec compression RAW : 40090.
    // La taille de l'image PSD avec compression RLE : 16185.
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


Obtient le nombre de canaux couleur.

**Returns:**
short - Le nombre de canaux de couleur.
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


Définit le nombre de canaux couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short | Le nombre de canaux de couleur. |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Créez une image PNG de 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Définissez un dégradé linéaire bleu‑transparent.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Remplissez l'image PNG avec le dégradé linéaire bleu‑transparent.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Les options suivantes seront utilisées pour enregistrer l'image PNG au format PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Le nombre de bits par canal.
    saveOptions.setChannelBitsCount((byte) 8);

    // Le nombre de canaux. Un canal pour chaque composant couleur R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Le mode couleur
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Pas de compression.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // La version par défaut est 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // La compression RLE permet de réduire la taille de l'image de sortie.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // La sortie peut ressembler à ceci :
    // La taille de l'image PSD avec compression RAW : 40090.
    // La taille de l'image PSD avec compression RLE : 16185.
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


Obtient une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après le traitement (principalement lié aux calques de texte avec polices manquantes). Après avoir utilisé cette option, l'utilisateur doit effectuer ce qui suit dans le fichier ouvert dans Photoshop : Menu "Text" -> "Process absent fonts". Après cette opération, tout le texte réapparaîtra. Veuillez noter que cette opération peut entraîner des modifications finales de la mise en page.

**Returns:**
boolean - `true` si [remove global text engine resource] ; sinon, `false`.
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


Définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après le traitement (principalement lié aux calques de texte avec polices manquantes). Après avoir utilisé cette option, l'utilisateur doit effectuer ce qui suit dans le fichier ouvert dans Photoshop : Menu "Text" -> "Process absent fonts". Après cette opération, tout le texte réapparaîtra. Veuillez noter que cette opération peut entraîner des modifications finales de la mise en page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si [remove global text engine resource] ; sinon, `false`. |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


Obtient une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD.

**Returns:**
boolean - `true` si [refresh image preview data] ; sinon, `false`.
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


Définit une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si [refresh image preview data] ; sinon, `false`. |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


Obtient les options de vectorisation du PSD.

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


Définit les options de vectorisation PSD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | les options de vectorisation PSD. |

