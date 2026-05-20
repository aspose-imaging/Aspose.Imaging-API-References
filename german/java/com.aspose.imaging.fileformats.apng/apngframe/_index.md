---
title: "ApngFrame"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Erstellen Sie animierte PNG APNG-Bildrahmen aus einseitigen Rasterbildern mit unserer API."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

Erstellen Sie animierte PNG (APNG)-Bildrahmen aus einseitigen Rasterbildern mit unserer API. Legen Sie nahtlos Animation und Bilddauer fest, programmieren Sie die Anzahl der Rahmen und passen Sie Gamma- und Kontrastwerte an, um fesselnde und anpassbare Animationen zu gewährleisten, die auf Ihre Vision zugeschnitten sind.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getFrameTime()](#getFrameTime--) | Liest die Frame-Dauer. |
| [setFrameTime(int value)](#setFrameTime-int-) | Legt die Bilddauer fest. |
| [getFrameTop()](#getFrameTop--) | Liest den oberen Frame-Offset. |
| [getFrameLeft()](#getFrameLeft--) | Liest den linken Frame-Offset. |
| [getDisposalMethod()](#getDisposalMethod--) | Liest die Entsorgungsmethode. |
| [hasTransparentColor()](#hasTransparentColor--) | Gibt einen Wert zurück, der angibt, ob das Bild eine transparente Farbe hat. |
| [hasAlpha()](#hasAlpha--) | Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat. |
| [getTransparentColor()](#getTransparentColor--) | Gibt die transparente Farbe zurück. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Ein Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Die transparente Farbe. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Gibt einen Wert zurück, der angibt, ob es eine Hintergrundfarbe hat. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest die Hintergrundfarbe. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Ein Wert, der angibt, ob es eine Hintergrundfarbe hat. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Die Hintergrundfarbe. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Liest einen Wert, der angibt, ob [use alpha blending]. |
| [getFullFrame()](#getFullFrame--) | Liest das vollständige Frame. |
| [cacheData()](#cacheData--) | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) durchgeführt werden. |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int – die Bit‑Pro‑Pixel‑Anzahl des Bildes.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermittelt die Bildbreite.

**Returns:**
int – die Bildbreite.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Bildhöhe.

**Returns:**
int – die Bildhöhe.
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Liest die Frame-Dauer.

**Returns:**
int - die Frame-Dauer.
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


Legt die Bilddauer fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Bilddauer. |

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
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Gibt einen Wert zurück, der angibt, ob das Bild eine transparente Farbe hat.

**Returns:**
boolesch - ein Wert, der angibt, ob das Bild eine transparente Farbe hat.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Gibt die transparente Farbe zurück.

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Ein Wert, der angibt, ob das Bild eine transparente Farbe hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob das Bild eine transparente Farbe hat. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Die transparente Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | die transparente Farbe. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Gibt einen Wert zurück, der angibt, ob es eine Hintergrundfarbe hat.

**Returns:**
boolean – ein Wert, der angibt, ob es eine Hintergrundfarbe hat.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Liest die Hintergrundfarbe.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Ein Wert, der angibt, ob es eine Hintergrundfarbe hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob es eine Hintergrundfarbe hat. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Die Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | die Hintergrundfarbe. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Liest einen Wert, der angibt, ob [use alpha blending].

Wert: `true`, wenn [use alpha blending]; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob [use alpha blending] verwendet wird.
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Liest das vollständige Frame.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) durchgeführt werden.

