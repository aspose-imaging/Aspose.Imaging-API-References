---
title: "StreamContainer"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示流容器，该容器包含流并提供流处理例程。"
type: docs
weight: 109
url: /zh/java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

表示流容器，该容器包含流并提供流处理例程。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | 初始化 `StreamContainer` 类的新实例。 |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | 初始化 `StreamContainer` 类的新实例。 |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | 初始化 `StreamContainer` 类的新实例。 |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | 初始化 `StreamContainer` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | 指定顺序读取时的读取和写入字节数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | 执行从 `com.aspose.imaging.StreamContainer` 到 `System.IO.Stream` 的显式转换。 |
| [getSyncRoot()](#getSyncRoot--) | 获取一个可用于同步访问同步资源的对象。 |
| [getPosition()](#getPosition--) | 获取或设置流中的当前位置。 |
| [setPosition(long value)](#setPosition-long-) | 获取或设置流中的当前位置。 |
| [getStream()](#getStream--) | 获取数据流。 |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | 获取一个值，指示此流在关闭时是否被释放。 |
| [getLength()](#getLength--) | 获取或设置流的字节长度。 |
| [setLength(long value)](#setLength-long-) | 获取或设置流的字节长度。 |
| [canRead()](#canRead--) | 获取指示流是否支持读取的值。 |
| [canSeek()](#canSeek--) | 获取指示流是否支持定位的值。 |
| [canWrite()](#canWrite--) | 获取指示流是否支持写入的值。 |
| [flush()](#flush--) | 清除此流的所有缓冲区，并导致任何缓冲数据写入底层设备。 |
| [write(byte[] bytes)](#write-byte---) | 将所有指定的字节写入流。 |
| [writeByte(byte value)](#writeByte-byte-) | 向流的当前位写入一个字节，并将流中的位置前移一个字节。 |
| [read(byte[] bytes)](#read-byte---) | 读取字节以填充指定的字节缓冲区。 |
| [toBytes()](#toBytes--) | 将流数据转换为 `byte` 数组。 |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | 将流数据转换为 `byte` 数组。 |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | 从当前流读取一系列字节，并将流中的位置前移已读取的字节数。 |
| [readByte()](#readByte--) | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到流的末尾，则返回 -1。 |
| [seek(long offset, int origin)](#seek-long-int-) | 设置当前流中的位置。 |
| [seekBegin()](#seekBegin--) | 将流位置设置为流的开头。 |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | 向当前流写入一系列字节，并将此流中的当前位置前移已写入的字节数。 |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | 保存（复制）流的数据到指定的流。 |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | 保存（复制）所有流的数据到指定的流。 |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | 保存（复制）流的数据到指定的流。 |
| [save(String filePath)](#save-java.lang.String-) | 保存（复制）流的数据到指定的流。 |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | 保存（复制）流的数据到指定的流。 |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | 保存（复制）流的数据到指定的流。 |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | 将包含的数据复制到另一个 `StreamContainer`。 |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | 将包含的数据复制到另一个 `StreamContainer`。 |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


初始化 `StreamContainer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流。 |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


初始化 `StreamContainer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.ms.System.IO.Stream | 流。 |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


初始化 `StreamContainer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 数据流。 |
| disposeStream | boolean | 如果设置为 `true`，则在容器被释放时流也会被释放。 |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


初始化 `StreamContainer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.ms.System.IO.Stream | 数据流。 |
| disposeStream | boolean | 如果设置为 `true`，则在容器被释放时流也会被释放。 |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


指定顺序读取时的读取和写入字节数。

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


执行从 `com.aspose.imaging.StreamContainer` 到 `System.IO.Stream` 的显式转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流容器。 |

**Returns:**
com.aspose.ms.System.IO.Stream - 转换的结果。
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取一个可用于同步访问同步资源的对象。

值：可用于同步对同步资源的访问的对象。

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


获取或设置流中的当前位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。

值：当前流位置。

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


获取或设置流中的当前位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。

值：当前流位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


获取数据流。

值：数据流。

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


获取一个值，指示此流在关闭时是否被释放。

值：如果在关闭时流被释放则为 `true`；否则为 `false`。

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


获取或设置流的字节长度。此值比 Stream\\#getLength().getLength() 的值减去在 StreamContainer 构造函数中传入的起始流位置。

值：流长度。

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


获取或设置流的字节长度。此值比 Stream\\#getLength().getLength() 的值减去在 StreamContainer 构造函数中传入的起始流位置。

值：流长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


获取指示流是否支持读取的值。

值：如果流支持读取则为 `true`；否则为 `false`。

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


获取指示流是否支持定位的值。

值：如果流支持定位则为 `true`；否则为 `false`。

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


获取指示流是否支持写入的值。

值：如果流支持写入则为 `true`；否则为 `false`。

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


清除此流的所有缓冲区，并导致任何缓冲数据写入底层设备。

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


将所有指定的字节写入流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字节 | byte[] | 要写入的字节。 |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


向流的当前位写入一个字节，并将流中的位置前移一个字节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte | 要写入流的字节。 |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


读取字节以填充指定的字节缓冲区。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字节 | byte[] | 要填充的字节。 |

**Returns:**
int - 已读取的字节数。如果流中的字节不足，此值可能小于缓冲区中的字节数。
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


将流数据转换为 `byte` 数组。

**Returns:**
byte[] - 将流数据转换为 `byte` 数组。
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


将流数据转换为 `byte` 数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | long | 开始读取字节的位置。 |
| bytesCount | long | 要读取的字节计数。 |

**Returns:**
byte[] - 将流数据转换为 `byte` 数组。
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


从当前流读取一系列字节，并将流中的位置前移已读取的字节数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | byte[] | 字节数组。当此方法返回时，buffer 包含指定的字节数组，其中 `offset` 与 (`offset` + `count` - 1) 之间的值已被当前来源读取的字节替换。 |
| offset | int | `buffer` 中的零基字节偏移量，指示从何处开始存储从当前流读取的数据。 |
| 计数 | int | 从当前流读取的最大字节数。 |

**Returns:**
int - 读取到缓冲区的总字节数。如果当前不可用的字节少于请求的字节数，则可能小于请求的字节数；如果已到达流的末尾，则为零 (0)。
### readByte() {#readByte--}
```
public int readByte()
```


从流中读取一个字节，并将流中的位置前移一个字节；如果已到流的末尾，则返回 -1。

**Returns:**
int - 将无符号字节转换为 Int32，或在流末尾时为 -1。
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


设置当前流中的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offset | long | 相对于 `origin` 参数的字节偏移量。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移。 |
| origin | int | `System.IO.SeekOrigin` 类型的值，指示用于获取新位置的参考点。 |

**Returns:**
long - 当前流中的新位置。
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


将流位置设置为流的开头。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移。

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


向当前流写入一系列字节，并将此流中的当前位置前移已写入的字节数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | byte[] | 字节数组。此方法将 `count` 字节从 `buffer` 复制到当前流。 |
| offset | int | `buffer` 中的零基字节偏移量，指示从何处开始将字节复制到当前流。 |
| 计数 | int | 要写入当前流的字节数。 |

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


将流的数据保存（复制）到指定的流。使用默认缓冲区大小 `ReadWriteBytesCount` 和流的 `Length` 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | 用于保存数据的流。 |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


将整个流的数据保存（复制）到指定的流。使用流的 `Length` 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | 用于保存数据的流。 |
| bufferSize | int | 缓冲区。 |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


保存（复制）流的数据到指定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | 用于保存数据的流。 |
| bufferSize | int | 缓冲区大小。默认使用 `ReadWriteBytesCount` 值。 |
| length | long | 要复制的流数据长度。默认情况下，长度设置为 `Length` 值。 |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


将流的数据保存（复制）到指定的流。使用默认缓冲区大小 `ReadWriteBytesCount` 和流的 `Length` 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于保存流数据的文件路径。 |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


将流的数据保存（复制）到指定的流。使用流的 `Length` 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于保存流数据的文件路径。 |
| bufferSize | int | 缓冲区大小。默认使用 `ReadWriteBytesCount` 值。 |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


保存（复制）流的数据到指定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 用于保存流数据的文件路径。 |
| bufferSize | int | 缓冲区大小。默认使用 `ReadWriteBytesCount` 值。 |
| length | long | 要复制的流数据长度。默认情况下，长度设置为 `Length` 值。 |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


将包含的数据复制到另一个 `StreamContainer`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 要复制到的流容器。 |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


将包含的数据复制到另一个 `StreamContainer`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 要复制到的流容器。 |
| length | long | 要写入的字节数。 |

