---
title: "类 EmfPlusPathPointTypeRle"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPathPointTypeRle 类。EmfPlusPathPointTypeRle 对象指定使用 RLE 压缩的图形路径点关联的类型值。0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B1RunCount  PointType  B 1 位 如果设置，则路径点位于贝塞尔曲线上；如果未设置，则路径点位于普通直线。RunCount 6 位 表示与 PointType 字段中的类型关联的路径点数量。PointType 1 字节 一个 EmfPlusPathPointType 对象（section 2.2.2.31），用于指定与路径点关联的类型。"
type: docs
weight: 5770
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
## EmfPlusPathPointTypeRle class

该 EmfPlusPathPointTypeRle 对象指定使用 RLE 压缩的图形路径上点的类型值。0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B&#x7C;1&#x7C;RunCount &#x7C; PointType &#x7C; B (1 位)：如果设置，则路径点位于贝塞尔曲线上。如果清除，则路径点位于图形直线上。RunCount (6 位)：运行计数，即与 PointType 字段中的类型关联的路径点数量。PointType (1 字节)：一个 EmfPlusPathPointType 对象（第 2.2.2.31 节），指定要与路径点关联的类型。

```csharp
public sealed class EmfPlusPathPointTypeRle : EmfPlusBasePointType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusPathPointTypeRle](emfpluspathpointtyperle/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bezier](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/bezier/) { get; set; } | 获取或设置一个值，指示此 `EmfPlusPathPointTypeRle` 是否为贝塞尔。如果设置，则路径点位于贝塞尔曲线上；如果未设置，则路径点位于普通直线。 |
| [Data](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/data/) { get; set; } | 获取或设置数据。 |
| [PointType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/pointtype/) { get; set; } | 获取或设置点的类型。PointType（1 字节）：一个 EmfPlusPathPointType 对象（section 2.2.2.31），用于指定与路径点关联的类型。 |
| [RunCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/runcount/) { get; set; } | 获取或设置运行计数。RunCount（6 位）：运行计数，即在 PointType 字段中与该类型关联的路径点数量。 |

### 另请参见

* class [EmfPlusBasePointType](../emfplusbasepointtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


