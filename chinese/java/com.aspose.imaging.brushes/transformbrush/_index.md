---
title: "TransformBrush"
second_title: "Aspose.Imaging for Java API 参考"
description: "具有变换功能的 Brush。"
type: docs
weight: 19
url: /zh/java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

具有变换功能的 `Brush`。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | 获取或设置一个 `Aspose.Imaging.WrapMode` 枚举，指示此 `TransformBrush` 的包装模式。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置一个 `Aspose.Imaging.WrapMode` 枚举，指示此 `TransformBrush` 的包装模式。 |
| [getTransform()](#getTransform--) | 获取或设置一个副本 `Aspose.Imaging.Matrix`，该矩阵定义此 `TransformBrush` 的局部几何变换。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | 获取或设置一个副本 `Aspose.Imaging.Matrix`，该矩阵定义此 `TransformBrush` 的局部几何变换。 |
| [isTransformChanged()](#isTransformChanged--) | 获取一个值，指示变换是否以某种方式被更改。 |
| [resetTransform()](#resetTransform--) | 将 `TransformBrush.Transform` 属性重置为单位矩阵。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | 将表示此 `LinearGradientBrush` 的局部几何变换的 `Aspose.Imaging.Matrix` 与指定的 `Aspose.Imaging.Matrix` 相乘，方式是预先添加指定的 `Aspose.Imaging.Matrix`。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | 将表示此 `LinearGradientBrush` 的局部几何变换的 `Aspose.Imaging.Matrix` 与指定的 `Aspose.Imaging.Matrix` 相乘，按照指定的顺序。 |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定的尺寸平移局部几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 按指定的尺寸并按照指定的顺序平移局部几何变换。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 按指定的量缩放局部几何变换。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按指定的量并按照指定的顺序缩放局部几何变换。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 按指定的量旋转局部几何变换。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 按指定的量并按照指定的顺序旋转局部几何变换。 |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取或设置一个 `Aspose.Imaging.WrapMode` 枚举，指示此 `TransformBrush` 的包装模式。

**Returns:**
int - 一个 `Aspose.Imaging.WrapMode`，指定使用此 `TransformBrush` 绘制的填充如何平铺。
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


获取或设置一个 `Aspose.Imaging.WrapMode` 枚举，指示此 `TransformBrush` 的包装模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


获取或设置一个副本 `Aspose.Imaging.Matrix`，该矩阵定义此 `TransformBrush` 的局部几何变换。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


获取或设置一个副本 `Aspose.Imaging.Matrix`，该矩阵定义此 `TransformBrush` 的局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


获取一个值，指示变换是否以某种方式被更改。例如设置变换矩阵或调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 而引入。

值：如果变换已更改则为 `True`；否则为 `false`。

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


将 `TransformBrush.Transform` 属性重置为单位矩阵。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


将表示此 `LinearGradientBrush` 的局部几何变换的 `Aspose.Imaging.Matrix` 与指定的 `Aspose.Imaging.Matrix` 相乘，方式是预先添加指定的 `Aspose.Imaging.Matrix`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 用于乘以几何变换的 `Aspose.Imaging.Matrix`。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


将表示此 `LinearGradientBrush` 的局部几何变换的 `Aspose.Imaging.Matrix` 与指定的 `Aspose.Imaging.Matrix` 相乘，按照指定的顺序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 用于乘以几何变换的 `Aspose.Imaging.Matrix`。 |
| order | int | 一个 `Aspose.Imaging.MatrixOrder`，指定两个矩阵相乘的顺序。 |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


按指定的尺寸平移局部几何变换。此方法将在变换前预先添加平移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


按指定的尺寸并按照指定的顺序平移局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | int | 应用平移的顺序（预先或后置）。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


按指定的量缩放局部几何变换。此方法将在变换前预先添加缩放矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


按指定的量并按照指定的顺序缩放局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |
| order | int | 一个 `Aspose.Imaging.MatrixOrder`，指定是追加还是预先添加缩放矩阵。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


按指定的量旋转局部几何变换。此方法将在变换前预先添加旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


按指定的量并按照指定的顺序旋转局部几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |
| order | int | 一个 `Aspose.Imaging.MatrixOrder`，指定是追加还是预先添加旋转矩阵。 |

