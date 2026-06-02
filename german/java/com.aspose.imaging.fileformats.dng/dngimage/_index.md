---
title: "DngImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API zur Verarbeitung des DNG Digital Negative Bilddateiformats, das für die Bedürfnisse der digitalen Fotografie verwendet wird, indem sie umfassende Unterstützung für Rohdateien und Metadaten bietet."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

Die API zur Verarbeitung des DNG (Digital Negative) Bilddateiformats, das für die Anforderungen der digitalen Fotografie verwendet wird, bietet umfassende Unterstützung für Rohdateien und Metadaten. Entwickelt für den Einsatz mit Digitalkameras verschiedener Hersteller, ermöglicht sie Entwicklern, Aspekte wie Bits pro Pixel zu manipulieren, interne Daten zu extrahieren und den Bildausgleich effizient anzupassen. Mit Funktionen zum nahtlosen Aktualisieren und Speichern von Bilddaten befähigt diese API Entwickler, mit DNG-Dateien zu arbeiten, und sorgt für hochwertige Ergebnisse sowie vielseitige Verarbeitungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DngImage()](#DngImage--) | Initialisieren Sie mühelos eine neue Instanz der Klasse [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermitteln Sie mühelos die Anzahl der Bits pro Pixel im Bild mit dieser Eigenschaft. |
| [getHeight()](#getHeight--) | Rufen Sie die Höhe des Bildes mit dieser Eigenschaft ab. |
| [getWidth()](#getWidth--) | Greifen Sie auf die Breite des Bildes mit dieser Eigenschaft zu. |
| [getFileFormat()](#getFileFormat--) | Identifizieren Sie das Dateiformat Ihres Bildes mit dieser Eigenschaft. |
| [getImgData()](#getImgData--) | Verwalten Sie die Bilddaten mit dieser Eigenschaft. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | Verwalten Sie die Bilddaten mit dieser Eigenschaft. |

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

### DngImage() {#DngImage--}
```
public DngImage()
```


Initialisieren Sie mühelos eine neue Instanz der Klasse [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage). Perfekt für Entwickler, die DngImage-Objekte schnell und effizient in ihren Projekten einsetzen möchten.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermitteln Sie mühelos die Anzahl der Bits pro Pixel im Bild mit dieser Eigenschaft. Ideal, um die Pixeltiefe des Bildes schnell und genau zu verstehen.

Wert: Die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Rufen Sie die Höhe des Bildes mit dieser Eigenschaft ab. Perfekt, um die vertikale Größe des Bildes ohne Aufwand zu bestimmen.

Wert: Die Bildhöhe.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Greifen Sie auf die Breite des Bildes mit dieser Eigenschaft zu. Ideal, um die horizontale Größe des Bildes schnell und effizient zu erhalten.

Wert: Die Bildbreite.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Identifizieren Sie das Dateiformat Ihres Bildes mit dieser Eigenschaft. Perfekt, um das Format zu verstehen - einfach und klar.

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


Verwalten Sie die Bilddaten mit dieser Eigenschaft. Egal, ob Sie sie abrufen oder aktualisieren, diese Eigenschaft bietet nahtlosen Zugriff auf die Bilddaten für eine effiziente Manipulation.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


Verwalten Sie die Bilddaten mit dieser Eigenschaft. Egal, ob Sie sie abrufen oder aktualisieren, diese Eigenschaft bietet nahtlosen Zugriff auf die Bilddaten für eine effiziente Manipulation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | Die img-Daten. |

