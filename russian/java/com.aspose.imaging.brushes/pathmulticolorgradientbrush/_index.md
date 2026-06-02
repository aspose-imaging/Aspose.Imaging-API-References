---
title: "PathMulticolorGradientBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Инкапсулирует объект Aspose.Imaging.Brush с градиентом."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.brushes/pathmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

Инкапсулирует объект `Aspose.Imaging.Brush` с градиентом. Этот класс нельзя наследовать.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) с указанными точками. |
| [PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) с указанными точками и режимом обтекания. |
| [PathMulticolorGradientBrush(Point[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) с указанными точками. |
| [PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) с указанными точками и режимом обтекания. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-) | Инициализирует новый экземпляр класса `PathMulticolorGradientBrush` с указанным путем. |
## Методы

| Метод | Описание |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Получает или задает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Получает или задает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент. |
### PathMulticolorGradientBrush(PointF[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---}
```
public PathMulticolorGradientBrush(PointF[] pathPoints)
```


Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив структур [PointF](../../com.aspose.imaging/pointf), представляющих точки, образующие вершины пути. |

### PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)
```


Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) с указанными точками и режимом обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив структур [PointF](../../com.aspose.imaging/pointf), представляющих точки, образующие вершины пути. |
| wrapMode | int | Объект [WrapMode](../../com.aspose.imaging/wrapmode), определяющий, как заполняемые этим [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) области будут чередоваться. |

### PathMulticolorGradientBrush(Point[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---}
```
public PathMulticolorGradientBrush(Point[] pathPoints)
```


Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | Массив структур [Point](../../com.aspose.imaging/point), представляющих точки, образующие вершины пути. |

### PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-}
```
public PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)
```


Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) с указанными точками и режимом обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | Массив структур [Point](../../com.aspose.imaging/point), представляющих точки, образующие вершины пути. |
| wrapMode | int | Объект [WrapMode](../../com.aspose.imaging/wrapmode), определяющий, как заполняемые этим [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) области будут чередоваться. |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


Инициализирует новый экземпляр класса `PathMulticolorGradientBrush` с указанным путем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `GraphicsPath`, определяющий область, заполненную этим `PathMulticolorGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Получает или задает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент.

Значение: `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Получает или задает `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент.

Значение: `com.aspose.imaging.ColorBlend`, определяющий многокрасочный линейный градиент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) |  |

