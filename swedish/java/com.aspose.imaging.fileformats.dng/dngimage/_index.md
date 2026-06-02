---
title: "DngImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för att bearbeta DNG Digital Negative-bildfilformatet som används för digital fotografering genom att tillhandahålla omfattande stöd för råfiler och metadata."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

API:et för att bearbeta DNG (Digital Negative) bildfilformat som används för digital fotografering genom att tillhandahålla omfattande stöd för råfiler och metadata. Designat för användning med digitalkameror från olika tillverkare, möjliggör det för utvecklare att manipulera aspekter som bitar per pixel, extrahera intern data och justera bildbalans effektivt. Med möjligheter att uppdatera och spara bilddata sömlöst ger detta API utvecklare möjlighet att arbeta med DNG-filer, vilket säkerställer högkvalitativa resultat och mångsidiga bearbetningsalternativ.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DngImage()](#DngImage--) | Initiera en ny instans av klassen [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) utan ansträngning. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Upptäck antalet bitar per pixel i bilden utan ansträngning med denna egenskap. |
| [getHeight()](#getHeight--) | Hämta bildens höjd med denna egenskap. |
| [getWidth()](#getWidth--) | Få åtkomst till bildens bredd med denna egenskap. |
| [getFileFormat()](#getFileFormat--) | Identifiera filformatet för din bild med denna egenskap. |
| [getImgData()](#getImgData--) | Hantera bilddata med denna egenskap. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | Hantera bilddata med denna egenskap. |

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

### DngImage() {#DngImage--}
```
public DngImage()
```


Initiera en ny instans av klassen [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) utan ansträngning. Perfekt för utvecklare som vill börja använda DngImage-objekt snabbt och effektivt i sina projekt.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Upptäck antalet bitar per pixel i bilden utan ansträngning med denna egenskap. Idealiskt för att snabbt och exakt förstå bildens pixeldjup.

Värde: Bildens bitar per pixel-antal.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämta bildens höjd med denna egenskap. Perfekt för att bestämma bildens vertikala storlek utan krångel.

Värde: Bildens höjd.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Få åtkomst till bildens bredd med denna egenskap. Idealiskt för att snabbt och effektivt erhålla bildens horisontella storlek.

Värde: Bildens bredd.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Identifiera filformatet för din bild med denna egenskap. Perfekt för att förstå formatet – bara enkla detaljer.

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


Hantera bilddata med denna egenskap. Oavsett om du hämtar eller uppdaterar, ger denna egenskap sömlös åtkomst till bilddata för effektiv manipulation.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


Hantera bilddata med denna egenskap. Oavsett om du hämtar eller uppdaterar, ger denna egenskap sömlös åtkomst till bilddata för effektiv manipulation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | Img-data. |

