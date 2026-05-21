---
title: "EmfPlusColorMatrixEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto ColorMatrixEffect especifica una transformación afín que se aplicará a una imagen."
type: docs
weight: 29
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

El objeto ColorMatrixEffect especifica una transformación afín que se aplicará a una imagen.

Las imágenes bitmap se especifican mediante objetos EmfPlusBitmap (sección 2.2.2.2). Un efecto de matriz de color se realiza multiplicando un vector de color por un objeto ColorMatrixEffect. Una matriz de color de 5x5 puede realizar una transformación lineal, incluyendo reflexión, rotación, cizallado o escalado seguido de una traslación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | Obtiene o establece Matrix[N][0] de la matriz de color 5x5. |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | Obtiene o establece Matrix[N][0] de la matriz de color 5x5. |
| [getMatrixN1()](#getMatrixN1--) | Obtiene o establece Matrix[N][1] de la matriz de color 5x5. |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | Obtiene o establece Matrix[N][1] de la matriz de color 5x5. |
| [getMatrixN2()](#getMatrixN2--) | Obtiene o establece Matrix[N][2] de la matriz de color 5x5. |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | Obtiene o establece Matrix[N][2] de la matriz de color 5x5. |
| [getMatrixN3()](#getMatrixN3--) | Obtiene o establece Matrix[N][3] de la matriz de color 5x5. |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | Obtiene o establece Matrix[N][3] de la matriz de color 5x5. |
| [getMatrixN4()](#getMatrixN4--) | Obtiene o establece Matrix[N][4] de la matriz de color 5x5. |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | Obtiene o establece Matrix[N][4] de la matriz de color 5x5. |
| [getMatrix()](#getMatrix--) | Obtiene o establece la matriz. |
| [setMatrix(int[][] value)](#setMatrix-int-----) | Obtiene o establece la matriz. |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


Obtiene o establece Matrix[N][0] de la matriz de color 5x5. Esta fila se utiliza para transformaciones.

Matrix\_0\_0 (4 bytes): Matrix[0][0], que es el factor para el color rojo. Matrix\_1\_0 (4 bytes): Matrix[1][0]. Matrix\_2\_0 (4 bytes): Matrix[2][0]. Matrix\_3\_0 (4 bytes): Matrix[3][0]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Este valor DEBE ser 0.0.

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


Obtiene o establece Matrix[N][0] de la matriz de color 5x5. Esta fila se utiliza para transformaciones.

Matrix\_0\_0 (4 bytes): Matrix[0][0], que es el factor para el color rojo. Matrix\_1\_0 (4 bytes): Matrix[1][0]. Matrix\_2\_0 (4 bytes): Matrix[2][0]. Matrix\_3\_0 (4 bytes): Matrix[3][0]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Este valor DEBE ser 0.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


Obtiene o establece Matrix[N][1] de la matriz de color 5x5. Esta fila se utiliza para transformaciones.

Valor: La matriz n1.

Matrix\_0\_1 (4 bytes): Matrix[0][1]. Matrix\_1\_1 (4 bytes): Matrix[1][1], que es el factor para el color verde. Matrix\_2\_1 (4 bytes): Matrix[2][1]. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Este valor DEBE ser 0.0.

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


Obtiene o establece Matrix[N][1] de la matriz de color 5x5. Esta fila se utiliza para transformaciones.

Valor: La matriz n1.

Matrix\_0\_1 (4 bytes): Matrix[0][1]. Matrix\_1\_1 (4 bytes): Matrix[1][1], que es el factor para el color verde. Matrix\_2\_1 (4 bytes): Matrix[2][1]. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Este valor DEBE ser 0.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


Obtiene o establece Matrix[N][2] de la matriz de color 5x5. Esta fila se utiliza para transformaciones.

Valor: La matriz n1.

Matrix\_0\_2 (4 bytes): Matrix[0][2]. Matrix\_1\_2 (4 bytes): Matrix[1][2]. Matrix\_2\_2 (4 bytes): Matrix[2][2], que es el factor para el color azul. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Este valor DEBE ser 0.0.

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


Obtiene o establece Matrix[N][2] de la matriz de color 5x5. Esta fila se utiliza para transformaciones.

Valor: La matriz n1.

Matrix\_0\_2 (4 bytes): Matrix[0][2]. Matrix\_1\_2 (4 bytes): Matrix[1][2]. Matrix\_2\_2 (4 bytes): Matrix[2][2], que es el factor para el color azul. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Este valor DEBE ser 0.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


Obtiene o establece Matrix[N][3] de la matriz de color 5x5. Esta fila se utiliza para transformaciones.

Valor: La matriz n1.

Matrix\_0\_3 (4 bytes): Matrix[0][3]. Matrix\_1\_3 (4 bytes): Matrix[1][3]. Matrix\_2\_3 (4 bytes): Matrix[2][3]. Matrix\_3\_3 (4 bytes): Matrix[3][3], que es el factor para el alfa (transparencia) Matrix\_4\_0 (4 bytes): Matrix[4][0]. Este valor DEBE ser 0.0.

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


Obtiene o establece Matrix[N][3] de la matriz de color 5x5. Esta fila se utiliza para transformaciones.

Valor: La matriz n1.

Matrix\_0\_3 (4 bytes): Matrix[0][3]. Matrix\_1\_3 (4 bytes): Matrix[1][3]. Matrix\_2\_3 (4 bytes): Matrix[2][3]. Matrix\_3\_3 (4 bytes): Matrix[3][3], que es el factor para el alfa (transparencia) Matrix\_4\_0 (4 bytes): Matrix[4][0]. Este valor DEBE ser 0.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


Obtiene o establece la Matrix[N][4] de la matriz de color 5x5. Esta fila se usa para traducciones de color.

Valor: La matriz n1.

Matrix\_0\_4 (4 bytes): Matrix[0][4]. Matrix\_1\_4 (4 bytes): Matrix[1][4]. Matrix\_2\_4 (4 bytes): Matrix[2][4]. Matrix\_3\_4 (4 bytes): Matrix[3][4]. Matrix\_4\_4 (4 bytes): Matrix[4][4]. Este valor DEBERÍA ser 1.0.

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


Obtiene o establece la Matrix[N][4] de la matriz de color 5x5. Esta fila se usa para traducciones de color.

Valor: La matriz n1.

Matrix\_0\_4 (4 bytes): Matrix[0][4]. Matrix\_1\_4 (4 bytes): Matrix[1][4]. Matrix\_2\_4 (4 bytes): Matrix[2][4]. Matrix\_3\_4 (4 bytes): Matrix[3][4]. Matrix\_4\_4 (4 bytes): Matrix[4][4]. Este valor DEBERÍA ser 1.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


Obtiene o establece la matriz.

Valor: La matriz.

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


Obtiene o establece la matriz.

Valor: La matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[][] |  |

