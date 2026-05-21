---
title: "EmfCommentRecordType"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "注释记录类型定义了在其他元文件格式中指定任意私有数据嵌入记录以及添加新或特殊用途命令的格式。"
type: docs
weight: 32
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

注释记录类型定义用于指定任意私有数据、在其他元文件格式中嵌入记录以及添加新建或特殊用途命令的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDataSize()](#getDataSize--) | 获取或设置一个 32 位无符号整数，用于指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。 |
| [setDataSize(int value)](#setDataSize-int-) | 获取或设置一个 32 位无符号整数，用于指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。 |
| [getCommentIdentifier()](#getCommentIdentifier--) | 获取或设置注释标识符。 |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | 获取或设置注释标识符。 |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


获取或设置一个 32 位无符号整数，用于指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。如果存在 AlignmentPadding 字段，则该大小不得包括自身或 AlignmentPadding 字段的大小。

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


获取或设置一个 32 位无符号整数，用于指定随后的 RecordBuffer 字段中 CommentIdentifier 和 CommentRecordParm 字段的大小（以字节为单位）。如果存在 AlignmentPadding 字段，则该大小不得包括自身或 AlignmentPadding 字段的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


获取或设置注释标识符。

值：注释标识符。

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


获取或设置注释标识符。

值：注释标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

