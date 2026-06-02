---
title: "EmfRestoreDc Class"
type: docs
weight: 1000
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---

**Summary:** The EMR_RESTOREDC record restores the playback device context to the specified state. The<br/>            playback device context is restored by popping state information off a stack that was created by<br/>            prior EMR_SAVEDC records (section 2.3.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRestoreDc

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfRestoreDc()](#EmfRestoreDc__1) | Inicializa una nueva instancia de la clase [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/). |
| [EmfRestoreDc(source)](#EmfRestoreDc_source_2) | Inicializa una nueva instancia de la clase [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| saved_dc | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el estado guardado que se debe restaurar relativo al<br/>            estado actual. Este valor DEBE ser negativo; –1 representa el estado que se guardó más<br/>            recientemente en la pila, –2 el anterior, etc. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfRestoreDc() {#EmfRestoreDc__1}


```
 EmfRestoreDc() 
```

Inicializa una nueva instancia de la clase [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/).

### Constructor: EmfRestoreDc(source) {#EmfRestoreDc_source_2}


```
 EmfRestoreDc(source) 
```

Inicializa una nueva instancia de la clase [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/).

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


