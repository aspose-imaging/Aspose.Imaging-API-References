---
title: "WebPImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Manipola le immagini raster WebP con la nostra API utilizzando le sue funzionalità moderne per la compressione sia senza perdita che con perdita, garantendo una qualità ottimale dell'immagine con dimensioni di file ridotte."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Manipola le immagini raster WebP con la nostra API, utilizzando le sue funzionalità moderne per la compressione sia senza perdita che con perdita, garantendo una qualità ottimale dell'immagine con dimensioni di file ridotte. Gestisci senza problemi formati di file estesi, animazioni e canali alfa, aggiornando facilmente le dimensioni, ridimensionando proporzionalmente, ritagliando, ruotando, applicando filtri, regolando i parametri dell'immagine e convertendo in altri formati per un'ottimizzazione versatile delle immagini web.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | Istanzia una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inizializzata da una sorgente stream fornita. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Crea una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) utilizzando uno stream e le opzioni di caricamento specificate, facilitando una gestione versatile dei dati immagine WebP. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | Istanzia una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inizializzata da una sorgente file fornita. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | Crea una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) utilizzando un file e le opzioni di caricamento specificate, facilitando una gestione flessibile dei dati immagine WebP. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | Istanzia una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inizializzata da un oggetto rasterImage fornito. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | Crea una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) utilizzando un oggetto rasterImage e le opzioni di caricamento specificate, consentendo una gestione flessibile dei dati immagine. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | Istanzia una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) con un'immagine vuota di dimensioni larghezza e altezza specificate. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | Crea una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) con un'immagine vuota e le opzioni di caricamento specificate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOptions()](#getOptions--) | Recupera o modifica le opzioni associate alla proprietà specificata, consentendo una personalizzazione fine del comportamento e delle impostazioni. |
| [getPages()](#getPages--) | Accedi ai blocchi WebP all'interno dell'immagine, consentendo un esame dettagliato o la manipolazione della struttura di blocchi sottostante. |
| [getPageCount()](#getPageCount--) | Recupera il conteggio totale delle pagine nel documento specificato, facilitando una navigazione efficiente e la gestione di contenuti multipagina. |
| [getFileFormat()](#getFileFormat--) | Accedi al valore del formato file associato all'immagine, fornendo informazioni sul formato in cui l'immagine è memorizzata. |
| [hasAlpha()](#hasAlpha--) | Recupera se l'immagine contiene un canale alfa, indicando la presenza di informazioni sulla trasparenza. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Aggiungi una nuova pagina all'immagine, espandendo il suo contenuto e accogliendo elementi visivi aggiuntivi. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Incorpora un nuovo blocco WebP nell'immagine, arricchendo il suo contenuto e facilitando una manipolazione avanzata dell'immagine. |
| [clearBlocks()](#clearBlocks--) | Cancella tutti i blocchi WebP esistenti dall'immagine, facilitando una base pulita per modifiche o aggiunte successive. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | Inserisci un nuovo blocco WebP all'indice specificato all'interno dell'immagine, consentendo un controllo preciso sulla sequenza dei blocchi. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Rimuovi il blocco WebP specificato dall'immagine, facilitando una gestione efficiente della struttura dei dati dell'immagine. |
| [getOriginalOptions()](#getOriginalOptions--) | Ottiene le opzioni basate sulle impostazioni del file originale. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Ruota l'immagine attorno al suo centro di un angolo specificato, ridimensionandola proporzionalmente e applicando i parametri di colore di sfondo specificati. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ridimensiona l'immagine, regolando le sue dimensioni mantenendo il rapporto d'aspetto. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Regola proporzionalmente la larghezza dell'immagine mantenendo il suo rapporto d'aspetto. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Regola proporzionalmente l'altezza dell'immagine, mantenendo il suo rapporto d'aspetto per un ridimensionamento coerente. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Applica rotazione, ribaltamento o entrambe le operazioni esclusivamente al fotogramma attivo all'interno dell'immagine. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Esegui il dithering sull'immagine corrente per ridurre le bande di colore e migliorare la qualità visiva. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Ritaglia l'immagine usando una regione rettangolare specificata, rimuovendo le parti indesiderate mantenendo il contenuto desiderato. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Ritaglia l'immagine applicando spostamenti a sinistra, destra, in alto e in basso, selezionando efficacemente una regione di interesse all'interno dell'immagine. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Esegui la binarizzazione dell'immagine utilizzando un valore di soglia predefinito, convertendola in un'immagine binaria in cui i pixel sono classificati come primo piano o sfondo in base alla loro intensità rispetto alla soglia. |
| [binarizeOtsu()](#binarizeOtsu--) | Esegui la binarizzazione dell'immagine usando il metodo di sogliatura di Otsu, determinando automaticamente il valore di soglia ottimale in base all'istogramma dell'immagine. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Applica la binarizzazione all'immagine utilizzando l'algoritmo di sogliatura adattiva di Bradley con sogliatura dell'immagine integrale. |
| [grayscale()](#grayscale--) | Applica la binarizzazione all'immagine utilizzando l'algoritmo di sogliatura adattiva di Bradley con sogliatura dell'immagine integrale. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Applica la correzione gamma all'immagine, regolando le intensità dei pixel per ottenere la luminosità e il bilanciamento dei colori desiderati. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Esegui la correzione gamma sull'immagine usando coefficienti individuali per i canali rosso, verde e blu, consentendo regolazioni precise del bilanciamento dei colori e del contrasto. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implementa la regolazione della `brightness` per l'immagine, consentendo la modifica dei livelli di luminanza complessiva. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Migliora il contrasto del [Image](../../com.aspose.imaging/image), amplificando le differenze tra le aree chiare e scure. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtra il contenuto all'interno del rettangolo specificato, applicando un filtro di elaborazione immagini designato per migliorare o modificare la regione selezionata. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ridimensiona l'immagine secondo le impostazioni specificate, consentendo un controllo preciso su dimensioni, rapporto d'aspetto e comportamento di scaling. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Carica un'immagine WebP da un file.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // Salva in PNG
    // Nota che solo il frame attivo verrà salvato in PNG, poiché PNG non è un formato multipagina.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


Istanzia una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inizializzata da una sorgente stream fornita. Utilizza questo costruttore per creare senza soluzione di continuità oggetti immagine WebP direttamente dallo stream, consentendo una gestione efficiente e la manipolazione dei dati immagine WebP all'interno della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | L'immagine WebP dello stream. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


Crea una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) utilizzando uno stream e le opzioni di caricamento specificate, facilitando una gestione versatile dei dati immagine WebP. Integra questo costruttore per inizializzare senza soluzione di continuità oggetti immagine WebP dallo stream personalizzando i parametri di caricamento secondo le necessità della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | L'immagine WebP dello stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


Istanzia una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inizializzata da una sorgente file fornita. Utilizza questo costruttore per creare senza soluzione di continuità oggetti immagine WebP direttamente dai file, semplificando il processo di caricamento e manipolazione dei dati immagine WebP nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso al file WebP Image |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


Crea una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) utilizzando un file e le opzioni di caricamento specificate, facilitando una gestione flessibile dei dati immagine WebP. Utilizza questo costruttore per inizializzare senza soluzione di continuità oggetti immagine WebP dai file personalizzando i parametri di caricamento in base ai requisiti della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso al file WebP Image |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


Istanzia una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inizializzata da un oggetto rasterImage fornito. Questo costruttore consente una conversione senza soluzione di continuità delle immagini raster in formato WebP, permettendo una gestione efficiente e la manipolazione dei dati immagine nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


Crea una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) utilizzando un oggetto rasterImage e le opzioni di caricamento specificate, consentendo una gestione flessibile dei dati immagine. Utilizza questo costruttore per inizializzare senza soluzione di continuità oggetti immagine WebP da immagini raster personalizzando i parametri di caricamento in base ai requisiti della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


Istanzia una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) con un'immagine vuota di larghezza e altezza specificate. Questo costruttore consente la creazione di immagini WebP vuote, fornendo una base per successive manipolazioni dell'immagine e generazione di contenuti nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine |
| height | int | L'altezza dell'immagine. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Le opzioni. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


Crea una nuova istanza della classe [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) con un'immagine vuota e le opzioni di caricamento specificate. Questo costruttore consente l'inizializzazione di immagini WebP con parametri di caricamento personalizzabili, offrendo flessibilità nella creazione e manipolazione delle immagini nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine |
| height | int | L'altezza dell'immagine. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Le opzioni. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


Recupera o modifica le opzioni associate alla proprietà specificata, consentendo una personalizzazione fine del comportamento e delle impostazioni. Utilizza questa proprietà per accedere e manipolare senza soluzione di continuità i parametri configurabili, facilitando un controllo versatile e l'ottimizzazione all'interno della funzionalità della tua applicazione.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accedi ai blocchi WebP all'interno dell'immagine, consentendo un esame dettagliato o la manipolazione della struttura dei blocchi sottostante. Utilizza questa proprietà per analizzare o modificare i singoli blocchi nei dati immagine WebP, facilitando tecniche avanzate di elaborazione delle immagini nella tua applicazione.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupera il conteggio totale delle pagine all'interno del documento specificato, facilitando una navigazione efficiente e la gestione di contenuti multipagina. Integra questa funzionalità per migliorare l'esperienza dell'utente, consentendo un accesso fluido a strutture documentali complete.

**Returns:**
int - il conteggio delle pagine.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accedi al valore del formato file associato all'immagine, fornendo informazioni sul formato in cui l'immagine è memorizzata. Utilizza questa proprietà per determinare il formato file dell'immagine, facilitando i controlli di compatibilità e l'elaborazione specifica del formato nella tua applicazione.

**Returns:**
long - un valore del formato file
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Recupera se l'immagine contiene un canale alfa, indicando la presenza di informazioni sulla trasparenza. Utilizza questa proprietà per determinare se l'immagine include la trasparenza, consentendo una gestione e un'elaborazione appropriate delle operazioni correlate all'alfa nella tua applicazione.

**Returns:**
boolean - `true` se è presente un canale alfa.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Se il frame TIFF attivo ha un canale alfa, allora l'intera immagine TIFF è considerata dotata di canale alfa.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, canali utilizzati: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, canali utilizzati: 1, HasAlpha=False
```

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Aggiungi una nuova pagina all'immagine, espandendo il suo contenuto e accogliendo elementi visivi aggiuntivi. Integra questo metodo per facilitare la gestione dinamica delle pagine nella tua applicazione, consentendo la creazione e l'ampliamento senza soluzione di continuità di documenti o immagini multipagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La pagina da aggiungere. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


Incorpora un nuovo blocco WebP nell'immagine, arricchendo il suo contenuto e facilitando la manipolazione avanzata delle immagini. Integra questo metodo per migliorare dinamicamente la struttura e la complessità dei dati immagine WebP nella tua applicazione, consentendo un controllo preciso e l'ottimizzazione del rendering delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Il blocco Webp da aggiungere. |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// Il fotogramma predefinito più 36 + 36 fotogrammi aggiuntivi.
createOptions.setAnimLoopCount(36 + 36 + 1);

// Crea un'immagine WebP di 100x100 px.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // Il primo cerchio è rosso
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Il secondo cerchio è nero
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Aumenta gradualmente l'angolo della forma ad arco rossa.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // Aumenta gradualmente l'angolo dell'arco nero e cancella l'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // Salva in un file WebP
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Cancella tutti i blocchi WebP esistenti dall'immagine, facilitando una base pulita per modifiche o aggiunte successive. Utilizza questo metodo per ripristinare efficacemente la struttura dei blocchi nei dati immagine WebP, garantendo una gestione e un'organizzazione ottimali del contenuto dell'immagine nella tua applicazione.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


Inserisci un nuovo blocco WebP all'indice specificato nell'immagine, consentendo un controllo preciso sulla sequenza dei blocchi. Integra questo metodo per incorporare senza soluzione di continuità blocchi WebP aggiuntivi nella struttura dei dati dell'immagine, facilitando l'elaborazione avanzata delle immagini e l'ottimizzazione nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'elemento indicizzato da zero, al quale verrà inserito `block`. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Il blocco Webp da aggiungere. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


Rimuovi il blocco WebP specificato dall'immagine, facilitando una gestione efficiente della struttura dei dati immagine. Utilizza questo metodo per semplificare i flussi di lavoro di elaborazione delle immagini eliminando blocchi o componenti non necessari nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Il blocco da rimuovere. |

--------------------

Nota: non dimenticare di chiamare Dispose su `block` se non lo aggiungerai a qualche altro WebPImage. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere inalterata la profondità di colore e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il metodo [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), verrà prodotta un'immagine PNG di output a 8 bit per pixel. Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al metodo [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) come secondo parametro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Ruota l'immagine attorno al suo centro di un angolo specificato, ridimensionandola proporzionalmente e applicando i parametri di colore di sfondo specificati. Incorpora questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per ottenere trasformazioni precise con colori di sfondo personalizzabili, garantendo una presentazione visiva ottimale nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | boolean | Se impostato su `true` la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ridimensiona l'immagine, regolando le sue dimensioni mantenendo il rapporto d'aspetto. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per scalare dinamicamente le immagini in modo da soddisfare vari requisiti di visualizzazione o archiviazione nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Riduci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Regola proporzionalmente la larghezza dell'immagine mantenendo il suo rapporto d'aspetto. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per ridimensionare dinamicamente le immagini con proporzioni coerenti, garantendo una visualizzazione o archiviazione ottimale nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| resizeType | int | Tipo di ridimensionamento. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Regola proporzionalmente l'altezza dell'immagine, mantenendo il suo rapporto d'aspetto per un ridimensionamento coerente. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per ridimensionare dinamicamente le immagini con proporzioni uniformi, garantendo una visualizzazione o archiviazione ottimale nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | int | La nuova altezza. |
| resizeType | int | Tipo di ridimensionamento. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Applica rotazione, capovolgimento o entrambe le operazioni esclusivamente al fotogramma attivo nell'immagine. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per ottenere una manipolazione precisa dei fotogrammi individuali, migliorando la flessibilità e il controllo sulle trasformazioni dei fotogrammi nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Il tipo di rotazione e capovolgimento. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Esegui il dithering sull'immagine corrente per ridurre le bande di colore e migliorare la qualità visiva. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per ottenere transizioni più fluide tra i colori e migliorare l'aspetto complessivo dell'immagine nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personalizzata per il dithering. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Ritaglia l'immagine usando una regione rettangolare specificata, rimuovendo le parti indesiderate mantenendo il contenuto desiderato. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per estrarre con precisione e focalizzare aree di interesse specifiche all'interno dell'immagine, migliorando chiarezza e composizione per varie applicazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Ritaglia l'immagine applicando spostamenti a sinistra, destra, alto e basso, selezionando efficacemente una regione di interesse nell'immagine. Utilizza questo metodo per estrarre dinamicamente le parti desiderate dell'immagine regolando la sua composizione e messa a fuoco secondo i requisiti della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftShift | int | Lo spostamento sinistro. |
| rightShift | int | Lo spostamento destro. |
| topShift | int | Lo spostamento superiore. |
| bottomShift | int | Lo spostamento inferiore. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Esegui la binarizzazione sull'immagine usando un valore di soglia predefinito, convertendola in un'immagine binaria in cui i pixel sono classificati come primo piano o sfondo in base alla loro intensità rispetto alla soglia. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per facilitare le attività di segmentazione e estrazione delle caratteristiche, migliorando l'accuratezza e l'efficienza dell'analisi successiva nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, gli verrà assegnato il valore (byte)255, altrimenti 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Esegui la binarizzazione dell'immagine utilizzando il metodo di sogliatura di Otsu, determinando automaticamente il valore di soglia ottimale in base all'istogramma dell'immagine. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per ottenere una segmentazione efficace e l'estrazione delle caratteristiche, migliorando l'accuratezza e l'affidabilità delle attività di analisi delle immagini nella tua applicazione.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Applica la binarizzazione all'immagine utilizzando l'algoritmo di sogliatura adattiva di Bradley con sogliatura a immagine integrale. Questo metodo calcola dinamicamente soglie locali in base al vicinato dell'immagine, migliorando l'adattabilità a condizioni di illuminazione variabili e garantendo una segmentazione robusta per le successive attività di elaborazione nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |
| windowSize | int | La dimensione della finestra s x s di pixel centrata su questo pixel. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Applica la binarizzazione all'immagine utilizzando l'algoritmo di sogliatura adattiva di Bradley con sogliatura a immagine integrale. Questo metodo calcola dinamicamente soglie locali in base al vicinato dell'immagine, migliorando l'adattabilità a condizioni di illuminazione variabili e garantendo una segmentazione robusta per le successive attività di elaborazione nella tua applicazione.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Applica la correzione gamma all'immagine, regolando le intensità dei pixel per ottenere la luminosità e il bilanciamento del colore desiderati. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per migliorare la qualità visiva e aumentare l'accuratezza delle successive attività di analisi o visualizzazione nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Esegui la correzione gamma sull'immagine utilizzando coefficienti individuali per i canali rosso, verde e blu, consentendo regolazioni precise del bilanciamento del colore e del contrasto. Integra questo metodo nella tua pipeline di elaborazione delle immagini per ottenere un controllo accurato sulla resa dei colori e migliorare la fedeltà visiva nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gammaRed | float | Gamma per il coefficiente del canale rosso |
| gammaGreen | float | Gamma per il coefficiente del canale verde |
| gammaBlue | float | Coefficiente gamma per il canale blu |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Implementa la regolazione `brightness` per l'immagine, consentendo la modifica dei livelli di luminanza complessiva. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per migliorare la visibilità e la qualità visiva delle immagini nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | int | Valore di luminosità. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Migliora il contrasto dell'[Image](../../com.aspose.imaging/image), amplificando le differenze tra le aree chiare e scure. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per migliorare la chiarezza visiva e la qualità complessiva dell'immagine nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrast | float | Valore di contrasto (nell'intervallo [-100; 100]) |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtra il contenuto all'interno del rettangolo specificato, applicando un filtro di elaborazione delle immagini designato per migliorare o modificare la regione selezionata. Integra questo metodo nel tuo flusso di lavoro di manipolazione delle immagini per ottenere miglioramenti o trasformazioni mirate nella tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Le opzioni. |


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applica un filtro mediano con una dimensione del rettangolo di 5 all'intera immagine.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applica un filtro di levigatura bilaterale con una dimensione del kernel di 5 all'intera immagine.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90.0 gradi all'intera immagine.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Applica un filtro di nitidezza con una dimensione del kernel di 5 e un valore sigma di 4.0 all'intera immagine.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ridimensiona l'immagine secondo le impostazioni specificate, consentendo un controllo preciso su dimensioni, rapporto d'aspetto e comportamento di scaling. Integra questo metodo nel tuo flusso di lavoro di elaborazione delle immagini per ottenere operazioni di ridimensionamento personalizzate in base ai requisiti specifici della tua applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Le impostazioni di ridimensionamento. |

