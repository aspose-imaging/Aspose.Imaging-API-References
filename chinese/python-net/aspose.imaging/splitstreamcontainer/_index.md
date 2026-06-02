---
title: "SplitStreamContainer 类"
type: docs
weight: 7330
url: /zh/python-net/aspose.imaging/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SplitStreamContainer

**Inheritance:** StreamContainer

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | 初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。 |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | 初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。 |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | 初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | 指定顺序读取时的读写字节计数。 |
| can_read | bool | r | 获取一个值，指示流是否支持读取。 |
| can_seek | bool | r | 获取一个值，指示流是否支持定位。 |
| can_write | bool | r | 获取一个值，指示流是否支持写入。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| is_stream_disposed_on_close | bool | r | 获取一个值，指示此流在关闭时是否被释放。 |
| length | int | r/w | 获取或设置流的字节长度。此值小于在 StreamContainer 构造函数中传入的起始流位置所产生的值。 |
| position | int | r/w | 获取或设置流中的当前位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| 流 | _io.BufferedRandom | r | 获取数据流。 |
| sync_root | System.Object | r | 获取一个可用于同步对同步资源访问的对象。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_stream(stream, dispose_stream)](#create_from_stream_stream_dispose_stream_1) | 初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。 |
| [create_from_stream_container(stream, dispose_stream)](#create_from_stream_container_stream_dispose_stream_2) | 初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。 |
| flush() | 清除此流的所有缓冲区，并导致任何缓冲的数据写入底层设备。 |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_3) | 将流容器插入指定位置。 |
| [read(buffer, offset, count)](#read_buffer_offset_count_4) | 从当前流读取一系列字节，并将流中的位置前移读取的字节数。 |
| [read(bytes)](#read_bytes_5) | 读取字节以填充指定的字节缓冲区。 |
| [read_byte()](#read_byte__6) | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流的末尾，则返回 -1。 |
| [save(destination_stream)](#save_destination_stream_7) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 和流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。 |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_8) | 将所有流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。 |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_9) | 将流的数据保存（复制）到指定的流。 |
| [save(file_path)](#save_file_path_10) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 和流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。 |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_11) | 将流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。 |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_12) | 将流的数据保存（复制）到指定的流。 |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_13) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 和流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。 |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_14) | 将所有流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。 |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_15) | 将流的数据保存（复制）到指定的流。 |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_16) | 将流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。 |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_17) | 将流的数据保存（复制）到指定的流。 |
| [seek(offset, origin)](#seek_offset_origin_18) | 设置当前流中的位置。 |
| seek_begin() | 将流位置设置为流的起始位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| [to_bytes()](#to_bytes__19) | 将流数据转换为 int 数组。 |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_20) | 将流数据转换为 int 数组。 |
| [write(buffer, offset, count)](#write_buffer_offset_count_21) | 将一系列字节写入当前流，并将此流中的当前位置向前移动已写入的字节数。 |
| [write(bytes)](#write_bytes_22) | 将所有指定的字节写入流。 |
| [write_byte(value)](#write_byte_value_23) | 在流的当前位写入一个字节，并将流中的位置前移一个字节。 |
| [write_to(stream_container)](#write_to_stream_container_24) | 将包含的数据复制到另一个 [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/)。 |
| [write_to(stream_container, length)](#write_to_stream_container_length_25) | 将包含的数据复制到另一个 [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/)。 |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 数据流。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，当容器被释放时流也将被释放。 |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 数据流。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，当容器被释放时流也将被释放。 |

### Method: create_from_stream(stream, dispose_stream)  [static] {#create_from_stream_stream_dispose_stream_1}


```
 create_from_stream(stream, dispose_stream) 
```

初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 数据流。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，当容器被释放时流也将被释放。 |

**Returns**

| Type | Description |
| :- | :- |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) |  |


### Method: create_from_stream_container(stream, dispose_stream)  [static] {#create_from_stream_container_stream_dispose_stream_2}


```
 create_from_stream_container(stream, dispose_stream) 
```

初始化一个新的 [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 流容器。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，则释放流。 |

**Returns**

| Type | Description |
| :- | :- |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) |  |


### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_3}


```
 insert(position, stream, dispose_stream) 
```

将流容器插入指定位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 要插入的位置。 |
| stream | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 要插入的流容器。 |
| dispose_stream | bool | 如果设置为 <c>true</c>，则释放流。 |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_4}


```
 read(buffer, offset, count) 
```

从当前流读取一系列字节，并将流中的位置前移读取的字节数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 缓冲区 | System.Byte | 字节数组。当此方法返回时，缓冲区包含指定的字节数组，其中 _offset_ 与 (_offset_ + _count_ - 1) 之间的值已被从当前源读取的字节替换。 |
| offset | int | 在 _buffer_ 中开始存储从当前流读取的数据的基于零的字节偏移量。 |
| count | int | 从当前流读取的最大字节数。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 读取到缓冲区的字节总数。如果当前可用字节不足请求的字节数，则可能少于请求的字节数；如果已到达流的末尾，则为零 (0)。 |


### Method: read(bytes) {#read_bytes_5}


```
 read(bytes) 
```

读取字节以填充指定的字节缓冲区。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 字节 | System.Byte | 要填充的字节。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 读取的字节数。如果流中的字节不足，则此值可能小于缓冲区中的字节数。 |


### Method: read_byte() {#read_byte__6}


```
 read_byte() 
```

从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流的末尾，则返回 -1。

**Returns**

| Type | Description |
| :- | :- |
| int | 在流的末尾时，将无符号字节转换为 Int32，或返回 -1。 |


### Method: save(destination_stream) {#save_destination_stream_7}


```
 save(destination_stream) 
```

将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 和流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 用于保存数据的流。 |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_8}


```
 save(destination_stream, buffer_size) 
```

将所有流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 用于保存数据的流。 |
| buffer_size | int | 缓冲区。 |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_9}


```
 save(destination_stream, buffer_size, length) 
```

将流的数据保存（复制）到指定的流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 用于保存数据的流。 |
| buffer_size | int | 缓冲区大小。 |
| length | int | 要复制的流数据长度。默认情况下，长度设置为 [SplitStreamContainer.length](/imaging/python-net/aspose.imaging/splitstreamcontainer/) 的值。 |

### Method: save(file_path) {#save_file_path_10}


```
 save(file_path) 
```

将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 和流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 用于保存流数据的文件路径。 |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_11}


```
 save(file_path, buffer_size) 
```

将流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 用于保存流数据的文件路径。 |
| buffer_size | int | 缓冲区大小。默认使用 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 的值。 |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_12}


```
 save(file_path, buffer_size, length) 
```

将流的数据保存（复制）到指定的流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 用于保存流数据的文件路径。 |
| buffer_size | int | 缓冲区大小。默认使用 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 的值。 |
| length | int | 要复制的流数据长度。默认情况下，长度设置为 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 的值。 |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_13}


```
 save_to_stream(destination_stream) 
```

将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 和流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 用于保存数据的流。 |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_14}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

将所有流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 用于保存数据的流。 |
| buffer_size | int | 缓冲区。 |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_15}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

将流的数据保存（复制）到指定的流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | 用于保存数据的流。 |
| buffer_size | int | 缓冲区大小。默认使用 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 的值。 |
| length | int | 要复制的流数据长度。默认情况下，长度设置为 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 的值。 |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_16}


```
 save_with_buf_size(file_path, buffer_size) 
```

将流的数据保存（复制）到指定的流。使用流的 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 用于保存流数据的文件路径。 |
| buffer_size | int | 缓冲区大小。默认使用 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 的值。 |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_17}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

将流的数据保存（复制）到指定的流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 用于保存流数据的文件路径。 |
| buffer_size | int | 缓冲区大小。默认使用 [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) 的值。 |
| length | int | 要复制的流数据长度。默认情况下，长度设置为 [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) 的值。 |

### Method: seek(offset, origin) {#seek_offset_origin_18}


```
 seek(offset, origin) 
```

设置当前流中的位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| offset | int | 相对于 _origin_ 参数的字节偏移量。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | SeekOrigin 类型的值，指示用于获取新位置的参考点。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 当前流中的新位置。 |


### Method: to_bytes() {#to_bytes__19}


```
 to_bytes() 
```

将流数据转换为 int 数组。

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 转换为 int 数组的流数据。 |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_20}


```
 to_bytes(position, bytes_count) 
```

将流数据转换为 int 数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| position | int | 开始读取字节的位置。 |
| bytes_count | int | 要读取的字节数。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 转换为 int 数组的流数据。 |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_21}


```
 write(buffer, offset, count) 
```

将一系列字节写入当前流，并将此流中的当前位置向前移动已写入的字节数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 缓冲区 | System.Byte | 字节数组。此方法将 _count_ 字节从 _buffer_ 复制到当前流。 |
| offset | int | 在 _buffer_ 中的零基字节偏移量，指示开始将字节复制到当前流的位置。 |
| count | int | 写入当前流的字节数。 |

### Method: write(bytes) {#write_bytes_22}


```
 write(bytes) 
```

将所有指定的字节写入流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 字节 | System.Byte | 要写入的字节。 |

### Method: write_byte(value) {#write_byte_value_23}


```
 write_byte(value) 
```

在流的当前位写入一个字节，并将流中的位置前移一个字节。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | System.Byte | 要写入流的字节。 |

### Method: write_to(stream_container) {#write_to_stream_container_24}


```
 write_to(stream_container) 
```

将包含的数据复制到另一个 [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 要复制到的流容器。 |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_25}


```
 write_to(stream_container, length) 
```

将包含的数据复制到另一个 [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 要复制到的流容器。 |
| length | int | 要写入的字节数。 |

