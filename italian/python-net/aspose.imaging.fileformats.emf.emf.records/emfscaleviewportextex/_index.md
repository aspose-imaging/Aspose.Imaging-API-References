---
title: "Classe EmfScaleViewportExtex"
type: docs
weight: 1040
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---

**Summary:** The EMR_SCALEVIEWPORTEXTEX record respecifies the viewport for a device context by using the<br/>            ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleViewportExtex

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex__1) | Inizializza una nuova istanza della classe [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/). |
| [EmfScaleViewportExtex(source)](#EmfScaleViewportExtex_source_2) | Inizializza una nuova istanza della classe [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
| x_denom | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il divisore orizzontale. Non può essere zero. |
| x_num | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicatore orizzontale. Non può essere zero. |
| y_denom | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il divisore verticale. Non può essere zero. |
| y_num | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicatore verticale. Non può essere zero. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfScaleViewportExtex() {#EmfScaleViewportExtex__1}


```
 EmfScaleViewportExtex() 
```

Inizializza una nuova istanza della classe [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/).

### Constructor: EmfScaleViewportExtex(source) {#EmfScaleViewportExtex_source_2}


```
 EmfScaleViewportExtex(source) 
```

Inizializza una nuova istanza della classe [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/).

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


