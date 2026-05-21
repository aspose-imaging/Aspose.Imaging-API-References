---
title: "EmfPlusColorMatrixEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن ColorMatrixEffect يحدد تحويلًا أفينيًا يُطبق على صورة."
type: docs
weight: 29
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

كائن ColorMatrixEffect يحدد تحويلًا أفينيًا يُطبق على صورة.

يتم تحديد صور البت ماب بواسطة كائنات EmfPlusBitmap (القسم 2.2.2.2). يتم تنفيذ تأثير مصفوفة اللون بضرب متجه اللون في كائن ColorMatrixEffect. يمكن لمصفوفة لون 5×5 إجراء تحويل خطي، بما في ذلك الانعكاس، الدوران، القص، أو التحجيم متبوعًا بعملية إزاحة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | يحصل أو يعيّن العنصر Matrix[N][0] من مصفوفة اللون 5×5. |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | يحصل أو يعيّن العنصر Matrix[N][0] من مصفوفة اللون 5×5. |
| [getMatrixN1()](#getMatrixN1--) | يحصل أو يعيّن العنصر Matrix[N][1] من مصفوفة اللون 5×5. |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | يحصل أو يعيّن العنصر Matrix[N][1] من مصفوفة اللون 5×5. |
| [getMatrixN2()](#getMatrixN2--) | يحصل أو يعيّن العنصر Matrix[N][2] من مصفوفة اللون 5×5. |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | يحصل أو يعيّن العنصر Matrix[N][2] من مصفوفة اللون 5×5. |
| [getMatrixN3()](#getMatrixN3--) | يحصل أو يعيّن العنصر Matrix[N][3] من مصفوفة اللون 5×5. |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | يحصل أو يعيّن العنصر Matrix[N][3] من مصفوفة اللون 5×5. |
| [getMatrixN4()](#getMatrixN4--) | يحصل أو يعيّن العنصر Matrix[N][4] من مصفوفة اللون 5×5. |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | يحصل أو يعيّن العنصر Matrix[N][4] من مصفوفة اللون 5×5. |
| [getMatrix()](#getMatrix--) | يحصل أو يعيّن المصفوفة. |
| [setMatrix(int[][] value)](#setMatrix-int-----) | يحصل أو يعيّن المصفوفة. |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


يحصل أو يعيّن العنصر Matrix[N][0] من مصفوفة اللون 5×5. يُستخدم هذا الصف للتحويلات.

Matrix\_0\_0 (4 بايت): Matrix[0][0]، وهو العامل للون الأحمر. Matrix\_1\_0 (4 بايت): Matrix[1][0]. Matrix\_2\_0 (4 بايت): Matrix[2][0]. Matrix\_3\_0 (4 بايت): Matrix[3][0]. Matrix\_4\_0 (4 بايت): Matrix[4][0]. يجب أن تكون هذه القيمة 0.0.

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


يحصل أو يعيّن العنصر Matrix[N][0] من مصفوفة اللون 5×5. يُستخدم هذا الصف للتحويلات.

Matrix\_0\_0 (4 بايت): Matrix[0][0]، وهو العامل للون الأحمر. Matrix\_1\_0 (4 بايت): Matrix[1][0]. Matrix\_2\_0 (4 بايت): Matrix[2][0]. Matrix\_3\_0 (4 بايت): Matrix[3][0]. Matrix\_4\_0 (4 بايت): Matrix[4][0]. يجب أن تكون هذه القيمة 0.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


يحصل أو يعيّن العنصر Matrix[N][1] من مصفوفة اللون 5×5. يُستخدم هذا الصف للتحويلات.

القيمة: المصفوفة n1.

Matrix\_0\_1 (4 بايت): Matrix[0][1]. Matrix\_1\_1 (4 بايت): Matrix[1][1]، وهو العامل للون الأخضر. Matrix\_2\_1 (4 بايت): Matrix[2][1]. Matrix\_3\_1 (4 بايت): Matrix[3][1]. Matrix\_4\_0 (4 بايت): Matrix[4][0]. يجب أن تكون هذه القيمة 0.0.

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


يحصل أو يعيّن العنصر Matrix[N][1] من مصفوفة اللون 5×5. يُستخدم هذا الصف للتحويلات.

القيمة: المصفوفة n1.

Matrix\_0\_1 (4 بايت): Matrix[0][1]. Matrix\_1\_1 (4 بايت): Matrix[1][1]، وهو العامل للون الأخضر. Matrix\_2\_1 (4 بايت): Matrix[2][1]. Matrix\_3\_1 (4 بايت): Matrix[3][1]. Matrix\_4\_0 (4 بايت): Matrix[4][0]. يجب أن تكون هذه القيمة 0.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


يحصل أو يعيّن العنصر Matrix[N][2] من مصفوفة اللون 5×5. يُستخدم هذا الصف للتحويلات.

القيمة: المصفوفة n1.

Matrix\_0\_2 (4 بايت): Matrix[0][2]. Matrix\_1\_2 (4 بايت): Matrix[1][2]. Matrix\_2\_2 (4 بايت): Matrix[2][2]، وهو العامل للون الأزرق. Matrix\_3\_1 (4 بايت): Matrix[3][1]. Matrix\_4\_0 (4 بايت): Matrix[4][0]. يجب أن تكون هذه القيمة 0.0.

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


يحصل أو يعيّن العنصر Matrix[N][2] من مصفوفة اللون 5×5. يُستخدم هذا الصف للتحويلات.

القيمة: المصفوفة n1.

Matrix\_0\_2 (4 بايت): Matrix[0][2]. Matrix\_1\_2 (4 بايت): Matrix[1][2]. Matrix\_2\_2 (4 بايت): Matrix[2][2]، وهو العامل للون الأزرق. Matrix\_3\_1 (4 بايت): Matrix[3][1]. Matrix\_4\_0 (4 بايت): Matrix[4][0]. يجب أن تكون هذه القيمة 0.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


يحصل أو يعيّن العنصر Matrix[N][3] من مصفوفة اللون 5×5. يُستخدم هذا الصف للتحويلات.

القيمة: المصفوفة n1.

Matrix\_0\_3 (4 بايت): Matrix[0][3]. Matrix\_1\_3 (4 بايت): Matrix[1][3]. Matrix\_2\_3 (4 بايت): Matrix[2][3]. Matrix\_3\_3 (4 بايت): Matrix[3][3]، وهو العامل للـ alpha (الشفافية). Matrix\_4\_0 (4 بايت): Matrix[4][0]. يجب أن تكون هذه القيمة 0.0.

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


يحصل أو يعيّن العنصر Matrix[N][3] من مصفوفة اللون 5×5. يُستخدم هذا الصف للتحويلات.

القيمة: المصفوفة n1.

Matrix\_0\_3 (4 بايت): Matrix[0][3]. Matrix\_1\_3 (4 بايت): Matrix[1][3]. Matrix\_2\_3 (4 بايت): Matrix[2][3]. Matrix\_3\_3 (4 بايت): Matrix[3][3]، وهو العامل للـ alpha (الشفافية). Matrix\_4\_0 (4 بايت): Matrix[4][0]. يجب أن تكون هذه القيمة 0.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


يسترجع أو يعيّن Matrix[N][4] من مصفوفة الألوان 5×5. يُستخدم هذا الصف في تحويلات الألوان.

القيمة: المصفوفة n1.

Matrix\_0\_4 (4 بايت): Matrix[0][4]. Matrix\_1\_4 (4 بايت): Matrix[1][4]. Matrix\_2\_4 (4 بايت): Matrix[2][4]. Matrix\_3\_4 (4 بايت): Matrix[3][4]. Matrix\_4\_4 (4 بايت): Matrix[4][4]. يجب أن تكون هذه القيمة 1.0.

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


يسترجع أو يعيّن Matrix[N][4] من مصفوفة الألوان 5×5. يُستخدم هذا الصف في تحويلات الألوان.

القيمة: المصفوفة n1.

Matrix\_0\_4 (4 بايت): Matrix[0][4]. Matrix\_1\_4 (4 بايت): Matrix[1][4]. Matrix\_2\_4 (4 بايت): Matrix[2][4]. Matrix\_3\_4 (4 بايت): Matrix[3][4]. Matrix\_4\_4 (4 بايت): Matrix[4][4]. يجب أن تكون هذه القيمة 1.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


يحصل أو يعيّن المصفوفة.

القيمة: المصفوفة.

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


يحصل أو يعيّن المصفوفة.

القيمة: المصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[][] |  |

