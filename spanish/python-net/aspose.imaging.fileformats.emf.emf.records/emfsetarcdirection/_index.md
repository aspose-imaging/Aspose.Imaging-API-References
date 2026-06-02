---
title: "Clase EmfSetArcDirection"
type: docs
weight: 1090
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---

**Summary:** The EMR_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetArcDirection

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetArcDirection()](#EmfSetArcDirection__1) | Inicializa una nueva instancia de la clase [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/). |
| [EmfSetArcDirection(source)](#EmfSetArcDirection_source_2) | Inicializa una nueva instancia de la clase [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| arc_direction | [EmfArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfarcdirection/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica la dirección del arco. El valor<br/>            DEBE estar en la enumeración ArcDirection (sección 2.1.2).<br/>            La dirección predeterminada es en sentido antihorario. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetArcDirection() {#EmfSetArcDirection__1}


```
 EmfSetArcDirection() 
```

Inicializa una nueva instancia de la clase [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/).

### Constructor: EmfSetArcDirection(source) {#EmfSetArcDirection_source_2}


```
 EmfSetArcDirection(source) 
```

Inicializa una nueva instancia de la clase [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/).

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


