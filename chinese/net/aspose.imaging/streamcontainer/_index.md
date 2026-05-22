---
title: "类 StreamContainer"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.StreamContainer 类。表示包含流并提供流处理例程的流容器。"
type: docs
weight: 11720
url: /zh/net/aspose.imaging/streamcontainer/
---
## StreamContainer class

表示流容器，包含流并提供流处理例程。

```csharp
public class StreamContainer : DisposableObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | 初始化 `StreamContainer` 类的新实例。 |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | 初始化 `StreamContainer` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread/) { get; } | 获取一个值，指示流是否支持读取。 |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek/) { get; } | 获取一个值，指示流是否支持定位。 |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite/) { get; } | 获取一个值，指示流是否支持写入。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose/) { get; } | 获取一个值，指示此流在关闭时是否被释放。 |
| virtual [Length](../../aspose.imaging/streamcontainer/length/) { get; set; } | 获取或设置流的字节长度。该值比 Length 小，差值为在 StreamContainer 构造函数中传入的起始流位置。 |
| virtual [Position](../../aspose.imaging/streamcontainer/position/) { get; set; } | 获取或设置流中的当前位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream/) { get; } | 获取数据流。 |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot/) { get; } | 获取可用于同步对同步资源访问的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush/)() | 清除此流的所有缓冲区，并导致任何缓冲的数据写入底层设备。 |
| virtual [Read](../../aspose.imaging/streamcontainer/read/#read)(byte[]) | 读取字节以填充指定的字节缓冲区。 |
| virtual [Read](../../aspose.imaging/streamcontainer/read/#read_1)(byte[], int, int) | 从当前流读取一系列字节，并将流中的位置前移读取的字节数。 |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte/)() | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流的末尾则返回 -1。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save)(Stream) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](./readwritebytescount/) 和流 [`Length`](./length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_3)(string) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](./readwritebytescount/) 和流 [`Length`](./length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_1)(Stream, int) | 将所有流的数据保存（复制）到指定的流。使用流 [`Length`](./length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_4)(string, int) | 将流的数据保存（复制）到指定的流。使用流 [`Length`](./length/) 值。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_2)(Stream, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Save](../../aspose.imaging/streamcontainer/save/#save_5)(string, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek/)(long, SeekOrigin) | 设置当前流中的位置。 |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin/)() | 将流的位置设置为流的开头。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/#tobytes)() | 将流数据转换为 Byte 数组。 |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes/#tobytes_1)(long, long) | 将流数据转换为 Byte 数组。 |
| virtual [Write](../../aspose.imaging/streamcontainer/write/#write)(byte[]) | 将所有指定的字节写入流。 |
| virtual [Write](../../aspose.imaging/streamcontainer/write/#write_1)(byte[], int, int) | 将一系列字节写入当前流，并将此流中的当前位置前移写入的字节数。 |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte/)(byte) | 将一个字节写入流的当前位置，并将流中的位置前移一个字节。 |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/#writeto)(StreamContainer) | 将包含的数据复制到另一个 `StreamContainer`。 |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | 将包含的数据复制到另一个 `StreamContainer`。 |
| [explicit operator](../../aspose.imaging/streamcontainer/op_explicit/) | 执行从 `StreamContainer` 到 Stream 的显式转换。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.imaging/streamcontainer/readwritebytescount/) | 指定顺序读取时的读写字节计数。 |

### 另请参见

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


