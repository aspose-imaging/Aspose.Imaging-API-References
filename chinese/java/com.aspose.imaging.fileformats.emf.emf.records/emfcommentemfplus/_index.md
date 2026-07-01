---
title: "EmfCommentEmfPlus"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_COMMENT_EMFPLUS 记录包含嵌入的 EMF 记录。"
type: docs
weight: 27
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

EMR\_COMMENT\_EMFPLUS 记录包含嵌入的 EMF+ 记录。注意，本节未描述的字段在第 2.3.3 节中指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCommentEmfPlus` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | 获取或设置一个 32 位无符号整数，用于标识此注释记录包含 EMF+ 记录。 |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | 获取或设置一个 32 位无符号整数，用于标识此注释记录包含 EMF+ 记录。 |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | 获取或设置一个字节数组，其中包含一个或多个 EMF+ 记录（[MS-EMFPLUS] 第 2.3.1 节）。 |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | 获取或设置一个字节数组，其中包含一个或多个 EMF+ 记录（[MS-EMFPLUS] 第 2.3.1 节）。 |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


初始化 `EmfCommentEmfPlus` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


获取或设置一个 32 位无符号整数，用于标识此注释记录包含 EMF+ 记录。值 0x2B464D45，即 ASCII 字符串 "+FME"，将其标识为 EMR\_COMMENT\_EMFPLUS 记录。

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


获取或设置一个 32 位无符号整数，用于标识此注释记录包含 EMF+ 记录。值 0x2B464D45，即 ASCII 字符串 "+FME"，将其标识为 EMR\_COMMENT\_EMFPLUS 记录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


获取或设置一个字节数组，其中包含一个或多个 EMF+ 记录（[MS-EMFPLUS] 第 2.3.1 节）。

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


获取或设置一个字节数组，其中包含一个或多个 EMF+ 记录（[MS-EMFPLUS] 第 2.3.1 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

