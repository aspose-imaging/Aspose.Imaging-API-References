---
title: "Clase EmfPolyDraw"
type: docs
weight: 800
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---

**Summary:** The EMR_POLYDRAW record specifies a set of line segments and Bezier curves.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyDraw

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPolyDraw()](#EmfPolyDraw__1) | Inicializa una nueva instancia de la clase [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/). |
| [EmfPolyDraw(source)](#EmfPolyDraw_source_2) | Inicializa una nueva instancia de la clase [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece una matriz de objetos WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica los datos de los puntos, en unidades lógicas. |
| ab_types | [EmfPointEnum[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/) | r/w | Obtiene o establece una matriz de valores byte de longitud Count que especifica cómo se usa cada punto en el <br/>            Obtiene o establece la matriz aPoints. Este valor DEBE estar en la enumeración Point (sección 2.1.26). |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL de 128 bits ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo delimitador, en unidades del dispositivo. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyDraw() {#EmfPolyDraw__1}


```
 EmfPolyDraw() 
```

Inicializa una nueva instancia de la clase [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/).

### Constructor: EmfPolyDraw(source) {#EmfPolyDraw_source_2}


```
 EmfPolyDraw(source) 
```

Inicializa una nueva instancia de la clase [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/).

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


