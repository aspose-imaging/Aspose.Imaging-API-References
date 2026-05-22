---
title: "类 DataStreamSupporter"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.DataStreamSupporter 类。数据流容器"
type: docs
weight: 820
url: /zh/net/aspose.imaging/datastreamsupporter/
---
## DataStreamSupporter class

数据流容器。

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata/)() | 缓存数据并确保不会从底层的 [`DataStreamContainer`](./datastreamcontainer/) 加载额外的数据。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/#save)() | 将对象的数据保存到当前的 `DataStreamSupporter`。 |
| [Save](../../aspose.imaging/datastreamsupporter/save/#save_1)(Stream) | 将对象的数据保存到指定的流。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/#save_2)(string) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/#save_3)(string, bool) | 将对象的数据保存到指定的文件位置。 |

### 另请参见

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


