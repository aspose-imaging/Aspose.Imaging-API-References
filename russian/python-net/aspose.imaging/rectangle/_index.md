---
title: "Класс Rectangle"
type: docs
weight: 7120
url: /ru/python-net/aspose.imaging/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Rectangle

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Инициализирует новый экземпляр класса Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Инициализирует новый экземпляр структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) с указанным расположением и размером. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Инициализирует новый экземпляр структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) с указанным расположением и размером. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Получает или задает координату y, которая является суммой значений свойств [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/) и [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| empty [static] | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Возвращает новый экземпляр структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), у которой значения [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.y](/imaging/python-net/aspose.imaging/rectangle/), [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) и [Rectangle.height](/imaging/python-net/aspose.imaging/rectangle/) установлены в ноль. |
| height | int | r/w | Получает или задает высоту этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| is_empty | bool | r | Возвращает значение, указывающее, имеют ли все числовые свойства этой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) значение ноль. |
| left | int | r/w | Получает или задает координату x левой границы этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает координаты верхнего левого угла этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| right | int | r/w | Получает или задает координату x, которая является суммой значений свойств [Rectangle.x](/imaging/python-net/aspose.imaging/rectangle/) и [Rectangle.width](/imaging/python-net/aspose.imaging/rectangle/) этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Получает или задает размер этой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | r/w | Получает или задает координату y верхней границы этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| width | int | r/w | Получает или задает ширину этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| x | int | r/w | Получает или задает координату x верхнего левого угла этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| y | int | r/w | Получает или задает координату y верхнего левого угла этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Преобразует указанную структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) в структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) путем округления значений [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) до следующего большего целого числа. |
| [contains(point)](#contains_point_2) | Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains(rect)](#contains_rect_3) | Определяет, полностью ли прямоугольная область, представленная _rect_, содержится внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains_point(point)](#contains_point_point_5) | Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [contains_rect(rect)](#contains_rect_rect_6) | Определяет, полностью ли прямоугольная область, представленная _rect_, содержится внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_7) | Создает структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) с указанными позициями краев. |
| [from_points(point1, point2)](#from_points_point1_point2_8) | Создает новый [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) из двух указанных точек. Две вертикали созданного [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) будут равны переданным _point1_ и _point2_. Обычно это противоположные вершины. |
| [inflate(rect, x, y)](#inflate_rect_x_y_9) | Создает и возвращает расширенную копию указанной структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Копия расширяется на указанную величину. Исходная структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) остаётся неизменной. |
| [inflate(size)](#inflate_size_10) | Расширяет этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) на указанную величину. |
| [inflate(width, height)](#inflate_width_height_11) | Расширяет этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) на указанную величину. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_12) | Создает и возвращает расширенную копию указанной структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Копия расширяется на указанную величину. Исходная структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) остаётся неизменной. |
| [intersect(a, b)](#intersect_a_b_13) | Возвращает третью структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), представляющую пересечение двух других структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Если пересечения нет, возвращается пустой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [intersect(rect)](#intersect_rect_14) | Заменяет этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) пересечением его самого с указанным [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [intersect_rects(a, b)](#intersect_rects_a_b_15) | Возвращает третью структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), представляющую пересечение двух других структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Если пересечения нет, возвращается пустой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| [intersects_with(rect)](#intersects_with_rect_16) | Определяет, пересекается ли этот прямоугольник с _rect_. |
| normalize() | Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю сторону меньше нижней. |
| [offset(pos)](#offset_pos_17) | Корректирует положение этого прямоугольника на заданную величину. |
| [offset(x, y)](#offset_x_y_18) | Корректирует положение этого прямоугольника на заданную величину. |
| [round(value)](#round_value_19) | Преобразует указанную [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) в [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) путем округления значений [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) до ближайшего целого числа. |
| [truncate(value)](#truncate_value_20) | Преобразует указанную [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) в [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) путем усечения значений [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [union(a, b)](#union_a_b_21) | Получает структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), содержащую объединение двух структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Инициализирует новый экземпляр класса Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Инициализирует новый экземпляр структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) с указанным расположением и размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| location | [Point](/imaging/python-net/aspose.imaging/point/) | Точка [Point](/imaging/python-net/aspose.imaging/point/), представляющая верхний левый угол прямоугольной области. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Объект [Size](/imaging/python-net/aspose.imaging/size/), представляющий ширину и высоту прямоугольной области. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Инициализирует новый экземпляр структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) с указанным расположением и размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x верхнего левого угла прямоугольника. |
| y | int | Координата y верхнего левого угла прямоугольника. |
| width | int | Ширина прямоугольника. |
| height | int | Высота прямоугольника. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Преобразует указанную структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) в структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) путем округления значений [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) до следующего большего целого числа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Возвращает [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Точка [Point](/imaging/python-net/aspose.imaging/point/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, представленная _point_, содержится в этой структуре [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); иначе false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Определяет, полностью ли прямоугольная область, представленная _rect_, содержится внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Тестируемый [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если прямоугольный регион, представленный _rect_, полностью содержится в этой структуре [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); иначе false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, определённая _x_ и _y_, содержится в этой структуре [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); иначе false. |


### Method: contains_point(point) {#contains_point_point_5}


```
 contains_point(point) 
```

Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Точка [Point](/imaging/python-net/aspose.imaging/point/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, представленная _point_, содержится в этой структуре [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); иначе false. |


### Method: contains_rect(rect) {#contains_rect_rect_6}


```
 contains_rect(rect) 
```

Определяет, полностью ли прямоугольная область, представленная _rect_, содержится внутри этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Тестируемый [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если прямоугольный регион, представленный _rect_, полностью содержится в этой структуре [Rectangle](/imaging/python-net/aspose.imaging/rectangle/); иначе false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_7}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Создает структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) с указанными позициями краев.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| left | int | Координата x верхнего левого угла этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| top | int | Координата y верхнего левого угла этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| right | int | Координата x нижнего правого угла этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |
| bottom | int | Координата y нижнего правого угла этой структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Новый [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), создаваемый этим методом. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_8}


```
 from_points(point1, point2) 
```

Создает новый [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) из двух указанных точек. Две вертикали созданного [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) будут равны переданным _point1_ и _point2_. Обычно это противоположные вершины.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Первая [Point](/imaging/python-net/aspose.imaging/point/) для нового прямоугольника. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Вторая [Point](/imaging/python-net/aspose.imaging/point/) для нового прямоугольника. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Новосозданный [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_9}


```
 inflate(rect, x, y) 
```

Создает и возвращает расширенную копию указанной структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Копия расширяется на указанную величину. Исходная структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) остаётся неизменной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), с которым начинается. Этот прямоугольник не изменяется. |
| x | int | Величина, на которую нужно расширить этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) по горизонтали. |
| y | int | Величина, на которую нужно расширить этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) по вертикали. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Увеличенный [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(size) {#inflate_size_10}


```
 inflate(size) 
```

Расширяет этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Величина расширения этого прямоугольника. |

### Method: inflate(width, height) {#inflate_width_height_11}


```
 inflate(width, height) 
```

Расширяет этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Величина, на которую нужно расширить этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) по горизонтали. |
| height | int | Величина, на которую нужно расширить этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) по вертикали. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_12}


```
 inflate_rect(rect, x, y) 
```

Создает и возвращает расширенную копию указанной структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Копия расширяется на указанную величину. Исходная структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) остаётся неизменной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Исходный [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), с которым начинается. Этот прямоугольник не изменяется. |
| x | int | Величина, на которую нужно расширить этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) по горизонтали. |
| y | int | Величина, на которую нужно расширить этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) по вертикали. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Увеличенный [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_13}


```
 intersect(a, b) 
```

Возвращает третью структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), представляющую пересечение двух других структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Если пересечения нет, возвращается пустой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Первый прямоугольник для пересечения. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Второй прямоугольник для пересечения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), представляющий пересечение _a_ и _b_. |


### Method: intersect(rect) {#intersect_rect_14}


```
 intersect(rect) 
```

Заменяет этот [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) пересечением его самого с указанным [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), с которым выполнять пересечение. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_15}


```
 intersect_rects(a, b) 
```

Возвращает третью структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), представляющую пересечение двух других структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). Если пересечения нет, возвращается пустой [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Первый прямоугольник для пересечения. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Второй прямоугольник для пересечения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), представляющий пересечение _a_ и _b_. |


### Method: intersects_with(rect) {#intersects_with_rect_16}


```
 intersects_with(rect) 
```

Определяет, пересекается ли этот прямоугольник с _rect_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если существует какое-либо пересечение, иначе false. |


### Method: offset(pos) {#offset_pos_17}


```
 offset(pos) 
```

Корректирует положение этого прямоугольника на заданную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pos | [Point](/imaging/python-net/aspose.imaging/point/) | Величина смещения положения. |

### Method: offset(x, y) {#offset_x_y_18}


```
 offset(x, y) 
```

Корректирует положение этого прямоугольника на заданную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Горизонтальное смещение. |
| y | int | Вертикальное смещение. |

### Method: round(value)  [static] {#round_value_19}


```
 round(value) 
```

Преобразует указанную [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) в [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) путем округления значений [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) до ближайшего целого числа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), подлежащий конвертации. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Новый [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_20}


```
 truncate(value) 
```

Преобразует указанную [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) в [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) путем усечения значений [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), подлежащий конвертации. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Новый [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_21}


```
 union(a, b) 
```

Получает структуру [Rectangle](/imaging/python-net/aspose.imaging/rectangle/), содержащую объединение двух структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Первый прямоугольник для объединения. |
| b | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Второй прямоугольник для объединения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) структура, ограничивающая объединение двух структур [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


