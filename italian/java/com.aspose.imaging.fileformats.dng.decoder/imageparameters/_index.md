---
title: "ImageParameters"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Parametri immagine DNG"
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

Parametri immagine DNG
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | Ottiene la versione DNG. |
| [getDescription()](#getDescription--) | Ottiene la descrizione dei colori (RGBG,RGBE,GMCY, o GBTG). |
| [getModel()](#getModel--) | Ottiene il modello della fotocamera. |
| [getCameraManufacturer()](#getCameraManufacturer--) | Ottiene il produttore della fotocamera. |
| [isFoveon()](#isFoveon--) | Ottiene la matrice foveon. |
| [getSoftware()](#getSoftware--) | Ottiene il software. |
| [getRawCount()](#getRawCount--) | Ottiene il numero di immagini RAW nel file (0 indica che il file non è stato riconosciuto). |
| [getFilters()](#getFilters--) | Ottiene la maschera di bit che descrive l'ordine dei pixel di colore nella matrice. |
| [getColorsCount()](#getColorsCount--) | Ottiene i colori. |
| [getXmpData()](#getXmpData--) | Ottiene i dati XMP. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | Ottiene l'array di traduzione per il formato DNG a mosaico CFA. |

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

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


Ottiene la versione DNG.

Valore: La versione DNG.

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


Ottiene la descrizione dei colori (RGBG,RGBE,GMCY, o GBTG).

Valore: La cdesc.

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


Ottiene il modello della fotocamera.

Valore: Il modello.

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


Ottiene il produttore della fotocamera.

Valore: Il produttore.

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


Ottiene la matrice foveon.

Valore: È foveon.

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Ottiene il software.

Valore: Il software.

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


Ottiene il numero di immagini RAW nel file (0 indica che il file non è stato riconosciuto).

Valore: Il conteggio RAW.

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


Ottiene la maschera di bit che descrive l'ordine dei pixel di colore nella matrice.

Valore: I filtri.

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


Ottiene i colori.

Valore: I colori.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


Ottiene i dati XMP.

Valore: I dati XMP.

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


Ottiene l'array di traduzione per il formato DNG a mosaico CFA.

Valore: Il xtrans.

**Returns:**
java.lang.String[]
