---
title: "TiffASCIIType"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "tiff ascii 类型。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

tiff ascii 类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | 初始化 `TiffASCIIType` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) | 获取或设置文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置文本。 |
| [getCount()](#getCount--) | 获取元素的计数。 |
| [getTagType()](#getTagType--) | 获取标签类型。 |
| [getValue()](#getValue--) | 获取或设置此数据类型包含的值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 获取或设置此数据类型包含的值。 |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | 写入附加标签数据。 |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


初始化 `TiffASCIIType` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagId | int | 标签 ID。 |

### getText() {#getText--}
```
public String getText()
```


获取或设置文本。

**Returns:**
java.lang.String - 文本。
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


获取或设置文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 文本。 |

### getCount() {#getCount--}
```
public long getCount()
```


获取元素的计数。

**Returns:**
long - 元素计数。
### getTagType() {#getTagType--}
```
public int getTagType()
```


获取标签类型。

**Returns:**
int - 标签类型。
### getValue() {#getValue--}
```
public Object getValue()
```


获取或设置此数据类型包含的值。

**Returns:**
java.lang.Object - 值。
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


获取或设置此数据类型包含的值。

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
