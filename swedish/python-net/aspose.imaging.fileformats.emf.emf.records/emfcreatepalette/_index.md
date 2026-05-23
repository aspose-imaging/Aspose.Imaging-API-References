---
title: "EmfCreatePalette klass"
type: docs
weight: 310
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---

**Summary:** The EMR_CREATEPALETTE record defines a logical palette for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePalette

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreatePalette(source)](#EmfCreatePalette_source_1) | Initierar en ny instans av klassen [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_pal | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för det logiska palettobjektet<br/>            i EMF‑objektabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan<br/>            återanvändas eller modifieras. |
| log_palette | [EmfLogPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpalette/) | r/w | Hämtar eller anger ett LogPalette‑objekt (avsnitt 2.2.17). Version‑fältet i detta objekt<br/>            MÅSTE sättas till 0x0300. Om NumberOfEntries‑värdet i detta objekt är noll, måste bearbetning av<br/>            denna post MISSLYCKAS. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreatePalette(source) {#EmfCreatePalette_source_1}


```
 EmfCreatePalette(source) 
```

Initierar en ny instans av klassen [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/) klass.

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


