---
title: "ImageParameters"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "DNG‑Bildparameter"
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

DNG‑Bildparameter
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | Liest die DNG-Version. |
| [getDescription()](#getDescription--) | Liest die Farbbeschreibung (RGBG,RGBE,GMCY oder GBTG). |
| [getModel()](#getModel--) | Liest das Kameramodell. |
| [getCameraManufacturer()](#getCameraManufacturer--) | Liest den Kamerahersteller. |
| [isFoveon()](#isFoveon--) | Liest die Foveon-Matrix. |
| [getSoftware()](#getSoftware--) | Liest die Software. |
| [getRawCount()](#getRawCount--) | Liest die Anzahl der RAW-Bilder in der Datei (0 bedeutet, dass die Datei nicht erkannt wurde). |
| [getFilters()](#getFilters--) | Liest die Bitmaske, die die Reihenfolge der Farbpixel in der Matrix beschreibt. |
| [getColorsCount()](#getColorsCount--) | Liest die Farben. |
| [getXmpData()](#getXmpData--) | Liest die XMP-Daten. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | Liest das Übersetzungsarray für das CFA-Mosaik-DNG-Format. |

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

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


Liest die DNG-Version.

Wert: Die DNG-Version.

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


Liest die Farbbeschreibung (RGBG,RGBE,GMCY oder GBTG).

Wert: Die cdesc.

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


Liest das Kameramodell.

Wert: Das Modell.

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


Liest den Kamerahersteller.

Wert: Der Hersteller.

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


Liest die Foveon-Matrix.

Wert: Ist foveon.

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Liest die Software.

Wert: Die Software.

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


Liest die Anzahl der RAW-Bilder in der Datei (0 bedeutet, dass die Datei nicht erkannt wurde).

Wert: Die Rohanzahl.

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


Liest die Bitmaske, die die Reihenfolge der Farbpixel in der Matrix beschreibt.

Wert: Die Filter.

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


Liest die Farben.

Wert: Die Farben.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


Liest die XMP-Daten.

Wert: Die XMP-Daten.

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


Liest das Übersetzungsarray für das CFA-Mosaik-DNG-Format.

Wert: Die xtrans.

**Returns:**
java.lang.String[]
