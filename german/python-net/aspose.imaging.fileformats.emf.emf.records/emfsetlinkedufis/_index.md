---
title: "EmfSetLinkedUfis Klasse"
type: docs
weight: 1200
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/
---

**Summary:** The EMR_SETLINKEDUFIS record sets the UniversalFontIds (section 2.2.27) of the linked fonts to<br/>            use during character lookup.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetLinkedUfis

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfSetLinkedUfis(source)](#EmfSetLinkedUfis_source_1) | Initialisiert eine neue Instanz der Klasse [EmfSetLinkedUfis](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| ufis | [EmfUniversalFontId[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/) | r/w | Liest oder schreibt ein Array von uNumLinkedUFI‑Elementen des Typs UniversalFontId, das<br/>            die Kennungen der verknüpften Schriften angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfSetLinkedUfis(source) {#EmfSetLinkedUfis_source_1}


```
 EmfSetLinkedUfis(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfSetLinkedUfis](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/).

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


