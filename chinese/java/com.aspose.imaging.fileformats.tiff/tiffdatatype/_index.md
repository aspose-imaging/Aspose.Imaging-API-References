---
title: "TiffDataType"
second_title: "Aspose.Imaging for Java API 参考"
description: "TIFF 数据类型。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

TIFF 数据类型。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getElementSize()](#getElementSize--) | 获取元素的字节大小。 |
| [getDataSize()](#getDataSize--) | 获取标签值的大小。 |
| [getCount()](#getCount--) | 获取元素的数量。 |
| [getId()](#getId--) | 获取标签 ID（数字）。 |
| [getTagId()](#getTagId--) | 获取标签 ID。 |
| [getTagType()](#getTagType--) | 获取标签类型。 |
| [getAlignedDataSize(byte sizeOfTagValue)](#getAlignedDataSize-byte-) | 获取在 4 字节（int）或 8 字节（long）边界对齐的数据大小。 |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | 获取附加标签值的字节大小（当标签无法容纳完整标签值时）。 |
| [getValue()](#getValue--) | 获取此数据类型包含的值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 设置此数据类型包含的值。 |
| [isValid()](#isValid--) | 获取指示标签数据是否有效的值。 |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | 读取标签数据。 |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于该对象之前、之后，还是相同位置。 |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | 对该实例执行深度克隆。 |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | 写入标签数据。 |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | 写入附加标签数据。 |
| [toString()](#toString--) | 返回表示此实例的 `System.String`。 |
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


获取元素的字节大小。

**Returns:**
byte - 元素的字节大小。
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


获取标签值的大小。

**Returns:**
long - 标签值的大小。
### getCount() {#getCount--}
```
public abstract long getCount()
```


获取元素的数量。

值：元素的数量。

**Returns:**
long - 元素的数量。
### getId() {#getId--}
```
public final int getId()
```


获取标签 ID（数字）。

**Returns:**
int - 标签 ID（数字）。
### getTagId() {#getTagId--}
```
public int getTagId()
```


获取标签 ID。

**Returns:**
int - 标签 ID。
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


获取标签类型。

**Returns:**
int - 标签类型。
### getAlignedDataSize(byte sizeOfTagValue) {#getAlignedDataSize-byte-}
```
public final long getAlignedDataSize(byte sizeOfTagValue)
```


获取在 4 字节（int）或 8 字节（long）边界对齐的数据大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sizeOfTagValue | byte | 标签值的大小。 |

**Returns:**
long - 对齐后的数据大小（字节）。
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
public abstract Object getValue()
```


获取此数据类型包含的值。

**Returns:**
java.lang.Object - 值。
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


设置此数据类型包含的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object | 值。 |

### isValid() {#isValid--}
```
public boolean isValid()
```


获取一个值，指示标签数据是否有效。有效的标签包含可以保留的数据。无效的标签无法存储。

**Returns:**
boolean - 如果标签数据有效则为 `true`；否则为 `false`。
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


读取标签数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | 数据流。 |
| 位置 | long | 标签位置。 |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例在排序顺序中是位于该对象之前、之后，还是相同位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 用于与此实例比较的对象。 |

**Returns:**
int - 一个 32 位有符号整数，指示被比较对象的相对顺序。返回值含义如下：值 含义 小于零 此实例小于 `obj`。 零 此实例等于 `obj`。 大于零 此实例大于 `obj`。
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


对该实例执行深度克隆。

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


写入标签数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | 数据流。 |
| additionalDataOffset | long | 写入附加数据的偏移量。 |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
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
