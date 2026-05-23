---
title: "Classe EmfCommentMultiFormats"
type: docs
weight: 210
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---

**Summary:** The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentMultiFormats

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfCommentMultiFormats(source)](#EmfCommentMultiFormats_source_1) | Inizializza una nuova istanza della classe [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| a_formats | [EmfFormat[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/) | r/w | Ottiene o imposta un array di lunghezza CountFormats di formati grafici, specificati da <br/> oggetti EmrFormat (sezione 2.2.4), in ordine di preferenza |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento <br/>            come contenente dati pubblici. Il valore 0x43494447, che è la stringa ASCII "CIDG", identifica <br/>            questo come un record EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, dei campi <br/>            CommentIdentifier e CommentRecordParm nel campo RecordBuffer che <br/>            segue. NON DEVE includere la dimensione di se stesso né la dimensione del campo AlignmentPadding, se <br/>            presente. |
| format_data | System.Byte[] | r/w | Ottiene o imposta un array di byte a lunghezza variabile contenente i dati dell'immagine per tutti i formati grafici <br/> contenuti in questo record. <br/> La dimensione dei dati per ogni immagine è fornita dal campo DataSize nell'oggetto EmrFormat corrispondente. Pertanto, la dimensione totale di questo campo è la somma dei valori DataSize in tutti gli <br/> oggetti EmrFormat. <br/> Il formato grafico dei dati per ogni immagine è specificato dal campo Signature nell'oggetto EmrFormat corrispondente. |
| output_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il <br/> rettangolo di output, in coordinate logiche. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di <br/>            record di commento pubblico. Questo DOVREBBE essere uno dei valori elencati nella tabella precedente, che <br/>            sono specificati nell'enumerazione EmrComment (sezione 2.1.10), a meno che tipi aggiuntivi di <br/>            record di commento pubblico siano stati implementati sul server di stampa. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentMultiFormats(source) {#EmfCommentMultiFormats_source_1}


```
 EmfCommentMultiFormats(source) 
```

Inizializza una nuova istanza della classe [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/).

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


