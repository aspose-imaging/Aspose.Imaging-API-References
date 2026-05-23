---
title: "Classe EmfPie"
type: docs
weight: 730
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/
---

**Summary:** The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two <br/>            radials. The pie is outlined by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPie

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPie()](#EmfPie__1) | Inizializza una nuova istanza della classe [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
| [EmfPie(source)](#EmfPie_source_2) | Inizializza una nuova istanza della classe [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che <br/>            specifica il rettangolo di delimitazione inclusive-inclusive. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta un oggetto PointL a 64 bit che specifica le coordinate, in unità logiche, del <br/>            punto finale del secondo raggio. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta oggetti WMF PointL a 64 bit, specificati in [MS-WMF] sezione 2.2.2.15, che <br/>            specificano le coordinate, in unità logiche, del punto finale del primo raggio. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPie() {#EmfPie__1}


```
 EmfPie() 
```

Inizializza una nuova istanza della classe [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

### Constructor: EmfPie(source) {#EmfPie_source_2}


```
 EmfPie(source) 
```

Inizializza una nuova istanza della classe [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

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


