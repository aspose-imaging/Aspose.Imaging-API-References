---
title: FileStreamContainer Class
type: docs
weight: 190
url: /python-net/aspose.imaging/filestreamcontainer/
---

Helper for file stream processing.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.FileStreamContainer

**Assembly:**  Aspose.Imaging Version: 23.5.6

The FileStreamContainer type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|sync_root|Gets an object that can be used to synchronize access to the synchronized resource.|
|position|Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.|
|stream|Gets the data stream.|
|is_stream_disposed_on_close|Gets a value indicating whether this stream is disposed on close.|
|length|Gets or sets the stream length in bytes. This value is less than the  by the starting stream position passed in the StreamContainer constructor.|
|can_read|Gets a value indicating whether stream supports reading.|
|can_seek|Gets a value indicating whether stream supports seeking.|
|can_write|Gets a value indicating whether stream supports writing.|
|READ_WRITE_BYTES_COUNT|Specifies read and write bytes count when reading sequentially.|
|is_temporal|Gets or sets a value indicating whether stream is temporal.|
|is_created|Gets a value indicating whether stream was created explicitly.|
|file_path|Gets the file path.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|write(bytes)|Writes all of the specified bytes to the stream.|
|write(buffer, offset, count)|Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.|
|read(bytes)|Reads bytes to fill the specified bytes buffer.|
|read(buffer, offset, count)|Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.|
|to_bytes()|Converts the stream data to the int array.|
|to_bytes(position, bytes_count)|  |
|save(destination_stream)|Saves (copies) the stream's data to the specified stream. Uses default buffer size [None](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.|
|save(destination_stream, buffer_size)|Saves (copies) all the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.|
|save(destination_stream, buffer_size, length)|  |
|save(file_path)|Saves (copies) the stream's data to the specified stream. Uses default buffer size [None](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.|
|save(file_path, buffer_size)|Saves (copies) the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.|
|save(file_path, buffer_size, length)|  |
|write_to(stream_container)|Copies the contained data to another [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/).|
|write_to(stream_container, length)|  |
|flush()|Clears all buffers for this stream and causes any buffered data to be written to the underlying device.|
|write_byte(value)|Writes a byte to the current position in the stream and advances the position within the stream by one byte.|
|read_byte()|Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream.|
|seek(offset, origin)|  |
|seek_begin()|Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.|
|save_to_stream(destination_stream)|Saves (copies) the stream's data to the specified stream. Uses default buffer size [None](/imaging/python-net/aspose.imaging/streamcontainer/) and stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.|
|save_to_stream_with_buf_size(destination_stream, buffer_size)|Saves (copies) all the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.|
|save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)|Saves (copies) the stream's data to the specified stream.|
|save_with_buf_size(file_path, buffer_size)|Saves (copies) the stream's data to the specified stream. Uses stream [length](/imaging/python-net/aspose.imaging/streamcontainer/) value.|
|save_with_buf_size_and_len(file_path, buffer_size, length)|Saves (copies) the stream's data to the specified stream.|
|create_file_stream(file_location, is_temporal)|Creates a new file stream.|
|open_file_stream(file_location)|Opens an existing file stream. If file stream does not exist the appropriate exception is thrown.|
