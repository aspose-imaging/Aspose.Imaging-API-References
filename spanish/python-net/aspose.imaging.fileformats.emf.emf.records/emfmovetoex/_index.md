---
title: "Clase EmfMoveToEx"
type: docs
weight: 650
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/
---

**Summary:** The EMR_MOVETOEX record specifies coordinates of the new current position, in logical units.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMoveToEx

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfMoveToEx()](#EmfMoveToEx__1) | Inicializa una nueva instancia de la clase [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/). |
| [EmfMoveToEx(record)](#EmfMoveToEx_record_2) | Inicializa una nueva instancia de la clase [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| offset | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en [MS-WMF] sección 2.2.2.15, <br/>            que especifica las coordenadas de la nueva posición actual en unidades lógicas. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMoveToEx() {#EmfMoveToEx__1}


```
 EmfMoveToEx() 
```

Inicializa una nueva instancia de la clase [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/).

### Constructor: EmfMoveToEx(record) {#EmfMoveToEx_record_2}


```
 EmfMoveToEx(record) 
```

Inicializa una nueva instancia de la clase [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/).

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


