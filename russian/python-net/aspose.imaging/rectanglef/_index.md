---
title: "Класс RectangleF"
type: docs
weight: 7130
url: /ru/python-net/aspose.imaging/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RectangleF

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Инициализирует новый экземпляр класса RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Инициализирует новый экземпляр структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) с указанным расположением и размером. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Инициализирует новый экземпляр структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) с указанным расположением и размером. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | float | r/w | Получает или задает координату y, которая является суммой [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/) и [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| empty [static] | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получает новый экземпляр структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), у которой значения [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.y](/imaging/python-net/aspose.imaging/rectanglef/), [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) и [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) установлены в ноль. |
| height | float | r/w | Получает или задает высоту этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| is_empty | bool | r | Получает значение, указывающее, имеет ли свойство [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) или [RectangleF.height](/imaging/python-net/aspose.imaging/rectanglef/) этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) значение ноль. |
| left | float | r/w | Получает или задает координату x левой грани этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает координаты верхнего левого угла этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| right | float | r/w | Получает или задает координату x, которая является суммой [RectangleF.x](/imaging/python-net/aspose.imaging/rectanglef/) и [RectangleF.width](/imaging/python-net/aspose.imaging/rectanglef/) этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Получает или задает размер этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| top | float | r/w | Получает или задает координату y верхней грани этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| width | float | r/w | Получает или задает ширину этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) структуры. |
| x | float | r/w | Получает или задает координату x верхнего левого угла этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| y | float | r/w | Получает или задает координату y верхнего левого угла этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains(point)](#contains_point_1) | Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(rect)](#contains_rect_2) | Определяет, полностью ли прямоугольная область, представленная _rect_, содержится внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_point_f(point)](#contains_point_f_point_4) | Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [contains_rect_f(rect)](#contains_rect_f_rect_5) | Определяет, полностью ли прямоугольная область, представленная _rect_, содержится внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_6) | Создаёт структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) с верхним левым и нижним правым углом в указанных позициях. |
| [from_points(point1, point2)](#from_points_point1_point2_7) | Создаёт новый [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) из двух указанных точек. Две вершины созданного [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) будут равны переданным _point1_ и _point2_. Обычно это противоположные вершины. |
| [inflate(rect, x, y)](#inflate_rect_x_y_8) | Создаёт и возвращает увеличенную копию указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). Копия увеличивается на заданную величину. Исходный прямоугольник остаётся неизменным. |
| [inflate(size)](#inflate_size_9) | Увеличивает этот [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) на заданную величину. |
| [inflate(x, y)](#inflate_x_y_10) | Увеличивает эту структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) на заданную величину. |
| [inflate_rect(rect, x, y)](#inflate_rect_rect_x_y_11) | Создаёт и возвращает увеличенную копию указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). Копия увеличивается на заданную величину. Исходный прямоугольник остаётся неизменным. |
| [intersect(a, b)](#intersect_a_b_12) | Возвращает структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [intersect(rect)](#intersect_rect_13) | Заменяет эту структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) на пересечение её с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [intersect_rects(a, b)](#intersect_rects_a_b_14) | Возвращает структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [intersects_with(rect)](#intersects_with_rect_15) | Определяет, пересекается ли этот прямоугольник с _rect_. |
| normalize() | Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю сторону меньше нижней. |
| [offset(pos)](#offset_pos_16) | Корректирует положение этого прямоугольника на заданную величину. |
| [offset(x, y)](#offset_x_y_17) | Корректирует положение этого прямоугольника на заданную величину. |
| [union(a, b)](#union_a_b_18) | Создаёт наименьший возможный третий прямоугольник, который может содержать оба из двух прямоугольников, образующих объединение. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Инициализирует новый экземпляр класса RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Инициализирует новый экземпляр структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) с указанным расположением и размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| location | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/), представляющая верхний левый угол прямоугольной области. |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Объект [SizeF](/imaging/python-net/aspose.imaging/sizef/), представляющий ширину и высоту прямоугольной области. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Инициализирует новый экземпляр структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) с указанным расположением и размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x верхнего левого угла прямоугольника. |
| y | float | Координата y верхнего левого угла прямоугольника. |
| width | float | Ширина прямоугольника. |
| height | float | Высота прямоугольника. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, представленная параметром _point_, содержится внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); в противном случае — false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Определяет, полностью ли прямоугольная область, представленная _rect_, содержится внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если прямоугольная область, представленная _rect_, полностью содержится в прямоугольной области, представленной этим [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); иначе false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, определённая _x_ и _y_, содержится в этой структуре [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); иначе false. |


### Method: contains_point_f(point) {#contains_point_f_point_4}


```
 contains_point_f(point) 
```

Определяет, содержится ли указанная точка внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Точка [PointF](/imaging/python-net/aspose.imaging/pointf/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если точка, представленная параметром _point_, содержится внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); в противном случае — false. |


### Method: contains_rect_f(rect) {#contains_rect_f_rect_5}


```
 contains_rect_f(rect) 
```

Определяет, полностью ли прямоугольная область, представленная _rect_, содержится внутри этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если прямоугольная область, представленная _rect_, полностью содержится в прямоугольной области, представленной этим [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/); иначе false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_6}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Создаёт структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) с верхним левым и нижним правым углом в указанных позициях.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| лево | float | Координата x верхнего левого угла прямоугольной области. |
| верх | float | Координата y верхнего левого угла прямоугольной области. |
| право | float | Координата x нижнего правого угла прямоугольной области. |
| низ | float | Координата y нижнего правого угла прямоугольной области. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Новый [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), создаваемый этим методом. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_7}


```
 from_points(point1, point2) 
```

Создаёт новый [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) из двух указанных точек. Две вершины созданного [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) будут равны переданным _point1_ и _point2_. Обычно это противоположные вершины.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Первая [Point](/imaging/python-net/aspose.imaging/point/) для нового прямоугольника. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Вторая [Point](/imaging/python-net/aspose.imaging/point/) для нового прямоугольника. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Новосозданный [Rectangle](/imaging/python-net/aspose.imaging/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_8}


```
 inflate(rect, x, y) 
```

Создаёт и возвращает увеличенную копию указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). Копия увеличивается на заданную величину. Исходный прямоугольник остаётся неизменным.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), который будет скопирован. Этот прямоугольник не изменяется. |
| x | float | Величина расширения копии прямоугольника по горизонтали. |
| y | float | Величина расширения копии прямоугольника по вертикали. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Увеличенный [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: inflate(size) {#inflate_size_9}


```
 inflate(size) 
```

Увеличивает этот [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) на заданную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Величина расширения этого прямоугольника. |

### Method: inflate(x, y) {#inflate_x_y_10}


```
 inflate(x, y) 
```

Увеличивает эту структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) на заданную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Величина расширения этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) по горизонтали. |
| y | float | Величина расширения этой структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) по вертикали. |

### Method: inflate_rect(rect, x, y)  [static] {#inflate_rect_rect_x_y_11}


```
 inflate_rect(rect, x, y) 
```

Создаёт и возвращает увеличенную копию указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). Копия увеличивается на заданную величину. Исходный прямоугольник остаётся неизменным.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), который будет скопирован. Этот прямоугольник не изменяется. |
| x | float | Величина расширения копии прямоугольника по горизонтали. |
| y | float | Величина расширения копии прямоугольника по вертикали. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Увеличенный [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |


### Method: intersect(a, b)  [static] {#intersect_a_b_12}


```
 intersect(a, b) 
```

Возвращает структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Первый прямоугольник для пересечения. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Второй прямоугольник для пересечения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Третья структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), размер которой представляет собой площадь перекрытия двух указанных прямоугольников. |


### Method: intersect(rect) {#intersect_rect_13}


```
 intersect(rect) 
```

Заменяет эту структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) на пересечение её с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник для пересечения. |

### Method: intersect_rects(a, b)  [static] {#intersect_rects_a_b_14}


```
 intersect_rects(a, b) 
```

Возвращает структуру [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Первый прямоугольник для пересечения. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Второй прямоугольник для пересечения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Третья структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), размер которой представляет собой площадь перекрытия двух указанных прямоугольников. |


### Method: intersects_with(rect) {#intersects_with_rect_15}


```
 intersects_with(rect) 
```

Определяет, пересекается ли этот прямоугольник с _rect_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Прямоугольник для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Этот метод возвращает true, если существует какое-либо пересечение. |


### Method: offset(pos) {#offset_pos_16}


```
 offset(pos) 
```

Корректирует положение этого прямоугольника на заданную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pos | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Величина смещения положения. |

### Method: offset(x, y) {#offset_x_y_17}


```
 offset(x, y) 
```

Корректирует положение этого прямоугольника на заданную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Величина смещения положения по горизонтали. |
| y | float | Величина смещения положения по вертикали. |

### Method: union(a, b)  [static] {#union_a_b_18}


```
 union(a, b) 
```

Создаёт наименьший возможный третий прямоугольник, который может содержать оба из двух прямоугольников, образующих объединение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Первый прямоугольник для объединения. |
| b | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Второй прямоугольник для объединения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Третья структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), содержащая оба прямоугольника, образующие объединение. |


