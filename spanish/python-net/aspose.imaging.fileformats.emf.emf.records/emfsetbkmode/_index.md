---
title: "EmfSetBkMode Clase"
type: docs
weight: 1110
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---

**Summary:** The EMR_SETBKMODE record specifies the background mix mode of the playback device context.<br/>            The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBkMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetBkMode()](#EmfSetBkMode__1) | Inicializa una nueva instancia de la [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/) clase. |
| [EmfSetBkMode(source)](#EmfSetBkMode_source_2) | Inicializa una nueva instancia de la [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/) clase. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de fondo<br/>            y DEBE estar en la enumeración BackgroundMode (sección 2.1.4). |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetBkMode() {#EmfSetBkMode__1}


```
 EmfSetBkMode() 
```

Inicializa una nueva instancia de la [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/) clase.

### Constructor: EmfSetBkMode(source) {#EmfSetBkMode_source_2}


```
 EmfSetBkMode(source) 
```

Inicializa una nueva instancia de la [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/) clase.

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


