---
title: "TransformBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Кисть с возможностями трансформации."
type: docs
weight: 19
url: /ru/java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

`Brush` с возможностями трансформации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Получает или задает перечисление `Aspose.Imaging.WrapMode`, которое указывает режим обтекания для этого `TransformBrush`. |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задает перечисление `Aspose.Imaging.WrapMode`, которое указывает режим обтекания для этого `TransformBrush`. |
| [getTransform()](#getTransform--) | Получает или задает копию `Aspose.Imaging.Matrix`, определяющую локальное геометрическое преобразование для этого `TransformBrush`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Получает или задает копию `Aspose.Imaging.Matrix`, определяющую локальное геометрическое преобразование для этого `TransformBrush`. |
| [isTransformChanged()](#isTransformChanged--) | Получает значение, указывающее, были ли трансформации изменены каким-либо образом. |
| [resetTransform()](#resetTransform--) | Сбрасывает свойство `TransformBrush.Transform` к единичному преобразованию. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Умножает `Aspose.Imaging.Matrix`, представляющую локальное геометрическое преобразование этого `LinearGradientBrush`, на указанный `Aspose.Imaging.Matrix`, предварительно добавив указанный `Aspose.Imaging.Matrix`. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Умножает `Aspose.Imaging.Matrix`, представляющую локальное геометрическое преобразование этого `LinearGradientBrush`, на указанный `Aspose.Imaging.Matrix` в указанном порядке. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Смещает локальное геометрическое преобразование на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование на указанные величины. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Поворачивает локальное геометрическое преобразование на указанную величину. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает или задает перечисление `Aspose.Imaging.WrapMode`, которое указывает режим обтекания для этого `TransformBrush`.

**Returns:**
int — `Aspose.Imaging.WrapMode`, определяющий, как заполняются области, нарисованные с помощью этого `TransformBrush`.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Получает или задает перечисление `Aspose.Imaging.WrapMode`, которое указывает режим обтекания для этого `TransformBrush`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Получает или задает копию `Aspose.Imaging.Matrix`, определяющую локальное геометрическое преобразование для этого `TransformBrush`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Получает или задает копию `Aspose.Imaging.Matrix`, определяющую локальное геометрическое преобразование для этого `TransformBrush`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Возвращает значение, указывающее, были ли преобразования изменены каким-либо образом. Например, установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+.

Значение: `True`, если преобразование было изменено; иначе `false`.

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Сбрасывает свойство `TransformBrush.Transform` к единичному преобразованию.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Умножает `Aspose.Imaging.Matrix`, представляющую локальное геометрическое преобразование этого `LinearGradientBrush`, на указанный `Aspose.Imaging.Matrix`, предварительно добавив указанный `Aspose.Imaging.Matrix`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `Aspose.Imaging.Matrix`, на который умножается геометрическое преобразование. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Умножает `Aspose.Imaging.Matrix`, представляющую локальное геометрическое преобразование этого `LinearGradientBrush`, на указанный `Aspose.Imaging.Matrix` в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `Aspose.Imaging.Matrix`, на который умножается геометрическое преобразование. |
| order | int | `Aspose.Imaging.MatrixOrder`, определяющий порядок умножения двух матриц. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | int | Порядок (добавление в начало или в конец), в котором применять трансляцию. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина масштабирования преобразования по оси X. |
| sy | float | Величина масштабирования преобразования по оси Y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина масштабирования преобразования по оси X. |
| sy | float | Величина масштабирования преобразования по оси Y. |
| order | int | `Aspose.Imaging.MatrixOrder`, определяющий, добавлять ли матрицу масштабирования в конец или в начало. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |
| order | int | `Aspose.Imaging.MatrixOrder`, определяющий, добавлять ли матрицу вращения в конец или в начало. |

