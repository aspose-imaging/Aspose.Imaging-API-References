---
title: "Matrix"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Заменяет матрицу GDI."
type: docs
weight: 72
url: /ru/java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

Заменяет матрицу GDI+.

--------------------

Большинство алгоритмов взяты из AffineTransform.java от Sun. Внутри используются имена элементов матрицы из Java. Сопоставление имен Java с .net и их описание: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scale Y m02 M31 Translate X m12 M32 Translate Y
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Matrix()](#Matrix--) | Инициализирует новый экземпляр класса Matrix как единичную матрицу. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Инициализирует новый экземпляр класса [Matrix](../../com.aspose.imaging/matrix). |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | Инициализирует новый экземпляр класса [Matrix](../../com.aspose.imaging/matrix) с геометрическим преобразованием, определённым заданным прямоугольником и массивом точек. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | Инициализирует новый экземпляр класса [Matrix](../../com.aspose.imaging/matrix) с геометрическим преобразованием, определённым заданным прямоугольником и массивом точек. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | Создаёт копию класса [Matrix](../../com.aspose.imaging/matrix). |
## Поля

| Поле | Описание |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Единичное преобразование — это такое, при котором выходные координаты всегда совпадают с входными. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Перенос смещает координаты на постоянное значение по осям x и y, не изменяя длину и угол векторов. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Однородное масштабирование умножает длину векторов на одинаковое значение по осям x и y, не изменяя угол между векторами. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Общий масштаб умножает длину векторов на разные величины в направлениях x и y, не изменяя угол между перпендикулярными векторами. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Эта константа является битовой маской для любого из битов флага масштаба. |
| [TYPE_FLIP](#TYPE-FLIP) | Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет зеркальное отражение относительно некоторой оси, которое меняет обычно правостороннюю систему координат на левостороннюю, в дополнение к преобразованиям, указанным другими битами флага. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет поворот квадранта на некоторый кратный 90‑градусный угол, в дополнение к преобразованиям, указанным другими битами флага. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет вращение на произвольный угол, в дополнение к преобразованиям, указанным другими битами флага. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Эта константа является битовой маской для любого из битов флага вращения. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Эта константа указывает, что преобразование, определённое этим объектом, выполняет произвольное преобразование входных координат. |
## Методы

| Метод | Описание |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | Определяет, равны ли две матрицы. |
| [getM11()](#getM11--) | Получает элемент матрицы в первой строке и первом столбце. |
| [getM12()](#getM12--) | Получает элемент матрицы в первой строке и втором столбце. |
| [getM21()](#getM21--) | Получает элемент матрицы во второй строке и первом столбце. |
| [getM22()](#getM22--) | Получает элемент матрицы во второй строке и втором столбце. |
| [getM31()](#getM31--) | Получает элемент матрицы в третьей строке и первом столбце. |
| [getM32()](#getM32--) | Получает элемент матрицы в третьей строке и первом столбце. |
| [toString()](#toString--) | Возвращает строку, представляющую этот экземпляр. |
| [getElements()](#getElements--) | Получает копию элементов матрицы. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | Применяет геометрическое преобразование, представленное этой [Matrix](../../com.aspose.imaging/matrix), к указанному массиву точек. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Применяет указанный вектор масштабирования (scaleX и scaleY) к этой [Matrix](../../com.aspose.imaging/matrix), используя указанный порядок. |
| [scale(float sx, float sy)](#scale-float-float-) | Применяет указанный вектор масштабирования (scaleX и scaleY) к этой Matrix, используя (по умолчанию) порядок Prepend. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Применяет указанный вектор переноса к этой Matrix в указанном порядке. |
| [translate(float tx, float ty)](#translate-float-float-) | Применяет указанный вектор переноса к этой [Matrix](../../com.aspose.imaging/matrix), используя (по умолчанию) порядок Prepend. |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | Умножает эту Matrix на матрицу, указанную в параметре matrix, и в порядке, указанном в параметре order. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | Умножает эту Matrix на матрицу, указанную в параметре matrix, используя (по умолчанию) порядок Prepend. |
| [rotate(float angle, int order)](#rotate-float-int-) | Применяет вращение по часовой стрелке на величину, указанную в параметре angle, вокруг начала координат (ноль по x и y) для этой Matrix в указанном порядке. |
| [rotate(float angle)](#rotate-float-) | Применяет вращение по часовой стрелке на величину, указанную в параметре angle, вокруг начала координат (ноль по x и y) для этой Matrix в порядке по умолчанию (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в порядке по умолчанию (Prepend). |
| [reset()](#reset--) | Сбрасывает эту матрицу, чтобы её элементы соответствовали единичной матрице. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `Object` этому экземпляру. |
| [isIdentity()](#isIdentity--) | Возвращает `true`, если этот `AffineTransform` является единичным преобразованием. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Инициализирует новый экземпляр класса Matrix как единичную матрицу.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Инициализирует новый экземпляр класса [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| m11 | float | m00 M11 Масштаб X |
| m12 | float | m10 M12 Сдвиг Y |
| m21 | float | m01 M21 Сдвиг X |
| m22 | float | m11 M22 Масштаб Y |
| m31 | float | m02 M31 Перемещение X |
| m32 | float | m12 M32 Перемещение Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Инициализирует новый экземпляр класса [Matrix](../../com.aspose.imaging/matrix) с геометрическим преобразованием, определённым заданным прямоугольником и массивом точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура [RectangleF](../../com.aspose.imaging/rectanglef), представляющая прямоугольник, подлежащий преобразованию. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив из трёх структур [PointF](../../com.aspose.imaging/pointf), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается третьими углами. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Инициализирует новый экземпляр класса [Matrix](../../com.aspose.imaging/matrix) с геометрическим преобразованием, определённым заданным прямоугольником и массивом точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура [Rectangle](../../com.aspose.imaging/rectangle), представляющая прямоугольник, подлежащий преобразованию. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | Массив из трёх структур [Point](../../com.aspose.imaging/point), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


Создаёт копию класса [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | Базовая матрица для копирования |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Единичное преобразование — это такое, при котором выходные координаты всегда совпадают с входными координатами. Если это преобразование не является единичным, тип будет либо константой GENERAL\_TRANSFORM, либо комбинацией соответствующих битов флагов для различных преобразований координат, которые выполняет данное преобразование.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Перенос смещает координаты на постоянное значение по осям x и y, не изменяя длину и угол векторов.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Однородный масштаб умножает длину векторов на одинаковую величину по осям x и y, не изменяя угол между векторами. Этот бит флага взаимно исключает бит флага TypeGeneralScale.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Общий масштаб умножает длину векторов на разные величины по осям x и y, не изменяя угол между перпендикулярными векторами. Этот бит флага взаимно исключает бит флага TypeUniformScale.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Эта константа является битовой маской для любого из битов флага масштаба.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет зеркальное отражение относительно некоторой оси, что меняет обычную правостороннюю систему координат на левостороннюю, в дополнение к преобразованиям, указанным другими битами флага. Правосторонняя система координат — это система, в которой положительная ось X вращается против часовой стрелки, накладываясь на положительную ось Y, аналогично направлению, в котором изгибаются пальцы правой руки, когда вы смотрите на большой палец. Левосторонняя система координат — это система, в которой положительная ось X вращается по часовой стрелке, накладываясь на положительную ось Y, аналогично направлению, в котором изгибаются пальцы левой руки. Нет математического способа определить угол исходного отражения или зеркального преобразования, поскольку все углы отражения одинаковы при соответствующем корректирующем вращении. ПРИМЕЧАНИЕ: TypeFlip был добавлен после того, как GENERAL\_TRANSFORM стал публичным, и биты флага больше нельзя было удобно перенумеровать без введения бинарной несовместимости во внешнем коде.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет поворот квадранта на кратное 90‑градусное значение, в дополнение к преобразованиям, указанным другими битами флага. Поворот изменяет углы векторов на одинаковую величину независимо от исходного направления вектора и без изменения длины вектора. Этот бит флага взаимно исключает бит флага TypeGeneralRotation.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет вращение на произвольный угол в дополнение к преобразованиям, указанным другими битами флага. Вращение изменяет углы векторов на одинаковую величину независимо от исходного направления вектора и без изменения длины вектора. Этот бит флага взаимно исключает с

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Эта константа является битовой маской для любого из битов флага вращения.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Эта константа указывает, что преобразование, определённое этим объектом, выполняет произвольное преобразование входных координат. Если это преобразование может быть классифицировано любой из вышеуказанных констант, тип будет либо константой TypeIdentity, либо комбинацией соответствующих битов флага для различных преобразований координат, которые выполняет это преобразование.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Определяет, равны ли две матрицы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | Первая матрица для сравнения. |
| b | [Matrix](../../com.aspose.imaging/matrix) | Вторая матрица для сравнения. |

**Returns:**
boolean - Истина, если матрицы равны.
### getM11() {#getM11--}
```
public final float getM11()
```


Получает элемент матрицы в первой строке первой колонке. Представляет масштаб вдоль оси X.

**Returns:**
float - элемент матрицы в первой строке первой колонке.
### getM12() {#getM12--}
```
public final float getM12()
```


Получает элемент матрицы в первой строке второй колонке. Представляет сдвиг вдоль оси Y.

**Returns:**
float - элемент матрицы в первой строке второй колонке.
### getM21() {#getM21--}
```
public final float getM21()
```


Получает элемент матрицы во второй строке первой колонке. Представляет сдвиг вдоль оси X.

**Returns:**
float - элемент матрицы во второй строке первой колонке.
### getM22() {#getM22--}
```
public final float getM22()
```


Получает элемент матрицы во второй строке второй колонке. Представляет масштаб вдоль оси Y.

**Returns:**
float - элемент матрицы во второй строке второй колонке.
### getM31() {#getM31--}
```
public final float getM31()
```


Получает элемент матрицы в третьей строке первой колонке. Представляет перемещение вдоль оси X.

**Returns:**
float - элемент матрицы в третьей строке первой колонке.
### getM32() {#getM32--}
```
public final float getM32()
```


Получает элемент матрицы в третьей строке первой колонке. Представляет перемещение вдоль оси Y.

**Returns:**
float - элемент матрицы в третьей строке первой колонке.
### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую этот экземпляр.

**Returns:**
java.lang.String - Строка, представляющая этот экземпляр.
### getElements() {#getElements--}
```
public final float[] getElements()
```


Получает копию элементов матрицы.

**Returns:**
float[] - Копия элементов матрицы.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


Применяет геометрическое преобразование, представленное этой [Matrix](../../com.aspose.imaging/matrix), к указанному массиву точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Точки. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


Применяет указанный вектор масштабирования (scaleX и scaleY) к этой [Matrix](../../com.aspose.imaging/matrix), используя указанный порядок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | float | Масштаб X. |
| scaleY | float | Масштаб Y. |
| order | int | Порядок. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


Применяет указанный вектор масштабирования (scaleX и scaleY) к этой Matrix, используя (по умолчанию) порядок Prepend.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Значение sx. Значение sx. Значение sx. |
| sy | float | Значение sy. Значение sy. Значение sy. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


Применяет указанный вектор переноса к этой Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| offsetX | float | Смещение X. |
| offsetY | float | Смещение Y. |
| order | int | Порядок. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


Применяет указанный вектор переноса к этой [Matrix](../../com.aspose.imaging/matrix), используя (по умолчанию) порядок Prepend.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tx | float | Значение tx. Значение tx. Значение tx. |
| ty | float | Значение ty. Значение ty. Значение ty. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


Умножает эту Matrix на матрицу, указанную в параметре matrix, и в порядке, указанном в параметре order.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | Значение tx. Значение tx. Значение tx. |
| order | int | Порядок. Порядок. Порядок. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


Умножает эту Matrix на матрицу, указанную в параметре matrix, используя (по умолчанию) порядок Prepend.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | Матрица для умножения. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


Применяет вращение по часовой стрелке на величину, указанную в параметре angle, вокруг начала координат (ноль по x и y) для этой Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |
| order | int | Порядок матрицы. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


Применяет вращение по часовой стрелке на величину, указанную в параметре angle, вокруг начала координат (ноль по x и y) для этой Matrix в порядке по умолчанию (Prepend).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол. |
| point | [PointF](../../com.aspose.imaging/pointf) | Точка. |
| order | int | Порядок. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в порядке по умолчанию (Prepend).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол. |
| point | [PointF](../../com.aspose.imaging/pointf) | Точка. |

### reset() {#reset--}
```
public final void reset()
```


Сбрасывает эту матрицу, чтобы её элементы соответствовали единичной матрице.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
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
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Возвращает `true`, если этот `AffineTransform` является единичным преобразованием.

**Returns:**
логический тип - `true`, если этот `AffineTransform` является единичным преобразованием; `false` в противном случае.
