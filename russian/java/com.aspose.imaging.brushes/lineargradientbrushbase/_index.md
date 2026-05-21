---
title: "LinearGradientBrushBase"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет кисть с возможностями градиента и соответствующими свойствами."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.brushes/lineargradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Представляет `Brush` с возможностями градиента и соответствующими свойствами.
## Методы

| Метод | Описание |
| --- | --- |
| [getRectangle()](#getRectangle--) | Возвращает прямоугольную область, определяющую начальные и конечные точки градиента. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.imaging.RectangleF-) | Устанавливает прямоугольную область, определяющую начальные и конечные точки градиента. |
| [getAngle()](#getAngle--) | Возвращает угол градиента. |
| [setAngle(float value)](#setAngle-float-) | Устанавливает угол градиента. |
| [isAngleScalable()](#isAngleScalable--) | Возвращает значение, указывающее, изменяется ли `LinearGradientBrushBase.Angle` при трансформациях с этим `LinearGradientBrushBase`. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Устанавливает значение, указывающее, изменяется ли `LinearGradientBrushBase.Angle` при трансформациях с этим `LinearGradientBrushBase`. |
| [getGammaCorrection()](#getGammaCorrection--) | Возвращает значение, указывающее, включена ли коррекция гаммы для этого `LinearGradientBrushBase`. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Устанавливает значение, указывающее, включена ли коррекция гаммы для этого `LinearGradientBrushBase`. |
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Возвращает прямоугольную область, определяющую начальные и конечные точки градиента.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A `com.aspose.imaging.RectangleF` structure that specifies the starting and ending points of the gradient.
### setRectangle(RectangleF value) {#setRectangle-com.aspose.imaging.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Устанавливает прямоугольную область, определяющую начальные и конечные точки градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF`, определяющая начальные и конечные точки градиента. |

### getAngle() {#getAngle--}
```
public float getAngle()
```


Возвращает угол градиента.

**Returns:**
float — угол градиента.
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Устанавливает угол градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Угол градиента. |

### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Возвращает значение, указывающее, изменяется ли `LinearGradientBrushBase.Angle` при трансформациях с этим `LinearGradientBrushBase`.

**Returns:**
boolean — `true`, если `LinearGradientBrushBase.Angle` изменяется при трансформациях с этим `LinearGradientBrushBase`; иначе `false`.
### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Устанавливает значение, указывающее, изменяется ли `LinearGradientBrushBase.Angle` при трансформациях с этим `LinearGradientBrushBase`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если `LinearGradientBrushBase.Angle` изменяется при трансформациях с этим `LinearGradientBrushBase`; иначе `false`. |

### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Возвращает значение, указывающее, включена ли коррекция гаммы для этого `LinearGradientBrushBase`.

**Returns:**
boolean — значение `true`, если коррекция гаммы включена для этого `LinearGradientBrushBase`; иначе `false`.
### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Устанавливает значение, указывающее, включена ли коррекция гаммы для этого `LinearGradientBrushBase`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | Значение `true`, если коррекция гаммы включена для этого `LinearGradientBrushBase`; иначе `false`. |

