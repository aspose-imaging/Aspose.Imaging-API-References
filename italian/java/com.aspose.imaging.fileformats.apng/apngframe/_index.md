---
title: "ApngFrame"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Crea fotogrammi di immagini PNG animate APNG da immagini raster a pagina singola con la nostra API."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

Crea fotogrammi di immagini PNG animate (APNG) da immagini raster a pagina singola con la nostra API. Imposta senza sforzo l'animazione e la durata dei fotogrammi, programma il numero di fotogrammi e regola i livelli di gamma e contrasto, garantendo animazioni accattivanti e personalizzabili su misura per la tua visione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce il conteggio dei bit per pixel dell'immagine. |
| [getWidth()](#getWidth--) | Restituisce la larghezza dell'immagine. |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine. |
| [getFrameTime()](#getFrameTime--) | Ottiene la durata del fotogramma. |
| [setFrameTime(int value)](#setFrameTime-int-) | Imposta la durata del fotogramma. |
| [getFrameTop()](#getFrameTop--) | Ottiene lo spostamento superiore del fotogramma. |
| [getFrameLeft()](#getFrameLeft--) | Ottiene lo spostamento sinistro del fotogramma. |
| [getDisposalMethod()](#getDisposalMethod--) | Ottiene il metodo di smaltimento. |
| [hasTransparentColor()](#hasTransparentColor--) | Restituisce un valore che indica se l'immagine ha un colore trasparente. |
| [hasAlpha()](#hasAlpha--) | Restituisce un valore che indica se questa istanza ha alfa. |
| [getTransparentColor()](#getTransparentColor--) | Restituisce il colore trasparente. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Un valore che indica se l'immagine ha un colore trasparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Il colore trasparente. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Restituisce un valore che indica se ha un colore di sfondo. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene il colore di sfondo. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Un valore che indica se ha un colore di sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Il colore di sfondo. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Ottiene un valore che indica se [use alpha blending]. |
| [getFullFrame()](#getFullFrame--) | Ottiene il fotogramma completo. |
| [cacheData()](#cacheData--) | Memorizza nella cache i dati e garantisce che non venga effettuato alcun caricamento aggiuntivo dei dati dal sottostante `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce il conteggio dei bit per pixel dell'immagine.

**Returns:**
int - il conteggio dei bit per pixel dell'immagine.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza dell'immagine.

**Returns:**
int - la larghezza dell'immagine.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Restituisce l'altezza dell'immagine.

**Returns:**
int - l'altezza dell'immagine.
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Ottiene la durata del fotogramma.

**Returns:**
int - la durata del fotogramma.
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


Imposta la durata del fotogramma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la durata del fotogramma. |

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
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Restituisce un valore che indica se l'immagine ha un colore trasparente.

**Returns:**
boolean - un valore che indica se l'immagine ha un colore trasparente.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Restituisce un valore che indica se questa istanza ha alfa.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Restituisce il colore trasparente.

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Un valore che indica se l'immagine ha un colore trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se l'immagine ha un colore trasparente. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Il colore trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | il colore trasparente. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Restituisce un valore che indica se ha un colore di sfondo.

**Returns:**
boolean - un valore che indica se ha un colore di sfondo.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ottiene il colore di sfondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Un valore che indica se ha un colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se ha un colore di sfondo. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Il colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | il colore di sfondo. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Ottiene un valore che indica se [use alpha blending].

Valore: `true` se [use alpha blending]; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se [use alpha blending].
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Ottiene il fotogramma completo.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Memorizza nella cache i dati e garantisce che non venga effettuato alcun caricamento aggiuntivo dei dati dal sottostante `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

