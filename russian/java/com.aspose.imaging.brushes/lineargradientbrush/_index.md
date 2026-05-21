---
title: "LinearGradientBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Инкапсулирует объект Aspose.Imaging.Brush с линейным градиентом."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Инкапсулирует `Aspose.Imaging.Brush` с линейным градиентом. Этот класс нельзя наследовать.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush()](#LinearGradientBrush--) | Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) с параметрами по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Возвращает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Устанавливает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент. |
| [getLinearColors()](#getLinearColors--) | Получает начальные и конечные цвета градиента. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | Устанавливает начальные и конечные цвета градиента. |
| [getStartColor()](#getStartColor--) | Получает начальный цвет градиента. |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | Устанавливает начальный цвет градиента. |
| [getEndColor()](#getEndColor--) | Получает конечный цвет градиента. |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | Устанавливает конечный цвет градиента. |
| [getBlend()](#getBlend--) | Получает `Aspose.Imaging.Blend`, который задает позиции и коэффициенты, определяющие пользовательское затухание градиента. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Устанавливает `Aspose.Imaging.Blend`, который задает позиции и коэффициенты, определяющие пользовательское затухание градиента. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Создаёт затухание градиента на основе колоколообразной кривой. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Создаёт затухание градиента на основе колоколообразной кривой. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Создаёт линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Создаёт линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах. |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник. |
| color1 | [Color](../../com.aspose.imaging/color) | Цвет1. |
| color2 | [Color](../../com.aspose.imaging/color) | Цвет2. |
| angle | float | Угол. |
| isAngleScalable | boolean | если установлено `true` [is angle scalable]. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |
| color1 | [Color](../../com.aspose.imaging/color) | Цвет1. |
| color2 | [Color](../../com.aspose.imaging/color) | Цвет2. |
| angle | float | Угол. |
| isAngleScalable | boolean | если установлено `true` [is angle scalable]. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник. |
| color1 | [Color](../../com.aspose.imaging/color) | Цвет1. |
| color2 | [Color](../../com.aspose.imaging/color) | Цвет2. |
| angle | float | Угол. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |
| color1 | [Color](../../com.aspose.imaging/color) | Цвет1. |
| color2 | [Color](../../com.aspose.imaging/color) | Цвет2. |
| angle | float | Угол. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Точка1. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Точка2. |
| color1 | [Color](../../com.aspose.imaging/color) | Цвет1. |
| color2 | [Color](../../com.aspose.imaging/color) | Цвет2. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Точка1. |
| point2 | [Point](../../com.aspose.imaging/point) | Точка2. |
| color1 | [Color](../../com.aspose.imaging/color) | Цвет1. |
| color2 | [Color](../../com.aspose.imaging/color) | Цвет2. |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Инициализирует новый экземпляр класса [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) с параметрами по умолчанию. Начальный цвет — черный, конечный цвет — белый, угол — 45 градусов и прямоугольник расположен в (0,0) размером (1,1).

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

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Получает начальные и конечные цвета градиента.

**Returns:**
com.aspose.imaging.Color[] - Массив из двух структур `Color`, представляющих начальные и конечные цвета градиента.
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


Устанавливает начальные и конечные цвета градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Массив из двух структур `Color`, представляющих начальные и конечные цвета градиента. |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Получает начальный цвет градиента.

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


Устанавливает начальный цвет градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Начальный цвет градиента. |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Получает конечный цвет градиента.

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


Устанавливает конечный цвет градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Конечный цвет градиента. |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Получает `Aspose.Imaging.Blend`, который задает позиции и коэффициенты, определяющие пользовательское затухание градиента.

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


Устанавливает `Aspose.Imaging.Blend`, который задает позиции и коэффициенты, определяющие пользовательское затухание градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | Объект `Aspose.Imaging.Blend`, представляющий пользовательское затухание градиента. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Создаёт затухание градиента на основе колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где начальный и конечный цвета смешиваются поровну). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Создаёт затухание градиента на основе колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| масштаб | float | Значение от 0 до 1, указывающее, как быстро цвета затухают от `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Создаёт линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Создаёт линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| масштаб | float | Значение от 0 до 1, указывающее, как быстро цвета затухают от начального цвета к `focus` (конечный цвет). |

