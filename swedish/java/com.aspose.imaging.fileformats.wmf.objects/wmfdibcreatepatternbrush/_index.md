---
title: "WmfDibCreatePatternBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "META_DIBCREATEPATTERNBRUSH-posten skapar ett Brush Object‑avsnitt 2.2.1.1 med ett mönster som specificeras av en DeviceIndependentBitmap DIB‑objektsektion 2.2.2.9."
type: docs
weight: 29
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

META\_DIBCREATEPATTERNBRUSH-posten skapar ett Brush-objekt (avsnitt 2.2.1.1) med ett mönster specificerat av ett DeviceIndependentBitmap (DIB)-objekt (avsnitt 2.2.2.9).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStyle()](#getStyle--) | Hämtar eller anger stilen. |
| [setStyle(int value)](#setStyle-int-) | Hämtar eller anger stilen. |
| [getColorUsage()](#getColorUsage--) | Hämtar eller anger färganvändningen. |
| [setColorUsage(int value)](#setColorUsage-int-) | Hämtar eller anger färganvändningen. |
| [getSourceBitmap()](#getSourceBitmap--) | Hämtar eller anger käll‑bitmapen. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger käll‑bitmapen. |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


Hämtar eller anger stilen.

Värde: De giltiga värdena för detta fält definieras enligt följande: om värdet inte är BS\_PATTERN, måste BS\_DIBPATTERNPT antas. Dessa värden specificeras i BrushStyle‑enumerationen (avsnitt 2.1.1.4).

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Hämtar eller anger stilen.

Värde: De giltiga värdena för detta fält definieras enligt följande: om värdet inte är BS\_PATTERN, måste BS\_DIBPATTERNPT antas. Dessa värden specificeras i BrushStyle‑enumerationen (avsnitt 2.1.1.4).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Hämtar eller anger färganvändningen.

Värde: Colors‑fältet i ett DIB‑objekt innehåller explicita RGB‑värden eller index i en palett.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Hämtar eller anger färganvändningen.

Värde: Colors‑fältet i ett DIB‑objekt innehåller explicita RGB‑värden eller index i en palett.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Hämtar eller anger käll‑bitmapen.

Värde: Variabel‑bit DIB‑objektsdata som definierar mönstret som ska användas i penseln.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger käll‑bitmapen.

Värde: Variabel‑bit DIB‑objektsdata som definierar mönstret som ska användas i penseln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

