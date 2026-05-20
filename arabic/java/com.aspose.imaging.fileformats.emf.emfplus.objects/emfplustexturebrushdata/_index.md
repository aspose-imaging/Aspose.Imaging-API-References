---
title: "EmfPlusTextureBrushData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد كائن EmfPlusTextureBrushData صورة نسيج لفرشاة رسومية."
type: docs
weight: 77
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

يحدد كائن EmfPlusTextureBrushData صورة نسيج لفرشاة رسومية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد البيانات في حقل OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد البيانات في حقل OptionalData. |
| [getWrapMode()](#getWrapMode--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت من تعداد WrapMode (القسم 2.1.1.34) يحدد طريقة تكرار صورة النسيج عبر الشكل عندما تكون الصورة أصغر من المنطقة التي يتم ملؤها. |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت من تعداد WrapMode (القسم 2.1.1.34) يحدد طريقة تكرار صورة النسيج عبر الشكل عندما تكون الصورة أصغر من المنطقة التي يتم ملؤها. |
| [getOptionalData()](#getOptionalData--) | يحصل أو يعيّن كائن EmfPlusTextureBrushOptionalData اختياري (القسم 2.2.2.46) يحدد بيانات إضافية لفرشاة النسيج. |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | يحصل أو يعيّن كائن EmfPlusTextureBrushOptionalData اختياري (القسم 2.2.2.46) يحدد بيانات إضافية لفرشاة النسيج. |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد البيانات في حقل OptionalData. يجب أن تتكون هذه القيمة من أعلام BrushData (القسم 2.1.2.1). الأعلام التالية ذات صلة بفرشاة النسيج: BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد البيانات في حقل OptionalData. يجب أن تتكون هذه القيمة من أعلام BrushData (القسم 2.1.2.1). الأعلام التالية ذات صلة بفرشاة النسيج: BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت من تعداد WrapMode (القسم 2.1.1.34) يحدد طريقة تكرار صورة النسيج عبر الشكل عندما تكون الصورة أصغر من المنطقة التي يتم ملؤها.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت من تعداد WrapMode (القسم 2.1.1.34) يحدد طريقة تكرار صورة النسيج عبر الشكل عندما تكون الصورة أصغر من المنطقة التي يتم ملؤها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


يحصل أو يعيّن كائن EmfPlusTextureBrushOptionalData اختياري (القسم 2.2.2.46) يحدد بيانات إضافية لفرشاة النسيج. المحتويات المحددة لهذا الحقل يتم تحديدها بواسطة قيمة حقل BrushDataFlags

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


يحصل أو يعيّن كائن EmfPlusTextureBrushOptionalData اختياري (القسم 2.2.2.46) يحدد بيانات إضافية لفرشاة النسيج. المحتويات المحددة لهذا الحقل يتم تحديدها بواسطة قيمة حقل BrushDataFlags

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

