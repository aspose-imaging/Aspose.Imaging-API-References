---
title: "EmfExtCreateFontIndirectW Klasse"
type: docs
weight: 420
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---

**Summary:** The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreateFontIndirectW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW__1) | Initialisiert eine neue Instanz der Klasse [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/). |
| [EmfExtCreateFontIndirectW(source)](#EmfExtCreateFontIndirectW_source_2) | Initialisiert eine neue Instanz der Klasse [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| elw | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | r/w | Liest oder setzt ein LogFontExDv‑Objekt (Abschnitt 2.2.15), das die logische Schriftart angibt. Ein<br/>            LogFont‑Objekt 2.2.13 KANN stattdessen vorhanden sein.[90]Der Vorgang zur Bestimmung des Typs des<br/>            Objekts in diesem Feld wird unten beschrieben. |
| ih_fonts | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Index des logischen Schriftart‑Objekts<br/>            in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt<br/>            wiederverwendet oder geändert werden kann. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW__1}


```
 EmfExtCreateFontIndirectW() 
```

Initialisiert eine neue Instanz der Klasse [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/).

### Constructor: EmfExtCreateFontIndirectW(source) {#EmfExtCreateFontIndirectW_source_2}


```
 EmfExtCreateFontIndirectW(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Die Quelle. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Die Quelle. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Der Datensatztyp. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


