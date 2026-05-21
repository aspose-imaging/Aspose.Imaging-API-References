---
title: "PathGradientBrushBase"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет кисть с базовой функциональностью градиента по пути."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

Представляет `Brush` с функциональностью градиента базового пути.

Обратите внимание, что при создании класса `PathGradientBrushBase` его следует инициализировать как минимум двумя точками. Внутренний путь всегда будет замкнутой фигурой, последняя точка соединяется с первой. Эта форма заполняется этим `PathGradientBrushBase`. Реализация GDI+ генерирует `OutOfMemoryError`, когда передаются пустые массивы или набор точек с одинаковыми координатами. `PathGradientBrushBase` бросает исключение, если массив точек содержит менее 2 точек; в этом случае генерируется `ArgumentException`, а не `OutOfMemoryError`, когда массив точек недопустим. Центр точки рассчитывается как центр масс переданных точек по умолчанию. Пользователь может изменить эту точку позже. Масштаб фокуса — пустая точка (0.0, 0.0) по умолчанию.
## Методы

| Метод | Описание |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | Возвращает точки пути, на котором построена эта кисть. |
| [getGraphicsPath()](#getGraphicsPath--) | Возвращает графический путь, на котором построена эта кисть. |
| [getCenterPoint()](#getCenterPoint--) | Получает или задает центральную точку градиента по пути. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | Получает или задает центральную точку градиента по пути. |
| [getFocusScales()](#getFocusScales--) | Возвращает точку фокуса для затухания градиента. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | Получает или задает точку фокуса для затухания градиента. |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Возвращает точки пути, на котором построена эта кисть.

**Returns:**
com.aspose.imaging.PointF[] — точки пути.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Возвращает графический путь, на котором построена эта кисть.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Получает или задает центральную точку градиента по пути.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


Получает или задает центральную точку градиента по пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Объект `Aspose.Imaging.PointF`, представляющий центральную точку градиента по пути. |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Возвращает точку фокуса для затухания градиента.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


Получает или задает точку фокуса для затухания градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Объект `Aspose.Imaging.PointF`, представляющий точку фокуса для падения градиента. |

