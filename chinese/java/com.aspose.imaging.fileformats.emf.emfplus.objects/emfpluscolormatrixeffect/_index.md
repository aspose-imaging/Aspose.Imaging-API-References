---
title: "EmfPlusColorMatrixEffect"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "ColorMatrixEffect 对象指定要应用于图像的仿射变换。"
type: docs
weight: 29
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

ColorMatrixEffect 对象指定要应用于图像的仿射变换。

位图图像由 EmfPlusBitmap 对象指定（第 2.2.2.2 节）。颜色矩阵效果通过将颜色向量与 ColorMatrixEffect 对象相乘来实现。5×5 颜色矩阵可以执行线性变换，包括反射、旋转、剪切或缩放后再平移。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | 获取或设置 5×5 颜色矩阵的 Matrix[N][0]。 |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | 获取或设置 5×5 颜色矩阵的 Matrix[N][0]。 |
| [getMatrixN1()](#getMatrixN1--) | 获取或设置 5×5 颜色矩阵的 Matrix[N][1]。 |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | 获取或设置 5×5 颜色矩阵的 Matrix[N][1]。 |
| [getMatrixN2()](#getMatrixN2--) | 获取或设置 5×5 颜色矩阵的 Matrix[N][2]。 |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | 获取或设置 5×5 颜色矩阵的 Matrix[N][2]。 |
| [getMatrixN3()](#getMatrixN3--) | 获取或设置 5×5 颜色矩阵的 Matrix[N][3]。 |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | 获取或设置 5×5 颜色矩阵的 Matrix[N][3]。 |
| [getMatrixN4()](#getMatrixN4--) | 获取或设置 5×5 颜色矩阵的 Matrix[N][4]。 |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | 获取或设置 5×5 颜色矩阵的 Matrix[N][4]。 |
| [getMatrix()](#getMatrix--) | 获取或设置矩阵。 |
| [setMatrix(int[][] value)](#setMatrix-int-----) | 获取或设置矩阵。 |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


获取或设置 5×5 颜色矩阵的 Matrix[N][0]。此行用于变换。

Matrix\_0\_0 (4 字节)：Matrix[0][0]，它是红色的因子。Matrix\_1\_0 (4 字节)：Matrix[1][0]。Matrix\_2\_0 (4 字节)：Matrix[2][0]。Matrix\_3\_0 (4 字节)：Matrix[3][0]。Matrix\_4\_0 (4 字节)：Matrix[4][0]。此值必须为 0.0。

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


获取或设置 5×5 颜色矩阵的 Matrix[N][0]。此行用于变换。

Matrix\_0\_0 (4 字节)：Matrix[0][0]，它是红色的因子。Matrix\_1\_0 (4 字节)：Matrix[1][0]。Matrix\_2\_0 (4 字节)：Matrix[2][0]。Matrix\_3\_0 (4 字节)：Matrix[3][0]。Matrix\_4\_0 (4 字节)：Matrix[4][0]。此值必须为 0.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


获取或设置 5×5 颜色矩阵的 Matrix[N][1]。此行用于变换。

值：矩阵 n1。

Matrix\_0\_1 (4 字节)：Matrix[0][1]。Matrix\_1\_1 (4 字节)：Matrix[1][1]，它是绿色的因子。Matrix\_2\_1 (4 字节)：Matrix[2][1]。Matrix\_3\_1 (4 字节)：Matrix[3][1]。Matrix\_4\_0 (4 字节)：Matrix[4][0]。此值必须为 0.0。

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


获取或设置 5×5 颜色矩阵的 Matrix[N][1]。此行用于变换。

值：矩阵 n1。

Matrix\_0\_1 (4 字节)：Matrix[0][1]。Matrix\_1\_1 (4 字节)：Matrix[1][1]，它是绿色的因子。Matrix\_2\_1 (4 字节)：Matrix[2][1]。Matrix\_3\_1 (4 字节)：Matrix[3][1]。Matrix\_4\_0 (4 字节)：Matrix[4][0]。此值必须为 0.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


获取或设置 5×5 颜色矩阵的 Matrix[N][2]。此行用于变换。

值：矩阵 n1。

Matrix\_0\_2 (4 字节)：Matrix[0][2]。Matrix\_1\_2 (4 字节)：Matrix[1][2]。Matrix\_2\_2 (4 字节)：Matrix[2][2]，它是蓝色的因子。Matrix\_3\_1 (4 字节)：Matrix[3][1]。Matrix\_4\_0 (4 字节)：Matrix[4][0]。此值必须为 0.0。

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


获取或设置 5×5 颜色矩阵的 Matrix[N][2]。此行用于变换。

值：矩阵 n1。

Matrix\_0\_2 (4 字节)：Matrix[0][2]。Matrix\_1\_2 (4 字节)：Matrix[1][2]。Matrix\_2\_2 (4 字节)：Matrix[2][2]，它是蓝色的因子。Matrix\_3\_1 (4 字节)：Matrix[3][1]。Matrix\_4\_0 (4 字节)：Matrix[4][0]。此值必须为 0.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


获取或设置 5×5 颜色矩阵的 Matrix[N][3]。此行用于变换。

值：矩阵 n1。

Matrix\_0\_3 (4 字节)：Matrix[0][3]。Matrix\_1\_3 (4 字节)：Matrix[1][3]。Matrix\_2\_3 (4 字节)：Matrix[2][3]。Matrix\_3\_3 (4 字节)：Matrix[3][3]，它是 alpha（透明度）的因子。Matrix\_4\_0 (4 字节)：Matrix[4][0]。此值必须为 0.0。

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


获取或设置 5×5 颜色矩阵的 Matrix[N][3]。此行用于变换。

值：矩阵 n1。

Matrix\_0\_3 (4 字节)：Matrix[0][3]。Matrix\_1\_3 (4 字节)：Matrix[1][3]。Matrix\_2\_3 (4 字节)：Matrix[2][3]。Matrix\_3\_3 (4 字节)：Matrix[3][3]，它是 alpha（透明度）的因子。Matrix\_4\_0 (4 字节)：Matrix[4][0]。此值必须为 0.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


获取或设置 5x5 颜色矩阵的 Matrix[N][4]。此行用于颜色转换。

值：矩阵 n1。

Matrix\_0\_4（4 字节）：Matrix[0][4]。Matrix\_1\_4（4 字节）：Matrix[1][4]。Matrix\_2\_4（4 字节）：Matrix[2][4]。Matrix\_3\_4（4 字节）：Matrix[3][4]。Matrix\_4\_4（4 字节）：Matrix[4][4]。此值应为 1.0。

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


获取或设置 5x5 颜色矩阵的 Matrix[N][4]。此行用于颜色转换。

值：矩阵 n1。

Matrix\_0\_4（4 字节）：Matrix[0][4]。Matrix\_1\_4（4 字节）：Matrix[1][4]。Matrix\_2\_4（4 字节）：Matrix[2][4]。Matrix\_3\_4（4 字节）：Matrix[3][4]。Matrix\_4\_4（4 字节）：Matrix[4][4]。此值应为 1.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


获取或设置矩阵。

值：矩阵。

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


获取或设置矩阵。

值：矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[][] |  |

