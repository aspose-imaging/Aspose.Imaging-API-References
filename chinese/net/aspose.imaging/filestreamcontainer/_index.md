---
title: "类 FileStreamContainer"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileStreamContainer 类。用于文件流处理的帮助程序"
type: docs
weight: 9480
url: /zh/net/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

用于文件流处理的帮助类。

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread/) { get; } | 获取一个值，指示流是否支持读取。 |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek/) { get; } | 获取一个值，指示流是否支持定位。 |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite/) { get; } | 获取一个值，指示流是否支持写入。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath/) { get; } | 获取文件路径。 |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated/) { get; } | 获取一个值，指示流是否已显式创建。 |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose/) { get; } | 获取一个值，指示此流在关闭时是否被释放。 |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal/) { get; set; } | 获取或设置一个值，指示流是否为临时的。 |
| virtual [Length](../../aspose.imaging/streamcontainer/length/) { get; set; } | 获取或设置流的字节长度。该值比 Length 小，差值为在 StreamContainer 构造函数中传入的起始流位置。 |
| virtual [Position](../../aspose.imaging/streamcontainer/position/) { get; set; } | 获取或设置流中的当前位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream/) { get; } | 获取数据流。 |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot/) { get; } | 获取可用于同步对同步资源访问的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream/)(string, bool) | 创建一个新的文件流。 |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream/)(string) | 打开一个现有的文件流。如果文件流不存在，则抛出相应的异常。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush/)() | 清除此流的所有缓冲区，并导致任何缓冲的数据写入底层设备。 |
| virtual [Read](../../aspose.imaging/streamcontainer/read/)(byte[]) | 读取字节以填充指定的字节缓冲区。 |
| virtual [Read](../../aspose.imaging/streamcontainer/read/)(byte[], int, int) | 从当前流读取一系列字节，并将流中的位置前移读取的字节数。 |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte/)() | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流的末尾则返回 -1。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 和流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 和流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream, int) | 将整个流的数据保存（复制）到指定的流。使用流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int) | 将流的数据保存（复制）到指定的流。使用流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek/)(long, SeekOrigin) | 设置当前流中的位置。 |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin/)() | 将流的位置设置为流的开头。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/)() | 将流数据转换为 Byte 数组。 |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/)(long, long) | 将流数据转换为 Byte 数组。 |
| virtual [Write](../../aspose.imaging/streamcontainer/write/)(byte[]) | 将所有指定的字节写入流。 |
| virtual [Write](../../aspose.imaging/streamcontainer/write/)(byte[], int, int) | 将一系列字节写入当前流，并将此流中的当前位置前移写入的字节数。 |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte/)(byte) | 将一个字节写入流的当前位置，并将流中的位置前移一个字节。 |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer) | 将包含的数据复制到另一个 [`StreamContainer`](../streamcontainer/)。 |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer, long) | 将包含的数据复制到另一个 [`StreamContainer`](../streamcontainer/)。 |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit/#op_explicit_1) | 执行从 `FileStreamContainer` 到 Stream 的显式转换。（2 个运算符） |

### 另请参见

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


