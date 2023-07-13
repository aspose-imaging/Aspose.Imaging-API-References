---
title: FileStreamContainer Class
type: docs
weight: 4740
url: /python-net/aspose.imaging/filestreamcontainer/
---

Helper for file stream processing.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FileStreamContainer

**Inheritance:** StreamContainer

**Aspose.Imaging Version:** 23.6

The FileStreamContainer type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| sync_root | object | r | Gets an object that can be used to synchronize access to the synchronized resource. |
| position | long | r/w | Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| stream | _io.BufferedRandom | r | Gets the data stream. |
| is_stream_disposed_on_close | bool | r | Gets a value indicating whether this stream is disposed on close. |
| length | long | r/w | Gets or sets the stream length in bytes. This value is less than the  by the starting stream position passed in the StreamContainer constructor. |
| can_read | bool | r | Gets a value indicating whether stream supports reading. |
| can_seek | bool | r | Gets a value indicating whether stream supports seeking. |
| can_write | bool | r | Gets a value indicating whether stream supports writing. |
| READ_WRITE_BYTES_COUNT [static] | int | r | Specifies read and write bytes count when reading sequentially. |
| is_temporal | bool | r/w | Gets or sets a value indicating whether stream is temporal. |
| is_created | bool | r | Gets a value indicating whether stream was created explicitly. |
| file_path | string | r | Gets the file path. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [write(bytes)](#write_bytes_0) | Writes all of the specified bytes to the stream. |
| [write(buffer, offset, count)](#write_buffer_offset_count_1) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [read(bytes)](#read_bytes_2) | Reads bytes to fill the specified bytes buffer. |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [to_bytes()](#to_bytes__4) | Converts the stream data to the int array. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_5) | Converts the stream data to the int array. |
| [save(destination_stream)](#save_destination_stream_6) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | Saves (copies) all the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | Saves (copies) the stream's data to the specified stream. |
| [save(file_path)](#save_file_path_9) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | Saves (copies) the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | Saves (copies) the stream's data to the specified stream. |
| [write_to(stream_container)](#write_to_stream_container_12) | Copies the contained data to another [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_13) | Copies the contained data to another [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| flush() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| [write_byte(value)](#write_byte_value_14) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [read_byte()](#read_byte__15) | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [seek(offset, origin)](#seek_offset_origin_16) | Sets the position within the current stream. |
| seek_begin() | Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_17) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_18) | Saves (copies) all the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_19) | Saves (copies) the stream's data to the specified stream. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_20) | Saves (copies) the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_21) | Saves (copies) the stream's data to the specified stream. |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_22) | Creates a new file stream. |
| [open_file_stream(file_location)](#open_file_stream_file_location_23) | Opens an existing file stream. If file stream does not exist the appropriate exception is thrown. |

### write(bytes) {#write_bytes_0}


```
 write(bytes) 
```

Writes all of the specified bytes to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | byte | The bytes to write. |

### write(buffer, offset, count) {#write_buffer_offset_count_1}


```
 write(buffer, offset, count) 
```

Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| buffer | byte | An array of bytes. This method copies <paramref name="count" /> bytes from <paramref name="buffer" /> to the current stream. |
| offset | int | The zero-based byte offset in <paramref name="buffer" /> at which to begin copying bytes to the current stream. |
| count | int | The number of bytes to be written to the current stream. |

### read(bytes) {#read_bytes_2}


```
 read(bytes) 
```

Reads bytes to fill the specified bytes buffer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | byte | The bytes to fill. |

**Returns**

| Type | Description |
| :- | :- |
| int | The number of bytes read. This value can be less than the number of bytes in the buffer if there is not enough bytes in the stream. |


### read(buffer, offset, count) {#read_buffer_offset_count_3}


```
 read(buffer, offset, count) 
```

Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| buffer | byte | An array of bytes. When this method returns, the buffer contains the specified byte array with the values between <paramref name="offset" /> and (<paramref name="offset" /> + <paramref name="count" /> - 1) replaced by the bytes read from the current source. |
| offset | int | The zero-based byte offset in <paramref name="buffer" /> at which to begin storing the data read from the current stream. |
| count | int | The maximum number of bytes to be read from the current stream. |

**Returns**

| Type | Description |
| :- | :- |
| int | The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached. |


### to_bytes() {#to_bytes__4}


```
 to_bytes() 
```

Converts the stream data to the int array.

**Returns**

| Type | Description |
| :- | :- |
| byte | The stream data converted to the int array. |


### to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_5}


```
 to_bytes(position, bytes_count) 
```

Converts the stream data to the int array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | long | The position to start reading bytes from. |
| bytes_count | long | The bytes count to read. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The stream data converted to the int array. |


### save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

Saves (copies) the stream's data to the specified stream. Uses default buffer size [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |

### save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

Saves (copies) all the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer. |

### save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer size. By default [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |
| length | long | The stream data length to copy. By default the length is set to [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |

### save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

Saves (copies) the stream's data to the specified stream. Uses default buffer size [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |

### save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

Saves (copies) the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |

### save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


```
 save(file_path, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |
| length | long | The stream data length to copy. By default the length is set to [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |

### write_to(stream_container) {#write_to_stream_container_12}


```
 write_to(stream_container) 
```

Copies the contained data to another [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | The stream container to copy to. |

### write_to(stream_container, length) {#write_to_stream_container_length_13}


```
 write_to(stream_container, length) 
```

Copies the contained data to another [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | The stream container to copy to. |
| length | long | The bytes count to write. |

### write_byte(value) {#write_byte_value_14}


```
 write_byte(value) 
```

Writes a byte to the current position in the stream and advances the position within the stream by one byte.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | byte | The byte to write to the stream. |

### read_byte() {#read_byte__15}


```
 read_byte() 
```

Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream.

**Returns**

| Type | Description |
| :- | :- |
| int | The unsigned byte cast to an Int32, or -1 if at the end of the stream. |


### seek(offset, origin) {#seek_offset_origin_16}


```
 seek(offset, origin) 
```

Sets the position within the current stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| offset | long | A byte offset relative to the <paramref name="origin" /> parameter. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin) | A value of type SeekOrigin indicating the reference point used to obtain the new position. |

**Returns**

| Type | Description |
| :- | :- |
| long | The new position within the current stream. |


### save_to_stream(destination_stream) {#save_to_stream_destination_stream_17}


```
 save_to_stream(destination_stream) 
```

Saves (copies) the stream's data to the specified stream. Uses default buffer size [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |

### save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_18}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Saves (copies) all the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer. |

### save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_19}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer size. By default [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |
| length | long | The stream data length to copy. By default the length is set to [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |

### save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_20}


```
 save_with_buf_size(file_path, buffer_size) 
```

Saves (copies) the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |

### save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_21}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |
| length | long | The stream data length to copy. By default the length is set to [length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |

### create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_22}


```
 create_file_stream(file_location, is_temporal) 
```

Creates a new file stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_location | string | The file location. |
| is_temporal | bool | If set to <c>true</c> the file stream container is temporal. |

**Returns**

| Type | Description |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer) | The file stream container. |


### open_file_stream(file_location)  [static] {#open_file_stream_file_location_23}


```
 open_file_stream(file_location) 
```

Opens an existing file stream. If file stream does not exist the appropriate exception is thrown.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_location | string | The file location. |

**Returns**

| Type | Description |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer) | The file stream container. |


