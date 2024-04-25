---
title: MetafileRecorderGraphics2D
second_title: Aspose.Imaging for .NET API 参考
description: 元文件记录器 graphics
type: docs
weight: 6500
url: /zh/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
## MetafileRecorderGraphics2D class

元文件记录器 graphics

```csharp
public abstract class MetafileRecorderGraphics2D
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor) { get; set; } | 获取或设置背景颜色。 |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip) { get; set; } | 获取或设置一个Region，限制此Graphics的绘制区域 |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds) { get; } | 获取剪辑边界。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear)() | 清除图形对象 的状态 |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc)(Pen, Rectangle, float, float) | 绘制表示由 Rectangle 结构指定的椭圆的一部分的圆弧。 |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier)(Pen, Point, Point, Point, Point) | 绘制三次贝塞尔曲线。 |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse)(Pen, Rectangle) | 绘制椭圆。 |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage)(RasterImage, Point) | 在指定位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_2)(byte[], Rectangle, GraphicsUnit) | 绘制图像。 |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_3)(Stream, Rectangle, GraphicsUnit) | 绘制图像。 |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_1)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | 在指定位置以指定大小绘制指定图像的指定部分。 |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline#drawline)(Pen, Point, Point) | 画线。 |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline#drawline_1)(Pen, int, int, int, int) | 画线。 |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath)(Pen, GraphicsPath) | 绘制路径。 |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie)(Pen, Rectangle, float, float) | 绘制饼图。 |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier)(Pen, Point[]) | 绘制多边形贝塞尔曲线。 |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon)(Pen, Point[]) | 绘制多边形。 |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline)(Pen, Point[]) | 绘制折线。 |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle#drawrectangle)(Pen, Rectangle) | 绘制矩形。 |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle#drawrectangle_1)(Pen, int, int, int, int) | 绘制矩形。 |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring#drawstring)(string, Font, Color, int, int) | 绘制字符串。 |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring#drawstring_1)(string, Font, Color, int, int, float) | 绘制字符串。 |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip#excludeclip)(Rectangle) | 更新此 Graphics 的剪辑区域以排除由 Rectangle 结构指定的区域。 |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip#excludeclip_1)(Region) | 更新此 Graphics 的剪辑区域以排除 Region 指定的区域。 |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse)(Brush, Rectangle) | 填充椭圆。 |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath)(Pen, Brush, GraphicsPath) | 填充路径。 |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie)(Brush, Rectangle, float, float) | 填满馅饼。 |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon#fillpolygon)(Brush, Point[]) | 填充多边形。 |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon#fillpolygon_1)(Brush, Point[], FillMode) | 填充多边形。 |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle)(Brush, Rectangle) | 填充矩形。 |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform)() | 获取世界变换。 |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip#intersectclip)(RectangleF) | 将此 Graphics 的剪辑区域更新为当前剪辑区域与指定的 Rectangle 结构的交集。 |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip#intersectclip_1)(Region) | 将此Graphics的剪辑区域更新为当前剪辑区域与指定区域的交集。 |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform#multiplytransform)(Matrix) | 将此图形的世界变换相乘并指定矩阵。 |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | 乘以这个Graphics的世界变换，并按指定的顺序指定Matrix。 |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip)() | 重置剪辑。 |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform#rotatetransform)(float) | 将指定的旋转应用于此 Graphics 的变换矩阵。 |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform#rotatetransform_1)(float, PointF, MatrixOrder) | 以指定的顺序将指定的旋转应用于此 Graphics 的变换矩阵。 |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform#scaletransform)(float, float) | 将指定的缩放操作应用于此 Graphics 的变换矩阵，方法是将其添加到对象的变换矩阵中。 |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform#scaletransform_1)(float, float, MatrixOrder) | 以指定的顺序对这个Graphics的变换矩阵应用指定的缩放操作。 |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform)(Matrix) | 设置变换。 |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform#translatetransform)(float, float) | 通过将指定的平移附加到此 Graphics 的变换矩阵来更改坐标系的原点。 |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform#translatetransform_1)(float, float, MatrixOrder) | 通过按指定顺序将指定的平移应用于此 Graphics 的变换矩阵来更改坐标系的原点。 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
