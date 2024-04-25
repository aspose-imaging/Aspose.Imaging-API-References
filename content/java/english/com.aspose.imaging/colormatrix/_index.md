---
title: ColorMatrix
second_title: Aspose.Imaging for Java API Reference
description: Defines a 5 x 5 matrix that contains the coordinates for the RGBA space.
type: docs
weight: 26
url: /com.aspose.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](../../com.aspose.imaging/imageattributes) class adjust image colors by using a color matrix. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initializes a new instance of the `Aspose.Imaging.ColorMatrix` class. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initializes a new instance of the `Aspose.Imaging.ColorMatrix` class using the elements in the specified matrix `newColorMatrix`. |
## Fields

| Field | Description |
| --- | --- |
| [MATRIX_DIMENSION_ELEMENTS_COUNT](#MATRIX-DIMENSION-ELEMENTS-COUNT) | The number of elements in matrix dimension. |
| [MATRIX_DIMENSIONS_COUNT](#MATRIX-DIMENSIONS-COUNT) | The number of matrix dimensions. |
| [MATRIX_TOTAL_ELEMENTS_COUNT](#MATRIX-TOTAL-ELEMENTS-COUNT) | The total number of elements in the matrix. |
## Methods

| Method | Description |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Gets the element at the 0 (zero) row and 0 column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix00(float value)](#setMatrix00-float-) | Sets the element at the 0 (zero) row and 0 column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix01()](#getMatrix01--) | Gets the element at the 0 (zero) row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix01(float value)](#setMatrix01-float-) | Sets the element at the 0 (zero) row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix02()](#getMatrix02--) | Gets the element at the 0 (zero) row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix02(float value)](#setMatrix02-float-) | Sets the element at the 0 (zero) row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix03()](#getMatrix03--) | Gets the element at the 0 (zero) row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix03(float value)](#setMatrix03-float-) | Sets the element at the 0 (zero) row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix04()](#getMatrix04--) | Gets the element at the 0 (zero) row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix04(float value)](#setMatrix04-float-) | Sets the element at the 0 (zero) row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix10()](#getMatrix10--) | Gets the element at the first row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix10(float value)](#setMatrix10-float-) | Sets the element at the first row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix11()](#getMatrix11--) | Gets the element at the first row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix11(float value)](#setMatrix11-float-) | Sets the element at the first row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix12()](#getMatrix12--) | Gets the element at the first row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix12(float value)](#setMatrix12-float-) | Sets the element at the first row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix13()](#getMatrix13--) | Gets the element at the first row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix13(float value)](#setMatrix13-float-) | Sets the element at the first row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix14()](#getMatrix14--) | Gets the element at the first row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix14(float value)](#setMatrix14-float-) | Sets the element at the first row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix20()](#getMatrix20--) | Gets the element at the second row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix20(float value)](#setMatrix20-float-) | Sets the element at the second row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix21()](#getMatrix21--) | Gets the element at the second row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix21(float value)](#setMatrix21-float-) | Sets the element at the second row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix22()](#getMatrix22--) | Gets the element at the second row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix22(float value)](#setMatrix22-float-) | Sets the element at the second row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix23()](#getMatrix23--) | Gets the element at the second row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix23(float value)](#setMatrix23-float-) | Sets the element at the second row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix24()](#getMatrix24--) | Gets the element at the second row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix24(float value)](#setMatrix24-float-) | Sets the element at the second row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix30()](#getMatrix30--) | Gets the element at the third row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix30(float value)](#setMatrix30-float-) | Sets the element at the third row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix31()](#getMatrix31--) | Gets the element at the third row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix31(float value)](#setMatrix31-float-) | Sets the element at the third row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix32()](#getMatrix32--) | Gets the element at the third row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix32(float value)](#setMatrix32-float-) | Sets the element at the third row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix33()](#getMatrix33--) | Gets the element at the third row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix33(float value)](#setMatrix33-float-) | Sets the element at the third row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix34()](#getMatrix34--) | Gets the element at the third row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix34(float value)](#setMatrix34-float-) | Sets the element at the third row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix40()](#getMatrix40--) | Gets the element at the fourth row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix40(float value)](#setMatrix40-float-) | Sets the element at the fourth row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix41()](#getMatrix41--) | Gets the element at the fourth row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | Sets the element at the fourth row and first column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Gets the element at the fourth row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix42(float value)](#setMatrix42-float-) | Sets the element at the fourth row and second column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix43()](#getMatrix43--) | Gets the element at the fourth row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix43(float value)](#setMatrix43-float-) | Sets the element at the fourth row and third column of this `Aspose.Imaging.ColorMatrix`. |
| [getMatrix44()](#getMatrix44--) | Gets the element at the fourth row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [setMatrix44(float value)](#setMatrix44-float-) | Sets the element at the fourth row and fourth column of this `Aspose.Imaging.ColorMatrix`. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Gets the element at the specified row and column in the `Aspose.Imaging.ColorMatrix`. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Sets the element at the specified row and column in the `Aspose.Imaging.ColorMatrix`. |
| [getMatrix()](#getMatrix--) | Gets the matrix values. |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initializes a new instance of the `Aspose.Imaging.ColorMatrix` class.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initializes a new instance of the `Aspose.Imaging.ColorMatrix` class using the elements in the specified matrix `newColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | float[][] | The values of the elements for the new `Aspose.Imaging.ColorMatrix`. |

### MATRIX_DIMENSION_ELEMENTS_COUNT {#MATRIX-DIMENSION-ELEMENTS-COUNT}
```
public static final int MATRIX_DIMENSION_ELEMENTS_COUNT
```


The number of elements in matrix dimension.

### MATRIX_DIMENSIONS_COUNT {#MATRIX-DIMENSIONS-COUNT}
```
public static final int MATRIX_DIMENSIONS_COUNT
```


The number of matrix dimensions.

### MATRIX_TOTAL_ELEMENTS_COUNT {#MATRIX-TOTAL-ELEMENTS-COUNT}
```
public static final int MATRIX_TOTAL_ELEMENTS_COUNT
```


The total number of elements in the matrix.

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Gets the element at the 0 (zero) row and 0 column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the 0 row and 0 column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Sets the element at the 0 (zero) row and 0 column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the 0 row and 0 column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Gets the element at the 0 (zero) row and first column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the 0 row and first column of this `Aspose.Imaging.ColorMatrix` .
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Sets the element at the 0 (zero) row and first column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the 0 row and first column of this `Aspose.Imaging.ColorMatrix` . |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Gets the element at the 0 (zero) row and second column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the 0 row and second column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Sets the element at the 0 (zero) row and second column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the 0 row and second column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Gets the element at the 0 (zero) row and third column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the 0 row and third column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Sets the element at the 0 (zero) row and third column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the 0 row and third column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Gets the element at the 0 (zero) row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the 0 row and fourth column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Sets the element at the 0 (zero) row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the 0 row and fourth column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Gets the element at the first row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the first row and 0 column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Sets the element at the first row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the first row and 0 column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Gets the element at the first row and first column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the first row and first column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Sets the element at the first row and first column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the first row and first column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Gets the element at the first row and second column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the first row and second column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Sets the element at the first row and second column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the first row and second column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Gets the element at the first row and third column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the first row and third column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Sets the element at the first row and third column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the first row and third column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Gets the element at the first row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the first row and fourth column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Sets the element at the first row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the first row and fourth column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Gets the element at the second row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the second row and 0 column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Sets the element at the second row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the second row and 0 column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Gets the element at the second row and first column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the second row and first column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Sets the element at the second row and first column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the second row and first column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Gets the element at the second row and second column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the second row and second column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Sets the element at the second row and second column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the second row and second column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Gets the element at the second row and third column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the second row and third column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Sets the element at the second row and third column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the second row and third column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Gets the element at the second row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the second row and fourth column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Sets the element at the second row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the second row and fourth column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Gets the element at the third row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the third row and 0 column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Sets the element at the third row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the third row and 0 column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Gets the element at the third row and first column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the third row and first column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Sets the element at the third row and first column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the third row and first column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Gets the element at the third row and second column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the third row and second column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Sets the element at the third row and second column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the third row and second column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Gets the element at the third row and third column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the third row and third column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Sets the element at the third row and third column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the third row and third column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Gets the element at the third row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the third row and fourth column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Sets the element at the third row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the third row and fourth column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Gets the element at the fourth row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the fourth row and 0 column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Sets the element at the fourth row and 0 (zero) column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the fourth row and 0 column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Gets the element at the fourth row and first column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the fourth row and first column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Sets the element at the fourth row and first column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the fourth row and first column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Gets the element at the fourth row and second column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the fourth row and second column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Sets the element at the fourth row and second column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the fourth row and second column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Gets the element at the fourth row and third column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the fourth row and third column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Sets the element at the fourth row and third column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the fourth row and third column of this `Aspose.Imaging.ColorMatrix`. |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Gets the element at the fourth row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - The element at the fourth row and fourth column of this `Aspose.Imaging.ColorMatrix`.
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Sets the element at the fourth row and fourth column of this `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The element at the fourth row and fourth column of this `Aspose.Imaging.ColorMatrix`. |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Gets the element at the specified row and column in the `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | The row number. |
| column | int | The column number. |

**Returns:**
float - The element at the specified row and column.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Sets the element at the specified row and column in the `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | The row number. |
| column | int | The column number. |
| value | float | The value |

### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


Gets the matrix values.

**Returns:**
float[][] - The matrix values array.
