---
title: "Класс GraphicsPath"
type: docs
weight: 5040
url: /ru/python-net/aspose.imaging/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.GraphicsPath

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Инициализирует новый экземпляр класса [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) . |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Инициализирует новый экземпляр класса [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) . |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Инициализирует новый экземпляр класса [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) . |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Инициализирует новый экземпляр класса [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает или задает границы объекта. |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | r | Получает фигуры пути. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | r/w | Получает или задает перечисление [FillMode](/imaging/python-net/aspose.imaging/fillmode/), которое определяет, как заполняются внутренности фигур в этом [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Добавляет новую фигуру. |
| [add_figures(figures)](#add_figures_figures_2) | Добавляет новые фигуры. |
| [add_path(adding_path)](#add_path_adding_path_3) | Добавляет указанный [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) к этому пути. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Добавляет указанный [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) к этому пути. |
| [deep_clone()](#deep_clone__5) | Выполняет глубокое клонирование этого графического пути. |
| flatten() | Преобразует каждую кривую в этом пути в последовательность соединённых отрезков. |
| [flatten(matrix)](#flatten_matrix_6) | Применяет указанное преобразование, а затем преобразует каждую кривую в этом [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в последовательность соединённых отрезков. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Преобразует каждую кривую в этом [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в последовательность соединённых отрезков. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Получает границы объекта. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Получает границы объекта. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_point(point, pen)](#is_outline_visible_point_point_pen_18) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_point_f(point, pen)](#is_outline_visible_point_f_point_pen_19) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_point_f_graphics(pt, pen, graphics)](#is_outline_visible_point_f_graphics_pt_pen_graphics_20) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_point_graphics(pt, pen, graphics)](#is_outline_visible_point_graphics_pt_pen_graphics_21) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_xy(x, y, pen)](#is_outline_visible_xy_x_y_pen_22) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_xy_graphics(x, y, pen, graphics)](#is_outline_visible_xy_graphics_x_y_pen_graphics_23) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_outline_visible_xyf(x, y, pen)](#is_outline_visible_xyf_x_y_pen_24) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [is_outline_visible_xyf_graphics(x, y, pen, graphics)](#is_outline_visible_xyf_graphics_x_y_pen_graphics_25) | Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(point)](#is_visible_point_26) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(point)](#is_visible_point_27) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_28) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_29) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_30) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_31) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_32) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в видимом области отсечения указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_33) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в видимом области отсечения указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_point(point)](#is_visible_point_point_34) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_35) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_f_graphics(pt, graphics)](#is_visible_point_f_graphics_pt_graphics_36) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_point_graphics(pt, graphics)](#is_visible_point_graphics_pt_graphics_37) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy(x, y)](#is_visible_xy_x_y_38) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xy_graphics(x, y, graphics)](#is_visible_xy_graphics_x_y_graphics_39) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), используя указанный [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xyf(x, y)](#is_visible_xyf_x_y_40) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [is_visible_xyf_graphics(x, y, graphics)](#is_visible_xyf_graphics_x_y_graphics_41) | Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в видимом области отсечения указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [remove_figure(figure)](#remove_figure_figure_42) | Удаляет фигуру. |
| [remove_figures(figures)](#remove_figures_figures_43) | Удаляет фигуры. |
| reset() | Очищает графический путь и устанавливает [FillMode](/imaging/python-net/aspose.imaging/fillmode/) в [FillMode.ALTERNATE](/imaging/python-net/aspose.imaging/fillmode/). |
| reverse() | Обращает порядок фигур, форм и точек в каждой форме этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [transform(transform)](#transform_transform_44) | Применяет указанное преобразование к форме. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_45) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_46) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_47) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_48) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen)](#widen_pen_49) | Добавляет дополнительный контур к пути. |
| [widen(pen, matrix)](#widen_pen_matrix_50) | Добавляет дополнительный контур к [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_51) | Заменяет этот [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) кривыми, которые охватывают область, заполняемую при отрисовке этого пути указанной ручкой. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Инициализирует новый экземпляр класса [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) .


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Инициализирует новый экземпляр класса [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) .

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Фигуры, из которых инициализировать. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Инициализирует новый экземпляр класса [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) .

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Фигуры, из которых инициализировать. |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Режим заливки. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Инициализирует новый экземпляр класса [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) .

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fill_mode | [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Режим заливки. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Добавляет новую фигуру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | Фигура для добавления. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Добавляет новые фигуры.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Фигуры для добавления. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Добавляет указанный [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) к этому пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) для добавления. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Добавляет указанный [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) к этому пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| adding_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) для добавления. |
| соединить | bool | Булево значение, указывающее, является ли первая фигура в добавленном пути частью последней фигуры в этом пути. Значение true указывает, что первая фигура в добавленном пути является частью последней фигуры в этом пути. Значение false указывает, что первая фигура в добавленном пути отдельна от последней фигуры в этом пути. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Выполняет глубокое клонирование этого графического пути.

**Returns**

| Тип | Описание |
| :- | :- |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Глубокая копия графического пути. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Применяет указанное преобразование, а затем преобразует каждую кривую в этом [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в последовательность соединённых отрезков.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), с помощью которой преобразовать этот [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) перед уплощением. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Преобразует каждую кривую в этом [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в последовательность соединённых отрезков.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), с помощью которой преобразовать этот [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) перед уплощением. |
| плоскостность | float | Указывает максимальную допустимую ошибку между кривой и её уплощённым приближением. Значение 0.25 является значением по умолчанию. Уменьшение значения плоскостности увеличит количество линейных сегментов в приближении. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, применяемая перед вычислением границ. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Оценочные границы объекта. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Получает границы объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица, применяемая перед вычислением границ. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка, используемая для объекта. Это может влиять на размер границ объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Оценочные границы объекта. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/), указывающая расположение для проверки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/), указывающая расположение для проверки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/), указывающая расположение для проверки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/), указывающая расположение для проверки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible_point(point, pen) {#is_outline_visible_point_point_pen_18}


```
 is_outline_visible_point(point, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/), указывающая расположение для проверки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible_point_f(point, pen) {#is_outline_visible_point_f_point_pen_19}


```
 is_outline_visible_point_f(point, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/), указывающая расположение для проверки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible_point_f_graphics(pt, pen, graphics) {#is_outline_visible_point_f_graphics_pt_pen_graphics_20}


```
 is_outline_visible_point_f_graphics(pt, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/), указывающая расположение для проверки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible_point_graphics(pt, pen, graphics) {#is_outline_visible_point_graphics_pt_pen_graphics_21}


```
 is_outline_visible_point_graphics(pt, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Точка [Point](/imaging/python-net/aspose.imaging/point/), указывающая расположение для проверки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible_xy(x, y, pen) {#is_outline_visible_xy_x_y_pen_22}


```
 is_outline_visible_xy(x, y, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible_xy_graphics(x, y, pen, graphics) {#is_outline_visible_xy_graphics_x_y_pen_graphics_23}


```
 is_outline_visible_xy_graphics(x, y, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible_xyf(x, y, pen) {#is_outline_visible_xyf_x_y_pen_24}


```
 is_outline_visible_xyf(x, y, pen) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_outline_visible_xyf_graphics(x, y, pen, graphics) {#is_outline_visible_xyf_graphics_x_y_pen_graphics_25}


```
 is_outline_visible_xyf_graphics(x, y, pen, graphics) 
```

Указывает, находится ли указанная точка внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанным [Pen](/imaging/python-net/aspose.imaging/pen/) и с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Ручка [Pen](/imaging/python-net/aspose.imaging/pen/) для проверки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка содержится внутри (под) контура этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) при отрисовке указанной [Pen](/imaging/python-net/aspose.imaging/pen/); в противном случае — false. |


### Method: is_visible(point) {#is_visible_point_26}


```
 is_visible(point) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Объект [PointF](/imaging/python-net/aspose.imaging/pointf/) представляет проверяемую точку. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible(point) {#is_visible_point_27}


```
 is_visible(point) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Объект [PointF](/imaging/python-net/aspose.imaging/pointf/) представляет проверяемую точку. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_28}


```
 is_visible(pt, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Объект [PointF](/imaging/python-net/aspose.imaging/pointf/) представляет проверяемую точку. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого объекта; в противном случае — false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_29}


```
 is_visible(pt, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Объект [PointF](/imaging/python-net/aspose.imaging/pointf/) представляет проверяемую точку. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого объекта; в противном случае — false. |


### Method: is_visible(x, y) {#is_visible_x_y_30}


```
 is_visible(x, y) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible(x, y) {#is_visible_x_y_31}


```
 is_visible(x, y) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_32}


```
 is_visible(x, y, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в видимом области отсечения указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_33}


```
 is_visible(x, y, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в видимом области отсечения указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible_point(point) {#is_visible_point_point_34}


```
 is_visible_point(point) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Объект [PointF](/imaging/python-net/aspose.imaging/pointf/) представляет проверяемую точку. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_35}


```
 is_visible_point_f(point) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Объект [PointF](/imaging/python-net/aspose.imaging/pointf/) представляет проверяемую точку. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible_point_f_graphics(pt, graphics) {#is_visible_point_f_graphics_pt_graphics_36}


```
 is_visible_point_f_graphics(pt, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Объект [PointF](/imaging/python-net/aspose.imaging/pointf/) представляет проверяемую точку. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри этого объекта; в противном случае — false. |


### Method: is_visible_point_graphics(pt, graphics) {#is_visible_point_graphics_pt_graphics_37}


```
 is_visible_point_graphics(pt, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pt | [Point](/imaging/python-net/aspose.imaging/point/) | Объект [Point](/imaging/python-net/aspose.imaging/point/) представляет проверяемую точку. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible_xy(x, y) {#is_visible_xy_x_y_38}


```
 is_visible_xy(x, y) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible_xy_graphics(x, y, graphics) {#is_visible_xy_graphics_x_y_graphics_39}


```
 is_visible_xy_graphics(x, y, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), используя указанный [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible_xyf(x, y) {#is_visible_xyf_x_y_40}


```
 is_visible_xyf(x, y) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: is_visible_xyf_graphics(x, y, graphics) {#is_visible_xyf_graphics_x_y_graphics_41}


```
 is_visible_xyf_graphics(x, y, graphics) 
```

Указывает, находится ли указанная точка внутри этого [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) в видимом области отсечения указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| graphics | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) для проверки видимости. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если указанная точка находится внутри данного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/); в противном случае — false. |


### Method: remove_figure(figure) {#remove_figure_figure_42}


```
 remove_figure(figure) 
```

Удаляет фигуру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figure | [Figure](/imaging/python-net/aspose.imaging/figure/) | Фигура для удаления. |

### Method: remove_figures(figures) {#remove_figures_figures_43}


```
 remove_figures(figures) 
```

Удаляет фигуры.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| figures | [Figure[]](/imaging/python-net/aspose.imaging/figure/) | Фигуры для удаления. |

### Method: transform(transform) {#transform_transform_44}


```
 transform(transform) 
```

Применяет указанное преобразование к форме.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Преобразование для применения. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_45}


```
 warp(dest_points, src_rect) 
```

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих параллелограмм, в который преобразуется прямоугольник, заданный _srcRect_. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Объект [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет прямоугольник, преобразуемый в параллелограмм, определённый _destPoints_. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_46}


```
 warp(dest_points, src_rect, matrix) 
```

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих параллелограмм, в который преобразуется прямоугольник, заданный _srcRect_. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Объект [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет прямоугольник, преобразуемый в параллелограмм, определённый _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Объект [Matrix](/imaging/python-net/aspose.imaging/matrix/) задаёт геометрическое преобразование, применяемое к пути. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_47}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих параллелограмм, в который преобразуется прямоугольник, заданный _srcRect_. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Объект [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет прямоугольник, преобразуемый в параллелограмм, определённый _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Объект [Matrix](/imaging/python-net/aspose.imaging/matrix/) задаёт геометрическое преобразование, применяемое к пути. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Перечисление [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) указывает, использует ли операция искажения перспективный или билинейный режим. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_48}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dest_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Массив структур [PointF](/imaging/python-net/aspose.imaging/pointf/), определяющих параллелограмм, в который преобразуется прямоугольник, заданный _srcRect_. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Объект [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) представляет прямоугольник, преобразуемый в параллелограмм, определённый _destPoints_. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Объект [Matrix](/imaging/python-net/aspose.imaging/matrix/) задаёт геометрическое преобразование, применяемое к пути. |
| warp_mode | [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Перечисление [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) указывает, использует ли операция искажения перспективный или билинейный режим. |
| flatness | float | Значение от 0 до 1, определяющее степень плоскости полученного пути. Для получения дополнительной информации см. методы [GraphicsPath.flatten()](/imaging/python-net/aspose.imaging/graphicspath/). |

### Method: widen(pen) {#widen_pen_49}


```
 widen(pen) 
```

Добавляет дополнительный контур к пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) задаёт ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |

### Method: widen(pen, matrix) {#widen_pen_matrix_50}


```
 widen(pen, matrix) 
```

Добавляет дополнительный контур к [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) задаёт ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Объект [Matrix](/imaging/python-net/aspose.imaging/matrix/) задаёт преобразование, применяемое к пути перед расширением. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_51}


```
 widen(pen, matrix, flatness) 
```

Заменяет этот [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) кривыми, которые охватывают область, заполняемую при отрисовке этого пути указанной ручкой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Объект [Pen](/imaging/python-net/aspose.imaging/pen/) задаёт ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Объект [Matrix](/imaging/python-net/aspose.imaging/matrix/) задаёт преобразование, применяемое к пути перед расширением. |
| плоскостность | float | Значение, определяющее степень плоскости кривых. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Создайте экземпляр файлового потока
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Создайте экземпляр TiffOptions и установите его различные свойства
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Установите источник для экземпляра ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Создайте экземпляр Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Создайте и инициализируйте экземпляр класса Graphics.
		graphics = Graphics(image)
		# Очистить поверхность Graphics.
		graphics.clear(Color.wheat);
		# Создайте экземпляр класса GraphicsPath
		graphics_path = GraphicsPath()
		# Создайте экземпляр класса Figure
		figure = Figure()
		# Добавьте формы в объект Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Добавьте объект Figure в GraphicsPath
		graphics_path.add_figure(figure)
		# Нарисуйте путь с объектом Pen цвета Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Сохраните все изменения.
		image.save()


```

### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#Создаёт экземпляр BmpOptions и устанавливает его различные свойства
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
	#Второй параметр типа Boolean определяет, будет ли создаваемый файл IsTemporal или нет
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Создайте экземпляр Image
	with Image.create(bmpOptions, 500, 500) as image:
		# Создайте и инициализируйте экземпляр класса Graphics.
		graphics = Graphics(image)
		# Очистить поверхность Graphics.
		graphics.clear(Color.wheat)
		# Создайте экземпляр класса GraphicsPath
		graphicspath = GraphicsPath()
		#Создайте экземпляр класса Figure
		figure1 = Figure()
		# Добавьте Shape в объект Figure
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Создайте экземпляр класса Figure
		figure2 = Figure()
		# Добавьте Shape в объект Figure
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Добавьте объект Figure в GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Нарисуйте путь с объектом Pen цвета Black
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# Сохраните все изменения.
		image.save()


```

