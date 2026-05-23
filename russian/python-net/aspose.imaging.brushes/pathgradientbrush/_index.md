---
title: "Класс PathGradientBrush"
type: docs
weight: 50
url: /ru/python-net/aspose.imaging.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Инициализирует новый экземпляр класса PathGradientBrush |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_2) | Инициализирует новый экземпляр класса PathGradientBrush |
| [PathGradientBrush(path_points)](#PathGradientBrush_path_points_3) | Инициализирует новый экземпляр класса PathGradientBrush |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_4) | Инициализирует новый экземпляр класса PathGradientBrush |
| [PathGradientBrush(path_points, wrap_mode)](#PathGradientBrush_path_points_wrap_mode_5) | Инициализирует новый экземпляр класса PathGradientBrush |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Получает или задает объект [Blend](/imaging/python-net/aspose.imaging/blend/), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента. |
| center_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает цвет в центре градиента пути. |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает центральную точку градиента пути. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает точку фокуса для затухания градиента. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Получает графический путь, на основе которого построена эта кисть. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Получает или задает объект [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/), определяющий многокрасочный линейный градиент. |
| is_transform_changed | bool | r | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. Например, установка матрицы преобразования или<br/>            вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| opacity | float | r/w | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Получает точки пути, на основе которых построена эта кисть. |
| surround_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает массив цветов, соответствующих точкам пути, который заполняет этот [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает копию [Matrix](/imaging/python-net/aspose.imaging/matrix/), определяющую локальное геометрическое преобразование для этого [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Получает или задает перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), которое указывает режим обтекания для этого [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанным путем. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанными точками. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанными точками. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанными точками и режимом обтекания. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанными точками и режимом обтекания. |
| [deep_clone()](#deep_clone__6) | Создает новый глубокий клон текущего [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) путем предварительного добавления указанного [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) в указанном порядке. |
| reset_transform() | Сбрасывает свойство [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) к единичному. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | Вращает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | Вращает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод предварительно добавляет матрицу масштабирования к преобразованию. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_13) | Создаёт градиент с центральным цветом и линейным переходом к одному окружающему цвету. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_14) | Создаёт градиент с центральным цветом и линейным переходом к каждому окружающему цвету. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_15) | Создаёт кисть градиента, изменяющую цвет, начиная от центра пути и распространяясь к его границе. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_16) | Создаёт кисть градиента, изменяющую цвет, начиная от центра пути и распространяясь к его границе. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_17) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_18) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Инициализирует новый экземпляр класса PathGradientBrush

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_2}


```
 PathGradientBrush(path_points) 
```

Инициализирует новый экземпляр класса PathGradientBrush

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |

### Constructor: PathGradientBrush(path_points) {#PathGradientBrush_path_points_3}


```
 PathGradientBrush(path_points) 
```

Инициализирует новый экземпляр класса PathGradientBrush

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_4}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Инициализирует новый экземпляр класса PathGradientBrush

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Constructor: PathGradientBrush(path_points, wrap_mode) {#PathGradientBrush_path_points_wrap_mode_5}


```
 PathGradientBrush(path_points, wrap_mode) 
```

Инициализирует новый экземпляр класса PathGradientBrush

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) |  |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) |  |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанным путем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Графический путь [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) определяет область, заполненную этим [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, образующие вершины пути. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанными точками.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, образующие вершины пути. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Режим [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) указывает, как заполнения, нарисованные этим [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/), размещаются плиткой. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

Инициализирует новый экземпляр класса [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) с указанными точками и режимом обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Массив структур [Point](/imaging/python-net/aspose.imaging/point/), представляющих точки, образующие вершины пути. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Режим [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) указывает, как заполнения, нарисованные этим [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/), размещаются плиткой. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) |  |


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_13}


```
 set_blend_triangular_shape(focus) 
```

Создаёт градиент с центральным цветом и линейным переходом к одному окружающему цвету.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе цвет центра будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_14}


```
 set_blend_triangular_shape(focus, scale) 
```

Создаёт градиент с центральным цветом и линейным переходом к каждому окружающему цвету.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе цвет центра будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |
| масштаб | float | Значение от 0 до 1, указывающее максимальную интенсивность цвета центра, который смешивается с цветом границы. Значение 1 приводит к наивысшей возможной интенсивности цвета центра и является значением по умолчанию. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_15}


```
 set_sigma_bell_shape(focus) 
```

Создаёт кисть градиента, изменяющую цвет, начиная от центра пути и распространяясь к его границе. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе цвет центра будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_16}


```
 set_sigma_bell_shape(focus, scale) 
```

Создаёт кисть градиента, изменяющую цвет, начиная от центра пути и распространяясь к его границе. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее, где вдоль любого радиала от центра пути к его границе цвет центра будет иметь наивысшую интенсивность. Значение 1 (по умолчанию) размещает наивысшую интенсивность в центре пути. |
| масштаб | float | Значение от 0 до 1, указывающее максимальную интенсивность цвета центра, который смешивается с цветом границы. Значение 1 приводит к наивысшей возможной интенсивности цвета центра и является значением по умолчанию. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_17}


```
 translate_transform(dx, dy) 
```

Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_18}


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

