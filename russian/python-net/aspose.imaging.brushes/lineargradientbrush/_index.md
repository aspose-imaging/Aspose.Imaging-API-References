---
title: "Класс LinearGradientBrush"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) с параметрами по умолчанию.<br/>            Начальный цвет — чёрный, конечный цвет — белый, угол — 45 градусов, а прямоугольник расположен в (0,0) с размером (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| угол | float | r/w | Получает или задает угол градиента. |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Получает или задает объект [Blend](/imaging/python-net/aspose.imaging/blend/), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| end_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает конечный цвет градиента. |
| gamma_correction | bool | r/w | Получает или задает значение, указывающее, включена ли коррекция гаммы для этого [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Получает или задает объект [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/), определяющий многокрасочный линейный градиент. |
| is_angle_scalable | bool | r/w | Получает или задает значение, указывающее, изменяется ли [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) во время преобразований с этим [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. Например, установка матрицы преобразования или<br/>            вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| linear_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает начальные и конечные цвета градиента. |
| opacity | float | r/w | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает прямоугольную область, определяющую начальные и конечные точки градиента. |
| start_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает начальный цвет градиента. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает копию [Matrix](/imaging/python-net/aspose.imaging/matrix/), определяющую локальное геометрическое преобразование для этого [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Получает или задает перечисление [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), которое указывает режим обтекания для этого [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_points(point1, point2, color1, color2)](#create_with_points_point1_point2_color1_color2_1) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) с указанными точками и цветами. |
| [create_with_points_f(point1, point2, color1, color2)](#create_with_points_f_point1_point2_color1_color2_2) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) с указанными точками и цветами. |
| [create_with_rect_colors_angle(rect, color1, color2, angle)](#create_with_rect_colors_angle_rect_color1_color2_angle_3) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [create_with_rect_f_colors_angle(rect, color1, color2, angle)](#create_with_rect_f_colors_angle_rect_color1_color2_angle_5) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6) | Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [deep_clone()](#deep_clone__7) | Создает новый глубокий клон текущего [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) путем предварительного добавления указанного [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) в указанном порядке. |
| reset_transform() | Сбрасывает свойство [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) к единичному. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Вращает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Вращает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод предварительно добавляет матрицу масштабирования к преобразованию. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_14) | Создаёт линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_15) | Создаёт линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_16) | Создаёт затухание градиента, основанное на колоколообразной кривой. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_17) | Создаёт затухание градиента, основанное на колоколообразной кривой. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_18) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_19) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) с параметрами по умолчанию.<br/>            Начальный цвет — чёрный, конечный цвет — белый, угол — 45 градусов, а прямоугольник расположен в (0,0) с размером (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка1. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет2. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Точка1. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Точка2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет2. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет2. |
| угол | float | Угол. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет2. |
| угол | float | Угол. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет2. |
| угол | float | Угол. |
| is_angle_scalable | bool | если установлено <c>true</c> [is angle scalable]. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет2. |
| угол | float | Угол. |
| is_angle_scalable | bool | если установлено <c>true</c> [is angle scalable]. |

### Method: create_with_points(point1, point2, color1, color2)  [static] {#create_with_points_point1_point2_color1_color2_1}


```
 create_with_points(point1, point2, color1, color2) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) с указанными точками и цветами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [Point](/imaging/python-net/aspose.imaging/point/) представляющая начальную точку линейного градиента. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [Point](/imaging/python-net/aspose.imaging/point/) представляющая конечную точку линейного градиента. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая начальный цвет линейного градиента. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая конечный цвет линейного градиента. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_points_f(point1, point2, color1, color2)  [static] {#create_with_points_f_point1_point2_color1_color2_2}


```
 create_with_points_f(point1, point2, color1, color2) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) с указанными точками и цветами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) представляющая начальную точку линейного градиента. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) представляющая конечную точку линейного градиента. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая начальный цвет линейного градиента. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая конечный цвет линейного градиента. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_colors_angle_rect_color1_color2_angle_3}


```
 create_with_rect_colors_angle(rect, color1, color2, angle) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) определяющая границы линейного градиента. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая начальный цвет градиента. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4}


```
 create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) определяющая границы линейного градиента. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая начальный цвет градиента. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |
| is_angle_scalable | bool | если установлено <c>true</c> угол изменяется во время преобразований с помощью этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_f_colors_angle_rect_color1_color2_angle_5}


```
 create_with_rect_f_colors_angle(rect, color1, color2, angle) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) определяющая границы линейного градиента. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая начальный цвет градиента. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6}


```
 create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Инициализирует новый экземпляр класса [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) определяющая границы линейного градиента. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая начальный цвет градиента. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Color](/imaging/python-net/aspose.imaging/color/) представляющая конечный цвет градиента. |
| угол | float | Угол, измеряемый в градусах по часовой стрелке от оси x, линии ориентации градиента. |
| is_angle_scalable | bool | если установлено <c>true</c> угол изменяется во время преобразований с помощью этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: deep_clone() {#deep_clone__7}


```
 deep_clone() 
```

Создает новый глубокий клон текущего [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Новый [Brush](/imaging/python-net/aspose.imaging/brush/), который является глубоким клоном этого экземпляра [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_8}


```
 multiply_transform(matrix) 
```

Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) путем предварительного добавления указанного [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), на которую следует умножить геометрическое преобразование. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_9}


```
 multiply_transform(matrix, order) 
```

Умножает [Matrix](/imaging/python-net/aspose.imaging/matrix/), представляющий локальное геометрическое преобразование этого [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/), на указанный [Matrix](/imaging/python-net/aspose.imaging/matrix/) в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/), на которую следует умножить геометрическое преобразование. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Структура [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), указывающая порядок умножения двух матриц. |

### Method: rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

Вращает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

Вращает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Структура [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), указывающая, следует ли добавить в конец или в начало матрицу вращения. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_12}


```
 scale_transform(sx, sy) 
```

Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод предварительно добавляет матрицу масштабирования к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_13}


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_14}


```
 set_blend_triangular_shape(focus) 
```

Создаёт линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_15}


```
 set_blend_triangular_shape(focus, scale) 
```

Создаёт линейный градиент с центральным цветом и линейным затуханием к единому цвету на обоих концах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| масштаб | float | Значение от 0 до 1, указывающее, насколько быстро цвета переходят от начального цвета к _focus_ (конечному цвету) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_16}


```
 set_sigma_bell_shape(focus) 
```

Создаёт затухание градиента, основанное на колоколообразной кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где начальный и конечный цвета смешаны поровну). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_17}


```
 set_sigma_bell_shape(focus, scale) 
```

Создаёт затухание градиента, основанное на колоколообразной кривой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| фокус | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| масштаб | float | Значение от 0 до 1, указывающее, насколько быстро цвета переходят от _focus_. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_18}


```
 translate_transform(dx, dy) 
```

Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_19}


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

