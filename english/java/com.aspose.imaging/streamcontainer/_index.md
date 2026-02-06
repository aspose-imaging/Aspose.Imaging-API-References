---
title: StreamContainer
second_title: Aspose.Imaging for Java API Reference
description: Represents stream container which contains the stream and provides stream processing routines.
type: docs
weight: 109
url: /java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Represents stream container which contains the stream and provides stream processing routines.
## Constructors

| Constructor | Description |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | Initializes a new instance of the `StreamContainer` class. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | Initializes a new instance of the `StreamContainer` class. |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | Initializes a new instance of the `StreamContainer` class. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | Initializes a new instance of the `StreamContainer` class. |
## Fields

| Field | Description |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Specifies read and write bytes count when reading sequentially. |
## Methods

| Method | Description |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | Performs an explicit conversion from `com.aspose.imaging.StreamContainer` to `System.IO.Stream`. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the synchronized resource. |
| [getPosition()](#getPosition--) | Gets or sets the current position within the stream. |
| [setPosition(long value)](#setPosition-long-) | Gets or sets the current position within the stream. |
| [getStream()](#getStream--) | Gets the data stream. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Gets a value indicating whether this stream is disposed on close. |
| [getLength()](#getLength--) | Gets or sets the stream length in bytes. |
| [setLength(long value)](#setLength-long-) | Gets or sets the stream length in bytes. |
| [canRead()](#canRead--) | Gets a value indicating whether stream supports reading. |
| [canSeek()](#canSeek--) | Gets a value indicating whether stream supports seeking. |
| [canWrite()](#canWrite--) | Gets a value indicating whether stream supports writing. |
| [flush()](#flush--) | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| [write(byte[] bytes)](#write-byte---) | Writes all specified bytes to the stream. |
| [writeByte(byte value)](#writeByte-byte-) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [read(byte[] bytes)](#read-byte---) | Reads bytes to fill the specified bytes buffer. |
| [toBytes()](#toBytes--) | Converts the stream data to the `byte` array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Converts the stream data to the `byte` array. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [readByte()](#readByte--) | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [seek(long offset, int origin)](#seek-long-int-) | Sets the position within the current stream. |
| [seekBegin()](#seekBegin--) | Sets the stream position to the beginning of the stream. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Saves (copies) the stream's data to the specified stream. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Saves (copies) all the stream's data to the specified stream. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Saves (copies) the stream's data to the specified stream. |
| [save(String filePath)](#save-java.lang.String-) | Saves (copies) the stream's data to the specified stream. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Saves (copies) the stream's data to the specified stream. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Saves (copies) the stream's data to the specified stream. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | Copies the contained data to another `StreamContainer`. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | Copies the contained data to another `StreamContainer`. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


Initializes a new instance of the `StreamContainer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


Initializes a new instance of the `StreamContainer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


Initializes a new instance of the `StreamContainer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The data stream. |
| disposeStream | boolean | if set to `true` the stream will be disposed when container is disposed. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


Initializes a new instance of the `StreamContainer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The data stream. |
| disposeStream | boolean | if set to `true` the stream will be disposed when container is disposed. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Specifies read and write bytes count when reading sequentially.

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Performs an explicit conversion from `com.aspose.imaging.StreamContainer` to `System.IO.Stream`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |

**Returns:**
com.aspose.ms.System.IO.Stream - The result of the conversion.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the synchronized resource.

Value: The object that can be used to synchronize access to the synchronized resource.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.

Value: The current stream position.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.

Value: The current stream position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


Gets the data stream.

Value: The data stream.

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Gets a value indicating whether this stream is disposed on close.

Value: `true` if stream is disposed on close; otherwise, `false`.

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


Gets or sets the stream length in bytes. This value is less than the Stream\#getLength().getLength() by the starting stream position passed in the StreamContainer constructor.

Value: The stream length.

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Gets or sets the stream length in bytes. This value is less than the Stream\#getLength().getLength() by the starting stream position passed in the StreamContainer constructor.

Value: The stream length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


Gets a value indicating whether stream supports reading.

Value: `true` if stream supports reading; otherwise, `false`.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Gets a value indicating whether stream supports seeking.

Value: `true` if stream supports seeking; otherwise, `false`.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Gets a value indicating whether stream supports writing.

Value: `true` if stream supports writing; otherwise, `false`.

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Clears all buffers for this stream and causes any buffered data to be written to the underlying device.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Writes all specified bytes to the stream.

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

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Saves (copies) the stream's data to the specified stream. Uses default buffer size `ReadWriteBytesCount` and stream `Length` value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | The stream to save the data to. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Saves (copies) all the stream's data to the specified stream. Uses stream `Length` value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | The stream to save the data to. |
| bufferSize | int | The buffer. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Saves (copies) the stream's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | The stream to save the data to. |
| bufferSize | int | The buffer size. By default `ReadWriteBytesCount` value is used. |
| length | long | The stream data length to copy. By default, the length is set to `Length` value. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Saves (copies) the stream's data to the specified stream. Uses default buffer size `ReadWriteBytesCount` and stream `Length` value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the stream data to. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Saves (copies) the stream's data to the specified stream. Uses stream `Length` value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the stream data to. |
| bufferSize | int | The buffer size. By default `ReadWriteBytesCount` value is used. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Saves (copies) the stream's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the stream data to. |
| bufferSize | int | The buffer size. By default `ReadWriteBytesCount` value is used. |
| length | long | The stream data length to copy. By default, the length is set to `Length` value. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Copies the contained data to another `StreamContainer`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container to copy to. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Copies the contained data to another `StreamContainer`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container to copy to. |
| length | long | The bytes count to write. |

