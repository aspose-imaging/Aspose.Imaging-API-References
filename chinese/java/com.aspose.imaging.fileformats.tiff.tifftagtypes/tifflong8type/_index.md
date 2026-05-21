---
title: "TiffLong8Type"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Tiff unsigned 64-bit 类型。"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffLong8Type extends TiffCommonArrayType
```

Tiff unsigned 64-bit 类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffLong8Type(int tagId)](#TiffLong8Type-int-) | 初始化 [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type) 类的新实例。 |
| [TiffLong8Type(int tagId, long[] values)](#TiffLong8Type-int-long---) | 初始化 [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValues()](#getValues--) | 获取值。 |
| [setValues(long[] value)](#setValues-long---) | 设置值。 |
| [getValuesContainer()](#getValuesContainer--) | 获取值容器。 |
| [getTagType()](#getTagType--) | 获取标签类型。 |
| [getValue()](#getValue--) | 获取此数据类型包含的值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 设置此数据类型包含的值。 |
| [getElementSize()](#getElementSize--) | 获取元素大小。 |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | 写入附加标签数据。 |
### TiffLong8Type(int tagId) {#TiffLong8Type-int-}
```
public TiffLong8Type(int tagId)
```


初始化 [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagId | int | 标签 ID。 |

### TiffLong8Type(int tagId, long[] values) {#TiffLong8Type-int-long---}
```
public TiffLong8Type(int tagId, long[] values)
```


初始化 [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tifflong8type) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagId | int | 标签 ID。 |
| 值 | long[] |  |

### getValues() {#getValues--}
```
public final long[] getValues()
```


获取值。

值：标签的值。

**Returns:**
long[] - 值。
### setValues(long[] value) {#setValues-long---}
```
public final void setValues(long[] value)
```


设置值。

值：标签的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long[] | 值。 |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


获取值容器。

**Returns:**
com.aspose.ms.System.Array - 值容器。
### getTagType() {#getTagType--}
```
public int getTagType()
```


获取标签类型。

值：标签类型。

**Returns:**
int - 标签类型。
### getValue() {#getValue--}
```
public Object getValue()
```


获取此数据类型包含的值。

**Returns:**
java.lang.Object - 此数据类型包含的值。
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


设置此数据类型包含的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object | 此数据类型包含的值。 |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


获取元素大小。

**Returns:**
byte - 元素大小。
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
