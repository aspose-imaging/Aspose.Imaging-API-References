---
title: "EmfPlusSharpenEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن SharpenEffect يحدد زيادة في فرق الشدة بين بكسلات الصورة."
type: docs
weight: 72
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

كائن SharpenEffect يحدد زيادة في فرق الشدة بين بكسلات الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | يحصل أو يعيّن عددًا عائمًا 32-بت يحدد نصف قطر الشحذ بالبكسل، والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. |
| [setRadius(float value)](#setRadius-float-) | يحصل أو يعيّن عددًا عائمًا 32-بت يحدد نصف قطر الشحذ بالبكسل، والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. |
| [getAmount()](#getAmount--) | يحصل أو يعيّن عددًا عائمًا 32-بت يحدد الفرق في الشدة بين بكسل معين والبكسلات المحيطة. |
| [setAmount(float value)](#setAmount-float-) | يحصل أو يعيّن عددًا عائمًا 32-بت يحدد الفرق في الشدة بين بكسل معين والبكسلات المحيطة. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


يحصل أو يعيّن عددًا عائمًا 32-بت يحدد نصف قطر الشحذ بالبكسل، والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. كلما زادت هذه القيمة، يزداد عدد البكسلات المشاركة في الحساب، ويجب أن يصبح البت ماب الناتج SHOULD أكثر حدة.

القيمة: نصف القطر.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


يحصل أو يعيّن عددًا عائمًا 32-بت يحدد نصف قطر الشحذ بالبكسل، والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. كلما زادت هذه القيمة، يزداد عدد البكسلات المشاركة في الحساب، ويجب أن يصبح البت ماب الناتج SHOULD أكثر حدة.

القيمة: نصف القطر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


يحصل أو يعيّن عددًا عائمًا 32-بت يحدد الفرق في الشدة بين بكسل معين والبكسلات المحيطة. 0 يحدد أن الشحذ MUST NOT يتم. 0 < value \\u2264 100 كلما زادت هذه القيمة، يجب أن يزداد الفرق في الشدة بين البكسلات SHOULD.

القيمة: المقدار.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


يحصل أو يعيّن عددًا عائمًا 32-بت يحدد الفرق في الشدة بين بكسل معين والبكسلات المحيطة. 0 يحدد أن الشحذ MUST NOT يتم. 0 < value \\u2264 100 كلما زادت هذه القيمة، يجب أن يزداد الفرق في الشدة بين البكسلات SHOULD.

القيمة: المقدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

