---
title: "EmfMetafileHeader 类"
type: docs
weight: 610
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---

**Summary:** The EMR_HEADER record types define the starting points of EMF metafiles<br/>            and specify properties of the device on which the image in the metafile<br/>            was created. The information in the header record makes it possible for<br/>            EMF metafiles to be independent of any specific output device.<br/>            The value of the Size field can be used to distinguish between the different<br/>            EMR_HEADER record types listed earlier in this section.<br/>            There are three possible headers:<br/>            The base header, which is the EmfMetafileHeader record.<br/>            The fixed-size part of this header is 88 bytes, and it contains a Header object.<br/>            The first extension header, which is the EmfMetafileHeaderExtension1 record.<br/>            The fixed-size part of this header is 100 bytes, and it contains a Header object<br/>            and a HeaderExtension1 object (section 2.2.10).<br/>            The second extension header, which is the EmfMetafileHeaderExtension2 record.<br/>            The fixed-size part of this header is 108 bytes, and it contains a Header object,<br/>            a HeaderExtension1 object, and a HeaderExtension2 object (section 2.2.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfMetafileHeader()](#EmfMetafileHeader__1) | 初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。 |
| [EmfMetafileHeader(header)](#EmfMetafileHeader_header_2) | 初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。 |
| [EmfMetafileHeader(record)](#EmfMetafileHeader_record_3) | 初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| emf_description | string | r/w | 获取或设置 EMF 描述<br/>            一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，长度和内容任意。<br/>            它在记录中的位置和字符数分别由 EmfHeader 中的 offDescription 和 nDescription 字段指定。<br/>            如果任一字段的值为零，则不存在描述字符串。 |
| emf_description_buffer | System.Byte | r/w | 获取或设置 EMF 描述缓冲区<br/>            一个可选的字节数组，包含 EMF 描述字符串，该字符串不需要与 EmfMetafileHeader 记录的固定部分连续。<br/>            因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | 获取或设置一个 Header 对象（第 2.2.9 节），该对象包含有关元文件内容<br/>            和结构的信息。 |
| emf_header_record_buffer | System.Byte | r/w | 获取或设置一个可选的字节数组，包含 EMF 头记录的其余部分。<br/>            此字段的大小必须是 4 字节的倍数。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | 初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。 |
| [create_from_record(record)](#create_from_record_record_2) | 初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_3) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfMetafileHeader() {#EmfMetafileHeader__1}


```
 EmfMetafileHeader() 
```

初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。

### Constructor: EmfMetafileHeader(header) {#EmfMetafileHeader_header_2}


```
 EmfMetafileHeader(header) 
```

初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | 头部。 |

### Constructor: EmfMetafileHeader(record) {#EmfMetafileHeader_record_3}


```
 EmfMetafileHeader(record) 
```

初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 该记录。 |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | 头部。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_2}


```
 create_from_record(record) 
```

初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 该记录。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_3}


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


