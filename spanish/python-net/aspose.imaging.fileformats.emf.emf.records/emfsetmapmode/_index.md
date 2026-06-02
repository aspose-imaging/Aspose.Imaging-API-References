---
title: "EmfSetMapMode Class"
type: docs
weight: 1210
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/
---

**Summary:** The EMR_SETMAPMODE record specifies the mapping mode of the playback device context. <br/>            The mapping mode specifies the unit of measure used to transform page space units <br/>            into device space units, and also specifies the orientation of the device's x-axis and y-axis.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetMapMode

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetMapMode()](#EmfSetMapMode__1) | Inicializa una nueva instancia de la clase [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/). |
| [EmfSetMapMode(record)](#EmfSetMapMode_record_2) | Inicializa una nueva instancia de la clase [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| map_mode | [EmfMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/) | r/w | Obtiene o establece el modo de mapa. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetMapMode() {#EmfSetMapMode__1}


```
 EmfSetMapMode() 
```

Inicializa una nueva instancia de la clase [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/).

### Constructor: EmfSetMapMode(record) {#EmfSetMapMode_record_2}


```
 EmfSetMapMode(record) 
```

Inicializa una nueva instancia de la clase [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | El registro. |

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


