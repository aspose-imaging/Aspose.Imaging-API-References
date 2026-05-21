---
title: "EmfPlusSetClipPath"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den EmfPlusSetClipPath-posten kombinerar den aktuella klippningsregionen med en grafikbana."
type: docs
weight: 55
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipPath extends EmfPlusClippingRecordType
```

EmfPlusSetClipPath-posten kombinerar den aktuella beskärningsregionen med en grafikbana. Den nya aktuella beskärningsregionen sätts till resultatet av CombineMode‑operationen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSetClipPath(EmfPlusRecord source)](#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusSetClipPath`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCm()](#getCm--) | Hämtar eller anger CM (4 bitar): Specificerar den logiska operationen för att kombinera två regioner. |
| [setCm(byte value)](#setCm-byte-) | Hämtar eller anger CM (4 bitar): Specificerar den logiska operationen för att kombinera två regioner. |
| [getObjectId()](#getObjectId--) | Hämtar eller anger indexet för ett EmfPlusPath-objekt (avsnitt 2.2.1.6) i EMF+ Object Table. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger indexet för ett EmfPlusPath-objekt (avsnitt 2.2.1.6) i EMF+ Object Table. |
### EmfPlusSetClipPath(EmfPlusRecord source) {#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipPath(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusSetClipPath`.

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


Hämtar eller anger indexet för ett EmfPlusPath-objekt (avsnitt 2.2.1.6) i EMF+ Object Table. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger indexet för ett EmfPlusPath-objekt (avsnitt 2.2.1.6) i EMF+ Object Table. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

