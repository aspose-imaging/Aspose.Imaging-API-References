---
title: "Clase EmfPie"
type: docs
weight: 730
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/
---

**Summary:** The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two <br/>            radials. The pie is outlined by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPie

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPie()](#EmfPie__1) | Inicializa una nueva instancia de la clase [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
| [EmfPie(source)](#EmfPie_source_2) | Inicializa una nueva instancia de la clase [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, que <br/>            especifica el rectángulo delimitador inclusivo-inclusivo. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece un objeto PointL de 64 bits que especifica las coordenadas, en unidades lógicas, del <br/>            punto final del segundo radial. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece objetos WMF PointL de 64 bits, especificados en la sección [MS-WMF] 2.2.2.15, que <br/>            especifican las coordenadas, en unidades lógicas, del punto final del primer radial. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPie() {#EmfPie__1}


```
 EmfPie() 
```

Inicializa una nueva instancia de la clase [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

### Constructor: EmfPie(source) {#EmfPie_source_2}


```
 EmfPie(source) 
```

Inicializa una nueva instancia de la clase [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

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


