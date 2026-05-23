---
title: "Класс Matrix"
type: docs
weight: 6070
url: /ru/python-net/aspose.imaging/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Matrix

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Matrix()](#Matrix__1) | Инициализирует новый экземпляр класса Matrix как единичную матрицу. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Создаёт копию класса [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | Этот бит флага указывает, что преобразование, определённое этим объектом<br/>            выполняет зеркальное отражение относительно некоторой оси, что меняет<br/>            обычно правостороннюю систему координат на левостороннюю<br/>            систему в дополнение к преобразованиям, указанным другими битами флага.<br/>            Правосторонняя система координат — это система, в которой положительная ось X<br/>            вращается против часовой стрелки, накладываясь на положительную ось Y,<br/>            аналогично направлению, в котором изгибаются пальцы правой руки,<br/>            когда вы смотрите на большой палец спереди.<br/>            Левосторонняя система координат — это система, в которой положительная ось X<br/>            вращается по часовой стрелке, накладываясь на положительную ось Y, аналогично<br/>            направлению, в котором изгибаются пальцы левой руки.<br/>            Нет математического способа определить угол исходного отражения или зеркального преобразования, поскольку все углы отражения одинаковы при соответствующем корректирующем вращении.<br/>            ПРИМЕЧАНИЕ: TypeFlip был добавлен после того, как GENERAL_TRANSFORM стал публичным<br/>            и биты флага больше нельзя было удобно перенумеровать без введения бинарной несовместимости во внешнем коде. |
| TYPE_GENERAL_ROTATION [static] | int | r | Этот бит флага указывает, что преобразование, определённое этим объектом<br/>            выполняет вращение на произвольный угол в дополнение к<br/>            преобразованиям, указанным другими битами флага.<br/>            Вращение изменяет углы векторов на одинаковую величину<br/>            независимо от исходного направления вектора и без<br/>            изменения длины вектора.<br/>            Этот бит флага взаимно исключает |
| TYPE_GENERAL_SCALE [static] | int | r | Общий масштаб умножает длину векторов на разные<br/>            величины по осям x и y, не изменяя угол<br/>            между перпендикулярными векторами.<br/>            Этот бит флага взаимно исключает флаг TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Эта константа указывает, что преобразование, определённое этим объектом<br/>            выполняет произвольное преобразование входных координат.<br/>            Если это преобразование может быть классифицировано любой из вышеуказанных констант,<br/>            тип будет либо константой TypeIdentity, либо<br/>            комбинацией соответствующих битов флага для различных координатных<br/>            преобразований, которые выполняет это преобразование. |
| TYPE_IDENTITY [static] | int | r | Трансформация идентичности — это такая, в которой выходные координаты<br/>            всегда совпадают с входными координатами.<br/>            Если эта трансформация отличается от трансформации идентичности,<br/>            тип будет либо константой GENERAL_TRANSFORM, либо<br/>            комбинацией соответствующих битов флага для различных координатных<br/>            преобразований, которые выполняет эта трансформация. |
| TYPE_MASK_ROTATION [static] | int | r | Эта константа является битовой маской для любого из битов флага вращения. |
| TYPE_MASK_SCALE [static] | int | r | Эта константа является битовой маской для любого из битов флага масштабирования. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Этот бит флага указывает, что преобразование, определённое этим объектом<br/>            выполняет квадрантное вращение на некоторый кратный 90 градусов в<br/>            дополнение к преобразованиям, указанным другими битами флага.<br/>            Вращение изменяет углы векторов на одинаковую величину<br/>            независимо от исходного направления вектора и без<br/>            изменения длины вектора.<br/>            Этот бит флага взаимно исключает флаг TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | Трансляция перемещает координаты на постоянное значение по x<br/>            и y, не изменяя длину или угол векторов. |
| TYPE_UNIFORM_SCALE [static] | int | r | Однородный масштаб умножает длину векторов на одинаковую величину<br/>            как по оси x, так и по оси y, не изменяя угол между<br/>            векторами.<br/>            Этот бит флага взаимно исключает флаг TypeGeneralScale. |
| elements | float[] | r | Получает массив значений с плавающей точкой, представляющих элементы этого [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| m11 | float | r | Получает элемент матрицы в первой строке первой колонке. Представляет масштаб вдоль оси X. |
| m12 | float | r | Получает элемент матрицы в первой строке второй колонке. Представляет сдвиг вдоль оси Y. |
| m21 | float | r | Получает элемент матрицы во второй строке первой колонке. Представляет сдвиг вдоль оси X. |
| m22 | float | r | Получает элемент матрицы во второй строке второй колонке. Представляет масштаб вдоль оси Y. |
| m31 | float | r | Получает элемент матрицы в третьей строке первой колонке. Представляет перемещение вдоль оси X. |
| m32 | float | r | Получает элемент матрицы в третьей строке первой колонке. Представляет перемещение вдоль оси Y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_rect(rect, plgpts)](#create_with_rect_rect_plgpts_1) | Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек. |
| [create_with_rect_f(rect, plgpts)](#create_with_rect_f_rect_plgpts_2) | Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек. |
| [get_elements()](#get_elements__3) | Получает копию элементов матрицы. |
| [multiply(t_tx)](#multiply_t_tx_4) | Умножает эту Matrix на матрицу, указанную в параметре matrix, используя (по умолчанию) порядок Prepend. |
| [multiply(t_tx, order)](#multiply_t_tx_order_5) | Умножает эту Matrix на матрицу, указанную в параметре matrix, в порядке, указанном в параметре order. |
| reset() | Сбрасывает эту Matrix, задавая элементы единичной матрицы. |
| [rotate(angle)](#rotate_angle_6) | Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (ноль по x и y) к этой Matrix в порядке по умолчанию (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_7) | Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (ноль по x и y) к этой Matrix в указанном порядке. |
| [rotate_at(angle, point)](#rotate_at_angle_point_8) | Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в порядке по умолчанию (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_9) | Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_10) | Применяет указанный вектор масштаба (scaleX и scaleY) к этой [Matrix](/imaging/python-net/aspose.imaging/matrix/) используя указанный порядок. |
| [scale(sx, sy)](#scale_sx_sy_11) | Применяет указанный вектор масштаба (scaleX и scaleY) к этой Matrix, используя (по умолчанию) порядок Prepend. |
| [transform_points(points)](#transform_points_points_12) | Применяет геометрическое преобразование, представленное этой [Matrix](/imaging/python-net/aspose.imaging/matrix/), к указанному массиву точек. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_13) | Применяет указанный вектор перемещения к этой Matrix в указанном порядке. |
| [translate(tx, ty)](#translate_tx_ty_14) | Применяет указанный вектор перемещения к этой [Matrix](/imaging/python-net/aspose.imaging/matrix/) используя (по умолчанию) порядок Prepend. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Инициализирует новый экземпляр класса Matrix как единичную матрицу.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| m11 | float | m00     M11     Масштаб X |
| m12 | float | m10     M12     Сдвиг Y |
| m21 | float | m01     M21     Сдвиг X |
| m22 | float | m11     M22     Масштаб Y |
| m31 | float | m02     M31     Перемещение X |
| m32 | float | m12     M32     Переместить Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Создаёт копию класса [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| origin | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Базовая матрица для копирования |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющая прямоугольник, который будет преобразован. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющая прямоугольник, который будет преобразован. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

### Method: create_with_rect(rect, plgpts)  [static] {#create_with_rect_rect_plgpts_1}


```
 create_with_rect(rect, plgpts) 
```

Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющая прямоугольник, который будет преобразован. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив из трёх структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: create_with_rect_f(rect, plgpts)  [static] {#create_with_rect_f_rect_plgpts_2}


```
 create_with_rect_f(rect, plgpts) 
```

Инициализирует новый экземпляр класса [Matrix](/imaging/python-net/aspose.imaging/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющая прямоугольник, который будет преобразован. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив из трёх структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: get_elements() {#get_elements__3}


```
 get_elements() 
```

Получает копию элементов матрицы.

**Returns**

| Тип | Описание |
| :- | :- |
| float[] | Копия элементов матрицы. |


### Method: multiply(t_tx) {#multiply_t_tx_4}


```
 multiply(t_tx) 
```

Умножает эту Matrix на матрицу, указанную в параметре matrix, используя (по умолчанию) порядок Prepend.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, с которой производится умножение. |

### Method: multiply(t_tx, order) {#multiply_t_tx_order_5}


```
 multiply(t_tx, order) 
```

Умножает эту Matrix на матрицу, указанную в параметре matrix, в порядке, указанном в параметре order.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | tx. tx. tx. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | порядок. порядок. порядок. |

### Method: rotate(angle) {#rotate_angle_6}


```
 rotate(angle) 
```

Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (ноль по x и y) к этой Matrix в порядке по умолчанию (Prepend).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate(angle, order) {#rotate_angle_order_7}


```
 rotate(angle, order) 
```

Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (ноль по x и y) к этой Matrix в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок матрицы. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_8}


```
 rotate_at(angle, point) 
```

Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в порядке по умолчанию (Prepend).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_9}


```
 rotate_at(angle, point, order) 
```

Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_10}


```
 scale(scale_x, scale_y, order) 
```

Применяет указанный вектор масштаба (scaleX и scaleY) к этой [Matrix](/imaging/python-net/aspose.imaging/matrix/) используя указанный порядок.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scale_x | float | Масштаб X. |
| scale_y | float | Масштаб Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок. |

### Method: scale(sx, sy) {#scale_sx_sy_11}


```
 scale(sx, sy) 
```

Применяет указанный вектор масштаба (scaleX и scaleY) к этой Matrix, используя (по умолчанию) порядок Prepend.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### Method: transform_points(points) {#transform_points_points_12}


```
 transform_points(points) 
```

Применяет геометрическое преобразование, представленное этой [Matrix](/imaging/python-net/aspose.imaging/matrix/), к указанному массиву точек.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Точки. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_13}


```
 translate(offset_x, offset_y, order) 
```

Применяет указанный вектор перемещения к этой Matrix в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| offset_x | float | Смещение X. |
| offset_y | float | Смещение Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок. |

### Method: translate(tx, ty) {#translate_tx_ty_14}


```
 translate(tx, ty) 
```

Применяет указанный вектор перемещения к этой [Matrix](/imaging/python-net/aspose.imaging/matrix/) используя (по умолчанию) порядок Prepend.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tx | float | tx. tx. tx. |
| ty | float | ty. ty. ty. |

