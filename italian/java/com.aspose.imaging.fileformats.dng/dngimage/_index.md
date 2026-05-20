---
title: "DngImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per l'elaborazione del formato di file immagine DNG Digital Negative, utilizzato per le esigenze della fotografia digitale, fornendo un supporto completo per i file raw e i metadati."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

L'API per l'elaborazione del formato di file immagine DNG (Digital Negative) utilizzato per le esigenze della fotografia digitale, fornendo supporto completo per file raw e metadati. Progettata per l'uso con fotocamere digitali di vari produttori, consente agli sviluppatori di manipolare aspetti come i bit per pixel, estrarre dati interni e regolare l'equilibrio dell'immagine in modo efficiente. Con capacità di aggiornare e salvare i dati dell'immagine senza interruzioni, questa API consente agli sviluppatori di lavorare con file DNG, garantendo risultati di alta qualità e opzioni di elaborazione versatili.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DngImage()](#DngImage--) | Inizializza una nuova istanza della classe [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) senza sforzo. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Scopri il numero di bit per pixel nell'immagine senza sforzo con questa proprietà. |
| [getHeight()](#getHeight--) | Recupera l'altezza dell'immagine con questa proprietà. |
| [getWidth()](#getWidth--) | Accedi alla larghezza dell'immagine con questa proprietà. |
| [getFileFormat()](#getFileFormat--) | Identifica il formato file della tua immagine con questa proprietà. |
| [getImgData()](#getImgData--) | Gestisci i dati dell'immagine con questa proprietà. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | Gestisci i dati dell'immagine con questa proprietà. |

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

### DngImage() {#DngImage--}
```
public DngImage()
```


Inizializza una nuova istanza della classe [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) senza sforzo. Perfetto per gli sviluppatori che desiderano iniziare a utilizzare gli oggetti DngImage rapidamente ed efficientemente nei loro progetti.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Scopri il numero di bit per pixel nell'immagine senza sforzo con questa proprietà. Ideale per comprendere rapidamente e accuratamente la profondità dei pixel dell'immagine.

Valore: il conteggio dei bit per pixel dell'immagine.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Recupera l'altezza dell'immagine con questa proprietà. Perfetto per determinare la dimensione verticale dell'immagine senza problemi.

Valore: l'altezza dell'immagine.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Accedi alla larghezza dell'immagine con questa proprietà. Ideale per ottenere rapidamente ed efficientemente la dimensione orizzontale dell'immagine.

Valore: la larghezza dell'immagine.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Identifica il formato file della tua immagine con questa proprietà. Perfetto per comprendere il formato - semplici dettagli.

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


Gestisci i dati dell'immagine con questa proprietà. Che tu stia recuperando o aggiornando, questa proprietà fornisce un accesso senza interruzioni ai dati dell'immagine per una manipolazione efficiente.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


Gestisci i dati dell'immagine con questa proprietà. Che tu stia recuperando o aggiornando, questa proprietà fornisce un accesso senza interruzioni ai dati dell'immagine per una manipolazione efficiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | I dati img. |

