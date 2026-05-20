---
title: "ApngImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per il formato di file immagine Animated PNG Animated Portable Network Graphics è una soluzione versatile per gli sviluppatori che desiderano integrare contenuti animati nelle loro applicazioni."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

L'API per il formato di file immagine Animated PNG (Animated Portable Network Graphics) è una soluzione versatile per gli sviluppatori che desiderano integrare contenuti animati nelle loro applicazioni. Questa API offre un controllo esteso sulle impostazioni dei fotogrammi, consentendo agli utenti di definire parametri specifici per fotogramma, inclusi la durata del ciclo e le impostazioni dei file PNG. Con questo strumento ricco di funzionalità, è possibile gestire e ottimizzare senza sforzo la visualizzazione delle immagini APNG, importare ed esportare immagini, migliorando gli aspetti dinamici e interattivi delle proprie applicazioni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | Inizia a lavorare con la classe [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) inizializzando una nuova istanza senza sforzo. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Accedi rapidamente alle informazioni sul formato file con questa proprietà comoda. |
| [getPageCount()](#getPageCount--) | Recupera il numero totale di pagine nel tuo file immagine senza sforzo con questa proprietà. |
| [getPages()](#getPages--) | Accedi senza sforzo alle pagine della tua immagine con questa proprietà comoda. |
| [getNumPlays()](#getNumPlays--) | Controlla senza sforzo il numero di volte in cui la tua animazione si ripete con questa proprietà versatile. |
| [setNumPlays(int value)](#setNumPlays-int-) | Controlla senza sforzo il numero di volte in cui la tua animazione si ripete con questa proprietà versatile. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Regola facilmente la durata predefinita del fotogramma per la creazione di nuovi fotogrammi con questa proprietà flessibile. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Regola facilmente la durata predefinita del fotogramma per la creazione di nuovi fotogrammi con questa proprietà flessibile. |
| [getInterlaced()](#getInterlaced--) | Determina rapidamente se questo oggetto [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è interlacciato con questa proprietà comoda. |
| [getOriginalOptions()](#getOriginalOptions--) | Recupera le opzioni basate sulle impostazioni originali del file senza sforzo con questo metodo intuitivo. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Recupera senza sforzo le opzioni predefinite con questo metodo semplice. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Ottieni rapidamente la data e l'ora dell'ultima modifica dell'immagine risorsa con questo metodo intuitivo. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Aggiungi una nuova pagina all'immagine senza sforzo con questo metodo intuitivo. |
| [addFrame()](#addFrame--) | /\*\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | Espandi senza sforzo la tua collezione di fotogrammi aggiungendo un nuovo fotogramma alla fine con questo metodo intuitivo. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | Espandi la tua collezione di fotogrammi senza interruzioni aggiungendo un nuovo fotogramma alla collezione con questo metodo intuitivo. |
| [insertFrame(int index)](#insertFrame-int-) | Inserisci senza sforzo un nuovo fotogramma nella tua collezione di fotogrammi all'indice specificato con questo metodo intuitivo. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | Inserisce un nuovo fotogramma nella propria collezione di fotogrammi all'indice specificato. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | Inserisce un nuovo fotogramma nella propria collezione di fotogrammi all'indice specificato. |
| [popFrameAt(int index)](#popFrameAt-int-) | Rimuovi e recupera il fotogramma all'indice specificato dalla tua collezione di fotogrammi con questo metodo intuitivo. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | Rimuovi il fotogramma all'indice specificato dalla tua collezione di fotogrammi senza interruzioni con questo metodo. |
| [removeAllFrames()](#removeAllFrames--) | Svuota la tua collezione di fotogrammi rimuovendo tutti i fotogrammi con questo metodo intuitivo. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | Imposta l'immagine raster specificata come immagine predefinita per l'animazione corrente senza sforzo con questo metodo. |
| [resetDefaultImage()](#resetDefaultImage--) | Rimuovi un'immagine predefinita impostata in precedenza con questo metodo intuitivo. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Esporta in animazione APNG con cicli di animazione illimitati come impostazione predefinita
    image.save("Animation1.webp.png", new ApngOptions());
    // Configurazione dei cicli di animazione
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Configurazione della durata predefinita del fotogramma
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


Inizia a lavorare con la classe [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) inizializzando una nuova istanza senza sforzo. Perfetto per gli sviluppatori che desiderano iniziare a utilizzare gli oggetti ApngImage rapidamente ed efficientemente nei loro progetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Le opzioni. |
| width | int | La larghezza. |
| height | int | L'altezza. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accedi rapidamente alle informazioni sul formato del file con questa proprietà comoda. Ideale per gli sviluppatori che hanno bisogno di recuperare facilmente i dettagli sul formato dei loro file Apng.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupera il numero totale di pagine nel tuo file immagine senza sforzo con questa proprietà. Ideale per gli sviluppatori che necessitano di un accesso rapido alle informazioni sul conteggio delle pagine.

Valore: Il conteggio delle pagine.

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accedi senza sforzo alle pagine della tua immagine con questa proprietà comoda. Perfetto per gli sviluppatori che cercano un accesso rapido e semplice alle singole pagine per la manipolazione.

Valore: Le pagine.

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


Controlla senza sforzo il numero di volte in cui la tua animazione si ripete con questa proprietà versatile. Perfetto per gli sviluppatori che desiderano un controllo preciso sul comportamento dell'animazione, con supporto per il looping infinito nel caso in cui il valore sia pari a 0.

Valore: Il numero di volte da ripetere.

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


Controlla senza sforzo il numero di volte in cui la tua animazione si ripete con questa proprietà versatile. Perfetto per gli sviluppatori che desiderano un controllo preciso sul comportamento dell'animazione, con supporto per il looping infinito nel caso in cui il valore sia pari a 0.

Valore: Il numero di volte da ripetere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


Regola facilmente la durata predefinita del fotogramma per creare nuovi fotogrammi con questa proprietà flessibile. Perfetto per gli sviluppatori che desiderano personalizzare la temporizzazione dei fotogrammi in modo efficiente nelle loro animazioni.

Valore: La durata predefinita del fotogramma, in millisecondi.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


Regola facilmente la durata predefinita del fotogramma per creare nuovi fotogrammi con questa proprietà flessibile. Perfetto per gli sviluppatori che desiderano personalizzare la temporizzazione dei fotogrammi in modo efficiente nelle loro animazioni.

Valore: La durata predefinita del fotogramma, in millisecondi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Determina rapidamente se questo oggetto [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) è interlacciato con questa proprietà comoda. Ideale per gli sviluppatori che hanno bisogno di verificare facilmente lo stato di interlacciamento delle immagini PNG.

Valore: `true` se interlacciato; altrimenti, `false`.

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Recupera le opzioni basate sulle impostazioni del file originale senza sforzo con questo metodo intuitivo. Perfetto per gli sviluppatori che desiderano accedere e utilizzare impostazioni che corrispondono alle caratteristiche del file originale. Questo può essere utile per mantenere inalterata la profondità di colore e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo utilizzando il metodo [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), verrà prodotta un'immagine PNG di output a 8 bit per pixel. Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al metodo [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) come secondo parametro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Recupera le opzioni predefinite senza sforzo con questo metodo semplice. Ideale per gli sviluppatori che cercano un accesso rapido alle impostazioni predefinite delle immagini Apng.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | java.lang.Object[] | Gli argomenti. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Ottieni rapidamente la data e l'ora in cui l'immagine di risorsa è stata modificata l'ultima volta con questo metodo intuitivo. Ideale per gli sviluppatori che hanno bisogno di monitorare le modifiche e gestire le risorse in modo efficace.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| useDefault | boolean | se impostato su `true` utilizza le informazioni da FileInfo come valore predefinito. |

**Returns:**
java.util.Date - La data e l'ora in cui l'immagine di risorsa è stata modificata l'ultima volta.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Aggiungi una nuova pagina all'immagine senza sforzo con questo metodo intuitivo. Perfetto per gli sviluppatori che desiderano espandere dinamicamente il contenuto dei loro file immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La pagina da aggiungere. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\*\*

Aggiungi facilmente un nuovo fotogramma alla fine della tua collezione di fotogrammi con questo metodo semplice. Ideale per gli sviluppatori che desiderano espandere dinamicamente la loro collezione di fotogrammi per animazioni con immagini a più fotogrammi. Un nuovo fotogramma verrà creato in base alle dimensioni dell'immagine corrente.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


Espandi senza sforzo la tua collezione di fotogrammi aggiungendo un nuovo fotogramma alla fine con questo metodo intuitivo. Perfetto per gli sviluppatori che desiderano migliorare dinamicamente le loro animazioni di immagini a più fotogrammi. Il contenuto del nuovo fotogramma verrà riempito dall'immagine specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine del fotogramma. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


Espandi la tua collezione di fotogrammi senza soluzione di continuità aggiungendo un nuovo fotogramma con questo metodo intuitivo. Ideale per gli sviluppatori che desiderano arricchire le loro animazioni di immagini a più fotogrammi. Il contenuto del nuovo fotogramma verrà riempito dall'immagine specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine del fotogramma. |
| frameTime | long | La durata del fotogramma, in millisecondi. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


Inserisci senza sforzo un nuovo fotogramma nella tua collezione di fotogrammi nella posizione specificata con questo metodo intuitivo. Ideale per gli sviluppatori che cercano un controllo preciso sulla disposizione dei fotogrammi nelle loro animazioni di immagini a più fotogrammi. Un nuovo fotogramma verrà creato in base alle dimensioni dell'immagine corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


Inserisce un nuovo fotogramma nella propria collezione di fotogrammi all'indice specificato. Il contenuto del nuovo fotogramma verrà riempito dall'immagine specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine del fotogramma. |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


Inserisce un nuovo fotogramma nella propria collezione di fotogrammi all'indice specificato. Il contenuto del nuovo fotogramma verrà riempito dall'immagine specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine del fotogramma. |
| frameTime | long | La durata del fotogramma, in millisecondi. |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


Rimuovi e recupera il fotogramma all'indice specificato dalla tua collezione di fotogrammi con questo metodo intuitivo. Perfetto per gli sviluppatori che cercano una gestione efficiente dei fotogrammi nelle loro animazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


Rimuovi il fotogramma all'indice specificato dalla tua collezione di fotogrammi senza soluzione di continuità con questo metodo. Perfetto per gli sviluppatori che cercano una gestione semplificata dei fotogrammi nelle loro immagini a più fotogrammi. Il fotogramma da eliminare verrà smaltito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


Cancella la tua collezione di fotogrammi rimuovendo tutti i fotogrammi con questo metodo intuitivo. Ideale per gli sviluppatori che desiderano reimpostare o aggiornare le loro animazioni.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


Imposta l'immagine raster specificata come immagine predefinita per l'animazione corrente senza sforzo con questo metodo. Perfetto per gli sviluppatori che desiderano personalizzare l'immagine predefinita nelle loro animazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


Rimuovi un'immagine predefinita impostata in precedenza con questo metodo intuitivo. Ideale per gli sviluppatori che desiderano reimpostare o cancellare l'immagine predefinita nella loro animazione. Dopo questa operazione, l'immagine predefinita è il primo fotogramma nella propria collezione di fotogrammi (non può essere eliminata usando questo metodo).

