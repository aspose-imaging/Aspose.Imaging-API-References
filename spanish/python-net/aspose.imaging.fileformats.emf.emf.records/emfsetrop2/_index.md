---
title: "Clase EmfSetRop2"
type: docs
weight: 1280
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---

**Summary:** The EMR_SETROP2 record defines a binary raster operation mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetRop2

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetRop2()](#EmfSetRop2__1) | Inicializa una nueva instancia de la clase [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/). |
| [EmfSetRop2(source)](#EmfSetRop2_source_2) | Inicializa una nueva instancia de la clase [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| rop_2_mode | [WmfBinaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de operación raster y<br/>            DEBE estar en la enumeración WMF Binary Raster Op ([MS-WMF] sección 2.1.1.2). |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetRop2() {#EmfSetRop2__1}


```
 EmfSetRop2() 
```

Inicializa una nueva instancia de la clase [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/).

### Constructor: EmfSetRop2(source) {#EmfSetRop2_source_2}


```
 EmfSetRop2(source) 
```

Inicializa una nueva instancia de la clase [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/).

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


