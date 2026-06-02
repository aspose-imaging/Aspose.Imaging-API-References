---
title: "ImageOptionsBase"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options de base de l'image."
type: docs
weight: 62
url: /fr/java/com.aspose.imaging/imageoptionsbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class ImageOptionsBase extends DisposableObject implements IMetadataContainer
```

Les options de base de l'image.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isKeepMetadata()](#isKeepMetadata--) | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| [setKeepMetadata(boolean value)](#setKeepMetadata-boolean-) | Une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| [getXmpData()](#getXmpData--) | Obtient le conteneur de métadonnées XMP. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Définit le conteneur de métadonnées XMP. |
| [getExifData()](#getExifData--) | Obtient les données Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Définit les données Exif. |
| [getSource()](#getSource--) | Obtient la source dans laquelle créer l'image. |
| [setSource(Source value)](#setSource-com.aspose.imaging.Source-) | Obtient ou définit la source dans laquelle créer l'image. |
| [getPalette()](#getPalette--) | Obtient la palette de couleurs. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Définit la palette de couleurs. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtient les paramètres de résolution. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Définit les paramètres de résolution. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtient les options de rasterisation vectorielle. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Définit les options de rasterisation vectorielle. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Les options multipages |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-) | Les options multipages |
| [getFullFrame()](#getFullFrame--) | Obtient une valeur indiquant si [full frame]. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Définit une valeur indiquant si [full frame]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient le gestionnaire d'événement de progression. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Définit le gestionnaire d'événement de progression. |
| [deepClone()](#deepClone--) | Clone cette instance. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Essaie de définir une instance `metadata`, si cette instance [Image](../../com.aspose.imaging/image) prend en charge et implémente une instance [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### isKeepMetadata() {#isKeepMetadata--}
```
public final boolean isKeepMetadata()
```


Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation.

**Returns:**
booléen - une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation.
### setKeepMetadata(boolean value) {#setKeepMetadata-boolean-}
```
public final void setKeepMetadata(boolean value)
```


Une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtient le conteneur de métadonnées XMP.

Valeur : le conteneur de données XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Définit le conteneur de métadonnées XMP.

Valeur : le conteneur de données XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | le conteneur de métadonnées XMP. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Obtient les données Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Définit les données Exif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | les données Exif. |

### getSource() {#getSource--}
```
public Source getSource()
```


Obtient la source dans laquelle créer l'image.

**Returns:**
[Source](../../com.aspose.imaging/source) - The source to create image in.
### setSource(Source value) {#setSource-com.aspose.imaging.Source-}
```
public void setSource(Source value)
```


Obtient ou définit la source dans laquelle créer l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Source](../../com.aspose.imaging/source) | La source dans laquelle créer l'image. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtient la palette de couleurs.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Définit la palette de couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs. |


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

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtient les paramètres de résolution.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Définit les paramètres de résolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Chargez une image BMP à partir d'un fichier.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Effectuez un traitement d'image.

    // Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Le nombre de bits par canal est de 8.
    // Lorsqu'une palette est utilisée, l'index de couleur est stocké dans les données de l'image au lieu de la couleur elle-même.
    saveOptions.setBitsPerChannel((byte) 8);

    // Définissez le type de compression progressive.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Définissez la qualité de l'image. C'est une valeur comprise entre 1 et 100.
    saveOptions.setQuality(100);

    // Définissez la résolution horizontale/verticale à 96 points par pouce.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Si l'image source est en couleur, elle sera convertie en niveaux de gris.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Utilisez une palette pour réduire la taille de sortie.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public VectorRasterizationOptions getVectorRasterizationOptions()
```


Obtient les options de rasterisation vectorielle.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The vector rasterization options.
### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Définit les options de rasterisation vectorielle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Les options de rasterisation vectorielle. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.

Valeur : L’indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes

**Returns:**
int - l’indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.

Valeur : L’indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l’indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |

### getMultiPageOptions() {#getMultiPageOptions--}
```
public MultiPageOptions getMultiPageOptions()
```


Les options multipages

**Returns:**
[MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions)
### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-}
```
public void setMultiPageOptions(MultiPageOptions value)
```


Les options multipages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions) |  |

### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Obtient une valeur indiquant si [full frame].

Valeur : `true` si [full frame]; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si [full frame].
### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Définit une valeur indiquant si [full frame].

Valeur : `true` si [full frame]; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si [full frame]. |

### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Obtient le gestionnaire d'événement de progression.

Valeur : le gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Définit le gestionnaire d'événement de progression.

Valeur : le gestionnaire d'événement de progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | le gestionnaire d'événement de progression. |


**Example: The following example shows how to print information about progress events for load/export operations.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Exemple d'utilisation de gestionnaires d'événements de progression d'opération séparés pour les opérations de chargement/exportation
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// Le journal STDOUT peut ressembler à ceci :
//        Événement de chargement Initialisation : 1/4
//        Événement de chargement Prétraitement : 2/4
//        Événement de chargement Traitement : 3/4
//        Événement de chargement Finalisation : 4/4
//        Événement d'exportation Initialisation : 1/4
//        Événement d'exportation Prétraitement : 2/4
//        Événement d'exportation Traitement : 3/4
//        Événement d'exportation RelativeProgress : 1/1
//        Événement de chargement RelativeProgress : 1/1
//        Événement d'exportation Finalisation : 4/4
```

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clone cette instance.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns shallow copy of this instance
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public final boolean trySetMetadata(IImageMetadataFormat metadata)
```


Essaie de définir une instance `metadata`, si cette instance [Image](../../com.aspose.imaging/image) prend en charge et implémente une instance [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Les métadonnées. |

**Returns:**
booléen - Vrai, si l'instance [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) prend en charge et/ou implémente l'instance [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) ; sinon, false.
