---
title: "EmfPlusSerializableObject"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSerializableObject-Datensatz definiert einen Bild-Effekt-Parameterblock, der in einen Datenpuffer serialisiert wurde."
type: docs
weight: 53
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

Der EmfPlusSerializableObject-Datensatz definiert einen Bild-Effekt-Parameterblock, der in einen Datenpuffer serialisiert wurde.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusSerializableObject`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFlags()](#getFlags--) | Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der nicht verwendet wird. |
| [setFlags(short value)](#setFlags-short-) | Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der nicht verwendet wird. |
| [getObjectGuid()](#getObjectGuid--) | Liest oder setzt den GUID-Paketrepräsentationswert ([MS-DTYP] Abschnitt 2.3.4.2) für den Bildeffekt. |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | Liest oder setzt den GUID-Paketrepräsentationswert ([MS-DTYP] Abschnitt 2.3.4.2) für den Bildeffekt. |
| [getBufferSize()](#getBufferSize--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe in Bytes des 32‑bit‑ausgerichteten Buffer‑Feldes angibt. |
| [setBufferSize(int value)](#setBufferSize-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe in Bytes des 32‑bit‑ausgerichteten Buffer‑Feldes angibt. |
| [getBuffer()](#getBuffer--) | Liest oder setzt ein Array von BufferSize‑Bytes, das den serialisierten Parameterblock der Bildeffekte enthält, der dem GUID im Feld ObjectGUID entspricht. |
| [setBuffer(byte[] value)](#setBuffer-byte---) | Liest oder setzt ein Array von BufferSize‑Bytes, das den serialisierten Parameterblock der Bildeffekte enthält, der dem GUID im Feld ObjectGUID entspricht. |
| [getImageEffect()](#getImageEffect--) | Liest oder setzt den Bildeffekt. |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | Liest oder setzt den Bildeffekt. |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusSerializableObject`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die nicht verwendet wird. Dieses Feld SOLLTE auf Null gesetzt werden und MUSS bei Empfang ignoriert werden.

Wert: Die Flags.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die nicht verwendet wird. Dieses Feld SOLLTE auf Null gesetzt werden und MUSS bei Empfang ignoriert werden.

Wert: Die Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


Liest oder setzt den GUID-Paketrepräsentationswert ([MS-DTYP] Abschnitt 2.3.4.2) für den Bildeffekt. Dieser MUST entspricht einem der ImageEffects‑Bezeichner (Abschnitt 2.1.3.1).

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


Liest oder setzt den GUID-Paketrepräsentationswert ([MS-DTYP] Abschnitt 2.3.4.2) für den Bildeffekt. Dieser MUST entspricht einem der ImageEffects‑Bezeichner (Abschnitt 2.1.3.1).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe in Bytes des 32‑bit‑ausgerichteten Buffer‑Feldes angibt.

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe in Bytes des 32‑bit‑ausgerichteten Buffer‑Feldes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


Liest oder setzt ein Array von BufferSize‑Bytes, das den serialisierten Parameterblock der Bildeffekte enthält, der dem GUID im Feld ObjectGUID entspricht. Dieses MUST ist eines der Image‑Effects‑Objekte (Abschnitt 2.2.3).

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


Liest oder setzt ein Array von BufferSize‑Bytes, das den serialisierten Parameterblock der Bildeffekte enthält, der dem GUID im Feld ObjectGUID entspricht. Dieses MUST ist eines der Image‑Effects‑Objekte (Abschnitt 2.2.3).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


Liest oder setzt den Bildeffekt.

Wert: Der Bildeffekt.

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


Liest oder setzt den Bildeffekt.

Wert: Der Bildeffekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

