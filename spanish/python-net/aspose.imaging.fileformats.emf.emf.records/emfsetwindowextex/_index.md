---
title: "EmfSetWindowExtEx Clase"
type: docs
weight: 1350
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/
---

**Summary:** The EMR_SETWINDOWEXTEX record defines the window extent.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWindowExtEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetWindowExtEx()](#EmfSetWindowExtEx__1) | Inicializa una nueva instancia de la clase [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/). |
| [EmfSetWindowExtEx(source)](#EmfSetWindowExtEx_source_2) | Inicializa una nueva instancia de la clase [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| extent | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtiene o establece un objeto WMF SizeL de 64 bits ([MS-WMF] sección 2.2.2.22) que especifica las extensiones horizontales y verticales en unidades lógicas. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetWindowExtEx() {#EmfSetWindowExtEx__1}


```
 EmfSetWindowExtEx() 
```

Inicializa una nueva instancia de la clase [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/).

### Constructor: EmfSetWindowExtEx(source) {#EmfSetWindowExtEx_source_2}


```
 EmfSetWindowExtEx(source) 
```

Inicializa una nueva instancia de la clase [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/).

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


