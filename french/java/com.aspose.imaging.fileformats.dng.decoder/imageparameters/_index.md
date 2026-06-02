---
title: "ImageParameters"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Paramètres d'image DNG."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

Paramètres d'image DNG.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | Obtient la version DNG. |
| [getDescription()](#getDescription--) | Obtient la description des couleurs (RGBG,RGBE,GMCY, ou GBTG). |
| [getModel()](#getModel--) | Obtient le modèle de l'appareil photo. |
| [getCameraManufacturer()](#getCameraManufacturer--) | Obtient le fabricant de l'appareil photo. |
| [isFoveon()](#isFoveon--) | Obtient la matrice foveon. |
| [getSoftware()](#getSoftware--) | Obtient le logiciel. |
| [getRawCount()](#getRawCount--) | Obtient le nombre d'images RAW dans le fichier (0 signifie que le fichier n'a pas été reconnu). |
| [getFilters()](#getFilters--) | Obtient le masque de bits décrivant l'ordre des pixels de couleur dans la matrice. |
| [getColorsCount()](#getColorsCount--) | Obtient les couleurs. |
| [getXmpData()](#getXmpData--) | Obtient les données XMP. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | Obtient le tableau de traduction pour le format DNG à mosaïque CFA. |

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

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


Obtient la version DNG.

Valeur : La version DNG.

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


Obtient la description des couleurs (RGBG,RGBE,GMCY, ou GBTG).

Valeur : La cdesc.

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


Obtient le modèle de l'appareil photo.

Valeur : Le modèle.

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


Obtient le fabricant de l'appareil photo.

Valeur : Le fabricant.

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


Obtient la matrice foveon.

Valeur : Le est foveon.

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Obtient le logiciel.

Valeur : Le logiciel.

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


Obtient le nombre d'images RAW dans le fichier (0 signifie que le fichier n'a pas été reconnu).

Valeur : Le nombre brut.

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


Obtient le masque de bits décrivant l'ordre des pixels de couleur dans la matrice.

Valeur : Les filtres.

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


Obtient les couleurs.

Valeur : Les couleurs.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


Obtient les données XMP.

Valeur : Les données XMP.

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


Obtient le tableau de traduction pour le format DNG à mosaïque CFA.

Valeur : Le xtrans.

**Returns:**
java.lang.String[]
