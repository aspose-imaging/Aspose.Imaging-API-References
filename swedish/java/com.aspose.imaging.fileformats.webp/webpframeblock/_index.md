---
title: "WebPFrameBlock"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar registret för webp-blockens öppnare."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

Representerar registret för webp-blockens öppnare.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | Initierar en ny instans av klassen `WebPFrameBlock`. |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | Initierar en ny instans av klassen `WebPFrameBlock`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [hasAlpha()](#hasAlpha--) | Hämtar ett värde som indikerar om detta objekt har alfa. |
| [getDuration()](#getDuration--) | Hämtar eller anger bildramens varaktighet. |
| [setDuration(short value)](#setDuration-short-) | Hämtar eller anger bildramens varaktighet. |
| [getLeft()](#getLeft--) | Hämtar eller anger bildramens vänstra position. |
| [setLeft(short value)](#setLeft-short-) | Hämtar eller anger bildramens vänstra position. |
| [getTop()](#getTop--) | Hämtar eller anger bildramens övre position. |
| [setTop(short value)](#setTop-short-) | Hämtar eller anger bildramens övre position. |
| [getFrameTime()](#getFrameTime--) | Hämtar bildramens varaktighet. |
| [getFrameTop()](#getFrameTop--) | Hämtar bildramens övre förskjutning. |
| [getFrameLeft()](#getFrameLeft--) | Hämtar bildramens vänstra förskjutning. |
| [getDisposalMethod()](#getDisposalMethod--) | Hämtar borttagningsmetoden. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Anger borttagningsmetoden. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Hämtar värdet som indikerar om den aktuella bildramen blandas med föregående bildramens alfavärden. |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | Anger värdet som indikerar om den aktuella bildramen blandas med föregående bildramens alfavärden. |
| [getFullFrame()](#getFullFrame--) | Hämtar hela ramen. |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


Initierar en ny instans av klassen `WebPFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbilden. |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


Initierar en ny instans av klassen `WebPFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

**Returns:**
int - Bildens bitar per pixel-antal.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

**Returns:**
int - Bildens höjd.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

**Returns:**
int - Bildens bredd.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämtar ett värde som indikerar om detta objekt har alfa.

**Returns:**
boolean - `true` om denna instans har alfa; annars `false`.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Om den aktiva TIFF-ramen har alfakanal, anses hela TIFF-bilden ha alfakanal.
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

// Utdata kan se ut så här:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
```

### getDuration() {#getDuration--}
```
public short getDuration()
```


Hämtar eller anger bildramens varaktighet.

**Returns:**
short - Varaktigheten.
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


Hämtar eller anger bildramens varaktighet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short | Varaktigheten. |

### getLeft() {#getLeft--}
```
public short getLeft()
```


Hämtar eller anger bildramens vänstra position.

**Returns:**
short - Vänster.
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


Hämtar eller anger bildramens vänstra position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short | Vänster. |

### getTop() {#getTop--}
```
public short getTop()
```


Hämtar eller anger bildramens övre position.

**Returns:**
short - Övre.
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


Hämtar eller anger bildramens övre position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short | Övre. |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Hämtar bildramens varaktighet.

**Returns:**
int - bildramens varaktighet.
### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


Hämtar bildramens övre förskjutning.

**Returns:**
int - bildramens övre förskjutning.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


Hämtar bildramens vänstra förskjutning.

**Returns:**
int - bildramens vänstra förskjutning.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


Hämtar borttagningsmetoden.

**Returns:**
int - borttagningsmetoden.
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


Anger borttagningsmetoden.

Värde: Dispositionsmetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | borttagningsmetoden. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Hämtar värdet som indikerar om den aktuella bildramen blandas med föregående bildramens alfavärden.

Värde: `` om denna bildram använder alfa-blandning; annars, ``.

**Returns:**
boolean - värdet som indikerar om den aktuella bildramen blandas med föregående bildramens alfavärden.
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


Anger värdet som indikerar om den aktuella bildramen blandas med föregående bildramens alfavärden.

Värde: `` om denna bildram använder alfa-blandning; annars, ``.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | värdet som indikerar om den aktuella bildramen blandas med föregående bildramens alfavärden. |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Hämtar hela ramen.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
