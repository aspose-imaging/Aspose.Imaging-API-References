---
title: "TiffStreamWriter"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Tiff 流写入器。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter extends TiffStreamSeeker implements ISynchronizable
```

Tiff 流写入器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.imaging.StreamContainer-) | 初始化 `TiffStreamWriter` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | 获取一个可用于同步对同步资源访问的对象。 |
| [getPosition()](#getPosition--) | 获取或设置流位置。 |
| [setPosition(long value)](#setPosition-long-) | 获取或设置流位置。 |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | 写入指定的数据。 |
| [write(byte[] data)](#write-byte---) | 写入指定的数据。 |
| [writeDouble(double data)](#writeDouble-double-) | 向流写入单个 double 值。 |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | 向流写入 double 值数组。 |
| [writeFloat(float data)](#writeFloat-float-) | 向流写入单个 float 值。 |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | 向流写入 float 值数组。 |
| [writeRational(TiffRational data)](#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-) | 将单个有理数值写入流。 |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-) | 将单个有符号有理数值写入流。 |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---) | 将无符号有理数数组写入流。 |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---) | 将有符号有理数数组写入流。 |
| [writeSByte(byte data)](#writeSByte-byte-) | 将单个有符号字节值写入流。 |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | 将有符号字节数组写入流。 |
| [writeIntArray(int[] data)](#writeIntArray-int---) | 将整数数组写入流。 |
| [writeSShort(short data)](#writeSShort-short-) | 将单个短整型值写入流。 |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | 将短整型数组写入流。 |
| [writeSInt(int data)](#writeSInt-int-) | 将单个整数值写入流。 |
| [writeUByte(byte data)](#writeUByte-byte-) | 将单个字节值写入流。 |
| [writeUInt(long data)](#writeUInt-long-) | 将单个无符号整数值写入流。 |
| [writeUIntArray(long[] data)](#writeUIntArray-long---) | 将无符号整数数组写入流。 |
| [writeUShort(int data)](#writeUShort-int-) | 将单个无符号短整型值写入流。 |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | 将无符号短整型数组写入流。 |
| [writeSLong(long data)](#writeSLong-long-) | 将有符号长整型数组写入流。 |
| [writeSLongArray(long[] data)](#writeSLongArray-long---) | 将有符号长整型数组写入流。 |
| [writeULong(long data)](#writeULong-long-) | 将无符号长整型数组写入流。 |
| [writeULongArray(long[] data)](#writeULongArray-long---) | 将无符号长整型数组写入流。 |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.imaging.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


初始化 `TiffStreamWriter` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流写入器。 |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取一个可用于同步对同步资源访问的对象。

值：可用于同步对同步资源的访问的对象。

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


获取或设置流位置。

值：流位置。

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


获取或设置流位置。

值：流位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


写入指定的数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 要写入的数据。 |
| offset | int | 数据偏移量。 |
| dataLength | int | 要写入的数据长度。 |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


写入指定的数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 要写入的数据。 |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


向流写入单个 double 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | double | 要写入的值。 |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


向流写入 double 值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | double[] | 要写入的数组。 |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


向流写入单个 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | float | 要写入的值。 |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


向流写入 float 值数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | float[] | 要写入的数组。 |

### writeRational(TiffRational data) {#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


将单个有理数值写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | 要写入的值。 |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


将单个有符号有理数值写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | 要写入的值。 |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


将无符号有理数数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | 要写入的数组。 |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


将有符号有理数数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | 要写入的数组。 |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


将单个有符号字节值写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte | 要写入的值。 |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


将有符号字节数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 要写入的数组。 |

### writeIntArray(int[] data) {#writeIntArray-int---}
```
public void writeIntArray(int[] data)
```


将整数数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | int[] | 要写入的数组。 |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


将单个短整型值写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | short | 要写入的值。 |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


将短整型数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | short[] | 要写入的数组。 |

### writeSInt(int data) {#writeSInt-int-}
```
public void writeSInt(int data)
```


将单个整数值写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | int | 要写入的值。 |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


将单个字节值写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte | 要写入的值。 |

### writeUInt(long data) {#writeUInt-long-}
```
public void writeUInt(long data)
```


将单个无符号整数值写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | long | 要写入的值。 |

### writeUIntArray(long[] data) {#writeUIntArray-long---}
```
public void writeUIntArray(long[] data)
```


将无符号整数数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | long[] | 要写入的数组。 |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


将单个无符号短整型值写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | int | 要写入的值。 |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


将无符号短整型数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | int[] | 要写入的数组。 |

### writeSLong(long data) {#writeSLong-long-}
```
public final void writeSLong(long data)
```


将有符号长整型数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | long | 要写入的数组。 |

### writeSLongArray(long[] data) {#writeSLongArray-long---}
```
public final void writeSLongArray(long[] data)
```


将有符号长整型数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | long[] | 要写入的数组。 |

### writeULong(long data) {#writeULong-long-}
```
public final void writeULong(long data)
```


将无符号长整型数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | long | 要写入的数组。 |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public final void writeULongArray(long[] data)
```


将无符号长整型数组写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | long[] | 要写入的数组。 |

