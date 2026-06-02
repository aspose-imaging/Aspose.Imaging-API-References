---
title: "EmfRestoreDc klass"
type: docs
weight: 1000
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---

**Summary:** The EMR_RESTOREDC record restores the playback device context to the specified state. The<br/>            playback device context is restored by popping state information off a stack that was created by<br/>            prior EMR_SAVEDC records (section 2.3.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRestoreDc

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRestoreDc()](#EmfRestoreDc__1) | Initierar en ny instans av klassen [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/). |
| [EmfRestoreDc(source)](#EmfRestoreDc_source_2) | Initierar en ny instans av klassen [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| saved_dc | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar det sparade tillståndet att återställa relativt till<br/>            det aktuella tillståndet. Detta värde MÅSTE vara negativt; –1 representerar det tillstånd som senast<br/>            sparades på stacken, –2 det föregående, osv. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfRestoreDc() {#EmfRestoreDc__1}


```
 EmfRestoreDc() 
```

Initierar en ny instans av klassen [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/).

### Constructor: EmfRestoreDc(source) {#EmfRestoreDc_source_2}


```
 EmfRestoreDc(source) 
```

Initierar en ny instans av klassen [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/).

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


