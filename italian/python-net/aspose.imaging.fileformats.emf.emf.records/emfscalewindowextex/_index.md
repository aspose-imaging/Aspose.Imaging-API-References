---
title: "Classe EmfScaleWindowExtex"
type: docs
weight: 1050
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---

**Summary:** The EMR_SCALEWINDOWEXTEX record respecifies the window for a playback device context by<br/>            using the ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleWindowExtex

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex__1) | Inizializza una nuova istanza della classe [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/). |
| [EmfScaleWindowExtex(source)](#EmfScaleWindowExtex_source_2) | Inizializza una nuova istanza della classe [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
| x_denom | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il divisore orizzontale. MUST NOT be zero. |
| x_num | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicatore orizzontale. MUST NOT be zero. |
| y_denom | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il divisore verticale. NON DEVE essere zero. |
| y_num | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicatore verticale. NON DEVE essere zero. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfScaleWindowExtex() {#EmfScaleWindowExtex__1}


```
 EmfScaleWindowExtex() 
```

Inizializza una nuova istanza della classe [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/).

### Constructor: EmfScaleWindowExtex(source) {#EmfScaleWindowExtex_source_2}


```
 EmfScaleWindowExtex(source) 
```

Inizializza una nuova istanza della classe [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/).

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


