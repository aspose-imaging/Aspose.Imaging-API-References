---
title: "EmfPlusDrawBeziers.PointData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusDrawBeziers 属性。获取或设置点数据。一个包含 Count 个点的数组，指定贝塞尔曲线的起点、终点和控制点。一个贝塞尔曲线的结束坐标是下一个贝塞尔曲线的起始坐标。控制点用于产生贝塞尔效果。此数组中的数据类型由 Flags 字段指定，如下：数据类型 含义 EmfPlusPointR 对象（章节 2.2.2.37）如果 Flags 中的 P 标志被设置，点指定相对位置。EmfPlusPointF 对象（章节 2.2.2.36）如果 Flags 字段中的 P 和 C 位均清除，点指定绝对位置。EmfPlusPoint 对象（章节 2.2.2.35）如果 Flags 字段中 P 位清除且 C 位设置，点指定相对位置。贝塞尔曲线不会经过其控制点。控制点的作用是"
type: docs
weight: 40
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata/
---
## EmfPlusDrawBeziers.PointData property

获取或设置点数据。一个包含 Count 个点的数组，指定贝塞尔曲线的起点、终点和控制点。一个贝塞尔曲线的结束坐标是下一个贝塞尔曲线的起始坐标。控制点用于产生贝塞尔效果。此数组中的数据类型由 Flags 字段指定，如下所示： 数据类型 含义 EmfPlusPointR 对象（第 2.2.2.37 节） 如果 Flags 中设置了 P 标志，则点指定相对位置。 EmfPlusPointF 对象（第 2.2.2.36 节） 如果 Flags 字段中的 P 和 C 位均未设置，则点指定绝对位置。 EmfPlusPoint 对象（第 2.2.2.35 节） 如果 Flags 中未设置 P 位且设置了 C 位，则点指定相对位置。贝塞尔曲线不会经过其控制点。控制点的作用是

```csharp
public PointF[] PointData { get; set; }
```

### 另请参见

* struct [PointF](../../../aspose.imaging/pointf/)
* class [EmfPlusDrawBeziers](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawbeziers/)
* assembly [Aspose.Imaging](../../../)


