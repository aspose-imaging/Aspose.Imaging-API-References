---
title: "ColorMatrix 类"
type: docs
weight: 1180
url: /zh/python-net/aspose.imaging/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorMatrix

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | 初始化一个新的 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 类实例。 |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | 使用指定矩阵 _newColorMatrix_ 中的元素初始化一个新的 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | 矩阵维度的数量。 |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | 矩阵维度中元素的数量。 |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | 矩阵中元素的总数。 |
| matrix00 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第 0（零）行第 0 列的元素。 |
| matrix01 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第 0（零）行第一列的元素。 |
| matrix02 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第 0（零）行第二列的元素。 |
| matrix03 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第 0（零）行第三列的元素。 |
| matrix04 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第 0（零）行和第四列的元素。 |
| matrix10 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第一行和第 0（零）列的元素。 |
| matrix11 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第一行和第一列的元素。 |
| matrix12 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第一行和第二列的元素。 |
| matrix13 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第一行和第三列的元素。 |
| matrix14 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第一行和第四列的元素。 |
| matrix20 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第二行和第 0（零）列的元素。 |
| matrix21 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第二行和第一列的元素。 |
| matrix22 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第二行和第二列的元素。 |
| matrix23 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第二行和第三列的元素。 |
| matrix24 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第二行和第四列的元素。 |
| matrix30 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第三行和第 0（零）列的元素。 |
| matrix31 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第三行和第一列的元素。 |
| matrix32 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第三行和第二列的元素。 |
| matrix33 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第三行和第三列的元素。 |
| matrix34 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第三行和第四列的元素。 |
| matrix40 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第四行和第 0（零）列的元素。 |
| matrix41 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第四行和第一列的元素。 |
| matrix42 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第四行和第二列的元素。 |
| matrix43 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第四行和第三列的元素。 |
| matrix44 | float | r/w | 获取或设置此 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的第四行和第四列的元素。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get(row, column)](#get_row_column_1) | 获取 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 中指定行列的元素。 |
| [get_matrix()](#get_matrix__2) | 获取矩阵的值。 |
| [set(row, column, value)](#set_row_column_value_3) | 设置 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 中指定行列的元素。 |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

初始化一个新的 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 类实例。

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

使用指定矩阵 _newColorMatrix_ 中的元素初始化一个新的 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_matrix | System.Single[] | 新 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 的元素值。 |

### Method: get(row, column) {#get_row_column_1}


```
 get(row, column) 
```

获取 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 中指定行列的元素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 行 | int | 行号。 |
| 列 | int | 列号。 |

**Returns**

| Type | Description |
| :- | :- |
| float | 指定行和列处的元素。 |


### Method: get_matrix() {#get_matrix__2}


```
 get_matrix() 
```

获取矩阵的值。

**Returns**

| Type | Description |
| :- | :- |
| System.Single[] | 矩阵值数组。 |


### Method: set(row, column, value) {#set_row_column_value_3}


```
 set(row, column, value) 
```

设置 [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) 中指定行列的元素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 行 | int | 行号。 |
| 列 | int | 列号。 |
| value | float | 指定行和列处的元素。 |

