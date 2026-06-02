---
title: "EmfMetafileHeader klass"
type: docs
weight: 610
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---

**Summary:** The EMR_HEADER record types define the starting points of EMF metafiles<br/>            and specify properties of the device on which the image in the metafile<br/>            was created. The information in the header record makes it possible for<br/>            EMF metafiles to be independent of any specific output device.<br/>            The value of the Size field can be used to distinguish between the different<br/>            EMR_HEADER record types listed earlier in this section.<br/>            There are three possible headers:<br/>            The base header, which is the EmfMetafileHeader record.<br/>            The fixed-size part of this header is 88 bytes, and it contains a Header object.<br/>            The first extension header, which is the EmfMetafileHeaderExtension1 record.<br/>            The fixed-size part of this header is 100 bytes, and it contains a Header object<br/>            and a HeaderExtension1 object (section 2.2.10).<br/>            The second extension header, which is the EmfMetafileHeaderExtension2 record.<br/>            The fixed-size part of this header is 108 bytes, and it contains a Header object,<br/>            a HeaderExtension1 object, and a HeaderExtension2 object (section 2.2.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfMetafileHeader()](#EmfMetafileHeader__1) | Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [EmfMetafileHeader(header)](#EmfMetafileHeader_header_2) | Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [EmfMetafileHeader(record)](#EmfMetafileHeader_record_3) | Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| emf_beskrivning | string | r/w | Hämtar eller anger EMF‑beskrivningen<br/>            En valfri, null‑terminerad Unicode UTF16‑LE‑sträng med godtycklig längd och innehåll. <br/>            Dess plats i posten och antalet tecken anges av fälten offDescription <br/>            och nDescription, respektive, i EmfHeader. Om värdet för något av fälten <br/>            är noll, finns ingen beskrivningssträng. |
| emf_description_buffer | System.Byte | r/w | Hämtar eller anger EMF‑beskrivningsbufferten<br/>            En valfri byte‑array som innehåller EMF‑beskrivningssträngen, vilken <br/>            inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeader <br/>            posten. Följaktligen är fältet i denna buffer som är märkt "UndefinedSpace" <br/>            valfritt och MÅSTE ignoreras. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Hämtar eller anger ett Header‑objekt (avsnitt 2.2.9), som innehåller information om innehållet<br/>            och strukturen för metafilen |
| emf_header_record_buffer | System.Byte | r/w | Hämtar eller anger en valfri byte‑array som innehåller resten av EMF‑header‑posten. <br/>            Storleken på detta fält MÅSTE vara en multipel av 4 byte |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_record(record)](#create_from_record_record_2) | Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_3) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeader() {#EmfMetafileHeader__1}


```
 EmfMetafileHeader() 
```

Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

### Constructor: EmfMetafileHeader(header) {#EmfMetafileHeader_header_2}


```
 EmfMetafileHeader(header) 
```

Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Headern. |

### Constructor: EmfMetafileHeader(record) {#EmfMetafileHeader_record_3}


```
 EmfMetafileHeader(record) 
```

Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Posten. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Initierar en ny instans av klassen [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Headern. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_2}


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


### Method: create_from_type(type)  [static] {#create_from_type_type_3}


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


