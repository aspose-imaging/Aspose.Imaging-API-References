---
title: "ImageParameters"
second_title: "Aspose.Imaging för Java API-referens"
description: "DNG-bildparametrar"
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

DNG-bildparametrar
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | Hämtar DNG-versionen. |
| [getDescription()](#getDescription--) | Hämtar beskrivningen av färger (RGBG,RGBE,GMCY, eller GBTG). |
| [getModel()](#getModel--) | Hämtar kameramodellen. |
| [getCameraManufacturer()](#getCameraManufacturer--) | Hämtar kameratillverkaren. |
| [isFoveon()](#isFoveon--) | Hämtar om det är en foveon-matris. |
| [getSoftware()](#getSoftware--) | Hämtar mjukvaran. |
| [getRawCount()](#getRawCount--) | Hämtar antalet RAW-bilder i filen (0 betyder att filen inte har identifierats). |
| [getFilters()](#getFilters--) | Hämtar bitmasken som beskriver ordningen på färgpixlar i matrisen. |
| [getColorsCount()](#getColorsCount--) | Hämtar färgerna. |
| [getXmpData()](#getXmpData--) | Hämtar XMP-data. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | Hämtar översättningsarrayen för CFA-mosaik DNG-format. |

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

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


Hämtar DNG-versionen.

Värde: DNG-versionen.

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


Hämtar beskrivningen av färger (RGBG,RGBE,GMCY, eller GBTG).

Värde: cdesc.

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


Hämtar kameramodellen.

Värde: Modellen.

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


Hämtar kameratillverkaren.

Värde: tillverkaren.

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


Hämtar om det är en foveon-matris.

Värde: är foveon.

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Hämtar mjukvaran.

Värde: Mjukvaran.

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


Hämtar antalet RAW-bilder i filen (0 betyder att filen inte har identifierats).

Värde: raw-antalet.

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


Hämtar bitmasken som beskriver ordningen på färgpixlar i matrisen.

Värde: filtren.

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


Hämtar färgerna.

Värde: färgerna.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


Hämtar XMP-data.

Värde: XMP-data.

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


Hämtar översättningsarrayen för CFA-mosaik DNG-format.

Värde: xtrans.

**Returns:**
java.lang.String[]
