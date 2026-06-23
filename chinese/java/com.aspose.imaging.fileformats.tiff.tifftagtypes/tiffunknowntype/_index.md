---
title: "TiffUnknownType"
second_title: "Aspose.Imaging for Java API 参考"
description: "未知的 tiff 类型。"
type: docs
weight: 27
url: /zh/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

未知的 tiff 类型。如果无法识别 tiff 标记，则实例化此类型。

注意 `TiffUnknownType` 不会序列化回流。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | 初始化 `TiffUnknownType` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 获取元素的数量。 |
| [getOffsetOrValue()](#getOffsetOrValue--) | 获取附加数据的偏移值，或在计数为 1 时获取值本身。 |
| [getStream()](#getStream--) | 获取用于读取附加数据的流。 |
| [getTagType()](#getTagType--) | 获取标签类型。 |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | 获取附加标签值的字节大小（当标签无法容纳完整标签值时）。 |
| [getValue()](#getValue--) | 获取或设置此数据类型包含的值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 获取或设置此数据类型包含的值。 |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | 写入附加标签数据。 |
| [toString()](#toString--) | 返回表示此实例的 `System.String`。 |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


初始化 `TiffUnknownType` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | 用于读取的流。 |
| tagType | int | 标签的类型。 |
| tagId | int | 标签 ID。 |
| 计数 | long | 计数值。 |
| offsetOrValue | long | 偏移或值。 |

### getCount() {#getCount--}
```
public long getCount()
```


获取元素的数量。

值：元素的数量。

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


获取附加数据的偏移值，或在计数为 1 时获取值本身。

值：偏移量或值。

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


获取用于读取附加数据的流。

值：用于读取数据的流。

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


获取标签类型。

值：标签类型。

**Returns:**
int
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


获取附加标签值的字节大小（当标签无法容纳完整标签值时）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sizeOfTagValue | byte | 标签值的大小：对于 BigTiff 为 4 或 8。 |

**Returns:**
long - 附加数据的大小（字节）。
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
### toString() {#toString--}
```
public String toString()
```


返回表示此实例的 `System.String`。

**Returns:**
java.lang.String - 表示此实例的 `System.String`。
