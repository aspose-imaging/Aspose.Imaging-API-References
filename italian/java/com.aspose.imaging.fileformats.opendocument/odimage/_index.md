---
title: "OdImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il documento aperto"
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

Il documento aperto
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Recupera la pagina predefinita associata all'immagine, fornendo un accesso essenziale alla pagina principale all'interno della collezione di immagini. |
| [isCached()](#isCached--) | Ottiene un valore booleano che indica se i dati dell'oggetto sono attualmente nella cache, eliminando così la necessità di leggere i dati. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera il conteggio dei bit per pixel dell'immagine. |
| [getPageCount()](#getPageCount--) | Recupera il conteggio totale delle pagine all'interno dell'immagine. |
| [getOdMetadata()](#getOdMetadata--) | Recupera i metadati specifici dei file OpenDocument. |
| [getRecords()](#getRecords--) | Recupera i record OpenDocument memorizzati all'interno dell'immagine. |
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Recupera la pagina predefinita associata all'immagine, fornendo un accesso essenziale alla pagina primaria all'interno della collezione di immagini. Questa proprietà semplifica la navigazione e la manipolazione dei dati dell'immagine, migliorando l'efficienza dei flussi di lavoro di sviluppo software.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Ottiene un valore booleano che indica se i dati dell'oggetto sono attualmente nella cache, eliminando così la necessità di leggere i dati. Questa proprietà funge da indicatore di ottimizzazione, migliorando le prestazioni riducendo le operazioni di accesso ai dati ridondanti.

**Returns:**
boolean - un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupera il conteggio dei bit per pixel dell'immagine. Questa proprietà fornisce informazioni sul livello di dettaglio e sulla profondità di colore rappresentata nell'immagine, aiutando in varie attività di elaborazione e ottimizzazione delle immagini.

**Returns:**
int - il conteggio dei bit per pixel dell'immagine.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupera il conteggio totale delle pagine all'interno dell'immagine. Questa proprietà è essenziale per le applicazioni che gestiscono immagini multipagina, consentendo loro di determinare accuratamente il numero di pagine disponibili per l'elaborazione o la visualizzazione.

**Returns:**
int - il conteggio delle pagine.
### getOdMetadata() {#getOdMetadata--}
```
public final OdMetadata getOdMetadata()
```


Recupera i metadati specifici dei file OpenDocument. Questa proprietà consente l'accesso alle informazioni essenziali incorporate nei file OD, facilitando varie operazioni come l'estrazione, la modifica o l'analisi dei metadati.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


Recupera i record OpenDocument memorizzati all'interno dell'immagine. Questa proprietà garantisce l'accesso a specifici elementi di dati strutturati incorporati nei file OpenDocument, facilitando il recupero o la manipolazione delle informazioni rilevanti per ulteriori elaborazioni o analisi.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - i record.
