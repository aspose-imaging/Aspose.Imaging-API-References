---
title: "EmfPlusBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusBrush يحدد فرشاة رسومية لتعبئة المناطق."
type: docs
weight: 24
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

كائن EmfPlusBrush يحدد فرشاة رسومية لتعبئة المناطق.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBrushData()](#getBrushData--) | يحصل أو يعيّن بيانات الفرشاة Variable-length التي تُعرّف كائن الفرشاة المحدد في حقل Type. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | يحصل أو يعيّن بيانات الفرشاة Variable-length التي تُعرّف كائن الفرشاة المحدد في حقل Type. |
| [getType()](#getType--) | يحصل أو يضبط النوع. |
| [setType(int value)](#setType-int-) | يحصل أو يضبط النوع. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


يحصل أو يعيّن بيانات الفرشاة Variable-length التي تُعرّف كائن الفرشاة المحدد في حقل Type. يمكن أن يكون المحتوى وتنسيق البيانات مختلفين لكل نوع من أنواع الفرشاة. EmfPlusHatchBrushData (القسم 2.2.2.20) (تم) EmfPlusLinearGradientBrushData object (القسم 2.2.2.24) (تم) EmfPlusPathGradientBrushData object (القسم 2.2.2.29) (تم) EmfPlusSolidBrushData object (القسم 2.2.2.43) (تم) EmfPlusTextureBrushData object (القسم 2.2.2.45) (تم)

القيمة: بيانات الفرشاة.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


يحصل أو يعيّن بيانات الفرشاة Variable-length التي تُعرّف كائن الفرشاة المحدد في حقل Type. يمكن أن يكون المحتوى وتنسيق البيانات مختلفين لكل نوع من أنواع الفرشاة. EmfPlusHatchBrushData (القسم 2.2.2.20) (تم) EmfPlusLinearGradientBrushData object (القسم 2.2.2.24) (تم) EmfPlusPathGradientBrushData object (القسم 2.2.2.29) (تم) EmfPlusSolidBrushData object (القسم 2.2.2.43) (تم) EmfPlusTextureBrushData object (القسم 2.2.2.45) (تم)

القيمة: بيانات الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


يحصل أو يضبط النوع.

القيمة: عدد صحيح غير موقع 32‑بت يحدد نوع الفرشاة، والذي يحدد محتويات حقل BrushData. يجب أن تكون هذه القيمة معرفة في تعداد `EmfPlusBrushType`.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


يحصل أو يضبط النوع.

القيمة: عدد صحيح غير موقع 32‑بت يحدد نوع الفرشاة، والذي يحدد محتويات حقل BrushData. يجب أن تكون هذه القيمة معرفة في تعداد `EmfPlusBrushType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

