---
title: "Clase EmfExcludeClipRect"
type: docs
weight: 410
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---

**Summary:** The EMR_EXCLUDECLIPRECT record specifies a new clipping region that consists of the existing <br/>            clipping region minus the specified rectangle. <br/>            Note  Fields that are not described in this section are specified in section 2.3.2.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExcludeClipRect

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfExcludeClipRect()](#EmfExcludeClipRect__1) | Inicializa una nueva instancia de la clase [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/). |
| [EmfExcludeClipRect(source)](#EmfExcludeClipRect_source_2) | Inicializa una nueva instancia de la clase [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| clip | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de recorte <br/>            en unidades lógicas. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExcludeClipRect() {#EmfExcludeClipRect__1}


```
 EmfExcludeClipRect() 
```

Inicializa una nueva instancia de la clase [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/).

### Constructor: EmfExcludeClipRect(source) {#EmfExcludeClipRect_source_2}


```
 EmfExcludeClipRect(source) 
```

Inicializa una nueva instancia de la clase [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/).

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


