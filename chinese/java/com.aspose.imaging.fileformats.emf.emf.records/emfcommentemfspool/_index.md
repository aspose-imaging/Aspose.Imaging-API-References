---
title: "EmfCommentEmfSpool"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_COMMENT_EMFSPOOL 记录包含嵌入的 EMFSPOOL 记录。"
type: docs
weight: 28
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

EMR\\_COMMENT\\_EMFSPOOL 记录包含嵌入的 EMFSPOOL 记录。注意，本节未描述的字段在第 2.3.3 节中指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCommentEmfSpool` 类的新实例。 |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | 初始化 `EmfCommentEmfSpool` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | 获取或设置一个 32 位无符号整数，用于标识此注释记录包含 EMFSPOOL 记录。 |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | 获取或设置一个 32 位无符号整数，用于标识此注释记录包含 EMFSPOOL 记录。 |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | 获取或设置一个 32 位无符号整数，用于标识 EMR\\_COMMENT\\_EMFSPOOL 记录的类型。 |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | 获取或设置一个 32 位无符号整数，用于标识 EMR\\_COMMENT\\_EMFSPOOL 记录的类型。 |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | 获取或设置一个可变长度的字节数组，包含一个或多个 EMFSPOOL 字体定义记录（[MS-EMFSPOOL] 第 2.2.3.3 节）。 |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | 获取或设置一个可变长度的字节数组，包含一个或多个 EMFSPOOL 字体定义记录（[MS-EMFSPOOL] 第 2.2.3.3 节）。 |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


初始化 `EmfCommentEmfSpool` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


初始化 `EmfCommentEmfSpool` 类的新实例。

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


获取或设置一个 32 位无符号整数，用于标识此注释记录包含 EMFSPOOL 记录。值 0x00000000 将其标识为 EMR\\_COMMENT\\_EMFSPOOL 记录。

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


获取或设置一个 32 位无符号整数，用于标识此注释记录包含 EMFSPOOL 记录。值 0x00000000 将其标识为 EMR\\_COMMENT\\_EMFSPOOL 记录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


获取或设置一个 32 位无符号整数，用于标识 EMR\\_COMMENT\\_EMFSPOOL 记录的类型。

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


获取或设置一个 32 位无符号整数，用于标识 EMR\\_COMMENT\\_EMFSPOOL 记录的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


获取或设置一个可变长度的字节数组，包含一个或多个 EMFSPOOL 字体定义记录（[MS-EMFSPOOL] 第 2.2.3.3 节）。

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


获取或设置一个可变长度的字节数组，包含一个或多个 EMFSPOOL 字体定义记录（[MS-EMFSPOOL] 第 2.2.3.3 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

