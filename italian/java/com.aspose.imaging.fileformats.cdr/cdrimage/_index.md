---
title: "CdrImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per il supporto del formato immagine vettoriale CorelDRAW CDR è un toolkit essenziale per gli sviluppatori che lavorano con la grafica vettoriale."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

L'API per il supporto del formato immagine vettoriale CorelDRAW CDR è un toolkit essenziale per gli sviluppatori che lavorano con la grafica vettoriale. Questa API consente l'elaborazione fluida dei file CDR, permettendo la memorizzazione e la manipolazione di diversi elementi come testo, linee, forme, immagini, colori ed effetti. Con le sue capacità complete, gli sviluppatori possono lavorare in modo efficiente con le rappresentazioni vettoriali dei contenuti delle immagini, garantendo precisione e flessibilità nella creazione e modifica della grafica vettoriale CorelDRAW in modo programmatico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Inizia a utilizzare la classe [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) senza sforzo, inizializzando una nuova istanza con i parametri stream e loadOptions. |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Inizia a utilizzare la classe [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) senza sforzo, inizializzando una nuova istanza con i parametri stream e loadOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Recupera la pagina predefinita dell'immagine con facilità utilizzando questa proprietà intuitiva. |
| [isCached()](#isCached--) | Determina senza sforzo se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di leggere i dati. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera la profondità di bit dell'immagine senza sforzo con questa proprietà intuitiva. |
| [getPageCount()](#getPageCount--) | Recupera o aggiorna senza sforzo il conteggio totale delle pagine dell'immagine con questa proprietà intuitiva. |
| [getPages()](#getPages--) | Recupera le pagine dell'immagine in modo fluido con questa proprietà intuitiva. |
| [getCdrDocument()](#getCdrDocument--) | Recupera o aggiorna senza sforzo il documento CDR utilizzando questa proprietà intuitiva. |
| [getFileFormat()](#getFileFormat--) | Recupera il formato file dell'immagine senza sforzo con questa proprietà intuitiva. |
| [getWidth()](#getWidth--) | Restituisce la larghezza dell'immagine. |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine. |
| [cacheData()](#cacheData--) | Metti nella cache i dati senza sforzo per evitare ulteriori caricamenti dalla sorgente sottostante con questo metodo intuitivo. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Personalizza la tavolozza dei colori dell'immagine con questo metodo intuitivo. |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// Carica un'immagine da un file CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Questa chiamata memorizza nella cache solo la pagina predefinita.
    image.cacheData();

    // Memorizza nella cache tutte le pagine in modo che non venga eseguito alcun caricamento dati aggiuntivo dallo stream di dati sottostante.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


Inizia a utilizzare la classe [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) senza sforzo, inizializzando una nuova istanza con i parametri stream e loadOptions. Ideale per gli sviluppatori che cercano un modo comodo per caricare immagini CDR da varie fonti di dati personalizzando il processo di caricamento secondo necessità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Inizia a utilizzare la classe [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) senza sforzo, inizializzando una nuova istanza con i parametri stream e loadOptions. Ideale per gli sviluppatori che cercano un modo comodo per caricare immagini CDR da varie fonti di dati personalizzando il processo di caricamento secondo necessità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | com.aspose.ms.System.IO.Stream | Il flusso. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Recupera la pagina predefinita dell'immagine con facilità utilizzando questa proprietà intuitiva. Perfetto per gli sviluppatori che desiderano un accesso rapido alla pagina principale della loro immagine, garantendo una navigazione e gestione efficienti.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Determina senza sforzo se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di leggere i dati. Ideale per gli sviluppatori che desiderano ottimizzare le prestazioni sfruttando i dati nella cache in modo efficiente, garantendo un accesso più rapido alle informazioni dell'oggetto.

**Returns:**
boolean - `true` se i dati dell'oggetto sono nella cache; altrimenti, `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupera la profondità di bit dell'immagine senza sforzo con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano determinare il livello di dettaglio o la profondità di colore presente nelle loro immagini, garantendo un'elaborazione e una manipolazione accurate.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Recupera o aggiorna senza sforzo il conteggio totale delle pagine dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano gestire dinamicamente immagini multipagina, garantendo una navigazione e manipolazione efficienti del contenuto dell'immagine.

**Returns:**
int - il conteggio delle pagine.
### getPages() {#getPages--}
```
public final Image[] getPages()
```


Recupera le pagine dell'immagine senza problemi con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano accedere e manipolare pagine individuali all'interno di immagini multipagina, garantendo una navigazione efficiente e l'elaborazione.

**Returns:**
com.aspose.imaging.Image[] - le pagine.

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Recupera o aggiorna senza sforzo il documento CDR utilizzando questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano accedere o modificare il documento CDR, garantendo flessibilità ed efficienza nelle loro applicazioni.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera il formato file dell'immagine senza sforzo con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano determinare dinamicamente il formato delle loro immagini, garantendo compatibilità e un'elaborazione accurata nelle loro applicazioni.

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza dell'immagine.

Valore: la larghezza dell'immagine.

**Returns:**
int - la larghezza dell'immagine.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Restituisce l'altezza dell'immagine.

Valore: l'altezza dell'immagine.

**Returns:**
int - l'altezza dell'immagine.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Metti nella cache i dati senza sforzo per evitare ulteriori caricamenti dalla sorgente sottostante con questo metodo intuitivo. Ideale per gli sviluppatori che desiderano ottimizzare le prestazioni pre-caricando i dati, garantendo un accesso più rapido e un funzionamento più fluido nelle loro applicazioni. `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine da un file CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Questa chiamata memorizza nella cache solo la pagina predefinita.
    image.cacheData();

    // Memorizza nella cache tutte le pagine in modo che non venga eseguito alcun caricamento dati aggiuntivo dallo stream di dati sottostante.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Personalizza la tavolozza dei colori dell'immagine con questo metodo intuitivo. Ideale per gli sviluppatori che desiderano applicare schemi di colore specifici o regolazioni in modo dinamico, garantendo un controllo preciso sull'aspetto visivo delle loro immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza da impostare. |
| updateColors | boolean | se impostato su `true` i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine durante il caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

