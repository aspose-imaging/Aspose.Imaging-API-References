---
title: "Clase EmfChord"
type: docs
weight: 110
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---

**Summary:** The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an <br/>            ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled <br/>            by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfChord

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfChord()](#EmfChord__1) | Inicializa una nueva instancia de la clase [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
| [EmfChord(source)](#EmfChord_source_2) | Inicializa una nueva instancia de la clase [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que <br/>            especifica el rectángulo delimitador inclusivo-inclusivo. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece un objeto WMF PointL de 64 bits que especifica las coordenadas lógicas del <br/>            punto final del radial que define el final del acorde. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en [MS-WMF] sección 2.2.2.15, que <br/>            especifica las coordenadas lógicas del punto final del radial que define el comienzo del acorde. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfChord() {#EmfChord__1}


```
 EmfChord() 
```

Inicializa una nueva instancia de la clase [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

### Constructor: EmfChord(source) {#EmfChord_source_2}


```
 EmfChord(source) 
```

Inicializa una nueva instancia de la clase [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La fuente. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | El tipo de registro. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


