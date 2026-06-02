---
title: "EmfPlusDrawEllipse"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawEllipse-posten specificerar ritning av en ellips."
type: docs
weight: 21
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawEllipse extends EmfPlusDrawingRecordType
```

EmfPlusDrawEllipse-posten specificerar ritning av en ellips.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawEllipse(EmfPlusRecord source)](#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawEllipse`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [getRectData()](#getRectData--) | Hämtar eller anger rektangeldata Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande rutan för ellipsen. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Hämtar eller anger rektangeldata Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande rutan för ellipsen. |
### EmfPlusDrawEllipse(EmfPlusRecord source) {#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawEllipse(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawEllipse`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen‑objekt (avsnitt 2.2.1.7) i EMF+‑objektbordet för att rita ellipsen. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusPen‑objekt (avsnitt 2.2.1.7) i EMF+‑objektbordet för att rita ellipsen. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

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

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Hämtar eller anger rektangeldata Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande rutan för ellipsen.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Hämtar eller anger rektangeldata Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande rutan för ellipsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

