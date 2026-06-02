---
title: "EmfPlusDrawPie"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawPie-posten specificerar ritning av ett avsnitt av insidan av en ellips."
type: docs
weight: 26
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

EmfPlusDrawPie-posten specificerar ritning av ett avsnitt av insidan av en ellips.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawPie`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getStartAngle()](#getStartAngle--) | Hämtar eller anger startvinkeln. Ett 32‑bitars, icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för pajbiten. |
| [setStartAngle(float value)](#setStartAngle-float-) | Hämtar eller anger startvinkeln. Ett 32‑bitars, icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för pajbiten. |
| [getSweepAngle()](#getSweepAngle--) | Hämtar eller anger svepvinkeln. Ett 32‑bitars flyttal som specificerar omfattningen av den båge som definierar den pajbit som ska ritas, som en vinkel i grader mätt från startpunkten som definieras av StartAngle‑värdet. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Hämtar eller anger svepvinkeln. Ett 32‑bitars flyttal som specificerar omfattningen av den båge som definierar den pajbit som ska ritas, som en vinkel i grader mätt från startpunkten som definieras av StartAngle‑värdet. |
| [getRectData()](#getRectData--) | Hämtar eller anger rektangeldata. Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande lådan för ellipsen som innehåller pajbiten. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Hämtar eller anger rektangeldata. Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande lådan för ellipsen som innehåller pajbiten. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawPie`.

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


Hämtar eller anger objektidentifieraren. Index för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Object Table för att rita pajen. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Index för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Object Table för att rita pajen. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Hämtar eller anger startvinkeln. Ett 32‑bitars, icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för pajbiten. Alla värden är tillåtna, men det MÅSTE tolkas modulo 360, så att resultatet ligger i intervallet 0,0 inklusive till 360,0 exklusive.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Hämtar eller anger startvinkeln. Ett 32‑bitars, icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för pajbiten. Alla värden är tillåtna, men det MÅSTE tolkas modulo 360, så att resultatet ligger i intervallet 0,0 inklusive till 360,0 exklusive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Hämtar eller anger svepvinkeln. Ett 32‑bitars flyttal som specificerar omfattningen av den båge som definierar den pajbit som ska ritas, som en vinkel i grader mätt från startpunkten som definieras av StartAngle‑värdet. Alla värden är tillåtna, men det MÅSTE begränsas till -360,0 till 360,0 inklusive. Ett positivt värde indikerar att svepet definieras i medurs riktning, och ett negativt värde indikerar att svepet definieras i moturs riktning.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Hämtar eller anger svepvinkeln. Ett 32‑bitars flyttal som specificerar omfattningen av den båge som definierar den pajbit som ska ritas, som en vinkel i grader mätt från startpunkten som definieras av StartAngle‑värdet. Alla värden är tillåtna, men det MÅSTE begränsas till -360,0 till 360,0 inklusive. Ett positivt värde indikerar att svepet definieras i medurs riktning, och ett negativt värde indikerar att svepet definieras i moturs riktning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Hämtar eller anger rektangeldata. Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande lådan för ellipsen som innehåller pajbiten. Denna rektangel definierar positionen, storleken och formen på pajen. Objektets typ i detta fält anges av värdet i Flags‑fältet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Hämtar eller anger rektangeldata. Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar den omgivande lådan för ellipsen som innehåller pajbiten. Denna rektangel definierar positionen, storleken och formen på pajen. Objektets typ i detta fält anges av värdet i Flags‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

