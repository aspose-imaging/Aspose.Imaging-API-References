---
title: "BildWeitereParameter"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Weitere Bildparameter"
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

Weitere Bildparameter
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDescription()](#getDescription--) | Liefert die Bildbeschreibung. |
| [getArtist()](#getArtist--) | Ermittelt den Autor des Bildes. |
| [getTimestamp()](#getTimestamp--) | Ermittelt das Aufnahmedatum. |
| [getShotOrder()](#getShotOrder--) | Ermittelt die Seriennummer des Bildes. |
| [getAperture()](#getAperture--) | Ermittelt die Blende. |
| [getShutterSpeed()](#getShutterSpeed--) | Ermittelt die Verschlusszeit. |
| [getGpsData()](#getGpsData--) | Ermittelt die GPS-Daten. |
| [getFocalLength()](#getFocalLength--) | Ermittelt die Brennweite. |
| [getIsoSpeed()](#getIsoSpeed--) | Ermittelt die ISO-Empfindlichkeit. |

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
        // Konvertiert den Zeitstempel in einen menschenlesbaren String.
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

    // Exportiere nach PNG mit den Standardoptionen.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// Der Kamerahersteller:              Leica
// Das Kameramodell:                     M8 Digital Camera
// Die Farbanzahl:                     3
// Die Farbbeschreibung:               RGBG
// Die DNG-Version:                      16777216
// Die Anzahl der RAW-Bilder in der Datei: 1
// Die Software:                         1.107
// Die Reihenfolge der Farbpixel:        10110100101101001011010010110100
// Die Blende:                         0
// Die Beschreibung:
// Die Brennweite:                     50
// Die ISO-Empfindlichkeit:                  160
// Die Seriennummer des Bildes:       0
// Die Verschlusszeit:                    12
// Das Aufnahmedatum:                 8/3/2007 3:13:49 AM
```

### getDescription() {#getDescription--}
```
public String getDescription()
```


Liefert die Bildbeschreibung.

Wert: Die Beschreibung.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


Ermittelt den Autor des Bildes.

Wert: Der Künstler.

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


Ermittelt das Aufnahmedatum.

Wert: Der Zeitstempel.

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


Ermittelt die Seriennummer des Bildes.

Wert: Die Aufnahmereihenfolge.

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


Ermittelt die Blende.

Wert: Die Blende.

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


Ermittelt die Verschlusszeit.

Wert: Der Verschluss.

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


Ermittelt die GPS-Daten.

Wert: Die GPS-Daten.

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


Ermittelt die Brennweite.

Wert: Die Brennweite.

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


Ermittelt die ISO-Empfindlichkeit.

Wert: Die ISO‑Geschwindigkeit.

**Returns:**
float
