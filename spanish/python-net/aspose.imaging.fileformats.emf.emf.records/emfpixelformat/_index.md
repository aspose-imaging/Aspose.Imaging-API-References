---
title: "Clase EmfPixelFormat"
type: docs
weight: 740
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfpixelformat/
---

**Summary:** The EMR_PIXELFORMAT record specifies the pixel format to use for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPixelFormat

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPixelFormat(source)](#EmfPixelFormat_source_1) | Inicializa una nueva instancia de la clase [EmfPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpixelformat/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| pfd | [EmfPixelFormatDescriptor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/) | r/w | Obtiene o establece un objeto PixelFormatDescriptor (sección 2.2.22) que especifica los datos del formato de píxel. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPixelFormat(source) {#EmfPixelFormat_source_1}


```
 EmfPixelFormat(source) 
```

Inicializa una nueva instancia de la clase [EmfPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpixelformat/).

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


