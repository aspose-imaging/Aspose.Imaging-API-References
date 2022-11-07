---
title: EmfPlusColorMatrixEffect
second_title: Aspose.Imaging for Java API Reference
description: The ColorMatrixEffect object specifies an affine transform to be applied to an image.
type: docs
weight: 29
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

The ColorMatrixEffect object specifies an affine transform to be applied to an image.

Bitmap images are specified by EmfPlusBitmap objects (section 2.2.2.2). A color matrix effect is performed by multiplying a color vector by a ColorMatrixEffect object. A 5x5 color matrix can perform a linear transform, including reflection, rotation, shearing, or scaling followed by a translation.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | Gets or sets the Matrix[N][0] of the 5x5 color matrix. |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | Gets or sets the Matrix[N][0] of the 5x5 color matrix. |
| [getMatrixN1()](#getMatrixN1--) | Gets or sets the Matrix[N][1] of the 5x5 color matrix. |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | Gets or sets the Matrix[N][1] of the 5x5 color matrix. |
| [getMatrixN2()](#getMatrixN2--) | Gets or sets the Matrix[N][2] of the 5x5 color matrix. |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | Gets or sets the Matrix[N][2] of the 5x5 color matrix. |
| [getMatrixN3()](#getMatrixN3--) | Gets or sets the Matrix[N][3] of the 5x5 color matrix. |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | Gets or sets the Matrix[N][3] of the 5x5 color matrix. |
| [getMatrixN4()](#getMatrixN4--) | Gets or sets the Matrix[N][4] of the 5x5 color matrix. |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | Gets or sets the Matrix[N][4] of the 5x5 color matrix. |
| [getMatrix()](#getMatrix--) | Gets or sets the matrix. |
| [setMatrix(int[][] value)](#setMatrix-int-----) | Gets or sets the matrix. |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


Gets or sets the Matrix[N][0] of the 5x5 color matrix. This row is used for transforms.

Matrix\_0\_0 (4 bytes): Matrix[0][0], which is the factor for the color red. Matrix\_1\_0 (4 bytes): Matrix[1][0]. Matrix\_2\_0 (4 bytes): Matrix[2][0]. Matrix\_3\_0 (4 bytes): Matrix[3][0]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. This value MUST be 0.0.

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


Gets or sets the Matrix[N][0] of the 5x5 color matrix. This row is used for transforms.

Matrix\_0\_0 (4 bytes): Matrix[0][0], which is the factor for the color red. Matrix\_1\_0 (4 bytes): Matrix[1][0]. Matrix\_2\_0 (4 bytes): Matrix[2][0]. Matrix\_3\_0 (4 bytes): Matrix[3][0]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. This value MUST be 0.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


Gets or sets the Matrix[N][1] of the 5x5 color matrix. This row is used for transforms.

Value: The matrix n1.

Matrix\_0\_1 (4 bytes): Matrix[0][1]. Matrix\_1\_1 (4 bytes): Matrix[1][1], which is the factor for the color green. Matrix\_2\_1 (4 bytes): Matrix[2][1]. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. This value MUST be 0.0.

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


Gets or sets the Matrix[N][1] of the 5x5 color matrix. This row is used for transforms.

Value: The matrix n1.

Matrix\_0\_1 (4 bytes): Matrix[0][1]. Matrix\_1\_1 (4 bytes): Matrix[1][1], which is the factor for the color green. Matrix\_2\_1 (4 bytes): Matrix[2][1]. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. This value MUST be 0.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


Gets or sets the Matrix[N][2] of the 5x5 color matrix. This row is used for transforms.

Value: The matrix n1.

Matrix\_0\_2 (4 bytes): Matrix[0][2]. Matrix\_1\_2 (4 bytes): Matrix[1][2]. Matrix\_2\_2 (4 bytes): Matrix[2][2], which is the factor for the color blue. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. This value MUST be 0.0.

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


Gets or sets the Matrix[N][2] of the 5x5 color matrix. This row is used for transforms.

Value: The matrix n1.

Matrix\_0\_2 (4 bytes): Matrix[0][2]. Matrix\_1\_2 (4 bytes): Matrix[1][2]. Matrix\_2\_2 (4 bytes): Matrix[2][2], which is the factor for the color blue. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. This value MUST be 0.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


Gets or sets the Matrix[N][3] of the 5x5 color matrix. This row is used for transforms.

Value: The matrix n1.

Matrix\_0\_3 (4 bytes): Matrix[0][3]. Matrix\_1\_3 (4 bytes): Matrix[1][3]. Matrix\_2\_3 (4 bytes): Matrix[2][3]. Matrix\_3\_3 (4 bytes): Matrix[3][3], which is the factor for the alpha (transparency) Matrix\_4\_0 (4 bytes): Matrix[4][0]. This value MUST be 0.0.

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


Gets or sets the Matrix[N][3] of the 5x5 color matrix. This row is used for transforms.

Value: The matrix n1.

Matrix\_0\_3 (4 bytes): Matrix[0][3]. Matrix\_1\_3 (4 bytes): Matrix[1][3]. Matrix\_2\_3 (4 bytes): Matrix[2][3]. Matrix\_3\_3 (4 bytes): Matrix[3][3], which is the factor for the alpha (transparency) Matrix\_4\_0 (4 bytes): Matrix[4][0]. This value MUST be 0.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


Gets or sets the Matrix[N][4] of the 5x5 color matrix. This row is used for color translations.

Value: The matrix n1.

Matrix\_0\_4 (4 bytes): Matrix[0][4]. Matrix\_1\_4 (4 bytes): Matrix[1][4]. Matrix\_2\_4 (4 bytes): Matrix[2][4]. Matrix\_3\_4 (4 bytes): Matrix[3][4]. Matrix\_4\_4 (4 bytes): Matrix[4][4]. This value SHOULD be 1.0.

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


Gets or sets the Matrix[N][4] of the 5x5 color matrix. This row is used for color translations.

Value: The matrix n1.

Matrix\_0\_4 (4 bytes): Matrix[0][4]. Matrix\_1\_4 (4 bytes): Matrix[1][4]. Matrix\_2\_4 (4 bytes): Matrix[2][4]. Matrix\_3\_4 (4 bytes): Matrix[3][4]. Matrix\_4\_4 (4 bytes): Matrix[4][4]. This value SHOULD be 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


Gets or sets the matrix.

Value: The matrix.

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


Gets or sets the matrix.

Value: The matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[][] |  |

