---
title: "类 EmfRecorderGraphics2D"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D 类。Emf 记录器图形"
type: docs
weight: 6610
url: /zh/net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
## EmfRecorderGraphics2D class

该 Emf 记录器图形

```csharp
public sealed class EmfRecorderGraphics2D : MetafileRecorderGraphics2D
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfRecorderGraphics2D](emfrecordergraphics2d/)(Rectangle, Size, Size) | 初始化 `EmfRecorderGraphics2D` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor/) { get; set; } | 获取或设置背景颜色。 |
| [BackgroundMode](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/backgroundmode/) { get; set; } | 获取或设置背景模式。 |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip/) { get; set; } | 获取或设置限制此 Graphics 绘图区域的 Region |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds/) { get; } | 获取剪辑边界。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromEmfImage](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/fromemfimage/)(EmfImage) | 获取 `EmfRecorderGraphics2D` 的实例，其中包含来自 Emf 图像的所有记录。 |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear/)() | 清除 graphics 对象的状态 |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc/)(Pen, Rectangle, float, float) | 绘制由 Rectangle 结构指定的椭圆部分的弧。 |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier/)(Pen, Point, Point, Point, Point) | 绘制三次贝塞尔曲线。 |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse/)(Pen, Rectangle) | 绘制椭圆。 |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(RasterImage, Point) | 在指定位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(byte[], Rectangle, GraphicsUnit) | 绘制图像。 |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(Stream, Rectangle, GraphicsUnit) | 绘制图像。 |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | 在指定位置以指定尺寸绘制指定图像的指定部分。 |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline/)(Pen, Point, Point) | 绘制直线。 |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline/)(Pen, int, int, int, int) | 绘制直线。 |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath/)(Pen, GraphicsPath) | 绘制路径。 |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie/)(Pen, Rectangle, float, float) | 绘制饼形。 |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier/)(Pen, Point[]) | 绘制多段三次贝塞尔曲线。 |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon/)(Pen, Point[]) | 绘制多边形。 |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline/)(Pen, Point[]) | 绘制折线。 |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle/)(Pen, Rectangle) | 绘制矩形。 |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle/)(Pen, int, int, int, int) | 绘制矩形。 |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring/)(string, Font, Color, int, int) | 绘制字符串。 |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring/)(string, Font, Color, int, int, float) | 绘制字符串。 |
| [EndRecording](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/endrecording/)() | 结束录制。 |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip/)(Rectangle) | 更新此 Graphics 的剪裁区域，以排除由 Rectangle 结构指定的区域。 |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip/)(Region) | 更新此 Graphics 的剪裁区域，以排除由 Region 指定的区域。 |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse/)(Brush, Rectangle) | 填充椭圆。 |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath/)(Pen, Brush, GraphicsPath) | 填充路径。 |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie/)(Brush, Rectangle, float, float) | 填充饼形。 |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon/)(Brush, Point[]) | 填充多边形。 |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon/)(Brush, Point[], FillMode) | 填充多边形。 |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle/)(Brush, Rectangle) | 填充矩形。 |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform/)() | 获取世界变换。 |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip/)(RectangleF) | 更新此 Graphics 的剪裁区域，使其为当前剪裁区域与指定的 Rectangle 结构的交集。 |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip/)(Region) | 更新此 Graphics 的剪裁区域，使其为当前剪裁区域与指定的 Region 的交集。 |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform/)(Matrix) | 将此 Graphics 的世界变换与指定的矩阵相乘。 |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform/)(Matrix, MatrixOrder) | 按指定顺序将此 Graphics 的世界变换与指定的矩阵相乘。 |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip/)() | 重置剪裁。 |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform/)(float) | 将指定的旋转应用于此 Graphics 的变换矩阵。 |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform/)(float, PointF, MatrixOrder) | 按指定顺序将指定的旋转应用于此 Graphics 的变换矩阵。 |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform/)(float, float) | 通过将指定的缩放操作前置到对象的变换矩阵中，将其应用于此 Graphics 的变换矩阵。 |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform/)(float, float, MatrixOrder) | 按指定顺序将指定的缩放操作应用于此 Graphics 的变换矩阵。 |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform/)(Matrix) | 设置变换。 |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform/)(float, float) | 通过将指定的平移前置到此 Graphics 的变换矩阵中，改变坐标系的原点。 |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform/)(float, float, MatrixOrder) | 按指定顺序将指定的平移应用于此 Graphics 的变换矩阵，改变坐标系的原点。 |

### 另请参见

* class [MetafileRecorderGraphics2D](../metafilerecordergraphics2d/)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics/)
* assembly [Aspose.Imaging](../../)


