---
title: "Pen 类"
type: docs
weight: 6890
url: /zh/python-net/aspose.imaging/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | 使用指定的 [Pen.brush](/imaging/python-net/aspose.imaging/pen/) 初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。 |
| [Pen(brush, width)](#Pen_brush_width_2) | 使用指定的 [Pen.brush](/imaging/python-net/aspose.imaging/pen/) 和 [Pen.width](/imaging/python-net/aspose.imaging/pen/) 初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。 |
| [Pen(color)](#Pen_color_3) | 使用指定的颜色初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。 |
| [Pen(color, width)](#Pen_color_width_4) | 使用指定的 [Pen.color](/imaging/python-net/aspose.imaging/pen/) 和 [Pen.width](/imaging/python-net/aspose.imaging/pen/) 属性初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | r/w | 获取或设置此 [Pen](/imaging/python-net/aspose.imaging/pen/) 的对齐方式。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | r/w | 获取或设置 [Pen.brush](/imaging/python-net/aspose.imaging/pen/)，它决定此 [Pen](/imaging/python-net/aspose.imaging/pen/) 的属性。 |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置此 [Pen](/imaging/python-net/aspose.imaging/pen/) 的颜色。 |
| compound_array | float[] | r/w | 获取或设置指定复合笔的值数组。复合笔绘制由平行线段和间隔组成的复合线。 |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | 获取或设置在使用此 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制的线条末端使用的自定义帽。 |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | 获取或设置在使用此 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制的线条起始端使用的自定义帽。 |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | r/w | 获取或设置在使用此 [Pen](/imaging/python-net/aspose.imaging/pen/) 绘制的虚线末端的帽式样式。 |
| dash_offset | float | r/w | 获取或设置从线段起点到虚线模式起始位置的距离。 |
| dash_pattern | float[] | r/w | 获取或设置自定义虚线和空格的数组。 |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | r/w | 获取或设置使用此[Pen](/imaging/python-net/aspose.imaging/pen/)绘制的虚线的样式。 |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | 获取或设置使用此[Pen](/imaging/python-net/aspose.imaging/pen/)绘制的线段末端的端帽样式。 |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | 获取或设置使用此[Pen](/imaging/python-net/aspose.imaging/pen/)绘制的两条相邻线段端点的连接样式。 |
| miter_limit | float | r/w | 获取或设置斜接拐角处连接的厚度限制。 |
| opacity | float | r/w | 获取或设置对象的不透明度。该值应在 0 到 1 之间。0 表示对象完全可见，1 表示对象完全不透明。 |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype/) | r | 获取使用此[Pen](/imaging/python-net/aspose.imaging/pen/)绘制的线条样式。 |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | 获取或设置使用此[Pen](/imaging/python-net/aspose.imaging/pen/)绘制的线段起始端的端帽样式。 |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置此[Pen](/imaging/python-net/aspose.imaging/pen/)的几何变换的副本。 |
| width | float | r/w | 获取或设置此[Pen](/imaging/python-net/aspose.imaging/pen/)的宽度，单位为用于绘图的 Graphics 对象的单位。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_brush(brush)](#create_with_brush_brush_1) | 使用指定的 [Pen.brush](/imaging/python-net/aspose.imaging/pen/) 初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。 |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_2) | 使用指定的 [Pen.brush](/imaging/python-net/aspose.imaging/pen/) 和 [Pen.width](/imaging/python-net/aspose.imaging/pen/) 初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。 |
| [create_with_color(color)](#create_with_color_color_3) | 使用指定的颜色初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。 |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_4) | 使用指定的 [Pen.color](/imaging/python-net/aspose.imaging/pen/) 和 [Pen.width](/imaging/python-net/aspose.imaging/pen/) 属性初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_5) | 将此[Pen](/imaging/python-net/aspose.imaging/pen/)的变换矩阵乘以指定的[Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_6) | 按照指定顺序，将此[Pen](/imaging/python-net/aspose.imaging/pen/)的变换矩阵乘以指定的[Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| reset_transform() | 将此[Pen](/imaging/python-net/aspose.imaging/pen/)的几何变换矩阵重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_7) | 按指定角度旋转局部几何变换。此方法将在变换前添加旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_8) | 按指定顺序，以指定角度旋转局部几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_9) | 按指定因子缩放局部几何变换。此方法将在变换前添加缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_10) | 按指定顺序，以指定因子缩放局部几何变换。 |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_11) | 设置决定此[Pen](/imaging/python-net/aspose.imaging/pen/)绘制的线段结束端帽样式的值。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | 按指定尺寸平移局部几何变换。此方法将在变换前添加平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | 按指定顺序，以指定尺寸平移局部几何变换。 |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

使用指定的 [Pen.brush](/imaging/python-net/aspose.imaging/pen/) 初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 一个决定此[Pen](/imaging/python-net/aspose.imaging/pen/)填充属性的[Pen.brush](/imaging/python-net/aspose.imaging/pen/)。 |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

使用指定的 [Pen.brush](/imaging/python-net/aspose.imaging/pen/) 和 [Pen.width](/imaging/python-net/aspose.imaging/pen/) 初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 一个决定此[Pen](/imaging/python-net/aspose.imaging/pen/)特性的[Pen.brush](/imaging/python-net/aspose.imaging/pen/)。 |
| width | float | 新[Pen](/imaging/python-net/aspose.imaging/pen/)的宽度。 |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

使用指定的颜色初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 一个指示此[Pen](/imaging/python-net/aspose.imaging/pen/)颜色的[Pen.color](/imaging/python-net/aspose.imaging/pen/)结构。 |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

使用指定的 [Pen.color](/imaging/python-net/aspose.imaging/pen/) 和 [Pen.width](/imaging/python-net/aspose.imaging/pen/) 属性初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 一个指示此[Pen](/imaging/python-net/aspose.imaging/pen/)颜色的[Pen.color](/imaging/python-net/aspose.imaging/pen/)结构。 |
| width | float | 指示此 [Pen](/imaging/python-net/aspose.imaging/pen/) 宽度的值。 |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: create_with_brush(brush)  [static] {#create_with_brush_brush_1}


```
 create_with_brush(brush) 
```

使用指定的 [Pen.brush](/imaging/python-net/aspose.imaging/pen/) 初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 一个决定此[Pen](/imaging/python-net/aspose.imaging/pen/)填充属性的[Pen.brush](/imaging/python-net/aspose.imaging/pen/)。 |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_2}


```
 create_with_brush_width(brush, width) 
```

使用指定的 [Pen.brush](/imaging/python-net/aspose.imaging/pen/) 和 [Pen.width](/imaging/python-net/aspose.imaging/pen/) 初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 一个决定此[Pen](/imaging/python-net/aspose.imaging/pen/)特性的[Pen.brush](/imaging/python-net/aspose.imaging/pen/)。 |
| width | float | 新[Pen](/imaging/python-net/aspose.imaging/pen/)的宽度。 |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color(color)  [static] {#create_with_color_color_3}


```
 create_with_color(color) 
```

使用指定的颜色初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 一个指示此[Pen](/imaging/python-net/aspose.imaging/pen/)颜色的[Pen.color](/imaging/python-net/aspose.imaging/pen/)结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_4}


```
 create_with_color_width(color, width) 
```

使用指定的 [Pen.color](/imaging/python-net/aspose.imaging/pen/) 和 [Pen.width](/imaging/python-net/aspose.imaging/pen/) 属性初始化 [Pen](/imaging/python-net/aspose.imaging/pen/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 一个指示此[Pen](/imaging/python-net/aspose.imaging/pen/)颜色的[Pen.color](/imaging/python-net/aspose.imaging/pen/)结构。 |
| width | float | 指示此 [Pen](/imaging/python-net/aspose.imaging/pen/) 宽度的值。 |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_5}


```
 multiply_transform(matrix) 
```

将此[Pen](/imaging/python-net/aspose.imaging/pen/)的变换矩阵乘以指定的[Matrix](/imaging/python-net/aspose.imaging/matrix/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以变换矩阵的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 对象。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_6}


```
 multiply_transform(matrix, order) 
```

按照指定顺序，将此[Pen](/imaging/python-net/aspose.imaging/pen/)的变换矩阵乘以指定的[Matrix](/imaging/python-net/aspose.imaging/matrix/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以变换矩阵的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 执行乘法操作的顺序。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_7}


```
 rotate_transform(angle) 
```

按指定角度旋转局部几何变换。此方法将在变换前添加旋转。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_8}


```
 rotate_transform(angle, order) 
```

按指定顺序，以指定角度旋转局部几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定是追加还是预置旋转矩阵的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_9}


```
 scale_transform(sx, sy) 
```

按指定因子缩放局部几何变换。此方法将在变换前添加缩放矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的因子。 |
| sy | float | 在 y 轴方向上缩放变换的因子。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_10}


```
 scale_transform(sx, sy, order) 
```

按指定顺序，以指定因子缩放局部几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的因子。 |
| sy | float | 在 y 轴方向上缩放变换的因子。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 一个 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) 用于指定是追加还是预先追加缩放矩阵。 |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_11}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

设置决定此[Pen](/imaging/python-net/aspose.imaging/pen/)绘制的线段结束端帽样式的值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | 表示使用此 [Pen] 绘制的线段起始处的帽子样式的 [LineCap](/imaging/python-net/aspose.imaging/linecap/)。 |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | 表示使用此 [Pen] 绘制的线段末端的帽子样式的 [LineCap](/imaging/python-net/aspose.imaging/linecap/)。 |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | 表示使用此 [Pen] 绘制的虚线起始或结束处的帽子样式的 [LineCap](/imaging/python-net/aspose.imaging/linecap/)。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

按指定尺寸平移局部几何变换。此方法将在变换前添加平移。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

按指定顺序，以指定尺寸平移局部几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 应用平移的顺序（预先追加或追加）。 |

## **Examples**
### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# 创建 BmpOptions 实例并设置其各种属性。
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# 创建 FileCreateSource 的实例并将其分配为 BmpOptions 实例的 Source
# 第二个布尔参数决定要创建的文件是否为临时文件
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# 在指定路径创建 Image 实例。
with Image.create(bmpOptions, 500, 500) as image:
	# 创建 Graphics 实例并使用 Image 对象进行初始化。
	graphics = Graphics(image)
	# 使用白色清除 Graphics 表面。
	graphics.clear(Color.white)
	#创建颜色为红色、宽度为 5 的 Pen 实例。
	pen = Pen(Color.red, 5.0);
	# 创建 HatchBrush 实例并设置其属性。
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# 创建 Pen 实例。
	# 使用 HatchBrush 对象和宽度进行初始化
	brusedpen = Pen(brush, 5.0)
	# 通过指定 Pen 对象绘制矩形
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# 通过指定 Pen 对象绘制矩形
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# 保存所有更改。
	image.save()


```

