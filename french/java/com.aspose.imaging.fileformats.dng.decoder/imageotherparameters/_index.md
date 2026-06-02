---
title: "ImageOtherParameters"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Autres paramètres d'image."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

Autres paramètres d'image.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDescription()](#getDescription--) | Obtient la description de l'image. |
| [getArtist()](#getArtist--) | Obtient l'auteur de l'image. |
| [getTimestamp()](#getTimestamp--) | Obtient la date de prise de vue. |
| [getShotOrder()](#getShotOrder--) | Obtient le numéro de série de l'image. |
| [getAperture()](#getAperture--) | Obtient l'ouverture. |
| [getShutterSpeed()](#getShutterSpeed--) | Obtient la vitesse d'obturation. |
| [getGpsData()](#getGpsData--) | Obtient les données GPS. |
| [getFocalLength()](#getFocalLength--) | Obtient la longueur focale. |
| [getIsoSpeed()](#getIsoSpeed--) | Obtient la sensibilité ISO. |

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

### getDescription() {#getDescription--}
```
public String getDescription()
```


Obtient la description de l'image.

Valeur : La description.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


Obtient l'auteur de l'image.

Valeur : L'artiste.

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


Obtient la date de prise de vue.

Valeur : L'horodatage.

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


Obtient le numéro de série de l'image.

Valeur : L'ordre de prise.

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


Obtient l'ouverture.

Valeur : L'ouverture.

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


Obtient la vitesse d'obturation.

Valeur : L'obturation.

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


Obtient les données GPS.

Valeur : Les données GPS.

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


Obtient la longueur focale.

Valeur: La longueur focale.

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


Obtient la sensibilité ISO.

Valeur : La vitesse ISO.

**Returns:**
float
