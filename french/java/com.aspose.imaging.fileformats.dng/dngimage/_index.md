---
title: "DngImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API de traitement du format d'image DNG Digital Negative utilisé pour les besoins de la photographie numérique en offrant une prise en charge complète des fichiers RAW et des métadonnées."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

L'API de traitement du format de fichier image DNG (Digital Negative) utilisé pour les besoins de la photographie numérique en offrant un support complet pour les fichiers bruts et les métadonnées. Conçue pour être utilisée avec les appareils photo numériques de divers fabricants, elle permet aux développeurs de manipuler des aspects tels que les bits par pixel, d'extraire les données internes et d'ajuster l'équilibre de l'image efficacement. Avec la capacité de mettre à jour et d'enregistrer les données d'image de manière fluide, cette API permet aux développeurs de travailler avec les fichiers DNG, garantissant des résultats de haute qualité et des options de traitement polyvalentes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DngImage()](#DngImage--) | Initialisez une nouvelle instance de la classe [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) sans effort. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Découvrez le nombre de bits par pixel de l'image sans effort grâce à cette propriété. |
| [getHeight()](#getHeight--) | Récupérez la hauteur de l'image avec cette propriété. |
| [getWidth()](#getWidth--) | Accédez à la largeur de l'image avec cette propriété. |
| [getFileFormat()](#getFileFormat--) | Identifiez le format de fichier de votre image avec cette propriété. |
| [getImgData()](#getImgData--) | Gérez les données de l'image avec cette propriété. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | Gérez les données de l'image avec cette propriété. |

## Example: This example shows how to load a DNG image from a file, print its properties and save it to PNG.

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "test.dng");
try {
    com.aspose.imaging.fileformats.dng.DngImage dngImage = (com.aspose.imaging.fileformats.dng.DngImage) image;
    com.aspose.imaging.fileformats.dng.decoder.RawData rawData = dngImage.getImgData();
    com.aspose.imaging.fileformats.dng.decoder.ImageParameters parameters = rawData.getImageDataParameters();
    if (parameters != null) {
        System.out.println("The camera manufacturer:              " + parameters.getCameraManufacturer());
        System.out.println("The camera model:                     " + parameters.getModel());
        System.out.println("The colors count:                     " + parameters.getColorsCount());
        System.out.println("The colors description:               " + parameters.getDescription());
        System.out.println("The DNG version:                      " + parameters.getDngVersion());
        System.out.println("The number of RAW images in the file: " + parameters.getRawCount());
        System.out.println("The software:                         " + parameters.getSoftware());
        System.out.println("The order of the color pixels:        " + Long.toBinaryString(parameters.getFilters()));

        String[] translationCfaDng = parameters.getTranslationCfaDng();
        if (translationCfaDng != null) {
            System.out.printf("The translation array for CFA mosaic %s:\r\n", translationCfaDng.length);
            for (String s : translationCfaDng) {
                System.out.printf("- %s\r\n", s);
            }
        }
    }

    com.aspose.imaging.fileformats.dng.decoder.ImageOtherParameters otherParameters = rawData.getImageOtherParameters();
    if (otherParameters != null) {
        // Convertit l'horodatage en une chaîne lisible par l'homme.
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat("yyyy-MM-dd");
        java.util.Date date = new java.util.Date(otherParameters.getTimestamp());
        //System.out.println(sf.format(date));

        System.out.printf("The aperture:                         " + otherParameters.getAperture());
        System.out.printf("The description:                      " + otherParameters.getDescription());
        System.out.printf("The focal length:                     " + otherParameters.getFocalLength());
        System.out.printf("The ISO sensitivity:                  " + otherParameters.getIsoSpeed());
        System.out.printf("The serial number of the image:       " + otherParameters.getShotOrder());
        System.out.printf("The shutter speed:                    " + otherParameters.getShutterSpeed());
        System.out.printf("The date of shooting:                 " + date);
    }

    // Exportation vers PNG avec les options par défaut.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// Le fabricant de l'appareil photo :              Leica
// Le modèle d'appareil photo:                     M8 Digital Camera
// Le nombre de couleurs:                     3
// La description des couleurs:               RGBG
// La version DNG:                      16777216
// Le nombre d'images RAW dans le fichier: 1
// Le logiciel:                         1.107
// L'ordre des pixels couleur:        10110100101101001011010010110100
// L'ouverture:                         0
// La description:
// La distance focale:                     50
// La sensibilité ISO:                  160
// Le numéro de série de l'image:       0
// La vitesse d'obturation:                    12
// La date de prise de vue:                 8/3/2007 3:13:49 AM
```

### DngImage() {#DngImage--}
```
public DngImage()
```


Initialisez une nouvelle instance de la classe [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) sans effort. Idéal pour les développeurs souhaitant commencer à utiliser les objets DngImage rapidement et efficacement dans leurs projets.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Découvrez le nombre de bits par pixel de l'image sans effort grâce à cette propriété. Idéal pour comprendre rapidement et précisément la profondeur de pixel de l'image.

Valeur : le nombre de bits par pixel de l'image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Récupérez la hauteur de l'image avec cette propriété. Idéal pour déterminer la taille verticale de l'image sans tracas.

Valeur : la hauteur de l'image.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Accédez à la largeur de l'image avec cette propriété. Idéal pour obtenir rapidement et efficacement la taille horizontale de l'image.

Valeur : la largeur de l'image.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Identifiez le format de fichier de votre image avec cette propriété. Idéal pour comprendre le format – des détails simples et clairs.

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


Gérez les données de l'image avec cette propriété. Que vous récupériez ou mettiez à jour, cette propriété offre un accès fluide aux données de l'image pour une manipulation efficace.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


Gérez les données de l'image avec cette propriété. Que vous récupériez ou mettiez à jour, cette propriété offre un accès fluide aux données de l'image pour une manipulation efficace.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | Les données img. |

