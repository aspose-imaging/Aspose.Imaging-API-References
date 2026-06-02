---
title: "EmfComment"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_COMMENT 记录包含任意私有数据。"
type: docs
weight: 25
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

EMR\_COMMENT 记录包含任意私有数据。注意，本节未描述的字段在第 2.3.3 节中指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfComment` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | 获取或设置指定私有数据的可选字节数组。 |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | 获取或设置指定私有数据的可选字节数组。 |
| [getCommentIdentifier()](#getCommentIdentifier--) | 获取或设置注释标识符。 |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | 获取或设置注释标识符。 |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


初始化 `EmfComment` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


获取或设置指定私有数据的可选字节数组。该数据的第一个 DWORD 必须不是第 2.3.3 节中指定的预定义注释标识符值。私有数据对 EMF 来说是未知的；仅对了解数据格式并知道如何使用它的应用程序有意义。EMR\_COMMENT 私有数据记录可以被忽略。

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


获取或设置指定私有数据的可选字节数组。该数据的第一个 DWORD 必须不是第 2.3.3 节中指定的预定义注释标识符值。私有数据对 EMF 来说是未知的；仅对了解数据格式并知道如何使用它的应用程序有意义。EMR\_COMMENT 私有数据记录可以被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

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

