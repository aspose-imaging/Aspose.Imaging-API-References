---
title: "EmfGlsRecord Klasse"
type: docs
weight: 550
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---

**Summary:** The EMR_GLSRECORD record specifies an OpenGL function.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGlsRecord

**Inheritance:** EmfOpenGlRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfGlsRecord(source)](#EmfGlsRecord_source_1) | Initialisiert eine neue Instanz der Klasse [EmfGlsRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe, in Bytes, des Datenfeldes angibt.<br/>            Wenn dieser Wert null ist, werden keine Daten an diesen Datensatz angehängt. |
| Daten | System.Byte | r/w | Liest oder schreibt ein optionales Byte‑Array der Länge cbData, das Daten für die OpenGL‑Funktion angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfGlsRecord(source) {#EmfGlsRecord_source_1}


```
 EmfGlsRecord(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfGlsRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/).

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


