---
title: EmfPlusPath
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusPath 对象指定形成图形路径的一系列直线和曲线段贝塞尔数据点的 顺序是起点控制点 1控制点 2 和终点有关 更多信息请参阅MSDN - DrawBeziers
type: docs
weight: 5610
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
## EmfPlusPath class

EmfPlusPath 对象指定形成图形路径的一系列直线和曲线段。贝塞尔数据点的 顺序是起点、控制点 1、控制点 2 和终点。有关 更多信息，请参阅[MSDN - DrawBeziers]。

```csharp
public sealed class EmfPlusPath : EmfPlusGraphicsObjectType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusPath](emfpluspath)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [PathPointFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointflags) { get; set; } | 获取或设置路径点数 一个 32 位无符号整数，指定如何解释由此定义的点和相关点类型对象 |
| [PathPoints](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpoints) { get; set; } | 获取或设置路径点数组 指定路径的 PathPointCount 点数组。此数组中的对象类型由 PathPointFlags 字段指定，如下所示: 如果设置了 P 标志，则这些点是 EmfPlusPointR 对象指定的相对位置（第 2.2.2.37 节）。 如果清除了 P 标志并设置了 C 标志，则这些点是 EmfPlusPoint 对象指定的绝对位置（第 2.2.2.35 节）。 如果清除了 P 标志并且清除了 C 标志，则这些点是 EmfPlusPointF 对象指定的绝对位置（第 2.2.2.36 节）。 |
| [PathPointTypes](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointtypes) { get; set; } | 获取或设置一个数组，该数组指定如何使用 PathPoints 字段中的点绘制路径。 此数组中的对象类型由 PathPointFlags 字段中的 R 标志指定 |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | 获取或设置版本。 |

### 也可以看看

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->