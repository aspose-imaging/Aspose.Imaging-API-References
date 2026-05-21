---
title: "ImageOtherParameters"
second_title: "Aspose.Imaging för Java API-referens"
description: "Andra bildparametrar"
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

Andra bildparametrar
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDescription()](#getDescription--) | Hämtar bildbeskrivningen. |
| [getArtist()](#getArtist--) | Hämtar bildens författare. |
| [getTimestamp()](#getTimestamp--) | Hämtar fotograferingsdatumet. |
| [getShotOrder()](#getShotOrder--) | Hämtar bildens serienummer. |
| [getAperture()](#getAperture--) | Hämtar bländaren. |
| [getShutterSpeed()](#getShutterSpeed--) | Hämtar slutartiden. |
| [getGpsData()](#getGpsData--) | Hämtar GPS-data. |
| [getFocalLength()](#getFocalLength--) | Hämtar fokallängden. |
| [getIsoSpeed()](#getIsoSpeed--) | Hämtar ISO‑känsligheten. |

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
        // Konvertera tidsstämpel till en läsbar sträng.
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat(\"yyyy-MM-dd\");
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

    // Exportera till PNG med standardalternativ.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// Kameratillverkaren:              Leica
// Kameramodellen:                     M8 Digital Camera
// Antalet färger:                     3
// Färgbeskrivning:               RGBG
// DNG-versionen:                      16777216
// Antalet RAW-bilder i filen: 1
// Programvaran:                         1.107
// Ordningen på färgpixlarna:        10110100101101001011010010110100
// Bländaren:                         0
// Beskrivningen:
// Brännvidden:                     50
// ISO-känsligheten:                  160
// Bildens serienummer:       0
// Slutartiden:                    12
// Fotodatum:                 8/3/2007 3:13:49 AM
```

### getDescription() {#getDescription--}
```
public String getDescription()
```


Hämtar bildbeskrivningen.

Värde: Beskrivning.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


Hämtar bildens författare.

Värde: Artisten.

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


Hämtar fotograferingsdatumet.

Värde: Tidsstämpeln.

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


Hämtar bildens serienummer.

Värde: Skottordning.

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


Hämtar bländaren.

Värde: Bländaren.

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


Hämtar slutartiden.

Värde: Slutaren.

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


Hämtar GPS-data.

Värde: GPS-data.

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


Hämtar fokallängden.

Value: Fokallängden.

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


Hämtar ISO‑känsligheten.

Värde: ISO-hastigheten.

**Returns:**
float
