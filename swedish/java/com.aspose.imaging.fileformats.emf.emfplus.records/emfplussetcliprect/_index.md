---
title: "EmfPlusSetClipRect"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den EmfPlusSetClipRect-posten kombinerar den aktuella klippningsregionen med en rektangel."
type: docs
weight: 56
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

Den EmfPlusSetClipRect-posten kombinerar den aktuella klippningsregionen med en rektangel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusSetClipRect`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCm()](#getCm--) | Hämtar eller anger CM (4 bitar): Specificerar den logiska operationen för att kombinera två regioner. |
| [setCm(byte value)](#setCm-byte-) | Hämtar eller anger CM (4 bitar): Specificerar den logiska operationen för att kombinera två regioner. |
| [getClipRect()](#getClipRect--) | Hämtar eller anger ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som definierar rektangeln som ska användas i CombineMode‑operationen. |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | Hämtar eller anger ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som definierar rektangeln som ska användas i CombineMode‑operationen. |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusSetClipRect`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getCm() {#getCm--}
```
public byte getCm()
```


Hämtar eller anger CM (4 bitar): Specificerar den logiska operationen för att kombinera två regioner. Se uppräkningen CombineMode (avsnitt 2.1.1.4) för betydelsen av värdena.

Värde: cm‑värdet.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Hämtar eller anger CM (4 bitar): Specificerar den logiska operationen för att kombinera två regioner. Se uppräkningen CombineMode (avsnitt 2.1.1.4) för betydelsen av värdena.

Värde: cm‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


Hämtar eller anger ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som definierar rektangeln som ska användas i CombineMode‑operationen.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


Hämtar eller anger ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som definierar rektangeln som ska användas i CombineMode‑operationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

