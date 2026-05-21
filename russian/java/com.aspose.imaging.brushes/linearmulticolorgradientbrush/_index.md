---
title: "LinearMulticolorGradientBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет кисть с линейным градиентом, определённым несколькими цветами и соответствующими позициями."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.brushes/linearmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Представляет `Brush` с линейным градиентом, определённым несколькими цветами и соответствующими позициями. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` с параметрами по умолчанию. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` с указанными точками. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` с указанными точками. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-) | Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` на основе прямоугольника и угла ориентации. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-) | Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` на основе прямоугольника и угла ориентации. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-) | Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` на основе прямоугольника и угла ориентации. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-) | Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` на основе прямоугольника и угла ориентации. |
## Методы

| Метод | Описание |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Возвращает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Устанавливает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент. |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` с параметрами по умолчанию. Начальный цвет — черный, конечный цвет — белый, угол — 45 градусов, а прямоугольник расположен в (0,0) размером (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Структура `Aspose.Imaging.Point`, представляющая начальную точку линейного градиента. |
| point2 | [Point](../../com.aspose.imaging/point) | Структура `Aspose.Imaging.Point`, представляющая конечную точку линейного градиента. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Структура `Aspose.Imaging.PointF`, представляющая начальную точку линейного градиента. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Структура `Aspose.Imaging.PointF`, представляющая конечную точку линейного градиента. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` на основе прямоугольника и угла ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `Aspose.Imaging.RectangleF`, задающая границы линейного градиента. |
| angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X, линии ориентации градиента. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` на основе прямоугольника и угла ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `Aspose.Imaging.RectangleF`, задающая границы линейного градиента. |
| angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X, линии ориентации градиента. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` на основе прямоугольника и угла ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `Aspose.Imaging.RectangleF`, задающая границы линейного градиента. |
| angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X, линии ориентации градиента. |
| isAngleScalable | boolean | Если установить значение `true`, угол изменяется во время преобразований с этим `LinearMulticolorGradientBrush`. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Инициализирует новый экземпляр класса `LinearMulticolorGradientBrush` на основе прямоугольника и угла ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `Aspose.Imaging.RectangleF`, задающая границы линейного градиента. |
| angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X, линии ориентации градиента. |
| isAngleScalable | boolean | Если установить значение `true`, угол изменяется во время преобразований с этим `LinearMulticolorGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Возвращает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Устанавливает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | Объект `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент. |

