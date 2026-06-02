---
title: "EmfMetafileHeaderExtension1-klass"
type: docs
weight: 620
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---

**Summary:** The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.<br/>            Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1

**Inheritance:** EmfMetafileHeader

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_1) | Initierar en ny instans av klassen [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) klass. |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_2) | Initierar en ny instans av klassen [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| emf_beskrivning | string | r/w | Hämtar eller anger EMF‑beskrivningen<br/>            En valfri, null‑terminerad Unicode UTF16‑LE‑sträng med godtycklig längd och innehåll. <br/>            Dess plats i posten och antalet tecken anges av fälten offDescription <br/>            och nDescription, respektive, i EmfHeader. Om värdet för något av fälten <br/>            är noll, finns ingen beskrivningssträng. |
| emf_description_buffer | System.Byte | r/w | Hämtar eller anger EMF‑beskrivningsbufferten<br/>            En valfri byte‑array som innehåller EMF‑beskrivningssträngen, vilken <br/>            inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeader <br/>            posten. Följaktligen är fältet i denna buffer som är märkt "UndefinedSpace" <br/>            valfritt och MÅSTE ignoreras. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Hämtar eller anger ett Header‑objekt (avsnitt 2.2.9), som innehåller information om innehållet<br/>            och strukturen för metafilen |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | Hämtar eller anger ett HeaderExtension1‑objekt, som specificerar ytterligare information om bilden i metafilen. |
| emf_header_record_buffer | System.Byte | r/w | Hämtar eller anger en valfri byte‑array som innehåller resten av EMF‑header‑posten. <br/>            Storleken på detta fält MÅSTE vara en multipel av 4 byte |
| emf_pixel_format_buffer | System.Byte | r/w | Hämtar eller anger en valfri byte‑array som innehåller EMF‑pixelformat‑beskrivaren, vilken inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeaderExtension1‑posten eller med EMF‑beskrivningssträngen. Följaktligen är fältet i denna buffer som är märkt "UndefinedSpace" valfritt och MÅSTE ignoreras |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Initierar en ny instans av klassen [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) klass. |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | Initierar en ny instans av klassen [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) klass. |
| [create_from_record(record)](#create_from_record_record_3) | Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_4) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_1}


```
 EmfMetafileHeaderExtension1(header) 
```

Initierar en ny instans av klassen [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Headern. |

### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_2}


```
 EmfMetafileHeaderExtension1(header) 
```

Initierar en ny instans av klassen [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | Headern. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Initierar en ny instans av klassen [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Headern. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

Initierar en ny instans av klassen [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | Headern. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_3}


```
 create_from_record(record) 
```

Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Posten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_4}


```
 create_from_type(type) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Posttypen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


