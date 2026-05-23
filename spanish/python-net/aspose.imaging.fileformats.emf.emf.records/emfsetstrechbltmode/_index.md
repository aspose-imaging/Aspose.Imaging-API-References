---
title: "Clase EmfSetStrechBltMode"
type: docs
weight: 1290
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetstrechbltmode/
---

**Summary:** The EMR_SETSTRETCHBLTMODE record specifies bitmap stretch mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetStrechBltMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetStrechBltMode(source)](#EmfSetStrechBltMode_source_1) | Inicializa una nueva instancia de la clase [EmfSetStrechBltMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetstrechbltmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| stretch_mode | [EmfStretchMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de estiramiento y PUEDEN estar<br/>            en la enumeración StretchMode. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetStrechBltMode(source) {#EmfSetStrechBltMode_source_1}


```
 EmfSetStrechBltMode(source) 
```

Inicializa una nueva instancia de la clase [EmfSetStrechBltMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetstrechbltmode/).

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


