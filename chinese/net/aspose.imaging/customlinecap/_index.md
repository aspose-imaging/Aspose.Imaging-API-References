---
title: "类 CustomLineCap"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.CustomLineCap 类。封装了自定义用户定义的线帽。"
type: docs
weight: 780
url: /zh/net/aspose.imaging/customlinecap/
---
## CustomLineCap class

封装自定义用户定义的线帽。

```csharp
public class CustomLineCap
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CustomLineCap](customlinecap/#constructor)(GraphicsPath, GraphicsPath) | 使用指定的轮廓和填充初始化 `CustomLineCap` 类的新实例。 |
| [CustomLineCap](customlinecap/#constructor_1)(GraphicsPath, GraphicsPath, LineCap) | 从指定的现有 [`LineCap`](../linecap/) 枚举以及指定的轮廓和填充初始化 `CustomLineCap` 类的新实例。 |
| [CustomLineCap](customlinecap/#constructor_2)(GraphicsPath, GraphicsPath, LineCap, float) | 从指定的现有 [`LineCap`](../linecap/) 枚举以及指定的轮廓、填充和内嵌距离初始化 `CustomLineCap` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BaseCap](../../aspose.imaging/customlinecap/basecap/) { get; set; } | 获取或设置此 `CustomLineCap` 所基于的 [`LineCap`](../linecap/) 枚举。 |
| [BaseInset](../../aspose.imaging/customlinecap/baseinset/) { get; set; } | 获取或设置帽子与线之间的距离。 |
| [FillPath](../../aspose.imaging/customlinecap/fillpath/) { get; set; } | 获取或设置定义自定义帽子填充的对象。 |
| [StrokeJoin](../../aspose.imaging/customlinecap/strokejoin/) { get; set; } | 获取或设置决定组成此 `CustomLineCap` 对象的线段如何连接的 [`LineJoin`](../linejoin/) 枚举。 |
| [StrokePath](../../aspose.imaging/customlinecap/strokepath/) { get; set; } | 获取或设置定义自定义帽子轮廓的对象。 |
| [WidthScale](../../aspose.imaging/customlinecap/widthscale/) { get; set; } | 获取或设置相对于 Pen 对象宽度，对此 `CustomLineCap` 类对象进行缩放的比例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.imaging/customlinecap/equals/)(object) | 检查对象是否相等。 |
| override [GetHashCode](../../aspose.imaging/customlinecap/gethashcode/)() | 获取当前对象的哈希码。 |
| [GetStrokeCaps](../../aspose.imaging/customlinecap/getstrokecaps/)(out LineCap, out LineCap) | 获取用于开始和结束构成此自定义帽子的线段的帽子。 |
| [SetStrokeCaps](../../aspose.imaging/customlinecap/setstrokecaps/)(LineCap, LineCap) | 设置用于开始和结束构成此自定义帽子的线段的帽子。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


