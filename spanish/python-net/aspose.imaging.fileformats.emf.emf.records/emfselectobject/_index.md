---
title: "Clase EmfSelectObject"
type: docs
weight: 1070
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---

**Summary:** The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device<br/>            context. The object is specified either by its index in the EMF Object Table(section 3.1.1.1) or by its<br/>            value from the StockObject enumeration(section 2.1.31).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectObject

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSelectObject()](#EmfSelectObject__1) | Inicializa una nueva instancia de la clase [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/). |
| [EmfSelectObject(record)](#EmfSelectObject_record_2) | Inicializa una nueva instancia de la clase [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| object_handle | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico <br/>            en la tabla de objetos EMF o el índice de un objeto predefinido de la enumeración [EmfStockObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/). |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSelectObject() {#EmfSelectObject__1}


```
 EmfSelectObject() 
```

Inicializa una nueva instancia de la clase [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/).

### Constructor: EmfSelectObject(record) {#EmfSelectObject_record_2}


```
 EmfSelectObject(record) 
```

Inicializa una nueva instancia de la clase [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/).

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


