---
title: "Clase EmfEllipse"
type: docs
weight: 370
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/
---

**Summary:** The EMR_ELLIPSE record specifies an ellipse. The center of the ellipse is the center of the specified <br/>            bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEllipse

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfEllipse()](#EmfEllipse__1) | Inicializa una nueva instancia de la clase [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/). |
| [EmfEllipse(source)](#EmfEllipse_source_2) | Inicializa una nueva instancia de la clase [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto RectL de 128 bits (WMF), especificado en [MS-WMF] sección 2.2.2.19, que <br/>            especifica el rectángulo delimitador inclusivo-inclusivo. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEllipse() {#EmfEllipse__1}


```
 EmfEllipse() 
```

Inicializa una nueva instancia de la clase [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/).

### Constructor: EmfEllipse(source) {#EmfEllipse_source_2}


```
 EmfEllipse(source) 
```

Inicializa una nueva instancia de la clase [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/).

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


