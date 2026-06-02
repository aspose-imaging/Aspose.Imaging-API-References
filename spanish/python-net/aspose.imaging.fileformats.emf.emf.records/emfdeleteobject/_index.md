---
title: "Clase EmfDeleteObject"
type: docs
weight: 340
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---

**Summary:** The EMR_DELETEOBJECT record deletes a graphics object, which is specified by its index in the EMF Object Table(section 3.1.1.1).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDeleteObject

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfDeleteObject()](#EmfDeleteObject__1) | Inicializa una nueva instancia de la clase [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/). |
| [EmfDeleteObject(record)](#EmfDeleteObject_record_2) | Inicializa una nueva instancia de la clase [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| object_handle | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica ya sea el índice de un objeto gráfico <br/>            en la tabla de objetos EMF o el índice de un objeto predeterminado de la enumeración StockObject. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfDeleteObject() {#EmfDeleteObject__1}


```
 EmfDeleteObject() 
```

Inicializa una nueva instancia de la clase [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/).

### Constructor: EmfDeleteObject(record) {#EmfDeleteObject_record_2}


```
 EmfDeleteObject(record) 
```

Inicializa una nueva instancia de la clase [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/).

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


