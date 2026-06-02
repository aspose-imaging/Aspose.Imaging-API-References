---
title: "EmfCommentPublicRecordType Clase"
type: docs
weight: 220
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---

**Summary:** The EMR_COMMENT_PUBLIC record types specify extensions to EMF processing.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType

**Inheritance:** EmfCommentRecordType

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario <br/>            como que especifica datos públicos. El valor 0x43494447, que es la cadena ASCII "CIDG", identifica <br/>            esto como un registro EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, de los campos CommentIdentifier y CommentRecordParm en el campo RecordBuffer que <br/>            sigue. NO DEBE incluir el tamaño de sí mismo o el tamaño del campo AlignmentPadding, si <br/>            está presente. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de <br/>            registro de comentario público. Este DEBERÍA ser uno de los valores listados en la tabla anterior, que <br/>            están especificados en la enumeración EmrComment (sección 2.1.10), a menos que se hayan implementado tipos adicionales de registros de comentario público en el servidor de impresión. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


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


