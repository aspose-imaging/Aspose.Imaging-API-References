---
title: "AltriParametriImmagine"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Altri parametri immagine"
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

Altri parametri immagine
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDescription()](#getDescription--) | Restituisce la descrizione dell'immagine. |
| [getArtist()](#getArtist--) | Ottiene l'autore dell'immagine. |
| [getTimestamp()](#getTimestamp--) | Ottiene la data dello scatto. |
| [getShotOrder()](#getShotOrder--) | Ottiene il numero di serie dell'immagine. |
| [getAperture()](#getAperture--) | Ottiene l'apertura. |
| [getShutterSpeed()](#getShutterSpeed--) | Ottiene la velocità dell'otturatore. |
| [getGpsData()](#getGpsData--) | Ottiene i dati GPS. |
| [getFocalLength()](#getFocalLength--) | Ottiene la lunghezza della focale. |
| [getIsoSpeed()](#getIsoSpeed--) | Ottiene la sensibilità ISO. |

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
        // Converti il timestamp in una stringa leggibile dall'uomo.
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

    // Esporta in PNG con le opzioni predefinite.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// Il produttore della fotocamera:              Leica
// Il modello della fotocamera:                     M8 Digital Camera
// Il conteggio dei colori:                     3
// La descrizione dei colori:               RGBG
// La versione DNG:                      16777216
// Il numero di immagini RAW nel file: 1
// Il software:                         1.107
// L'ordine dei pixel di colore:        10110100101101001011010010110100
// L'apertura:                         0
// La descrizione:
// La lunghezza focale:                     50
// La sensibilità ISO:                  160
// Il numero di serie dell'immagine:       0
// La velocità dell'otturatore:                    12
// La data di scatto:                 8/3/2007 3:13:49 AM
```

### getDescription() {#getDescription--}
```
public String getDescription()
```


Restituisce la descrizione dell'immagine.

Valore: La descrizione.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


Ottiene l'autore dell'immagine.

Valore: L'artista.

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


Ottiene la data dello scatto.

Valore: Il timestamp.

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


Ottiene il numero di serie dell'immagine.

Valore: L'ordine di scatto.

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


Ottiene l'apertura.

Valore: L'apertura.

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


Ottiene la velocità dell'otturatore.

Valore: L'otturatore.

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


Ottiene i dati GPS.

Valore: I dati GPS.

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


Ottiene la lunghezza della focale.

Valore: La lunghezza focale.

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


Ottiene la sensibilità ISO.

Valore: La velocità ISO.

**Returns:**
float
