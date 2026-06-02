---
title: "Clase EmfCommentMultiFormats"
type: docs
weight: 210
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---

**Summary:** The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentMultiFormats

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfCommentMultiFormats(source)](#EmfCommentMultiFormats_source_1) | Inicializa una nueva instancia de la clase [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| a_formats | [EmfFormat[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/) | r/w | Obtiene o establece una matriz de longitud CountFormats de formatos gráficos, especificada por <br/>            objetos EmrFormat (sección 2.2.4), en orden de preferencia. |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario <br/>            como que especifica datos públicos. El valor 0x43494447, que es la cadena ASCII "CIDG", identifica <br/>            esto como un registro EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, de los campos CommentIdentifier y CommentRecordParm en el campo RecordBuffer que <br/>            sigue. NO DEBE incluir el tamaño de sí mismo o el tamaño del campo AlignmentPadding, si <br/>            está presente. |
| format_data | System.Byte[] | r/w | Obtiene o establece una matriz de bytes de longitud variable con los datos de imagen para todos los formatos gráficos <br/>            contenidos en este registro. <br/>            El tamaño de los datos de cada imagen lo proporciona el campo DataSize en el objeto EmrFormat correspondiente. <br/>            Por lo tanto, el tamaño total de este campo es la suma de los valores DataSize en todos los <br/>            objetos EmrFormat. <br/>            El formato gráfico de los datos de cada imagen se especifica mediante el campo Signature en el <br/>            objeto EmrFormat correspondiente. |
| output_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el <br/>            rectángulo de salida, en coordenadas lógicas. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de <br/>            registro de comentario público. Este DEBERÍA ser uno de los valores listados en la tabla anterior, que <br/>            están especificados en la enumeración EmrComment (sección 2.1.10), a menos que se hayan implementado tipos adicionales de registros de comentario público en el servidor de impresión. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentMultiFormats(source) {#EmfCommentMultiFormats_source_1}


```
 EmfCommentMultiFormats(source) 
```

Inicializa una nueva instancia de la clase [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/).

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


