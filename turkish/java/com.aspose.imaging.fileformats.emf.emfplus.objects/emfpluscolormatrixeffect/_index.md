---
title: "EmfPlusColorMatrixEffect"
second_title: "Aspose.Imaging for Java API Referansı"
description: "ColorMatrixEffect nesnesi, bir görüntüye uygulanacak bir afin dönüşümünü belirtir."
type: docs
weight: 29
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

ColorMatrixEffect nesnesi, bir görüntüye uygulanacak bir afin dönüşümünü belirtir.

Bitmap görüntüler EmfPlusBitmap nesneleri (bölüm 2.2.2.2) ile belirtilir. Bir renk matrisi etkisi, bir renk vektörünün ColorMatrixEffect nesnesiyle çarpılmasıyla gerçekleştirilir. 5x5 renk matrisi, yansıma, döndürme, kaydırma veya ölçeklendirme ve ardından bir çevirme içeren lineer bir dönüşüm yapabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | 5x5 renk matrisinin Matrix[N][0] değerini alır veya ayarlar. |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | 5x5 renk matrisinin Matrix[N][0] değerini alır veya ayarlar. |
| [getMatrixN1()](#getMatrixN1--) | 5x5 renk matrisinin Matrix[N][1] değerini alır veya ayarlar. |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | 5x5 renk matrisinin Matrix[N][1] değerini alır veya ayarlar. |
| [getMatrixN2()](#getMatrixN2--) | 5x5 renk matrisinin Matrix[N][2] değerini alır veya ayarlar. |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | 5x5 renk matrisinin Matrix[N][2] değerini alır veya ayarlar. |
| [getMatrixN3()](#getMatrixN3--) | 5x5 renk matrisinin Matrix[N][3] değerini alır veya ayarlar. |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | 5x5 renk matrisinin Matrix[N][3] değerini alır veya ayarlar. |
| [getMatrixN4()](#getMatrixN4--) | 5x5 renk matrisinin Matrix[N][4] değerini alır veya ayarlar. |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | 5x5 renk matrisinin Matrix[N][4] değerini alır veya ayarlar. |
| [getMatrix()](#getMatrix--) | Matrisi alır veya ayarlar. |
| [setMatrix(int[][] value)](#setMatrix-int-----) | Matrisi alır veya ayarlar. |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


5x5 renk matrisinin Matrix[N][0] değerini alır veya ayarlar. Bu satır dönüşümler için kullanılır.

Matrix\_0\_0 (4 bayt): Matrix[0][0], kırmızı renk faktörüdür. Matrix\_1\_0 (4 bayt): Matrix[1][0]. Matrix\_2\_0 (4 bayt): Matrix[2][0]. Matrix\_3\_0 (4 bayt): Matrix[3][0]. Matrix\_4\_0 (4 bayt): Matrix[4][0]. Bu değer 0.0 olmalıdır.

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


5x5 renk matrisinin Matrix[N][0] değerini alır veya ayarlar. Bu satır dönüşümler için kullanılır.

Matrix\_0\_0 (4 bayt): Matrix[0][0], kırmızı renk faktörüdür. Matrix\_1\_0 (4 bayt): Matrix[1][0]. Matrix\_2\_0 (4 bayt): Matrix[2][0]. Matrix\_3\_0 (4 bayt): Matrix[3][0]. Matrix\_4\_0 (4 bayt): Matrix[4][0]. Bu değer 0.0 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


5x5 renk matrisinin Matrix[N][1] değerini alır veya ayarlar. Bu satır dönüşümler için kullanılır.

Değer: Matris n1.

Matrix\_0\_1 (4 bayt): Matrix[0][1]. Matrix\_1\_1 (4 bayt): Matrix[1][1], yeşil renk faktörüdür. Matrix\_2\_1 (4 bayt): Matrix[2][1]. Matrix\_3\_1 (4 bayt): Matrix[3][1]. Matrix\_4\_0 (4 bayt): Matrix[4][0]. Bu değer 0.0 olmalıdır.

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


5x5 renk matrisinin Matrix[N][1] değerini alır veya ayarlar. Bu satır dönüşümler için kullanılır.

Değer: Matris n1.

Matrix\_0\_1 (4 bayt): Matrix[0][1]. Matrix\_1\_1 (4 bayt): Matrix[1][1], yeşil renk faktörüdür. Matrix\_2\_1 (4 bayt): Matrix[2][1]. Matrix\_3\_1 (4 bayt): Matrix[3][1]. Matrix\_4\_0 (4 bayt): Matrix[4][0]. Bu değer 0.0 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


5x5 renk matrisinin Matrix[N][2] değerini alır veya ayarlar. Bu satır dönüşümler için kullanılır.

Değer: Matris n1.

Matrix\_0\_2 (4 bayt): Matrix[0][2]. Matrix\_1\_2 (4 bayt): Matrix[1][2]. Matrix\_2\_2 (4 bayt): Matrix[2][2], mavi renk faktörüdür. Matrix\_3\_1 (4 bayt): Matrix[3][1]. Matrix\_4\_0 (4 bayt): Matrix[4][0]. Bu değer 0.0 olmalıdır.

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


5x5 renk matrisinin Matrix[N][2] değerini alır veya ayarlar. Bu satır dönüşümler için kullanılır.

Değer: Matris n1.

Matrix\_0\_2 (4 bayt): Matrix[0][2]. Matrix\_1\_2 (4 bayt): Matrix[1][2]. Matrix\_2\_2 (4 bayt): Matrix[2][2], mavi renk faktörüdür. Matrix\_3\_1 (4 bayt): Matrix[3][1]. Matrix\_4\_0 (4 bayt): Matrix[4][0]. Bu değer 0.0 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


5x5 renk matrisinin Matrix[N][3] değerini alır veya ayarlar. Bu satır dönüşümler için kullanılır.

Değer: Matris n1.

Matrix\_0\_3 (4 bayt): Matrix[0][3]. Matrix\_1\_3 (4 bayt): Matrix[1][3]. Matrix\_2\_3 (4 bayt): Matrix[2][3]. Matrix\_3\_3 (4 bayt): Matrix[3][3], alfa (şeffaflık) faktörüdür. Matrix\_4\_0 (4 bayt): Matrix[4][0]. Bu değer 0.0 olmalıdır.

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


5x5 renk matrisinin Matrix[N][3] değerini alır veya ayarlar. Bu satır dönüşümler için kullanılır.

Değer: Matris n1.

Matrix\_0\_3 (4 bayt): Matrix[0][3]. Matrix\_1\_3 (4 bayt): Matrix[1][3]. Matrix\_2\_3 (4 bayt): Matrix[2][3]. Matrix\_3\_3 (4 bayt): Matrix[3][3], alfa (şeffaflık) faktörüdür. Matrix\_4\_0 (4 bayt): Matrix[4][0]. Bu değer 0.0 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


5x5 renk matrisinin Matrix[N][4] değerini alır veya ayarlar. Bu satır renk dönüşümleri için kullanılır.

Değer: Matris n1.

Matrix\_0\_4 (4 bayt): Matrix[0][4]. Matrix\_1\_4 (4 bayt): Matrix[1][4]. Matrix\_2\_4 (4 bayt): Matrix[2][4]. Matrix\_3\_4 (4 bayt): Matrix[3][4]. Matrix\_4\_4 (4 bayt): Matrix[4][4]. Bu değer 1.0 OLMALIDIR.

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


5x5 renk matrisinin Matrix[N][4] değerini alır veya ayarlar. Bu satır renk dönüşümleri için kullanılır.

Değer: Matris n1.

Matrix\_0\_4 (4 bayt): Matrix[0][4]. Matrix\_1\_4 (4 bayt): Matrix[1][4]. Matrix\_2\_4 (4 bayt): Matrix[2][4]. Matrix\_3\_4 (4 bayt): Matrix[3][4]. Matrix\_4\_4 (4 bayt): Matrix[4][4]. Bu değer 1.0 OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


Matrisi alır veya ayarlar.

Değer: Matris.

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


Matrisi alır veya ayarlar.

Değer: Matris.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[][] |  |

