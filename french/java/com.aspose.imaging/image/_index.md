---
title: "Image"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'image est la classe de base pour tous les types d'images."
type: docs
weight: 56
url: /fr/java/com.aspose.imaging/image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.imaging.IObjectWithBounds](../../com.aspose.imaging/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler, [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler, IMetadataContainer
```

L'image est la classe de base pour tous les types d'images.
## Méthodes

| Méthode | Description |
| --- | --- |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les `loadOptions` spécifiés. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.imaging.ImageOptionsBase-int-int-) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| [create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)](#create-com.aspose.imaging.ImageOptionsBase-int-int-int---) | Crée une instance de [RasterImage](../../com.aspose.imaging/rasterimage) à partir du tableau de pixels fourni. |
| [create(Image[] images)](#create-com.aspose.imaging.Image---) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create(MultipageCreateOptions multipageCreateOptions)](#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-) | Crée les options de création multipage spécifiées. |
| [create(String[] files, boolean throwExceptionOnLoadError)](#create-java.lang.String---boolean-) | Crée l'image multipage contenant les fichiers spécifiés. |
| [create(String[] files)](#create-java.lang.String---) | Crée l'image multipage contenant les fichiers spécifiés. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.imaging.Image---boolean-) | Crée une nouvelle image les images spécifiées comme pages. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Obtient le format de fichier. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.imaging.LoadOptions-) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié. |
| [load(String filePath)](#load-java.lang.String-) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Charge une nouvelle image depuis le flux spécifié. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Obtient le format de fichier. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Obtient une largeur proportionnelle. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Obtient une hauteur proportionnelle. |
| [removeMetadata()](#removeMetadata--) | Supprime les métadonnées. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Essaie de définir une instance `metadata`, si cette instance [Image](../../com.aspose.imaging/image) prend en charge et implémente le type [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getBounds()](#getBounds--) | Obtient les limites de l'image. |
| [getContainer()](#getContainer--) | Obtient le conteneur `Image`. |
| [getPalette()](#getPalette--) | Obtient la palette de couleurs. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Définit la palette de couleurs. |
| [isUsePalette()](#isUsePalette--) | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| [getSize()](#getSize--) | Obtient la taille de l'image. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Obtient le moniteur d'interruption. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-) | Définit le moniteur d'interruption. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [isAutoAdjustPalette()](#isAutoAdjustPalette--) | Obtient une valeur indiquant si la palette d'ajustement automatique est activée. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Définit une valeur indiquant si la palette d'ajustement automatique est activée. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Obtient une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| [getFileFormat()](#getFileFormat--) | Récupérez facilement la valeur du format de fichier avec cette propriété conviviale. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [getMetadata()](#getMetadata--) | Obtient les métadonnées de l'image. |
| [getExifData()](#getExifData--) | Obtient les données Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Définit les données Exif. |
| [getXmpData()](#getXmpData--) | Obtient les données Xmp. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Définit les données Xmp. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Obtient les informations du gestionnaire d'événement de progression. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Obtient les informations du gestionnaire d'événement de progression. |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.imaging.ImageOptionsBase-) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne l'image. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtient les options par défaut. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options basées sur les paramètres du fichier original. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Redimensionne la largeur proportionnellement. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Redimensionne la hauteur proportionnellement. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Redimensionne la largeur proportionnellement. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Redimensionne la hauteur proportionnellement. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne la largeur proportionnellement. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne la hauteur proportionnellement. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Fait pivoter, retourner, ou pivoter et retourner l'image. |
| [rotate(float angle)](#rotate-float-) | Faire pivoter l'image autour du centre. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadre le rectangle spécifié. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Recadre l'image avec des décalages. |
| [save()](#save--) | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(String filePath)](#save-java.lang.String-) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Définit la palette de l'image. |
| [getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)](#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---) | Convertit en aps. |

## Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.
Cet exemple crée un nouveau fichier Image à un emplacement disque spécifié par la propriété Source de l'instance BmpOptions. Plusieurs propriétés de l'instance BmpOptions sont définies avant la création de l'image réelle. En particulier la propriété Source, qui fait référence à l'emplacement disque réel dans ce cas.
``` java
// Créez une instance de BmpOptions et définissez ses différentes propriétés
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Créez une instance de FileCreateSource et affectez‑la comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est IsTemporal ou non
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Créez une instance de Image et initialisez‑la avec une instance de BmpOptions en appelant la méthode Create
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Effectuez un traitement d'image

    // Enregistrez toutes les modifications
    image.save();
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


## Example: Determine if the palette is used by the image.

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Détermine si l'image peut être chargée depuis le chemin de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |

**Returns:**
booléen - `true` si l'image peut être chargée depuis le fichier spécifié ; sinon, `false`.

**Example: This example determines whether image can be loaded from a file.**

``` java

// Utilisez un chemin absolu vers le fichier
boolean canLoad = com.aspose.imaging.Image.canLoad("c:\\temp\\sample.gif");
```

### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

**Returns:**
booléen - `true` si l'image peut être chargée depuis le fichier spécifié ; sinon, `false`.
### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Détermine si l'image peut être chargée depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux depuis lequel charger. |

**Returns:**
booléen - `true` si l'image peut être chargée depuis le flux spécifié ; sinon, `false`.

**Example: This example determines whether image can be loaded from a file stream.**

``` java
String dir = "c:\\temp\\";

boolean canLoad;

// Utilisez un flux de fichier
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
try {
    canLoad = com.aspose.imaging.Image.canLoad(stream);
} finally {
    stream.close();
}

// Les données suivantes ne constituent pas un flux d'image valide, donc CanLoad renvoie false.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    canLoad = com.aspose.imaging.Image.canLoad(stream);
}
```

### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les `loadOptions` spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux depuis lequel charger. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

**Returns:**
booléen - `true` si l'image peut être chargée depuis le flux spécifié ; sinon, `false`.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.imaging.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Crée une nouvelle image en utilisant les options de création spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'image. |
| width | int | La largeur. |
| height | int | La hauteur. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The newly created image.

**Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.**
Cet exemple crée un nouveau fichier Image à un emplacement disque spécifié par la propriété Source de l'instance BmpOptions. Plusieurs propriétés de l'instance BmpOptions sont définies avant la création de l'image réelle. En particulier la propriété Source, qui fait référence à l'emplacement disque réel dans ce cas.
``` java
// Créez une instance de BmpOptions et définissez ses différentes propriétés
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Créez une instance de FileCreateSource et affectez‑la comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est IsTemporal ou non
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Créez une instance de Image et initialisez‑la avec une instance de BmpOptions en appelant la méthode Create
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Effectuez un traitement d'image

    // Enregistrez toutes les modifications
    image.save();
} finally {
    image.dispose();
}
```

### create(ImageOptionsBase imageOptions, int width, int height, int[] pixels) {#create-com.aspose.imaging.ImageOptionsBase-int-int-int---}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)
```


Crée une instance de [RasterImage](../../com.aspose.imaging/rasterimage) à partir du tableau de pixels fourni. Vérifie que la largeur et la hauteur spécifiées correspondent aux dimensions des données de pixels. Cette méthode ne peut être utilisée que lorsque la bibliothèque est en mode Licensed.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options utilisées pour créer le [RasterImage](../../com.aspose.imaging/rasterimage). |
| width | int | La largeur du [RasterImage](../../com.aspose.imaging/rasterimage). |
| height | int | La hauteur du [RasterImage](../../com.aspose.imaging/rasterimage). |
| pixels | int[] | Le tableau de valeurs de pixels utilisé pour remplir l'image. |

**Returns:**
[Image](../../com.aspose.imaging/image) - A [RasterImage](../../com.aspose.imaging/rasterimage) populated with the provided pixel data.
### create(Image[] images) {#create-com.aspose.imaging.Image---}
```
public static Image create(Image[] images)
```


Crée une nouvelle image en utilisant les images spécifiées comme pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Les images. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### create(MultipageCreateOptions multipageCreateOptions) {#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-}
```
public static Image create(MultipageCreateOptions multipageCreateOptions)
```


Crée les options de création multipage spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| multipageCreateOptions | [MultipageCreateOptions](../../com.aspose.imaging.imageoptions/multipagecreateoptions) | Les options de création multipage. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files, boolean throwExceptionOnLoadError) {#create-java.lang.String---boolean-}
```
public static Image create(String[] files, boolean throwExceptionOnLoadError)
```


Crée l'image multipage contenant les fichiers spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichiers | java.lang.String[] | Les fichiers. |
| throwExceptionOnLoadError | boolean | si défini sur `true` [throw exception on load error]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files) {#create-java.lang.String---}
```
public static Image create(String[] files)
```


Crée l'image multipage contenant les fichiers spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichiers | java.lang.String[] | Les fichiers. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(Image[] images, boolean disposeImages) {#create-com.aspose.imaging.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Crée une nouvelle image les images spécifiées comme pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Les images. |
| disposeImages | boolean | si défini sur `true` [dispose images]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Obtient le format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier. |

Le format de fichier déterminé ne signifie pas que l'image spécifiée puisse être chargée. Utilisez l'une des surcharges de la méthode CanLoad pour déterminer si le fichier peut être chargé. |

**Returns:**
long - Le format de fichier déterminé.

**Example: This example shows how to determine the image format without loading the entire image from a file.**

``` java
String dir = "c:\\temp\\";

// Utilisez un chemin absolu vers le fichier
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Une représentation sous forme de chaîne du format de fichier.
String strFormat;
if (format == com.aspose.imaging.FileFormat.Bmp) {
    strFormat = "BMP";
} else if (format == com.aspose.imaging.FileFormat.Gif) {
    strFormat = "GIF";
} else if (format == com.aspose.imaging.FileFormat.Dicom) {
    strFormat = "DICOM";
} else if (format == com.aspose.imaging.FileFormat.Djvu) {
    strFormat = "DJVU";
} else if (format == com.aspose.imaging.FileFormat.Dng) {
    strFormat = "DNG";
} else if (format == com.aspose.imaging.FileFormat.Png) {
    strFormat = "PNG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg) {
    strFormat = "JPEG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg2000) {
    strFormat = "JPEG2000";
} else if (format == com.aspose.imaging.FileFormat.Psd) {
    strFormat = "PSD";
} else if (format == com.aspose.imaging.FileFormat.Tiff) {
    strFormat = "Tiff";
} else if (format == com.aspose.imaging.FileFormat.Webp) {
    strFormat = "WEBP";
} else if (format == com.aspose.imaging.FileFormat.Cdr) {
    strFormat = "CDR";
} else if (format == com.aspose.imaging.FileFormat.Cmx) {
    strFormat = "CMX";
} else if (format == com.aspose.imaging.FileFormat.Emf) {
    strFormat = "EMF";
} else if (format == com.aspose.imaging.FileFormat.Wmf) {
    strFormat = "WMF";
} else if (format == com.aspose.imaging.FileFormat.Svg) {
    strFormat = "SVG";
} else if (format == com.aspose.imaging.FileFormat.Odg) {
    strFormat = "ODG";
} else if (format == com.aspose.imaging.FileFormat.Eps) {
    strFormat = "EPS";
} else {
    strFormat = "UNDEFINED";
}

System.out.println("The file format is " + strFormat);
```

### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié. Si `filePath` est un chemin de fichier, la méthode ouvre simplement le fichier. Si `filePath` est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin de fichier ou l'URL depuis lequel charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié. Si `filePath` est un chemin de fichier, la méthode ouvre simplement le fichier. Si `filePath` est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin de fichier ou l'URL depuis lequel charger l'image. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the loading of an existing Image file into an instance of com.**
Cet exemple montre le chargement d'un fichier Image existant dans une instance de com.aspose.imaging.Image en utilisant le chemin de fichier spécifié
``` java
// Créez une instance Image et initialisez‑la avec un fichier image existant depuis l'emplacement du disque
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Effectuez un traitement d'image.
} finally {
    image.dispose();
}
```

### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier depuis lequel charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier depuis lequel charger l'image. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger l'image. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the use of InputStream object to load an existing Image file**

``` java
// Créer une instance de FileInputStream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.bmp");
try {
    // Créer une instance de la classe Image et charger un fichier existant via l'objet FileStream en appelant la méthode Load
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(stream);
    try {
        // Effectuez un traitement d'image.
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Obtient le format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.InputStream | Le flux. |

Le format de fichier déterminé ne signifie pas que l'image spécifiée puisse être chargée. Utilisez l'une des surcharges de la méthode CanLoad pour déterminer si le flux peut être chargé. |

**Returns:**
long - Le format de fichier déterminé.

**Example: This example shows how to determine the image format without loading the entire image from a file stream.**

``` java

// La classe d'assistance utilisée dans l'exemple principal ci-dessous.
class Utils {
    // La méthode d'assistance pour obtenir une représentation sous forme de chaîne du format de fichier.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Voici l'exemple principal
Utils utils = new Utils();

String dir = "c:\\temp\\";

// Utilisez un flux de fichier
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// Les données suivantes ne constituent pas un flux d'image valide, donc GetFileFormat renvoie FileFormat.Undefined.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// La sortie peut ressembler à ceci :
// Le format de fichier est BMP
// Le format de fichier est UNDEFINED
```

### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Obtient le rectangle qui s'adapte à l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle pour obtenir le rectangle d'ajustement. |
| width | int | La largeur de l'objet. |
| height | int | La hauteur de l'objet. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Obtient le rectangle qui s'adapte à l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle pour obtenir le rectangle d'ajustement. |
| pixels | int[] | Les pixels ARGB 32 bits. |
| width | int | La largeur de l'objet. |
| height | int | La hauteur de l'objet. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Obtient une largeur proportionnelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur. |
| height | int | La hauteur. |
| newHeight | int | La nouvelle hauteur. |

**Returns:**
int - La largeur proportionnelle.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Obtient une hauteur proportionnelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur. |
| height | int | La hauteur. |
| newWidth | int | La nouvelle largeur. |

**Returns:**
int - La hauteur proportionnelle.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Supprime les métadonnées.

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Essaie de définir une instance `metadata`, si cette instance [Image](../../com.aspose.imaging/image) prend en charge et implémente le type [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Les métadonnées. |

**Returns:**
boolean - Vrai, si l'instance [Image](../../com.aspose.imaging/image) prend en charge et implémente le type [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) ; sinon, faux.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient les limites de l'image.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The image bounds.
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Obtient le conteneur `Image`.

Valeur : Le conteneur `Image`.

Si cette propriété n'est pas nulle, cela indique que l'image est contenue dans une autre image.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtient la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs. |

### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Obtient une valeur indiquant si la palette de l'image est utilisée.

Valeur : `true` si la palette est utilisée dans l'image ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si la palette d'image est utilisée.

**Example: Determine if the palette is used by the image.**

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### getSize() {#getSize--}
```
public Size getSize()
```


Obtient la taille de l'image.

**Returns:**
[Size](../../com.aspose.imaging/size) - The image size.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Charger une image DJVU à partir d'un flux de fichier.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//La sortie peut ressembler à ceci :
//Le nombre total de pages : 2
//Le numéro de page actif :    1
//Le numéro de la première page :     1
//Le numéro de la dernière page :      2
//--------------------------------------------------
//Numéro de page :     1
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
//--------------------------------------------------
//Numéro de page :     2
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
```

### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Obtient le moniteur d'interruption.

**Returns:**
[InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) - the interrupt monitor.
### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Définit le moniteur d'interruption.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) | le moniteur d’interruption. |

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

### isAutoAdjustPalette() {#isAutoAdjustPalette--}
```
public boolean isAutoAdjustPalette()
```


Obtient une valeur indiquant si la palette d'ajustement automatique est activée.

**Returns:**
booléen - `true` si l’ajustement automatique de la palette est activé ; sinon, `false`.
### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Définit une valeur indiquant si la palette d'ajustement automatique est activée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si l’ajustement automatique de la palette est activé ; sinon, `false`. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Obtient une valeur indiquant si l'image possède une couleur d'arrière-plan.

**Returns:**
boolean
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez facilement la valeur du format de fichier avec cette propriété conviviale. Idéal pour les développeurs cherchant un accès rapide aux informations sur le format de fichier.

**Returns:**
long
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient ou définit une valeur pour la couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Obtient ou définit une valeur pour la couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Obtient les métadonnées de l'image.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
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

### getXmpData() {#getXmpData--}
```
public final XmpPacketWrapper getXmpData()
```


Obtient les données Xmp.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public final void setXmpData(XmpPacketWrapper value)
```


Définit les données Xmp.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | les données Xmp. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public final ProgressEventHandler getIProgressEventHandler()
```


Obtient les informations du gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Obtient les informations du gestionnaire d'événement de progression.

Valeur : Les informations du gestionnaire d’événement de progression.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### canSave(ImageOptionsBase options) {#canSave-com.aspose.imaging.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d’enregistrement à utiliser. |

**Returns:**
booléen - `true` si l’image peut être enregistrée dans le format de fichier spécifié représenté par les options d’enregistrement fournies ; sinon, `false`.

**Example: This example shows how to determine whether image can be saved to the specified file format represented by the passed save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    saveOptions.setQuality(50);

    // Déterminez si l’image peut être enregistrée au format JPEG
    boolean canSave = image.canSave(saveOptions);
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Redimensionne l’image. Le [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) par défaut est utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |


**Example: The following example shows how to resize a metafile (WMF and EMF).**

``` java
String baseFolder = "c:\\temp\\";

String[] files = new String[]{"image3.emf", "image4.wmf"};
for (String fileName : files) {
    String inputFile = baseFolder + fileName;
    String outputFile = baseFolder + "Resize_" + fileName;
    com.aspose.imaging.fileformats.emf.MetaImage image = (com.aspose.imaging.fileformats.emf.MetaImage) com.aspose.imaging.Image.load(inputFile);
    try {
        image.resize(image.getWidth() / 4, image.getHeight() / 4);
        image.save(outputFile);
    } finally {
        image.close();
    }
}
```


**Example: The following example shows how to resize SVG image and save it to PNG.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1431\\";
String[] fileNames = new String[] {
                "Logotype.svg",
                "sample_car.svg",
                "rg1024_green_grapes.svg",
                "MidMarkerFigure.svg",
                "embeddedFonts.svg"
        };

com.aspose.imaging.PointF[] scales = new com.aspose.imaging.PointF[] {
                new com.aspose.imaging.PointF(0.5f, 0.5f),
                new com.aspose.imaging.PointF(1f, 1f),
                new com.aspose.imaging.PointF(2f, 2f),
                new com.aspose.imaging.PointF(3.5f, 9.2f),
        };

for (String inputFile : fileNames) {
    for (com.aspose.imaging.PointF scale : scales) {
        String outputFile = String.format("%s_%2.2f_%2.2f.png", inputFile, scale.getX(), scale.getY());
        com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + inputFile);
        try {
            image.resize((int) (image.getWidth() * scale.getX()), (int) (image.getHeight() * scale.getY()));
            image.save(dir + outputFile, new com.aspose.imaging.imageoptions.PngOptions());
        }
        finally {
            image.close();
        }
    }
}
```

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


**Example: This example loads an image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
}
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```


**Example: This example loads a WMF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
}
```


**Example: This example loads a multi-page ODG image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Options d’exportation du masquage
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Utilisez le clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// La couleur d'arrière-plan sera transparente.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Réduire la taille de l'image pour accélérer le processus de segmentation
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Créer une instance de la classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Diviser l'image source en plusieurs clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Obtention du masque de premier plan
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Augmenter la taille du masque à celle de l'image originale
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Appliquer le masque à l'image originale pour obtenir un segment de premier plan
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image and export it to PNG format.**

``` java
// Charger l'image EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Redimensionner l'image en utilisant la méthode d'interpolation cubique Mitchell
    image.resize(400, 400, ResizeType.Mitchell);

    // Exporter l'image au format PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement. |


**Example: This example loads an image and resizes it using various resizing settings.**

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
    // Réduisez de 2 fois en utilisant le rééchantillonnage adaptatif.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing settings.**

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
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Réduisez de 2 fois en utilisant le rééchantillonnage adaptatif.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image using advanced settings.**

``` java
// Charger l'image EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Définir le mode d'interpolation
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Définir le type du filtre
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Définit la méthode de comparaison des couleurs
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Définir la méthode de quantification des couleurs
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Redimensionner l'image en utilisant des paramètres de redimensionnement avancés
    image.resize(400, 400, resizeSettings);

    // Exporter l'image au format PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Obtient les options par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | Les arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis la sauvegardons en utilisant la méthode `DataStreamSupporter.Save(string)`, une image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode `Image.Save(string, ImageOptionsBase)` en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Redimensionne la largeur proportionnellement. Le [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) par défaut est utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Redimensionne la hauteur proportionnellement. Le [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) par défaut est utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |

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


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
Cet exemple charge une image et la redimensionne proportionnellement en utilisant diverses méthodes de redimensionnement. Seule la largeur est spécifiée, la hauteur est calculée automatiquement.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
{
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Redimensionne la hauteur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Type de redimensionnement. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
Cet exemple charge une image et la redimensionne proportionnellement en utilisant diverses méthodes de redimensionnement. Seule la hauteur est spécifiée, la largeur est calculée automatiquement.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Options d’exportation du masquage
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Utilisez le clustering GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// La couleur d'arrière-plan sera transparente.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Réduire la taille de l'image pour accélérer le processus de segmentation
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Créer une instance de la classe ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Diviser l'image source en plusieurs clusters (segments).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Obtention du masque de premier plan
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Augmenter la taille du masque à celle de l'image originale
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Appliquer le masque à l'image originale pour obtenir un segment de premier plan
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Redimensionne la largeur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Redimensionne la hauteur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Fait pivoter, retourner, ou pivoter et retourner l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Type de l'inversion de rotation. |


**Example: This example demonstrates the use of Rotate operation on an image.**
Cet exemple montre l'utilisation de l'opération Rotate sur une image. L'exemple charge un fichier image existant depuis un emplacement disque et effectue l'opération Rotate sur l'image selon la valeur de l'énumération com.aspose.imaging.RotateFlipType
``` java
// Créez une instance de la classe image et initialisez‑la avec un fichier image existant via le chemin du fichier
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Tournez l'image de 180 degrés autour de l'axe X
    image.rotateFlip(com.aspose.imaging.RotateFlipType.Rotate180FlipX);

    // Enregistrer toutes les modifications.
    image.save();
} finally {
    image.dispose();
}
```

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Faire pivoter l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens des aiguilles d'une montre. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadre le rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |


**Example: The following example crops a raster image.**
L'exemple suivant recadre une image raster. La zone de recadrage est spécifiée via com.aspose.imaging.Rectangle.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Recadrez l'image. La zone de recadrage est la zone centrale rectangulaire de l'image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    image.crop(area);

    // Enregistrez l'image recadrée au format PNG
    image.save(dir + "sample.Crop.png");
}
```

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


**Example: The following example crops a raster image.**
L'exemple suivant recadre une image raster. La zone de recadrage est spécifiée via les marges Left, Top, Right, Bottom.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Recadrez à nouveau. Définissez une marge de 10 % de la taille de l'image.
    int horizontalMargin = rasterImage.getWidth() / 10;
    int verticalMargin = rasterImage.getHeight() / 10;
    image.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Enregistrez l'image recadrée au format PNG.
    image.save(dir + "sample.Crop.png");
}
```

### save() {#save--}
```
public final void save()
```


Enregistre les données de l'image dans le flux sous-jacent.


**Example: The following example shows how to save an entire BMP image or part of it to a file or stream.**

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Convertissez en image noir et blanc
    bmpImage.binarizeOtsu();

    // Enregistrez au même emplacement avec les options par défaut.
    image.save();

    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Une palette ne contient que deux couleurs : Noir et Blanc dans ce cas.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.createMonochrome());

    // Pour toutes les images monochromes (y compris les noir et blanc), il suffit d'allouer 1 bit par pixel.
    saveOptions.setBitsPerPixel(1);

    // Enregistrez à un autre emplacement avec les options spécifiées.
    image.save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Enregistrez uniquement la partie centrale de l'image.
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(image.getWidth() / 4, image.getHeight() / 4, image.getWidth() / 2, image.getHeight() / 2);
    image.save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Enregistrez l'image complète dans un flux mémoire
    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions);
        System.out.println("The size of the whole image in bytes: " + stream.size());
    } finally {
        stream.close();
    }

    // Enregistrez la partie centrale de l'image dans un flux mémoire
    stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions, bounds);
        System.out.println("The size of the central part of the image in bytes: " + stream.size());
    } finally {
        stream.close();
    }
} finally {
    image.close();
}

//La sortie peut ressembler à ceci :
//La taille de l'image complète en octets : 1662
//La taille de la partie centrale de l'image en octets : 462
```

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Enregistre l'image à l'emplacement de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer l'image. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options. |


**Example: This example shows the simple steps to Save an Image.**
Cet exemple montre les étapes simples pour enregistrer une image. Pour démontrer cette opération, nous chargeons un fichier existant depuis un emplacement disque et enregistrons l'image au format PSD.
``` java
// Chargez un fichier existant depuis le disque.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Enregistrez l'image au format PSD vers le chemin du fichier avec les paramètres par défaut de PsdOptions
    image.save("C:\\temp\\output.psd", new com.aspose.imaging.imageoptions.PsdOptions());
} finally {
    image.dispose();
}
```

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |


**Example: The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Enregistrez la moitié supérieure de l'image dans un fichier PNG.
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    image.save(dir + "output.png", saveOptions, bounds);
} finally {
    image.dispose();
}
```

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier dans lequel enregistrer les données de l'image. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier dans lequel enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'enregistrement. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | Le flux dans lequel enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'enregistrement. |


**Example: This example shows the process of saving an Image to memory buffer.**
Cet exemple montre le processus d'enregistrement d'une Image dans un tampon mémoire. Pour démontrer cette opération, l'exemple charge un fichier existant depuis un emplacement disque et enregistre l'image au format PSD.
``` java
java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
try {            //Create an instance of image class and initialize it with an existing image file through File path
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
    try {
        //Enregistrez l'image dans un flux mémoire PSD avec les paramètres par défaut de PsdOptions
        image.save(stream, new com.aspose.imaging.imageoptions.PsdOptions());
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | Le flux dans lequel enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'enregistrement. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |


**Example: The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    java.io.OutputStream outputStream = new java.io.FileOutputStream(dir + "sample.output.png");
    try {
        // Enregistrez la moitié supérieure de l'image dans un flux de fichier.
        image.save(outputStream, saveOptions, bounds);
    } finally {
        outputStream.close();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Définit la palette de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette à définir. |
| updateColors | boolean | si défini sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber) {#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---}
```
public InputStream getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)
```


Convertit en aps.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'image. |
| clippingRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle de découpage. |
| pageNumber | int[] | Le numéro de page. |

**Returns:**
java.io.InputStream - Le flux sérialisé
