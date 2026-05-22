---
title: "类 SplitStreamContainer"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.SplitStreamContainer 类。表示包含流并提供流处理例程的分割流容器"
type: docs
weight: 11710
url: /zh/net/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

表示分割流容器，包含流并提供流处理例程。

```csharp
public class SplitStreamContainer : StreamContainer
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | 初始化 `SplitStreamContainer` 类的新实例。 |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | 初始化 `SplitStreamContainer` 类的新实例。 |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | 初始化 `SplitStreamContainer` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread/) { get; } | 获取一个值，指示流是否支持读取。 |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek/) { get; } | 获取一个值，指示流是否支持定位。 |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite/) { get; } | 获取一个值，指示流是否支持写入。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose/) { get; } | 获取一个值，指示此流在关闭时是否被释放。 |
| override [Length](../../aspose.imaging/splitstreamcontainer/length/) { get; set; } | 获取或设置流的字节长度。该值比 Length 小，差值为在 StreamContainer 构造函数中传入的起始流位置。 |
| override [Position](../../aspose.imaging/splitstreamcontainer/position/) { get; set; } | 获取或设置流中的当前位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream/) { get; } | 获取数据流。 |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot/) { get; } | 获取可用于同步对同步资源访问的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush/)() | 清除此流的所有缓冲区，并导致任何缓冲的数据写入底层设备。 |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert/)(int, StreamContainer, bool) | 将流容器插入指定位置。 |
| override [Read](../../aspose.imaging/splitstreamcontainer/read/#read)(byte[]) | 读取字节以填充指定的字节缓冲区。 |
| override [Read](../../aspose.imaging/splitstreamcontainer/read/#read_1)(byte[], int, int) | 从当前流读取一系列字节，并将流中的位置前移读取的字节数。 |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte/)() | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流的末尾则返回 -1。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 和流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 和流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(Stream, int) | 将整个流的数据保存（复制）到指定的流。使用流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int) | 将流的数据保存（复制）到指定的流。使用流的 [`Length`](../streamcontainer/length/) 值。 |
| override [Save](../../aspose.imaging/splitstreamcontainer/save/#save_2)(Stream, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/)(string, int, long) | 将流的数据保存（复制）到指定的流。 |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek/)(long, SeekOrigin) | 设置当前流中的位置。 |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin/)() | 将流的位置设置为流的开头。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes/#tobytes)() | 将流数据转换为 Byte 数组。 |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | 将流数据转换为 Byte 数组。 |
| override [Write](../../aspose.imaging/splitstreamcontainer/write/#write)(byte[]) | 将所有指定的字节写入流。 |
| override [Write](../../aspose.imaging/splitstreamcontainer/write/#write_1)(byte[], int, int) | 将一系列字节写入当前流，并将此流中的当前位置前移写入的字节数。 |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte/)(byte) | 将一个字节写入流的当前位置，并将流中的位置前移一个字节。 |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer) | 将包含的数据复制到另一个 [`StreamContainer`](../streamcontainer/)。 |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/)(StreamContainer, long) | 将包含的数据复制到另一个 [`StreamContainer`](../streamcontainer/)。 |

### 另请参见

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


