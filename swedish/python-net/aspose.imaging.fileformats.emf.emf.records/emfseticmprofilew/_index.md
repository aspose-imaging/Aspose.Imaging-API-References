---
title: "EmfSetIcmProfileW klass"
type: docs
weight: 1180
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---

**Summary:** The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of<br/>            Unicode characters, for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileW

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetIcmProfileW(source)](#EmfSetIcmProfileW_source_1) | Initierar en ny instans av klassen [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken på färgprofildata, om bifogad. |
| cb_name | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte i den Unicode‑<br/>            UTF16‑LE‑namnet för den önskade färgprofilen. |
| data | System.Byte | r/w | Hämtar eller anger en array med storlek (cbName + cbData) i byte, som specificerar UTF16-LE<br/>            namn och rådata för den önskade färgprofilen. |
| dw_flags | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som innehåller flaggor för färgprofilen. |
| namn | string | r | Hämtar namnet |
| raw_data | System.Byte | r | Hämtar rådata |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetIcmProfileW(source) {#EmfSetIcmProfileW_source_1}


```
 EmfSetIcmProfileW(source) 
```

Initierar en ny instans av klassen [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

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


