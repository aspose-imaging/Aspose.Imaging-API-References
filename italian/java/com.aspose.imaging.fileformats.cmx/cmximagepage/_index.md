---
title: "CmxImagePage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'immagine della pagina CMX"
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

L'immagine della pagina CMX
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | Inizializza una nuova istanza della classe [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | Inizializza una nuova istanza della classe [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | Ottiene la pagina CMX. |
| [getFileFormat()](#getFileFormat--) | Ottiene un valore del formato file |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce il conteggio dei bit per pixel dell'immagine. |
| [isCached()](#isCached--) | Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati. |
| [getWidthF()](#getWidthF--) | Ottiene la larghezza dell'oggetto, in pollici. |
| [getHeightF()](#getHeightF--) | Ottiene l'altezza dell'oggetto, in pollici. |
| [getWidth()](#getWidth--) | Restituisce la larghezza dell'immagine. |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Ottiene le opzioni predefinite. |
| [cacheData()](#cacheData--) | La cache non può essere utilizzata. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Imposta la tavolozza dell'immagine. |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


Inizializza una nuova istanza della classe [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | La pagina CMX. |
| container | [Image](../../com.aspose.imaging/image) | Il contenitore. |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


Inizializza una nuova istanza della classe [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | La pagina CMX. |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Ottiene la pagina CMX.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ottiene un valore del formato file

**Returns:**
long - un valore del formato file
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce il conteggio dei bit per pixel dell'immagine.

**Returns:**
int - il conteggio dei bit per pixel dell'immagine.
### isCached() {#isCached--}
```
public boolean isCached()
```


Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati.

Valore: `true` se i dati dell'oggetto sono nella cache; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Ottiene la larghezza dell'oggetto, in pollici.

**Returns:**
float - la larghezza dell'oggetto, in pollici.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Ottiene l'altezza dell'oggetto, in pollici.

**Returns:**
float - l'altezza dell'oggetto, in pollici.
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
public void cacheData()
```


La cache non può essere utilizzata.


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


Imposta la tavolozza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza da impostare. |
| updateColors | boolean | se impostato su `true` i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine durante il caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

