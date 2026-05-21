---
title: "LinearGradientBrushBase"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示具有渐变功能和相应属性的画刷。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

表示具有渐变功能和相应属性的 `Brush`。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRectangle()](#getRectangle--) | 获取定义渐变起始点和结束点的矩形区域。 |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | 设置定义渐变起始点和结束点的矩形区域。 |
| [getAngle()](#getAngle--) | 获取渐变角度。 |
| [setAngle(float value)](#setAngle-float-) | 设置渐变角度。 |
| [isAngleScalable()](#isAngleScalable--) | 获取一个值，指示在使用此 `LinearGradientBrushBase` 进行转换时是否更改 `LinearGradientBrushBase.Angle`。 |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | 设置一个值，指示在使用此 `LinearGradientBrushBase` 进行转换时是否更改 `LinearGradientBrushBase.Angle`。 |
| [getGammaCorrection()](#getGammaCorrection--) | 获取一个值，指示此 `LinearGradientBrushBase` 是否启用伽马校正。 |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | 设置一个值，指示此 `LinearGradientBrushBase` 是否启用伽马校正。 |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


获取定义渐变起始点和结束点的矩形区域。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


设置定义渐变起始点和结束点的矩形区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | 一个指定渐变起始点和结束点的 `com.aspose.imaging.RectangleF` 结构。 |

### getAngle() {#getAngle--}
```
public float getAngle()
```


获取渐变角度。

**Returns:**
float - 渐变角度。
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


设置渐变角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 渐变角度。 |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


获取一个值，指示在使用此 `LinearGradientBrushBase` 进行转换时是否更改 `LinearGradientBrushBase.Angle`。

**Returns:**
boolean - 如果在使用此 `LinearGradientBrushBase` 进行转换时更改了 `LinearGradientBrushBase.Angle` 则为 `true`；否则为 `false`。
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


设置一个值，指示在使用此 `LinearGradientBrushBase` 进行转换时是否更改 `LinearGradientBrushBase.Angle`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | `true` 如果在使用此 `LinearGradientBrushBase` 进行转换时更改了 `LinearGradientBrushBase.Angle`；否则为 `false`。 |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


获取一个值，指示此 `LinearGradientBrushBase` 是否启用伽马校正。

**Returns:**
boolean - 如果此 `LinearGradientBrushBase` 启用了伽马校正，则值为 true；否则为 false。
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


设置一个值，指示此 `LinearGradientBrushBase` 是否启用伽马校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 如果此 `LinearGradientBrushBase` 启用了伽马校正，则值为 true；否则为 false。 |

