---
title: "PathGradientBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Инкапсулирует объект Aspose.Imaging.Brush с градиентом."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Инкапсулирует объект `Aspose.Imaging.Brush` с градиентом. Этот класс нельзя наследовать.

Цвет центра по умолчанию белый. Пользователь может изменить это значение в любой момент позже.

Массив окружающих цветов инициализируется одним элементом, содержащим белый цвет, по умолчанию. Окружающие цвета могут быть изменены позже, однако при настройке массива окружающих цветов требуется как минимум один элемент.

Смотрите `Blend` для получения более подробной информации об его инициализации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками и режимом обтекания. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками и режимом обтекания. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанным путем. |
## Методы

| Метод | Описание |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Возвращает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Устанавливает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент. |
| [getCenterColor()](#getCenterColor--) | Получает цвет в центре градиента пути. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | Устанавливает цвет в центре градиента пути. |
| [getSurroundColors()](#getSurroundColors--) | Получает массив цветов, соответствующих точкам в пути, который заполняет этот `PathGradientBrush`. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | Устанавливает массив цветов, соответствующих точкам в пути, который заполняет этот `PathGradientBrush`. |
| [getBlend()](#getBlend--) | Получает `Aspose.Imaging.Blend`, который задает позиции и коэффициенты, определяющие пользовательское затухание градиента. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Устанавливает `Aspose.Imaging.Blend`, который задает позиции и коэффициенты, определяющие пользовательское затухание градиента. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Создаёт кисть градиента, меняющую цвет, начиная от центра пути и распространяясь к границе пути. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Создаёт кисть градиента, меняющую цвет, начиная от центра пути и распространяясь к границе пути. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Создаёт градиент с центральным цветом и линейным спадом к одному окружающему цвету. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Создаёт градиент с центральным цветом и линейным спадом к каждому окружающему цвету. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив структур `Aspose.Imaging.PointF`, представляющих точки, образующие вершины пути. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками и режимом обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив структур `Aspose.Imaging.PointF`, представляющих точки, образующие вершины пути. |
| wrapMode | int | Тип `Aspose.Imaging.WrapMode`, который определяет, как заполнения, нарисованные этим `PathGradientBrush`, чередуются. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Массив структур `Aspose.Imaging.Point`, представляющих точки, образующие вершины пути. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками и режимом обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Массив структур `Aspose.Imaging.Point`, представляющих точки, образующие вершины пути. |
| wrapMode | int | Тип `Aspose.Imaging.WrapMode`, который определяет, как заполнения, нарисованные этим `PathGradientBrush`, чередуются. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Инициализирует новый экземпляр класса `PathGradientBrush` с указанным путем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `GraphicsPath`, определяющий область, заполняемую этим `PathGradientBrush`. |

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

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Получает цвет в центре градиента пути.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


Устанавливает цвет в центре градиента пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | `com.aspose.imaging.Color`, представляющий цвет в центре градиента пути. |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Получает массив цветов, соответствующих точкам в пути, который заполняет этот `PathGradientBrush`.

**Returns:**
com.aspose.imaging.Color[] — массив структур `com.aspose.imaging.Color`, представляющих цвета, связанные с каждой точкой в пути, который заполняет этот `PathGradientBrush`.
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


Устанавливает массив цветов, соответствующих точкам в пути, который заполняет этот `PathGradientBrush`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Массив структур `com.aspose.imaging.Color`, представляющих цвета, связанные с каждой точкой в пути, который заполняет этот `PathGradientBrush`. |

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


Создаёт кисть градиента, меняющую цвет, начиная от центра пути и распространяясь к границе пути. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиуса от центра пути к его границе центральный цвет будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Создаёт кисть градиента, меняющую цвет, начиная от центра пути и распространяясь к границе пути. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиуса от центра пути к его границе центральный цвет будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |
| масштаб | float | Значение от 0 до 1, определяющее максимальную интенсивность центрального цвета, смешиваемого с граничным цветом. Значение 1 приводит к максимально возможной интенсивности центрального цвета и является значением по умолчанию. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Создаёт градиент с центральным цветом и линейным спадом к одному окружающему цвету.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиуса от центра пути к его границе центральный цвет будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Создаёт градиент с центральным цветом и линейным спадом к каждому окружающему цвету.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиуса от центра пути к его границе центральный цвет будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |
| масштаб | float | Значение от 0 до 1, определяющее максимальную интенсивность центрального цвета, смешиваемого с граничным цветом. Значение 1 приводит к максимально возможной интенсивности центрального цвета и является значением по умолчанию. |

