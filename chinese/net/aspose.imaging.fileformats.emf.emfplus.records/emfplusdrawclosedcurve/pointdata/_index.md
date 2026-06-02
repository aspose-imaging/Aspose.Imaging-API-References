---
title: "EmfPlusDrawClosedCurve.PointData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusDrawClosedCurve 属性。获取或设置点数据。一个包含 Count 个点的数组，指定定义样条线的线段的端点。在闭合基数样条中，曲线会通过 PointData 数组的最后一个点并连接到数组的第一个点。此数组中的数据类型由 Flags 字段指定，如下：Data Type Meaning EmfPlusPointR 对象（第 2.2.2.37 节）——如果 Flags 中设置了 P 标志，则点指定相对位置。EmfPlusPointF 对象（第 2.2.2.36 节）——如果 Flags 中同时设置了 P 和 C 位，则点指定绝对位置。EmfPlusPoint 对象（第 2.2.2.35 节）——如果 Flags 中未设置 P 位且设置了 C 位，则点指定相对位置。"
type: docs
weight: 40
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata/
---
## EmfPlusDrawClosedCurve.PointData property

获取或设置点数据。一个包含 Count 个点的数组，这些点指定定义样条曲线的线段的端点。在闭合基数样条中，曲线通过 PointData 数组中的最后一点继续，并与数组中的第一点相连。此数组中的数据类型由 Flags 字段指定，如下所示：数据类型 含义 EmfPlusPointR 对象（第 2.2.2.37 节）如果 Flags 中设置了 P 标志，则点指定相对位置。EmfPlusPointF 对象（第 2.2.2.36 节）如果 Flags 字段中同时设置了 P 和 C 位，则点指定绝对位置。EmfPlusPoint 对象（第 2.2.2.35 节）如果 Flags 字段中 P 位未设置且 C 位已设置，则点指定相对位置。

```csharp
public PointF[] PointData { get; set; }
```

### 另请参见

* struct [PointF](../../../aspose.imaging/pointf/)
* class [EmfPlusDrawClosedCurve](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawclosedcurve/)
* assembly [Aspose.Imaging](../../../)


