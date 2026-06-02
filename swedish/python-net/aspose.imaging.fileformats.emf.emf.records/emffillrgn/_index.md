---
title: "EmfFillRgn klass"
type: docs
weight: 500
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---

**Summary:** The EMR_FILLRGN record fills the specified region by using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFillRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfFillRgn()](#EmfFillRgn__1) | Initierar en ny instans av klassen [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/). |
| [EmfFillRgn(source)](#EmfFillRgn_source_2) | Initierar en ny instans av klassen [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, <br/>            som specificerar den omgivande rektangeln. |
| ih_brush | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet i brush EMF Object Table <br/>            för att fylla regionen. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | Hämtar eller anger en array av byte med längden RgnDataSize som innehåller ett RegionData-objekt (avsnitt 2.2.24). |
| rgn_data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på regiondata, i byte. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfFillRgn() {#EmfFillRgn__1}


```
 EmfFillRgn() 
```

Initierar en ny instans av klassen [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/).

### Constructor: EmfFillRgn(source) {#EmfFillRgn_source_2}


```
 EmfFillRgn(source) 
```

Initierar en ny instans av klassen [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/).

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


