---
title: "EmfCommentMultiFormats klass"
type: docs
weight: 210
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---

**Summary:** The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentMultiFormats

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCommentMultiFormats(source)](#EmfCommentMultiFormats_source_1) | Initierar en ny instans av [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_formats | [EmfFormat[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/) | r/w | Hämtar eller anger en CountFormats‑längd array av grafikformat, specificerade av <br/>            EmrFormat‑objekt (avsnitt 2.2.4), i prioritetsordning |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar detta kommentarsregister <br/>            som specificerar offentliga data. Värdet 0x43494447, som är ASCII-strängen "CIDG", identifierar <br/>            detta som ett EMR_COMMENT_PUBLIC-register. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för fälten CommentIdentifier och CommentRecordParm i RecordBuffer-fältet som <br/>            följer. Det FÅR INTE inkludera sin egen storlek eller storleken på AlignmentPadding-fältet, om <br/>            närvarande |
| format_data | System.Byte[] | r/w | Hämtar eller anger en variabel‑längd array av byte för bilddata för alla grafikformat <br/>            som finns i denna post. <br/>            Storleken på data för varje bild tillhandahålls av DataSize‑fältet i motsvarande <br/>            EmrFormat‑objekt. Således är den totala storleken på detta fält summan av DataSize‑värdena i alla <br/>            EmrFormat‑objekt. <br/>            Grafikformatet för data för varje bild specificeras av Signature‑fältet i det <br/>            motsvarande EmrFormat‑objektet. |
| output_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL‑objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar <br/>            utdatarektangeln i logiska koordinater. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar typen av <br/>            offentligt kommentarsregister. Detta BÖR vara ett av värdena som listas i föregående tabell, vilka <br/>            är specificerade i EmrComment‑enumerationen (avsnitt 2.1.10), såvida inte ytterligare offentliga <br/>            kommentarsregistertyper har implementerats på utskriftsservern. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentMultiFormats(source) {#EmfCommentMultiFormats_source_1}


```
 EmfCommentMultiFormats(source) 
```

Initierar en ny instans av [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/) klass.

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


