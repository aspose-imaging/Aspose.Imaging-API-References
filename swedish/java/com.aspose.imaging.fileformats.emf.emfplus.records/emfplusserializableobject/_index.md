---
title: "EmfPlusSerializableObject"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusSerializableObject-posten definierar ett bildeffektparameterblock som har serialiserats till en databuffert."
type: docs
weight: 53
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

EmfPlusSerializableObject-posten definierar ett bildeffektparameterblock som har serialiserats till en databuffert.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusSerializableObject`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFlags()](#getFlags--) | Hämtar eller anger ett 16-bitars osignerat heltal som inte används. |
| [setFlags(short value)](#setFlags-short-) | Hämtar eller anger ett 16-bitars osignerat heltal som inte används. |
| [getObjectGuid()](#getObjectGuid--) | Hämtar eller anger GUID‑paketrepräsentationsvärdet ([MS-DTYP] avsnitt 2.3.4.2) för bildeffekten. |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | Hämtar eller anger GUID‑paketrepräsentationsvärdet ([MS-DTYP] avsnitt 2.3.4.2) för bildeffekten. |
| [getBufferSize()](#getBufferSize--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken i byte för det 32‑bitars justerade Buffer‑fältet. |
| [setBufferSize(int value)](#setBufferSize-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken i byte för det 32‑bitars justerade Buffer‑fältet. |
| [getBuffer()](#getBuffer--) | Hämtar eller anger en array av BufferSize‑byte som innehåller det serialiserade parameterblocket för bildeffekter som motsvarar GUID‑värdet i ObjectGUID‑fältet. |
| [setBuffer(byte[] value)](#setBuffer-byte---) | Hämtar eller anger en array av BufferSize‑byte som innehåller det serialiserade parameterblocket för bildeffekter som motsvarar GUID‑värdet i ObjectGUID‑fältet. |
| [getImageEffect()](#getImageEffect--) | Hämtar eller anger bildeffekten. |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | Hämtar eller anger bildeffekten. |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusSerializableObject`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Hämtar eller anger ett 16‑bitars osignerat heltal som inte används. Detta fält SHOULD sättas till noll och MUST ignoreras vid mottagning.

Värde: Flaggor.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Hämtar eller anger ett 16‑bitars osignerat heltal som inte används. Detta fält SHOULD sättas till noll och MUST ignoreras vid mottagning.

Värde: Flaggor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


Hämtar eller anger GUID‑paketrepräsentationsvärdet ([MS-DTYP] avsnitt 2.3.4.2) för bildeffekten. Detta MUST motsvara en av ImageEffects‑identifierarna (avsnitt 2.1.3.1).

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


Hämtar eller anger GUID‑paketrepräsentationsvärdet ([MS-DTYP] avsnitt 2.3.4.2) för bildeffekten. Detta MUST motsvara en av ImageEffects‑identifierarna (avsnitt 2.1.3.1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken i byte för det 32‑bitars justerade Buffer‑fältet.

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken i byte för det 32‑bitars justerade Buffer‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


Hämtar eller anger en array av BufferSize‑byte som innehåller det serialiserade parameterblocket för bildeffekter som motsvarar GUID‑värdet i ObjectGUID‑fältet. Detta MUST vara ett av Image Effects‑objekten (avsnitt 2.2.3).

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


Hämtar eller anger en array av BufferSize‑byte som innehåller det serialiserade parameterblocket för bildeffekter som motsvarar GUID‑värdet i ObjectGUID‑fältet. Detta MUST vara ett av Image Effects‑objekten (avsnitt 2.2.3).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


Hämtar eller anger bildeffekten.

Värde: Bildeffekten.

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


Hämtar eller anger bildeffekten.

Värde: Bildeffekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

