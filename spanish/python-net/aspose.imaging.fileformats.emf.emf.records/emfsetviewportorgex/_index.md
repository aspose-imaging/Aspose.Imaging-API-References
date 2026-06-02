---
title: "Clase EmfSetViewportOrgEx"
type: docs
weight: 1340
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/
---

**Summary:** The EMR_SETVIEWPORTORGEX record defines the viewport origin.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetViewportOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetViewportOrgEx()](#EmfSetViewportOrgEx__1) | Inicializa una nueva instancia de la clase [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/). |
| [EmfSetViewportOrgEx(source)](#EmfSetViewportOrgEx_source_2) | Inicializa una nueva instancia de la clase [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece un objeto WMF PointL de 64 bits ([MS-WMF] sección 2.2.2.15) que especifica el<br/>            origen horizontal y vertical de la ventana en unidades del dispositivo. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetViewportOrgEx() {#EmfSetViewportOrgEx__1}


```
 EmfSetViewportOrgEx() 
```

Inicializa una nueva instancia de la clase [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/).

### Constructor: EmfSetViewportOrgEx(source) {#EmfSetViewportOrgEx_source_2}


```
 EmfSetViewportOrgEx(source) 
```

Inicializa una nueva instancia de la clase [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/).

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


