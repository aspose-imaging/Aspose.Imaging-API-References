---
title: "Clase EmfFillRgn"
type: docs
weight: 500
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---

**Summary:** The EMR_FILLRGN record fills the specified region by using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFillRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfFillRgn()](#EmfFillRgn__1) | Inicializa una nueva instancia de la clase [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/). |
| [EmfFillRgn(source)](#EmfFillRgn_source_2) | Inicializa una nueva instancia de la clase [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en [MS-WMF] sección 2.2.2.19, <br/>            que especifica el rectángulo delimitador. |
| ih_brush | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el índice de la tabla de objetos EMF del pincel <br/>            para rellenar la región. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | Obtiene o establece una matriz de bytes de longitud RgnDataSize que contiene un objeto RegionData (sección 2.2.24). |
| rgn_data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos de la región, en bytes. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfFillRgn() {#EmfFillRgn__1}


```
 EmfFillRgn() 
```

Inicializa una nueva instancia de la clase [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/).

### Constructor: EmfFillRgn(source) {#EmfFillRgn_source_2}


```
 EmfFillRgn(source) 
```

Inicializa una nueva instancia de la clase [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/).

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


