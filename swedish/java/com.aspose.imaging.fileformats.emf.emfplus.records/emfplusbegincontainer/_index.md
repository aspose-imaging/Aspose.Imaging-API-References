---
title: "EmfPlusBeginContainer"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusBeginContainer-posten öppnar en ny grafikstatusbehållare och specificerar en transformation för den."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

EmfPlusBeginContainer-posten öppnar en ny grafikstatusbehållare och specificerar en transformation för den.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusBeginContainer`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Hämtar sidans enhet. |
| [getDestRect()](#getDestRect--) | Hämtar eller anger ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som, tillsammans med SrcRect, specificerar en transformation för containern. |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | Hämtar eller anger ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som, tillsammans med SrcRect, specificerar en transformation för containern. |
| [getSrcRect()](#getSrcRect--) | Hämtar eller anger en EmfPlusRectF‑rektangel som, tillsammans med DestRect, specificerar en transformation för containern. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Hämtar eller anger en EmfPlusRectF‑rektangel som, tillsammans med DestRect, specificerar en transformation för containern. |
| [getStackIndex()](#getStackIndex--) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar ett index att associera med grafikstatusbehållaren. |
| [setStackIndex(int value)](#setStackIndex-int-) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar ett index att associera med grafikstatusbehållaren. |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusBeginContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Hämtar sidans enhet.

Värde: Sidans enhet.

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


Hämtar eller anger ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som, tillsammans med SrcRect, specificerar en transformation för containern. Denna transformation resulterar i SrcRect när den tillämpas på DestRect.

Värde: Dest‑rektangeln.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


Hämtar eller anger ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39) som, tillsammans med SrcRect, specificerar en transformation för containern. Denna transformation resulterar i SrcRect när den tillämpas på DestRect.

Värde: Dest‑rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Hämtar eller anger en EmfPlusRectF‑rektangel som, tillsammans med DestRect, specificerar en transformation för containern. Denna transformation resulterar i SrcRect när den tillämpas på DestRect.

Värde: Källrektangeln.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Hämtar eller anger en EmfPlusRectF‑rektangel som, tillsammans med DestRect, specificerar en transformation för containern. Denna transformation resulterar i SrcRect när den tillämpas på DestRect.

Värde: Källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar ett index att associera med grafikstatusbehållaren. Indexet MÅSTE refereras av en efterföljande EmfPlusEndContainer‑post (avsnitt 2.3.7.3) för att stänga grafikstatusbehållaren.

Värde: Indexet för stacken.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar ett index att associera med grafikstatusbehållaren. Indexet MÅSTE refereras av en efterföljande EmfPlusEndContainer‑post (avsnitt 2.3.7.3) för att stänga grafikstatusbehållaren.

Värde: Indexet för stacken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

