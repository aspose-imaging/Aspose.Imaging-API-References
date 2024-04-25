---
title: TiffStreamReader
second_title: Aspose.Imaging for Java API Reference
description: The tiff stream for handling little endian tiff file format.
type: docs
weight: 13
url: /com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

The tiff stream for handling little endian tiff file format.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Initializes a new instance of the `TiffStreamReader` class. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Initializes a new instance of the `TiffStreamReader` class. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Initializes a new instance of the `TiffStreamReader` class. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | Initializes a new instance of the `TiffStreamReader` class. |
## Methods

| Method | Description |
| --- | --- |
| [getLength()](#getLength--) | Gets the reader length. |
| [getThrowExceptions()](#getThrowExceptions--) | Gets or sets a value indicating whether exceptions are thrown on incorrect data processing (reading or writing to stream). |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Gets or sets a value indicating whether exceptions are thrown on incorrect data processing (reading or writing to stream). |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Reads an array of byte values from the stream. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Reads an array of unsigned byte values from the stream. |
| [readDouble(long position)](#readDouble-long-) | Read a single double value from the stream. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Reads an array of double values from the stream. |
| [readFloat(long position)](#readFloat-long-) | Read a single float value from the stream. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Reads an array of float values from the stream. |
| [readRational(long position)](#readRational-long-) | Read a single rational number value from the stream. |
| [readSRational(long position)](#readSRational-long-) | Read a single signed rational number value from the stream. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Reads an array of rational values from the stream. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Reads an array of signed rational values from the stream. |
| [readSByte(long position)](#readSByte-long-) | Reads signed byte data from the stream. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Reads an array of signed byte values from the stream. |
| [readSInt(long position)](#readSInt-long-) | Read signed integer value from the stream. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | Reads an array of signed integer values from the stream. |
| [readSShort(long position)](#readSShort-long-) | Read signed short value from the stream. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Reads an array of signed short values from the stream. |
| [readUInt(long position)](#readUInt-long-) | Read unsigned integer value from the stream. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | Reads an array of unsigned integer values from the stream. |
| [readUShort(long position)](#readUShort-long-) | Read unsigned short value from the stream. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Reads an array of unsigned integer values from the stream. |
| [readLong(long position)](#readLong-long-) | Read unsigned long value from the stream. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | Reads an array of ulong values from the stream. |
| [readULong(long position)](#readULong-long-) | Read unsigned long value from the stream. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Reads an array of ulong values from the stream. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Converts the underlying data to the stream container. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Initializes a new instance of the `TiffStreamReader` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The byte array data. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Initializes a new instance of the `TiffStreamReader` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The byte array data. |
| startIndex | int | The start index into `data`. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Initializes a new instance of the `TiffStreamReader` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The byte array data. |
| startIndex | int | The start index into `data`. |
| dataLength | int | Length of the data. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Initializes a new instance of the `TiffStreamReader` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |

### getLength() {#getLength--}
```
public long getLength()
```


Gets the reader length.

Value: The reader length.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Gets or sets a value indicating whether exceptions are thrown on incorrect data processing (reading or writing to stream).

Value: `true` if exceptions are thrown on incorrect data processing; otherwise, the error conditions are silently ignored.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Gets or sets a value indicating whether exceptions are thrown on incorrect data processing (reading or writing to stream).

Value: `true` if exceptions are thrown on incorrect data processing; otherwise, the error conditions are silently ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Reads an array of byte values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | byte[] | The array to fill. |
| arrayIndex | int | The array index to start putting values to. |
| position | long | The stream position to read from. |
| count | long | The elements count to read. |

**Returns:**
long - The array of byte values.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Reads an array of unsigned byte values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
byte[] - The array of unsigned byte values.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Read a single double value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
double - The single double value.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Reads an array of double values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
double[] - The array of double values.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Read a single float value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
float - The single float value.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Reads an array of float values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
float[] - The array of float values.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Read a single rational number value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Read a single signed rational number value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Reads an array of rational values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - The array of rational values.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Reads an array of signed rational values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - The array of signed rational values.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Reads signed byte data from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
byte - The signed byte value.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Reads an array of signed byte values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
byte[] - The array of signed byte values.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


Read signed integer value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
int - A signed integer value.
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


Reads an array of signed integer values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
int[] - The array of signed integer values.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Read signed short value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
short - A signed short value.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Reads an array of signed short values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
short[] - The array of signed short values.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


Read unsigned integer value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
long - An unsigned integer value.
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


Reads an array of unsigned integer values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
long[] - The array of unsigned integer values.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Read unsigned short value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
int - An unsigned short value.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Reads an array of unsigned integer values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
int[] - The array of unsigned integer values.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


Read unsigned long value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
long - An unsigned short value.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


Reads an array of ulong values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
long[] - The ulong array.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


Read unsigned long value from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |

**Returns:**
long - An unsigned short value.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


Reads an array of ulong values from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to read from. |
| count | long | The elements count. |

**Returns:**
long[] - The ulong array.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Converts the underlying data to the stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPosition | long | The start position to start conversion from. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
