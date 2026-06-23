---
title: "TiffStreamReader"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于处理小端 tiff 文件格式的 tiff 流。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

用于处理小端 tiff 文件格式的 tiff 流。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | 初始化 `TiffStreamReader` 类的新实例。 |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | 初始化 `TiffStreamReader` 类的新实例。 |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | 初始化 `TiffStreamReader` 类的新实例。 |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | 初始化 `TiffStreamReader` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLength()](#getLength--) | 获取读取器长度。 |
| [getThrowExceptions()](#getThrowExceptions--) | 获取或设置一个值，指示在数据处理错误（读取或写入流）时是否抛出异常。 |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | 获取或设置一个值，指示在数据处理错误（读取或写入流）时是否抛出异常。 |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | 从流中读取字节值数组。 |
| [readBytes(long position, long count)](#readBytes-long-long-) | 从流中读取无符号字节值数组。 |
| [readDouble(long position)](#readDouble-long-) | 从流中读取单个 double 值。 |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | 从流中读取 double 值数组。 |
| [readFloat(long position)](#readFloat-long-) | 从流中读取单个 float 值。 |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | 从流中读取 float 值数组。 |
| [readRational(long position)](#readRational-long-) | 从流中读取单个有理数值。 |
| [readSRational(long position)](#readSRational-long-) | 从流中读取单个有符号有理数值。 |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | 从流中读取有理数值数组。 |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | 从流中读取有符号有理数值数组。 |
| [readSByte(long position)](#readSByte-long-) | 从流中读取有符号字节数据。 |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | 从流中读取有符号字节值数组。 |
| [readSInt(long position)](#readSInt-long-) | 从流中读取有符号整数值。 |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | 从流中读取有符号整数值数组。 |
| [readSShort(long position)](#readSShort-long-) | 从流中读取有符号短整数值。 |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | 从流中读取有符号短整型值数组。 |
| [readUInt(long position)](#readUInt-long-) | 从流中读取无符号整数值。 |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | 从流中读取无符号整数值数组。 |
| [readUShort(long position)](#readUShort-long-) | 从流中读取无符号短整型值。 |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | 从流中读取无符号整数值数组。 |
| [readLong(long position)](#readLong-long-) | 从流中读取无符号长整型值。 |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | 从流中读取长整型值数组。 |
| [readULong(long position)](#readULong-long-) | 从流中读取无符号长整型值。 |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | 从流中读取无符号长整型值数组。 |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | 将底层数据转换为流容器。 |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


初始化 `TiffStreamReader` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 字节数组数据。 |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


初始化 `TiffStreamReader` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 字节数组数据。 |
| startIndex | int | `data` 的起始索引。 |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


初始化 `TiffStreamReader` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 字节数组数据。 |
| startIndex | int | `data` 的起始索引。 |
| dataLength | int | 数据的长度。 |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


初始化 `TiffStreamReader` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流容器。 |

### getLength() {#getLength--}
```
public long getLength()
```


获取读取器长度。

值：读取器长度。

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


获取或设置一个值，指示在数据处理错误（读取或写入流）时是否抛出异常。

值：如果在错误的数据处理时抛出异常则为 `true`；否则，错误情况将被静默忽略。

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


获取或设置一个值，指示在数据处理错误（读取或写入流）时是否抛出异常。

值：如果在错误的数据处理时抛出异常则为 `true`；否则，错误情况将被静默忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


从流中读取字节值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数组 | byte[] | 要填充的数组。 |
| arrayIndex | int | 开始放置值的数组索引。 |
| 位置 | long | 要读取的流位置。 |
| 计数 | long | 要读取的元素数量。 |

**Returns:**
long - 字节值数组。
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


从流中读取无符号字节值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
byte[] - 无符号字节值数组。
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


从流中读取单个 double 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
double - 单个 double 值。
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


从流中读取 double 值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
double[] - double 值数组。
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


从流中读取单个 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
float - 单个 float 值。
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


从流中读取 float 值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
float[] - float 值数组。
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


从流中读取单个有理数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


从流中读取单个有符号有理数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


从流中读取有理数值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - 有理数值数组。
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


从流中读取有符号有理数值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - 有符号有理数值数组。
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


从流中读取有符号字节数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
byte - 有符号字节值。
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


从流中读取有符号字节值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
byte[] - 有符号字节值的数组。
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


从流中读取有符号整数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
int - 有符号整数值。
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


从流中读取有符号整数值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
int[] - 有符号整数值的数组。
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


从流中读取有符号短整数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
short - 有符号短整数值。
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


从流中读取有符号短整型值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
short[] - 有符号短整数值的数组。
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


从流中读取无符号整数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
long - 无符号整数值。
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


从流中读取无符号整数值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
long[] - 无符号整数值的数组。
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


从流中读取无符号短整型值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
int - 无符号短整数值。
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


从流中读取无符号整数值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
int[] - 无符号整数值的数组。
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


从流中读取无符号长整型值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
long - 无符号短整数值。
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


从流中读取长整型值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
long[] - 长整数数组。
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


从流中读取无符号长整型值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |

**Returns:**
long - 无符号短整数值。
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


从流中读取无符号长整型值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 读取的位置。 |
| 计数 | long | 元素计数。 |

**Returns:**
long[] - 长整数数组。
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


将底层数据转换为流容器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startPosition | long | 开始转换的起始位置。 |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
