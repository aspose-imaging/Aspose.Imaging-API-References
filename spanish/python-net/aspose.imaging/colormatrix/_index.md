---
title: "Clase ColorMatrix"
type: docs
weight: 1180
url: /es/python-net/aspose.imaging/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorMatrix

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Inicializa una nueva instancia de la clase [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Inicializa una nueva instancia de la clase [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) usando los elementos de la matriz especificada _newColorMatrix_. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | El número de dimensiones de la matriz. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | El número de elementos en la dimensión de la matriz. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | El número total de elementos en la matriz. |
| matrix00 | float | r/w | Obtiene o establece el elemento en la fila 0 (cero) y columna 0 de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix01 | float | r/w | Obtiene o establece el elemento en la fila 0 (cero) y primera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix02 | float | r/w | Obtiene o establece el elemento en la fila 0 (cero) y segunda columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix03 | float | r/w | Obtiene o establece el elemento en la fila 0 (cero) y tercera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix04 | float | r/w | Obtiene o establece el elemento en la fila 0 (cero) y la cuarta columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix10 | float | r/w | Obtiene o establece el elemento en la primera fila y la columna 0 (cero) de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix11 | float | r/w | Obtiene o establece el elemento en la primera fila y la primera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix12 | float | r/w | Obtiene o establece el elemento en la primera fila y la segunda columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix13 | float | r/w | Obtiene o establece el elemento en la primera fila y la tercera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix14 | float | r/w | Obtiene o establece el elemento en la primera fila y la cuarta columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix20 | float | r/w | Obtiene o establece el elemento en la segunda fila y la columna 0 (cero) de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix21 | float | r/w | Obtiene o establece el elemento en la segunda fila y la primera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix22 | float | r/w | Obtiene o establece el elemento en la segunda fila y la segunda columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix23 | float | r/w | Obtiene o establece el elemento en la segunda fila y la tercera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix24 | float | r/w | Obtiene o establece el elemento en la segunda fila y la cuarta columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix30 | float | r/w | Obtiene o establece el elemento en la tercera fila y la columna 0 (cero) de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix31 | float | r/w | Obtiene o establece el elemento en la tercera fila y la primera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix32 | float | r/w | Obtiene o establece el elemento en la tercera fila y la segunda columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix33 | float | r/w | Obtiene o establece el elemento en la tercera fila y la tercera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix34 | float | r/w | Obtiene o establece el elemento en la tercera fila y la cuarta columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix40 | float | r/w | Obtiene o establece el elemento en la cuarta fila y la columna 0 (cero) de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix41 | float | r/w | Obtiene o establece el elemento en la cuarta fila y la primera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix42 | float | r/w | Obtiene o establece el elemento en la cuarta fila y la segunda columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix43 | float | r/w | Obtiene o establece el elemento en la cuarta fila y la tercera columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| matrix44 | float | r/w | Obtiene o establece el elemento en la cuarta fila y la cuarta columna de este [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get(row, column)](#get_row_column_1) | Obtiene el elemento en la fila y columna especificadas del [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |
| [get_matrix()](#get_matrix__2) | Obtiene los valores de la matriz. |
| [set(row, column, value)](#set_row_column_value_3) | Establece el elemento en la fila y columna especificadas del [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Inicializa una nueva instancia de la clase [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Inicializa una nueva instancia de la clase [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) usando los elementos de la matriz especificada _newColorMatrix_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_matrix | System.Single[] | Los valores de los elementos para la nueva [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/). |

### Method: get(row, column) {#get_row_column_1}


```
 get(row, column) 
```

Obtiene el elemento en la fila y columna especificadas del [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fila | int | El número de fila. |
| columna | int | El número de columna. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El elemento en la fila y columna especificadas. |


### Method: get_matrix() {#get_matrix__2}


```
 get_matrix() 
```

Obtiene los valores de la matriz.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Single[] | El array de valores de la matriz. |


### Method: set(row, column, value) {#set_row_column_value_3}


```
 set(row, column, value) 
```

Establece el elemento en la fila y columna especificadas del [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fila | int | El número de fila. |
| columna | int | El número de columna. |
| valor | float | El elemento en la fila y columna especificadas. |

