---
title: "TiffDoubleType"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "tiff double 类型。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

tiff double 类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | 初始化 `TiffDoubleType` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValues()](#getValues--) | 获取值。 |
| [setValues(double[] value)](#setValues-double---) | 设置值。 |
| [getValuesContainer()](#getValuesContainer--) | 获取值容器。 |
| [getTagType()](#getTagType--) | 获取标签类型。 |
| [getElementSize()](#getElementSize--) | 获取元素的字节大小。 |
| [getValue()](#getValue--) | 获取此数据类型包含的值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 设置此数据类型包含的值。 |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | 写入附加标签数据。 |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


初始化 `TiffDoubleType` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagId | int | 标签 ID。 |

### getValues() {#getValues--}
```
public double[] getValues()
```


获取值。

**Returns:**
double[] - 值。
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


设置值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double[] | 值。 |

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

**Returns:**
int - 标签类型。
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


获取元素的字节大小。

**Returns:**
byte - 元素大小（字节）。
### getValue() {#getValue--}
```
public Object getValue()
```


获取此数据类型包含的值。

**Returns:**
java.lang.Object - 值。
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


设置此数据类型包含的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object | 值。 |

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
