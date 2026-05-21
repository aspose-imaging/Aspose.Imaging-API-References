---
title: "GifFrameBlock"
second_title: "Aspose.Imaging för Java API-referens"
description: "Gif-ramblock."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

Gif-ramblock.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | Initierar en ny instans av klassen `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | Initierar en ny instans av klassen `GifFrameBlock`. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Blockförlängningsetikett. |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | Bildbeskrivarens storlek. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | Hämtar den associerade färgpaletten. |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | Skapar flaggorna. |
| [getFileFormat()](#getFileFormat--) | Hämtar ett värde för filformat. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getFrameTime()](#getFrameTime--) | Hämtar varaktigheten. |
| [setFrameTime(int value)](#setFrameTime-int-) | Ställer in varaktigheten. |
| [getInterlaced()](#getInterlaced--) | Hämtar eller anger ett värde som indikerar om detta `GifFrameBlock` är interlaced. |
| [isInterlaced()](#isInterlaced--) | Hämtar ett värde som indikerar om denna bildinstans är interlaced. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Hämtar eller anger ett värde som indikerar om detta `GifFrameBlock` är interlaced. |
| [isPaletteSorted()](#isPaletteSorted--) | Hämtar eller anger ett värde som indikerar om färgpaletten är sorterad. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Hämtar eller anger ett värde som indikerar om färgpaletten är sorterad. |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | Hämtar eller anger GIF-ramens bitar per pixel. |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | Hämtar eller anger GIF-ramens bitar per pixel. |
| [getLeft()](#getLeft--) | Hämtar eller anger den vänstra bildens position. |
| [setLeft(int value)](#setLeft-int-) | Hämtar eller anger den vänstra bildens position. |
| [getTop()](#getTop--) | Hämtar eller anger den övre bildens position. |
| [setTop(int value)](#setTop-int-) | Hämtar eller anger den övre bildens position. |
| [getFrameTop()](#getFrameTop--) | Konverterar till p. |
| [getFrameLeft()](#getFrameLeft--) | Hämtar vänster. |
| [getDisposalMethod()](#getDisposalMethod--) | Hämtar borttagningsmetoden. |
| [getFlags()](#getFlags--) | Hämtar eller anger flaggorna. |
| [setFlags(byte value)](#setFlags-byte-) | Hämtar eller anger flaggorna. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Hämtar ett värde som indikerar om [use alpha blending]. |
| [getControlBlock()](#getControlBlock--) | Hämtar grafikstyrningsblocket som är associerat med detta block. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar ett värde som indikerar om ramblocket har transparent färg. |
| [getTransparentColor()](#getTransparentColor--) | Hämtar den transparenta färgen för ramblocket. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Hämtar ett värde som indikerar om ramblocket har transparent färg. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Hämtar den transparenta färgen för ramblocket. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar ett värde för bakgrundsfärgen. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Ställer in ett värde för bakgrundsfärgen. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar alternativen baserat på de ursprungliga filinställningarna. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Justering av bildens ljusstyrka. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [getFullFrame()](#getFullFrame--) | Hämtar hela ramen. |
| [resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändrar storlek på denna [RasterCachedImage](../../com.aspose.imaging/rastercachedimage) instans. |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | int | Den vänstra bildens position. |
| övre | int | Den övre bildens position. |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | int | Den vänstra bildens position. |
| övre | int | Den övre bildens position. |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten. |
| isPaletteSorted | boolean | om den är satt till `true` sorteras färgpaletten. |
| isGifFrameInterlaced | boolean | om den är satt till `true` är GIF-ramen interfolierad. |
| bitsPerPixel | byte | Bitar per pixel. |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden att initiera bildramens pixel- och palettdata med. |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden att initiera bildramens pixel- och palettdata med. |
| vänster | int | Den vänstra bildens position. |
| övre | int | Den övre bildens position. |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden att initiera bildramens pixel- och palettdata med. |
| vänster | int | Den vänstra bildens position. |
| övre | int | Den övre bildens position. |
| isPaletteSorted | boolean | om den är satt till `true` sorteras färgpaletten. |
| isGifFrameInterlaced | boolean | om den är satt till `true` är GIF-ramen interfolierad. |
| lzwCodeSize | byte | Bitar per pixel. |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att ladda en bild från och initiera bildramens pixel- och palettdata med. |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att ladda en bild från och initiera bildramens pixel- och palettdata med. |
| vänster | int | Den vänstra bildens position. |
| övre | int | Den övre bildens position. |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att ladda en bild från och initiera bildramens pixel- och palettdata med. |
| vänster | int | Den vänstra bildens position. |
| övre | int | Den övre bildens position. |
| isPaletteSorted | boolean | om den är satt till `true` sorteras färgpaletten. |
| isGifFrameInterlaced | boolean | om den är satt till `true` är GIF-ramen interfolierad. |
| lzwCodeSize | byte | Bitar per pixel. |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att ladda en bild från och initiera bildramens pixel- och palettdata med. |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att ladda en bild från och initiera bildramens pixel- och palettdata med. |
| vänster | int | Den vänstra bildens position. |
| övre | int | Den övre bildens position. |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initierar en ny instans av klassen `GifFrameBlock`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att ladda en bild från och initiera bildramens pixel- och palettdata med. |
| vänster | int | Den vänstra bildens position. |
| övre | int | Den övre bildens position. |
| isPaletteSorted | boolean | om den är satt till `true` sorteras färgpaletten. |
| isGifFrameInterlaced | boolean | om den är satt till `true` är GIF-ramen interfolierad. |
| lzwCodeSize | byte | Bitar per pixel. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


Blockförlängningsetikett.

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


Bildbeskrivarens storlek.

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


Hämtar den associerade färgpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Ramens palett. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Behållarens palett. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


Skapar flaggorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten. |
| isPaletteSorted | boolean | om den är satt till `true` är färgerna i färgpaletten sorterade. |
| isGifFrameInterlaced | boolean | om den är satt till `true` är GIF-ramens bild interfolierad. |

**Returns:**
byte - De skapade flaggorna.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämtar ett värde för filformat.

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

**Returns:**
int - Bildens bredd.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

**Returns:**
int - Bildens höjd.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

**Returns:**
int - Bildens bitar per pixel-antal.
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


Hämtar varaktigheten.

Värde: Varaktigheten i millisekunder.

**Returns:**
int - varaktigheten.
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


Ställer in varaktigheten.

Värde: Varaktigheten i millisekunder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | varaktigheten. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Hämtar eller anger ett värde som indikerar om detta `GifFrameBlock` är interlaced.

**Returns:**
boolean - `true` om interfolierad; annars `false`.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Hämtar ett värde som indikerar om denna bildinstans är interlaced.

Värde: `true` om den här bildinstansen är interfolierad; annars `false`.

**Returns:**
boolean - ett värde som indikerar om den här bildinstansen är interfolierad.
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta `GifFrameBlock` är interlaced.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om interfolierad; annars `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Hämtar eller anger ett värde som indikerar om färgpaletten är sorterad.

**Returns:**
boolean - `true` om färgpaletten är sorterad; annars `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Hämtar eller anger ett värde som indikerar om färgpaletten är sorterad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om färgpaletten är sorterad; annars `false`. |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


Hämtar eller anger GIF-ramens bitar per pixel.

**Returns:**
byte - GIF-ramens bitar per pixel.
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


Hämtar eller anger GIF-ramens bitar per pixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | GIF-ramens bitar per pixel. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Hämtar eller anger den vänstra bildens position.

**Returns:**
int - Bildens vänstra position.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Hämtar eller anger den vänstra bildens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Bildens vänstra position. |

### getTop() {#getTop--}
```
public int getTop()
```


Hämtar eller anger den övre bildens position.

**Returns:**
int - Den övre bildens plats.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Hämtar eller anger den övre bildens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den övre bildens plats. |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


Konverterar till p.

Värde: Överst.

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


Hämtar vänster.

Värde: Vänster.

**Returns:**
int - vänster.
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Hämtar borttagningsmetoden.

**Returns:**
int - borttagningsmetoden.
### getFlags() {#getFlags--}
```
public byte getFlags()
```


Hämtar eller anger flaggorna.

**Returns:**
byte - Flaggorna.
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Hämtar eller anger flaggorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | Flaggorna. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


Hämtar ett värde som indikerar om [use alpha blending].

Värde: `true` om [use alpha blending]; annars, `false`.

**Returns:**
boolean - ett värde som indikerar om [use alpha blending].
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


Hämtar grafikstyrningsblocket som är associerat med detta block.

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Hämtar ett värde som indikerar om ramblocket har transparent färg.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Hämtar den transparenta färgen för ramblocket.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Hämtar ett värde som indikerar om ramblocket har transparent färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Hämtar den transparenta färgen för ramblocket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar ett värde för bakgrundsfärgen.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Ställer in ett värde för bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | ett värde för bakgrundsfärgen. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Får alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av metoden [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), kommer en PNG-bild med 8 bitar per pixel att produceras. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Justering av bildens ljusstyrka.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | int | Ljusstyrkevärde. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldColorArgb | int | Gammalt färg-ARGB-värde som ska ersättas. |
| oldColorDiff | byte | Tillåten skillnad i gammal färg för att kunna bredda den ersatta färgtonen. |
| newColorArgb | int | Nytt färg-ARGB-värde att ersätta den gamla färgen med. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Ersätter alla icke‑transparenta färger med ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorArgb | int | Nytt färg-ARGB-värde att ersätta icke-transparenta färger med. |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


Hämtar hela ramen.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
### resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)
```


Ändrar storlek på denna [RasterCachedImage](../../com.aspose.imaging/rastercachedimage) instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Ny bredd. |
| newHeight | int | Ny höjd. |
| imageResizeSettings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningar för storleksändring. |

