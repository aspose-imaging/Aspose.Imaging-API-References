---
title: "EmfPlusGetDc"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusGetDC-posten specificerar att efterföljande EMF-poster som påträffas i metafilen SKA bearbetas."
type: docs
weight: 39
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusGetDc extends EmfPlusControlRecordType
```

EmfPlusGetDC-posten specificerar att efterföljande EMF-poster som påträffas i metafilen SKA bearbetas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusGetDc(EmfPlusRecord source)](#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusGetDc`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFlags()](#getFlags--) | Hämtar eller anger ett 16-bitars osignerat heltal som inte används. |
| [setFlags(short value)](#setFlags-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som inte används. |
### EmfPlusGetDc(EmfPlusRecord source) {#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusGetDc(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusGetDc`.

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

