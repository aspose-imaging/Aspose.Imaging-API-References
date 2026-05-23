---
title: "EmfNamedEscape klass"
type: docs
weight: 660
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---

**Summary:** The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfNamedEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfNamedEscape(source)](#EmfNamedEscape_source_1) | Initierar en ny instans av klassen [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cj_driver | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte i <br/>            DriverName‑fältet. Detta värde MÅSTE vara ett jämnt tal. |
| cj_in | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen. |
| data | System.Byte | r/w | Hämtar eller anger data som ska skickas till skrivardrivrutinen. Det MÅSTE finnas cjIn byte tillgängliga. |
| driver_name | string | r/w | Hämtar eller anger en sträng med 16-bitars Unicode-tecken som specificerar namnet på<br/>            skrivardrivrutinen som kommer att ta emot data. Detta värde MÅSTE vara cjDriver byte långt, och det MÅSTE<br/>            avslutas med ett null-tecken. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar skrivardrivrutinens escape‑funktion att<br/>            utföra. Detta MÅSTE vara ett av värdena i WMF MetafileEscapes enumeration ([MSWMF] avsnitt 2.1.1.17). |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfNamedEscape(source) {#EmfNamedEscape_source_1}


```
 EmfNamedEscape(source) 
```

Initierar en ny instans av klassen [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/).

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


