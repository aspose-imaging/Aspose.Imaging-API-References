---
title: "EmfCommentEmfPlus Clase"
type: docs
weight: 180
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---

**Summary:** The EMR_COMMENT_EMFPLUS record contains embedded EMF+ records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfPlus

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfCommentEmfPlus(source)](#EmfCommentEmfPlus_source_1) | Inicializa una nueva instancia de la clase [EmfCommentEmfPlus](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario <br/>            como contenedor de registros EMF+. El valor 0x2B464D45, que es la cadena ASCII \"+FME\", <br/>            identifica esto como un registro EMR_COMMENT_EMFPLUS. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, de los campos CommentIdentifier y CommentRecordParm en el campo RecordBuffer que <br/>            sigue. NO DEBE incluir el tamaño de sí mismo o el tamaño del campo AlignmentPadding, si <br/>            está presente. |
| emf_plus_records | [EmfPlusRecord[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | r/w | Obtiene o establece una matriz de bytes que contiene uno o más registros EMF+ ([MS-EMFPLUS] sección 2.3.1). |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentEmfPlus(source) {#EmfCommentEmfPlus_source_1}


```
 EmfCommentEmfPlus(source) 
```

Inicializa una nueva instancia de la clase [EmfCommentEmfPlus](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/).

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


