---
title: "EmfRecorderGraphics2D 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---

**Summary:** The Emf recorder graphics

**Module:** [aspose.imaging.fileformats.emf.graphics](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/)

**Full Name:** aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D

**Inheritance:** MetafileRecorderGraphics2D

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfRecorderGraphics2D(frame, device_size, device_size_mm)](#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1) | 初始化一个新的 [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置背景颜色。 |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | 获取或设置背景模式。 |
| clip | [Region](/imaging/python-net/aspose.imaging/region/) | r/w | 获取或设置限制此 Graphics 绘图区域的 Region |
| clip_bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取剪辑边界。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| clear() | 清除 graphics 对象的状态。 |
| [draw_arc(pen, rect, start_angle, arc_angle)](#draw_arc_pen_rect_start_angle_arc_angle_1) | 绘制由 Rectangle 结构指定的椭圆的一部分弧。 |
| [draw_cubic_bezier(pen, pt1, pt2, pt3, pt4)](#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2) | 绘制三次贝塞尔曲线。 |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_3) | 绘制椭圆。 |
| [draw_image(image, dest_rect, src_rect, src_unit)](#draw_image_image_dest_rect_src_rect_src_unit_4) | 在指定位置以指定大小绘制指定 Image 的指定部分。 |
| [draw_image(image, location)](#draw_image_image_location_5) | 在指定位置绘制指定的 Image，使用其原始物理尺寸。 |
| [draw_image(image_bytes, dest_rect, src_unit)](#draw_image_image_bytes_dest_rect_src_unit_6) | 绘制图像。 |
| [draw_image(stream, dest_rect, src_unit)](#draw_image_stream_dest_rect_src_unit_7) | 绘制图像。 |
| [draw_image_from_bytes(image_bytes, dest_rect, src_unit)](#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8) | 绘制图像。 |
| [draw_image_from_stream(stream, dest_rect, src_unit)](#draw_image_from_stream_stream_dest_rect_src_unit_9) | 绘制图像。 |
| [draw_line(pen, pt1, pt2)](#draw_line_pen_pt1_pt2_10) | 绘制直线。 |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_11) | 绘制直线。 |
| [draw_path(pen, path)](#draw_path_pen_path_12) | 绘制路径。 |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_13) | 绘制饼形图。 |
| [draw_poly_cubic_bezier(pen, points)](#draw_poly_cubic_bezier_pen_points_14) | 绘制多段三次贝塞尔曲线。 |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_15) | 绘制多边形。 |
| [draw_polyline(pen, points)](#draw_polyline_pen_points_16) | 绘制折线。 |
| [draw_rectangle(pen, rectangle)](#draw_rectangle_pen_rectangle_17) | 绘制矩形。 |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_18) | 绘制矩形。 |
| [draw_string(string, font, color, x, y)](#draw_string_string_font_color_x_y_19) | 绘制字符串。 |
| [draw_string(string, font, color, x, y, angle)](#draw_string_string_font_color_x_y_angle_20) | 绘制字符串。 |
| [end_recording()](#end_recording__21) | 结束录制。 |
| [exclude_clip(rect)](#exclude_clip_rect_22) | 更新此 Graphics 的裁剪区域，以排除由 Rectangle 结构指定的区域。 |
| [exclude_clip(region)](#exclude_clip_region_23) | 更新此 Graphics 的裁剪区域，以排除由 Region 指定的区域。 |
| [exclude_clip_rect(rect)](#exclude_clip_rect_rect_24) | 更新此 Graphics 的裁剪区域，以排除由 Rectangle 结构指定的区域。 |
| [exclude_clip_rgn(region)](#exclude_clip_rgn_region_25) | 更新此 Graphics 的裁剪区域，以排除由 Region 指定的区域。 |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_26) | 填充椭圆。 |
| [fill_path(pen, brush, path)](#fill_path_pen_brush_path_27) | 填充路径。 |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_28) | 填充饼形图。 |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_29) | 填充多边形。 |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_30) | 填充多边形。 |
| [fill_rectangle(brush, rectangle)](#fill_rectangle_brush_rectangle_31) | 填充矩形。 |
| [from_emf_image(emf_image)](#from_emf_image_emf_image_32) | 获取一个 [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) 实例，其中包含来自 Emf 图像的所有记录。 |
| [get_transform()](#get_transform__33) | 获取世界变换。 |
| [intersect_clip(rect)](#intersect_clip_rect_34) | 更新此 Graphics 的裁剪区域，使其为当前裁剪区域与指定 Rectangle 结构的交集。 |
| [intersect_clip(region)](#intersect_clip_region_35) | 更新此 Graphics 的裁剪区域，使其为当前裁剪区域与指定 Region 的交集。 |
| [intersect_clip_rect_f(rect)](#intersect_clip_rect_f_rect_36) | 更新此 Graphics 的裁剪区域，使其为当前裁剪区域与指定 Rectangle 结构的交集。 |
| [intersect_clip_rgn(region)](#intersect_clip_rgn_region_37) | 更新此 Graphics 的裁剪区域，使其为当前裁剪区域与指定 Region 的交集。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_38) | 将此 Graphics 的世界变换与指定的 Matrix 相乘。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_39) | 按指定顺序将此 Graphics 的世界变换与指定的 Matrix 相乘。 |
| reset_clip() | 重置剪裁。 |
| [rotate_transform(angle)](#rotate_transform_angle_40) | 将指定的旋转应用于此 Graphics 的变换矩阵。 |
| [rotate_transform(angle, center, order)](#rotate_transform_angle_center_order_41) | 按指定顺序将指定的旋转应用于此 Graphics 的变换矩阵。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_42) | 通过将指定的缩放操作预先添加到对象的变换矩阵中，将其应用于此 Graphics 的变换矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_43) | 按指定顺序将指定的缩放操作应用于此 Graphics 的变换矩阵。 |
| [set_transform(transform)](#set_transform_transform_44) | 设置变换。 |
| [translate_transform(x, y)](#translate_transform_x_y_45) | 通过将指定的平移预先添加到此 Graphics 的变换矩阵中，改变坐标系的原点。 |
| [translate_transform(x, y, order)](#translate_transform_x_y_order_46) | 按指定顺序将指定的平移应用于此 Graphics 的变换矩阵，改变坐标系的原点。 |


### Constructor: EmfRecorderGraphics2D(frame, device_size, device_size_mm) {#EmfRecorderGraphics2D_frame_device_size_device_size_mm_1}


```
 EmfRecorderGraphics2D(frame, device_size, device_size_mm) 
```

初始化一个新的 [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 帧。 |
| device_size | [Size](/imaging/python-net/aspose.imaging/size/) | 设备的尺寸。 |
| device_size_mm | [Size](/imaging/python-net/aspose.imaging/size/) | 设备尺寸（毫米）。 |


**See also:**

**[Example # 1](#example_174)**: This example shows how to create a EMF image and draw some geometric shapes o...


### Method: draw_arc(pen, rect, start_angle, arc_angle) {#draw_arc_pen_rect_start_angle_arc_angle_1}


```
 draw_arc(pen, rect, start_angle, arc_angle) 
```

绘制由 Rectangle 结构指定的椭圆的一部分弧。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 椭圆的边界。 |
| start_angle | float | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| arc_angle | float | 以度为单位的角度，顺时针测量，从 startAngle 参数到弧线的结束点。 |

### Method: draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) {#draw_cubic_bezier_pen_pt1_pt2_pt3_pt4_2}


```
 draw_cubic_bezier(pen, pt1, pt2, pt3, pt4) 
```

绘制三次贝塞尔曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | 曲线的起始点。 |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | 曲线的第一个控制点。 |
| pt3 | [Point](/imaging/python-net/aspose.imaging/point/) | 曲线的第二个控制点。 |
| pt4 | [Point](/imaging/python-net/aspose.imaging/point/) | 曲线的结束点。 |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_3}


```
 draw_ellipse(pen, rect) 
```

绘制椭圆。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 椭圆的边界。 |

### Method: draw_image(image, dest_rect, src_rect, src_unit) {#draw_image_image_dest_rect_src_rect_src_unit_4}


```
 draw_image(image, dest_rect, src_rect, src_unit) 
```

在指定位置以指定大小绘制指定 Image 的指定部分。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 要绘制的图像。 |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定绘制图像位置和大小的矩形结构。图像会按比例缩放以适应矩形。 |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定要绘制的图像对象部分的矩形结构。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | srcRect 参数使用的计量单位。 |

### Method: draw_image(image, location) {#draw_image_image_location_5}


```
 draw_image(image, location) 
```

在指定位置绘制指定的 Image，使用其原始物理尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 要绘制的图像。 |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | 绘制图像左上角的位置。 |

### Method: draw_image(image_bytes, dest_rect, src_unit) {#draw_image_image_bytes_dest_rect_src_unit_6}


```
 draw_image(image_bytes, dest_rect, src_unit) 
```

绘制图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_bytes | System.Byte | 图像字节。 |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 源单位。 |

### Method: draw_image(stream, dest_rect, src_unit) {#draw_image_stream_dest_rect_src_unit_7}


```
 draw_image(stream, dest_rect, src_unit) 
```

绘制图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 源单位。 |

### Method: draw_image_from_bytes(image_bytes, dest_rect, src_unit) {#draw_image_from_bytes_image_bytes_dest_rect_src_unit_8}


```
 draw_image_from_bytes(image_bytes, dest_rect, src_unit) 
```

绘制图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_bytes | System.Byte | 图像字节。 |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 源单位。 |

### Method: draw_image_from_stream(stream, dest_rect, src_unit) {#draw_image_from_stream_stream_dest_rect_src_unit_9}


```
 draw_image_from_stream(stream, dest_rect, src_unit) 
```

绘制图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标矩形。 |
| src_unit | [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 源单位。 |

### Method: draw_line(pen, pt1, pt2) {#draw_line_pen_pt1_pt2_10}


```
 draw_line(pen, pt1, pt2) 
```

绘制直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| pt1 | [Point](/imaging/python-net/aspose.imaging/point/) | 第一个点。 |
| pt2 | [Point](/imaging/python-net/aspose.imaging/point/) | 第二个点。 |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_11}


```
 draw_line(pen, x1, y1, x2, y2) 
```

绘制直线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| x1 | int | 第一个点的 x 坐标。 |
| y1 | int | 第一个点的 y 坐标。 |
| x2 | int | 第二个点的 x 坐标。 |
| y2 | int | 第二个点的 y 坐标。 |

### Method: draw_path(pen, path) {#draw_path_pen_path_12}


```
 draw_path(pen, path) 
```

绘制路径。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 要绘制的路径。 |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_13}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

绘制饼形图。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 椭圆的边界。 |
| start_angle | float | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | float | 以度为单位的角度，顺时针测量，从 startAngle 参数到弧线的结束点。 |

### Method: draw_poly_cubic_bezier(pen, points) {#draw_poly_cubic_bezier_pen_points_14}


```
 draw_poly_cubic_bezier(pen, points) 
```

绘制多段三次贝塞尔曲线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 该 点。 |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_15}


```
 draw_polygon(pen, points) 
```

绘制多边形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 该 点。 |

### Method: draw_polyline(pen, points) {#draw_polyline_pen_points_16}


```
 draw_polyline(pen, points) 
```

绘制折线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 该 点。 |

### Method: draw_rectangle(pen, rectangle) {#draw_rectangle_pen_rectangle_17}


```
 draw_rectangle(pen, rectangle) 
```

绘制矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要绘制的矩形。 |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_18}


```
 draw_rectangle(pen, x, y, width, height) 
```

绘制矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| width | int | 要绘制的矩形的宽度。 |
| height | int | 要绘制的矩形的高度。 |

### Method: draw_string(string, font, color, x, y) {#draw_string_string_font_color_x_y_19}


```
 draw_string(string, font, color, x, y) 
```

绘制字符串。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| string | string | 字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的字体。 |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 文本颜色。 |
| x | int | 绘制文本左上角的 x 坐标。 |
| y | int | 绘制文本左上角的 y 坐标。 |

### Method: draw_string(string, font, color, x, y, angle) {#draw_string_string_font_color_x_y_angle_20}


```
 draw_string(string, font, color, x, y, angle) 
```

绘制字符串。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| string | string | 字符串。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 定义字符串文本格式的字体。 |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 文本颜色。 |
| x | int | 绘制文本左上角的 x 坐标。 |
| y | int | 绘制文本左上角的 y 坐标。 |
| 角度 | float | 角度（以度为单位），介于设备的倾斜向量和 x 轴之间。 <br/>            倾斜向量与一行文本的基线平行。 |

### Method: end_recording() {#end_recording__21}


```
 end_recording() 
```

结束录制。

**Returns**

| Type | Description |
| :- | :- |
| [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | 结果图像。 |


### Method: exclude_clip(rect) {#exclude_clip_rect_22}


```
 exclude_clip(rect) 
```

更新此 Graphics 的裁剪区域，以排除由 Rectangle 结构指定的区域。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定要从剪裁区域排除的矩形的矩形结构。 |

### Method: exclude_clip(region) {#exclude_clip_region_23}


```
 exclude_clip(region) 
```

更新此 Graphics 的裁剪区域，以排除由 Region 指定的区域。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 指定要从剪裁区域排除的区域。 |

### Method: exclude_clip_rect(rect) {#exclude_clip_rect_rect_24}


```
 exclude_clip_rect(rect) 
```

更新此 Graphics 的裁剪区域，以排除由 Rectangle 结构指定的区域。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定要从剪裁区域排除的矩形的矩形结构。 |

### Method: exclude_clip_rgn(region) {#exclude_clip_rgn_region_25}


```
 exclude_clip_rgn(region) 
```

更新此 Graphics 的裁剪区域，以排除由 Region 指定的区域。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 指定要从剪裁区域排除的区域。 |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_26}


```
 fill_ellipse(brush, rect) 
```

填充椭圆。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的画刷。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 椭圆的边界。 |

### Method: fill_path(pen, brush, path) {#fill_path_pen_brush_path_27}


```
 fill_path(pen, brush, path) 
```

填充路径。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 确定图形颜色、宽度和样式的笔。 |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的画刷。 |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 要填充的路径。 |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_28}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

填充饼形图。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的画刷。 |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 椭圆的边界。 |
| start_angle | float | 角度（度），从 x 轴顺时针测量到弧线起始点。 |
| sweep_angle | float | 以度为单位的角度，顺时针测量，从 startAngle 参数到弧线的结束点。 |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_29}


```
 fill_polygon(brush, points) 
```

填充多边形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的画刷。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 该 点。 |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_30}


```
 fill_polygon(brush, points, fill_mode) 
```

填充多边形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的画刷。 |
| points | [Point[]](/imaging/python-net/aspose.imaging/point/) | 该 点。 |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 填充模式。 |

### Method: fill_rectangle(brush, rectangle) {#fill_rectangle_brush_rectangle_31}


```
 fill_rectangle(brush, rectangle) 
```

填充矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | 确定填充特性的画刷。 |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 要填充的矩形。 |

### Method: from_emf_image(emf_image)  [static] {#from_emf_image_emf_image_32}


```
 from_emf_image(emf_image) 
```

获取一个 [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) 实例，其中包含来自 Emf 图像的所有记录。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| emf_image | [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) | 用于读取记录的 Emf 图像。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) | 一个 [EmfRecorderGraphics2D](/imaging/python-net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/) 实例 |


### Method: get_transform() {#get_transform__33}


```
 get_transform() 
```

获取世界变换。

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 变换矩阵。 |


### Method: intersect_clip(rect) {#intersect_clip_rect_34}


```
 intersect_clip(rect) 
```

更新此 Graphics 的裁剪区域，使其为当前裁剪区域与指定 Rectangle 结构的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 与当前剪裁区域相交的矩形结构。 |

### Method: intersect_clip(region) {#intersect_clip_region_35}


```
 intersect_clip(region) 
```

更新此 Graphics 的裁剪区域，使其为当前裁剪区域与指定 Region 的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 与当前区域相交的区域。 |

### Method: intersect_clip_rect_f(rect) {#intersect_clip_rect_f_rect_36}


```
 intersect_clip_rect_f(rect) 
```

更新此 Graphics 的裁剪区域，使其为当前裁剪区域与指定 Rectangle 结构的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 与当前剪裁区域相交的矩形结构。 |

### Method: intersect_clip_rgn(region) {#intersect_clip_rgn_region_37}


```
 intersect_clip_rgn(region) 
```

更新此 Graphics 的裁剪区域，使其为当前裁剪区域与指定 Region 的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | 与当前区域相交的区域。 |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_38}


```
 multiply_transform(matrix) 
```

将此 Graphics 的世界变换与指定的 Matrix 相乘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以世界变换的矩阵。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_39}


```
 multiply_transform(matrix, order) 
```

按指定顺序将此 Graphics 的世界变换与指定的 Matrix 相乘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以世界变换的矩阵。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 乘法的顺序。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_40}


```
 rotate_transform(angle) 
```

将指定的旋转应用于此 Graphics 的变换矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。 |

### Method: rotate_transform(angle, center, order) {#rotate_transform_angle_center_order_41}


```
 rotate_transform(angle, center, order) 
```

按指定顺序将指定的旋转应用于此 Graphics 的变换矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。 |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | 旋转中心。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定旋转是附加到矩阵变换的前面还是后面.. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_42}


```
 scale_transform(sx, sy) 
```

通过将指定的缩放操作预先添加到对象的变换矩阵中，将其应用于此 Graphics 的变换矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | X 方向的缩放因子。 |
| sy | float | Y 方向的缩放因子。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_43}


```
 scale_transform(sx, sy, order) 
```

按指定顺序将指定的缩放操作应用于此 Graphics 的变换矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | X 方向的缩放因子。 |
| sy | float | Y 方向的缩放因子。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定缩放操作是预先还是后附加到变换矩阵。 |

### Method: set_transform(transform) {#set_transform_transform_44}


```
 set_transform(transform) 
```

设置变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 新的变换矩阵。 |

### Method: translate_transform(x, y) {#translate_transform_x_y_45}


```
 translate_transform(x, y) 
```

通过将指定的平移预先添加到此 Graphics 的变换矩阵中，改变坐标系的原点。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 平移的 X 坐标。 |
| y | float | 平移的 Y 坐标。 |

### Method: translate_transform(x, y, order) {#translate_transform_x_y_order_46}


```
 translate_transform(x, y, order) 
```

按指定顺序将指定的平移应用于此 Graphics 的变换矩阵，改变坐标系的原点。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | float | 平移的 X 坐标。 |
| y | float | 平移的 Y 坐标。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定平移是预先还是后附加到变换矩阵。 |

## **Examples**
### This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D. {#example_174}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Rectangle, Pen, Color, Point, Image, RasterImage, GraphicsUnit, Font, FontStyle, Figure, GraphicsPath,\
	PointF, RectangleF, Size
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.shapes import ArcShape, BezierShape, PolygonShape, RectangleShape
from aspose.imaging.imageoptions import SvgRasterizationOptions, PngOptions
from aspose.imaging.fileformats.emf.graphics import EmfRecorderGraphics2D
from os.path import join

dir_: str = "c:\\temp"
# 图像像素尺寸
device_width: int = 600
device_height: int = 400
# 图像毫米尺寸
device_width_mm = device_width // 100
device_height_mm = device_height // 100
frame = Rectangle(0, 0, device_width, device_height)
# 创建一个 EMF 图像。
graphics = EmfRecorderGraphics2D(frame, Size(device_width, device_height), Size(device_width_mm, device_height_mm))
# 使用 1 像素宽的黑色笔在图像边缘绘制一个黑色矩形。
graphics.draw_rectangle(Pen(Color.black, 1), 0, 0, device_width, device_height)
# 使用白烟色填充矩形。
graphics.fill_rectangle(SolidBrush(Color.white_smoke), Rectangle(10, 10, 580, 380))
# 使用 1 像素宽的深绿色笔绘制两条对角线。
graphics.draw_line(Pen(Color.dark_green, 1), 0, 0, device_width, device_height)
graphics.draw_line(Pen(Color.dark_green, 1), 0, device_height, device_width, 0)
# 使用 2 像素宽的蓝色笔在矩形 {0, 0, 200, 200} 内绘制弧线。
graphics.draw_arc(Pen(Color.blue, 2), Rectangle(0, 0, 200, 200), 90, 270)
# 填充弧线
graphics.fill_pie(SolidBrush(Color.light_sky_blue), Rectangle(0, 0, 150, 150), 90, 270)
# 使用 2 像素宽的红色笔绘制三次贝塞尔曲线。
graphics.draw_cubic_bezier(Pen(Color.red, 2), Point(0, 0), Point(200, 133), Point(400, 166), Point(600, 400))

# 在指定位置绘制指定大小的光栅图像。
# 图像已缩放以适应所需的矩形。
with aspycore.as_of(Image.load(join(dir_, "sample.bmp")), RasterImage) as image_to_draw:
	graphics.draw_image(image_to_draw, Rectangle(400, 200, 100, 50), Rectangle(0, 0, device_width, device_height), GraphicsUnit.PIXEL)

# 绘制文本字符串
graphics.draw_string("Hello World!", Font("Arial", 48, FontStyle.REGULAR), Color.dark_red, 200, 300)

# 创建用于填充的路径
figure_to_fill = Figure()
figure_to_fill.is_closed = True
path_to_fill = GraphicsPath()
path_to_fill.add_figure(figure_to_fill)
figure_to_fill.add_shapes([ArcShape(Rectangle(400, 0, 200, 100), 45, 300), BezierShape([PointF(300, 200), PointF(400, 200), PointF(500, 100), PointF(600, 200)]), PolygonShape([PointF(300, 100)]), RectangleShape(RectangleF(0, 100, 200, 200))])

# 使用黄色画刷和绿色笔绘制轮廓来填充路径
graphics.fill_path(Pen(Color.green, 2), SolidBrushColor.yellow), path_to_fill)

# 创建用于绘制的路径
path_to_draw = GraphicsPath()
figure_to_draw = Figure()
path_to_draw.add_figure(figure_to_draw)
figure_to_draw.add_shapes([ArcShape(RectangleF(200, 200, 200, 200), 0, 360)])

# 使用 5 像素宽的橙色笔绘制路径。
graphics.draw_path(Pen(Color.orange, 5), path_to_draw)

# 获取包含所有绘图命令的最终 WMF 图像
with graphics.end_recording() as emf_image:
	emf_image.save(join(dir_, "test.output.emf"))


```

