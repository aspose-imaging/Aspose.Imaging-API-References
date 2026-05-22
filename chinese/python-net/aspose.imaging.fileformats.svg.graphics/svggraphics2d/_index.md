---
title: "SvgGraphics2D 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---

**Summary:** Provides drawing commmands to compose an Svg image.

**Module:** [aspose.imaging.fileformats.svg.graphics](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/)

**Full Name:** aspose.imaging.fileformats.svg.graphics.SvgGraphics2D

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [SvgGraphics2D(image)](#SvgGraphics2D_image_1) | 初始化 [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) 类的新实例。 |
| [SvgGraphics2D(width, height, dpi)](#SvgGraphics2D_width_height_dpi_2) | 初始化 [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) 类的新实例。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | 绘制由 Rectangle 结构指定的椭圆的一部分弧。 |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | 绘制三次贝塞尔曲线。 |
| [draw_image(image, origin)](#draw_image_image_origin_3) | 在指定位置绘制指定的图像。 |
| [draw_image(image, origin, size)](#draw_image_image_origin_size_4) | 在指定位置绘制指定大小的指定图像。 |
| [draw_image(src_rect, dest_rect, image)](#draw_image_src_rect_dest_rect_image_5) | 在指定位置并使用指定大小绘制指定图像的指定部分。 |
| [draw_image_point_size(image, origin, size)](#draw_image_point_size_image_origin_size_6) | 在指定位置绘制指定大小的指定图像。 |
| [draw_image_src_dst_rects(src_rect, dest_rect, image)](#draw_image_src_dst_rects_src_rect_dest_rect_image_7) | 在指定位置并使用指定大小绘制指定图像的指定部分。 |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_8) | 绘制直线。 |
| [draw_path(pen, path)](#draw_path_pen_path_9) | 绘制路径。 |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_10) | 绘制矩形。 |
| [draw_string(font, text, origin, text_color)](#draw_string_font_text_origin_text_color_11) | 绘制文本字符串。 |
| [end_recording()](#end_recording__12) | 获取最终的 Svg 图像，其中包括通过 [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) 对象执行的所有绘图命令。 |
| [fill_arc(pen, brush, rect, start_angle, arc_angle)](#fill_arc_pen_brush_rect_start_angle_arc_angle_13) | 填充由矩形结构指定的椭圆的一部分弧线。 |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_14) | 填充路径。 |
| [fill_rectangle(pen, brush, x, y, width, height)](#fill_rectangle_pen_brush_x_y_width_height_15) | 填充矩形。 |


### Constructor: SvgGraphics2D(image) {#SvgGraphics2D_image_1}


```
 SvgGraphics2D(image) 
```

初始化 [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | 用于执行绘图操作的图像。 |

### Constructor: SvgGraphics2D(width, height, dpi) {#SvgGraphics2D_width_height_dpi_2}


```
 SvgGraphics2D(width, height, dpi) 
```

初始化 [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 输出 Svg 图像的宽度。 |
| height | int | 输出 Svg 图像的宽度。 |
| dpi | int | 设备分辨率，例如每英寸 96 点。 |


**See also:**

**[Example # 1](#example_171)**: This example shows how to create an SVG image of the specified size and raste...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

绘制由 Rectangle 结构指定的椭圆的一部分弧。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于绘制图形轮廓的笔。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 椭圆的边界。 |
| start_angle | float | 从 x 轴顺时针测量到弧线起始点的角度（度）。 |
| arc_angle | float | 从 startAngle 参数顺时针测量到弧线结束点的角度（度）。 |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

绘制三次贝塞尔曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定图形颜色、宽度和样式的笔。 |
| pt1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 曲线的起始点。 |
| pt2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 曲线的第一个控制点。 |
| pt3 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 曲线的第二个控制点。 |
| pt4 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 曲线的结束点。 |

### Method: draw_image(image, origin) {#draw_image_image_origin_3}


```
 draw_image(image, origin) 
```

在指定位置绘制指定的图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 已绘制的图像。 |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | 已绘制图像的位置。 |

### Method: draw_image(image, origin, size) {#draw_image_image_origin_size_4}


```
 draw_image(image, origin, size) 
```

在指定位置绘制指定大小的指定图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 已绘制的图像。 |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | 已绘制图像的位置。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 已绘制图像的期望大小。 |

### Method: draw_image(src_rect, dest_rect, image) {#draw_image_src_rect_dest_rect_image_5}


```
 draw_image(src_rect, dest_rect, image) 
```

在指定位置并使用指定大小绘制指定图像的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要绘制的图像对象的部分。 |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 已绘制图像的位置和大小。图像会缩放以适应矩形。 |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 要绘制的图像。 |

### Method: draw_image_point_size(image, origin, size) {#draw_image_point_size_image_origin_size_6}


```
 draw_image_point_size(image, origin, size) 
```

在指定位置绘制指定大小的指定图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 已绘制的图像。 |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | 已绘制图像的位置。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 已绘制图像的期望大小。 |

### Method: draw_image_src_dst_rects(src_rect, dest_rect, image) {#draw_image_src_dst_rects_src_rect_dest_rect_image_7}


```
 draw_image_src_dst_rects(src_rect, dest_rect, image) 
```

在指定位置并使用指定大小绘制指定图像的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要绘制的图像对象的部分。 |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 已绘制图像的位置和大小。图像会缩放以适应矩形。 |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 要绘制的图像。 |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_8}


```
 draw_line(pen, x1, y1, x2, y2) 
```

绘制直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 决定图形颜色、宽度和样式的笔。 |
| x1 | int | 第一个点的 x 坐标。 |
| y1 | int | 第一个点的 y 坐标。 |
| x2 | int | 第二个点的 x 坐标。 |
| y2 | int | 第二个点的 y 坐标。 |

### Method: draw_path(pen, path) {#draw_path_pen_path_9}


```
 draw_path(pen, path) 
```

绘制路径。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于绘制图形轮廓的笔。 |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 要绘制的路径。 |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_10}


```
 draw_rectangle(pen, x, y, width, height) 
```

绘制矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于绘制图形轮廓的笔。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| width | int | 要绘制的矩形的宽度。 |
| height | int | 要绘制的矩形的高度。 |

### Method: draw_string(font, text, origin, text_color) {#draw_string_font_text_origin_text_color_11}


```
 draw_string(font, text, origin, text_color) 
```

绘制文本字符串。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 用于呈现文本的字体。 |
| text | string | Unicode 文本字符串。 |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | 文本运行的左上角。 |
| text_color | [Color](/imaging/python-net/aspose.imaging/color/) | 文本颜色。 |

### Method: end_recording() {#end_recording__12}


```
 end_recording() 
```

获取最终的 Svg 图像，其中包括通过 [SvgGraphics2D](/imaging/python-net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/) 对象执行的所有绘图命令。

**Returns**

| Type | Description |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) | 最终的 Svg 图像。 |


### Method: fill_arc(pen, brush, rect, start_angle, arc_angle) {#fill_arc_pen_brush_rect_start_angle_arc_angle_13}


```
 fill_arc(pen, brush, rect, start_angle, arc_angle) 
```

填充由矩形结构指定的椭圆的一部分弧线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于绘制图形轮廓的笔。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 用于填充图形内部的画笔。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 椭圆的边界。 |
| start_angle | float | 从 x 轴顺时针测量到弧线起始点的角度（度）。 |
| arc_angle | float | 从 startAngle 参数顺时针测量到弧线结束点的角度（度）。 |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_14}


```
 fill_path(pen, brush, path) 
```

填充路径。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于绘制图形轮廓的笔。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 用于填充图形内部的画笔。 |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 要绘制的路径。 |

### Method: fill_rectangle(pen, brush, x, y, width, height) {#fill_rectangle_pen_brush_x_y_width_height_15}


```
 fill_rectangle(pen, brush, x, y, width, height) 
```

填充矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于绘制图形轮廓的笔。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 用于填充图形内部的画笔。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| width | int | 要绘制的矩形的宽度。 |
| height | int | 要绘制的矩形的高度。 |

## **Examples**
### This example shows how to create an SVG image of the specified size and rasterize it to PNG. {#example_171}
``` python
from aspose.imaging.fileformats.svg.graphics import SvgGraphics2D
from aspose.imaging import Graphics, Color, Pen
from aspose.imaging.brushes import SolidBrush
from os.path import join

dir_: str = "c:\\temp"
image_width: int = 100
image_height: int = 100
dpi: int = 96
# 创建一个 100x100 像素的 SVG 图像。
graphics = SvgGraphics2D(image_width, image_height, dpi)
pen = Pen(Color.yellow, 10)
brush = SolidBrush(Color.red)
# 将整幅图像填充为红色。
# 在图像边界上绘制一个宽度为 10 像素的黄色矩形。
graphics.fill_rectangle(pen, brush, 0, 0, image_width, image_height)
# 获取包含所有绘图命令的最终 Svg 图像
with graphics.end_recording() as svg_image:
	svg_image.save(join(dir_, "test.output.svg"))


```

