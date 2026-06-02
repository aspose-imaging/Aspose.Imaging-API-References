---
title: "EmfCommentWindowsMetaFile-klass"
type: docs
weight: 240
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---

**Summary:** The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentWindowsMetaFile

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCommentWindowsMetaFile(source)](#EmfCommentWindowsMetaFile_source_1) | Initierar en ny instans av klassen [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| kontrollsumma | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar kontrollsumman för denna post. |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar detta kommentarsregister <br/>            som specificerar offentliga data. Värdet 0x43494447, som är ASCII-strängen "CIDG", identifierar <br/>            detta som ett EMR_COMMENT_PUBLIC-register. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för fälten CommentIdentifier och CommentRecordParm i RecordBuffer-fältet som <br/>            följer. Det FÅR INTE inkludera sin egen storlek eller storleken på AlignmentPadding-fältet, om <br/>            närvarande |
| flaggor | int | r/w | Hämtar eller anger ett 32-bitars värde som MÅSTE vara 0x00000000 och MÅSTE ignoreras. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som identifierar typen av <br/>            offentligt kommentarsregister. Detta BÖR vara ett av värdena som listas i föregående tabell, vilka <br/>            är specificerade i EmrComment‑enumerationen (avsnitt 2.1.10), såvida inte ytterligare offentliga <br/>            kommentarsregistertyper har implementerats på utskriftsservern. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
| version | [WmfMetafileVersion](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileversion/) | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar WMF-metafils version i termer <br/>            av stöd för enhetsoberoende bitmaps (DIBs), från WMF MetafileVersion-<br/>            uppräkningen ([MS-WMF] avsnitt 2.1.1.19). |
| win_metafile | [MetaImage](/imaging/python-net/aspose.imaging.fileformats.emf/metaimage/) | r/w | Hämtar eller anger en buffert som innehåller WMF-metafilen. |
| win_metafile_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för <br/>            WMF-metafilen i WinMetafile-fältet. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentWindowsMetaFile(source) {#EmfCommentWindowsMetaFile_source_1}


```
 EmfCommentWindowsMetaFile(source) 
```

Initierar en ny instans av klassen [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/).

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


