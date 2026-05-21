---
title: "PngImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Manipola le immagini raster PNG Portable Network Graphics con la nostra API versatile, che supporta livelli di compressione e varie profondità di colore, inclusi Grayscale, Indexed Color, TrueColor e canali alfa."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

Manipola le immagini raster Portable Network Graphics (PNG) con la nostra API versatile, che supporta livelli di compressione e varie profondità di colore, inclusi Grayscale, Indexed Color, TrueColor e canali alfa. Elabora senza problemi i metadati XMP, consentendo una gestione completa dei metadati delle immagini, mentre carichi facilmente le immagini PNG, esegui diverse manipolazioni, applichi filtri e converta le immagini in altri formati di file per una versatilità e personalizzazione ottimali.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | Inizializza un nuovo oggetto della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) fornendo i parametri di larghezza e altezza. |
| [PngImage(String path)](#PngImage-java.lang.String-) | Costruisce una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) utilizzando il parametro path per specificare la posizione del file immagine da caricare. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | Crea una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) fornendo un'immagine raster come parametro. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | Inizializza una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) specificando il percorso del file immagine e il tipo di colore. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | Crea una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) specificando un'immagine raster e un tipo di colore. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | Crea una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) inizializzandola con uno stream. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | Istanzia una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), specificando i parametri desiderati di larghezza, altezza e tipo di colore. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | Inizializza una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), incorporando le opzioni PNG insieme ai parametri di larghezza e altezza. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera il valore dei bit per pixel dell'immagine. |
| [getHeight()](#getHeight--) | Ottieni l'altezza dell'immagine in pixel. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Recupera o modifica la risoluzione orizzontale dell'immagine. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Recupera o modifica la risoluzione orizzontale dell'immagine. |
| [getFileFormat()](#getFileFormat--) | Recupera il formato del file associato all'istanza dell'immagine. |
| [getRawDataFormat()](#getRawDataFormat--) | Accede al formato dei dati grezzi dell'immagine. |
| [getVerticalResolution()](#getVerticalResolution--) | Fornisce l'accesso alla risoluzione verticale dell'immagine. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Fornisce l'accesso alla risoluzione verticale dell'immagine. |
| [getWidth()](#getWidth--) | Consente di recuperare la larghezza dell'immagine in pixel, fornendo informazioni essenziali sulle sue dimensioni. |
| [hasTransparentColor()](#hasTransparentColor--) | Fornisce un valore booleano che indica se l'immagine contiene un colore trasparente. |
| [hasAlpha()](#hasAlpha--) | Restituisce un valore booleano che indica se l'immagine ha un canale alfa, che determina la sua trasparenza. |
| [getTransparentColor()](#getTransparentColor--) | Recupera il colore trasparente dell'immagine, se esiste. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Fornisce un valore booleano che indica se l'immagine contiene un colore trasparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Modifica il colore trasparente dell'immagine, se esiste. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Recupera un valore booleano che indica se l'immagine ha un colore di sfondo. |
| [getBackgroundColor()](#getBackgroundColor--) | Recupera il colore di sfondo dell'immagine, se è specificato. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Recupera un valore booleano che indica se l'immagine ha un colore di sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Recupera il colore di sfondo dell'immagine, se è specificato. |
| [getInterlaced()](#getInterlaced--) | Recupera un valore booleano che indica se il [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è interlacciato, il che determina se i dati dell'immagine sono memorizzati in modo progressivo per un caricamento o una trasmissione più rapida. |
| [isInterlaced()](#isInterlaced--) | Ottiene un valore che indica se questa istanza di immagine è interlacciata. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Ottiene le opzioni predefinite. |
| [getOriginalOptions()](#getOriginalOptions--) | Ottiene le opzioni basate sulle impostazioni del file originale. |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// Carica un'immagine PNG da un file.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // Trasforma l'immagine in una rappresentazione in scala di grigi
    pngImage.grayscale();

    // Salva su un file.
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


Inizializza un nuovo oggetto della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) fornendo i parametri di larghezza e altezza. Questo costruttore semplifica la creazione di immagini PNG consentendo agli sviluppatori di specificare direttamente le dimensioni, facilitando una gestione efficiente dei dati delle immagini PNG nelle loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza. |
| height | int | L'altezza. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


Costruisce una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) utilizzando il parametro path per specificare la posizione del file immagine da caricare. Questo costruttore consente agli sviluppatori di creare comodamente immagini PNG caricandole da un file, semplificando il processo di utilizzo delle immagini PNG nelle loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso per caricare un'immagine. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


Crea una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) fornendo un'immagine raster come parametro. Questo costruttore permette agli sviluppatori di inizializzare direttamente un oggetto immagine PNG utilizzando un'immagine raster esistente, ottimizzando il processo di utilizzo delle immagini PNG nelle loro applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


Inizializza una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) specificando il percorso del file immagine e il tipo di colore. Questo costruttore consente una creazione comoda di immagini PNG da file con diversi tipi di colore, offrendo flessibilità nella gestione di vari formati di immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso per caricare un'immagine. |
| colorType | int | Il tipo di colore. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


Crea una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) specificando un'immagine raster e un tipo di colore. Questo costruttore consente agli sviluppatori di convertire direttamente le immagini raster in formato PNG specificando il tipo di colore desiderato, offrendo flessibilità nella rappresentazione dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |
| colorType | int | Il tipo di colore. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


Crea una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) inizializzandola con uno stream. Questo costruttore permette agli sviluppatori di caricare immagini PNG direttamente da uno stream, offrendo flessibilità nel recupero delle immagini da diverse fonti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream per caricare un'immagine. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


Istanzia una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), specificando i parametri di larghezza, altezza e tipo di colore desiderati. Questo costruttore consente una rapida creazione di immagini PNG con dimensioni e configurazioni di colore personalizzate, facilitando una generazione di immagini ottimizzata per varie applicazioni e flussi di lavoro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza. |
| height | int | L'altezza. |
| colorType | int | Il tipo di colore. |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


Inizializza una nuova istanza della classe [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), incorporando le opzioni PNG insieme ai parametri di larghezza e altezza. Questo costruttore consente agli sviluppatori di creare immagini PNG con impostazioni e dimensioni personalizzabili, offrendo flessibilità nella generazione di immagini per diversi casi d'uso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Le opzioni png. |
| width | int | La larghezza. |
| height | int | L'altezza. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupera il valore dei bit per pixel dell'immagine. Questa proprietà fornisce informazioni cruciali sulla profondità di colore dell'immagine, consentendo agli sviluppatori di comprendere il livello di dettaglio e la precisione del colore presenti nei dati dell'immagine.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottieni l'altezza dell'immagine in pixel. Questa proprietà restituisce la dimensione verticale dell'immagine, consentendo agli sviluppatori di determinarne la dimensione in pixel lungo l'asse verticale.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Recupera o modifica la risoluzione orizzontale dell'immagine. Questa proprietà rappresenta il numero di pixel per pollice lungo l'asse orizzontale dell'immagine. Modificare questa risoluzione può influire sulla dimensione fisica dell'immagine quando stampata o visualizzata.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Ottieni la risoluzione orizzontale e verticale del PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//L'output potrebbe apparire così:
//La risoluzione orizzontale, in pixel per pollice: 96.0
//La risoluzione verticale, in pixel per pollice: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Recupera o modifica la risoluzione orizzontale dell'immagine. Questa proprietà rappresenta il numero di pixel per pollice lungo l'asse orizzontale dell'immagine. Modificare questa risoluzione può influire sulla dimensione fisica dell'immagine quando stampata o visualizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera il formato del file associato all'istanza dell'immagine. Questa proprietà fornisce informazioni essenziali sul tipo di file, consentendo una gestione e un'elaborazione efficienti in base ai requisiti specifici del formato.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Accede al formato dei dati grezzi dell'immagine. Questa proprietà fornisce indicazioni su come i dati dell'immagine sono strutturati internamente, il che può essere utile per attività avanzate di elaborazione delle immagini o conversione di formato.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// Le immagini PNG da caricare.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// L'output potrebbe apparire così:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Fornisce l'accesso alla risoluzione verticale dell'immagine. Gli sviluppatori possono utilizzare questa proprietà per recuperare o modificare l'impostazione della risoluzione, che indica il numero di pixel per pollice (PPI) lungo l'asse verticale dell'immagine.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Ottieni la risoluzione orizzontale e verticale del PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//L'output potrebbe apparire così:
//La risoluzione orizzontale, in pixel per pollice: 96.0
//La risoluzione verticale, in pixel per pollice: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Fornisce l'accesso alla risoluzione verticale dell'immagine. Gli sviluppatori possono utilizzare questa proprietà per recuperare o modificare l'impostazione della risoluzione, che indica il numero di pixel per pollice (PPI) lungo l'asse verticale dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Consente di recuperare la larghezza dell'immagine in pixel, fornendo informazioni essenziali sulle sue dimensioni. Questa proprietà è frequentemente utilizzata dagli sviluppatori per determinare la larghezza dell'immagine, consentendo loro di eseguire varie operazioni basate sulla sua dimensione.

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Fornisce un valore booleano che indica se l'immagine contiene un colore trasparente. Questa proprietà è fondamentale per le applicazioni che devono gestire la trasparenza, consentendo agli sviluppatori di determinare se è necessario un ulteriore elaborazione per gestire le regioni trasparenti nell'immagine.

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Restituisce un valore booleano che indica se l'immagine ha un canale alfa, il quale determina la sua trasparenza. Questa proprietà è utile per le applicazioni che devono gestire la trasparenza, consentendo agli sviluppatori di determinare se è necessario un ulteriore elaborazione per gestire le aree trasparenti nell'immagine.

**Returns:**
boolean - `true` se questa istanza ha alfa; altrimenti, `false`.

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// Classe di supporto
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// Ecco l'esempio principale
Utils utils = new Utils();

// Ottieni tutti i tipi di colore PNG supportati.
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// L'output appare così:
// Un'immagine PNG in scala di grigi non supporta il canale alfa
// Un'immagine PNG Truecolor non supporta il canale alfa
// Un'immagine PNG IndexedColor non supporta il canale alfa
// Un'immagine PNG GrayscaleWithAlpha supporta il canale alfa
// Un'immagine PNG TruecolorWithAlpha supporta il canale alfa
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Recupera il colore trasparente dell'immagine, se presente. Questa proprietà è preziosa per le applicazioni che richiedono una gestione precisa delle aree trasparenti all'interno delle immagini, consentendo agli sviluppatori di accedere e manipolare il colore trasparente specifico utilizzato.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Fornisce un valore booleano che indica se l'immagine contiene un colore trasparente. Questa proprietà è fondamentale per le applicazioni che devono gestire la trasparenza, consentendo agli sviluppatori di determinare se è necessario un ulteriore elaborazione per gestire le regioni trasparenti nell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Crea un'immagine PNG TrueColor di 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tutti i pixel rossi saranno considerati completamente trasparenti.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tutti i pixel trasparenti avranno un colore di sfondo.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Riempie l'intera immagine con colore bianco.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Riempie il quarto in alto a sinistra dell'immagine con il colore trasparente.
    // Questo rende il quarto in alto a sinistra colorato con il colore di sfondo.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Modifica il colore trasparente dell'immagine, se presente. Questa proprietà è preziosa per le applicazioni che richiedono una gestione precisa delle aree trasparenti all'interno delle immagini, consentendo agli sviluppatori di accedere e manipolare il colore trasparente specifico utilizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Crea un'immagine PNG TrueColor di 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tutti i pixel rossi saranno considerati completamente trasparenti.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tutti i pixel trasparenti avranno un colore di sfondo.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Riempie l'intera immagine con colore bianco.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Riempie il quarto in alto a sinistra dell'immagine con il colore trasparente.
    // Questo rende il quarto in alto a sinistra colorato con il colore di sfondo.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Recupera un valore booleano che indica se l'immagine ha un colore di sfondo. Questa proprietà è utile per le applicazioni che necessitano di determinare se un'immagine include un colore di sfondo, il che può essere importante per vari compiti di elaborazione come compositing, rendering o esportazione.

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Recupera il colore di sfondo dell'immagine, se specificato. Questa proprietà è utile per le applicazioni che devono identificare e potenzialmente manipolare il colore di sfondo di un'immagine.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Recupera un valore booleano che indica se l'immagine ha un colore di sfondo. Questa proprietà è utile per le applicazioni che necessitano di determinare se un'immagine include un colore di sfondo, il che può essere importante per vari compiti di elaborazione come compositing, rendering o esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Crea un'immagine PNG TrueColor di 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tutti i pixel rossi saranno considerati completamente trasparenti.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tutti i pixel trasparenti avranno un colore di sfondo.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Riempie l'intera immagine con colore bianco.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Riempie il quarto in alto a sinistra dell'immagine con il colore trasparente.
    // Questo rende il quarto in alto a sinistra colorato con il colore di sfondo.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Recupera il colore di sfondo dell'immagine, se specificato. Questa proprietà è utile per le applicazioni che devono identificare e potenzialmente manipolare il colore di sfondo di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Crea un'immagine PNG TrueColor di 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tutti i pixel rossi saranno considerati completamente trasparenti.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tutti i pixel trasparenti avranno un colore di sfondo.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Riempie l'intera immagine con colore bianco.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Riempie il quarto in alto a sinistra dell'immagine con il colore trasparente.
    // Questo rende il quarto in alto a sinistra colorato con il colore di sfondo.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Recupera un valore booleano che indica se il [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è interlacciato, il che determina se i dati dell'immagine sono memorizzati in modo progressivo per un caricamento o una trasmissione più rapida.

**Returns:**
boolean - `true` se interlacciato; altrimenti, `false`.
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


Ottiene un valore che indica se questa istanza di immagine è interlacciata.

Valore: `true` se questa istanza di immagine è interlacciata; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questa istanza di immagine è interlacciata.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Ottiene le opzioni predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | java.lang.Object[] | Gli argomenti. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ottiene le opzioni basate sulle impostazioni del file originale. Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e poi la salviamo usando il metodo `DataStreamSupporter.Save(string)`, verrà prodotta un'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al metodo `Image.Save(string, ImageOptionsBase)` come secondo parametro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
