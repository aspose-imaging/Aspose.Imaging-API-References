---
title: "Classe EmfSelectClipPath"
type: docs
weight: 1060
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---

**Summary:** The EMR_SELECTCLIPPATH record specifies the current path as a clipping region for a playback <br/>            device context, combining the new region with any existing clipping region using the specified mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectClipPath

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfSelectClipPath()](#EmfSelectClipPath__1) | Inizializza una nuova istanza della classe [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/). |
| [EmfSelectClipPath(source)](#EmfSelectClipPath_source_2) | Inizializza una nuova istanza della classe [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| region_mode | [EmfRegionMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il modo di utilizzare il percorso. Il <br/>            valore DEVE essere nell'enumerazione RegionMode (sezione 2.1.29). |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSelectClipPath() {#EmfSelectClipPath__1}


```
 EmfSelectClipPath() 
```

Inizializza una nuova istanza della classe [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/).

### Constructor: EmfSelectClipPath(source) {#EmfSelectClipPath_source_2}


```
 EmfSelectClipPath(source) 
```

Inizializza una nuova istanza della classe [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/).

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


