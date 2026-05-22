---
title: "EmfPlusPath.PathPoints"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusPath 属性。获取或设置路径点数组。一个由 PathPointCount 点组成的数组，指定路径。此数组中对象的类型由 PathPointFlags 字段指定，如下：如果 P 标志被设置，则点是相对位置，由 EmfPlusPointR 对象（第 2.2.2.37 节）指定。如果 P 标志未设置且 C 标志被设置，则点是绝对位置，由 EmfPlusPoint 对象（第 2.2.2.35 节）指定。如果 P 标志未设置且 C 标志也未设置，则点是绝对位置，由 EmfPlusPointF 对象（第 2.2.2.36 节）指定。"
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpoints/
---
## EmfPlusPath.PathPoints property

获取或设置路径点数组。一个包含 PathPointCount 个点的数组，用于指定路径。数组中对象的类型由 PathPointFlags 字段指定，具体如下：如果设置了 P 标志，则这些点是由 EmfPlusPointR 对象（章节 2.2.2.37）指定的相对位置；如果 P 标志未设置且 C 标志已设置，则这些点是由 EmfPlusPoint 对象（章节 2.2.2.35）指定的绝对位置；如果 P 标志和 C 标志均未设置，则这些点是由 EmfPlusPointF 对象（章节 2.2.2.36）指定的绝对位置。

```csharp
public PointF[] PathPoints { get; set; }
```

### 另请参见

* struct [PointF](../../../aspose.imaging/pointf/)
* class [EmfPlusPath](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfpluspath/)
* assembly [Aspose.Imaging](../../../)


