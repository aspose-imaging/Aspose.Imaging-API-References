---
title: "类 Graphics"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Graphics 类。表示根据当前程序集使用的图形引擎的图形。"
type: docs
weight: 9540
url: /zh/net/aspose.imaging/graphics/
---
## Graphics class

表示根据当前程序集使用的图形引擎的图形。

```csharp
public sealed class Graphics
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Graphics](graphics/)(Image) | 初始化 `Graphics` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip/) { get; set; } | 获取或设置裁剪区域。 |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality/) { get; set; } | 获取或设置复合质量。 |
| [DpiX](../../aspose.imaging/graphics/dpix/) { get; } | 获取此 Aspose.Imaging.Graphics 的水平分辨率。 |
| [DpiY](../../aspose.imaging/graphics/dpiy/) { get; } | 获取此 Aspose.Imaging.Graphics 的垂直分辨率。 |
| [Image](../../aspose.imaging/graphics/image/) { get; } | 获取图像。 |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode/) { get; set; } | 获取或设置插值模式。 |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall/) { get; } | 获取一个值，指示图形是否处于 BeginUpdate 调用状态。 |
| [PageScale](../../aspose.imaging/graphics/pagescale/) { get; set; } | 获取或设置此 Aspose.Imaging.Graphics 的世界单位与页面单位之间的缩放比例。 |
| [PageUnit](../../aspose.imaging/graphics/pageunit/) { get; set; } | 获取或设置此 Aspose.Imaging.Graphics 中页面坐标使用的计量单位。 |
| [PaintableImageOptions](../../aspose.imaging/graphics/paintableimageoptions/) { get; set; } | 获取或设置图像选项，用于创建可绘制的矢量图像。 |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode/) { get; set; } | 获取或设置平滑模式。 |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint/) { get; set; } | 获取或设置文本渲染提示。 |
| [Transform](../../aspose.imaging/graphics/transform/) { get; set; } | 获取或设置此 `Graphics` 的几何世界变换的副本。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate/)() | 开始缓存以下图形操作。随后应用的图形效果不会立即生效，而是等到 EndUpdate 时一次性应用所有效果。 |
| [Clear](../../aspose.imaging/graphics/clear/)(Color) | 使用指定的颜色清除图形表面。 |
| [DrawArc](../../aspose.imaging/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | 绘制一个弧线，表示由 [`Rectangle`](../rectangle/) 结构指定的椭圆的一部分。 |
| [DrawArc](../../aspose.imaging/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | 绘制一个弧线，表示由 [`RectangleF`](../rectanglef/) 结构指定的椭圆的一部分。 |
| [DrawArc](../../aspose.imaging/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | 绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。 |
| [DrawArc](../../aspose.imaging/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | 绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。 |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | 绘制由四个[`Point`](../point/)结构定义的贝塞尔样条。 |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | 绘制由四个[`PointF`](../pointf/)结构定义的贝塞尔样条。 |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | 绘制由四对有序坐标点（表示点）定义的贝塞尔样条。 |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | 从[`PointF`](../pointf/)结构数组绘制一系列贝塞尔样条。 |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | 从[`Point`](../point/)结构数组绘制一系列贝塞尔样条。 |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | 绘制由[`PointF`](../pointf/)结构数组定义的闭合基数样条。此方法使用默认张力 0.5 和 Alternate 填充模式。 |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | 绘制由[`Point`](../point/)结构数组定义的闭合基数样条。此方法使用默认张力 0.5 和 Alternate 填充模式。 |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | 绘制由[`PointF`](../pointf/)结构数组定义的闭合基数样条，使用指定的张力。此方法使用默认的 Alternate 填充模式。 |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | 绘制由[`Point`](../point/)结构数组定义的闭合基数样条，使用指定的张力。此方法使用默认的 Alternate 填充模式。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | 绘制通过指定的[`PointF`](../pointf/)结构数组的基数样条。此方法使用默认张力 0.5。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | 绘制通过指定的[`Point`](../point/)结构数组的基数样条。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | 绘制通过指定的[`PointF`](../pointf/)结构数组的基数样条，使用指定的张力。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | 绘制通过指定的[`Point`](../point/)结构数组的基数样条，使用指定的张力。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | 绘制通过指定的[`PointF`](../pointf/)结构数组的基数样条。绘制从数组起始位置偏移开始。此方法使用默认张力 0.5。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | 绘制通过指定的[`PointF`](../pointf/)结构数组的基数样条，使用指定的张力。绘制从数组起始位置偏移开始。 |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | 绘制通过指定的[`Point`](../point/)结构数组的基数样条，使用指定的张力。 |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | 绘制由边界[`Rectangle`](../rectangle/)结构指定的椭圆。 |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | 绘制由边界[`RectangleF`](../rectanglef/)定义的椭圆。 |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | 绘制由一对坐标、宽度和高度指定的边界矩形定义的椭圆。 |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | 绘制由一对坐标、宽度和高度指定的边界矩形定义的椭圆。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage)(Image, Point) | 在指定位置绘制指定的[`Image`](./image/)，使用其原始物理尺寸。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_1)(Image, PointF) | 在指定位置绘制指定的[`Image`](./image/)，使用其原始物理尺寸。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_2)(Image, PointF[]) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_6)(Image, Point[]) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_10)(Image, Rectangle) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_15)(Image, RectangleF) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_22)(Image, float, float) | 在指定位置绘制指定的[`Image`](./image/)，使用其原始物理尺寸。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_20)(Image, int, int) | 在由坐标对指定的位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImage](../../aspose.imaging/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | 在指定位置并使用指定尺寸绘制指定的[`Image`](./image/)。 |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | 在指定位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | 在指定位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | 在由坐标对指定的位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | 在指定位置绘制指定的图像，使用其原始物理尺寸。 |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | 在不进行缩放的情况下绘制指定的图像，并在必要时裁剪它以适应指定的矩形。 |
| [DrawLine](../../aspose.imaging/graphics/drawline/#drawline)(Pen, Point, Point) | 绘制一条连接两个[`Point`](../point/)结构的直线。 |
| [DrawLine](../../aspose.imaging/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | 绘制一条连接两个[`PointF`](../pointf/)结构的直线。 |
| [DrawLine](../../aspose.imaging/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | 绘制一条连接由坐标对指定的两个点的直线。 |
| [DrawLine](../../aspose.imaging/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | 绘制一条连接由坐标对指定的两个点的直线。 |
| [DrawLines](../../aspose.imaging/graphics/drawlines/#drawlines)(Pen, PointF[]) | 绘制一系列连接[`PointF`](../pointf/)结构数组的线段。 |
| [DrawLines](../../aspose.imaging/graphics/drawlines/#drawlines_1)(Pen, Point[]) | 绘制一系列连接[`Point`](../point/)结构数组的线段。 |
| [DrawPath](../../aspose.imaging/graphics/drawpath/)(Pen, GraphicsPath) | 绘制一个[`GraphicsPath`](../graphicspath/)。 |
| [DrawPie](../../aspose.imaging/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | 绘制由[`Rectangle`](../rectangle/)结构指定的椭圆和两条径向线定义的饼形。 |
| [DrawPie](../../aspose.imaging/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | 绘制由[`RectangleF`](../rectanglef/)结构指定的椭圆和两条径向线定义的饼形。 |
| [DrawPie](../../aspose.imaging/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [DrawPie](../../aspose.imaging/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | 绘制由[`PointF`](../pointf/)结构数组定义的多边形。 |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | 绘制由[`Point`](../point/)结构数组定义的多边形。 |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | 绘制由[`Rectangle`](../rectangle/)结构指定的矩形。 |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | 绘制由[`RectangleF`](../rectanglef/)结构指定的矩形。 |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | 绘制由[`RectangleF`](../rectanglef/)结构指定的一系列矩形。 |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | 绘制由[`Rectangle`](../rectangle/)结构指定的一系列矩形。 |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | 在指定位置使用指定的[`Brush`](../brush/)和[`Font`](../font/)对象绘制指定的文本字符串。 |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | 在指定矩形中使用指定的[`Brush`](../brush/)和[`Font`](../font/)对象绘制指定的文本字符串。 |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | 在指定位置使用指定的[`Brush`](../brush/)和[`Font`](../font/)对象绘制指定的文本字符串。 |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | 在指定位置使用指定的[`Brush`](../brush/)和[`Font`](../font/)对象，并使用指定[`StringFormat`](../stringformat/)的格式属性绘制指定的文本字符串。 |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | 在指定矩形中使用指定的[`Brush`](../brush/)和[`Font`](../font/)对象，并使用指定[`StringFormat`](../stringformat/)的格式属性绘制指定的文本字符串。 |
| [DrawString](../../aspose.imaging/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | 在指定位置使用指定的[`Brush`](../brush/)和[`Font`](../font/)对象，并使用指定[`StringFormat`](../stringformat/)的格式属性绘制指定的文本字符串。 |
| [EndUpdate](../../aspose.imaging/graphics/endupdate/)() | 完成在调用 BeginUpdate 后启动的图形操作的缓存。调用此方法时，前面的图形操作将一次性应用。 |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | 填充由[`PointF`](../pointf/)结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 Alternate 填充模式。 |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | 填充由[`Point`](../point/)结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 Alternate 填充模式。 |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | 使用指定的填充模式填充由[`PointF`](../pointf/)结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。 |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | 使用指定的填充模式填充由一组 [`Point`](../point/) 结构定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。 |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | 使用指定的填充模式和张力填充由一组 [`PointF`](../pointf/) 结构定义的闭合基数样条曲线的内部。 |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | 使用指定的填充模式和张力填充由一组 [`Point`](../point/) 结构定义的闭合基数样条曲线的内部。 |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | 填充由 [`Rectangle`](../rectangle/) 结构指定的边界矩形定义的椭圆的内部。 |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | 填充由 [`RectangleF`](../rectanglef/) 结构指定的边界矩形定义的椭圆的内部。 |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [FillPath](../../aspose.imaging/graphics/fillpath/)(Brush, GraphicsPath) | 填充 [`GraphicsPath`](../graphicspath/) 的内部。 |
| [FillPie](../../aspose.imaging/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | 填充由 [`RectangleF`](../rectanglef/) 结构指定的椭圆和两条径向线定义的饼形区域的内部。 |
| [FillPie](../../aspose.imaging/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | 填充由 [`RectangleF`](../rectanglef/) 结构指定的椭圆和两条径向线定义的饼形区域的内部。 |
| [FillPie](../../aspose.imaging/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | 填充由一对坐标、宽度、高度以及两条径向线指定的椭圆定义的饼形区域的内部。 |
| [FillPie](../../aspose.imaging/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | 填充由一对坐标、宽度、高度以及两条径向线指定的椭圆定义的饼形区域的内部。 |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | 使用 Alternate 填充由一组由 [`PointF`](../pointf/) 结构指定的点定义的多边形的内部。 |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | 使用 Alternate 填充由一组由 [`Point`](../point/) 结构指定的点定义的多边形的内部。 |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | 使用指定的填充模式填充由一组由 [`PointF`](../pointf/) 结构指定的点定义的多边形的内部。 |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | 使用指定的填充模式填充由一组由 [`Point`](../point/) 结构指定的点定义的多边形的内部。 |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | 填充由 [`Rectangle`](../rectangle/) 结构指定的矩形的内部。 |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | 填充由 [`RectangleF`](../rectanglef/) 结构指定的矩形的内部。 |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | 填充由 [`RectangleF`](../rectanglef/) 结构指定的一系列矩形的内部。 |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | 填充由 [`Rectangle`](../rectangle/) 结构指定的一系列矩形的内部。 |
| [FillRegion](../../aspose.imaging/graphics/fillregion/)(Brush, Region) | 填充 [`Region`](../region/) 的内部。 |
| [MeasureString](../../aspose.imaging/graphics/measurestring/)(string, Font, SizeF, StringFormat) | 使用指定的参数测量指定的文本字符串。 |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform/#multiplytransform)(Matrix) | 通过在前面添加指定的 [`Matrix`](../matrix/)，将表示此 `Graphics` 本地几何变换的 [`Matrix`](../matrix/) 与指定的 [`Matrix`](../matrix/) 相乘。 |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 按照指定的顺序，将表示此 `Graphics` 本地几何变换的 [`Matrix`](../matrix/) 与指定的 [`Matrix`](../matrix/) 相乘。 |
| [ResetTransform](../../aspose.imaging/graphics/resettransform/)() | 将 [`Transform`](./transform/) 属性重置为单位矩阵。 |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform/#rotatetransform)(float) | 按指定角度旋转本地几何变换。此方法将旋转前置到变换中。 |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 按指定顺序以指定角度旋转本地几何变换。 |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform/#scaletransform)(float, float) | 按指定比例缩放本地几何变换。此方法将缩放矩阵前置到变换中。 |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 按指定顺序以指定比例缩放本地几何变换。 |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform/#translatetransform)(float, float) | 按指定尺寸平移本地几何变换。此方法将平移前置到变换中。 |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 按指定顺序以指定尺寸平移本地几何变换。 |

## 示例

此示例使用 Graphics 类在 Image 表面创建基本形状。为了演示操作，示例创建一个 PNG 格式的新 Image，并使用 Graphics 类提供的 Draw 方法在 Image 表面绘制基本形状。

```csharp
[C#]

//创建 FileStream 的实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //创建 PngOptions 的实例并设置其各种属性
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //为 PngOptions 设置 Source
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //创建并初始化 Graphics 类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除 Graphics 表面
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //通过指定具有黑色的 Pen 对象绘制弧线，
        //一个围绕弧线的 Rectangle、起始角度和扫掠角度
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //通过指定具有蓝色的 Pen 对象和坐标点绘制贝塞尔曲线。
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //通过指定具有绿色的 Pen 对象和点数组绘制曲线
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //使用 Pen 对象和围绕的 Rectangle 绘制椭圆
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //绘制直线
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //绘制饼图扇形
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //通过指定具有红色的 Pen 对象和点数组绘制多边形
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //绘制矩形
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //创建 SolidBrush 对象并设置其各种属性
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //使用 SolidBrush 对象和 Font 在特定点绘制字符串
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // 保存所有更改。
        image.Save();
    }
}
```

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


