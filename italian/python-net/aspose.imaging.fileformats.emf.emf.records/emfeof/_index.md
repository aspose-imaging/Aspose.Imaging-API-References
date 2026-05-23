---
title: "Classe EmfEof"
type: docs
weight: 390
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

**Summary:** The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfEof()](#EmfEof__1) | Inizializza una nuova istanza della classe [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/). |
| [EmfEof(record)](#EmfEof_record_2) | Inizializza una nuova istanza della classe [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| palette_argb_32_entries | int[] | r/w | Ottiene o imposta un buffer opzionale che contiene i dati della tavolozza, che non <br/> è necessario essere contiguo con la parte fissa del record EMR_EOF <br/> . Di conseguenza, i campi in questo buffer etichettati <br/> "UndefinedSpace" sono opzionali e MUST essere ignorati. <br/> La dimensione di questo campo MUST essere un multiplo di 4 byte. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| size_last | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che MUST essere uguale a Size e MUST essere l'ultimo <br/> campo del record e quindi del metafile. Gli oggetti LogPaletteEntry, se presenti, MUST precedere questo campo. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

Inizializza una nuova istanza della classe [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/).

### Constructor: EmfEof(record) {#EmfEof_record_2}


```
 EmfEof(record) 
```

Inizializza una nuova istanza della classe [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Il record. |

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


