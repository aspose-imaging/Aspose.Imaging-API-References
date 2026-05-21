---
title: "GifOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per la creazione di file immagine raster GIF (Graphics Interchange Format) offre agli sviluppatori opzioni complete per generare immagini GIF con controllo preciso."
type: docs
weight: 22
url: /it/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

L'API per la creazione di file immagine raster Graphical Interchange Format (GIF) offre agli sviluppatori opzioni complete per generare immagini GIF con controllo preciso. Con funzionalità per impostare il colore di sfondo, la tavolozza dei colori, la risoluzione, il tipo interlacciato, il colore trasparente, il contenitore di metadati XMP e la compressione dell'immagine, questa API garantisce flessibilità ed efficienza nella creazione di GIF ottimizzate e visivamente accattivanti, adattate a requisiti applicativi specifici.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inizializza una nuova istanza della classe `GifOptions`. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | Inizializza una nuova istanza della classe `GifOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Ottiene o imposta un valore che indica se la correzione della tavolozza è applicata. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Ottiene o imposta un valore che indica se la correzione della tavolozza è applicata. |
| [getLoopsCount()](#getLoopsCount--) | Ottiene il conteggio dei cicli (Predefinito 1 ciclo) |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Imposta il conteggio dei cicli (Predefinito 1 ciclo) |
| [getColorResolution()](#getColorResolution--) | Ottiene o imposta la risoluzione colore GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Ottiene o imposta la risoluzione colore GIF. |
| [isPaletteSorted()](#isPaletteSorted--) | Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Ottiene o imposta il rapporto d'aspetto dei pixel GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Ottiene o imposta il rapporto d'aspetto dei pixel GIF. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Ottiene o imposta l'indice del colore di sfondo GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Ottiene o imposta l'indice del colore di sfondo GIF. |
| [hasTrailer()](#hasTrailer--) | Ottiene o imposta un valore che indica se il GIF ha un trailer. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Ottiene o imposta un valore che indica se il GIF ha un trailer. |
| [getInterlaced()](#getInterlaced--) | Vero se l'immagine deve essere interlacciata. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Vero se l'immagine deve essere interlacciata. |
| [getMaxDiff()](#getMaxDiff--) | Ottiene o imposta la differenza massima consentita tra i pixel. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Ottiene o imposta la differenza massima consentita tra i pixel. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene il colore di sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Imposta il colore di sfondo. |
| [hasTransparentColor()](#hasTransparentColor--) | Ottiene un valore che indica se un'immagine GIF ha colore trasparente. |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | Imposta un valore che indica se un'immagine GIF ha colore trasparente. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Questo esempio dimostra l'uso di diverse classi dal namespace SaveOptions per scopi di esportazione. Un'immagine di tipo Gif viene caricata in un'istanza di Image e poi esportata in diversi formati.
``` java
String dir = "c:\\temp\\";

//Carica un'immagine esistente (di tipo Gif) in un'istanza della classe Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Esporta nel formato file BMP utilizzando le opzioni predefinite
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Esporta nel formato file JPEG utilizzando le opzioni predefinite
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Esporta nel formato file PNG utilizzando le opzioni predefinite
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Esporta nel formato file TIFF utilizzando le opzioni predefinite
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. Queste pagine saranno presentate come fotogrammi animati nel GIF di output.
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

### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Inizializza una nuova istanza della classe `GifOptions`.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Inizializza una nuova istanza della classe `GifOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | Le opzioni GIF. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Ottiene o imposta un valore che indica se la correzione della tavolozza è applicata.

**Returns:**
boolean - `true` se la correzione della palette è applicata; altrimenti, `false`.

La correzione della palette significa che, ogni volta che un'immagine viene esportata in GIF, i colori dell'immagine sorgente verranno analizzati per creare la palette più adatta (nel caso in cui la Palette dell'immagine non esista o non sia specificata nelle opzioni). Il processo di analisi richiede del tempo, tuttavia l'immagine di output avrà la palette di colori più adatta e il risultato sarà visivamente migliore.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Ottiene o imposta un valore che indica se la correzione della tavolozza è applicata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | `true` se la correzione della palette è applicata; altrimenti, `false`. |

La correzione della palette significa che, ogni volta che un'immagine viene esportata in GIF, i colori dell'immagine sorgente verranno analizzati per creare la palette più adatta (nel caso in cui la Palette dell'immagine non esista o non sia specificata nelle opzioni). Il processo di analisi richiede del tempo, tuttavia l'immagine di output avrà la palette di colori più adatta e il risultato sarà visivamente migliore. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Riempie l'intera immagine con il gradiente blu-giallo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Il numero di bit richiesti per memorizzare un colore, meno 1.
    saveOptions.setColorResolution((byte) 7);

    // La correzione della palette significa che, ogni volta che un'immagine viene esportata in GIF, i colori dell'immagine sorgente verranno analizzati
    // per creare la palette più adatta (nel caso in cui la Palette dell'immagine non esista o non sia specificata nelle opzioni)
    saveOptions.setDoPaletteCorrection(true);

    // Carica un'immagine GIF in modo progressivo.
    // Un GIF interlacciato non visualizza le sue linee di scansione linearmente dall'alto verso il basso, ma le riordina
    // così il contenuto del GIF diventa chiaro anche prima che il caricamento sia completato.
    saveOptions.setInterlaced(true);

    // Salva come GIF senza perdita.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Imposta la differenza massima consentita tra i pixel. Se maggiore di zero, verrà utilizzata la compressione con perdita.
    // Il valore consigliato per una compressione con perdita ottimale è 80. 30 è una compressione molto leggera, 200 è pesante.
    saveOptions.setMaxDiff(80);

    // Salva come GIF con perdita.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//L'output potrebbe apparire così:
//La dimensione del GIF senza perdita: 212816 byte.
//La dimensione del GIF con perdita: 89726 byte.
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


Ottiene il conteggio dei cicli (Predefinito 1 ciclo)

Valore: Il conteggio dei cicli.

**Returns:**
int - il conteggio dei cicli (Predefinito 1 ciclo)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


Imposta il conteggio dei cicli (Predefinito 1 ciclo)

Valore: Il conteggio dei cicli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il conteggio dei cicli (Predefinito 1 ciclo) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Ottiene o imposta la risoluzione colore GIF.

**Returns:**
byte - La risoluzione del colore.

Risoluzione colore - Numero di bit per colore primario disponibili nell'immagine originale, meno 1. Questo valore rappresenta la dimensione dell'intera tavolozza da cui sono stati selezionati i colori nella grafica, non il numero di colori effettivamente usati nella grafica. Ad esempio, se il valore in questo campo è 3, allora la tavolozza dell'immagine originale aveva 4 bit per colore primario disponibili per creare l'immagine. Questo valore dovrebbe essere impostato per indicare la ricchezza della tavolozza originale, anche se non tutti i colori dell'intera tavolozza sono disponibili sulla macchina di origine.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Ottiene o imposta la risoluzione colore GIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte | La risoluzione colore. |

Risoluzione colore - Numero di bit per colore primario disponibili nell'immagine originale, meno 1. Questo valore rappresenta la dimensione dell'intera tavolozza da cui sono stati selezionati i colori nella grafica, non il numero di colori effettivamente usati nella grafica. Ad esempio, se il valore in questo campo è 3, allora la tavolozza dell'immagine originale aveva 4 bit per colore primario disponibili per creare l'immagine. Questo valore dovrebbe essere impostato per indicare la ricchezza della tavolozza originale, anche se non tutti i colori dell'intera tavolozza sono disponibili sulla macchina di origine. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Riempie l'intera immagine con il gradiente blu-giallo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Il numero di bit richiesti per memorizzare un colore, meno 1.
    saveOptions.setColorResolution((byte) 7);

    // La correzione della palette significa che, ogni volta che un'immagine viene esportata in GIF, i colori dell'immagine sorgente verranno analizzati
    // per creare la palette più adatta (nel caso in cui la Palette dell'immagine non esista o non sia specificata nelle opzioni)
    saveOptions.setDoPaletteCorrection(true);

    // Carica un'immagine GIF in modo progressivo.
    // Un GIF interlacciato non visualizza le sue linee di scansione linearmente dall'alto verso il basso, ma le riordina
    // così il contenuto del GIF diventa chiaro anche prima che il caricamento sia completato.
    saveOptions.setInterlaced(true);

    // Salva come GIF senza perdita.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Imposta la differenza massima consentita tra i pixel. Se maggiore di zero, verrà utilizzata la compressione con perdita.
    // Il valore consigliato per una compressione con perdita ottimale è 80. 30 è una compressione molto leggera, 200 è pesante.
    saveOptions.setMaxDiff(80);

    // Salva come GIF con perdita.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//L'output potrebbe apparire così:
//La dimensione del GIF senza perdita: 212816 byte.
//La dimensione del GIF con perdita: 89726 byte.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate.

**Returns:**
boolean - `true` se le voci della tavolozza sono ordinate; altrimenti, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se le voci della tavolozza sono ordinate; altrimenti, `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Ottiene o imposta il rapporto d'aspetto dei pixel GIF.

Pixel Aspect Ratio - Fattore usato per calcolare un'approssimazione del rapporto d'aspetto del pixel nell'immagine originale. Se il valore del campo non è 0, questa approssimazione del rapporto d'aspetto è calcolata in base alla formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Il Pixel Aspect Ratio è definito come il quoziente tra la larghezza del pixel e la sua altezza. L'intervallo di valori in questo campo consente di specificare il pixel più largo da 4:1 al pixel più alto da 1:4 in incrementi di 1/64. Valori: 0 - Nessuna informazione sul rapporto d'aspetto fornita. 1..255 - Valore usato nel calcolo.

**Returns:**
byte - Il rapporto d'aspetto del pixel GIF.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Ottiene o imposta il rapporto d'aspetto dei pixel GIF.

Pixel Aspect Ratio - Fattore usato per calcolare un'approssimazione del rapporto d'aspetto del pixel nell'immagine originale. Se il valore del campo non è 0, questa approssimazione del rapporto d'aspetto è calcolata in base alla formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Il Pixel Aspect Ratio è definito come il quoziente tra la larghezza del pixel e la sua altezza. L'intervallo di valori in questo campo consente di specificare il pixel più largo da 4:1 al pixel più alto da 1:4 in incrementi di 1/64. Valori: 0 - Nessuna informazione sul rapporto d'aspetto fornita. 1..255 - Valore usato nel calcolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | Il rapporto d'aspetto del pixel GIF. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Ottiene o imposta l'indice del colore di sfondo GIF.

**Returns:**
byte - L'indice del colore di sfondo GIF.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Ottiene o imposta l'indice del colore di sfondo GIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | L'indice del colore di sfondo GIF. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Ottiene o imposta un valore che indica se il GIF ha un trailer.

**Returns:**
boolean - `true` se il GIF ha trailer; altrimenti, `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Ottiene o imposta un valore che indica se il GIF ha un trailer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se il GIF ha trailer; altrimenti, `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Vero se l'immagine deve essere interlacciata.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Vero se l'immagine deve essere interlacciata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Riempie l'intera immagine con il gradiente blu-giallo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Il numero di bit richiesti per memorizzare un colore, meno 1.
    saveOptions.setColorResolution((byte) 7);

    // La correzione della palette significa che, ogni volta che un'immagine viene esportata in GIF, i colori dell'immagine sorgente verranno analizzati
    // per creare la palette più adatta (nel caso in cui la Palette dell'immagine non esista o non sia specificata nelle opzioni)
    saveOptions.setDoPaletteCorrection(true);

    // Carica un'immagine GIF in modo progressivo.
    // Un GIF interlacciato non visualizza le sue linee di scansione linearmente dall'alto verso il basso, ma le riordina
    // così il contenuto del GIF diventa chiaro anche prima che il caricamento sia completato.
    saveOptions.setInterlaced(true);

    // Salva come GIF senza perdita.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Imposta la differenza massima consentita tra i pixel. Se maggiore di zero, verrà utilizzata la compressione con perdita.
    // Il valore consigliato per una compressione con perdita ottimale è 80. 30 è una compressione molto leggera, 200 è pesante.
    saveOptions.setMaxDiff(80);

    // Salva come GIF con perdita.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//L'output potrebbe apparire così:
//La dimensione del GIF senza perdita: 212816 byte.
//La dimensione del GIF con perdita: 89726 byte.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Ottiene o imposta la differenza massima consentita tra pixel. Se maggiore di zero, verrà utilizzata la compressione con perdita. Il valore consigliato per una compressione con perdita ottimale è 80. 30 corrisponde a una compressione molto leggera, 200 è intensa. Funziona al meglio quando viene introdotta solo una piccola perdita, e a causa delle limitazioni dell'algoritmo di compressione livelli di perdita molto alti non offrono tanto guadagno. L'intervallo di valori consentiti è [0, 1000].

**Returns:**
int - L'intervallo di valori consentiti.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Ottiene o imposta la differenza massima consentita tra pixel. Se maggiore di zero, verrà utilizzata la compressione con perdita. Il valore consigliato per una compressione con perdita ottimale è 80. 30 corrisponde a una compressione molto leggera, 200 è intensa. Funziona al meglio quando viene introdotta solo una piccola perdita, e a causa delle limitazioni dell'algoritmo di compressione livelli di perdita molto alti non offrono tanto guadagno. L'intervallo di valori consentiti è [0, 1000].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'intervallo di valori consentiti. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Riempie l'intera immagine con il gradiente blu-giallo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Il numero di bit richiesti per memorizzare un colore, meno 1.
    saveOptions.setColorResolution((byte) 7);

    // La correzione della palette significa che, ogni volta che un'immagine viene esportata in GIF, i colori dell'immagine sorgente verranno analizzati
    // per creare la palette più adatta (nel caso in cui la Palette dell'immagine non esista o non sia specificata nelle opzioni)
    saveOptions.setDoPaletteCorrection(true);

    // Carica un'immagine GIF in modo progressivo.
    // Un GIF interlacciato non visualizza le sue linee di scansione linearmente dall'alto verso il basso, ma le riordina
    // così il contenuto del GIF diventa chiaro anche prima che il caricamento sia completato.
    saveOptions.setInterlaced(true);

    // Salva come GIF senza perdita.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Imposta la differenza massima consentita tra i pixel. Se maggiore di zero, verrà utilizzata la compressione con perdita.
    // Il valore consigliato per una compressione con perdita ottimale è 80. 30 è una compressione molto leggera, 200 è pesante.
    saveOptions.setMaxDiff(80);

    // Salva come GIF con perdita.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//L'output potrebbe apparire così:
//La dimensione del GIF senza perdita: 212816 byte.
//La dimensione del GIF con perdita: 89726 byte.
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Ottiene il colore di sfondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


Imposta il colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | il colore di sfondo. |

### hasTransparentColor() {#hasTransparentColor--}
```
public final Boolean hasTransparentColor()
```


Ottiene un valore che indica se un'immagine GIF ha un colore trasparente. Se il valore restituito è `null`, questa proprietà è sovrascritta dal contesto dell'immagine di origine.

**Returns:**
java.lang.Boolean - un valore che indica se un'immagine GIF ha un colore trasparente.
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


Imposta un valore che indica se un'immagine GIF ha un colore trasparente. Se il valore restituito è `null`, questa proprietà è sovrascritta dal contesto dell'immagine di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Boolean | un valore che indica se un'immagine GIF ha un colore trasparente. |

