---
title: "Класс ColorMatrix"
type: docs
weight: 1180
url: /ru/python-net/aspose.imaging/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorMatrix

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Инициализирует новый экземпляр класса [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Инициализирует новый экземпляр класса [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) с использованием элементов указанной матрицы _newColorMatrix_. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | Количество измерений матрицы. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | Количество элементов в измерении матрицы. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | Общее количество элементов в матрице. |
| matrix00 | float | r/w | Получает или задает элемент в 0‑й (ноль) строке и 0‑м столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix01 | float | r/w | Получает или задает элемент в 0‑й (ноль) строке и первом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix02 | float | r/w | Получает или задает элемент в 0‑й (ноль) строке и втором столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix03 | float | r/w | Получает или задает элемент в 0‑й (ноль) строке и третьем столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix04 | float | r/w | Получает или задает элемент в 0‑й (нулевой) строке и четвертом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix10 | float | r/w | Получает или задает элемент в первой строке и 0‑м (нулевом) столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix11 | float | r/w | Получает или задает элемент в первой строке и первом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix12 | float | r/w | Получает или задает элемент в первой строке и втором столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix13 | float | r/w | Получает или задает элемент в первой строке и третьем столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix14 | float | r/w | Получает или задает элемент в первой строке и четвертом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix20 | float | r/w | Получает или задает элемент во второй строке и 0‑м (нулевом) столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix21 | float | r/w | Получает или задает элемент во второй строке и первом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix22 | float | r/w | Получает или задает элемент во второй строке и втором столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix23 | float | r/w | Получает или задает элемент во второй строке и третьем столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix24 | float | r/w | Получает или задает элемент во второй строке и четвертом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix30 | float | r/w | Получает или задает элемент в третьей строке и 0‑м (нулевом) столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix31 | float | r/w | Получает или задает элемент в третьей строке и первом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix32 | float | r/w | Получает или задает элемент в третьей строке и втором столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix33 | float | r/w | Получает или задает элемент в третьей строке и третьем столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix34 | float | r/w | Получает или задает элемент в третьей строке и четвертом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix40 | float | r/w | Получает или задает элемент в четвертой строке и 0‑м (нулевом) столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix41 | float | r/w | Получает или задает элемент в четвертой строке и первом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix42 | float | r/w | Получает или задает элемент в четвертой строке и втором столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix43 | float | r/w | Получает или задает элемент в четвертой строке и третьем столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix44 | float | r/w | Получает или задает элемент в четвертой строке и четвертом столбце этой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get(row, column)](#get_row_column_1) | Получает элемент в указанной строке и столбце в [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [get_matrix()](#get_matrix__2) | Получает значения матрицы. |
| [set(row, column, value)](#set_row_column_value_3) | Задает элемент в указанной строке и столбце в [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Инициализирует новый экземпляр класса [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Инициализирует новый экземпляр класса [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) с использованием элементов указанной матрицы _newColorMatrix_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_matrix | System.Single[] | Значения элементов новой [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |

### Method: get(row, column) {#get_row_column_1}


```
 get(row, column) 
```

Получает элемент в указанной строке и столбце в [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| строка | int | Номер строки. |
| столбец | int | Номер столбца. |

**Returns**

| Тип | Описание |
| :- | :- |
| float | Элемент в указанной строке и столбце. |


### Method: get_matrix() {#get_matrix__2}


```
 get_matrix() 
```

Получает значения матрицы.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Single[] | Массив значений матрицы. |


### Method: set(row, column, value) {#set_row_column_value_3}


```
 set(row, column, value) 
```

Задает элемент в указанной строке и столбце в [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| строка | int | Номер строки. |
| столбец | int | Номер столбца. |
| значение | float | Элемент в указанной строке и столбце. |

