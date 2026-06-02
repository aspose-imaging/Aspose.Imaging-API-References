---
title: "EmfSetIcmProfileW Klasse"
type: docs
weight: 1180
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---

**Summary:** The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of<br/>            Unicode characters, for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileW

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfSetIcmProfileW(source)](#EmfSetIcmProfileW_source_1) | Initialisiert eine neue Instanz der [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Liest oder setzt eine 32‑Bit‑Unsigned‑Integer, die die Größe der Farbbildprofildaten angibt, falls angehängt. |
| cb_name | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes im Unicode‑<br/>            UTF16‑LE‑Namen des gewünschten Farbprofils angibt. |
| Daten | System.Byte | r/w | Liest oder schreibt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE<br/>            Namen und die Rohdaten des gewünschten Farbprofils angibt. |
| dw_flags | int | r/w | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der Farbprofil‑Flags enthält. |
| name | string | r | Liest den Namen |
| raw_data | System.Byte | r | Liest die Rohdaten |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfSetIcmProfileW(source) {#EmfSetIcmProfileW_source_1}


```
 EmfSetIcmProfileW(source) 
```

Initialisiert eine neue Instanz der [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/) Klasse.

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


