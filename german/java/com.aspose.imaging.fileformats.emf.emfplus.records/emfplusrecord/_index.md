---
title: "EmfPlusRecord"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Emf‑Basis‑Record‑Typ."
type: docs
weight: 46
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

Der Emf+-Basistyp-Datensatz.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | Initialisiert eine neue Instanz der Klasse `EmfPlusRecord`. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der Klasse `EmfPlusRecord`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Liest ein 16‑Bit‑vorzeichenloses Integer, das den Record‑Typ identifiziert. |
| [getFlags()](#getFlags--) | Liest ein 16‑Bit‑vorzeichenloses Integer, das Informationen für einige Records darüber enthält, wie die Operation auszuführen ist und wie die Struktur des Records beschaffen ist. |
| [setFlags(short value)](#setFlags-short-) | Setzt ein 16‑Bit‑vorzeichenloses Integer, das Informationen für einige Records darüber enthält, wie die Operation auszuführen ist und wie die Struktur des Records beschaffen ist. |
| [getSize()](#getSize--) | Liest ein 32‑Bit‑vorzeichenloses Integer, das die 32‑Bit‑ausgerichtete Anzahl von Bytes im gesamten Record angibt, einschließlich des 12‑Byte‑Record‑Headers und der recordspezifischen Daten. |
| [setSize(int value)](#setSize-int-) | Setzt ein 32‑Bit‑vorzeichenloses Integer, das die 32‑Bit‑ausgerichtete Anzahl von Bytes im gesamten Record angibt, einschließlich des 12‑Byte‑Record‑Headers und der recordspezifischen Daten. |
| [getDataSize()](#getDataSize--) | Liest ein 32‑Bit‑vorzeichenloses Integer, das MUSS die 32‑Bit\u2013ausgerichtete Anzahl von Bytes der Daten im nachfolgenden RecordData‑Feld definieren. |
| [setDataSize(int value)](#setDataSize-int-) | Setzt ein 32‑Bit‑vorzeichenloses Integer, das MUSS die 32‑Bit\u2013ausgerichtete Anzahl von Bytes der Daten im nachfolgenden RecordData‑Feld definieren. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


Initialisiert eine neue Instanz der Klasse `EmfPlusRecord`.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfPlusRecord`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getType() {#getType--}
```
public short getType()
```


Liest ein 16‑Bit‑vorzeichenloses Integer, das den Record‑Typ identifiziert.

**Returns:**
short
### getFlags() {#getFlags--}
```
public short getFlags()
```


Liest ein 16‑Bit‑vorzeichenloses Integer, das Informationen für einige Records darüber enthält, wie die Operation auszuführen ist und wie die Struktur des Records beschaffen ist.

**Returns:**
short - Die Flags.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Setzt ein 16‑Bit‑vorzeichenloses Integer, das Informationen für einige Records darüber enthält, wie die Operation auszuführen ist und wie die Struktur des Records beschaffen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short | Die Flags. |

### getSize() {#getSize--}
```
public int getSize()
```


Liest ein 32‑Bit‑vorzeichenloses Integer, das die 32‑Bit‑ausgerichtete Anzahl von Bytes im gesamten Record angibt, einschließlich des 12‑Byte‑Record‑Headers und der recordspezifischen Daten.

**Returns:**
int - Die Größe.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Setzt ein 32‑Bit‑vorzeichenloses Integer, das die 32‑Bit‑ausgerichtete Anzahl von Bytes im gesamten Record angibt, einschließlich des 12‑Byte‑Record‑Headers und der recordspezifischen Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Größe. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Liefert einen 32‑Bit‑vorzeichenlosen Integer, der DIE 32‑Bit‑ausgerichtete Anzahl von Bytes an Daten im nachfolgenden RecordData‑Feld definieren MUSS. Diese Zahl schließt den 12‑Byte‑Datensatzkopf nicht ein.

**Returns:**
int - Die Größe der Daten.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Setzt einen 32‑Bit‑vorzeichenlosen Integer, der DIE 32‑Bit‑ausgerichtete Anzahl von Bytes an Daten im nachfolgenden RecordData‑Feld definieren MUSS. Diese Zahl schließt den 12‑Byte‑Datensatzkopf nicht ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Größe der Daten. |

