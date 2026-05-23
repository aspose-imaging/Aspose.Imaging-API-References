---
title: "EmfMetafileHeaderExtension1 Klasse"
type: docs
weight: 620
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---

**Summary:** The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.<br/>            Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1

**Inheritance:** EmfMetafileHeader

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_1) | Initialisiert eine neue Instanz der Klasse [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_2) | Initialisiert eine neue Instanz der Klasse [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| emf_description | string | r/w | Liest oder setzt die EMF-Beschreibung<br/>            Eine optionale, nullterminierte Unicode UTF16-LE-Zeichenkette beliebiger Länge und Inhalts. <br/>            Ihr Speicherort im Datensatz und die Anzahl der Zeichen werden durch die Felder offDescription <br/>            und nDescription im EmfHeader angegeben. Wenn der Wert eines dieser Felder <br/>            null ist, ist keine Beschreibungszeichenkette vorhanden. |
| emf_description_buffer | System.Byte | r/w | Liest oder setzt den EMF-Beschreibungs-Puffer<br/>            Ein optionales Byte-Array, das die EMF-Beschreibungszeichenkette enthält, die <br/>            nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeader-<br/>            Datensatzes sein muss. Dementsprechend ist das Feld in diesem Puffer, das "UndefinedSpace" heißt, <br/>            optional und MUSS ignoriert werden. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Liest oder setzt ein Header-Objekt (Abschnitt 2.2.9), das Informationen über den Inhalt<br/>            und die Struktur der Metadatei enthält. |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | Liest oder setzt ein HeaderExtension1-Objekt, das zusätzliche Informationen über das Bild in der Metadatei angibt. |
| emf_header_record_buffer | System.Byte | r/w | Liest oder setzt ein optionales Byte-Array, das den Rest des EMF-Header-Datensatzes enthält. <br/>            Die Größe dieses Feldes MUSS ein Vielfaches von 4 Bytes sein. |
| emf_pixel_format_buffer | System.Byte | r/w | Liest oder setzt ein optionales Byte-Array, das den EMF-Pixel-Format-Deskriptor enthält, der nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeaderExtension1-Datensatzes oder mit der EMF-<br/>            Beschreibungszeichenkette sein muss. Dementsprechend ist das Feld in diesem Puffer, das "UndefinedSpace" heißt, <br/>            optional und MUSS ignoriert werden. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Initialisiert eine neue Instanz der Klasse [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | Initialisiert eine neue Instanz der Klasse [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [create_from_record(record)](#create_from_record_record_3) | Initialisiert eine neue Instanz der Klasse [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_4) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_1}


```
 EmfMetafileHeaderExtension1(header) 
```

Initialisiert eine neue Instanz der Klasse [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Der Header. |

### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_2}


```
 EmfMetafileHeaderExtension1(header) 
```

Initialisiert eine neue Instanz der Klasse [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | Der Header. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Initialisiert eine neue Instanz der Klasse [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Der Header. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

Initialisiert eine neue Instanz der Klasse [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | Der Header. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_3}


```
 create_from_record(record) 
```

Initialisiert eine neue Instanz der Klasse [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Der Datensatz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_4}


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


