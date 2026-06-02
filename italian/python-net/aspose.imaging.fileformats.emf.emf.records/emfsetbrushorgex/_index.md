---
title: "EmfSetBrushOrgEx Classe"
type: docs
weight: 1120
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/
---

**Summary:** The EMR_SETBRUSHORGEX record specifies the origin of the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBrushOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfSetBrushOrgEx()](#EmfSetBrushOrgEx__1) | Inizializza una nuova istanza della classe [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/). |
| [EmfSetBrushOrgEx(source)](#EmfSetBrushOrgEx_source_2) | Inizializza una nuova istanza della classe [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato nella sezione [MS-WMF] 2.2.2.15, che<br/>            specifica l'origine orizzontale e verticale del pennello in unità dispositivo. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetBrushOrgEx() {#EmfSetBrushOrgEx__1}


```
 EmfSetBrushOrgEx() 
```

Inizializza una nuova istanza della classe [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/).

### Constructor: EmfSetBrushOrgEx(source) {#EmfSetBrushOrgEx_source_2}


```
 EmfSetBrushOrgEx(source) 
```

Inizializza una nuova istanza della classe [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/).

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


