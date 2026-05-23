---
title: "EmfSaveDc Clase"
type: docs
weight: 1030
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---

**Summary:** Saves the current state of playback device context on a<br/>            stack of states saved by preceding EMR_SAVEDC<br/>            records, if any. The state consists of graphics properties<br/>            and objects, including the currently selected bitmap,<br/>            brush, palette, font, pen, and region. An<br/>            EMR_RESTOREDC record is used to restore the state.<br/>            This EMF record specifies no parameters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSaveDc

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSaveDc()](#EmfSaveDc__1) | Inicializa una nueva instancia de la clase [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/). |
| [EmfSaveDc(source)](#EmfSaveDc_source_2) | Inicializa una nueva instancia de la clase [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSaveDc() {#EmfSaveDc__1}


```
 EmfSaveDc() 
```

Inicializa una nueva instancia de la clase [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/).

### Constructor: EmfSaveDc(source) {#EmfSaveDc_source_2}


```
 EmfSaveDc(source) 
```

Inicializa una nueva instancia de la clase [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/).

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


