---
title: "EmfPlusSharpenEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد كائن SharpenEffect زيادة في فرق الشدة بين بكسلات الصورة."
type: docs
weight: 72
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

يحدد كائن SharpenEffect زيادة في فرق الشدة بين بكسلات الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | يحصل أو يضبط عددًا عائمًا 32-بت يحدد نصف قطر الشحذ بالبكسل، والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. |
| [setRadius(float value)](#setRadius-float-) | يحصل أو يضبط عددًا عائمًا 32-بت يحدد نصف قطر الشحذ بالبكسل، والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. |
| [getAmount()](#getAmount--) | يحصل أو يضبط عددًا عائمًا 32-بت يحدد الفرق في الشدة بين بكسل معين والبكسلات المحيطة. |
| [setAmount(float value)](#setAmount-float-) | يحصل أو يضبط عددًا عائمًا 32-بت يحدد الفرق في الشدة بين بكسل معين والبكسلات المحيطة. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


يحصل أو يضبط عددًا عائمًا 32-بت يحدد نصف قطر الشحذ بالبكسل، والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. كلما زادت هذه القيمة، يزداد عدد البكسلات المشاركة في الحساب، ويجب أن يصبح البت ماب الناتج أكثر حدة.

القيمة: نصف القطر.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


يحصل أو يضبط عددًا عائمًا 32-بت يحدد نصف قطر الشحذ بالبكسل، والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. كلما زادت هذه القيمة، يزداد عدد البكسلات المشاركة في الحساب، ويجب أن يصبح البت ماب الناتج أكثر حدة.

القيمة: نصف القطر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


يحصل أو يضبط عددًا عائمًا 32-بت يحدد الفرق في الشدة بين بكسل معين والبكسلات المحيطة. 0 يعني أنه لا يجب تنفيذ الشحذ. 0 < القيمة \\u2264 100 كلما زادت هذه القيمة، يجب أن يزداد الفرق في الشدة بين البكسلات.

القيمة: المقدار.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


يحصل أو يضبط عددًا عائمًا 32-بت يحدد الفرق في الشدة بين بكسل معين والبكسلات المحيطة. 0 يعني أنه لا يجب تنفيذ الشحذ. 0 < القيمة \\u2264 100 كلما زادت هذه القيمة، يجب أن يزداد الفرق في الشدة بين البكسلات.

القيمة: المقدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

