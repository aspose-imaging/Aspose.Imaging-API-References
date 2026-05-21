---
title: "EmfPlusDrawRects"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawRects-posten specificerar ritning av en serie rektanglar"
type: docs
weight: 27
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawRects extends EmfPlusDrawingRecordType
```

EmfPlusDrawRects-posten specificerar ritning av en serie rektanglar
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawRects(EmfPlusRecord source)](#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawRects`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getRectData()](#getRectData--) | Hämtar eller anger rektangeldata En array av antingen EmfPlusRect- eller EmfPlusRectF-objekt med längden Count som definierar rektangeldata. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Hämtar eller anger rektangeldata En array av antingen EmfPlusRect- eller EmfPlusRectF-objekt med längden Count som definierar rektangeldata. |
### EmfPlusDrawRects(EmfPlusRecord source) {#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawRects(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawRects`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Hämtar eller anger ett värde som indikerar om PointData är komprimerad. Om satt innehåller RectData ett EmfPlusRect‑objekt (avsnitt 2.2.2.38). Om rensad innehåller RectData ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39).

Värde: `true` om komprimerad; annars `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Hämtar eller anger ett värde som indikerar om PointData är komprimerad. Om satt innehåller RectData ett EmfPlusRect‑objekt (avsnitt 2.2.2.38). Om rensad innehåller RectData ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39).

Värde: `true` om komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Object Table för att rita rektanglarna. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Object Table för att rita rektanglarna. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Hämtar eller anger rektangeldata En array av antingen EmfPlusRect- eller EmfPlusRectF-objekt med längden Count som definierar rektangeldata.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Hämtar eller anger rektangeldata En array av antingen EmfPlusRect- eller EmfPlusRectF-objekt med längden Count som definierar rektangeldata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

