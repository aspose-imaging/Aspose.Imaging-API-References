---
title: FileStreamContainer
second_title: Aspose.Imaging for .NET API 参考
description: 文件流处理助手
type: docs
weight: 9300
url: /zh/net/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

文件流处理助手。

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | 获取流是否支持读取的值。 |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | 获取流是否支持搜索的值。 |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | 获取流是否支持写入的值。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath) { get; } | 获取文件路径。 |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated) { get; } | 获取一个值，该值指示是否明确创建了流。 |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | 获取一个值，该值指示此流是否在关闭时被释放。 |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal) { get; set; } | 获取或设置一个指示流是否是临时的值。 |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | 获取或设置流长度（以字节为单位）。这个值小于Length通过 StreamContainer 构造函数中传递的起始流位置。 |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | 获取或设置流中的当前位置。此值表示从 StreamContainer 构造函数中传递的起始流位置的偏移量。 |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | 获取数据流。 |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | 获取可用于同步访问已同步资源的对象。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream)(string, bool) | 创建一个新的文件流。 |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream)(string) | 打开现有文件流。如果文件流不存在，则引发相应的异常。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | 清除此流的所有缓冲区并导致任何缓冲数据写入底层设备。 |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[]) | 读取字节以填充指定的字节缓冲区。 |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[], int, int) | 从当前流中读取字节序列，并将流中的位置前进读取的字节数。 |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | 从流中读取一个字节并将流中的位置前移一个字节，如果在流的末尾则返回 -1。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount)和流[`Length`](../streamcontainer/length)值. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount)和流[`Length`](../streamcontainer/length)值. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | 将所有流的数据保存（复制）到指定的流。使用流[`Length`](../streamcontainer/length)值. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | 将流的数据保存（复制）到指定的流。使用流[`Length`](../streamcontainer/length)值. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | 设置当前流中的位置。 |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | 将流位置设置为流的开头。此值表示从 StreamContainer 构造函数中传递的起始流位置的偏移量。 |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)() | 将流数据转换为Byte数组. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)(long, long) | 将流数据转换为Byte数组. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[]) | 将所有指定字节写入流。 |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[], int, int) | 将字节序列写入当前流，并将该流中的当前位置前进写入的字节数。 |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | 将一个字节写入流中的当前位置，并将流中的位置前移一个字节。 |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | 将包含的数据复制到另一个[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | 将包含的数据复制到另一个[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit#op_explicit_1) | 执行显式转换[`FileStreamContainer`](../filestreamcontainer)至Stream . (2 operators) |

### 也可以看看

* class [StreamContainer](../streamcontainer)
* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
