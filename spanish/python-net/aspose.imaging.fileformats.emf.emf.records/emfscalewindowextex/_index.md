---
title: "Clase EmfScaleWindowExtex"
type: docs
weight: 1050
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---

**Summary:** The EMR_SCALEWINDOWEXTEX record respecifies the window for a playback device context by<br/>            using the ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleWindowExtex

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex__1) | Inicializa una nueva instancia de la clase [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/). |
| [EmfScaleWindowExtex(source)](#EmfScaleWindowExtex_source_2) | Inicializa una nueva instancia de la clase [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| x_denom | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el divisor horizontal. NO DEBE ser cero. |
| x_num | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el multiplicador horizontal. NO DEBE ser cero. |
| y_denom | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el divisor vertical. NO DEBE ser cero. |
| y_num | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el multiplicador vertical. NO DEBE ser cero. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfScaleWindowExtex() {#EmfScaleWindowExtex__1}


```
 EmfScaleWindowExtex() 
```

Inicializa una nueva instancia de la clase [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/).

### Constructor: EmfScaleWindowExtex(source) {#EmfScaleWindowExtex_source_2}


```
 EmfScaleWindowExtex(source) 
```

Inicializa una nueva instancia de la clase [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/).

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


