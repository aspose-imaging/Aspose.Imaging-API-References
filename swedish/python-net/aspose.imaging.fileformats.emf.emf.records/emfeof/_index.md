---
title: "EmfEof klass"
type: docs
weight: 390
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

**Summary:** The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfEof()](#EmfEof__1) | Initierar en ny instans av [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) klass. |
| [EmfEof(record)](#EmfEof_record_2) | Initierar en ny instans av [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| palette_argb_32_entries | int[] | r/w | Hämtar eller anger en valfri buffer som innehåller palettdata, som inte <br/>            krävs vara sammanhängande med den fasta delen av EMR_EOF <br/>            posten. Följaktligen är fält i denna buffer som är märkta <br/>            "UndefinedSpace" valfria och MÅSTE ignoreras. <br/>            Storleken på detta fält MÅSTE vara en multipel av 4 byte |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| size_last | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som MÅSTE vara samma som Size och MÅSTE vara det sista <br/>            fältet i posten och därmed metafilen. LogPaletteEntry‑objekt, om de <br/>            finns, MÅSTE föregå detta fält. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

Initierar en ny instans av [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) klass.

### Constructor: EmfEof(record) {#EmfEof_record_2}


```
 EmfEof(record) 
```

Initierar en ny instans av [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Posten. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


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


