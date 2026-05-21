---
title: "EmfPlusBlendBase"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الكائن الأساسي لكائنات الدمج"
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

الكائن الأساسي لكائنات الدمج
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | يحصل أو يضبط مواضع الدمج مصفوفة من قيم PositionCount عائمة 32-بت تحدد نسب المسافة على طول خط التدرج. |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | يحصل أو يضبط مواضع الدمج مصفوفة من قيم PositionCount عائمة 32-بت تحدد نسب المسافة على طول خط التدرج. |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


يحصل أو يضبط مواضع الدمج مصفوفة من قيم PositionCount عائمة 32-بت تحدد نسب المسافة على طول خط التدرج. يجب أن يكون كل عنصر رقمًا بين 0.0 و 1.0 شاملًا. بالنسبة لفرشاة التدرج الخطي، 0.0 تمثل نقطة البداية و 1.0 تمثل نقطة النهاية. بالنسبة لفرشاة التدرج المساري، 0.0 تمثل نقطة المنتصف و 1.0 تمثل نقطة النهاية.

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


يحصل أو يضبط مواضع الدمج مصفوفة من قيم PositionCount عائمة 32-بت تحدد نسب المسافة على طول خط التدرج. يجب أن يكون كل عنصر رقمًا بين 0.0 و 1.0 شاملًا. بالنسبة لفرشاة التدرج الخطي، 0.0 تمثل نقطة البداية و 1.0 تمثل نقطة النهاية. بالنسبة لفرشاة التدرج المساري، 0.0 تمثل نقطة المنتصف و 1.0 تمثل نقطة النهاية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float[] |  |

