---
title: "WmfCreatePatternBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "META_CREATEPATTERNBRUSH-posten skapar ett penselobjekt med ett mönster som specificeras av en bitmap."
type: docs
weight: 23
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

META\_CREATEPATTERNBRUSH-posten skapar ett penselobjekt med ett mönster specificerat av en bitmap.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | WMFs-posten. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitmap()](#getBitmap--) | Hämtar eller anger bitmapen. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Hämtar eller anger bitmapen. |
| [getReserved()](#getReserved--) | Hämtar eller anger reserverade. |
| [setReserved(byte[] value)](#setReserved-byte---) | Hämtar eller anger reserverade. |
| [getPattern()](#getPattern--) | Hämtar eller anger mönstret. |
| [setPattern(byte[] value)](#setPattern-byte---) | Hämtar eller anger mönstret. |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


WMFs-posten.

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Hämtar eller anger bitmapen.

Värde: Bitmapen som specificerar mönstret för penseln.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Hämtar eller anger bitmapen.

Värde: Bitmapen som specificerar mönstret för penseln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


Hämtar eller anger reserverade.

Värde: Den reserverade. Detta fält MÅSTE ignoreras.

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


Hämtar eller anger reserverade.

Värde: Den reserverade. Detta fält MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


Hämtar eller anger mönstret.

Värde: En variabel‑längds array av byte som definierar bitmap‑pixeldata som utgör penselns mönster. Längden på detta fält, i byte, kan beräknas från bitmap‑parametrar enligt följande.

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


Hämtar eller anger mönstret.

Värde: En variabel‑längds array av byte som definierar bitmap‑pixeldata som utgör penselns mönster. Längden på detta fält, i byte, kan beräknas från bitmap‑parametrar enligt följande.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

