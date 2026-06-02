---
title: "IcoImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Manipola senza sforzo i file immagine ICO con la nostra API che supporta vari formati file e tipi di frame, inclusi PNG e BMP."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.ico/icoimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public class IcoImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Manipola senza sforzo i file immagine ICO con la nostra API, supportando vari formati file e tipi di frame, inclusi PNG e BMP. Personalizza le impostazioni dei bit per pixel e aggiorna le dimensioni dell'immagine in modo fluido, garantendo una rappresentazione ottimale e compatibilità per le tue icone su diverse piattaforme.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [IcoImage(int width, int height, IcoOptions options)](#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-) | Inizia la creazione di immagini ICO senza sforzo utilizzando la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). |
| [IcoImage(Image image, IcoOptions icoOptions)](#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Progettata per semplicità ed efficienza, la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) ti consente di creare immagini ICO con facilità. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupera il formato file senza sforzo con questa proprietà, consentendo un'integrazione fluida nel tuo flusso di lavoro. |
| [getPageCount()](#getPageCount--) | Ottieni immediatamente una panoramica della struttura del documento con questa proprietà semplice. |
| [getPages()](#getPages--) | Recupera facilmente informazioni complete sulle pagine del documento tramite questa proprietà. |
| [hasAlpha()](#hasAlpha--) | Determina se il canale alfa è presente in questa istanza con questa proprietà. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Espandi la tua immagine ICO aggiungendo una voce di pagina immagine, sfruttando le [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page)](#addPage-com.aspose.imaging.Image-) | Arricchisci la tua immagine ICO senza sforzo inserendo una voce di pagina immagine usando le impostazioni predefinite di [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page, IcoOptions icoOptions)](#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Diversifica la tua immagine ICO senza sforzo integrando una voce immagine personalizzata secondo le tue esigenze con le [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) specificate. |
| [removePage(int index)](#removePage-int-) | Affina la tua immagine ICO rimuovendo una voce immagine specifica situata al `` designato all'interno del file. |
### IcoImage(int width, int height, IcoOptions options) {#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(int width, int height, IcoOptions options)
```


Inizia la creazione di immagini ICO senza sforzo utilizzando la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). Questo costruttore consente di inizializzare nuove istanze di immagini ICO specificando i parametri di larghezza, altezza e opzioni di creazione. Con questo costruttore semplice, puoi personalizzare le immagini ICO secondo le tue specifiche esatte, garantendo compatibilità senza interruzioni e un aspetto visivo accattivante su diverse piattaforme e dispositivi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza. |
| height | int | L'altezza. |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Le opzioni di creazione ICO. |

### IcoImage(Image image, IcoOptions icoOptions) {#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(Image image, IcoOptions icoOptions)
```


Progettata per semplicità ed efficienza, la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) ti consente di creare immagini ICO con facilità. Questo costruttore inizializza una nuova istanza della classe, fornendo una solida base per le tue esigenze di manipolazione delle immagini. Che tu stia sviluppando applicazioni o migliorando le interfacce utente, la classe [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) semplifica la gestione delle immagini ICO, permettendoti di concentrarti sulla fornitura di esperienze eccezionali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'immagine. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Le opzioni ICO. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupera il formato del file senza sforzo con questa proprietà, consentendo un'integrazione fluida nel tuo flusso di lavoro. Utilizzando questa proprietà, ottieni accesso a informazioni critiche sul formato del tuo file, garantendo compatibilità e elaborazione efficiente.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Ottieni immediatamente una panoramica della struttura del documento con questa proprietà semplice. Richiamando questa proprietà, recuperi senza sforzo il numero totale di pagine contenute nel file.

**Returns:**
int - il conteggio delle pagine.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Recupera facilmente informazioni complete sulle pagine del documento tramite questa proprietà. Accedendo a questa proprietà, ottieni una collezione o un array contenente tutte le pagine presenti nel documento.

**Returns:**
com.aspose.imaging.Image[] - le pagine.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Determina se il canale alfa è presente in questa istanza con questa proprietà. Offre un modo rapido per verificare se l'immagine o il documento contiene un canale alfa, fondamentale per varie operazioni di elaborazione e rendering delle immagini. Ideale per garantire la compatibilità e gestire gli effetti di trasparenza in immagini o documenti.

**Returns:**
boolean - un valore che indica se questa istanza ha alfa.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public final void addPage(RasterImage page)
```


Espandi la tua immagine ICO aggiungendo una voce di pagina immagine, sfruttando le [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). Questo metodo incorpora senza soluzione di continuità immagini raster nel tuo file ICO, convertendole in un formato PNG a 32 bit di alta qualità. Perfetto per migliorare i tuoi file ICO con immagini raster garantendo al contempo compatibilità ottimale e qualità di rendering.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine. |

### addPage(Image page) {#addPage-com.aspose.imaging.Image-}
```
public final void addPage(Image page)
```


Arricchisci la tua immagine ICO senza sforzo inserendo una voce di pagina immagine usando le impostazioni predefinite di [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). Questo metodo converte comodamente l'immagine inserita in un formato PNG a 32 bit, garantendo compatibilità e rendering di alta qualità all'interno dell'immagine ICO. Perfetto per integrare senza soluzione di continuità immagini PNG nei tuoi file ICO con facilità ed efficienza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | L'immagine. |

### addPage(Image page, IcoOptions icoOptions) {#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public final void addPage(Image page, IcoOptions icoOptions)
```


Diversifica la tua immagine ICO senza sforzo integrando una voce immagine personalizzata secondo le tue esigenze con le [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) specificate. Questo metodo incorpora senza soluzione di continuità l'immagine secondo le tue opzioni personalizzate, garantendo flessibilità e precisione nel tuo file ICO.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | L'immagine. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Le opzioni ICO. |

### removePage(int index) {#removePage-int-}
```
public final void removePage(int index)
```


Affina la tua immagine ICO rimuovendo una voce immagine specifica situata al `` designato all'interno del file. Questo metodo offre un controllo preciso sulla composizione dell'immagine, permettendoti di perfezionare il tuo file ICO con facilità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice. |

