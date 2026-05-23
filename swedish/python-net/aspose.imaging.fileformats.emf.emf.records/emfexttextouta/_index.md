---
title: "EmfExtTextOutA-klass"
type: docs
weight: 470
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---

**Summary:** The EMR_EXTTEXTOUTA record draws an ASCII text string using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtTextOutA

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfExtTextOutA()](#EmfExtTextOutA__1) | Initierar en ny instans av klassen [EmfExtTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/) klass. |
| [EmfExtTextOutA(source)](#EmfExtTextOutA_source_2) | Initierar en ny instans av klassen [EmfExtTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_emr_text | [EmfText](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | Hämtar eller anger ett EmrText-objekt (avsnitt 2.2.5) som specificerar utskriftssträngen i 8-bitars <br/>            ASCII-tecken, textattribut och avståndsvärden. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19). Det används inte och <br/>            MÅSTE ignoreras vid mottagning. |
| ex_scale | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn att tillämpa längs <br/>            X-axeln för att konvertera från sidrymdsenheter till .01 mm-enheter. Detta BÖR endast användas om <br/>            grafikläget som anges av iGraphicsMode är GM_COMPATIBLE. |
| ey_scale | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn att tillämpa längs <br/>            Y-axeln för att konvertera från sidrymdsenheter till .01 mm-enheter. Detta BÖR endast användas om <br/>            grafikläget som anges av iGraphicsMode är GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget från <br/>            GraphicsMode‑enumerationen (avsnitt 2.1.16). |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtTextOutA() {#EmfExtTextOutA__1}


```
 EmfExtTextOutA() 
```

Initierar en ny instans av klassen [EmfExtTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/) klass.

### Constructor: EmfExtTextOutA(source) {#EmfExtTextOutA_source_2}


```
 EmfExtTextOutA(source) 
```

Initierar en ny instans av klassen [EmfExtTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/) klass.

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


