---
title: "ColorMatrix"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define una matriz de 5 x 5 que contiene las coordenadas del espacio RGBA."
type: docs
weight: 26
url: /es/java/com.aspose.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Define una matriz de 5 x 5 que contiene las coordenadas del espacio RGBA. Varios métodos de la clase [ImageAttributes](../../com.aspose.imaging/imageattributes) ajustan los colores de la imagen usando una matriz de colores. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Inicializa una nueva instancia de la clase `Aspose.Imaging.ColorMatrix`. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Inicializa una nueva instancia de la clase `Aspose.Imaging.ColorMatrix` usando los elementos de la matriz especificada `newColorMatrix`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [MATRIX_DIMENSION_ELEMENTS_COUNT](#MATRIX-DIMENSION-ELEMENTS-COUNT) | El número de elementos en la dimensión de la matriz. |
| [MATRIX_DIMENSIONS_COUNT](#MATRIX-DIMENSIONS-COUNT) | El número de dimensiones de la matriz. |
| [MATRIX_TOTAL_ELEMENTS_COUNT](#MATRIX-TOTAL-ELEMENTS-COUNT) | El número total de elementos en la matriz. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Obtiene el elemento en la fila 0 (cero) y columna 0 de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix00(float value)](#setMatrix00-float-) | Establece el elemento en la fila 0 (cero) y columna 0 de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix01()](#getMatrix01--) | Obtiene el elemento en la fila 0 (cero) y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix01(float value)](#setMatrix01-float-) | Establece el elemento en la fila 0 (cero) y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix02()](#getMatrix02--) | Obtiene el elemento en la fila 0 (cero) y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix02(float value)](#setMatrix02-float-) | Establece el elemento en la fila 0 (cero) y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix03()](#getMatrix03--) | Obtiene el elemento en la fila 0 (cero) y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix03(float value)](#setMatrix03-float-) | Establece el elemento en la fila 0 (cero) y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix04()](#getMatrix04--) | Obtiene el elemento en la fila 0 (cero) y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix04(float value)](#setMatrix04-float-) | Establece el elemento en la fila 0 (cero) y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix10()](#getMatrix10--) | Obtiene el elemento en la primera fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix10(float value)](#setMatrix10-float-) | Establece el elemento en la primera fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix11()](#getMatrix11--) | Obtiene el elemento en la primera fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix11(float value)](#setMatrix11-float-) | Establece el elemento en la primera fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix12()](#getMatrix12--) | Obtiene el elemento en la primera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix12(float value)](#setMatrix12-float-) | Establece el elemento en la primera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix13()](#getMatrix13--) | Obtiene el elemento en la primera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix13(float value)](#setMatrix13-float-) | Establece el elemento en la primera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix14()](#getMatrix14--) | Obtiene el elemento en la primera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix14(float value)](#setMatrix14-float-) | Establece el elemento en la primera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix20()](#getMatrix20--) | Obtiene el elemento en la segunda fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix20(float value)](#setMatrix20-float-) | Establece el elemento en la segunda fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix21()](#getMatrix21--) | Obtiene el elemento en la segunda fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix21(float value)](#setMatrix21-float-) | Establece el elemento en la segunda fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix22()](#getMatrix22--) | Obtiene el elemento en la segunda fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix22(float value)](#setMatrix22-float-) | Establece el elemento en la segunda fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix23()](#getMatrix23--) | Obtiene el elemento en la segunda fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix23(float value)](#setMatrix23-float-) | Establece el elemento en la segunda fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix24()](#getMatrix24--) | Obtiene el elemento en la segunda fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix24(float value)](#setMatrix24-float-) | Establece el elemento en la segunda fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix30()](#getMatrix30--) | Obtiene el elemento en la tercera fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix30(float value)](#setMatrix30-float-) | Establece el elemento en la tercera fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix31()](#getMatrix31--) | Obtiene el elemento en la tercera fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix31(float value)](#setMatrix31-float-) | Establece el elemento en la tercera fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix32()](#getMatrix32--) | Obtiene el elemento en la tercera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix32(float value)](#setMatrix32-float-) | Establece el elemento en la tercera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix33()](#getMatrix33--) | Obtiene el elemento en la tercera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix33(float value)](#setMatrix33-float-) | Establece el elemento en la tercera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix34()](#getMatrix34--) | Obtiene el elemento en la tercera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix34(float value)](#setMatrix34-float-) | Establece el elemento en la tercera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix40()](#getMatrix40--) | Obtiene el elemento en la cuarta fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix40(float value)](#setMatrix40-float-) | Establece el elemento en la cuarta fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix41()](#getMatrix41--) | Obtiene el elemento en la cuarta fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | Establece el elemento en la cuarta fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Obtiene el elemento en la cuarta fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix42(float value)](#setMatrix42-float-) | Establece el elemento en la cuarta fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix43()](#getMatrix43--) | Obtiene el elemento en la cuarta fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix43(float value)](#setMatrix43-float-) | Establece el elemento en la cuarta fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |
| [getMatrix44()](#getMatrix44--) | Obtiene el elemento en la cuarta fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [setMatrix44(float value)](#setMatrix44-float-) | Establece el elemento en la cuarta fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Obtiene los valores de la matriz. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | newColorMatrix |
| [getMatrix()](#getMatrix--) | float[][] |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Inicializa una nueva instancia de la clase `Aspose.Imaging.ColorMatrix`.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Inicializa una nueva instancia de la clase `Aspose.Imaging.ColorMatrix` usando los elementos de la matriz especificada `newColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Los valores de los elementos para la nueva `Aspose.Imaging.ColorMatrix`. | float - El elemento en la fila 0 y columna 0 de este `Aspose.Imaging.ColorMatrix`. | El elemento en la fila 0 y columna 0 de este `Aspose.Imaging.ColorMatrix`. |

### MATRIX_DIMENSION_ELEMENTS_COUNT {#MATRIX-DIMENSION-ELEMENTS-COUNT}
```
public static final int MATRIX_DIMENSION_ELEMENTS_COUNT
```


El número de elementos en la dimensión de la matriz.

### MATRIX_DIMENSIONS_COUNT {#MATRIX-DIMENSIONS-COUNT}
```
public static final int MATRIX_DIMENSIONS_COUNT
```


El número de dimensiones de la matriz.

### MATRIX_TOTAL_ELEMENTS_COUNT {#MATRIX-TOTAL-ELEMENTS-COUNT}
```
public static final int MATRIX_TOTAL_ELEMENTS_COUNT
```


El número total de elementos en la matriz.

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Obtiene el elemento en la fila 0 (cero) y columna 0 de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la fila 0 y primera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Establece el elemento en la fila 0 (cero) y columna 0 de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la fila 0 y primera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Obtiene el elemento en la fila 0 (cero) y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la fila 0 y segunda columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Establece el elemento en la fila 0 (cero) y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la fila 0 y segunda columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Obtiene el elemento en la fila 0 (cero) y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la fila 0 y tercera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Establece el elemento en la fila 0 (cero) y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la fila 0 y tercera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Obtiene el elemento en la fila 0 (cero) y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la fila 0 y cuarta columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Establece el elemento en la fila 0 (cero) y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la fila 0 y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Obtiene el elemento en la fila 0 (cero) y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la primera fila y columna 0 de este `Aspose.Imaging.ColorMatrix`.
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Establece el elemento en la fila 0 (cero) y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la primera fila y columna 0 de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Obtiene el elemento en la primera fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la primera fila y primera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Establece el elemento en la primera fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la primera fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Obtiene el elemento en la primera fila y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la primera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Establece el elemento en la primera fila y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la primera fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Obtiene el elemento en la primera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la primera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Establece el elemento en la primera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la primera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Obtiene el elemento en la primera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la primera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Establece el elemento en la primera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la primera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Obtiene el elemento en la primera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la primera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Establece el elemento en la primera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la primera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Obtiene el elemento en la segunda fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la segunda fila y columna 0 de este `Aspose.Imaging.ColorMatrix`.
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Establece el elemento en la segunda fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la segunda fila y columna 0 de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Obtiene el elemento en la segunda fila y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la segunda fila y primera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Establece el elemento en la segunda fila y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la segunda fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Obtiene el elemento en la segunda fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la segunda fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Establece el elemento en la segunda fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la segunda fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Obtiene el elemento en la segunda fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la segunda fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Establece el elemento en la segunda fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la segunda fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Obtiene el elemento en la segunda fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la segunda fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Establece el elemento en la segunda fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la segunda fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Obtiene el elemento en la tercera fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la tercera fila y columna 0 de este `Aspose.Imaging.ColorMatrix`.
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Establece el elemento en la tercera fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la tercera fila y columna 0 de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Obtiene el elemento en la tercera fila y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la tercera fila y primera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Establece el elemento en la tercera fila y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la tercera fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Obtiene el elemento en la tercera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la tercera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Establece el elemento en la tercera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la tercera fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Obtiene el elemento en la tercera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la tercera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Establece el elemento en la tercera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la tercera fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Obtiene el elemento en la tercera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la tercera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Establece el elemento en la tercera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la tercera fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Obtiene el elemento en la cuarta fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la cuarta fila y columna 0 de este `Aspose.Imaging.ColorMatrix`.
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Establece el elemento en la cuarta fila y columna 0 (cero) de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la cuarta fila y columna 0 de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Obtiene el elemento en la cuarta fila y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la cuarta fila y primera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Establece el elemento en la cuarta fila y primera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la cuarta fila y primera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Obtiene el elemento en la cuarta fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la cuarta fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Establece el elemento en la cuarta fila y segunda columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la cuarta fila y segunda columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Obtiene el elemento en la cuarta fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la cuarta fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Establece el elemento en la cuarta fila y tercera columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la cuarta fila y tercera columna de este `Aspose.Imaging.ColorMatrix`. |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Obtiene el elemento en la cuarta fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - El elemento en la cuarta fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Establece el elemento en la cuarta fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El elemento en la cuarta fila y cuarta columna de este `Aspose.Imaging.ColorMatrix`. |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Obtiene los valores de la matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fila | int | El número de fila. |
| columna | int | El número de columna. |

**Returns:**
float - El elemento en la fila y columna especificadas.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


newColorMatrix

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fila | int | El número de fila. |
| columna | int | El número de columna. |
| valor | float | El valor |

### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


float[][]

**Returns:**
float[][] - El arreglo de valores de la matriz.
