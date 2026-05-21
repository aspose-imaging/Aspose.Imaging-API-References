---
title: "EmfPlusComment"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusComment-Datensatz gibt beliebige private Daten an."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord)
```
public final class EmfPlusComment extends EmfPlusRecord
```

Der EmfPlusComment-Datensatz gibt beliebige private Daten an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusComment(EmfPlusRecord source)](#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusComment`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Liest oder setzt ein Byte‑Array der Länge DataSize mit privaten Daten. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Liest oder setzt ein Byte‑Array der Länge DataSize mit privaten Daten. |
| [getFlags()](#getFlags--) | Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der nicht verwendet wird. |
| [setFlags(short value)](#setFlags-short-) | Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der nicht verwendet wird. |
### EmfPlusComment(EmfPlusRecord source) {#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusComment(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusComment`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Liest oder setzt ein Byte‑Array der Länge DataSize mit privaten Daten. Bytes von aufzeichnungsspezifischen Daten, die folgen.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Liest oder setzt ein Byte‑Array der Länge DataSize mit privaten Daten. Bytes von aufzeichnungsspezifischen Daten, die folgen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der nicht verwendet wird. Dieses Feld SOLLTE auf Null gesetzt werden und MUSS bei Empfang ignoriert werden.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der nicht verwendet wird. Dieses Feld SOLLTE auf Null gesetzt werden und MUSS bei Empfang ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

