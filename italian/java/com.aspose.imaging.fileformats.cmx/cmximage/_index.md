---
title: "CmxImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per il formato immagine vettoriale CMX di Corel Metafile Exchange con supporto alle descrizioni dei metadati è una soluzione completa per gli sviluppatori che lavorano con file CMX."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

L'API per il formato immagine vettoriale Corel Metafile Exchange (CMX) con supporto alle descrizioni dei metadati è una soluzione completa per gli sviluppatori che lavorano con file CMX. Questa API consente il caricamento fluido delle immagini CMX, l'estrazione dei metadati come bit per pixel, dimensioni degli oggetti e altro. Con funzionalità aggiuntive come ridimensionamento, rotazione, impostazione delle palette e conversione in altri formati, questa API permette agli sviluppatori di manipolare e personalizzare efficientemente le immagini vettoriali CMX per soddisfare i requisiti specifici della loro applicazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Inizia a lavorare con la classe [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) in modo fluido inizializzando una nuova istanza con i parametri streamContainer e loadOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupera il formato file dell'immagine senza sforzo con questa proprietà intuitiva. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera la profondità di bit dell'immagine senza sforzo con questa proprietà intuitiva. |
| [getDefaultPage()](#getDefaultPage--) | Recupera senza sforzo la pagina predefinita dell'immagine con questa proprietà intuitiva. |
| [isCached()](#isCached--) | Determina se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di leggere i dati. |
| [getWidthF()](#getWidthF--) | Recupera la larghezza dell'oggetto in pollici con questa proprietà intuitiva. |
| [getHeightF()](#getHeightF--) | Ottieni senza sforzo l'altezza dell'oggetto, misurata in pollici, con questa proprietà intuitiva. |
| [getDocument()](#getDocument--) | Recupera il documento CMX senza sforzo con questa proprietà intuitiva. |
| [getCmxPage()](#getCmxPage--) | Recupera senza sforzo la pagina CMX dell'immagine con questa proprietà intuitiva. |
| [getPageCount()](#getPageCount--) | Recupera il conteggio totale delle pagine dell'immagine con questa proprietà intuitiva. |
| [getPages()](#getPages--) | Recupera le pagine dell'immagine in modo fluido con questa proprietà intuitiva. |
| [cacheData()](#cacheData--) | Metti nella cache i dati per evitare ulteriori caricamenti dalla sorgente sottostante [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) con questo metodo comodo. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Personalizza la tavolozza dei colori dell'immagine con questo metodo intuitivo. |

## Example: The following example shows how to cache all pages of a CMX image.

``` java
String dir = "c:\\temp\\";

// Carica un'immagine da un file CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Questa chiamata memorizza nella cache solo la pagina predefinita.
    image.cacheData();

    // Memorizza nella cache tutte le pagine in modo che non venga eseguito alcun caricamento dati aggiuntivo dallo stream di dati sottostante.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Inizia a lavorare con la classe [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) in modo fluido inizializzando una nuova istanza con i parametri streamContainer e loadOptions. Ideale per gli sviluppatori che cercano un modo comodo per caricare immagini CMX da varie fonti di dati, personalizzando il processo di caricamento secondo le necessità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore dello stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera il formato file dell'immagine senza sforzo con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano determinare dinamicamente il formato delle loro immagini, garantendo compatibilità e un'elaborazione accurata nelle loro applicazioni.

**Returns:**
long - Il formato file [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupera la profondità di bit dell'immagine senza sforzo con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano determinare il livello di dettaglio o la profondità di colore presente nelle loro immagini, garantendo un'elaborazione e una manipolazione accurate.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Recupera senza sforzo la pagina predefinita dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori che cercano un accesso rapido alla pagina principale della loro immagine, garantendo una navigazione e una gestione efficienti.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Determina se i dati dell'oggetto sono attualmente nella cache, eliminando la necessità di leggere i dati. Ideale per gli sviluppatori che desiderano ottimizzare le prestazioni sfruttando i dati nella cache in modo efficiente, garantendo un accesso più rapido alle informazioni dell'oggetto.

**Returns:**
boolean - `true` se i dati dell'oggetto sono nella cache; altrimenti, `false`.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Recupera la larghezza dell'oggetto in pollici con questa proprietà intuitiva. Ideale per gli sviluppatori che cercano misurazioni precise degli oggetti nelle loro applicazioni, garantendo layout e presentazione accurati.

**Returns:**
float - La larghezza dell'oggetto, in pollici.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Ottieni senza sforzo l'altezza dell'oggetto, misurata in pollici, con questa proprietà intuitiva. Ideale per gli sviluppatori che cercano informazioni dimensionali precise per un layout e una presentazione efficaci nelle loro applicazioni.

**Returns:**
float - L'altezza dell'oggetto, in pollici.
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


Recupera il documento CMX senza sforzo con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano accedere o modificare immagini CMX, garantendo flessibilità ed efficienza nelle loro applicazioni.

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Recupera senza sforzo la pagina CMX dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori che cercano un accesso rapido a pagine individuali all'interno delle immagini CMX, garantendo una navigazione e una gestione efficienti.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupera il conteggio totale delle pagine dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano gestire immagini multipagina in modo dinamico, garantendo una navigazione efficiente e la manipolazione del contenuto dell'immagine.

**Returns:**
int - il conteggio delle pagine.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Recupera le pagine dell'immagine senza problemi con questa proprietà intuitiva. Ideale per gli sviluppatori che desiderano accedere e manipolare pagine individuali all'interno di immagini multipagina, garantendo una navigazione efficiente e l'elaborazione.

**Returns:**
com.aspose.imaging.Image[] - le pagine.

**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine da un file CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Questa chiamata memorizza nella cache solo la pagina predefinita.
    image.cacheData();

    // Memorizza nella cache tutte le pagine in modo che non venga eseguito alcun caricamento dati aggiuntivo dallo stream di dati sottostante.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Metti in cache i dati per evitare ulteriori caricamenti dalla sorgente sottostante [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) con questo metodo conveniente. Ideale per gli sviluppatori che desiderano ottimizzare le prestazioni pre-caricando i dati, garantendo un accesso più rapido e un funzionamento più fluido nelle loro applicazioni.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine da un file CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Questa chiamata memorizza nella cache solo la pagina predefinita.
    image.cacheData();

    // Memorizza nella cache tutte le pagine in modo che non venga eseguito alcun caricamento dati aggiuntivo dallo stream di dati sottostante.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
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

