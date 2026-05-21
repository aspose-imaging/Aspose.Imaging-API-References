---
title: "Jpeg2000Image"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Manipola in modo efficiente i file immagine JPEG2000 JP2 con la nostra API, supportando una gamma di profondità di bit per pixel e una gestione fluida dei metadati XMP contenenti informazioni essenziali sull'immagine."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

Manipola in modo efficiente i file immagine JPEG2000 (JP2) con la nostra API, supportando una gamma di profondità di bit per pixel e una gestione fluida dei metadati XMP contenenti informazioni essenziali sull'immagine. Con capacità di compressione senza perdita, garantisci una qualità ottimale dell'immagine mantenendo l'integrità del file, consentendoti di personalizzare le immagini JP2 secondo le tue specifiche esatte con facilità.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | Inizia a lavorare con la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) inizializzando una nuova istanza con il percorso dell'immagine che desideri caricare. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | Inizia facilmente con la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) creando una nuova istanza con sia il percorso del file sia il parametro di bit per pixel desiderato. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | Inizializza facilmente una nuova istanza della classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) fornendo un oggetto stream. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | Inizializza una nuova istanza della classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con uno stream per caricare l'immagine, insieme ai parametri di bit per pixel. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | Crea una nuova istanza della classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), specificando i parametri di larghezza e altezza. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Istanzia un nuovo oggetto [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), fornendo i parametri di larghezza, altezza e opzioni immagine. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | Crea una nuova istanza della classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con parametri per larghezza, altezza e conteggio dei bit. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | Istanzia una nuova classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con un'immagine raster. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | Inizializza una nuova istanza di [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con un'immagine raster e parametri di bit per pixel. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupera il formato del file immagine. |
| [getRawDataFormat()](#getRawDataFormat--) | Questa proprietà recupera il formato dei dati grezzi dell'immagine. |
| [getRawLineSize()](#getRawLineSize--) | Questa proprietà recupera la dimensione di una singola riga di dati immagine grezzi in byte. |
| [getWidth()](#getWidth--) | Questa proprietà restituisce la larghezza dell'immagine in pixel. |
| [getHeight()](#getHeight--) | Questa proprietà recupera l'altezza dell'immagine in pixel. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Questa proprietà restituisce la profondità dell'immagine, misurata in bit per pixel (bpp). |
| [getHorizontalResolution()](#getHorizontalResolution--) | Questa proprietà consente di recuperare o modificare la risoluzione orizzontale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice (PPI). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Questa proprietà consente di recuperare o modificare la risoluzione orizzontale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice (PPI). |
| [getVerticalResolution()](#getVerticalResolution--) | Questa proprietà fornisce l'accesso alla risoluzione verticale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice (PPI). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Questa proprietà fornisce l'accesso alla risoluzione verticale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice (PPI). |
| [getComments()](#getComments--) | Questa proprietà consente di recuperare o aggiornare i commenti associati all'immagine. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Questa proprietà consente di recuperare o aggiornare i commenti associati all'immagine. |
| [getCodec()](#getCodec--) | Questa proprietà recupera il codec JPEG2000 associato all'immagine. |
| [getOriginalOptions()](#getOriginalOptions--) | Recupera le opzioni dell'immagine in base alle impostazioni del file originale. |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Carica un'immagine JPEG2000.
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // Salva in PNG
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


Inizia a lavorare con la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) inizializzando una nuova istanza con il percorso dell'immagine che desideri caricare. Questo costruttore consente un facile accesso alle immagini JPEG2000, semplificando il processo di caricamento e gestione dei file immagine. Fornendo il percorso del file, puoi avviare rapidamente l'elaborazione e la manipolazione delle immagini JPEG2000 nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


Inizia facilmente con la classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) creando una nuova istanza con sia il percorso del file sia il parametro dei bit per pixel desiderato. Questo costruttore consente di affinare il processo di caricamento dell'immagine, garantendo la compatibilità con vari formati immagine e impostazioni di qualità. Con questa flessibilità, puoi gestire e manipolare efficacemente le immagini JPEG2000 in base alle tue specifiche esigenze.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette |
| bitsPerPixel | int | I bit per pixel. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


Inizializza facilmente una nuova istanza della classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) fornendo un oggetto stream. Questo costruttore semplifica il processo di caricamento delle immagini JPEG2000 direttamente da stream, offrendo flessibilità e praticità nella gestione dei dati immagine provenienti da varie fonti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


Inizializza una nuova istanza della classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con uno stream per caricare l'immagine, insieme ai parametri dei bit per pixel. Questo costruttore offre flessibilità consentendo di specificare sia la sorgente dei dati immagine sia i bit per pixel desiderati, fornendo un controllo più preciso sul processo di caricamento dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream da cui caricare l'immagine e con cui inizializzare i dati dei pixel e della palette. |
| bitsPerPixel | int | I bit per pixel. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


Crea una nuova istanza della classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), specificando i parametri di larghezza e altezza. Questo costruttore consente di inizializzare un'immagine JPEG2000 con dimensioni specifiche, utile in scenari in cui è necessario creare programmaticamente un'immagine di una certa dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine |
| height | int | L'altezza dell'immagine |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


Istanzia un nuovo oggetto [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), fornendo i parametri di larghezza, altezza e opzioni immagine. Questo costruttore consente la creazione di immagini JPEG2000 con dimensioni specifiche e opzioni aggiuntive, offrendo flessibilità nella generazione delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine |
| height | int | L'altezza dell'immagine |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Le opzioni. |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


Crea una nuova istanza della classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con parametri per larghezza, altezza e conteggio dei bit. Questo costruttore consente la creazione di immagini JPEG2000 con dimensioni specifiche e profondità di bit, fornendo flessibilità per varie esigenze di imaging.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine |
| height | int | L'altezza dell'immagine |
| bitsCount | int | Il conteggio dei bit. |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


Istanzia una nuova classe [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con un'immagine raster. Questo costruttore facilita la creazione di un'immagine JPEG2000 a partire da un'immagine raster esistente, offrendo un'integrazione fluida e la conversione tra diversi formati immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


Inizializza una nuova istanza di [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con un'immagine raster e i parametri di bit per pixel. Questo costruttore consente un controllo preciso sulla qualità e sulle dimensioni dell'immagine JPEG2000 risultante, rendendolo ideale per scenari in cui la personalizzazione è fondamentale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine con cui inizializzare i dati dei pixel e della palette. |
| bitsPerPixel | int | I bit per pixel. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera il formato del file immagine. Questa proprietà fornisce informazioni sul formato del file dell'immagine. Utilizza questa proprietà per determinare programmaticamente il formato del file immagine, facilitando una gestione e un'elaborazione appropriate in base al formato del file.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Questa proprietà recupera il formato dei dati grezzi dell'immagine. Fornisce informazioni su come i dati dei pixel sono memorizzati in memoria. Usa questa proprietà per comprendere il formato dei dati sottostante dell'immagine, il che può essere fondamentale per varie operazioni di elaborazione delle immagini come la conversione dei colori, la compressione o la decompressione.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Questa proprietà recupera la dimensione di una singola riga di dati grezzi dell'immagine in byte. Indica la quantità di memoria occupata da una singola fila di pixel nel formato dei dati grezzi dell'immagine. Comprendere la dimensione della riga grezza è essenziale per attività come l'allocazione della memoria, la manipolazione dei dati e gli algoritmi di elaborazione delle immagini che operano su singole righe dell'immagine.

**Returns:**
int - La dimensione della riga grezza in byte.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Questa proprietà restituisce la larghezza dell'immagine in pixel. Fornisce un'informazione fondamentale sulle dimensioni dell'immagine, cruciale per varie attività di elaborazione delle immagini, inclusi ridimensionamento, ritaglio e rendering.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Questa proprietà recupera l'altezza dell'immagine in pixel. Fornisce informazioni essenziali per comprendere le dimensioni verticali dell'immagine, facilitando varie operazioni di manipolazione come ridimensionamento, ritaglio e rendering. Accedere a questa proprietà consente agli utenti di determinare l'altezza verticale dell'immagine, permettendo una disposizione e una visualizzazione precise nelle applicazioni.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Questa proprietà restituisce la profondità dell'immagine, misurata in bit per pixel (bpp). Indica la quantità di informazioni di colore memorizzate in ogni pixel dell'immagine. Comprendere la profondità dell'immagine è fondamentale per determinare la fedeltà cromatica e la qualità dell'immagine. Con queste informazioni, gli utenti possono valutare il livello di dettaglio e la ricchezza dei colori presenti nell'immagine.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Questa proprietà consente di recuperare o modificare la risoluzione orizzontale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice (PPI). Regolare questa risoluzione può influire sulla dimensione e sulla qualità dell'immagine quando stampata o visualizzata. Impostando la risoluzione orizzontale, gli utenti possono ottimizzare l'immagine per dispositivi di output o applicazioni specifiche, garantendo i migliori risultati visivi possibili.

**Returns:**
double - La risoluzione orizzontale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Ottieni la risoluzione orizzontale e verticale del Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 72.0
// La risoluzione verticale, in pixel per pollice: 72.0
// Imposta i valori di risoluzione a 96 dpi
// La risoluzione orizzontale, in pixel per pollice: 72.0
// La risoluzione verticale, in pixel per pollice: 72.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Questa proprietà consente di recuperare o modificare la risoluzione orizzontale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice (PPI). Regolare questa risoluzione può influire sulla dimensione e sulla qualità dell'immagine quando stampata o visualizzata. Impostando la risoluzione orizzontale, gli utenti possono ottimizzare l'immagine per dispositivi di output o applicazioni specifiche, garantendo i migliori risultati visivi possibili.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione orizzontale. |

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Questa proprietà fornisce l'accesso alla risoluzione verticale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice (PPI). Modificare questa risoluzione può influire sulla qualità e sulla dimensione dell'immagine quando stampata o visualizzata. Regolando la risoluzione verticale, gli utenti possono ottimizzare l'immagine per diversi dispositivi di output o applicazioni, garantendo un rendering visivo ottimale.

**Returns:**
double - La risoluzione verticale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Ottieni la risoluzione orizzontale e verticale del Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// La risoluzione orizzontale, in pixel per pollice: 72.0
// La risoluzione verticale, in pixel per pollice: 72.0
// Imposta i valori di risoluzione a 96 dpi
// La risoluzione orizzontale, in pixel per pollice: 72.0
// La risoluzione verticale, in pixel per pollice: 72.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Questa proprietà fornisce l'accesso alla risoluzione verticale del [RasterImage](../../com.aspose.imaging/rasterimage), misurata in pixel per pollice (PPI). Modificare questa risoluzione può influire sulla qualità e sulla dimensione dell'immagine quando stampata o visualizzata. Regolando la risoluzione verticale, gli utenti possono ottimizzare l'immagine per diversi dispositivi di output o applicazioni, garantendo un rendering visivo ottimale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione verticale. |

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Questa proprietà consente di recuperare o aggiornare i commenti associati all'immagine. I commenti forniscono informazioni aggiuntive sul contenuto dell'immagine, come annotazioni, descrizioni o metadati. Modificare questi commenti può essere utile per organizzare e categorizzare le immagini, nonché per trasmettere dettagli importanti a spettatori o utenti.

**Returns:**
java.lang.String[] - I commenti.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Questa proprietà consente di recuperare o aggiornare i commenti associati all'immagine. I commenti forniscono informazioni aggiuntive sul contenuto dell'immagine, come annotazioni, descrizioni o metadati. Modificare questi commenti può essere utile per organizzare e categorizzare le immagini, nonché per trasmettere dettagli importanti a spettatori o utenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String[] | I commenti. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Questa proprietà recupera il codec JPEG2000 associato all'immagine. Il codec JPEG2000 è responsabile della codifica e decodifica dei dati dell'immagine nel formato JPEG2000, fornendo una compressione efficiente mantenendo alta la qualità dell'immagine. Accedere a questo codec può essere utile per eseguire operazioni avanzate di elaborazione delle immagini o per ottimizzare le impostazioni di compressione dell'immagine su misura per requisiti specifici.

**Returns:**
int - Il codec.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Recupera le opzioni dell'immagine basate sulle impostazioni del file originale. Questo metodo è utile per mantenere la profondità di bit e gli altri parametri dell'immagine originale, garantendo coerenza e preservando l'integrità dei dati dell'immagine. Accedere a queste opzioni facilita una gestione e un'elaborazione fluide dell'immagine mantenendo le sue caratteristiche originali. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e poi la salviamo utilizzando il metodo [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), verrà prodotto un PNG di output con 8 bit per pixel. Per evitare ciò e salvare l'immagine PNG con 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al metodo [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) come secondo parametro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
