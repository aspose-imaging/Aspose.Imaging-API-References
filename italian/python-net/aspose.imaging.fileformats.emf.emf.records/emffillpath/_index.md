---
title: "EmfFillPath Classe"
type: docs
weight: 490
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/
---

**Summary:** The EMR_FILLPATH record closes any open figures in the current path and fills the path's interior by <br/>            using the current brush and polygon-filling mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFillPath

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfFillPath()](#EmfFillPath__1) | Inizializza una nuova istanza della classe [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/). |
| [EmfFillPath(source)](#EmfFillPath_source_2) | Inizializza una nuova istanza della classe [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato nella sezione [MS-WMF] 2.2.2.19, <br/>            che specifica il rettangolo di delimitazione, in unità dispositivo. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfFillPath() {#EmfFillPath__1}


```
 EmfFillPath() 
```

Inizializza una nuova istanza della classe [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/).

### Constructor: EmfFillPath(source) {#EmfFillPath_source_2}


```
 EmfFillPath(source) 
```

Inizializza una nuova istanza della classe [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/).

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


