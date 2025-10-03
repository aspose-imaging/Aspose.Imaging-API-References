---
title: Class SplitStreamContainer
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.SplitStreamContainer class. Represents split stream container which contains the stream and provides stream processing routines
type: docs
weight: 11620
url: /net/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

Represents split stream container which contains the stream and provides stream processing routines.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Constructors

| Name | Description |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Initializes a new instance of the `SplitStreamContainer` class. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Initializes a new instance of the `SplitStreamContainer` class. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Initializes a new instance of the `SplitStreamContainer` class. |

## Properties

| Name | Description |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread/) { get; } | Gets a value indicating whether stream supports reading. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek/) { get; } | Gets a value indicating whether stream supports seeking. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite/) { get; } | Gets a value indicating whether stream supports writing. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose/) { get; } | Gets a value indicating whether this stream is disposed on close. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length/) { get; set; } | Gets or sets the stream length in bytes. This value is less than the Length by the starting stream position passed in the StreamContainer constructor. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position/) { get; set; } | Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream/) { get; } | Gets the data stream. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot/) { get; } | Gets an object that can be used to synchronize access to the synchronized resource. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush/)() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Inserts the stream container into specified position. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read/#read)(byte[]) | Reads bytes to fill the specified bytes buffer. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read/#read_1)(byte[], int, int) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte/)() | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) and stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) and stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream, int) | Saves (copies) all the stream's data to the specified stream. Uses stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int) | Saves (copies) the stream's data to the specified stream. Uses stream [`Length`](../streamcontainer/length/) value. |
| override [Save](../../aspose.imaging/splitstreamcontainer/save/#save_2)(Stream, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int, long) | Saves (copies) the stream's data to the specified stream. |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek/)(long, SeekOrigin) | Sets the position within the current stream. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin/)() | Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes/#tobytes)() | Converts the stream data to the Byte array. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Converts the stream data to the Byte array. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write/#write)(byte[]) | Writes all of the specified bytes to the stream. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write/#write_1)(byte[], int, int) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte/)(byte) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer) | Copies the contained data to another [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer, long) | Copies the contained data to another [`StreamContainer`](../streamcontainer/). |

### See Also

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


