---
title: "ColorMatrix"
second_title: "Aspose.Imaging for Java API 参考"
description: "定义一个 5 x 5 矩阵，包含 RGBA 空间的坐标。"
type: docs
weight: 26
url: /zh/java/com.aspose.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

定义一个 5 x 5 矩阵，包含 RGBA 空间的坐标。 [ImageAttributes](../../com.aspose.imaging/imageattributes) 类的多个方法通过使用颜色矩阵来调整图像颜色。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | 初始化 `Aspose.Imaging.ColorMatrix` 类的新实例。 |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | 使用指定矩阵 `newColorMatrix` 中的元素初始化 `Aspose.Imaging.ColorMatrix` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [MATRIX_DIMENSION_ELEMENTS_COUNT](#MATRIX-DIMENSION-ELEMENTS-COUNT) | 矩阵维度中的元素数量。 |
| [MATRIX_DIMENSIONS_COUNT](#MATRIX-DIMENSIONS-COUNT) | 矩阵维度的数量。 |
| [MATRIX_TOTAL_ELEMENTS_COUNT](#MATRIX-TOTAL-ELEMENTS-COUNT) | 矩阵中元素的总数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | 获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第 0 列的元素。 |
| [setMatrix00(float value)](#setMatrix00-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第 0 列的元素。 |
| [getMatrix01()](#getMatrix01--) | 获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第一列的元素。 |
| [setMatrix01(float value)](#setMatrix01-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第一列的元素。 |
| [getMatrix02()](#getMatrix02--) | 获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第二列的元素。 |
| [setMatrix02(float value)](#setMatrix02-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第二列的元素。 |
| [getMatrix03()](#getMatrix03--) | 获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第三列的元素。 |
| [setMatrix03(float value)](#setMatrix03-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第三列的元素。 |
| [getMatrix04()](#getMatrix04--) | 获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第四列的元素。 |
| [setMatrix04(float value)](#setMatrix04-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第四列的元素。 |
| [getMatrix10()](#getMatrix10--) | 获取此 `Aspose.Imaging.ColorMatrix` 中第一行第 0（零）列的元素。 |
| [setMatrix10(float value)](#setMatrix10-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第一行第0（零）列的元素。 |
| [getMatrix11()](#getMatrix11--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第一行第一列的元素。 |
| [setMatrix11(float value)](#setMatrix11-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第一行第一列的元素。 |
| [getMatrix12()](#getMatrix12--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第一行第二列的元素。 |
| [setMatrix12(float value)](#setMatrix12-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第一行第二列的元素。 |
| [getMatrix13()](#getMatrix13--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第一行第三列的元素。 |
| [setMatrix13(float value)](#setMatrix13-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第一行第三列的元素。 |
| [getMatrix14()](#getMatrix14--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第一行第四列的元素。 |
| [setMatrix14(float value)](#setMatrix14-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第一行第四列的元素。 |
| [getMatrix20()](#getMatrix20--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第二行第0（零）列的元素。 |
| [setMatrix20(float value)](#setMatrix20-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第二行第0（零）列的元素。 |
| [getMatrix21()](#getMatrix21--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第二行第一列的元素。 |
| [setMatrix21(float value)](#setMatrix21-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第二行第一列的元素。 |
| [getMatrix22()](#getMatrix22--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第二行第二列的元素。 |
| [setMatrix22(float value)](#setMatrix22-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第二行第二列的元素。 |
| [getMatrix23()](#getMatrix23--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第二行第三列的元素。 |
| [setMatrix23(float value)](#setMatrix23-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第二行第三列的元素。 |
| [getMatrix24()](#getMatrix24--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第二行第四列的元素。 |
| [setMatrix24(float value)](#setMatrix24-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第二行第四列的元素。 |
| [getMatrix30()](#getMatrix30--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第三行第0（零）列的元素。 |
| [setMatrix30(float value)](#setMatrix30-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第三行第0（零）列的元素。 |
| [getMatrix31()](#getMatrix31--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第三行第一列的元素。 |
| [setMatrix31(float value)](#setMatrix31-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第三行第一列的元素。 |
| [getMatrix32()](#getMatrix32--) | 获取此 `Aspose.Imaging.ColorMatrix` 的第三行第二列的元素。 |
| [setMatrix32(float value)](#setMatrix32-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 的第三行第二列的元素。 |
| [getMatrix33()](#getMatrix33--) | 获取此 `Aspose.Imaging.ColorMatrix` 第三行第三列的元素。 |
| [setMatrix33(float value)](#setMatrix33-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 第三行第三列的元素。 |
| [getMatrix34()](#getMatrix34--) | 获取此 `Aspose.Imaging.ColorMatrix` 第三行第四列的元素。 |
| [setMatrix34(float value)](#setMatrix34-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 第三行第四列的元素。 |
| [getMatrix40()](#getMatrix40--) | 获取此 `Aspose.Imaging.ColorMatrix` 第四行第0（零）列的元素。 |
| [setMatrix40(float value)](#setMatrix40-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 第四行第0（零）列的元素。 |
| [getMatrix41()](#getMatrix41--) | 获取此 `Aspose.Imaging.ColorMatrix` 第四行第一列的元素。 |
| [setMatrix41(float value)](#setMatrix41-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 第四行第一列的元素。 |
| [getMatrix42()](#getMatrix42--) | 获取此 `Aspose.Imaging.ColorMatrix` 第四行第二列的元素。 |
| [setMatrix42(float value)](#setMatrix42-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 第四行第二列的元素。 |
| [getMatrix43()](#getMatrix43--) | 获取此 `Aspose.Imaging.ColorMatrix` 第四行第三列的元素。 |
| [setMatrix43(float value)](#setMatrix43-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 第四行第三列的元素。 |
| [getMatrix44()](#getMatrix44--) | 获取此 `Aspose.Imaging.ColorMatrix` 第四行第四列的元素。 |
| [setMatrix44(float value)](#setMatrix44-float-) | 设置此 `Aspose.Imaging.ColorMatrix` 第四行第四列的元素。 |
| [get_Item(int row, int column)](#get-Item-int-int-) | 获取 `Aspose.Imaging.ColorMatrix` 中指定行列的元素。 |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | 设置 `Aspose.Imaging.ColorMatrix` 中指定行列的元素。 |
| [getMatrix()](#getMatrix--) | 获取矩阵值。 |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


初始化 `Aspose.Imaging.ColorMatrix` 类的新实例。

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


使用指定矩阵 `newColorMatrix` 中的元素初始化 `Aspose.Imaging.ColorMatrix` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorMatrix | float[][] | 新 `Aspose.Imaging.ColorMatrix` 的元素值。 |

### MATRIX_DIMENSION_ELEMENTS_COUNT {#MATRIX-DIMENSION-ELEMENTS-COUNT}
```
public static final int MATRIX_DIMENSION_ELEMENTS_COUNT
```


矩阵维度中的元素数量。

### MATRIX_DIMENSIONS_COUNT {#MATRIX-DIMENSIONS-COUNT}
```
public static final int MATRIX_DIMENSIONS_COUNT
```


矩阵维度的数量。

### MATRIX_TOTAL_ELEMENTS_COUNT {#MATRIX-TOTAL-ELEMENTS-COUNT}
```
public static final int MATRIX_TOTAL_ELEMENTS_COUNT
```


矩阵中元素的总数。

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第 0 列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第0行第0列的元素。
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第 0 列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第0行第0列的元素。 |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第一列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第0行第一列的元素。
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第一列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第0行第一列的元素。 |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第二列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第0行第二列的元素。
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第二列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第0行第二列的元素。 |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第三列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第0行第三列的元素。
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第三列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第0行第三列的元素。 |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


获取此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第四列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第0行第四列的元素。
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 中第 0（零）行第四列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第0行第四列的元素。 |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


获取此 `Aspose.Imaging.ColorMatrix` 中第一行第 0（零）列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第一行第0列的元素。
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第一行第0（零）列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第一行第0列的元素。 |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第一行第一列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第一行第一列的元素。
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第一行第一列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第一行第一列的元素。 |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第一行第二列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第一行第二列的元素。
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第一行第二列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第一行第二列的元素。 |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第一行第三列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第一行第三列的元素。
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第一行第三列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第一行第三列的元素。 |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第一行第四列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第一行第四列的元素。
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第一行第四列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第一行第四列的元素。 |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第二行第0（零）列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第二行第0列的元素。
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第二行第0（零）列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第二行第0列的元素。 |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第二行第一列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第二行第一列的元素。
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第二行第一列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第二行第一列的元素。 |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第二行第二列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第二行第二列的元素。
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第二行第二列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第二行第二列的元素。 |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第二行第三列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第二行第三列的元素。
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第二行第三列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第二行第三列的元素。 |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第二行第四列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 的第二行第四列的元素。
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第二行第四列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 的第二行第四列的元素。 |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第三行第0（零）列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第三行第0列的元素。
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第三行第0（零）列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第三行第0列的元素。 |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第三行第一列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第三行第1列的元素。
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第三行第一列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第三行第1列的元素。 |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


获取此 `Aspose.Imaging.ColorMatrix` 的第三行第二列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第三行第2列的元素。
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 的第三行第二列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第三行第2列的元素。 |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


获取此 `Aspose.Imaging.ColorMatrix` 第三行第三列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第三行第3列的元素。
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 第三行第三列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第三行第3列的元素。 |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


获取此 `Aspose.Imaging.ColorMatrix` 第三行第四列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第三行第4列的元素。
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 第三行第四列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第三行第4列的元素。 |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


获取此 `Aspose.Imaging.ColorMatrix` 第四行第0（零）列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第四行第0列的元素。
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 第四行第0（零）列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第四行第0列的元素。 |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


获取此 `Aspose.Imaging.ColorMatrix` 第四行第一列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第四行第1列的元素。
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 第四行第一列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第四行第1列的元素。 |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


获取此 `Aspose.Imaging.ColorMatrix` 第四行第二列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第四行第2列的元素。
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 第四行第二列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第四行第2列的元素。 |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


获取此 `Aspose.Imaging.ColorMatrix` 第四行第三列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第四行第3列的元素。
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 第四行第三列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第四行第3列的元素。 |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


获取此 `Aspose.Imaging.ColorMatrix` 第四行第四列的元素。

**Returns:**
float - 此 `Aspose.Imaging.ColorMatrix` 第四行第4列的元素。
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


设置此 `Aspose.Imaging.ColorMatrix` 第四行第四列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 此 `Aspose.Imaging.ColorMatrix` 第四行第4列的元素。 |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


获取 `Aspose.Imaging.ColorMatrix` 中指定行列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 行 | int | 行号。 |
| 列 | int | 列号。 |

**Returns:**
float - 指定行和列处的元素。
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


设置 `Aspose.Imaging.ColorMatrix` 中指定行列的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 行 | int | 行号。 |
| 列 | int | 列号。 |
| 值 | float | 该值 |

### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


获取矩阵值。

**Returns:**
float[][] - 矩阵值数组。
