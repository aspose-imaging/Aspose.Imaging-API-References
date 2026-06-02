---
title: "Clase EmfCreateBrushIndirect"
type: docs
weight: 260
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---

**Summary:** The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateBrushIndirect

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect__1) | Inicializa una nueva instancia de la clase [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/). |
| [EmfCreateBrushIndirect(source)](#EmfCreateBrushIndirect_source_2) | Inicializa una nueva instancia de la clase [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| ih_brush | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto pincel lógico<br/>            en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda ser<br/>            reutilizado o modificado. |
| log_brush | [EmfLogBrushEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/) | r/w | Obtiene o establece un objeto LogBrushEx (sección 2.2.12) que especifica el estilo, color y<br/>            patrón del pincel lógico. El campo BrushStyle en este objeto DEBE ser BS_SOLID,<br/>            BS_HATCHED o BS_NULL. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateBrushIndirect() {#EmfCreateBrushIndirect__1}


```
 EmfCreateBrushIndirect() 
```

Inicializa una nueva instancia de la clase [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/).

### Constructor: EmfCreateBrushIndirect(source) {#EmfCreateBrushIndirect_source_2}


```
 EmfCreateBrushIndirect(source) 
```

Inicializa una nueva instancia de la clase [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/).

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


