---
title: "类 EmfPlusPath"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPath 类。EmfPlusPath 对象指定形成图形路径的一系列直线和曲线段。Bezier 数据点的顺序为起点、控制点 1、控制点 2 和终点。更多信息请参见 MSDN DrawBeziers。"
type: docs
weight: 5730
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
## EmfPlusPath class

该 EmfPlusPath 对象指定形成图形路径的一系列直线和曲线段。Bezier 数据点的顺序为起点、控制点 1、控制点 2 和终点。更多信息请参见[MSDN - DrawBeziers]。

```csharp
public sealed class EmfPlusPath : EmfPlusGraphicsObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusPath](emfpluspath/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [PathPointFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointflags/) { get; set; } | 获取或设置路径点计数，一个 32 位无符号整数，指定如何解释此对象定义的点及其关联的点类型。 |
| [PathPoints](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpoints/) { get; set; } | 获取或设置路径点数组。一个包含 PathPointCount 个点的数组，用于指定路径。数组中对象的类型由 PathPointFlags 字段指定，具体如下：如果设置了 P 标志，则这些点是由 EmfPlusPointR 对象（章节 2.2.2.37）指定的相对位置；如果 P 标志未设置且 C 标志已设置，则这些点是由 EmfPlusPoint 对象（章节 2.2.2.35）指定的绝对位置；如果 P 标志和 C 标志均未设置，则这些点是由 EmfPlusPointF 对象（章节 2.2.2.36）指定的绝对位置。 |
| [PathPointTypes](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointtypes/) { get; set; } | 获取或设置一个数组，指定 PathPoints 字段中的点如何用于绘制路径。数组中对象的类型由 PathPointFlags 字段中的 R 标志指定。 |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version/) { get; set; } | 获取或设置版本。 |

### 另请参见

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


