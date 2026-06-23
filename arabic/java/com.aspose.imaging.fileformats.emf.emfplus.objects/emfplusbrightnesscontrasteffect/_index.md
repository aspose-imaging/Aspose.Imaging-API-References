---
title: "EmfPlusBrightnessContrastEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن BrightnessContrastEffect يحدد توسعًا أو انكماشًا لأوضح وأظلم مناطق الصورة."
type: docs
weight: 23
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

كائن BrightnessContrastEffect يحدد توسعًا أو انكماشًا لأوضح وأظلم مناطق الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد مستوى السطوع. |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد مستوى السطوع. |
| [getContrastLevel()](#getContrastLevel--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد مستوى التباين. |
| [setContrastLevel(int value)](#setContrastLevel-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد مستوى التباين. |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد مستوى السطوع. يجب أن تكون هذه القيمة في النطاق -255 إلى 255، مع التأثيرات التالية: -255 \\u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل سطوع الصورة. 0 قيمة 0 تحدد أن السطوع يجب ألا يتغير. 0 < value \\u2264 255 كلما زادت القيمة، يجب أن يزيد سطوع الصورة.

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد مستوى السطوع. يجب أن تكون هذه القيمة في النطاق -255 إلى 255، مع التأثيرات التالية: -255 \\u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل سطوع الصورة. 0 قيمة 0 تحدد أن السطوع يجب ألا يتغير. 0 < value \\u2264 255 كلما زادت القيمة، يجب أن يزيد سطوع الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد مستوى التباين. يجب أن تكون هذه القيمة في النطاق -100 إلى 100، مع التأثيرات التالية: -100 \\u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل تباين الصورة. 0 قيمة 0 تحدد أن التباين يجب ألا يتغير. 0 < value \\u2264 100 كلما زادت القيمة، يجب أن يزيد تباين الصورة.

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد مستوى التباين. يجب أن تكون هذه القيمة في النطاق -100 إلى 100، مع التأثيرات التالية: -100 \\u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل تباين الصورة. 0 قيمة 0 تحدد أن التباين يجب ألا يتغير. 0 < value \\u2264 100 كلما زادت القيمة، يجب أن يزيد تباين الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

