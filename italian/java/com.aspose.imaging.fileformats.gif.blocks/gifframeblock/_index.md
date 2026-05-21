---
title: "GifFrameBlock"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Blocco di fotogramma Gif."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

Blocco di fotogramma Gif.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | Inizializza una nuova istanza della classe `GifFrameBlock`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etichetta di estensione del blocco. |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | La dimensione del descrittore dell'immagine. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | Ottiene la tavolozza dei colori associata. |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | Crea le flag. |
| [getFileFormat()](#getFileFormat--) | Ottiene un valore del formato file |
| [getWidth()](#getWidth--) | Restituisce la larghezza dell'immagine. |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce il conteggio dei bit per pixel dell'immagine. |
| [getFrameTime()](#getFrameTime--) | Ottiene la durata. |
| [setFrameTime(int value)](#setFrameTime-int-) | Imposta la durata. |
| [getInterlaced()](#getInterlaced--) | Ottiene o imposta un valore che indica se questo `GifFrameBlock` è interlacciato. |
| [isInterlaced()](#isInterlaced--) | Ottiene un valore che indica se questa istanza di immagine è interlacciata. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Ottiene o imposta un valore che indica se questo `GifFrameBlock` è interlacciato. |
| [isPaletteSorted()](#isPaletteSorted--) | Ottiene o imposta un valore che indica se la tavolozza dei colori è ordinata. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Ottiene o imposta un valore che indica se la tavolozza dei colori è ordinata. |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | Ottiene o imposta i bit per pixel del fotogramma GIF. |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | Ottiene o imposta i bit per pixel del fotogramma GIF. |
| [getLeft()](#getLeft--) | Ottiene o imposta la posizione sinistra dell'immagine. |
| [setLeft(int value)](#setLeft-int-) | Ottiene o imposta la posizione sinistra dell'immagine. |
| [getTop()](#getTop--) | Ottiene o imposta la posizione superiore dell'immagine. |
| [setTop(int value)](#setTop-int-) | Ottiene o imposta la posizione superiore dell'immagine. |
| [getFrameTop()](#getFrameTop--) | Converte in p. |
| [getFrameLeft()](#getFrameLeft--) | Ottiene il valore sinistro. |
| [getDisposalMethod()](#getDisposalMethod--) | Ottiene il metodo di smaltimento. |
| [getFlags()](#getFlags--) | Ottiene o imposta le flag. |
| [setFlags(byte value)](#setFlags-byte-) | Ottiene o imposta le flag. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Ottiene un valore che indica se [use alpha blending]. |
| [getControlBlock()](#getControlBlock--) | Ottiene il blocco di controllo grafico associato a questo blocco. |
| [hasTransparentColor()](#hasTransparentColor--) | Ottiene un valore che indica se il blocco del fotogramma ha un colore trasparente. |
| [getTransparentColor()](#getTransparentColor--) | Ottiene il colore trasparente del blocco del fotogramma. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Ottiene un valore che indica se il blocco del fotogramma ha un colore trasparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Ottiene il colore trasparente del blocco del fotogramma. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene un valore per il colore di sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Imposta un valore per il colore di sfondo. |
| [getOriginalOptions()](#getOriginalOptions--) | Ottiene le opzioni basate sulle impostazioni del file originale. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Regola la luminosità dell'immagine. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. |
| [getFullFrame()](#getFullFrame--) | Ottiene il fotogramma completo. |
| [resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ridimensiona questa istanza di [RasterCachedImage](../../com.aspose.imaging/rastercachedimage). |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | La larghezza dell'immagine. |
| height | int | L'altezza dell'immagine. |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | int | La posizione sinistra dell'immagine. |
| alto | int | La posizione superiore dell'immagine. |
| width | int | La larghezza dell'immagine. |
| height | int | L'altezza dell'immagine. |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | int | La posizione sinistra dell'immagine. |
| alto | int | La posizione superiore dell'immagine. |
| width | int | La larghezza dell'immagine. |
| height | int | L'altezza dell'immagine. |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza dei colori. |
| isPaletteSorted | boolean | se impostato su `true` la tavolozza dei colori è ordinata. |
| isGifFrameInterlaced | boolean | se impostato su `true` il fotogramma GIF è interlacciato. |
| bitsPerPixel | byte | I bit per pixel. |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine con cui inizializzare i dati dei pixel e della tavolozza del fotogramma. |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine con cui inizializzare i dati dei pixel e della tavolozza del fotogramma. |
| sinistra | int | La posizione sinistra dell'immagine. |
| alto | int | La posizione superiore dell'immagine. |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine con cui inizializzare i dati dei pixel e della tavolozza del fotogramma. |
| sinistra | int | La posizione sinistra dell'immagine. |
| alto | int | La posizione superiore dell'immagine. |
| isPaletteSorted | boolean | se impostato su `true` la tavolozza dei colori è ordinata. |
| isGifFrameInterlaced | boolean | se impostato su `true` il fotogramma GIF è interlacciato. |
| lzwCodeSize | byte | I bit per pixel. |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso da cui caricare un'immagine e con cui inizializzare i dati dei pixel e della tavolozza del fotogramma. |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso da cui caricare un'immagine e con cui inizializzare i dati dei pixel e della tavolozza del fotogramma. |
| sinistra | int | La posizione sinistra dell'immagine. |
| alto | int | La posizione superiore dell'immagine. |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso da cui caricare un'immagine e con cui inizializzare i dati dei pixel e della tavolozza del fotogramma. |
| sinistra | int | La posizione sinistra dell'immagine. |
| alto | int | La posizione superiore dell'immagine. |
| isPaletteSorted | boolean | se impostato su `true` la tavolozza dei colori è ordinata. |
| isGifFrameInterlaced | boolean | se impostato su `true` il fotogramma GIF è interlacciato. |
| lzwCodeSize | byte | I bit per pixel. |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso da cui caricare un'immagine e con cui inizializzare i dati dei pixel e della tavolozza del fotogramma. |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso da cui caricare un'immagine e con cui inizializzare i dati dei pixel e della tavolozza del fotogramma. |
| sinistra | int | La posizione sinistra dell'immagine. |
| alto | int | La posizione superiore dell'immagine. |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Inizializza una nuova istanza della classe `GifFrameBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Il percorso da cui caricare un'immagine e con cui inizializzare i dati dei pixel e della tavolozza del fotogramma. |
| sinistra | int | La posizione sinistra dell'immagine. |
| alto | int | La posizione superiore dell'immagine. |
| isPaletteSorted | boolean | se impostato su `true` la tavolozza dei colori è ordinata. |
| isGifFrameInterlaced | boolean | se impostato su `true` il fotogramma GIF è interlacciato. |
| lzwCodeSize | byte | I bit per pixel. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


Etichetta di estensione del blocco.

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


La dimensione del descrittore dell'immagine.

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


Ottiene la tavolozza dei colori associata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza del fotogramma. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza del contenitore. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


Crea le flag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza dei colori. |
| isPaletteSorted | boolean | se impostato su `true` i colori nella tavolozza dei colori sono ordinati. |
| isGifFrameInterlaced | boolean | se impostato su `true` l'immagine del fotogramma GIF è interlacciata. |

**Returns:**
byte - I flag creati.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ottiene un valore del formato file

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza dell'immagine.

**Returns:**
int - La larghezza dell'immagine.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Restituisce l'altezza dell'immagine.

**Returns:**
int - L'altezza dell'immagine.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce il conteggio dei bit per pixel dell'immagine.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


Ottiene la durata.

Valore: La durata, in millisecondi.

**Returns:**
int - la durata.
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


Imposta la durata.

Valore: La durata, in millisecondi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la durata. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Ottiene o imposta un valore che indica se questo `GifFrameBlock` è interlacciato.

**Returns:**
boolean - `true` se interlacciato; altrimenti, `false`.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Ottiene un valore che indica se questa istanza di immagine è interlacciata.

Valore: `true` se questa istanza di immagine è interlacciata; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questa istanza di immagine è interlacciata.
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Ottiene o imposta un valore che indica se questo `GifFrameBlock` è interlacciato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se interlacciato; altrimenti, `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Ottiene o imposta un valore che indica se la tavolozza dei colori è ordinata.

**Returns:**
boolean - `true` se la tavolozza dei colori è ordinata; altrimenti, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Ottiene o imposta un valore che indica se la tavolozza dei colori è ordinata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se la tavolozza dei colori è ordinata; altrimenti, `false`. |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


Ottiene o imposta i bit per pixel del fotogramma GIF.

**Returns:**
byte - I bit per pixel del fotogramma GIF.
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


Ottiene o imposta i bit per pixel del fotogramma GIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | I bit per pixel del fotogramma GIF. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Ottiene o imposta la posizione sinistra dell'immagine.

**Returns:**
int - La posizione sinistra dell'immagine.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Ottiene o imposta la posizione sinistra dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La posizione sinistra dell'immagine. |

### getTop() {#getTop--}
```
public int getTop()
```


Ottiene o imposta la posizione superiore dell'immagine.

**Returns:**
int - La posizione superiore dell'immagine.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Ottiene o imposta la posizione superiore dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La posizione superiore dell'immagine. |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


Converte in p.

Valore: La parte superiore.

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


Ottiene il valore sinistro.

Valore: La sinistra.

**Returns:**
int - la sinistra.
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Ottiene il metodo di smaltimento.

**Returns:**
int - il metodo di smaltimento.
### getFlags() {#getFlags--}
```
public byte getFlags()
```


Ottiene o imposta le flag.

**Returns:**
byte - I flag.
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Ottiene o imposta le flag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | I flag. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


Ottiene un valore che indica se [use alpha blending].

Valore: `true` se [use alpha blending]; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se [use alpha blending].
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


Ottiene il blocco di controllo grafico associato a questo blocco.

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Ottiene un valore che indica se il blocco del fotogramma ha un colore trasparente.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Ottiene il colore trasparente del blocco del fotogramma.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Ottiene un valore che indica se il blocco del fotogramma ha un colore trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Ottiene il colore trasparente del blocco del fotogramma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ottiene un valore per il colore di sfondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Imposta un valore per il colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | un valore per il colore di sfondo. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere inalterata la profondità di colore e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il metodo [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), verrà prodotta un'immagine PNG di output a 8 bit per pixel. Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al metodo [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) come secondo parametro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Regola la luminosità dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | int | Valore di luminosità. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldColorArgb | int | Valore ARGB del colore vecchio da sostituire. |
| oldColorDiff | byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| newColorArgb | int | Valore ARGB del nuovo colore con cui sostituire il colore vecchio. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Sostituisce tutti i colori non trasparenti con il nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorArgb | int | Valore ARGB del nuovo colore con cui sostituire i colori non trasparenti. |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


Ottiene il fotogramma completo.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
### resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)
```


Ridimensiona questa istanza di [RasterCachedImage](../../com.aspose.imaging/rastercachedimage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | Nuova larghezza. |
| newHeight | int | Nuova altezza. |
| imageResizeSettings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Impostazioni di ridimensionamento. |

