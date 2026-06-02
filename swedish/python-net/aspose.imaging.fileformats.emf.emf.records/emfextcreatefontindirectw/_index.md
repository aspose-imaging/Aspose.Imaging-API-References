---
title: "EmfExtCreateFontIndirectW-klass"
type: docs
weight: 420
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---

**Summary:** The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreateFontIndirectW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW__1) | Initierar en ny instans av klassen [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/). |
| [EmfExtCreateFontIndirectW(source)](#EmfExtCreateFontIndirectW_source_2) | Initierar en ny instans av klassen [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| elw | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | r/w | Hämtar eller anger ett LogFontExDv-objekt (avsnitt 2.2.15), som specificerar det logiska teckensnittet. Ett<br/>            LogFont-objekt 2.2.13 KAN finnas istället.[90]Processen för att bestämma typen av<br/>            objekt i detta fält beskrivs nedan. |
| ih_fonts | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska teckensnittobjektet<br/>            i EMF-objektabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan<br/>            återanvändas eller modifieras. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW__1}


```
 EmfExtCreateFontIndirectW() 
```

Initierar en ny instans av klassen [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/).

### Constructor: EmfExtCreateFontIndirectW(source) {#EmfExtCreateFontIndirectW_source_2}


```
 EmfExtCreateFontIndirectW(source) 
```

Initierar en ny instans av klassen [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/).

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


