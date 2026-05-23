---
title: "EmfColorMatchToTargetW Klasse"
type: docs
weight: 150
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---

**Summary:** The EMR_COLORMATCHTOTargetW record specifies whether to perform color matching with a color<br/>            profile that is specified in a file with a name consisting of Unicode characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfColorMatchToTargetW

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfColorMatchToTargetW(source)](#EmfColorMatchToTargetW_source_1) | Initialisiert eine neue Instanz der [EmfColorMatchToTargetW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Rohdaten des Ziel‑<br/>            Farbprofils angibt, falls sie im Datenfeld enthalten ist. |
| cb_name | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes im Unicode‑<br/>            UTF16‑LE‑Namen des gewünschten Farbprofils angibt. |
| Daten | System.Byte | r/w | Liest oder schreibt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE<br/>            Namen und die Rohdaten des gewünschten Farbprofils angibt. |
| dw_action | [EmfColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/) | r/w | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Wert aus der ColorSpace‑<br/>            Aufzählung (Abschnitt 2.1.7) angibt. |
| dw_flags | [EmfColorMatchToTarget](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcolormatchtotarget/) | r/w | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die einen Wert aus der<br/>            ColorMatchToTarget‑Aufzählung (Abschnitt 2.1.6) angibt. |
| name | string | r | Liest den Namen |
| raw_data | System.Byte | r | Liest die Rohdaten |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfColorMatchToTargetW(source) {#EmfColorMatchToTargetW_source_1}


```
 EmfColorMatchToTargetW(source) 
```

Initialisiert eine neue Instanz der [EmfColorMatchToTargetW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/) Klasse.

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


