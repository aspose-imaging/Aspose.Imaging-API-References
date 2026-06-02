---
title: "EmfPolygon16 Classe"
type: docs
weight: 910
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/
---

**Summary:** The EMR_POLYGON16 record specifies a polygon consisting of two or more vertexes connected by <br/>            straight lines. The polygon is outlined by using the current pen and filled by using the current brush <br/>            and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolygon16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPolygon16()](#EmfPolygon16__1) | Inizializza una nuova istanza della [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) classe. |
| [EmfPolygon16(source)](#EmfPolygon16_source_2) | Inizializza una nuova istanza della [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) classe. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta un array di oggetti WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica i dati dei punti, in unità logiche. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di delimitazione, in unità del dispositivo. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolygon16() {#EmfPolygon16__1}


```
 EmfPolygon16() 
```

Inizializza una nuova istanza della [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) classe.

### Constructor: EmfPolygon16(source) {#EmfPolygon16_source_2}


```
 EmfPolygon16(source) 
```

Inizializza una nuova istanza della [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) classe.

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


