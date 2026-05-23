---
title: "Clase EmfEof"
type: docs
weight: 390
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

**Summary:** The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfEof()](#EmfEof__1) | Inicializa una nueva instancia de la clase [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/). |
| [EmfEof(record)](#EmfEof_record_2) | Inicializa una nueva instancia de la clase [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| palette_argb_32_entries | int[] | r/w | Obtiene o establece un búfer opcional que contiene datos de paleta, que no <br/>            necesita ser contiguo con la porción fija del registro EMR_EOF. <br/>            En consecuencia, los campos en este búfer que están etiquetados <br/>            "UndefinedSpace" son opcionales y DEBEN ser ignorados. <br/>            El tamaño de este campo DEBE ser un múltiplo de 4 bytes. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| size_last | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE ser igual a Size y DEBE ser el último <br/>            campo del registro y, por lo tanto, del metafichero. Los objetos LogPaletteEntry, si existen, <br/>            DEBEN preceder a este campo. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

Inicializa una nueva instancia de la clase [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/).

### Constructor: EmfEof(record) {#EmfEof_record_2}


```
 EmfEof(record) 
```

Inicializa una nueva instancia de la clase [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/).

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


