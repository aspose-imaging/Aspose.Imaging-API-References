---
title: "EmfMetafileHeader"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_HEADER 记录类型定义 EMF 元文件的起始点，并指定创建该元文件图像的设备属性。"
type: docs
weight: 70
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

EMR\_HEADER 记录类型定义 EMF 元文件的起始点，并指定创建该元文件图像的设备属性。头记录中的信息使 EMF 元文件能够独立于任何特定输出设备。Size 字段的值可用于区分本节前面列出的不同 EMR\_HEADER 记录类型。共有三种可能的头：基础头，即 EmfMetafileHeader 记录。该头的固定大小部分为 88 字节，包含一个 Header 对象。第一扩展头，即 EmfMetafileHeaderExtension1 记录。该头的固定大小部分为 100 字节，包含一个 Header 对象和一个 HeaderExtension1 对象（第 2.2.10 节）。第二扩展头，即 EmfMetafileHeaderExtension2 记录。该头的固定大小部分为 108 字节，包含一个 Header 对象、一个 HeaderExtension1 对象和一个 HeaderExtension2 对象（第 2.2.11 节）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfMetafileHeader` 类的新实例。 |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | 初始化 `EmfMetafileHeader` 类的新实例。 |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | 初始化 `EmfMetafileHeader` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | 获取 Header 对象（第 2.2.9 节），其中包含有关元文件内容和结构的信息。 |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | 设置 Header 对象（第 2.2.9 节），其中包含有关元文件内容和结构的信息。 |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | 获取一个可选的字节数组，其中包含 EMF 标头记录的其余部分。 |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | 设置一个可选的字节数组，其中包含 EMF 标头记录的其余部分。 |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | 获取 EMF 描述缓冲区——一个可选的字节数组，其中包含 EMF 描述字符串，该字符串不需要与 EmfMetafileHeader 记录的固定部分连续。 |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | 设置 EMF 描述缓冲区——一个可选的字节数组，其中包含 EMF 描述字符串，该字符串不需要与 EmfMetafileHeader 记录的固定部分连续。 |
| [getEmfDescription()](#getEmfDescription--) | 获取 EMF 描述——一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，长度和内容任意。 |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | 设置 EMF 描述——一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，长度和内容任意。 |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


初始化 `EmfMetafileHeader` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 记录。 |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


初始化 `EmfMetafileHeader` 类的新实例。

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


初始化 `EmfMetafileHeader` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | 头部。 |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


获取 Header 对象（第 2.2.9 节），其中包含有关元文件内容和结构的信息。

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


设置 Header 对象（第 2.2.9 节），其中包含有关元文件内容和结构的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


获取一个可选的字节数组，其中包含 EMF 标头记录的其余部分。该字段的大小必须是 4 字节的倍数。

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


设置一个可选的字节数组，其中包含 EMF 标头记录的其余部分。该字段的大小必须是 4 字节的倍数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


获取 EMF 描述缓冲区——一个可选的字节数组，其中包含 EMF 描述字符串，该字符串不需要与 EmfMetafileHeader 记录的固定部分连续。因此，缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


设置 EMF 描述缓冲区——一个可选的字节数组，其中包含 EMF 描述字符串，该字符串不需要与 EmfMetafileHeader 记录的固定部分连续。因此，缓冲区中标记为 \"UndefinedSpace\" 的字段是可选的，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


获取 EMF 描述——一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，长度和内容任意。其在记录中的位置和字符数分别由 EmfHeader 中的 offDescription 和 nDescription 字段指定。如果任一字段的值为零，则不存在描述字符串。

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


设置 EMF 描述——一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，长度和内容任意。其在记录中的位置和字符数分别由 EmfHeader 中的 offDescription 和 nDescription 字段指定。如果任一字段的值为零，则不存在描述字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

