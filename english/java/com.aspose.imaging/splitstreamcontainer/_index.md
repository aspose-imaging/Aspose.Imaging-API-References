---
title: SplitStreamContainer
second_title: Aspose.Imaging for Java API Reference
description: Represents split stream container which contains the stream and provides stream processing routines.
type: docs
weight: 109
url: /java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Represents split stream container which contains the stream and provides stream processing routines.
## Constructors

| Constructor | Description |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Initializes a new instance of the `SplitStreamContainer` class. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Initializes a new instance of the `SplitStreamContainer` class. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | Initializes a new instance of the `SplitStreamContainer` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the synchronized resource. |
| [getPosition()](#getPosition--) | Gets the current position within the stream. |
| [setPosition(long value)](#setPosition-long-) | Sets the current position within the stream. |
| [getLength()](#getLength--) | Gets the stream length in bytes. |
| [setLength(long value)](#setLength-long-) | Sets the stream length in bytes. |
| [canRead()](#canRead--) | Gets a value indicating whether stream supports reading. |
| [canSeek()](#canSeek--) | Gets a value indicating whether stream supports seeking. |
| [canWrite()](#canWrite--) | Gets a value indicating whether stream supports writing. |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | Inserts the stream container into specified position. |
| [flush()](#flush--) | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| [write(byte[] bytes)](#write-byte---) | Writes all of the specified bytes to the stream. |
| [writeByte(byte value)](#writeByte-byte-) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [read(byte[] bytes)](#read-byte---) | Reads bytes to fill the specified bytes buffer. |
| [toBytes()](#toBytes--) | Converts the stream data to the `byte` array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Converts the stream data to the `byte` array. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [readByte()](#readByte--) | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [seek(long offset, int origin)](#seek-long-int-) | Sets the position within the current stream. |
| [seekBegin()](#seekBegin--) | Sets the stream position to the beginning of the stream. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Initializes a new instance of the `SplitStreamContainer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Initializes a new instance of the `SplitStreamContainer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The data stream. |
| disposeStream | boolean | if set to `true` the stream will be disposed when container is disposed. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Initializes a new instance of the `SplitStreamContainer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |
| disposeStream | boolean | if set to `true` disposes stream. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the synchronized resource.

**Returns:**
java.lang.Object - The object that can be used to synchronize access to the synchronized resource.
### getPosition() {#getPosition--}
```
public long getPosition()
```


Gets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.

**Returns:**
long - The current stream position.
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The current stream position. |

### getLength() {#getLength--}
```
public long getLength()
```


Gets the stream length in bytes. This value is less than the `System.IO.Stream.Length` by the starting stream position passed in the StreamContainer constructor.

**Returns:**
long - The stream length.
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Sets the stream length in bytes. This value is less than the `System.IO.Stream.Length` by the starting stream position passed in the StreamContainer constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The stream length. |

### canRead() {#canRead--}
```
public boolean canRead()
```


Gets a value indicating whether stream supports reading.

**Returns:**
boolean - `true` if stream supports reading; otherwise, `false`.
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Gets a value indicating whether stream supports seeking.

**Returns:**
boolean - `true` if stream supports seeking; otherwise, `false`.
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Gets a value indicating whether stream supports writing.

**Returns:**
boolean - `true` if stream supports writing; otherwise, `false`.
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


Inserts the stream container into specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | The position to insert to. |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container to insert. |
| disposeStream | boolean | if set to `true` disposes stream. |

### flush() {#flush--}
```
public void flush()
```


Clears all buffers for this stream and causes any buffered data to be written to the underlying device.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Writes all of the specified bytes to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] | The bytes to write. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Writes a byte to the current position in the stream and advances the position within the stream by one byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The byte to write to the stream. |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Reads bytes to fill the specified bytes buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] | The bytes to fill. |

**Returns:**
int - The number of bytes read. This value can be less than the number of bytes in the buffer if there is not enough bytes in the stream.
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Converts the stream data to the `byte` array.

**Returns:**
byte[] - The stream data converted to the `byte` array.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Converts the stream data to the `byte` array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to start reading bytes from. |
| bytesCount | long | The bytes count to read. |

**Returns:**
byte[] - The stream data converted to the `byte` array.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | An array of bytes. When this method returns, the buffer contains the specified byte array with the values between `offset` and (`offset` + `count` - 1) replaced by the bytes read from the current source. |
| offset | int | The zero-based byte offset in `buffer` at which to begin storing the data read from the current stream. |
| count | int | The maximum number of bytes to be read from the current stream. |

**Returns:**
int - The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached.
### readByte() {#readByte--}
```
public int readByte()
```


Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream.

**Returns:**
int - The unsigned byte cast to an Int32, or -1 if at the end of the stream.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Sets the position within the current stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offset | long | A byte offset relative to the `origin` parameter. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| origin | int | A value of type `System.IO.SeekOrigin` indicating the reference point used to obtain the new position. |

**Returns:**
long - The new position within the current stream.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | An array of bytes. This method copies `count` bytes from `buffer` to the current stream. |
| offset | int | The zero-based byte offset in `buffer` at which to begin copying bytes to the current stream. |
| count | int | The number of bytes to be written to the current stream. |

