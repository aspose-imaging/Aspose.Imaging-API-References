---
title: "EmfPlusCustomLineCapOptionalData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusCustomLineCapOptionalData يحدد بيانات تعبئة وتحديد اختيارية لغطاء خط مخصص."
type: docs
weight: 37
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCustomLineCapOptionalData extends EmfPlusStructureObjectType
```

كائن EmfPlusCustomLineCapOptionalData يحدد بيانات تعبئة وتحديد اختيارية لغطاء خط مخصص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFillData()](#getFillData--) | يحصل أو يعيّن كائن EmfPlusFillPath اختياري (القسم 2.2.2.17) يحدد المسار لملء غطاء خط رسومي مخصص. |
| [setFillData(EmfPlusFillPath value)](#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-) | يحصل أو يعيّن كائن EmfPlusFillPath اختياري (القسم 2.2.2.17) يحدد المسار لملء غطاء خط رسومي مخصص. |
| [getOutlineData()](#getOutlineData--) | يحصل أو يعيّن كائن EmfPlusLinePath اختياري (القسم 2.2.2.26) يحدد المسار لتحديد حدود غطاء خط رسومي مخصص. |
| [setOutlineData(EmfPlusLinePath value)](#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-) | يحصل أو يعيّن كائن EmfPlusLinePath اختياري (القسم 2.2.2.26) يحدد المسار لتحديد حدود غطاء خط رسومي مخصص. |
### EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData--}
```
public EmfPlusCustomLineCapOptionalData()
```


### getFillData() {#getFillData--}
```
public EmfPlusFillPath getFillData()
```


يحصل أو يعيّن كائن EmfPlusFillPath اختياري (القسم 2.2.2.17) يحدد المسار لملء غطاء خط رسومي مخصص. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة CustomLineCapDataFillPath في حقل CustomLineCapDataFlags لكائن EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath)
### setFillData(EmfPlusFillPath value) {#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-}
```
public void setFillData(EmfPlusFillPath value)
```


يحصل أو يعيّن كائن EmfPlusFillPath اختياري (القسم 2.2.2.17) يحدد المسار لملء غطاء خط رسومي مخصص. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة CustomLineCapDataFillPath في حقل CustomLineCapDataFlags لكائن EmfPlusCustomLineCapData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath) |  |

### getOutlineData() {#getOutlineData--}
```
public EmfPlusLinePath getOutlineData()
```


يحصل أو يعيّن كائن EmfPlusLinePath اختياري (القسم 2.2.2.26) يحدد المسار لتحديد حدود غطاء خط رسومي مخصص. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة CustomLineCapDataLinePath في حقل CustomLineCapDataFlags لكائن EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath)
### setOutlineData(EmfPlusLinePath value) {#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-}
```
public void setOutlineData(EmfPlusLinePath value)
```


يحصل أو يعيّن كائن EmfPlusLinePath اختياري (القسم 2.2.2.26) يحدد المسار لتحديد حدود غطاء خط رسومي مخصص. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علامة CustomLineCapDataLinePath في حقل CustomLineCapDataFlags لكائن EmfPlusCustomLineCapData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath) |  |

