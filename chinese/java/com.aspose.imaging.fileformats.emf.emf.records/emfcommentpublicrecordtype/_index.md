---
title: "EmfCommentPublicRecordType"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_COMMENT_PUBLIC 记录类型指定对 EMF 处理的扩展。"
type: docs
weight: 31
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

该 EMR\_COMMENT\_PUBLIC 记录类型指定对 EMF 处理的扩展。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | 获取或设置一个 32 位无符号整数，用于标识此注释记录为公共数据。 |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | 获取或设置一个 32 位无符号整数，用于标识此注释记录为公共数据。 |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | 获取或设置一个 32 位无符号整数，用于标识公共注释记录的类型。 |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | 获取或设置一个 32 位无符号整数，用于标识公共注释记录的类型。 |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


获取或设置一个 32 位无符号整数，用于标识此注释记录为公共数据。值 0x43494447（ASCII 字符串 "CIDG"）将其标识为 EMR\\_COMMENT\\_PUBLIC 记录。

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


获取或设置一个 32 位无符号整数，用于标识此注释记录为公共数据。值 0x43494447（ASCII 字符串 "CIDG"）将其标识为 EMR\\_COMMENT\\_PUBLIC 记录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


获取或设置一个 32 位无符号整数，用于标识公共注释记录的类型。除非在打印服务器上实现了额外的公共注释记录类型，否则该值 SHOULD 为前表中列出的值之一，这些值在 EmrComment 枚举（第 2.1.10 节）中指定。

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


获取或设置一个 32 位无符号整数，用于标识公共注释记录的类型。除非在打印服务器上实现了额外的公共注释记录类型，否则该值 SHOULD 为前表中列出的值之一，这些值在 EmrComment 枚举（第 2.1.10 节）中指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

