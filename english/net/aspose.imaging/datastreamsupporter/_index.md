---
title: Class DataStreamSupporter
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.DataStreamSupporter class. The data stream container
type: docs
weight: 810
url: /net/aspose.imaging/datastreamsupporter/
---
## DataStreamSupporter class

The data stream container.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Properties

| Name | Description |
| --- | --- |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached/) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |

## Methods

| Name | Description |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata/)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](./datastreamcontainer/). |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/#save)() | Saves the object's data to the current `DataStreamSupporter`. |
| [Save](../../aspose.imaging/datastreamsupporter/save/#save_1)(Stream) | Saves the object's data to the specified stream. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/#save_2)(string) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/#save_3)(string, bool) | Saves the object's data to the specified file location. |

### See Also

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


