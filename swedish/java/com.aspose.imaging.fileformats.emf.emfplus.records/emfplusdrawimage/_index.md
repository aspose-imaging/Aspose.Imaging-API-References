---
title: "EmfPlusDrawImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawImage-posten specificerar ritning av en skalad bild."
type: docs
weight: 22
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

EmfPlusDrawImage-posten specificerar ritning av en skalad bild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawImage`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getImageAttributesId()](#getImageAttributesId--) | Hämtar eller anger bildattributens identifierare En 32-bit osignerad heltal som specificerar indexet för ett valfritt EmfPlusImageAttributes-objekt (avsnitt 2.2.1.5) i EMF+-objektabellen. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Hämtar eller anger bildattributens identifierare En 32-bit osignerad heltal som specificerar indexet för ett valfritt EmfPlusImageAttributes-objekt (avsnitt 2.2.1.5) i EMF+-objektabellen. |
| [getRectData()](#getRectData--) | Hämtar eller anger rektangeldata Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar bildens omgivningsruta. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Hämtar eller anger rektangeldata Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar bildens omgivningsruta. |
| [getSrcRect()](#getSrcRect--) | Hämtar eller anger källrektangeln Ett EmfPlusRectF-objekt som specificerar en del av bilden som ska renderas. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Hämtar eller anger källrektangeln Ett EmfPlusRectF-objekt som specificerar en del av bilden som ska renderas. |
| [getSrcUnit()](#getSrcUnit--) | Hämtar eller anger källenheten 32-bitars signerat heltal som specificerar enheterna för SrcRect-fältet. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Hämtar eller anger källenheten 32-bitars signerat heltal som specificerar enheterna för SrcRect-fältet. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawImage`.

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


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusImage-objekt (sektion 2.2.1.4) i EMF+ Object Table, som specificerar bilden som ska renderas. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för ett EmfPlusImage-objekt (sektion 2.2.1.4) i EMF+ Object Table, som specificerar bilden som ska renderas. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Hämtar eller anger bildattributens identifierare En 32-bit osignerad heltal som specificerar indexet för ett valfritt EmfPlusImageAttributes-objekt (avsnitt 2.2.1.5) i EMF+-objektabellen.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Hämtar eller anger bildattributens identifierare En 32-bit osignerad heltal som specificerar indexet för ett valfritt EmfPlusImageAttributes-objekt (avsnitt 2.2.1.5) i EMF+-objektabellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Hämtar eller anger rektangeldata Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar bildens omgivningsruta. Den del av bilden som specificeras av SrcRect-fältet skalas för att passa denna rektangel.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Hämtar eller anger rektangeldata Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar bildens omgivningsruta. Den del av bilden som specificeras av SrcRect-fältet skalas för att passa denna rektangel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Hämtar eller anger källrektangeln Ett EmfPlusRectF-objekt som specificerar en del av bilden som ska renderas. Den del av bilden som specificeras av denna rektangel skalas för att passa destinationsrektangeln som anges av RectData-fältet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Hämtar eller anger källrektangeln Ett EmfPlusRectF-objekt som specificerar en del av bilden som ska renderas. Den del av bilden som specificeras av denna rektangel skalas för att passa destinationsrektangeln som anges av RectData-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Hämtar eller anger källenheten 32-bitars signerat heltal som specificerar enheterna för SrcRect-fältet. Den MÅSTE vara UnitTypePixel-medlemmen i UnitType‑uppräkningen (avsnitt 2.1.1.33).

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Hämtar eller anger källenheten 32-bitars signerat heltal som specificerar enheterna för SrcRect-fältet. Den MÅSTE vara UnitTypePixel-medlemmen i UnitType‑uppräkningen (avsnitt 2.1.1.33).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

