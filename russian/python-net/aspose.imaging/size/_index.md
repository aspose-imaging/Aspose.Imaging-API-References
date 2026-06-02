---
title: "Класс Size"
type: docs
weight: 7280
url: /ru/python-net/aspose.imaging/size/
---

**Summary:** Represents size.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Size

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Size()](#Size__1) | Инициализирует новый экземпляр класса Size |
| [Size(point)](#Size_point_2) | Инициализирует новый экземпляр структуры [Size](/imaging/python-net/aspose.imaging/size/) из указанного [Point](/imaging/python-net/aspose.imaging/point/). |
| [Size(width, height)](#Size_width_height_3) | Инициализирует новый экземпляр структуры [Size](/imaging/python-net/aspose.imaging/size/) из указанных размеров. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Size](/imaging/python-net/aspose.imaging/size/) | r | Получает новый экземпляр структуры [Size](/imaging/python-net/aspose.imaging/size/), у которой значения [Size.width](/imaging/python-net/aspose.imaging/size/) и [Size.height](/imaging/python-net/aspose.imaging/size/) установлены в ноль. |
| height | int | r/w | Получает или задает вертикальную компоненту этого [Size](/imaging/python-net/aspose.imaging/size/). |
| is_empty | bool | r | Получает значение, указывающее, имеет ли этот [Size](/imaging/python-net/aspose.imaging/size/) ширину и высоту, равные 0. |
| width | int | r/w | Получает или задает горизонтальную компоненту этого [Size](/imaging/python-net/aspose.imaging/size/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Добавляет ширину и высоту одной структуры [Size](/imaging/python-net/aspose.imaging/size/) к ширине и высоте другой структуры [Size](/imaging/python-net/aspose.imaging/size/). |
| [ceiling(size)](#ceiling_size_2) | Преобразует указанную структуру [SizeF](/imaging/python-net/aspose.imaging/sizef/) в структуру [Size](/imaging/python-net/aspose.imaging/size/) путем округления значений структуры [Size](/imaging/python-net/aspose.imaging/size/) до следующего большего целого. |
| [round(size)](#round_size_3) | Преобразует указанную структуру [SizeF](/imaging/python-net/aspose.imaging/sizef/) в структуру [Size](/imaging/python-net/aspose.imaging/size/) путем округления значений структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) до ближайшего целого. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Вычитает ширину и высоту одной структуры [Size](/imaging/python-net/aspose.imaging/size/) из ширины и высоты другой структуры [Size](/imaging/python-net/aspose.imaging/size/). |
| [truncate(size)](#truncate_size_5) | Преобразует указанную структуру [SizeF](/imaging/python-net/aspose.imaging/sizef/) в структуру [Size](/imaging/python-net/aspose.imaging/size/) путем усечения значений структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) до следующего меньшего целого. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Инициализирует новый экземпляр класса Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Инициализирует новый экземпляр структуры [Size](/imaging/python-net/aspose.imaging/size/) из указанного [Point](/imaging/python-net/aspose.imaging/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Точка [Point](/imaging/python-net/aspose.imaging/point/) из которой инициализировать этот [Size](/imaging/python-net/aspose.imaging/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Инициализирует новый экземпляр структуры [Size](/imaging/python-net/aspose.imaging/size/) из указанных размеров.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Компонент ширины нового [Size](/imaging/python-net/aspose.imaging/size/). |
| height | int | Компонент высоты нового [Size](/imaging/python-net/aspose.imaging/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Добавляет ширину и высоту одной структуры [Size](/imaging/python-net/aspose.imaging/size/) к ширине и высоте другой структуры [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Первый [Size](/imaging/python-net/aspose.imaging/size/) для добавления. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Второй [Size](/imaging/python-net/aspose.imaging/size/) для добавления. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | [Size](/imaging/python-net/aspose.imaging/size/) структура, являющаяся результатом операции сложения. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Преобразует указанную структуру [SizeF](/imaging/python-net/aspose.imaging/sizef/) в структуру [Size](/imaging/python-net/aspose.imaging/size/) путем округления значений структуры [Size](/imaging/python-net/aspose.imaging/size/) до следующего большего целого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) структура для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | [Size](/imaging/python-net/aspose.imaging/size/) структура, в которую преобразует этот метод. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Преобразует указанную структуру [SizeF](/imaging/python-net/aspose.imaging/sizef/) в структуру [Size](/imaging/python-net/aspose.imaging/size/) путем округления значений структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) до ближайшего целого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) структура для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | [Size](/imaging/python-net/aspose.imaging/size/) структура, в которую преобразует этот метод. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Вычитает ширину и высоту одной структуры [Size](/imaging/python-net/aspose.imaging/size/) из ширины и высоты другой структуры [Size](/imaging/python-net/aspose.imaging/size/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size1 | [Size](/imaging/python-net/aspose.imaging/size/) | Структура [Size](/imaging/python-net/aspose.imaging/size/) слева от оператора вычитания. |
| size2 | [Size](/imaging/python-net/aspose.imaging/size/) | Структура [Size](/imaging/python-net/aspose.imaging/size/) справа от оператора вычитания. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | Структура [Size](/imaging/python-net/aspose.imaging/size/), являющаяся результатом операции вычитания. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Преобразует указанную структуру [SizeF](/imaging/python-net/aspose.imaging/sizef/) в структуру [Size](/imaging/python-net/aspose.imaging/size/) путем усечения значений структуры [SizeF](/imaging/python-net/aspose.imaging/sizef/) до следующего меньшего целого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | [SizeF](/imaging/python-net/aspose.imaging/sizef/) структура для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/imaging/python-net/aspose.imaging/size/) | [Size](/imaging/python-net/aspose.imaging/size/) структура, в которую преобразует этот метод. |


