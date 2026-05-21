---
title: "EmfPlusSetClipRegion"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den EmfPlusSetClipRegion-posten kombinerar den aktuella klippningsregionen med en annan grafikregion."
type: docs
weight: 57
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRegion extends EmfPlusClippingRecordType
```

Posten EmfPlusSetClipRegion kombinerar den aktuella beskärningsregionen med en annan grafikregion. Den nya aktuella beskärningsregionen sätts till resultatet av att utföra CombineMode‑operationen på den tidigare aktuella beskärningsregionen och det angivna EmfPlusRegion‑objektet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSetClipRegion(EmfPlusRecord source)](#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusSetClipRegion`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCm()](#getCm--) | Hämtar eller anger CM (4 bitar): Specificerar den logiska operationen för att kombinera två regioner. |
| [setCm(byte value)](#setCm-byte-) | Hämtar eller anger CM (4 bitar): Specificerar den logiska operationen för att kombinera två regioner. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger indexet för ett EmfPlusRegion‑objekt (avsnitt 2.2.1.8) i EMF+‑objektabellen. Värdet MÅSTE vara mellan 0 och 63, inklusive. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger indexet för ett EmfPlusRegion‑objekt (avsnitt 2.2.1.8) i EMF+‑objektabellen. Värdet MÅSTE vara mellan 0 och 63, inklusive. |
### EmfPlusSetClipRegion(EmfPlusRecord source) {#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRegion(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusSetClipRegion`.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger indexet för ett EmfPlusRegion‑objekt (avsnitt 2.2.1.8) i EMF+‑objektabellen. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger indexet för ett EmfPlusRegion‑objekt (avsnitt 2.2.1.8) i EMF+‑objektabellen. Värdet MÅSTE vara mellan 0 och 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

