---
title: Graphics
second_title: Aspose.Imaging for .NET API 参考
description: 根据当前程序集中使用的图形引擎表示图形
type: docs
weight: 9360
url: /zh/net/aspose.imaging/graphics/
---
## Graphics class

根据当前程序集中使用的图形引擎表示图形。

```csharp
public sealed class Graphics
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Graphics](graphics)(Image) | 初始化[`Graphics`](../graphics)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | 获取或设置剪辑区域。 |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | 获取或设置合成质量。 |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | 获取此 Aspose.Imaging.Graphics. 的水平分辨率 |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | 获取此 Aspose.Imaging.Graphics. 的垂直分辨率 |
| [Image](../../aspose.imaging/graphics/image) { get; } | 获取图像。 |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | 获取或设置插值模式。 |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | 获取一个值，该值指示图形是否处于 BeginUpdate 调用状态。 |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | 获取或设置此 Aspose.Imaging.Graphics. 的世界单位和页面单位之间的缩放比例 |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | 获取或设置用于此 Aspose.Imaging.Graphics. 中页面坐标的测量单位 |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | 获取或设置平滑模式。 |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | 获取或设置文本渲染提示。 |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | 获取或设置几何世界变换的副本[`Graphics`](../graphics) . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | 开始缓存以下图形操作。之后应用的图形效果不会立即应用，而是 EndUpdate 将导致一次应用所有效果。 |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | 使用指定颜色清除图形表面。 |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | 绘制一条弧，表示由 a 指定的椭圆的一部分[`Rectangle`](../rectangle)结构. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | 绘制一条弧，表示由 a 指定的椭圆的一部分[`RectangleF`](../rectanglef)结构. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | 绘制表示由一对坐标、宽度和高度指定的椭圆的一部分的弧。 |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | 绘制表示由一对坐标、宽度和高度指定的椭圆的一部分的弧。 |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | 绘制由四个定义的贝塞尔样条曲线[`Point`](../point)结构. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | 绘制由四个定义的贝塞尔样条曲线[`PointF`](../pointf)结构. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | 绘制由四个有序坐标对定义的贝塞尔样条曲线，这些坐标对表示点。 |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | 从数组中绘制一系列贝塞尔样条[`PointF`](../pointf)结构. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | 从数组中绘制一系列贝塞尔样条[`Point`](../point)结构. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | 绘制由数组定义的闭合基数样条[`PointF`](../pointf)结构。此方法使用默认张力 0.5 和Alternate填充模式. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | 绘制由数组定义的闭合基数样条[`Point`](../point)结构。此方法使用默认张力 0.5 和Alternate填充模式. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | 绘制由数组定义的闭合基数样条[`PointF`](../pointf)使用指定张力的结构。此方法使用默认值Alternate填充模式. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | 绘制由数组定义的闭合基数样条[`Point`](../point)使用指定张力的结构。此方法使用默认值Alternate填充模式. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | 通过指定的数组绘制基数样条[`PointF`](../pointf)结构。此方法使用默认张力 0.5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | 通过指定的数组绘制基数样条[`Point`](../point)结构. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | 通过指定的数组绘制基数样条[`PointF`](../pointf)使用指定张力的结构。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | 通过指定的数组绘制基数样条[`Point`](../point)使用指定张力的结构。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | 通过指定的数组绘制基数样条[`PointF`](../pointf)结构。绘图从数组的开头偏移开始。 此方法使用默认张力 0.5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | 通过指定的数组绘制基数样条[`PointF`](../pointf)使用指定张力的结构。绘图从数组的开头偏移开始。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | 通过指定的数组绘制基数样条[`Point`](../point)使用指定张力的结构。 |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | 绘制由边界指定的椭圆[`Rectangle`](../rectangle)结构. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | 绘制由边界定义的椭圆[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | 绘制由一对坐标、高度和宽度指定的边界矩形定义的椭圆。 |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | 绘制由一对坐标、高度和宽度指定的边界矩形定义的椭圆。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | 绘制指定的[`Image`](./image)，在指定位置使用其原始物理尺寸。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | 绘制指定的[`Image`](./image)，在指定位置使用其原始物理尺寸。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | 绘制指定的指定部分*image*在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | 绘制指定的指定部分*image*在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | 绘制指定的[`Image`](./image)，在指定位置使用其原始物理尺寸。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | 在坐标对指定的位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | 绘制指定的指定部分*image*在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | 绘制指定的指定部分*image*在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | 绘制指定的指定部分*image*在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | 绘制指定的指定部分*image*在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | 绘制指定的指定部分*image*在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | 绘制指定的指定部分*image*在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | 绘制指定的[`Image`](./image)在指定的位置和指定的大小。 |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | 在指定位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | 在指定位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | 在坐标对指定的位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | 在指定位置使用其原始物理尺寸绘制指定图像。 |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | 在不缩放的情况下绘制指定的图像，并在必要时将其裁剪以适合指定的矩形。 |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | 画一条线连接两个[`Point`](../point)结构. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | 画一条线连接两个[`PointF`](../pointf)结构. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | 绘制一条连接由坐标对指定的两个点的线。 |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | 绘制一条连接由坐标对指定的两个点的线。 |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | 绘制一系列连接数组的线段[`PointF`](../pointf)结构. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | 绘制一系列连接数组的线段[`Point`](../point)结构. |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | 绘制一个[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | 绘制由 a 指定的椭圆定义的饼形[`Rectangle`](../rectangle)结构和两条径向线。 |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | 绘制由 a 指定的椭圆定义的饼形[`RectangleF`](../rectanglef)结构和两条径向线。 |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | 绘制由坐标对、宽度、高度和两条径向线指定的椭圆定义的饼形。 |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | 绘制由坐标对、宽度、高度和两条径向线指定的椭圆定义的饼形。 |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | 绘制由数组定义的多边形[`PointF`](../pointf)结构. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | 绘制由数组定义的多边形[`Point`](../point)结构. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | 绘制一个由 a 指定的矩形[`Rectangle`](../rectangle)结构. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | 绘制一个由 a 指定的矩形[`RectangleF`](../rectanglef)结构. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | 绘制一系列由指定的矩形[`RectangleF`](../rectanglef)结构. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | 绘制一系列由指定的矩形[`Rectangle`](../rectangle)结构. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | 在指定位置绘制指定文本字符串[`Brush`](../brush)和[`Font`](../font)对象. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | 用指定的矩形在指定的矩形中绘制指定的文本字符串[`Brush`](../brush)和[`Font`](../font)对象. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | 在指定位置绘制指定文本字符串[`Brush`](../brush)和[`Font`](../font)对象. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | 在指定位置绘制指定文本字符串[`Brush`](../brush)和[`Font`](../font)使用指定格式属性的对象[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | 用指定的矩形在指定的矩形中绘制指定的文本字符串[`Brush`](../brush)和[`Font`](../font)使用指定格式属性的对象[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | 在指定位置绘制指定文本字符串[`Brush`](../brush)和[`Font`](../font)使用指定格式属性的对象[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | 完成调用 BeginUpdate 后开始的图形操作的缓存。调用此方法时会立即应用前面的图形操作。 |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | 填充由数组定义的闭合基数样条曲线的内部[`PointF`](../pointf)结构。此方法使用默认张力 0.5 和Alternate填充模式. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | 填充由数组定义的闭合基数样条曲线的内部[`Point`](../point)结构。此方法使用默认张力 0.5 和Alternate填充模式. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | 填充由数组定义的闭合基数样条曲线的内部[`PointF`](../pointf)使用指定填充模式的结构。此方法使用默认张力 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | 填充由数组定义的闭合基数样条曲线的内部[`Point`](../point)使用指定填充模式的结构。此方法使用默认张力 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | 填充由数组定义的闭合基数样条曲线的内部[`PointF`](../pointf)使用指定填充模式和张力的结构。 |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | 填充由数组定义的闭合基数样条曲线的内部[`Point`](../point)使用指定填充模式和张力的结构。 |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | 填充由 a 指定的边界矩形定义的椭圆的内部[`Rectangle`](../rectangle)结构. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | 填充由 a 指定的边界矩形定义的椭圆的内部[`RectangleF`](../rectanglef)结构. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | 填充一个内部[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | 填充由 a 指定的椭圆定义的饼图部分的内部[`RectangleF`](../rectanglef)结构和两条径向线。 |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | 填充由 a 指定的椭圆定义的饼图部分的内部[`RectangleF`](../rectanglef)结构和两条径向线。 |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | 填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼图部分的内部。 |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | 填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的饼图部分的内部。 |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | 填充由指定的点数组定义的多边形内部[`PointF`](../pointf)结构和Alternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | 填充由指定的点数组定义的多边形内部[`Point`](../point)结构和Alternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | 填充由指定的点数组定义的多边形内部[`PointF`](../pointf)使用指定填充模式的结构。 |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | 填充由指定的点数组定义的多边形内部[`Point`](../point)使用指定填充模式的结构。 |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | 填充由 a 指定的矩形的内部[`Rectangle`](../rectangle)结构. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | 填充由 a 指定的矩形的内部[`RectangleF`](../rectanglef)结构. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | 填充由指定的一系列矩形的内部[`RectangleF`](../rectanglef)结构. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | 填充由指定的一系列矩形的内部[`Rectangle`](../rectangle)结构. |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | 填充一个内部[`Region`](../region) . |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | 用指定的参数测量指定的文本字符串 |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | 乘以[`Matrix`](../matrix)表示这个的局部几何变换[`Graphics`](../graphics)由指定的[`Matrix`](../matrix)通过预先指定[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | 乘以[`Matrix`](../matrix)表示这个的局部几何变换[`Graphics`](../graphics)由指定的[`Matrix`](../matrix)按指定顺序。 |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | 重置[`Transform`](./transform)身份的属性. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | 将局部几何变换旋转指定的量。此方法将旋转添加到 transform. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | 以指定顺序将局部几何变换旋转指定量。 |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | 按指定量缩放局部几何变换。此方法将缩放矩阵添加到 transform. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | 按指定顺序按指定量缩放局部几何变换。 |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到 transform. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | 以指定顺序按指定维度平移局部几何变换。 |

### 例子

此示例使用 Graphics 类在 Image 表面上创建原始形状。为了演示该操作，该示例创建一个 PNG 格式的新图像，并使用 Graphics 类公开的 Draw 方法在图像表面上绘制原始形状

```csharp
[C#]

//创建一个FileStream实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //创建一个PngOptions实例并设置它的各种属性
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //设置PngOptions的来源
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建一个Image实例 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //创建并初始化一个Graphics类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除图形表面
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //通过指定具有黑色颜色的Pen对象来绘制弧线， 
        //一个围绕圆弧的矩形，起始角和扫角
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //通过指定具有蓝色和坐标点的 Pen 对象来绘制 Bezier。
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //通过指定具有绿色的 Pen 对象和点数组来绘制曲线
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //使用 Pen 对象和周围的 Rectangle 绘制一个椭圆
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //画一条线 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //画一个饼段
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //通过指定具有红色的 Pen 对象和点数组来绘制多边形
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //画一个矩形
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //创建一个SolidBrush对象并设置它的各种属性
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //使用 SolidBrush 对象和字体在特定点绘制一个字符串
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // 保存所有更改。
        image.Save();
    }
}
```

### 也可以看看

* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
