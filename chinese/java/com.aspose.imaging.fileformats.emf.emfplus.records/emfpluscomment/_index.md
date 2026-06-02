---
title: "EmfPlusComment"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusComment 记录指定任意私有数据。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord)
```
public final class EmfPlusComment extends EmfPlusRecord
```

EmfPlusComment 记录指定任意私有数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusComment(EmfPlusRecord source)](#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusComment` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | 获取或设置长度为 DataSize 的私有数据字节数组。 |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | 获取或设置长度为 DataSize 的私有数据字节数组。 |
| [getFlags()](#getFlags--) | 获取或设置一个未使用的 16 位无符号整数。 |
| [setFlags(short value)](#setFlags-short-) | 获取或设置一个未使用的 16 位无符号整数。 |
### EmfPlusComment(EmfPlusRecord source) {#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusComment(EmfPlusRecord source)
```


初始化 `EmfPlusComment` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


获取或设置长度为 DataSize 的私有数据字节数组。后续的记录特定数据字节。

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


获取或设置长度为 DataSize 的私有数据字节数组。后续的记录特定数据字节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getFlags() {#getFlags--}
```
public short getFlags()
```


获取或设置一个未使用的 16 位无符号整数。该字段应设置为零，并且在接收时必须被忽略。

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


获取或设置一个未使用的 16 位无符号整数。该字段应设置为零，并且在接收时必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

