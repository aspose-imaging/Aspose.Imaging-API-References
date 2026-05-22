---
title: "EmfMetafileHeaderExtension2 类"
type: docs
weight: 630
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/
---

**Summary:** The EmfMetafileHeaderExtension2 record is the header record used in the second extension to EMF<br/>            metafiles. Following the EmfHeaderExtension2 field, the remaining fields are optional and<br/>            can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension2

**Inheritance:** EmfMetafileHeaderExtension1

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfMetafileHeaderExtension2(header)](#EmfMetafileHeaderExtension2_header_1) | 初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。 |
| [EmfMetafileHeaderExtension2(header)](#EmfMetafileHeaderExtension2_header_2) | 初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| emf_description | string | r/w | 获取或设置 EMF 描述<br/>            一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，长度和内容任意。<br/>            它在记录中的位置和字符数分别由 EmfHeader 中的 offDescription 和 nDescription 字段指定。<br/>            如果任一字段的值为零，则不存在描述字符串。 |
| emf_description_buffer | System.Byte | r/w | 获取或设置 EMF 描述缓冲区<br/>            一个可选的字节数组，包含 EMF 描述字符串，该字符串不需要与 EmfMetafileHeader 记录的固定部分连续。<br/>            因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | 获取或设置一个 Header 对象（第 2.2.9 节），该对象包含有关元文件内容<br/>            和结构的信息。 |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | 获取或设置一个 HeaderExtension1 对象，该对象指定元文件中图像的附加信息。 |
| emf_header_extension2 | [EmfHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/) | r/w | 获取或设置一个 HeaderExtension2 对象，该对象指定元文件中图像的附加信息。 |
| emf_header_record_buffer | System.Byte | r/w | 获取或设置一个可选的字节数组，包含 EMF 头记录的其余部分。<br/>            此字段的大小必须是 4 字节的倍数。 |
| emf_pixel_format_buffer | System.Byte | r/w | 获取或设置一个可选的字节数组，包含 EMF 像素格式描述符，该描述符不需要与 EmfMetafileHeaderExtension1 记录的固定部分或 EMF<br/>            描述字符串连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | 初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。 |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | 初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。 |
| [create_from_header_extension2(header)](#create_from_header_extension2_header_3) | 初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。 |
| [create_from_record(record)](#create_from_record_record_4) | 初始化 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_5) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfMetafileHeaderExtension2(header) {#EmfMetafileHeaderExtension2_header_1}


```
 EmfMetafileHeaderExtension2(header) 
```

初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | 头部。 |

### Constructor: EmfMetafileHeaderExtension2(header) {#EmfMetafileHeaderExtension2_header_2}


```
 EmfMetafileHeaderExtension2(header) 
```

初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) | 头部。 |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | 头部。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | 头部。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) |  |


### Method: create_from_header_extension2(header)  [static] {#create_from_header_extension2_header_3}


```
 create_from_header_extension2(header) 
```

初始化一个新的 [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) | 头部。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_4}


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


### Method: create_from_type(type)  [static] {#create_from_type_type_5}


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


