---
title: "EmfPlusEndOfFile"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusEndOfFile-posten specificerar slutet på EMF-data i metafilen."
type: docs
weight: 31
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusEndOfFile extends EmfPlusControlRecordType
```

EmfPlusEndOfFile-posten specificerar slutet på EMF+-data i metafilen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusEndOfFile(EmfPlusRecord source)](#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusEndOfFile`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFlags()](#getFlags--) | Hämtar eller anger ett 16-bitars osignerat heltal som inte används. |
| [setFlags(short value)](#setFlags-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som inte används. |
### EmfPlusEndOfFile(EmfPlusRecord source) {#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndOfFile(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusEndOfFile`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Hämtar eller anger ett 16-bitars osignerat heltal som inte används. Detta fält SKALL sättas till noll och MÅSTE ignoreras vid mottagning.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Hämtar eller anger ett 16-bitars osignerat heltal som inte används. Detta fält SKALL sättas till noll och MÅSTE ignoreras vid mottagning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

