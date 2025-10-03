---
title: FileStreamContainer Class
type: docs
weight: 4810
url: /python-net/aspose.imaging/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FileStreamContainer

**Inheritance:** StreamContainer

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Specifies read and write bytes count when reading sequentially. |
| can_read | bool | r | Gets a value indicating whether stream supports reading. |
| can_seek | bool | r | Gets a value indicating whether stream supports seeking. |
| can_write | bool | r | Gets a value indicating whether stream supports writing. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| file_path | string | r | Gets the file path. |
| is_created | bool | r | Gets a value indicating whether stream was created explicitly. |
| is_stream_disposed_on_close | bool | r | Gets a value indicating whether this stream is disposed on close. |
| is_temporal | bool | r/w | Gets or sets a value indicating whether stream is temporal. |
| length | int | r/w | Gets or sets the stream length in bytes. This value is less than the  by the starting stream position passed in the StreamContainer constructor. |
| position | int | r/w | Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| stream | _io.BufferedRandom | r | Gets the data stream. |
| sync_root | System.Object | r | Gets an object that can be used to synchronize access to the synchronized resource. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | Creates a new file stream. |
| flush() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | Opens an existing file stream. If file stream does not exist the appropriate exception is thrown. |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [read(bytes)](#read_bytes_4) | Reads bytes to fill the specified bytes buffer. |
| [read_byte()](#read_byte__5) | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [save(destination_stream)](#save_destination_stream_6) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | Saves (copies) all the stream's data to the specified stream. Uses stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | Saves (copies) the stream's data to the specified stream. |
| [save(file_path)](#save_file_path_9) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | Saves (copies) the stream's data to the specified stream. Uses stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | Saves (copies) the stream's data to the specified stream. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_12) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_13) | Saves (copies) all the stream's data to the specified stream. Uses stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14) | Saves (copies) the stream's data to the specified stream. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_15) | Saves (copies) the stream's data to the specified stream. Uses stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_16) | Saves (copies) the stream's data to the specified stream. |
| [seek(offset, origin)](#seek_offset_origin_17) | Sets the position within the current stream. |
| seek_begin() | Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| [to_bytes()](#to_bytes__18) | Converts the stream data to the int array. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_19) | Converts the stream data to the int array. |
| [write(buffer, offset, count)](#write_buffer_offset_count_20) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [write(bytes)](#write_bytes_21) | Writes all of the specified bytes to the stream. |
| [write_byte(value)](#write_byte_value_22) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [write_to(stream_container)](#write_to_stream_container_23) | Copies the contained data to another [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_24) | Copies the contained data to another [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/). |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


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
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | The file stream container. |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


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
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | The file stream container. |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


```
 read(buffer, offset, count) 
```

Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| buffer | System.Byte | An array of bytes. When this method returns, the buffer contains the specified byte array with the values between _offset_ and (_offset_ + _count_ - 1) replaced by the bytes read from the current source. |
| offset | int | The zero-based byte offset in _buffer_ at which to begin storing the data read from the current stream. |
| count | int | The maximum number of bytes to be read from the current stream. |

**Returns**

| Type | Description |
| :- | :- |
| int | The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached. |


### Method: read(bytes) {#read_bytes_4}


```
 read(bytes) 
```

Reads bytes to fill the specified bytes buffer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | System.Byte | The bytes to fill. |

**Returns**

| Type | Description |
| :- | :- |
| int | The number of bytes read. This value can be less than the number of bytes in the buffer if there is not enough bytes in the stream. |


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream.

**Returns**

| Type | Description |
| :- | :- |
| int | The unsigned byte cast to an Int32, or -1 if at the end of the stream. |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

Saves (copies) all the stream's data to the specified stream. Uses stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |
| length | int | The stream data length to copy. By default the length is set to [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

Saves (copies) the stream's data to the specified stream. Uses stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


```
 save(file_path, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |
| length | int | The stream data length to copy. By default the length is set to [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_12}


```
 save_to_stream(destination_stream) 
```

Saves (copies) the stream's data to the specified stream. Uses default buffer size [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_13}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

Saves (copies) all the stream's data to the specified stream. Uses stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | The stream to save the data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |
| length | int | The stream data length to copy. By default the length is set to [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_15}


```
 save_with_buf_size(file_path, buffer_size) 
```

Saves (copies) the stream's data to the specified stream. Uses stream [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_16}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

Saves (copies) the stream's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) value is used. |
| length | int | The stream data length to copy. By default the length is set to [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/) value. |

### Method: seek(offset, origin) {#seek_offset_origin_17}


```
 seek(offset, origin) 
```

Sets the position within the current stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| offset | int | A byte offset relative to the _origin_ parameter. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | A value of type SeekOrigin indicating the reference point used to obtain the new position. |

**Returns**

| Type | Description |
| :- | :- |
| int | The new position within the current stream. |


### Method: to_bytes() {#to_bytes__18}


```
 to_bytes() 
```

Converts the stream data to the int array.

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | The stream data converted to the int array. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_19}


```
 to_bytes(position, bytes_count) 
```

Converts the stream data to the int array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| position | int | The position to start reading bytes from. |
| bytes_count | int | The bytes count to read. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | The stream data converted to the int array. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_20}


```
 write(buffer, offset, count) 
```

Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| buffer | System.Byte | An array of bytes. This method copies _count_ bytes from _buffer_ to the current stream. |
| offset | int | The zero-based byte offset in _buffer_ at which to begin copying bytes to the current stream. |
| count | int | The number of bytes to be written to the current stream. |

### Method: write(bytes) {#write_bytes_21}


```
 write(bytes) 
```

Writes all of the specified bytes to the stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | System.Byte | The bytes to write. |

### Method: write_byte(value) {#write_byte_value_22}


```
 write_byte(value) 
```

Writes a byte to the current position in the stream and advances the position within the stream by one byte.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | System.Byte | The byte to write to the stream. |

### Method: write_to(stream_container) {#write_to_stream_container_23}


```
 write_to(stream_container) 
```

Copies the contained data to another [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | The stream container to copy to. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_24}


```
 write_to(stream_container, length) 
```

Copies the contained data to another [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | The stream container to copy to. |
| length | int | The bytes count to write. |

