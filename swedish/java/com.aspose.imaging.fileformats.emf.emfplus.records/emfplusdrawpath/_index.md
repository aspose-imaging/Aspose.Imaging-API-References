---
title: "EmfPlusDrawPath"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawPath-posten specificerar ritning av en grafikväg."
type: docs
weight: 25
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

EmfPlusDrawPath-posten specificerar ritning av en grafikväg.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawPath`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectId()](#getObjectId--) | Hämtar eller anger objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Hämtar eller anger objektidentifieraren. |
| [getPenId()](#getPenId--) | Hämtar eller anger pennidentifieraren En 32-bitars osignerad heltal som specificerar ett index i EMF+ Object Table för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) som ska användas för att rita EmfPlusPath. |
| [setPenId(int value)](#setPenId-int-) | Hämtar eller anger pennidentifieraren En 32-bitars osignerad heltal som specificerar ett index i EMF+ Object Table för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) som ska användas för att rita EmfPlusPath. |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar eller anger objektidentifieraren. Indexet för EmfPlusPath-objektet (avsnitt 2.2.1.6) som ska ritas, i EMF+ Object Table. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Hämtar eller anger objektidentifieraren. Indexet för EmfPlusPath-objektet (avsnitt 2.2.1.6) som ska ritas, i EMF+ Object Table. Värdet MÅSTE vara 0 till 63, inklusive.

Värde: Objektidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


Hämtar eller anger pennidentifieraren En 32-bitars osignerad heltal som specificerar ett index i EMF+ Object Table för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) som ska användas för att rita EmfPlusPath. Värdet MÅSTE vara 0 till 63, inklusive.

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


Hämtar eller anger pennidentifieraren En 32-bitars osignerad heltal som specificerar ett index i EMF+ Object Table för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) som ska användas för att rita EmfPlusPath. Värdet MÅSTE vara 0 till 63, inklusive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

