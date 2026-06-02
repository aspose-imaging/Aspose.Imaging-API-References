---
title: "EmfSetWindowOrgEx Classe"
type: docs
weight: 1360
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/
---

**Summary:** The EMR_SETWINDOWORGEX record defines the window origin.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWindowOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfSetWindowOrgEx()](#EmfSetWindowOrgEx__1) | Inizializza una nuova istanza della classe [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/). |
| [EmfSetWindowOrgEx(source)](#EmfSetWindowOrgEx_source_2) | Inizializza una nuova istanza della classe [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta un oggetto WMF PointL a 64 bit ([MS-WMF] sezione 2.2.2.15) che specifica l'origine orizzontale e verticale della finestra in unità logiche. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetWindowOrgEx() {#EmfSetWindowOrgEx__1}


```
 EmfSetWindowOrgEx() 
```

Inizializza una nuova istanza della classe [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/).

### Constructor: EmfSetWindowOrgEx(source) {#EmfSetWindowOrgEx_source_2}


```
 EmfSetWindowOrgEx(source) 
```

Inizializza una nuova istanza della classe [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/).

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


