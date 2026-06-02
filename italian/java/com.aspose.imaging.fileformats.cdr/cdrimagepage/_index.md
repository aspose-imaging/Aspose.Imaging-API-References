---
title: "CdrImagePage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La pagina dell'immagine Cdr"
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

La pagina dell'immagine Cdr
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParentImage()](#getParentImage--) | Ottiene l'immagine padre. |
| [getPageNumber()](#getPageNumber--) | Ottiene il numero di pagina. |
| [isCached()](#isCached--) | Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce il conteggio dei bit per pixel dell'immagine. |
| [getFileFormat()](#getFileFormat--) | Ottiene un valore del formato file |
| [getCdrDocument()](#getCdrDocument--) | Ottiene il documento CDR. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Ottiene le opzioni predefinite. |
| [cacheData()](#cacheData--) | Memorizza nella cache i dati e garantisce che non vengano effettuati ulteriori caricamenti di dati dal sottostante `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Imposta la tavolozza dell'immagine. |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


Ottiene l'immagine padre.

Valore: L'immagine padre.

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Ottiene il numero di pagina.

Valore: Il numero di pagina.

**Returns:**
int - il numero di pagina.
### isCached() {#isCached--}
```
public boolean isCached()
```


Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce il conteggio dei bit per pixel dell'immagine.

**Returns:**
int - il conteggio dei bit per pixel dell'immagine.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ottiene un valore del formato file

**Returns:**
long - un valore del formato file
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Ottiene il documento CDR.

Valore: Il documento CDR.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
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
### cacheData() {#cacheData--}
```
public synchronized void cacheData()
```


Memorizza nella cache i dati e garantisce che non vengano effettuati ulteriori caricamenti di dati dal sottostante `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer`.

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Imposta la tavolozza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza da impostare. |
| updateColors | boolean | se impostato su `true` i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine durante il caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

