---
title: "ApngFrame"
second_title: "Aspose.Imaging för Java API-referens"
description: "Skapa animerade PNG APNG-bildramar från enkelsidiga rasterbilder med vårt API."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

Skapa animerade PNG (APNG)-bildramar från enkelsidiga rasterbilder med vårt API. Ställ enkelt in animation och ramlängd, programmera antalet ramar och justera gamma- och kontrastnivåer, vilket säkerställer fängslande och anpassningsbara animationer skräddarsydda efter din vision.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getFrameTime()](#getFrameTime--) | Hämtar bildramens varaktighet. |
| [setFrameTime(int value)](#setFrameTime-int-) | Ställer in ramlängden. |
| [getFrameTop()](#getFrameTop--) | Hämtar bildramens övre förskjutning. |
| [getFrameLeft()](#getFrameLeft--) | Hämtar bildramens vänstra förskjutning. |
| [getDisposalMethod()](#getDisposalMethod--) | Hämtar borttagningsmetoden. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar ett värde som indikerar om bilden har transparent färg. |
| [hasAlpha()](#hasAlpha--) | Hämta ett värde som indikerar om detta objekt har alfa. |
| [getTransparentColor()](#getTransparentColor--) | Hämtar den transparenta färgen. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Ett värde som indikerar om bilden har transparent färg. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Den transparenta färgen. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Hämtar ett värde som indikerar om den har bakgrundsfärg. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar bakgrundsfärgen. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Ett värde som indikerar om den har bakgrundsfärg. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Bakgrundsfärgen. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Hämtar ett värde som indikerar om [use alpha blending]. |
| [getFullFrame()](#getFullFrame--) | Hämtar hela ramen. |
| [cacheData()](#cacheData--) | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

**Returns:**
int - bildens bitar per pixel-antal.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

**Returns:**
int - bildens bredd.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

**Returns:**
int - bildens höjd.
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Hämtar bildramens varaktighet.

**Returns:**
int - bildramens varaktighet.
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


Ställer in ramlängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | ramlängden. |

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
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Hämtar ett värde som indikerar om bilden har transparent färg.

**Returns:**
boolean - ett värde som indikerar om bilden har transparent färg.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämta ett värde som indikerar om detta objekt har alfa.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Hämtar den transparenta färgen.

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Ett värde som indikerar om bilden har transparent färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om bilden har transparent färg. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Den transparenta färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | den transparenta färgen. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Hämtar ett värde som indikerar om den har bakgrundsfärg.

**Returns:**
boolean - ett värde som indikerar om den har bakgrundsfärg.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar bakgrundsfärgen.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Ett värde som indikerar om den har bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om den har bakgrundsfärg. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | bakgrundsfärgen. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Hämtar ett värde som indikerar om [use alpha blending].

Värde: `true` om [use alpha blending]; annars, `false`.

**Returns:**
boolean - ett värde som indikerar om [use alpha blending].
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Hämtar hela ramen.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

