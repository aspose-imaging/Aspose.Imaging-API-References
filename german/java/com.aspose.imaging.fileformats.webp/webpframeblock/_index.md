---
title: "WebPFrameBlock"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt das Registry für WebP-Blocköffner dar."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

Stellt das Registry für WebP-Blocköffner dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | Initialisiert eine neue Instanz der Klasse `WebPFrameBlock`. |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | Initialisiert eine neue Instanz der Klasse `WebPFrameBlock`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [hasAlpha()](#hasAlpha--) | Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat. |
| [getDuration()](#getDuration--) | Liest oder setzt die Frame-Dauer. |
| [setDuration(short value)](#setDuration-short-) | Liest oder setzt die Frame-Dauer. |
| [getLeft()](#getLeft--) | Liest oder setzt die linke Frame-Position. |
| [setLeft(short value)](#setLeft-short-) | Liest oder setzt die linke Frame-Position. |
| [getTop()](#getTop--) | Liest oder setzt die obere Frame-Position. |
| [setTop(short value)](#setTop-short-) | Liest oder setzt die obere Frame-Position. |
| [getFrameTime()](#getFrameTime--) | Liest die Frame-Dauer. |
| [getFrameTop()](#getFrameTop--) | Liest den oberen Frame-Offset. |
| [getFrameLeft()](#getFrameLeft--) | Liest den linken Frame-Offset. |
| [getDisposalMethod()](#getDisposalMethod--) | Liest die Entsorgungsmethode. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Setzt die Entsorgungsmethode. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Liest den Wert, der angibt, ob das aktuelle Frame mit den Alpha-Werten des vorherigen Frames gemischt wird. |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | Setzt den Wert, der angibt, ob das aktuelle Frame mit den Alpha-Werten des vorherigen Frames gemischt wird. |
| [getFullFrame()](#getFullFrame--) | Liest das vollständige Frame. |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


Initialisiert eine neue Instanz der Klasse `WebPFrameBlock`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


Initialisiert eine neue Instanz der Klasse `WebPFrameBlock`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Bildhöhe.

**Returns:**
int - Die Bildhöhe.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermittelt die Bildbreite.

**Returns:**
int - Die Bildbreite.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat.

**Returns:**
boolean - `true`, wenn diese Instanz Alpha hat; andernfalls `false`.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Hat der aktive TIFF‑Frame einen Alpha‑Kanal, wird das gesamte TIFF‑Bild als Alpha‑Kanal‑vorhanden betrachtet.
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

// Die Ausgabe könnte so aussehen:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### getDuration() {#getDuration--}
```
public short getDuration()
```


Liest oder setzt die Frame-Dauer.

**Returns:**
short - Die Dauer.
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


Liest oder setzt die Frame-Dauer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short | Die Dauer. |

### getLeft() {#getLeft--}
```
public short getLeft()
```


Liest oder setzt die linke Frame-Position.

**Returns:**
short - Der linke.
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


Liest oder setzt die linke Frame-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short | Der linke. |

### getTop() {#getTop--}
```
public short getTop()
```


Liest oder setzt die obere Frame-Position.

**Returns:**
short - Der obere.
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


Liest oder setzt die obere Frame-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short | Der obere. |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Liest die Frame-Dauer.

**Returns:**
int - die Frame-Dauer.
### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


Liest den oberen Frame-Offset.

**Returns:**
int - der obere Frame-Offset.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


Liest den linken Frame-Offset.

**Returns:**
int - der linke Frame-Offset.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


Liest die Entsorgungsmethode.

**Returns:**
int - die Entsorgungsmethode.
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


Setzt die Entsorgungsmethode.

Wert: Die Entsorgungsmethode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Entsorgungsmethode. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Liest den Wert, der angibt, ob das aktuelle Frame mit den Alpha-Werten des vorherigen Frames gemischt wird.

Wert: `` wenn dieses Frame Alpha-Blending verwendet; andernfalls, ``.

**Returns:**
boolean - der Wert, der angibt, ob das aktuelle Frame mit den Alpha-Werten des vorherigen Frames gemischt wird.
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


Setzt den Wert, der angibt, ob das aktuelle Frame mit den Alpha-Werten des vorherigen Frames gemischt wird.

Wert: `` wenn dieses Frame Alpha-Blending verwendet; andernfalls, ``.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | der Wert, der angibt, ob das aktuelle Frame mit den Alpha-Werten des vorherigen Frames gemischt wird. |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Liest das vollständige Frame.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
