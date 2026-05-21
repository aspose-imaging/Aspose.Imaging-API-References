---
title: "EmfPlusComment"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusComment-posten specificerar godtycklig privat data."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord)
```
public final class EmfPlusComment extends EmfPlusRecord
```

EmfPlusComment-posten specificerar godtycklig privat data.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusComment(EmfPlusRecord source)](#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusComment`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Hämtar eller anger en bytearray med längden DataSize av privat data. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Hämtar eller anger en bytearray med längden DataSize av privat data. |
| [getFlags()](#getFlags--) | Hämtar eller anger ett 16-bitars osignerat heltal som inte används. |
| [setFlags(short value)](#setFlags-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som inte används. |
### EmfPlusComment(EmfPlusRecord source) {#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusComment(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusComment`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Hämtar eller anger en bytearray med längden DataSize av privat data. byte av postspecifik data som följer.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Hämtar eller anger en bytearray med längden DataSize av privat data. byte av postspecifik data som följer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

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

