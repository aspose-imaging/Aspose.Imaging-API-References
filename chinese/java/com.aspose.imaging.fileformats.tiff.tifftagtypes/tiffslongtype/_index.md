---
title: "TiffSLongType"
second_title: "Aspose.Imaging for Java API 参考"
description: "tiff 有符号 long 类型。"
type: docs
weight: 22
url: /zh/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffSLongType extends TiffCommonArrayType
```

tiff 有符号 long 类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffSLongType(int tagId)](#TiffSLongType-int-) | 初始化 `TiffSLongType` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValues()](#getValues--) | 获取或设置值。 |
| [setValues(int[] value)](#setValues-int---) | 获取或设置值。 |
| [getValuesContainer()](#getValuesContainer--) | 获取值容器。 |
| [getElementSize()](#getElementSize--) | 获取元素的字节大小。 |
| [getTagType()](#getTagType--) | 获取标签类型。 |
| [getValue()](#getValue--) | 获取或设置此数据类型包含的值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 获取或设置此数据类型包含的值。 |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | 写入附加标签数据。 |
### TiffSLongType(int tagId) {#TiffSLongType-int-}
```
public TiffSLongType(int tagId)
```


初始化 `TiffSLongType` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagId | int | 标签 ID。 |

### getValues() {#getValues--}
```
public int[] getValues()
```


获取或设置值。

值：这些值。

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


获取或设置值。

值：这些值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


获取值容器。

值：值的容器。

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


获取元素的字节大小。

值：元素大小（字节）。

**Returns:**
byte
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
