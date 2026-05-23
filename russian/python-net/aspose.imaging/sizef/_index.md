---
title: "Класс SizeF"
type: docs
weight: 7290
url: /ru/python-net/aspose.imaging/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.SizeF

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SizeF()](#SizeF__1) | Инициализирует новый экземпляр класса SizeF |
| [SizeF(point)](#SizeF_point_2) | Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанной [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанного [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанных размеров. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Возвращает новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/), у которой значения [SizeF.width](/imaging/python-net/aspose.imaging/sizef/) и [SizeF.height](/imaging/python-net/aspose.imaging/sizef/) установлены в ноль. |
| height | float | r/w | Получает или задает вертикальную компоненту этого [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| is_empty | bool | r | Возвращает значение, указывающее, имеет ли этот [SizeF](/imaging/python-net/aspose.imaging/sizef/) нулевую ширину и высоту. |
| width | float | r/w | Получает или задает горизонтальную компоненту этого [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Добавляет ширину и высоту одной структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) к ширине и высоте другой структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [create_from_point_f(point)](#create_from_point_f_point_2) | Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанной [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [create_from_size_f(size)](#create_from_size_f_size_3) | Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанного [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Вычитает ширину и высоту одной структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из ширины и высоты другой структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| [to_point_f()](#to_point_f__5) | Преобразует [SizeF](/imaging/python-net/aspose.imaging/sizef/) в [PointF](/imaging/python-net/aspose.imaging/pointf/). |
| [to_size()](#to_size__6) | Преобразует [SizeF](/imaging/python-net/aspose.imaging/sizef/) в структуру [Size](/imaging/python-net/aspose.imaging/size/) с усечёнными значениями размеров. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Инициализирует новый экземпляр класса SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанной [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Объект [PointF](/imaging/python-net/aspose.imaging/pointf/) из которого инициализируется данный [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанного [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Объект [SizeF](/imaging/python-net/aspose.imaging/sizef/) из которого создаётся новый [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанных размеров.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | float | Компонента ширины нового [SizeF](/imaging/python-net/aspose.imaging/sizef/). |
| height | float | Компонента высоты нового [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Добавляет ширину и высоту одной структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) к ширине и высоте другой структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Первый [SizeF](/imaging/python-net/aspose.imaging/sizef/) для добавления. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Второй [SizeF](/imaging/python-net/aspose.imaging/sizef/) для добавления. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Структура [SizeF](/imaging/python-net/aspose.imaging/sizef/), являющаяся результатом операции сложения. |


### Method: create_from_point_f(point)  [static] {#create_from_point_f_point_2}


```
 create_from_point_f(point) 
```

Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанной [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Объект [PointF](/imaging/python-net/aspose.imaging/pointf/) из которого инициализируется данный [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: create_from_size_f(size)  [static] {#create_from_size_f_size_3}


```
 create_from_size_f(size) 
```

Инициализирует новый экземпляр структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из указанного [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Объект [SizeF](/imaging/python-net/aspose.imaging/sizef/) из которого создаётся новый [SizeF](/imaging/python-net/aspose.imaging/sizef/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) |  |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Вычитает ширину и высоту одной структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) из ширины и высоты другой структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size1 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Структура [SizeF](/imaging/python-net/aspose.imaging/sizef/) слева от оператора вычитания. |
| size2 | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Структура [SizeF](/imaging/python-net/aspose.imaging/sizef/) справа от оператора вычитания. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) являющийся результатом операции вычитания. |


### Method: to_point_f() {#to_point_f__5}


```
 to_point_f() 
```

Преобразует [SizeF](/imaging/python-net/aspose.imaging/sizef/) в [PointF](/imaging/python-net/aspose.imaging/pointf/).

**Returns**

| Тип | Описание |
| :- | :- |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Возвращает структуру [PointF](/imaging/python-net/aspose.imaging/pointf/). |


### Method: to_size() {#to_size__6}


```
 to_size() 
```

Преобразует [SizeF](/imaging/python-net/aspose.imaging/sizef/) в структуру [Size](/imaging/python-net/aspose.imaging/size/) с усечёнными значениями размеров.

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Возвращает структуру [Size](/imaging/python-net/aspose.imaging/size/). |


