---
title: "GifFrameBlock"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gif-Frame-Block."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

Gif-Frame-Block.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Block-Erweiterungsbezeichnung. |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | Die Größe des Bilddeskriptors. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | Liest die zugehörige Farbpalette. |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | Erstellt die Flags. |
| [getFileFormat()](#getFileFormat--) | Ruft einen Wert des Dateiformats ab |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getFrameTime()](#getFrameTime--) | Liest die Dauer ab. |
| [setFrameTime(int value)](#setFrameTime-int-) | Setzt die Dauer. |
| [getInterlaced()](#getInterlaced--) | Liest oder setzt einen Wert, der angibt, ob dieses `GifFrameBlock` interlaced ist. |
| [isInterlaced()](#isInterlaced--) | Liest einen Wert, der angibt, ob diese Bildinstanz interlaced ist. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Liest oder setzt einen Wert, der angibt, ob dieses `GifFrameBlock` interlaced ist. |
| [isPaletteSorted()](#isPaletteSorted--) | Liest oder setzt einen Wert, der angibt, ob die Farbpalette sortiert ist. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Farbpalette sortiert ist. |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | Liest oder setzt die GIF-Frame-Bits pro Pixel. |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | Liest oder setzt die GIF-Frame-Bits pro Pixel. |
| [getLeft()](#getLeft--) | Liest oder setzt die linke Bildposition. |
| [setLeft(int value)](#setLeft-int-) | Liest oder setzt die linke Bildposition. |
| [getTop()](#getTop--) | Liest oder setzt die obere Bildposition. |
| [setTop(int value)](#setTop-int-) | Liest oder setzt die obere Bildposition. |
| [getFrameTop()](#getFrameTop--) | Konvertiert zu p. |
| [getFrameLeft()](#getFrameLeft--) | Liest den linken Wert. |
| [getDisposalMethod()](#getDisposalMethod--) | Liest die Entsorgungsmethode. |
| [getFlags()](#getFlags--) | Liest oder setzt die Flags. |
| [setFlags(byte value)](#setFlags-byte-) | Liest oder setzt die Flags. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Liest einen Wert, der angibt, ob [use alpha blending]. |
| [getControlBlock()](#getControlBlock--) | Liest den Grafiksteuerungsblock, der mit diesem Block verknüpft ist. |
| [hasTransparentColor()](#hasTransparentColor--) | Liest einen Wert, der angibt, ob der Frame-Block eine transparente Farbe hat. |
| [getTransparentColor()](#getTransparentColor--) | Liest die transparente Farbe des Frame-Blocks. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Liest einen Wert, der angibt, ob der Frame-Block eine transparente Farbe hat. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Liest die transparente Farbe des Frame-Blocks. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest einen Wert für die Hintergrundfarbe. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Setzt einen Wert für die Hintergrundfarbe. |
| [getOriginalOptions()](#getOriginalOptions--) | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Anpassung der Helligkeit des Bildes. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersetzt alle nicht-transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [getFullFrame()](#getFullFrame--) | Liest das vollständige Frame. |
| [resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändert die Größe dieser [RasterCachedImage](../../com.aspose.imaging/rastercachedimage) Instanz. |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | int | Die linke Bildposition. |
| oben | int | Die obere Bildposition. |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | int | Die linke Bildposition. |
| oben | int | Die obere Bildposition. |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette. |
| isPaletteSorted | boolean | wenn auf `true` gesetzt, ist die Farbpalette sortiert. |
| isGifFrameInterlaced | boolean | wenn auf `true` gesetzt, ist das GIF‑Frame interlaced. |
| bitsPerPixel | byte | Die Bits pro Pixel. |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild, mit dem Frame-Pixel- und Palettendaten initialisiert werden. |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild, mit dem Frame-Pixel- und Palettendaten initialisiert werden. |
| links | int | Die linke Bildposition. |
| oben | int | Die obere Bildposition. |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild, mit dem Frame-Pixel- und Palettendaten initialisiert werden. |
| links | int | Die linke Bildposition. |
| oben | int | Die obere Bildposition. |
| isPaletteSorted | boolean | wenn auf `true` gesetzt, ist die Farbpalette sortiert. |
| isGifFrameInterlaced | boolean | wenn auf `true` gesetzt, ist das GIF‑Frame interlaced. |
| lzwCodeSize | byte | Die Bits pro Pixel. |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |
| links | int | Die linke Bildposition. |
| oben | int | Die obere Bildposition. |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |
| links | int | Die linke Bildposition. |
| oben | int | Die obere Bildposition. |
| isPaletteSorted | boolean | wenn auf `true` gesetzt, ist die Farbpalette sortiert. |
| isGifFrameInterlaced | boolean | wenn auf `true` gesetzt, ist das GIF‑Frame interlaced. |
| lzwCodeSize | byte | Die Bits pro Pixel. |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |
| links | int | Die linke Bildposition. |
| oben | int | Die obere Bildposition. |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initialisiert eine neue Instanz der `GifFrameBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |
| links | int | Die linke Bildposition. |
| oben | int | Die obere Bildposition. |
| isPaletteSorted | boolean | wenn auf `true` gesetzt, ist die Farbpalette sortiert. |
| isGifFrameInterlaced | boolean | wenn auf `true` gesetzt, ist das GIF‑Frame interlaced. |
| lzwCodeSize | byte | Die Bits pro Pixel. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


Block-Erweiterungsbezeichnung.

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


Die Größe des Bilddeskriptors.

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


Liest die zugehörige Farbpalette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Frame-Palette. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Container-Palette. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


Erstellt die Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette. |
| isPaletteSorted | boolean | wenn auf `true` gesetzt, sind die Farben in der Farbpalette sortiert. |
| isGifFrameInterlaced | boolean | wenn auf `true` gesetzt, ist das GIF‑Frame‑Bild interlaced. |

**Returns:**
byte - Die erstellten Flags.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ruft einen Wert des Dateiformats ab

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermittelt die Bildbreite.

**Returns:**
int - Die Bildbreite.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Bildhöhe.

**Returns:**
int - Die Bildhöhe.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


Liest die Dauer ab.

Wert: Die Dauer in Millisekunden.

**Returns:**
int - die Dauer.
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


Setzt die Dauer.

Wert: Die Dauer in Millisekunden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Dauer. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Liest oder setzt einen Wert, der angibt, ob dieses `GifFrameBlock` interlaced ist.

**Returns:**
boolean - `true`, wenn interlaced; sonst `false`.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Liest einen Wert, der angibt, ob diese Bildinstanz interlaced ist.

Wert: `true`, wenn diese Bildinstanz interlaced ist; sonst `false`.

**Returns:**
boolean - ein Wert, der angibt, ob diese Bildinstanz interlaced ist.
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob dieses `GifFrameBlock` interlaced ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn interlaced; sonst `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Liest oder setzt einen Wert, der angibt, ob die Farbpalette sortiert ist.

**Returns:**
boolean - `true`, wenn die Farbpalette sortiert ist; sonst `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Farbpalette sortiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn die Farbpalette sortiert ist; sonst `false`. |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


Liest oder setzt die GIF-Frame-Bits pro Pixel.

**Returns:**
byte - Die GIF‑Frame‑Bits pro Pixel.
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


Liest oder setzt die GIF-Frame-Bits pro Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Die GIF‑Frame‑Bits pro Pixel. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Liest oder setzt die linke Bildposition.

**Returns:**
int - Die linke Bildposition.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Liest oder setzt die linke Bildposition.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die linke Bildposition. |

### getTop() {#getTop--}
```
public int getTop()
```


Liest oder setzt die obere Bildposition.

**Returns:**
int - Die obere Bildposition.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Liest oder setzt die obere Bildposition.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die obere Bildposition. |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


Konvertiert zu p.

Wert: Oben.

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


Liest den linken Wert.

Wert: Links.

**Returns:**
int - links.
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Liest die Entsorgungsmethode.

**Returns:**
int - die Entsorgungsmethode.
### getFlags() {#getFlags--}
```
public byte getFlags()
```


Liest oder setzt die Flags.

**Returns:**
byte - Die Flags.
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Liest oder setzt die Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Die Flags. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


Liest einen Wert, der angibt, ob [use alpha blending].

Wert: `true`, wenn [use alpha blending]; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob [use alpha blending] verwendet wird.
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


Liest den Grafiksteuerungsblock, der mit diesem Block verknüpft ist.

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Liest einen Wert, der angibt, ob der Frame-Block eine transparente Farbe hat.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Liest die transparente Farbe des Frame-Blocks.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Liest einen Wert, der angibt, ob der Frame-Block eine transparente Farbe hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Liest die transparente Farbe des Frame-Blocks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Liest einen Wert für die Hintergrundfarbe.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Setzt einen Wert für die Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | ein Wert für die Hintergrundfarbe. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es dann mit der [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) Methode speichern, wird ein PNG‑Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie an die [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) Methode als zweiten Parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Anpassung der Helligkeit des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | int | Helligkeitswert. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldColorArgb | int | Alter ARGB-Farbwert, der ersetzt werden soll. |
| oldColorDiff | byte | Erlaubte Differenz im alten Farbwert, um den ersetzten Farbton erweitern zu können. |
| newColorArgb | int | Neuer ARGB-Farbwert, mit dem die alte Farbe ersetzt wird. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Ersetzt alle nicht transparenten Farben durch die neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorArgb | int | Neuer ARGB-Farbwert, mit dem nicht-transparente Farben ersetzt werden. |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


Liest das vollständige Frame.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
### resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)
```


Ändert die Größe dieser [RasterCachedImage](../../com.aspose.imaging/rastercachedimage) Instanz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Neue Breite. |
| newHeight | int | Neue Höhe. |
| imageResizeSettings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Einstellungen zum Ändern der Größe. |

