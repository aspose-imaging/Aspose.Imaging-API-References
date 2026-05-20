---
title: "Jpeg2000Options"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Crea file immagine JPEG2000 JP2 con la nostra API, utilizzando la tecnologia wavelet avanzata per la codifica di contenuti senza perdita."
type: docs
weight: 25
url: /it/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

Crea file immagine JPEG2000 (JP2) con la nostra API, utilizzando la tecnologia wavelet avanzata per la codifica di contenuti senza perdita. Approfitta del supporto per vari codec, inclusa la compressione irreversibile e senza perdita, nonché dei contenitori di metadati XMP, garantendo versatilità e creazione di immagini ad alta qualità su misura per le tue esigenze.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Inizializza una nuova istanza della classe `Jpeg2000Options`. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Inizializza una nuova istanza della classe `Jpeg2000Options`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getComments()](#getComments--) | Ottiene o imposta i marcatori di commento Jpeg. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Ottiene o imposta i marcatori di commento Jpeg. |
| [getCodec()](#getCodec--) | Ottiene o imposta il codec JPEG2000. |
| [setCodec(int value)](#setCodec-int-) | Ottiene o imposta il codec JPEG2000. |
| [getCompressionRatios()](#getCompressionRatios--) | Ottiene o imposta l'Array di rapporto di compressione. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Ottiene o imposta l'Array di rapporto di compressione. |
| [getIrreversible()](#getIrreversible--) | Ottiene un valore che indica se utilizzare il DWT 9-7 irreversibile (true) o la compressione DWT 5-3 senza perdita (default). |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Imposta un valore che indica se utilizzare il DWT 9-7 irreversibile (true) o la compressione DWT 5-3 senza perdita (default). |

## Example: The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. In realtà, verrà rasterizzata solo una pagina perché JPEG 2000 non è un formato multipagina.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Inizializza una nuova istanza della classe `Jpeg2000Options`.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Inizializza una nuova istanza della classe `Jpeg2000Options`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Le opzioni del formato file Jpeg2000 da cui copiare le impostazioni. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Ottiene o imposta i marcatori di commento Jpeg.

**Returns:**
java.lang.String[] - I marcatori di commento Jpeg.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Ottiene o imposta i marcatori di commento Jpeg.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String[] | I marcatori di commento Jpeg. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Ottiene o imposta il codec JPEG2000.

**Returns:**
int - Il codec JPEG2000
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Ottiene o imposta il codec JPEG2000.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il codec JPEG2000 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Riempire l'intera immagine di rosso.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Utilizza la Discrete Wavelet Transform 9-7 irreversibile
    saveOptions.setIrreversible(true);

    // JP2 è il formato "container" per i codestream JPEG 2000.
    // J2K è dati compressi grezzi, senza un wrapper.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Salva su un file
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Ottiene o imposta l'Array di rapporto di compressione. Rapporti di compressione diversi per i livelli successivi. Il tasso specificato per ciascun livello di qualità è il fattore di compressione desiderato. Sono richiesti rapporti decrescenti.

**Returns:**
int[] - I rapporti di compressione.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Ottiene o imposta l'Array di rapporto di compressione. Rapporti di compressione diversi per i livelli successivi. Il tasso specificato per ciascun livello di qualità è il fattore di compressione desiderato. Sono richiesti rapporti decrescenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | I rapporti di compressione. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Ottiene un valore che indica se utilizzare il DWT 9-7 irreversibile (true) o la compressione DWT 5-3 senza perdita (default).

**Returns:**
boolean - un valore che indica se utilizzi il DWT 9-7 irreversibile (true) o la compressione DWT 5-3 senza perdita
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Imposta un valore che indica se utilizzare il DWT 9-7 irreversibile (true) o la compressione DWT 5-3 senza perdita (default).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se utilizzi il DWT 9-7 irreversibile (true) o la compressione DWT 5-3 senza perdita |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Riempire l'intera immagine di rosso.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Utilizza la Discrete Wavelet Transform 9-7 irreversibile
    saveOptions.setIrreversible(true);

    // JP2 è il formato "container" per i codestream JPEG 2000.
    // J2K è dati compressi grezzi, senza un wrapper.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Salva su un file
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

