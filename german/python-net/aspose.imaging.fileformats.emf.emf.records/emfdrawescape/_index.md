---
title: "EmfDrawEscape Klasse"
type: docs
weight: 350
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---

**Summary:** The EMR_DRAWESCAPE record passes arbitrary information to a printer driver. The intent is that the<br/>            information will result in drawing being done.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDrawEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfDrawEscape(source)](#EmfDrawEscape_source_1) | Initialisiert eine neue Instanz der [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| cj_in | int | r/w | Liest oder setzt eine 32‑Bit‑unsigned Integer, die die Anzahl der Bytes angibt, die an den Druckertreiber übergeben werden sollen. |
| Daten | System.Byte | r/w | Liest oder setzt die Daten, die an den Druckertreiber übergeben werden. Es MUSS cjIn Bytes verfügbar sein. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | Liest oder setzt eine 32‑Bit‑unsigned Integer, die den Druckertreiber‑Escape zum <br/>            Ausführen angibt. Dieser MUSS einer der Werte in der WMF MetafileEscapes Aufzählung ([MSWMF] Abschnitt 2.1.1.17) sein. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfDrawEscape(source) {#EmfDrawEscape_source_1}


```
 EmfDrawEscape(source) 
```

Initialisiert eine neue Instanz der [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/) Klasse.

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


