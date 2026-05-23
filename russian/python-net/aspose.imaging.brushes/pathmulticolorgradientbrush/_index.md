---
title: "Класс PathMulticolorGradientBrush"
type: docs
weight: 70
url: /ru/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_2) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_3) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_4) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_5) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает центральную точку градиента пути. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает точку фокуса для затухания градиента. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Получает графический путь, на основе которого построена эта кисть. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Получает или задает объект [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/), определяющий многокрасочный линейный градиент. |
| is_transform_changed | bool | r | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. Например, установка матрицы преобразования или<br/>            вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| opacity | float | r/w | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Получает точки пути, на основе которых построена эта кисть. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает копию [Matrix](/imaging/python-net/aspose.imaging/matrix/), определяющую локальное геометрическое преобразование для этого [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Получает или задает перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), которое указывает режим обтекания для этого [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанным путем. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания. |
| [deep_clone()](#deep_clone__6) | Создает новый глубокий клон текущего [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) путем предварительного добавления указанного [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) в указанном порядке. |
| reset_transform() | Сбрасывает свойство [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) к единичному. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | Вращает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | Вращает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод предварительно добавляет матрицу масштабирования к преобразованию. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_13) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_14) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_2}


```
 PathMulticolorGradientBrush(path_points) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, образующие вершины пути. |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_3}


```
 PathMulticolorGradientBrush(path_points) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, образующие вершины пути. |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Тип [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), который определяет, как заполнения, нарисованные этим [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/), будут повторяться. |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Тип [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), который определяет, как заполнения, нарисованные этим [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/), будут повторяться. |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанным путем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), определяющий область, заполняемую этим [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, образующие вершины пути. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), представляющих точки, образующие вершины пути. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Тип [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), который определяет, как заполнения, нарисованные этим [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/), будут повторяться. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Тип [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), который определяет, как заполнения, нарисованные этим [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/), будут повторяться. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

Создает новый глубокий клон текущего [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Новый [Brush](/imaging/python-net/aspose.imaging/brush/), который является глубоким клоном этого экземпляра [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) путем предварительного добавления указанного [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), на которую следует умножить геометрическое преобразование. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), на которую следует умножить геометрическое преобразование. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Структура [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), указывающая порядок умножения двух матриц. |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

Вращает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

Вращает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Структура [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), указывающая, следует ли добавить в конец или в начало матрицу вращения. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод предварительно добавляет матрицу масштабирования к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


```
 scale_transform(sx, sy, order) 
```

Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Тип [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) который указывает, добавлять или предварять матрицу масштабирования. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_13}


```
 translate_transform(dx, dy) 
```

Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_14}


```
 translate_transform(dx, dy, order) 
```

Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок (предварительно или последовательно), в котором применяется трансляция. |

