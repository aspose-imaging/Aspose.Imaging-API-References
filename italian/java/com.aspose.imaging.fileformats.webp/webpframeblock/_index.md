---
title: "WebPFrameBlock"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta il registro degli apritori di blocchi webp."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

Rappresenta il registro degli apritori di blocchi webp.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | Inizializza una nuova istanza della classe `WebPFrameBlock`. |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | Inizializza una nuova istanza della classe `WebPFrameBlock`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce il conteggio dei bit per pixel dell'immagine. |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine. |
| [getWidth()](#getWidth--) | Restituisce la larghezza dell'immagine. |
| [hasAlpha()](#hasAlpha--) | Ottiene un valore che indica se questa istanza ha alfa. |
| [getDuration()](#getDuration--) | Ottiene o imposta la durata del fotogramma. |
| [setDuration(short value)](#setDuration-short-) | Ottiene o imposta la durata del fotogramma. |
| [getLeft()](#getLeft--) | Ottiene o imposta la posizione sinistra del fotogramma. |
| [setLeft(short value)](#setLeft-short-) | Ottiene o imposta la posizione sinistra del fotogramma. |
| [getTop()](#getTop--) | Ottiene o imposta la posizione superiore del fotogramma. |
| [setTop(short value)](#setTop-short-) | Ottiene o imposta la posizione superiore del fotogramma. |
| [getFrameTime()](#getFrameTime--) | Ottiene la durata del fotogramma. |
| [getFrameTop()](#getFrameTop--) | Ottiene lo spostamento superiore del fotogramma. |
| [getFrameLeft()](#getFrameLeft--) | Ottiene lo spostamento sinistro del fotogramma. |
| [getDisposalMethod()](#getDisposalMethod--) | Ottiene il metodo di smaltimento. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Imposta il metodo di smaltimento. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Ottiene il valore che indica se il fotogramma corrente viene miscelato con i valori alfa del fotogramma precedente. |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | Imposta il valore che indica se il fotogramma corrente viene miscelato con i valori alfa del fotogramma precedente. |
| [getFullFrame()](#getFullFrame--) | Ottiene il fotogramma completo. |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


Inizializza una nuova istanza della classe `WebPFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine raster. |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


Inizializza una nuova istanza della classe `WebPFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza. |
| height | int | L'altezza. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce il conteggio dei bit per pixel dell'immagine.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Restituisce l'altezza dell'immagine.

**Returns:**
int - L'altezza dell'immagine.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza dell'immagine.

**Returns:**
int - La larghezza dell'immagine.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Ottiene un valore che indica se questa istanza ha alfa.

**Returns:**
boolean - `true` se questa istanza ha alfa; altrimenti, `false`.

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

### getDuration() {#getDuration--}
```
public short getDuration()
```


Ottiene o imposta la durata del fotogramma.

**Returns:**
short - La durata.
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


Ottiene o imposta la durata del fotogramma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short | La durata. |

### getLeft() {#getLeft--}
```
public short getLeft()
```


Ottiene o imposta la posizione sinistra del fotogramma.

**Returns:**
short - La sinistra.
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


Ottiene o imposta la posizione sinistra del fotogramma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short | La sinistra. |

### getTop() {#getTop--}
```
public short getTop()
```


Ottiene o imposta la posizione superiore del fotogramma.

**Returns:**
short - La parte superiore.
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


Ottiene o imposta la posizione superiore del fotogramma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short | La parte superiore. |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Ottiene la durata del fotogramma.

**Returns:**
int - la durata del fotogramma.
### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


Ottiene lo spostamento superiore del fotogramma.

**Returns:**
int - lo spostamento superiore del fotogramma.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


Ottiene lo spostamento sinistro del fotogramma.

**Returns:**
int - lo spostamento sinistro del fotogramma.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


Ottiene il metodo di smaltimento.

**Returns:**
int - il metodo di smaltimento.
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


Imposta il metodo di smaltimento.

Valore: Il metodo di smaltimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il metodo di smaltimento. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Ottiene il valore che indica se il fotogramma corrente viene miscelato con i valori alfa del fotogramma precedente.

Valore: `` se questo fotogramma utilizza l'alpha-blending; altrimenti, ``.

**Returns:**
boolean - il valore che indica se il fotogramma corrente viene miscelato con i valori alfa del fotogramma precedente.
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


Imposta il valore che indica se il fotogramma corrente viene miscelato con i valori alfa del fotogramma precedente.

Valore: `` se questo fotogramma utilizza l'alpha-blending; altrimenti, ``.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | il valore che indica se il fotogramma corrente viene miscelato con i valori alfa del fotogramma precedente. |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Ottiene il fotogramma completo.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
