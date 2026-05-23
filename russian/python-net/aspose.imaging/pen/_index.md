---
title: "Класс Pen"
type: docs
weight: 6890
url: /ru/python-net/aspose.imaging/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанным [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |
| [Pen(brush, width)](#Pen_brush_width_2) | Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанными [Pen.brush](/imaging/python-net/aspose.imaging/pen/) и [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
| [Pen(color)](#Pen_color_3) | Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанным цветом. |
| [Pen(color, width)](#Pen_color_width_4) | Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанными свойствами [Pen.color](/imaging/python-net/aspose.imaging/pen/) и [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | r/w | Получает или задаёт выравнивание для этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | r/w | Получает или задаёт [Pen.brush](/imaging/python-net/aspose.imaging/pen/), определяющий атрибуты этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задаёт цвет этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| compound_array | float[] | r/w | Получает или задаёт массив значений, определяющих составное перо. Составное перо рисует составную линию, состоящую из параллельных линий и промежутков. |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Получает или задаёт пользовательскую насадку, используемую в конце линий, нарисованных этим [Pen](/imaging/python-net/aspose.imaging/pen/). |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Получает или задаёт пользовательскую насадку, используемую в начале линий, нарисованных этим [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | r/w | Получает или задаёт стиль насадки, используемый в конце штрихов, составляющих пунктирные линии, нарисованные этим [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_offset | float | r/w | Получает или задает расстояние от начала линии до начала шаблона штриха. |
| dash_pattern | float[] | r/w | Получает или задает массив пользовательских штрихов и пробелов. |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | r/w | Получает или задает стиль, используемый для пунктирных линий, нарисованных с помощью этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Получает или задает стиль окончания, используемый в конце линий, нарисованных с помощью этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Получает или задает стиль соединения для концов двух последовательных линий, нарисованных с помощью этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| miter_limit | float | r/w | Получает или задает предел толщины соединения на скошенном угле. |
| opacity | float | r/w | Получает или задает непрозрачность объекта. Значение должно быть от 0 до 1. Значение 0 означает, что объект полностью видим, значение 1 означает, что объект полностью непрозрачен. |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype/) | r | Получает стиль линий, нарисованных с помощью этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Получает или задает стиль окончания, используемый в начале линий, нарисованных с помощью этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает копию геометрического преобразования для этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | r/w | Получает или задает ширину этого [Pen](/imaging/python-net/aspose.imaging/pen/), в единицах объекта Graphics, используемого для рисования. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_brush(brush)](#create_with_brush_brush_1) | Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанным [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_2) | Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанными [Pen.brush](/imaging/python-net/aspose.imaging/pen/) и [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
| [create_with_color(color)](#create_with_color_color_3) | Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанным цветом. |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_4) | Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанными свойствами [Pen.color](/imaging/python-net/aspose.imaging/pen/) и [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_5) | Умножает матрицу преобразования для этого [Pen](/imaging/python-net/aspose.imaging/pen/) на указанную [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_6) | Умножает матрицу преобразования для этого [Pen](/imaging/python-net/aspose.imaging/pen/) на указанную [Matrix](/imaging/python-net/aspose.imaging/matrix/) в заданном порядке. |
| reset_transform() | Сбрасывает матрицу геометрического преобразования для этого [Pen](/imaging/python-net/aspose.imaging/pen/) к единичной. |
| [rotate_transform(angle)](#rotate_transform_angle_7) | Вращает локальное геометрическое преобразование на указанный угол. Этот метод добавляет вращение в начало преобразования. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_8) | Вращает локальное геометрическое преобразование на указанный угол в заданном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_9) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод добавляет матрицу масштабирования в начало преобразования. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_10) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в заданном порядке. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_11) | Устанавливает значения, определяющие стиль окончания, используемый для завершения линий, нарисованных этим [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Перемещает локальное геометрическое преобразование на указанные размеры в заданном порядке. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанным [Pen.brush](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Объект [Pen.brush](/imaging/python-net/aspose.imaging/pen/), определяющий свойства заливки этого [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанными [Pen.brush](/imaging/python-net/aspose.imaging/pen/) и [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Объект [Pen.brush](/imaging/python-net/aspose.imaging/pen/), определяющий характеристики этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Ширина нового [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанным цветом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Pen.color](/imaging/python-net/aspose.imaging/pen/), указывающая цвет этого [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанными свойствами [Pen.color](/imaging/python-net/aspose.imaging/pen/) и [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Pen.color](/imaging/python-net/aspose.imaging/pen/), указывающая цвет этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Значение, указывающее ширину этого [Pen](/imaging/python-net/aspose.imaging/pen/). |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: create_with_brush(brush)  [static] {#create_with_brush_brush_1}


```
 create_with_brush(brush) 
```

Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанным [Pen.brush](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Объект [Pen.brush](/imaging/python-net/aspose.imaging/pen/), определяющий свойства заливки этого [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_2}


```
 create_with_brush_width(brush, width) 
```

Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанными [Pen.brush](/imaging/python-net/aspose.imaging/pen/) и [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Объект [Pen.brush](/imaging/python-net/aspose.imaging/pen/), определяющий характеристики этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Ширина нового [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color(color)  [static] {#create_with_color_color_3}


```
 create_with_color(color) 
```

Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанным цветом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Pen.color](/imaging/python-net/aspose.imaging/pen/), указывающая цвет этого [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_4}


```
 create_with_color_width(color, width) 
```

Инициализирует новый экземпляр класса [Pen](/imaging/python-net/aspose.imaging/pen/) с указанными свойствами [Pen.color](/imaging/python-net/aspose.imaging/pen/) и [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Структура [Pen.color](/imaging/python-net/aspose.imaging/pen/), указывающая цвет этого [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Значение, указывающее ширину этого [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_5}


```
 multiply_transform(matrix) 
```

Умножает матрицу преобразования для этого [Pen](/imaging/python-net/aspose.imaging/pen/) на указанную [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Объект [Matrix](/imaging/python-net/aspose.imaging/matrix/), с помощью которого умножать матрицу преобразования. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_6}


```
 multiply_transform(matrix, order) 
```

Умножает матрицу преобразования для этого [Pen](/imaging/python-net/aspose.imaging/pen/) на указанную [Matrix](/imaging/python-net/aspose.imaging/matrix/) в заданном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | [Matrix](/imaging/python-net/aspose.imaging/matrix/), с помощью которого умножать матрицу преобразования. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок, в котором выполнять операцию умножения. |

### Method: rotate_transform(angle) {#rotate_transform_angle_7}


```
 rotate_transform(angle) 
```

Вращает локальное геометрическое преобразование на указанный угол. Этот метод добавляет вращение в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_8}


```
 rotate_transform(angle, order) 
```

Вращает локальное геометрическое преобразование на указанный угол в заданном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Структура [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/), указывающая, следует ли добавить в конец или в начало матрицу вращения. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_9}


```
 scale_transform(sx, sy) 
```

Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Коэффициент, на который масштабировать преобразование по оси x. |
| sy | float | Коэффициент, на который масштабировать преобразование по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_10}


```
 scale_transform(sx, sy, order) 
```

Масштабирует локальное геометрическое преобразование на указанные коэффициенты в заданном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Коэффициент, на который масштабировать преобразование по оси x. |
| sy | float | Коэффициент, на который масштабировать преобразование по оси y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Тип [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) который указывает, добавлять или предварять матрицу масштабирования. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_11}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Устанавливает значения, определяющие стиль окончания, используемый для завершения линий, нарисованных этим [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Объект [LineCap](/imaging/python-net/aspose.imaging/linecap/), представляющий стиль окончания, используемый в начале линий, нарисованных этим [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Объект [LineCap](/imaging/python-net/aspose.imaging/linecap/), представляющий стиль окончания, используемый в конце линий, нарисованных этим [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Объект [LineCap](/imaging/python-net/aspose.imaging/linecap/), представляющий стиль окончания, используемый в начале или в конце пунктирных линий, нарисованных этим [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Перемещает локальное геометрическое преобразование на указанные размеры в заданном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Порядок (предварительно или последовательно), в котором применяется трансляция. |

## **Examples**
### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Создайте экземпляр BmpOptions и задайте его различные свойства
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
# Второй параметр типа Boolean определяет, будет ли создаваемый файл IsTemporal или нет
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Создайте экземпляр Image по указанному пути
with Image.create(bmpOptions, 500, 500) as image:
	# Создайте экземпляр Graphics и инициализируйте его объектом Image
	graphics = Graphics(image)
	# Очистите поверхность Graphics белым цветом
	graphics.clear(Color.white)
	#Создайте экземпляр Pen с красным цветом и шириной 5
	pen = Pen(Color.red, 5.0);
	# Создайте экземпляр HatchBrush и задайте его свойства
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Создайте экземпляр Pen
	# инициализировать его объектом HatchBrush и шириной
	brusedpen = Pen(brush, 5.0)
	# Рисовать прямоугольники, указывая объект Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Рисовать прямоугольники, указывая объект Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# Сохраните все изменения.
	image.save()


```

