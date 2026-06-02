---
title: "JpegImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Manipulez efficacement les images raster JPEG avec notre API offrant la prise en charge de divers profils couleur tels que RGB et CMYK, une résolution personnalisable en bits par pixel et le traitement des conteneurs de métadonnées EXIF, JFIF et XMP."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

Manipulez efficacement les images raster JPEG avec notre API, offrant la prise en charge de divers profils couleur tels que RGB et CMYK, une résolution personnalisable en bits par pixel et le traitement des conteneurs de métadonnées EXIF, JFIF et XMP. Profitez d'une rotation automatisée basée sur les données d'orientation et choisissez parmi différents niveaux de compression, y compris le JPEG sans perte, pour obtenir un équilibre optimal entre qualité d'image et taille de fichier pour vos projets.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | La classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) s'initialise sans effort en invoquant son constructeur avec le paramètre de chemin spécifié. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | Initialisez un objet image JPEG avec la classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) en utilisant un paramètre de flux. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | Initialisez une nouvelle instance de la classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) avec un paramètre d'image raster. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | Créez une nouvelle instance de la classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) avec les paramètres de largeur et de hauteur spécifiés. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | Initialisez un nouvel objet [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) avec les options JPEG fournies. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Récupérez le format de l'image sans effort avec cette propriété. |
| [getJpegOptions()](#getJpegOptions--) | Accédez facilement aux options JPEG utilisées lors de la création ou du chargement de cette instance [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage). |
| [getBitsPerPixel()](#getBitsPerPixel--) | Récupérez la profondeur de pixel de l'image sans effort avec cette propriété, offrant un aperçu de la richesse de la représentation couleur ou niveaux de gris. |
| [getComment()](#getComment--) | Gérez les commentaires du fichier JPEG avec cette propriété, vous permettant d'ajouter ou de récupérer des annotations descriptives associées à l'image. |
| [setComment(String value)](#setComment-java.lang.String-) | Gérez les commentaires du fichier JPEG avec cette propriété, vous permettant d'ajouter ou de récupérer des annotations descriptives associées à l'image. |
| [getJpegExifData()](#getJpegExifData--) | Obtient l'instance Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Gérez les données EXIF avec cette propriété, vous permettant d'ajouter ou de récupérer les métadonnées associées à l'image. |
| [getExifData()](#getExifData--) | Obtient les données Exif ; |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Définit les données Exif ; |
| [getHeight()](#getHeight--) | Récupérez sans effort la hauteur de l'image avec cette propriété. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Cette propriété vous donne accès à la résolution horizontale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Cette propriété vous donne accès à la résolution horizontale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce. |
| [getJfif()](#getJfif--) | Cette propriété vous permet d'accéder ou de modifier les données JFIF (JPEG File Interchange Format) associées à l'image JPEG. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Cette propriété vous permet d'accéder ou de modifier les données JFIF (JPEG File Interchange Format) associées à l'image JPEG. |
| [getRawDataFormat()](#getRawDataFormat--) | Cette propriété récupère le format des données brutes de l'image, indiquant comment les données de l'image sont structurées et encodées. |
| [getVerticalResolution()](#getVerticalResolution--) | Cette propriété gère la résolution verticale, exprimée en pixels par pouce, pour le [RasterImage](../../com.aspose.imaging/rasterimage) associé. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Cette propriété gère la résolution verticale, exprimée en pixels par pouce, pour le [RasterImage](../../com.aspose.imaging/rasterimage) associé. |
| [getWidth()](#getWidth--) | Cette propriété récupère la largeur de l'image, exprimée en pixels. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Le profil couleur RGB pour les images JPEG CMYK et YCCK garantit une conversion et une représentation précises des couleurs. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Le profil couleur RGB pour les images JPEG CMYK et YCCK garantit une conversion et une représentation précises des couleurs. |
| [getCmykColorProfile()](#getCmykColorProfile--) | Le profil couleur CMYK associé aux images JPEG CMYK et YCCK assure une conversion précise des couleurs et une fidélité optimale. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Le profil couleur CMYK associé aux images JPEG CMYK et YCCK assure une conversion précise des couleurs et une fidélité optimale. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | Le RGBColorProfile est essentiel pour une conversion précise des couleurs des images JPEG CMYK et YCCK lors du processus d'enregistrement. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Le RGBColorProfile est essentiel pour une conversion précise des couleurs des images JPEG CMYK et YCCK lors du processus d'enregistrement. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | Le profil couleur CMYK est vital pour une conversion précise des couleurs des images JPEG CMYK et YCCK lors du processus d'enregistrement. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Le profil couleur CMYK est vital pour une conversion précise des couleurs des images JPEG CMYK et YCCK lors du processus d'enregistrement. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | Récupère ou modifie le drapeau indiquant si le profil couleur intégré est ignoré. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | Récupère ou modifie le drapeau indiquant si le profil couleur intégré est ignoré. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options d'image originales de cette instance [Image](../../com.aspose.imaging/image). |
| [removeMetadata()](#removeMetadata--) | Supprime les métadonnées de cette instance d'image en définissant les valeurs `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) et `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) à `null`. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Établit la résolution pour le [RasterImage](../../com.aspose.imaging/rasterimage) spécifié, garantissant un redimensionnement et une impression précis. |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// Chargez une image JPEG depuis un fichier.
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // Effectuez un traitement d'image.
    // Enregistrez dans un autre fichier JPEG.
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


La classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) s'initialise sans effort en invoquant son constructeur avec le paramètre de chemin spécifié. Ce constructeur permet une création fluide d'images JPEG, assurant une intégration rapide dans vos projets avec facilité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger l'image et initialiser les données de pixels et de palette. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


Initialisez un objet image JPEG avec la classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) en utilisant un paramètre de flux. Ce constructeur simplifie le processus de manipulation des images JPEG, offrant une approche directe pour les intégrer à vos projets sans effort.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger l'image et initialiser les données de pixels et de palette. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


Initialisez une nouvelle instance de la classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) avec un paramètre d'image raster. Ce constructeur offre un moyen pratique de créer des images JPEG directement à partir d'images raster, simplifiant le flux de travail pour travailler avec des images JPEG dans vos applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image avec laquelle initialiser les données de pixels et de palette. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


Créez une nouvelle instance de la classe [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) avec les paramètres de largeur et de hauteur spécifiés. Ce constructeur vous permet de créer des images JPEG avec des dimensions personnalisées, vous offrant une flexibilité dans la gestion des tailles d'image dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image. |
| height | int | La hauteur de l'image. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


Initialisez un nouvel objet [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) avec les options JPEG fournies. Ce constructeur vous permet d'ajuster divers paramètres pour l'image JPEG, tels que le niveau de compression, la qualité et d'autres paramètres, offrant un contrôle précis sur le format d'image résultant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Les options jpeg. |
| width | int | Largeur de l'image. |
| height | int | Hauteur de l'image. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez le format de l'image facilement avec cette propriété. Elle fournit des informations précieuses sur le format de fichier, facilitant l'intégration transparente et les vérifications de compatibilité sur diverses plateformes et applications.

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


Accédez facilement aux options JPEG utilisées lors de la création ou du chargement de cette instance [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage). Cette propriété offre des détails précieux sur les paramètres spécifiques employés, permettant aux utilisateurs de comprendre et de reproduire efficacement les flux de travail de traitement d'image. Qu'il s'agisse des niveaux de compression, des réglages de qualité ou d'autres paramètres, cette propriété fournit des informations essentielles pour une manipulation d'image fluide.

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//Le résultat ressemble à ceci :
//Le nombre de bits par canal : 8
//La taille maximale autorisée pour tous les tampons internes : 0
//Le type de couleur : YCbCr
//Le type de compression : Baseline
//La qualité de l'image : 75
//L'échantillonnage pour le composant 0 : 1x1
//L'échantillonnage pour le composant 1 : 1x1
//L'échantillonnage pour le composant 2 : 1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Récupérez facilement la profondeur de pixel de l'image avec cette propriété, offrant des informations sur la richesse de la représentation couleur ou niveaux de gris. Qu'il s'agisse d'une photographie vibrante ou d'une illustration monochrome, cette propriété fournit des informations essentielles sur la complexité visuelle de l'image.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getComment() {#getComment--}
```
public String getComment()
```


Gérez les commentaires de fichiers JPEG avec cette propriété, vous permettant d'ajouter ou de récupérer des annotations descriptives associées à l'image. Qu'il s'agisse d'étiqueter les images avec des métadonnées ou d'ajouter un contexte supplémentaire, cette propriété offre une flexibilité dans l'organisation et la catégorisation de vos fichiers JPEG.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Gérez les commentaires de fichiers JPEG avec cette propriété, vous permettant d'ajouter ou de récupérer des annotations descriptives associées à l'image. Qu'il s'agisse d'étiqueter les images avec des métadonnées ou d'ajouter un contexte supplémentaire, cette propriété offre une flexibilité dans l'organisation et la catégorisation de vos fichiers JPEG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


Obtient l'instance Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Gérez les données EXIF avec cette propriété, vous permettant d'ajouter ou de récupérer les métadonnées associées à l'image. Qu'il s'agisse d'extraire des informations sur les réglages de l'appareil photo ou de modifier les métadonnées existantes, cette propriété offre une flexibilité dans la gestion du conteneur de données EXIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Obtient les données Exif ;

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//Le résultat ressemble à ceci :
//Les données EXIF générales
//------------------------------------------
//La version EXIF : [B@163e4e87
//Le numéro de série de l'appareil photo : 7100536
//L'espace colorimétrique : SRgb
//La luminosité:
//Le contraste : Normal
//Le gamma:
//La netteté : 0
//L'ouverture : 4,64(4643856 / 1000000)
//Le mode d'exposition : Manuel
//Le biais d'exposition : 0,67(4 / 6)
//Le temps d'exposition : 0,01(1 / 160)
//La distance focale : 145,00(1450 / 10)
//L'unité de résolution du plan focal : cm
//Le modèle d'objectif : 70,0 - 200,0 mm f/ 4,0
//La vitesse d'obturation : 7,32(7321928 / 1000000)
//Les données EXIF JPEG
//------------------------------------------
//Le fabricant de l'appareil photo : NIKON CORPORATION
//Le modèle de l'appareil photo : NIKON D5
//L'interprétation photométrique : 0
//L'artiste :
//Le droit d'auteur :
//La description de l'image :
//L'orientation : HautGauche
//Le logiciel : Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Définit les données Exif ;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Données Exif; |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Récupérez la hauteur de l'image sans effort grâce à cette propriété. Elle offre un accès rapide à la dimension verticale de l'image, vous permettant de déterminer efficacement sa taille et son ratio d'aspect sans avoir besoin de calculs complexes ou de méthodes supplémentaires.

**Returns:**
int - La hauteur de l'image en pixels.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Cette propriété vous donne accès à la résolution horizontale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce. En définissant ou en récupérant cette valeur, vous pouvez contrôler précisément la résolution de l'image, en veillant à ce qu'elle réponde à vos exigences spécifiques en matière de qualité et de clarté.

**Returns:**
double - La résolution horizontale.

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Obtenir la résolution horizontale et verticale du BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 300.0
// La résolution verticale, en pixels par pouce : 300.0
// Définissez les valeurs de résolution à 96 dpi
// La résolution horizontale, en pixels par pouce : 96.0
// La résolution verticale, en pixels par pouce : 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Cette propriété vous donne accès à la résolution horizontale du [RasterImage](../../com.aspose.imaging/rasterimage), mesurée en pixels par pouce. En définissant ou en récupérant cette valeur, vous pouvez contrôler précisément la résolution de l'image, en veillant à ce qu'elle réponde à vos exigences spécifiques en matière de qualité et de clarté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution horizontale. |

Remarque : par défaut, cette valeur est toujours de 96 car les différentes plateformes ne peuvent pas renvoyer la résolution d'écran. Vous pouvez envisager d'utiliser la méthode `setResolution` pour mettre à jour les deux valeurs de résolution en un seul appel. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Cette propriété vous permet d'accéder ou de modifier les données JFIF (JPEG File Interchange Format) associées à l'image JPEG. JFIF est un format standard pour l'échange d'images compressées JPEG entre ordinateurs et autres appareils. En obtenant ou en définissant cette propriété, vous pouvez interagir avec les données JFIF, qui peuvent inclure des informations telles que la résolution de l'image, le ratio d'aspect et la vignette.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Cette propriété vous permet d'accéder ou de modifier les données JFIF (JPEG File Interchange Format) associées à l'image JPEG. JFIF est un format standard pour l'échange d'images compressées JPEG entre ordinateurs et autres appareils. En obtenant ou en définissant cette propriété, vous pouvez interagir avec les données JFIF, qui peuvent inclure des informations telles que la résolution de l'image, le ratio d'aspect et la vignette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Cette propriété récupère le format de données brutes de l'image, qui indique comment les données de l'image sont structurées et encodées. Comprendre le format de données brutes est essentiel pour traiter ou manipuler les données de l'image efficacement. Il fournit des informations sur la représentation sous-jacente de l'image, comme si elle est compressée, encodée dans un espace colorimétrique spécifique ou stockée dans un format de fichier particulier. Accéder à cette propriété vous permet d'obtenir des informations précieuses sur la structure des données de l'image, vous permettant d'effectuer diverses opérations ou optimisations adaptées à son format spécifique.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Cette propriété gère la résolution verticale, exprimée en pixels par pouce, pour le [RasterImage](../../com.aspose.imaging/rasterimage) associé. Ajuster cette résolution influence la taille et la qualité de l'image lorsqu'elle est imprimée ou affichée à une taille physique fixe. En définissant cette propriété, vous contrôlez la densité d'empilement vertical des pixels de l'image, affectant ainsi sa netteté et sa clarté globales.

**Returns:**
double - La résolution verticale.

Remarque : par défaut, cette valeur est toujours 72 car les différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Obtenir la résolution horizontale et verticale du BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 300.0
// La résolution verticale, en pixels par pouce : 300.0
// Définissez les valeurs de résolution à 96 dpi
// La résolution horizontale, en pixels par pouce : 96.0
// La résolution verticale, en pixels par pouce : 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Cette propriété gère la résolution verticale, exprimée en pixels par pouce, pour le [RasterImage](../../com.aspose.imaging/rasterimage) associé. Ajuster cette résolution influence la taille et la qualité de l'image lorsqu'elle est imprimée ou affichée à une taille physique fixe. En définissant cette propriété, vous contrôlez la densité d'empilement vertical des pixels de l'image, affectant ainsi sa netteté et sa clarté globales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution verticale. |

Remarque : par défaut, cette valeur est toujours 72 car les différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Cette propriété récupère la largeur de l'image, exprimée en pixels. Elle fournit des informations essentielles sur les dimensions de l'image, permettant un rendu, une manipulation ou un affichage précis des données de l'image.

**Returns:**
int - La largeur de l'image en pixels.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Le profil couleur RGB pour les images JPEG CMYK et YCCK garantit une conversion et une représentation précises des couleurs. Il doit être associé au CMYKColorProfile pour maintenir la cohérence et la fidélité du rendu des couleurs. Cette association est indispensable pour les applications nécessitant une gestion précise des couleurs et la reproduction d'images, assurant que les données RGB sont correctement interprétées et affichées.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Le profil couleur RGB pour les images JPEG CMYK et YCCK garantit une conversion et une représentation précises des couleurs. Il doit être associé au CMYKColorProfile pour maintenir la cohérence et la fidélité du rendu des couleurs. Cette association est indispensable pour les applications nécessitant une gestion précise des couleurs et la reproduction d'images, assurant que les données RGB sont correctement interprétées et affichées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
L'exemple suivant charge un PNG et l'enregistre au format JPEG CMYK en utilisant un profil ICC personnalisé. Ensuite, il charge le JPEG CMYK et le réenregistre au format PNG. La conversion des couleurs de RGB à CMYK et de CMYK à RGB est effectuée à l'aide de profils ICC personnalisés.
``` java
String dir = "c:\\temp\\";

// Charger le PNG et l'enregistrer au JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Utiliser des profils ICC personnalisés
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Charger le JPEG CMYK et l'enregistrer au PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Utiliser des profils ICC personnalisés
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Le profil couleur CMYK associé aux images JPEG CMYK et YCCK assure une conversion précise des couleurs et une fidélité élevée. Il fonctionne en conjonction avec le RGBColorProfile pour garantir une représentation exacte des couleurs sur divers appareils et applications. Cette association est cruciale pour maintenir la cohérence du rendu des couleurs et obtenir une qualité d'image optimale.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Le profil couleur CMYK associé aux images JPEG CMYK et YCCK assure une conversion précise des couleurs et une fidélité élevée. Il fonctionne en conjonction avec le RGBColorProfile pour garantir une représentation exacte des couleurs sur divers appareils et applications. Cette association est cruciale pour maintenir la cohérence du rendu des couleurs et obtenir une qualité d'image optimale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
L'exemple suivant charge un PNG et l'enregistre au format JPEG CMYK en utilisant un profil ICC personnalisé. Ensuite, il charge le JPEG CMYK et le réenregistre au format PNG. La conversion des couleurs de RGB à CMYK et de CMYK à RGB est effectuée à l'aide de profils ICC personnalisés.
``` java
String dir = "c:\\temp\\";

// Charger le PNG et l'enregistrer au JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Utiliser des profils ICC personnalisés
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Charger le JPEG CMYK et l'enregistrer au PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Utiliser des profils ICC personnalisés
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


Le RGBColorProfile est essentiel pour la conversion précise des couleurs des images JPEG CMYK et YCCK lors du processus d'enregistrement. Lorsqu'il est associé au CMYKColorProfile, il garantit que les couleurs sont rendues correctement et maintient la cohérence sur différents appareils et applications. Cette combinaison est cruciale pour préserver la représentation des couleurs prévue et obtenir une sortie d'image de haute qualité.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


Le RGBColorProfile est essentiel pour la conversion précise des couleurs des images JPEG CMYK et YCCK lors du processus d'enregistrement. Lorsqu'il est associé au CMYKColorProfile, il garantit que les couleurs sont rendues correctement et maintient la cohérence sur différents appareils et applications. Cette combinaison est cruciale pour préserver la représentation des couleurs prévue et obtenir une sortie d'image de haute qualité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


Le profil couleur CMYK est vital pour la conversion précise des couleurs des images JPEG CMYK et YCCK lors du processus d'enregistrement. Il fonctionne en tandem avec le RGBColorProfile pour assurer une représentation correcte des couleurs, en maintenant la cohérence et la qualité sur différents appareils et logiciels. Cette synchronisation est cruciale pour obtenir un rendu des couleurs précis et fiable dans les images finales enregistrées.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


Le profil couleur CMYK est vital pour la conversion précise des couleurs des images JPEG CMYK et YCCK lors du processus d'enregistrement. Il fonctionne en tandem avec le RGBColorProfile pour assurer une représentation correcte des couleurs, en maintenant la cohérence et la qualité sur différents appareils et logiciels. Cette synchronisation est cruciale pour obtenir un rendu des couleurs précis et fiable dans les images finales enregistrées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


Récupère ou modifie le drapeau indiquant si le profil couleur intégré est ignoré. En définissant ce drapeau, les utilisateurs peuvent spécifier si le profil couleur par défaut doit être utilisé à la place de celui intégré. Cette option offre un meilleur contrôle de la gestion des couleurs, facilitant les ajustements pour la cohérence et la compatibilité sur diverses plateformes et applications.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


Récupère ou modifie le drapeau indiquant si le profil couleur intégré est ignoré. En définissant ce drapeau, les utilisateurs peuvent spécifier si le profil couleur par défaut doit être utilisé à la place de celui intégré. Cette option offre un meilleur contrôle de la gestion des couleurs, facilitant les ajustements pour la cohérence et la compatibilité sur diverses plateformes et applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options d'image originales de cette instance [Image](../../com.aspose.imaging/image).

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Supprime les métadonnées de cette instance d'image en définissant les valeurs `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) et `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) à `null`.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Définit la résolution pour le [RasterImage](../../com.aspose.imaging/rasterimage) spécifié, garantissant un redimensionnement et des capacités d'impression précis. Cette méthode permet aux utilisateurs d'adapter la résolution de l'image à leurs besoins spécifiques, que ce soit pour l'affichage numérique ou la reproduction physique. En définissant la résolution, les utilisateurs peuvent optimiser la qualité de l'image et assurer la compatibilité avec divers périphériques et supports de sortie, améliorant ainsi l'expérience visuelle globale et l'utilisabilité de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpiX | double | La résolution horizontale, en points par pouce, du `RasterImage`. |
| dpiY | double | La résolution verticale, en points par pouce, du `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Obtenir la résolution horizontale et verticale du BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 300.0
// La résolution verticale, en pixels par pouce : 300.0
// Définissez les valeurs de résolution à 96 dpi
// La résolution horizontale, en pixels par pouce : 96.0
// La résolution verticale, en pixels par pouce : 96.0
```

