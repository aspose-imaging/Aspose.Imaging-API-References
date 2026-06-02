---
title: "TransformBrush 类"
type: docs
weight: 100
url: /zh/python-net/aspose.imaging.brushes/transformbrush/
---

**Summary:** A [Brush](/imaging/python-net/aspose.imaging/brush/) with transform capabilities.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TransformBrush

**Inheritance:** Brush

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| is_transform_changed | bool | r | 获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或<br/>            调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| opacity | float | r/w | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。 |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 副本，用于定义此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的局部几何变换。 |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | 获取或设置一个指示此 [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 的包装模式的 [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) 枚举。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并在前面预置指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | 将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。 |
| reset_transform() | 将 [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) 属性重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_4) | 按指定量旋转本地几何变换。此方法将在变换前预置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | 按指定量并按指定顺序旋转本地几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | 按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | 按指定的比例并按指定顺序缩放本地几何变换。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | 按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | 按指定的尺寸并按指定顺序平移本地几何变换。 |


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

创建当前 [Brush](/imaging/python-net/aspose.imaging/brush/) 的新深度克隆。

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | 一个新的 [Brush](/imaging/python-net/aspose.imaging/brush/)，它是此 [Brush](/imaging/python-net/aspose.imaging/brush/) 实例的深度克隆。 |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 相乘，并在前面预置指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

将表示此 [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) 的本地几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 与指定的 [Matrix](/imaging/python-net/aspose.imaging/matrix/) 按指定顺序相乘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 用于乘以几何变换的 [Matrix](/imaging/python-net/aspose.imaging/matrix/)。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定两个矩阵相乘顺序的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

按指定量旋转本地几何变换。此方法将在变换前预置旋转。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

按指定量并按指定顺序旋转本地几何变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定是追加还是预置旋转矩阵的 [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

按指定的比例缩放本地几何变换。此方法将在变换前预置缩放矩阵。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

按指定的尺寸平移本地几何变换。此方法将在变换前预置平移。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


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

