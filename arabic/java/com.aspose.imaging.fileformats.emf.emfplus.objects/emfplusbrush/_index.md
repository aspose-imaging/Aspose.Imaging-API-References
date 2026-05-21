---
title: "EmfPlusBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusBrush يحدد فرشاة رسومية لملء المناطق."
type: docs
weight: 24
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

كائن EmfPlusBrush يحدد فرشاة رسومية لملء المناطق.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBrushData()](#getBrushData--) | يحصل أو يعيّن بيانات Brush بيانات ذات طول متغيّر تُعرّف كائن الفرشاة المحدد في حقل Type. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | يحصل أو يعيّن بيانات Brush بيانات ذات طول متغيّر تُعرّف كائن الفرشاة المحدد في حقل Type. |
| [getType()](#getType--) | يحصل أو يعيّن النوع. |
| [setType(int value)](#setType-int-) | يحصل أو يعيّن النوع. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


يحصل أو يعيّن بيانات Brush بيانات ذات طول متغيّر تُعرّف كائن الفرشاة المحدد في حقل Type. يمكن أن يكون محتوى البيانات وتنسيقها مختلفين لكل نوع فرشاة. EmfPlusHatchBrushData (section 2.2.2.20) (done) كائن EmfPlusLinearGradientBrushData (section 2.2.2.24) (done) كائن EmfPlusPathGradientBrushData (section 2.2.2.29) (done) كائن EmfPlusSolidBrushData (section 2.2.2.43) (done) كائن EmfPlusTextureBrushData (section 2.2.2.45) (done)

القيمة: بيانات الفرشاة.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


يحصل أو يعيّن بيانات Brush بيانات ذات طول متغيّر تُعرّف كائن الفرشاة المحدد في حقل Type. يمكن أن يكون محتوى البيانات وتنسيقها مختلفين لكل نوع فرشاة. EmfPlusHatchBrushData (section 2.2.2.20) (done) كائن EmfPlusLinearGradientBrushData (section 2.2.2.24) (done) كائن EmfPlusPathGradientBrushData (section 2.2.2.29) (done) كائن EmfPlusSolidBrushData (section 2.2.2.43) (done) كائن EmfPlusTextureBrushData (section 2.2.2.45) (done)

القيمة: بيانات الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


يحصل أو يعيّن النوع.

القيمة: عدد صحيح غير موقع 32‑بت يحدد نوع الفرشاة، والذي يحدد محتويات حقل BrushData. يجب أن تكون هذه القيمة معرفة في تعداد `EmfPlusBrushType`.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


يحصل أو يعيّن النوع.

القيمة: عدد صحيح غير موقع 32‑بت يحدد نوع الفرشاة، والذي يحدد محتويات حقل BrushData. يجب أن تكون هذه القيمة معرفة في تعداد `EmfPlusBrushType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

