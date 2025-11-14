---
title: ColorMatrix Class
type: docs
weight: 1180
url: /python-net/aspose.imaging/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorMatrix

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Initializes a new instance of the [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) class. |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Initializes a new instance of the [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) class using the elements in the specified matrix _newColorMatrix_. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | The number of matrix dimensions. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | The number of elements in matrix dimension. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | The total number of elements in the matrix. |
| matrix00 | float | r/w | Gets or sets the element at the 0 (zero) row and 0 column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix01 | float | r/w | Gets or sets the element at the 0 (zero) row and first column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix02 | float | r/w | Gets or sets the element at the 0 (zero) row and second column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix03 | float | r/w | Gets or sets the element at the 0 (zero) row and third column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix04 | float | r/w | Gets or sets the element at the 0 (zero) row and fourth column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix10 | float | r/w | Gets or sets the element at the first row and 0 (zero) column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix11 | float | r/w | Gets or sets the element at the first row and first column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix12 | float | r/w | Gets or sets the element at the first row and second column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix13 | float | r/w | Gets or sets the element at the first row and third column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix14 | float | r/w | Gets or sets the element at the first row and fourth column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix20 | float | r/w | Gets or sets the element at the second row and 0 (zero) column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix21 | float | r/w | Gets or sets the element at the second row and first column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix22 | float | r/w | Gets or sets the element at the second row and second column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix23 | float | r/w | Gets or sets the element at the second row and third column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix24 | float | r/w | Gets or sets the element at the second row and fourth column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix30 | float | r/w | Gets or sets the element at the third row and 0 (zero) column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix31 | float | r/w | Gets or sets the element at the third row and first column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix32 | float | r/w | Gets or sets the element at the third row and second column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix33 | float | r/w | Gets or sets the element at the third row and third column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix34 | float | r/w | Gets or sets the element at the third row and fourth column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix40 | float | r/w | Gets or sets the element at the fourth row and 0 (zero) column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix41 | float | r/w | Gets or sets the element at the fourth row and first column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix42 | float | r/w | Gets or sets the element at the fourth row and second column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix43 | float | r/w | Gets or sets the element at the fourth row and third column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix44 | float | r/w | Gets or sets the element at the fourth row and fourth column of this [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get(row, column)](#get_row_column_1) | Gets the element at the specified row and column in the [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [get_matrix()](#get_matrix__2) | Gets the matrix values. |
| [set(row, column, value)](#set_row_column_value_3) | Sets the element at the specified row and column in the [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Initializes a new instance of the [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) class.

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Initializes a new instance of the [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) class using the elements in the specified matrix _newColorMatrix_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_matrix | System.Single[] | The values of the elements for the new [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |

### Method: get(row, column) {#get_row_column_1}


```
 get(row, column) 
```

Gets the element at the specified row and column in the [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| row | int | The row number. |
| column | int | The column number. |

**Returns**

| Type | Description |
| :- | :- |
| float | The element at the specified row and column. |


### Method: get_matrix() {#get_matrix__2}


```
 get_matrix() 
```

Gets the matrix values.

**Returns**

| Type | Description |
| :- | :- |
| System.Single[] | The matrix values array. |


### Method: set(row, column, value) {#set_row_column_value_3}


```
 set(row, column, value) 
```

Sets the element at the specified row and column in the [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| row | int | The row number. |
| column | int | The column number. |
| value | float | The element at the specified row and column. |

