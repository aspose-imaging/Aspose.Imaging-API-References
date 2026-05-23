---
title: "EmfPolylineTo16 Clase"
type: docs
weight: 950
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---

**Summary:** The EMR_POLYLINETO16 record specifies one or more straight lines based upon the current position. <br/>            A line is drawn from the current position to the first point specified by the aPoints field by using the <br/>            current pen. For each additional line, drawing is performed from the ending point of the previous <br/>            line to the next point specified by aPoints.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolylineTo16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPolylineTo16()](#EmfPolylineTo16__1) | Inicializa una nueva instancia de la clase [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/). |
| [EmfPolylineTo16(source)](#EmfPolylineTo16_source_2) | Inicializa una nueva instancia de la clase [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece una matriz de objetos WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica los datos de los puntos, en unidades lógicas. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL de 128 bits ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo delimitador, en unidades del dispositivo. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolylineTo16() {#EmfPolylineTo16__1}


```
 EmfPolylineTo16() 
```

Inicializa una nueva instancia de la clase [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/).

### Constructor: EmfPolylineTo16(source) {#EmfPolylineTo16_source_2}


```
 EmfPolylineTo16(source) 
```

Inicializa una nueva instancia de la clase [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/).

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


