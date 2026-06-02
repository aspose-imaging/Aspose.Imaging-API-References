---
title: "类 CurveShape"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Shapes.CurveShape 类。表示一个曲线样条形状"
type: docs
weight: 11560
url: /zh/net/aspose.imaging.shapes/curveshape/
---
## CurveShape class

表示曲线样条形状。

```csharp
public sealed class CurveShape : PolygonShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | 初始化 `CurveShape` 类的新实例。 |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | 初始化 `CurveShape` 类的新实例。使用默认张力 0.5。 |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | 初始化 `CurveShape` 类的新实例。使用默认张力 0.5。 |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | 初始化 `CurveShape` 类的新实例。 |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | 初始化 `CurveShape` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/curveshape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.imaging.shapes/curveshape/center/) { get; } | 获取形状的中心。 |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint/) { get; } | 获取结束形状点。 |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments/) { get; } | 获取一个值，指示形状是否具有段。 |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed/) { get; set; } | 获取或设置一个值，指示形状是否闭合。 |
| [Points](../../aspose.imaging.shapes/polygonshape/points/) { get; set; } | 获取或设置曲线点。 |
| override [Segments](../../aspose.imaging.shapes/curveshape/segments/) { get; } | 获取形状的段。 |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint/) { get; } | 获取起始形状点。 |
| [Tension](../../aspose.imaging.shapes/curveshape/tension/) { get; set; } | 获取或设置曲线张力。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.imaging.shapes/curveshape/equals/)(object) | 检查对象是否相等。 |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| override [GetHashCode](../../aspose.imaging.shapes/curveshape/gethashcode/)() | 获取当前对象的哈希码。 |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse/)() | 反转此形状的点顺序。 |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform/)(Matrix) | 对形状应用指定的变换。 |

### 另请参见

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.Imaging.Shapes](../../aspose.imaging.shapes/)
* assembly [Aspose.Imaging](../../)


