---
title: "EmfSetColorAdjustment Class"
type: docs
weight: 1130
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---

**Summary:** The EMR_SETCOLORADJUSTMENT record specifies color adjustment properties in the playback<br/>            device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetColorAdjustment

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfSetColorAdjustment(source)](#EmfSetColorAdjustment_source_1) | Inizializza una nuova istanza della classe [EmfSetColorAdjustment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| color_adjustment | [EmfColorAdjustment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/) | r/w | Ottiene o imposta un oggetto ColorAdjustment (sezione 2.2.2) che specifica i valori di regolazione del colore<br/>            . |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetColorAdjustment(source) {#EmfSetColorAdjustment_source_1}


```
 EmfSetColorAdjustment(source) 
```

Inizializza una nuova istanza della classe [EmfSetColorAdjustment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/).

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


