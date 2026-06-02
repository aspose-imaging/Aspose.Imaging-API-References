---
title: "DjvuPage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe pagina Djvu"
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

Classe pagina Djvu
## Campi

| Campo | Descrizione |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | Si verifica quando [page exported action]. |
| [PropertyChanged](#PropertyChanged) | Si verifica quando il valore di una proprietà cambia. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce il conteggio dei bit per pixel dell'immagine. |
| [getParentImage()](#getParentImage--) | Restituisce l'immagine padre a cui appartiene la pagina |
| [getWidth()](#getWidth--) | Restituisce la larghezza della pagina |
| [getHeight()](#getHeight--) | Ottiene l'altezza della pagina |
| [getImage()](#getImage--) | Ottiene l'immagine. |
| [getThumbnailImage()](#getThumbnailImage--) | Ottiene o imposta l'immagine miniatura per la pagina |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | Ottiene o imposta l'immagine miniatura per la pagina |
| [getPageNumber()](#getPageNumber--) | Ottiene il numero di pagina. |
| [isColor()](#isColor--) | Ottiene un valore che indica se questa istanza è a colori. |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | Ottiene il testo per la posizione del rettangolo |
| [getForegroundImage()](#getForegroundImage--) | Ottiene l'immagine di primo piano per la pagina |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | Ottiene l'immagine di primo piano per la pagina |
| [getTextImage()](#getTextImage--) | Ottiene l'immagine del testo. |
| [getTextImage(int subsample)](#getTextImage-int-) | Ottiene l'immagine del testo. |
| [getBackgroundImage()](#getBackgroundImage--) | Ottiene l'immagine di sfondo. |
| [extractThumbnailImage()](#extractThumbnailImage--) | Estrae l'immagine miniatura dalla pagina Djvu. |
### PageExportedAction {#PageExportedAction}
```
public static final DefEvent<OnPageExportedAction> PageExportedAction
```


Si verifica quando [page exported action].

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Si verifica quando il valore di una proprietà cambia.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce il conteggio dei bit per pixel dell'immagine.

Valore: il conteggio dei bit per pixel dell'immagine.

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


Restituisce l'immagine padre a cui appartiene la pagina

Valore: Il documento.

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza della pagina

Valore: La larghezza.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene l'altezza della pagina

Valore: L'altezza.

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


Ottiene l'immagine.

Valore: L'immagine.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


Ottiene o imposta l'immagine miniatura per la pagina

Valore: L'immagine miniatura.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


Ottiene o imposta l'immagine miniatura per la pagina

Valore: L'immagine miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Ottiene il numero di pagina.

Valore: Il numero di pagina.

**Returns:**
int

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Carica un'immagine DJVU da un flusso file.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//L'output potrebbe apparire così:
//Il numero totale di pagine: 2
//Il numero della pagina attiva:    1
//Il numero della prima pagina:     1
//Il numero dell'ultima pagina:      2
//--------------------------------------------------
//Numero di pagina:     1
//Dimensione pagina:       { Width = 2481, Height = 3508}
//Formato grezzo della pagina: RgbIndexed1Bpp, canali usati: 1
//--------------------------------------------------
//Numero di pagina:     2
//Dimensione pagina:       { Width = 2481, Height = 3508}
//Formato grezzo della pagina: RgbIndexed1Bpp, canali usati: 1
```

### isColor() {#isColor--}
```
public boolean isColor()
```


Ottiene un valore che indica se questa istanza è a colori.

Valore: `true` se questa istanza è a colori; altrimenti, `false`.

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


Ottiene il testo per la posizione del rettangolo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo di posizione. |

**Returns:**
java.lang.String - Testo trovato nella posizione
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


Ottiene l'immagine di primo piano per la pagina

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


Ottiene l'immagine di primo piano per la pagina

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sottocampionamento | int | Il sottocampionamento. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


Ottiene l'immagine del testo.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


Ottiene l'immagine del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sottocampionamento | int | Il sottocampionamento. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


Ottiene l'immagine di sfondo.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


Estrae l'immagine miniatura dalla pagina Djvu.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The DjVu raster image.
