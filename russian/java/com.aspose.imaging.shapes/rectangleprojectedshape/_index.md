---
title: "RectangleProjectedShape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет форму, проецируемую на прямоугольник, повернутый в определённую ориентацию."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Представляет форму, проецируемую на прямоугольник, повернутый в определённую ориентацию. Задаётся четырьмя точками, которые могут вращаться в пространстве, сохраняя одинаковую длину сторон и 90 градусов между соседними сторонами.
## Методы

| Метод | Описание |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | Получает левую верхнюю точку прямоугольника. |
| [getRightTop()](#getRightTop--) | Получает правую верхнюю точку прямоугольника. |
| [getLeftBottom()](#getLeftBottom--) | Получает левую нижнюю точку прямоугольника. |
| [getRightBottom()](#getRightBottom--) | Получает правую нижнюю точку прямоугольника. |
| [getCenter()](#getCenter--) | Получает центр фигуры. |
| [getBounds()](#getBounds--) | Получает границы объекта. |
| [getRectangleWidth()](#getRectangleWidth--) | Получает ширину прямоугольника. |
| [getRectangleHeight()](#getRectangleHeight--) | Получает высоту прямоугольника. |
| [hasSegments()](#hasSegments--) | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Получает границы объекта. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Применяет указанное преобразование к форме. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `Object` этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Получает левую верхнюю точку прямоугольника.

Значение: Левая верхняя точка прямоугольника.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Получает правую верхнюю точку прямоугольника.

Значение: Правая верхняя точка прямоугольника.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Получает левую нижнюю точку прямоугольника.

Значение: Левая нижняя точка прямоугольника.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Получает правую нижнюю точку прямоугольника.

Значение: Правая нижняя точка прямоугольника.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Получает центр фигуры.

Значение: Центр формы.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Получает границы объекта.

Значение: Границы объекта.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Получает ширину прямоугольника.

Значение: Ширина прямоугольника.

**Returns:**
double
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Получает высоту прямоугольника.

Значение: Высота прямоугольника.

**Returns:**
double
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Получает значение, указывающее, есть ли у фигуры сегменты.

Значение: `True`, если у формы есть сегменты; иначе `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Получает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Матрица, применяемая перед вычислением границ. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Получает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Матрица, применяемая перед вычислением границ. |
| pen | [Pen](../../com.aspose.imaging/pen) | Карандаш, используемый для объекта. Это может влиять на размер границ объекта. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Применяет указанное преобразование к форме.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Преобразование, которое следует применить. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный `Object` этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `Object` для сравнения с этим экземпляром. |

**Returns:**
логический тип - `true`, если указанный `Object` равен этому экземпляру; иначе `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
