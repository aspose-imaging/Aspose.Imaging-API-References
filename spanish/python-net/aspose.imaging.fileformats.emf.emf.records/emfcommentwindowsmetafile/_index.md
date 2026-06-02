---
title: "EmfCommentWindowsMetaFile Clase"
type: docs
weight: 240
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---

**Summary:** The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentWindowsMetaFile

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfCommentWindowsMetaFile(source)](#EmfCommentWindowsMetaFile_source_1) | Inicializa una nueva instancia de la clase [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| checksum | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica la suma de verificación para este registro. |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario <br/>            como que especifica datos públicos. El valor 0x43494447, que es la cadena ASCII "CIDG", identifica <br/>            esto como un registro EMR_COMMENT_PUBLIC. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, de los campos CommentIdentifier y CommentRecordParm en el campo RecordBuffer que <br/>            sigue. NO DEBE incluir el tamaño de sí mismo o el tamaño del campo AlignmentPadding, si <br/>            está presente. |
| banderas | int | r/w | Obtiene o establece un valor de 32 bits que DEBE ser 0x00000000 y DEBE ser ignorado. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de <br/>            registro de comentario público. Este DEBERÍA ser uno de los valores listados en la tabla anterior, que <br/>            están especificados en la enumeración EmrComment (sección 2.1.10), a menos que se hayan implementado tipos adicionales de registros de comentario público en el servidor de impresión. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| version | [WmfMetafileVersion](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileversion/) | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica la versión del metafichero WMF en términos <br/>            de soporte para mapas de bits independientes del dispositivo (DIBs), de la enumeración WMF MetafileVersion <br/>            ([MS-WMF] sección 2.1.1.19). |
| win_metafile | [MetaImage](/imaging/python-net/aspose.imaging.fileformats.emf/metaimage/) | r/w | Obtiene o establece un búfer que contiene el metafichero WMF. |
| win_metafile_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del <br/>            metafichero WMF en el campo WinMetafile. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCommentWindowsMetaFile(source) {#EmfCommentWindowsMetaFile_source_1}


```
 EmfCommentWindowsMetaFile(source) 
```

Inicializa una nueva instancia de la clase [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/).

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


