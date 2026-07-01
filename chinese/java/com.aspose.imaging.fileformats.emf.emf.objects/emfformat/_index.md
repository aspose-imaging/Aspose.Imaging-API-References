---
title: "EmfFormat"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmrFormat 对象包含用于标识 EMR_COMMENT_MULTIFORMATS 记录（第 2.3.3.4.3 节）中图像数据格式的信息。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

EmrFormat 对象包含用于识别 EMR\_COMMENT\_MULTIFORMATS 记录（第 2.3.3.4.3 节）中图像数据格式的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSignature()](#getSignature--) | 获取或设置一个指定图像数据格式的 32 位无符号整数。 |
| [setSignature(int value)](#setSignature-int-) | 获取或设置一个指定图像数据格式的 32 位无符号整数。 |
| [getVersion()](#getVersion--) | 获取或设置一个指定格式版本号的 32 位无符号整数。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置一个指定格式版本号的 32 位无符号整数。 |
| [getSizeData()](#getSizeData--) | 获取或设置一个指定数据大小（以字节为单位）的 32 位无符号整数。 |
| [setSizeData(int value)](#setSizeData-int-) | 获取或设置一个指定数据大小（以字节为单位）的 32 位无符号整数。 |
| [getOffData()](#getOffData--) | 获取或设置一个指定 EMR\_COMMENT\_PUBLIC 记录（第 2.3.3.4 节）中标识字段起始位置到数据偏移量的 32 位无符号整数。 |
| [setOffData(int value)](#setOffData-int-) | 获取或设置一个指定 EMR\_COMMENT\_PUBLIC 记录（第 2.3.3.4 节）中标识字段起始位置到数据偏移量的 32 位无符号整数。 |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


获取或设置一个指定图像数据格式的 32 位无符号整数。该值必须位于 FormatSignature 枚举中（第 2.1.14 节）。

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


获取或设置一个指定图像数据格式的 32 位无符号整数。该值必须位于 FormatSignature 枚举中（第 2.1.14 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


获取或设置一个指定格式版本号的 32 位无符号整数。如果 Signature 字段指定封装的 PostScript（EPS），则该值必须为 0x00000001；否则，该值必须被忽略。

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


获取或设置一个指定格式版本号的 32 位无符号整数。如果 Signature 字段指定封装的 PostScript（EPS），则该值必须为 0x00000001；否则，该值必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


获取或设置一个指定数据大小（以字节为单位）的 32 位无符号整数。

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


获取或设置一个指定数据大小（以字节为单位）的 32 位无符号整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


获取或设置一个指定 EMR\_COMMENT\_PUBLIC 记录（第 2.3.3.4 节）中标识字段起始位置到数据偏移量的 32 位无符号整数。偏移量必须是 32 位对齐的。

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


获取或设置一个指定 EMR\_COMMENT\_PUBLIC 记录（第 2.3.3.4 节）中标识字段起始位置到数据偏移量的 32 位无符号整数。偏移量必须是 32 位对齐的。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

