---
title: "TiffUndefinedType"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 tiff 未定义类型。"
type: docs
weight: 26
url: /zh/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public class TiffUndefinedType extends TiffDataType
```

该 tiff 未定义类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffUndefinedType(int tagId)](#TiffUndefinedType-int-) | 初始化 `TiffUndefinedType` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getData()](#getData--) | 获取或设置数据。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置数据。 |
| [getCount()](#getCount--) | 获取元素的数量。 |
| [getTagType()](#getTagType--) | 获取标签类型。 |
| [getValue()](#getValue--) | 获取或设置此数据类型包含的值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 获取或设置此数据类型包含的值。 |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | 写入附加标签数据。 |
### TiffUndefinedType(int tagId) {#TiffUndefinedType-int-}
```
public TiffUndefinedType(int tagId)
```


初始化 `TiffUndefinedType` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagId | int | 标签 ID。 |

### getData() {#getData--}
```
public byte[] getData()
```


获取或设置数据。

值：数据。

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


获取或设置数据。

值：数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### getCount() {#getCount--}
```
public long getCount()
```


获取元素的数量。

值：元素的数量。

**Returns:**
long
### getTagType() {#getTagType--}
```
public int getTagType()
```


获取标签类型。

值：标签类型。

**Returns:**
int
### getValue() {#getValue--}
```
public Object getValue()
```


获取或设置此数据类型包含的值。

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


获取或设置此数据类型包含的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


写入附加标签数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | 数据流。 |

**Returns:**
long - 实际写入的字节数。
