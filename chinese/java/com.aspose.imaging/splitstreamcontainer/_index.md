---
title: "SplitStreamContainer"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示分割流容器，该容器包含流并提供流处理例程。"
type: docs
weight: 108
url: /zh/java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

表示分割流容器，该容器包含流并提供流处理例程。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | 初始化 `SplitStreamContainer` 类的新实例。 |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | 初始化 `SplitStreamContainer` 类的新实例。 |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | 初始化 `SplitStreamContainer` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | 获取一个可用于同步访问同步资源的对象。 |
| [getPosition()](#getPosition--) | 获取流中的当前位置信息。 |
| [setPosition(long value)](#setPosition-long-) | 设置流中的当前位置。 |
| [getLength()](#getLength--) | 获取流的字节长度。 |
| [setLength(long value)](#setLength-long-) | 设置流的字节长度。 |
| [canRead()](#canRead--) | 获取指示流是否支持读取的值。 |
| [canSeek()](#canSeek--) | 获取指示流是否支持定位的值。 |
| [canWrite()](#canWrite--) | 获取指示流是否支持写入的值。 |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | 将流容器插入指定位置。 |
| [flush()](#flush--) | 清除此流的所有缓冲区，并导致任何缓冲数据写入底层设备。 |
| [write(byte[] bytes)](#write-byte---) | 将所有指定的字节写入流中。 |
| [writeByte(byte value)](#writeByte-byte-) | 向流的当前位写入一个字节，并将流中的位置前移一个字节。 |
| [read(byte[] bytes)](#read-byte---) | 读取字节以填充指定的字节缓冲区。 |
| [toBytes()](#toBytes--) | 将流数据转换为 `byte` 数组。 |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | 将流数据转换为 `byte` 数组。 |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | 从当前流读取一系列字节，并将流中的位置前移已读取的字节数。 |
| [readByte()](#readByte--) | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到流的末尾，则返回 -1。 |
| [seek(long offset, int origin)](#seek-long-int-) | 设置当前流中的位置。 |
| [seekBegin()](#seekBegin--) | 将流位置设置为流的开头。 |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | 向当前流写入一系列字节，并将此流中的当前位置前移已写入的字节数。 |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


初始化 `SplitStreamContainer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流。 |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


初始化 `SplitStreamContainer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 数据流。 |
| disposeStream | boolean | 如果设置为 `true`，则在容器被释放时流也会被释放。 |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


初始化 `SplitStreamContainer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流容器。 |
| disposeStream | boolean | 如果设置为 `true`，则释放流。 |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取一个可用于同步访问同步资源的对象。

**Returns:**
java.lang.Object - 可用于同步对同步资源访问的对象。
### getPosition() {#getPosition--}
```
public long getPosition()
```


获取流中的当前位置。该值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。

**Returns:**
long - 当前流位置。
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


设置流中的当前位置。该值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 当前流位置。 |

### getLength() {#getLength--}
```
public long getLength()
```


获取流的字节长度。该值比 `System.IO.Stream.Length` 少了在 StreamContainer 构造函数中传入的起始流位置。

**Returns:**
long - 流长度。
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


设置流的字节长度。该值比 `System.IO.Stream.Length` 少了在 StreamContainer 构造函数中传入的起始流位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 流长度。 |

### canRead() {#canRead--}
```
public boolean canRead()
```


获取指示流是否支持读取的值。

**Returns:**
boolean - 如果流支持读取则为 `true`；否则为 `false`。
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


获取指示流是否支持定位的值。

**Returns:**
boolean - 如果流支持定位则为 `true`；否则为 `false`。
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


获取指示流是否支持写入的值。

**Returns:**
boolean - 如果流支持写入则为 `true`；否则为 `false`。
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


将流容器插入指定位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | int | 要插入的位置。 |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 要插入的流容器。 |
| disposeStream | boolean | 如果设置为 `true`，则释放流。 |

### flush() {#flush--}
```
public void flush()
```


清除此流的所有缓冲区，并导致任何缓冲数据写入底层设备。

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


将所有指定的字节写入流中。

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

