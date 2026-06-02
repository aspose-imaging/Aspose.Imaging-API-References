---
title: "EmfMoveToEx Classe"
type: docs
weight: 650
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/
---

**Summary:** The EMR_MOVETOEX record specifies coordinates of the new current position, in logical units.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMoveToEx

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfMoveToEx()](#EmfMoveToEx__1) | Inizializza una nuova istanza della classe [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/). |
| [EmfMoveToEx(record)](#EmfMoveToEx_record_2) | Inizializza una nuova istanza della classe [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| offset | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato nella sezione [MS-WMF] 2.2.2.15, <br/>            che specifica le coordinate della nuova posizione corrente in unità logiche. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMoveToEx() {#EmfMoveToEx__1}


```
 EmfMoveToEx() 
```

Inizializza una nuova istanza della classe [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/).

### Constructor: EmfMoveToEx(record) {#EmfMoveToEx_record_2}


```
 EmfMoveToEx(record) 
```

Inizializza una nuova istanza della classe [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/).

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


