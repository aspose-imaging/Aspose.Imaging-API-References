---
title: "OtgImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Elabora i file immagine di disegno OTG di OpenDocument Template con la nostra API sfruttando il formato OpenDocument XML con contenuto grafico per una manipolazione senza interruzioni."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

Elabora i file immagine di disegno OpenDocument Template (OTG) con la nostra API, sfruttando il formato OpenDocument XML con contenuto grafico per una manipolazione senza interruzioni. Analizza facilmente i documenti, personalizza i colori di sfondo e regola le dimensioni delle pagine, garantendo un controllo ottimale e flessibilità per i tuoi progetti di grafica vettoriale OTG.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Inizializza un nuovo oggetto [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) fornendo un contenitore di flusso e opzioni di caricamento. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | Crea un nuovo oggetto della classe [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) fornendo un contenitore di flusso. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Questa proprietà fornisce l'accesso al formato di file OTG, offrendo informazioni cruciali sul tipo di dati incapsulati nel file immagine. |
| [getPages()](#getPages--) | Recupera la collezione di pagine associate all'immagine, consentendo agli sviluppatori software di accedere e manipolare ogni singola pagina in modo efficiente. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Inizializza un nuovo oggetto [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) fornendo un contenitore di flusso e opzioni di caricamento. Questo costruttore consente agli sviluppatori di caricare in modo efficiente immagini OTG da stream specificando configurazioni di caricamento personalizzate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il flusso. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


Crea un nuovo oggetto della classe [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) fornendo un contenitore di flusso. Questo costruttore permette agli sviluppatori di creare immagini OTG direttamente da contenitori di flusso, semplificando il processo di lavoro con i dati delle immagini OTG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore dello stream. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Questa proprietà fornisce l'accesso al formato di file OTG, offrendo informazioni cruciali sul tipo di dati incapsulati nel file immagine. Funziona come punto di riferimento fondamentale per gli sviluppatori software, consentendo loro di gestire efficacemente i file OTG nelle proprie applicazioni. Utilizzando questa proprietà, è possibile determinare il formato specifico del file immagine, facilitando l'integrazione e la manipolazione senza soluzione di continuità dei file OTG nei loro sistemi software.

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


Recupera la collezione di pagine associate all'immagine, consentendo agli sviluppatori software di accedere e manipolare ogni singola pagina in modo efficiente. Questa proprietà facilita l'iterazione fluida attraverso le pagine per varie operazioni, migliorando la funzionalità e la versatilità delle applicazioni di elaborazione delle immagini.

**Returns:**
com.aspose.imaging.Image[] - le pagine.
