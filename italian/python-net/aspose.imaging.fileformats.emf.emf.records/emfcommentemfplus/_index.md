---
title: "Classe EmfCommentEmfPlus"
type: docs
weight: 180
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---

**Summary:** The EMR_COMMENT_EMFPLUS record contains embedded EMF+ records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfPlus

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfCommentEmfPlus(source)](#EmfCommentEmfPlus_source_1) | Inizializza una nuova istanza della classe [EmfCommentEmfPlus](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento <br/>            come contenente record EMF+. Il valore 0x2B464D45, che è la stringa ASCII "+FME", <br/>            identifica questo come un record EMR_COMMENT_EMFPLUS. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, dei campi <br/>            CommentIdentifier e CommentRecordParm nel campo RecordBuffer che <br/>            segue. NON DEVE includere la dimensione di se stesso né la dimensione del campo AlignmentPadding, se <br/>            presente. |
| emf_plus_records | [EmfPlusRecord[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | r/w | Ottiene o imposta un array di byte che contiene uno o più record EMF+ ([MS-EMFPLUS] sezione 2.3.1). |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentEmfPlus(source) {#EmfCommentEmfPlus_source_1}


```
 EmfCommentEmfPlus(source) 
```

Inizializza una nuova istanza della classe [EmfCommentEmfPlus](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La sorgente. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La sorgente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Il tipo di record. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


