---
title: "Classe EmfChord"
type: docs
weight: 110
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---

**Summary:** The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an <br/>            ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled <br/>            by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfChord

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfChord()](#EmfChord__1) | Inizializza una nuova istanza della classe [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
| [EmfChord(source)](#EmfChord_source_2) | Inizializza una nuova istanza della classe [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che <br/>            specifica il rettangolo di delimitazione inclusive-inclusive. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta un oggetto PointL WMF a 64 bit che specifica le coordinate logiche del <br/>            punto finale del raggio che definisce la fine della corda. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta un oggetto PointL WMF a 64 bit, specificato in [MS-WMF] sezione 2.2.2.15, che <br/>            specifica le coordinate logiche del punto finale del raggio che definisce l'inizio della corda. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfChord() {#EmfChord__1}


```
 EmfChord() 
```

Inizializza una nuova istanza della classe [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

### Constructor: EmfChord(source) {#EmfChord_source_2}


```
 EmfChord(source) 
```

Inizializza una nuova istanza della classe [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

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


