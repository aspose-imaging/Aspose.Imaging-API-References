---
title: "EmfCommentWindowsMetaFile 类"
type: docs
weight: 240
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---

**Summary:** The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentWindowsMetaFile

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfCommentWindowsMetaFile(source)](#EmfCommentWindowsMetaFile_source_1) | 初始化一个新的 [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| checksum | int | r/w | 获取或设置一个指定此记录校验和的 32 位无符号整数。 |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | 获取或设置一个 32 位无符号整数，用于标识此注释记录 <br/>            为公共数据。值 0x43494447，即 ASCII 字符串 "CIDG"，标识 <br/>            这是一条 EMR_COMMENT_PUBLIC 记录。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，指定 <br/>            CommentIdentifier 和 CommentRecordParm 字段在随后 RecordBuffer 字段中的大小（以字节为单位）。它不得包括自身的大小或 AlignmentPadding 字段的大小（如果存在）。 |
| flags | int | r/w | 获取或设置一个必须为 0x00000000 且必须被忽略的 32 位值。 |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | 获取或设置一个 32 位无符号整数，用于标识 <br/>            公共注释记录的类型。除非打印服务器已实现其他公共 <br/>            注释记录类型，否则此值应为前表中列出的值之一，这些值在 EmrComment 枚举（第 2.1.10 节）中指定。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| version | [WmfMetafileVersion](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileversion/) | r/w | 获取或设置一个指定 WMF 元文件版本的 16 位无符号整数，表示对设备无关位图（DIB）支持的 <br/>            条件，来自 WMF MetafileVersion 枚举 <br/>            （[MS-WMF] 第 2.1.1.19 节）。 |
| win_metafile | [MetaImage](/imaging/python-net/aspose.imaging.fileformats.emf/metaimage/) | r/w | 获取或设置一个包含 WMF 元文件的缓冲区。 |
| win_metafile_size | int | r/w | 获取或设置一个指定 WinMetafile 字段中 <br/>            WMF 元文件大小（以字节为单位）的 32 位无符号整数。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfCommentWindowsMetaFile(source) {#EmfCommentWindowsMetaFile_source_1}


```
 EmfCommentWindowsMetaFile(source) 
```

初始化一个新的 [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | 记录类型。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


