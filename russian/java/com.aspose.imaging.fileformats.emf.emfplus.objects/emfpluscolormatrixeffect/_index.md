---
title: "EmfPlusColorMatrixEffect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект ColorMatrixEffect указывает аффинное преобразование, применяемое к изображению."
type: docs
weight: 29
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

Объект ColorMatrixEffect указывает аффинное преобразование, применяемое к изображению.

Битовые изображения задаются объектами EmfPlusBitmap (раздел 2.2.2.2). Эффект цветовой матрицы выполняется умножением цветового вектора на объект ColorMatrixEffect. 5×5 цветовая матрица может выполнять линейное преобразование, включая отражение, вращение, сдвиг или масштабирование, за которым следует трансляция.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | Получает или задает Matrix[N][0] 5×5 цветовой матрицы. |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | Получает или задает Matrix[N][0] 5×5 цветовой матрицы. |
| [getMatrixN1()](#getMatrixN1--) | Получает или задает Matrix[N][1] 5×5 цветовой матрицы. |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | Получает или задает Matrix[N][1] 5×5 цветовой матрицы. |
| [getMatrixN2()](#getMatrixN2--) | Получает или задает Matrix[N][2] 5×5 цветовой матрицы. |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | Получает или задает Matrix[N][2] 5×5 цветовой матрицы. |
| [getMatrixN3()](#getMatrixN3--) | Получает или задает Matrix[N][3] 5×5 цветовой матрицы. |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | Получает или задает Matrix[N][3] 5×5 цветовой матрицы. |
| [getMatrixN4()](#getMatrixN4--) | Получает или задает Matrix[N][4] 5×5 цветовой матрицы. |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | Получает или задает Matrix[N][4] 5×5 цветовой матрицы. |
| [getMatrix()](#getMatrix--) | Получает или задает матрицу. |
| [setMatrix(int[][] value)](#setMatrix-int-----) | Получает или задает матрицу. |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


Получает или задает Matrix[N][0] 5×5 цветовой матрицы. Эта строка используется для преобразований.

Matrix\_0\_0 (4 байта): Matrix[0][0], который является коэффициентом для красного цвета. Matrix\_1\_0 (4 байта): Matrix[1][0]. Matrix\_2\_0 (4 байта): Matrix[2][0]. Matrix\_3\_0 (4 байта): Matrix[3][0]. Matrix\_4\_0 (4 байта): Matrix[4][0]. Это значение ДОЛЖНО быть 0.0.

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


Получает или задает Matrix[N][0] 5×5 цветовой матрицы. Эта строка используется для преобразований.

Matrix\_0\_0 (4 байта): Matrix[0][0], который является коэффициентом для красного цвета. Matrix\_1\_0 (4 байта): Matrix[1][0]. Matrix\_2\_0 (4 байта): Matrix[2][0]. Matrix\_3\_0 (4 байта): Matrix[3][0]. Matrix\_4\_0 (4 байта): Matrix[4][0]. Это значение ДОЛЖНО быть 0.0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


Получает или задает Matrix[N][1] 5×5 цветовой матрицы. Эта строка используется для преобразований.

Значение: матрица n1.

Matrix\_0\_1 (4 байта): Matrix[0][1]. Matrix\_1\_1 (4 байта): Matrix[1][1], который является коэффициентом для зеленого цвета. Matrix\_2\_1 (4 байта): Matrix[2][1]. Matrix\_3\_1 (4 байта): Matrix[3][1]. Matrix\_4\_0 (4 байта): Matrix[4][0]. Это значение ДОЛЖНО быть 0.0.

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


Получает или задает Matrix[N][1] 5×5 цветовой матрицы. Эта строка используется для преобразований.

Значение: матрица n1.

Matrix\_0\_1 (4 байта): Matrix[0][1]. Matrix\_1\_1 (4 байта): Matrix[1][1], который является коэффициентом для зеленого цвета. Matrix\_2\_1 (4 байта): Matrix[2][1]. Matrix\_3\_1 (4 байта): Matrix[3][1]. Matrix\_4\_0 (4 байта): Matrix[4][0]. Это значение ДОЛЖНО быть 0.0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


Получает или задает Matrix[N][2] 5×5 цветовой матрицы. Эта строка используется для преобразований.

Значение: матрица n1.

Matrix\_0\_2 (4 байта): Matrix[0][2]. Matrix\_1\_2 (4 байта): Matrix[1][2]. Matrix\_2\_2 (4 байта): Matrix[2][2], который является коэффициентом для синего цвета. Matrix\_3\_1 (4 байта): Matrix[3][1]. Matrix\_4\_0 (4 байта): Matrix[4][0]. Это значение ДОЛЖНО быть 0.0.

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


Получает или задает Matrix[N][2] 5×5 цветовой матрицы. Эта строка используется для преобразований.

Значение: матрица n1.

Matrix\_0\_2 (4 байта): Matrix[0][2]. Matrix\_1\_2 (4 байта): Matrix[1][2]. Matrix\_2\_2 (4 байта): Matrix[2][2], который является коэффициентом для синего цвета. Matrix\_3\_1 (4 байта): Matrix[3][1]. Matrix\_4\_0 (4 байта): Matrix[4][0]. Это значение ДОЛЖНО быть 0.0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


Получает или задает Matrix[N][3] 5×5 цветовой матрицы. Эта строка используется для преобразований.

Значение: матрица n1.

Matrix\_0\_3 (4 байта): Matrix[0][3]. Matrix\_1\_3 (4 байта): Matrix[1][3]. Matrix\_2\_3 (4 байта): Matrix[2][3]. Matrix\_3\_3 (4 байта): Matrix[3][3], который является коэффициентом для альфа (прозрачность) Matrix\_4\_0 (4 байта): Matrix[4][0]. Это значение ДОЛЖНО быть 0.0.

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


Получает или задает Matrix[N][3] 5×5 цветовой матрицы. Эта строка используется для преобразований.

Значение: матрица n1.

Matrix\_0\_3 (4 байта): Matrix[0][3]. Matrix\_1\_3 (4 байта): Matrix[1][3]. Matrix\_2\_3 (4 байта): Matrix[2][3]. Matrix\_3\_3 (4 байта): Matrix[3][3], который является коэффициентом для альфа (прозрачность) Matrix\_4\_0 (4 байта): Matrix[4][0]. Это значение ДОЛЖНО быть 0.0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


Получает или задает Matrix[N][4] 5×5 цветовой матрицы. Эта строка используется для цветовых преобразований.

Значение: матрица n1.

Matrix\_0\_4 (4 байта): Matrix[0][4]. Matrix\_1\_4 (4 байта): Matrix[1][4]. Matrix\_2\_4 (4 байта): Matrix[2][4]. Matrix\_3\_4 (4 байта): Matrix[3][4]. Matrix\_4\_4 (4 байта): Matrix[4][4]. Это значение ДОЛЖНО быть 1.0.

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


Получает или задает Matrix[N][4] 5×5 цветовой матрицы. Эта строка используется для цветовых преобразований.

Значение: матрица n1.

Matrix\_0\_4 (4 байта): Matrix[0][4]. Matrix\_1\_4 (4 байта): Matrix[1][4]. Matrix\_2\_4 (4 байта): Matrix[2][4]. Matrix\_3\_4 (4 байта): Matrix[3][4]. Matrix\_4\_4 (4 байта): Matrix[4][4]. Это значение ДОЛЖНО быть 1.0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


Получает или задает матрицу.

Значение: Матрица.

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


Получает или задает матрицу.

Значение: Матрица.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[][] |  |

