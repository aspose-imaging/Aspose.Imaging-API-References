---
title: "EmfRecord"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Basisklasse für EMF-Datensätze. Alle EMF-Datensätze MÜSSEN eine Länge haben, die ein Vielfaches von 4 Bytes ist."
type: docs
weight: 106
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

Basisklasse für EMF‑Datensätze. Alle EMF‑Datensätze MÜSSEN eine Länge haben, die ein Vielfaches von 4 Byte ist. Dies wird in den generischen Strukturen der vorhergehenden EMF‑Datensatztypen dargestellt, indem bei Bedarf am Ende dieser Strukturen AlignmentPadding‑Felder eingefügt werden. Der Inhalt von AlignmentPadding‑Feldern MÜSSEN stets ignoriert werden. Der Übersichtlichkeit halber werden diese Felder nicht in jeder einzelnen EMF‑Datensatzdefinition gezeigt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | Initialisiert eine neue Instanz der `EmfRecord`‑Klasse. |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfRecord`‑Klasse. |
| [EmfRecord(int type)](#EmfRecord-int-) | Initialisiert eine neue Instanz der `EmfRecord`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Liest den Typ. |
| [setType(int value)](#setType-int-) | Setzt den Typ. |
| [getSize()](#getSize--) | Liest die Größe des Datensatzes |
| [setSize(int value)](#setSize-int-) | Setzt die Größe des Datensatzes |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


Initialisiert eine neue Instanz der `EmfRecord`‑Klasse.

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfRecord`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


Initialisiert eine neue Instanz der `EmfRecord`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Der Datensatztyp. |

### getType() {#getType--}
```
public int getType()
```


Liest den Typ.

**Returns:**
int – Der Typ.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Setzt den Typ.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Typ. |

### getSize() {#getSize--}
```
public int getSize()
```


Liest die Größe des Datensatzes

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Setzt die Größe des Datensatzes

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

