---
title: "EmfPlusBlurEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن BlurEffect يحدد انخفاضًا في الفرق في الشدة بين البكسلات في الصورة."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

كائن BlurEffect يحدد انخفاضًا في الفرق في الشدة بين البكسلات في الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | يحصل أو يعيّن عددًا عائمًا 32-بت يحدد نصف قطر الضبابية بالبكسل، وهو ما يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. |
| [setBlurRadius(float value)](#setBlurRadius-float-) | يحصل أو يعيّن عددًا عائمًا 32-بت يحدد نصف قطر الضبابية بالبكسل، وهو ما يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. |
| [getExpandEdge()](#getExpandEdge--) | يحصل أو يعيّن قيمة منطقية 32-بت تحدد ما إذا كانت الصورة النقطية تتوسع بمقدار يساوي قيمة BlurRadius لإنتاج حواف ناعمة. |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | يحصل أو يعيّن قيمة منطقية 32-بت تحدد ما إذا كانت الصورة النقطية تتوسع بمقدار يساوي قيمة BlurRadius لإنتاج حواف ناعمة. |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


يحصل أو يعيّن عددًا عائمًا 32-بت يحدد نصف قطر الضبابية بالبكسل، وهو ما يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. يجب أن تكون هذه القيمة في النطاق من 0.0 إلى 255.0.

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


يحصل أو يعيّن عددًا عائمًا 32-بت يحدد نصف قطر الضبابية بالبكسل، وهو ما يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. يجب أن تكون هذه القيمة في النطاق من 0.0 إلى 255.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


يحصل أو يعيّن قيمة منطقية 32-بت تحدد ما إذا كانت الصورة النقطية تتوسع بمقدار يساوي قيمة BlurRadius لإنتاج حواف ناعمة. يجب أن تكون هذه القيمة واحدة من التالي: FALSE 0x00000000 يجب ألا يتغير حجم الصورة النقطية، ويجب قص حوافها الناعمة إلى حجم BlurRadius. TRUE 0x00000001 يجب أن يتوسع حجم الصورة النقطية بمقدار يساوي BlurRadius لإنتاج حواف ناعمة.

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


يحصل أو يعيّن قيمة منطقية 32-بت تحدد ما إذا كانت الصورة النقطية تتوسع بمقدار يساوي قيمة BlurRadius لإنتاج حواف ناعمة. يجب أن تكون هذه القيمة واحدة من التالي: FALSE 0x00000000 يجب ألا يتغير حجم الصورة النقطية، ويجب قص حوافها الناعمة إلى حجم BlurRadius. TRUE 0x00000001 يجب أن يتوسع حجم الصورة النقطية بمقدار يساوي BlurRadius لإنتاج حواف ناعمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

