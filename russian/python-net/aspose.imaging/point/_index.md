---
title: "Класс Point"
type: docs
weight: 6960
url: /ru/python-net/aspose.imaging/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Point

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Point()](#Point__1) | Создаёт новый экземпляр класса Point |
| [Point(dw)](#Point_dw_2) | Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) с использованием координат, заданных целочисленным значением. |
| [Point(size)](#Point_size_3) | Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) из структуры [Size](/imaging/python-net/aspose.imaging/size/). |
| [Point(x, y)](#Point_x_y_4) | Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) с указанными координатами. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Point](/imaging/python-net/aspose.imaging/point/) | r | Получает новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/), у которого значения [Point.x](/imaging/python-net/aspose.imaging/point/) и [Point.y](/imaging/python-net/aspose.imaging/point/) установлены в ноль. |
| is_empty | bool | r | Получает значение, указывающее, пустой ли этот [Point](/imaging/python-net/aspose.imaging/point/). |
| x | int | r/w | Получает или задаёт координату x этого [Point](/imaging/python-net/aspose.imaging/point/). |
| y | int | r/w | Получает или задаёт координату y этого [Point](/imaging/python-net/aspose.imaging/point/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Добавляет указанный [Size](/imaging/python-net/aspose.imaging/size/) к указанному [Point](/imaging/python-net/aspose.imaging/point/). |
| [ceiling(point)](#ceiling_point_2) | Преобразует указанный [PointF](/imaging/python-net/aspose.imaging/pointf/) в [Point](/imaging/python-net/aspose.imaging/point/), округляя значения [PointF](/imaging/python-net/aspose.imaging/pointf/) до следующего большего целого числа. |
| [create_from_d_word(dw)](#create_from_d_word_dw_3) | Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) с использованием координат, заданных целочисленным значением. |
| [create_from_size(size)](#create_from_size_size_4) | Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) из структуры [Size](/imaging/python-net/aspose.imaging/size/). |
| [from_long(packed_point, x, y)](#from_long_packed_point_x_y_5) | Разбирает объект Point, упакованный в long, на отдельные целочисленные значения X и Y. |
| [offset(dx, dy)](#offset_dx_dy_6) | Смещает этот [Point](/imaging/python-net/aspose.imaging/point/) на указанную величину. |
| [offset(point)](#offset_point_7) | Смещает этот [Point](/imaging/python-net/aspose.imaging/point/) на указанный [Point](/imaging/python-net/aspose.imaging/point/). |
| [round(point)](#round_point_8) | Преобразует указанный [PointF](/imaging/python-net/aspose.imaging/pointf/) в объект [Point](/imaging/python-net/aspose.imaging/point/), округляя значения [Point](/imaging/python-net/aspose.imaging/point/) до ближайшего целого числа. |
| [subtract(point, size)](#subtract_point_size_9) | Возвращает результат вычитания указанного [Size](/imaging/python-net/aspose.imaging/size/) из указанного [Point](/imaging/python-net/aspose.imaging/point/). |
| [to_long()](#to_long__10) | Преобразует этот Point в одно значение типа long, содержащее координаты X и Y в старших и младших битах. |
| [truncate(point)](#truncate_point_11) | Преобразует указанный [PointF](/imaging/python-net/aspose.imaging/pointf/) в [Point](/imaging/python-net/aspose.imaging/point/), отбрасывая значения [Point](/imaging/python-net/aspose.imaging/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Создаёт новый экземпляр класса Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) с использованием координат, заданных целочисленным значением.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dw | int | 32‑битное целое число, задающее координаты новой точки. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) из структуры [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Содержит координаты новой точки. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) с указанными координатами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Горизонтальное положение точки. |
| y | int | Вертикальное положение точки. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Добавляет указанный [Size](/imaging/python-net/aspose.imaging/size/) к указанному [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Точка [Point](/imaging/python-net/aspose.imaging/point/), к которой нужно добавить. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Размер [Size](/imaging/python-net/aspose.imaging/size/), который нужно добавить к _point_. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Точка [Point](/imaging/python-net/aspose.imaging/point/), являющаяся результатом операции сложения. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Преобразует указанный [PointF](/imaging/python-net/aspose.imaging/pointf/) в [Point](/imaging/python-net/aspose.imaging/point/), округляя значения [PointF](/imaging/python-net/aspose.imaging/pointf/) до следующего большего целого числа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Элемент [PointF](/imaging/python-net/aspose.imaging/pointf/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Элемент [Point](/imaging/python-net/aspose.imaging/point/), в который преобразует этот метод. |


### Method: create_from_d_word(dw)  [static] {#create_from_d_word_dw_3}


```
 create_from_d_word(dw) 
```

Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) с использованием координат, заданных целочисленным значением.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dw | int | 32‑битное целое число, задающее координаты новой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: create_from_size(size)  [static] {#create_from_size_size_4}


```
 create_from_size(size) 
```

Создаёт новый экземпляр структуры [Point](/imaging/python-net/aspose.imaging/point/) из структуры [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Содержит координаты новой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) |  |


### Method: from_long(packed_point, x, y)  [static] {#from_long_packed_point_x_y_5}


```
 from_long(packed_point, x, y) 
```

Разбирает объект Point, упакованный в long, на отдельные целочисленные значения X и Y.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| packed_point | int | Объект Point, упакованный в одно длинное значение. |
| x | int[] | Значение X, извлечённое из упакованного Point. |
| y | int[] | Значение Y, извлечённое из упакованного Point. |

### Method: offset(dx, dy) {#offset_dx_dy_6}


```
 offset(dx, dy) 
```

Смещает этот [Point](/imaging/python-net/aspose.imaging/point/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | int | Величина смещения координаты x. |
| dy | int | Величина смещения координаты y. |

### Method: offset(point) {#offset_point_7}


```
 offset(point) 
```

Смещает этот [Point](/imaging/python-net/aspose.imaging/point/) на указанный [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Элемент [Point](/imaging/python-net/aspose.imaging/point/), используемый для смещения этого [Point](/imaging/python-net/aspose.imaging/point/). |

### Method: round(point)  [static] {#round_point_8}


```
 round(point) 
```

Преобразует указанный [PointF](/imaging/python-net/aspose.imaging/pointf/) в объект [Point](/imaging/python-net/aspose.imaging/point/), округляя значения [Point](/imaging/python-net/aspose.imaging/point/) до ближайшего целого числа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Элемент [PointF](/imaging/python-net/aspose.imaging/pointf/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Элемент [Point](/imaging/python-net/aspose.imaging/point/), в который преобразует этот метод. |


### Method: subtract(point, size)  [static] {#subtract_point_size_9}


```
 subtract(point, size) 
```

Возвращает результат вычитания указанного [Size](/imaging/python-net/aspose.imaging/size/) из указанного [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Элемент [Point](/imaging/python-net/aspose.imaging/point/), из которого будет вычитаться. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Элемент [Size](/imaging/python-net/aspose.imaging/size/), из которого будет вычитаться _point_. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Элемент [Point](/imaging/python-net/aspose.imaging/point/), являющийся результатом операции вычитания. |


### Method: to_long() {#to_long__10}


```
 to_long() 
```

Преобразует этот Point в одно значение типа long, содержащее координаты X и Y в старших и младших битах.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Объект Point, упакованный в одно длинное значение. |


### Method: truncate(point)  [static] {#truncate_point_11}


```
 truncate(point) 
```

Преобразует указанный [PointF](/imaging/python-net/aspose.imaging/pointf/) в [Point](/imaging/python-net/aspose.imaging/point/), отбрасывая значения [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Элемент [PointF](/imaging/python-net/aspose.imaging/pointf/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Point](/imaging/python-net/aspose.imaging/point/) | Элемент [Point](/imaging/python-net/aspose.imaging/point/), в который преобразует этот метод. |


