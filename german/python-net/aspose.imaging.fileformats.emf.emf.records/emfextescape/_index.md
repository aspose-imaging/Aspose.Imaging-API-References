---
title: "EmfExtEscape Klasse"
type: docs
weight: 440
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfextescape/
---

**Summary:** The EMR_EXTESCAPE record passes arbitrary information to a printer driver. The intent is that the<br/>            information will not result in drawing being done.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfExtEscape(source)](#EmfExtEscape_source_1) | Initialisiert eine neue Instanz der [EmfExtEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextescape/) Klasse. |
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


### Constructor: EmfExtEscape(source) {#EmfExtEscape_source_1}


```
 EmfExtEscape(source) 
```

Initialisiert eine neue Instanz der [EmfExtEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextescape/) Klasse.

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


