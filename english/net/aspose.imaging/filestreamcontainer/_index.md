---
title: Class FileStreamContainer
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileStreamContainer class. Helper for file stream processing
type: docs
weight: 9480
url: /net/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

Helper for file stream processing.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Properties

| Name | Description |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread/) { get; } | Gets a value indicating whether stream supports reading. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek/) { get; } | Gets a value indicating whether stream supports seeking. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite/) { get; } | Gets a value indicating whether stream supports writing. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath/) { get; } | Gets the file path. |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated/) { get; } | Gets a value indicating whether stream was created explicitly. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose/) { get; } | Gets a value indicating whether this stream is disposed on close. |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal/) { get; set; } | Gets or sets a value indicating whether stream is temporal. |
| virtual [Length](../../aspose.imaging/streamcontainer/length/) { get; set; } | Gets or sets the stream length in bytes. This value is less than the Length by the starting stream position passed in the StreamContainer constructor. |
| virtual [Position](../../aspose.imaging/streamcontainer/position/) { get; set; } | Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream/) { get; } | Gets the data stream. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot/) { get; } | Gets an object that can be used to synchronize access to the synchronized resource. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream/)(string, bool) | Creates a new file stream. |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream/)(string) | Opens an existing file stream. If file stream does not exist the appropriate exception is thrown. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush/)() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| virtual [Read](../../aspose.imaging/streamcontainer/read/)(byte[]) | Reads bytes to fill the specified bytes buffer. |
| virtual [Read](../../aspose.imaging/streamcontainer/read/)(byte[], int, int) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte/)() | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) and stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) and stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream, int) | Saves (copies) all the stream's data to the specified stream. Uses stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int) | Saves (copies) the stream's data to the specified stream. Uses stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek/)(long, SeekOrigin) | Sets the position within the current stream. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin/)() | Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/)() | Converts the stream data to the Byte array. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/)(long, long) | Converts the stream data to the Byte array. |
| virtual [Write](../../aspose.imaging/streamcontainer/write/)(byte[]) | Writes all of the specified bytes to the stream. |
| virtual [Write](../../aspose.imaging/streamcontainer/write/)(byte[], int, int) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte/)(byte) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer) | Copies the contained data to another [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer, long) | Copies the contained data to another [`StreamContainer`](../streamcontainer/). |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit/#op_explicit_1) | Performs an explicit conversion from `FileStreamContainer` to Stream. (2 operators) |

### See Also

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


