---
title: "TextureBrush 类"
type: docs
weight: 90
url: /zh/python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | 使用指定的图像初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | 使用指定的图像和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | 使用指定的图像和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | 使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | 使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | 使用指定的图像和包装模式初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | 使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | 使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | 获取与此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象关联的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | 获取与此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 关联的 [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/)。 |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取与此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 关联的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/)。 |
| is_transform_changed | bool | r | 获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或<br/>            调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| opacity | float | r/w | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。 |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 副本，用于定义此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的局部几何变换。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | 获取或设置一个指示此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的包装模式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | 使用指定的图像和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | 使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | 使用指定的图像和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | 使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | 使用指定的图像和包装模式初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | 使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | 使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。 |
| [deep_clone()](#deep_clone__8) | 创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并在前面预置指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。 |
| reset_transform() | 将 [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 属性重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_11) | 按指定量旋转本地几何变换。此方法将在变换前预置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | 按指定量并按指定顺序旋转本地几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | 按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | 按指定的比例并按指定顺序缩放本地几何变换。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | 按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | 按指定的尺寸并按指定顺序平移本地几何变换。 |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

使用指定的图像初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

使用指定的图像和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

使用指定的图像和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 包含关于此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象使用的图像的附加信息的 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象。 |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 包含关于此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象使用的图像的附加信息的 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象。 |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

使用指定的图像和包装模式初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 指定此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象平铺方式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 指定此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象平铺方式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 指定此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象平铺方式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

使用指定的图像和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) 结构。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 包含关于此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象使用的图像的附加信息的 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象。 |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

使用指定的图像和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 包含关于此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象使用的图像的附加信息的 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象。 |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

使用指定的图像和包装模式初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 指定此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象平铺方式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 指定此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象平铺方式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象用于填充内部的 [Image](/imaging/python-net/aspose.imaging/image/) 对象。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 指定此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象平铺方式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 表示此 [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) 结构。 |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | 一个新的 [Brush](/imaging/python-net/aspose.imaging/brush/)，它是此 [Brush](/imaging/python-net/aspose.imaging/brush/) 实例的深度克隆。 |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并在前面预置指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定两个矩阵相乘顺序的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

按指定量旋转本地几何变换。此方法将在变换前预置旋转。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

按指定量并按指定顺序旋转本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定是追加还是预置旋转矩阵的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


```
 scale_transform(sx, sy, order) 
```

按指定的比例并按指定顺序缩放本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 一个 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) 用于指定是追加还是预先追加缩放矩阵。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


```
 translate_transform(dx, dy, order) 
```

按指定的尺寸并按指定顺序平移本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 应用平移的顺序（预先追加或追加）。 |

