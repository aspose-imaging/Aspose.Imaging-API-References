---
title: "EmfPlusPenData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusPenData يحدد خصائص قلم رسومي."
type: docs
weight: 64
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

كائن EmfPlusPenData يحدد خصائص قلم رسومي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد البيانات في حقل OptionalData. |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد البيانات في حقل OptionalData. |
| [getPenUnit()](#getPenUnit--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد وحدات القياس للقلم. |
| [setPenUnit(int value)](#setPenUnit-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد وحدات القياس للقلم. |
| [getPenWidth()](#getPenWidth--) | يحصل أو يضبط قيمة عائمة 32-بت تحدد عرض الخط المرسوم بالقلم بالوحدات المحددة في حقل PenUnit. |
| [setPenWidth(float value)](#setPenWidth-float-) | يحصل أو يضبط قيمة عائمة 32-بت تحدد عرض الخط المرسوم بالقلم بالوحدات المحددة في حقل PenUnit. |
| [getOptionalData()](#getOptionalData--) | يحصل أو يضبط كائن EmfPlusPenOptionalData اختياري (section 2.2.2.34) يحدد بيانات إضافية لكائن القلم. |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | يحصل أو يضبط كائن EmfPlusPenOptionalData اختياري (section 2.2.2.34) يحدد بيانات إضافية لكائن القلم. |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد البيانات في حقل OptionalData. يجب أن تتكون هذه القيمة من أعلام PenData (section 2.1.2.7).

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد البيانات في حقل OptionalData. يجب أن تتكون هذه القيمة من أعلام PenData (section 2.1.2.7).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد وحدات القياس للقلم. يجب أن تكون القيمة من تعداد UnitType (section 2.1.1.33).

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد وحدات القياس للقلم. يجب أن تكون القيمة من تعداد UnitType (section 2.1.1.33).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


يحصل أو يضبط قيمة عائمة 32-بت تحدد عرض الخط المرسوم بالقلم بالوحدات المحددة في حقل PenUnit. إذا تم تحديد عرض صفر، يتم استخدام قيمة حد أدنى تُحدد بواسطة الوحدات.

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


يحصل أو يضبط قيمة عائمة 32-بت تحدد عرض الخط المرسوم بالقلم بالوحدات المحددة في حقل PenUnit. إذا تم تحديد عرض صفر، يتم استخدام قيمة حد أدنى تُحدد بواسطة الوحدات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


يحصل أو يضبط كائن EmfPlusPenOptionalData اختياري (section 2.2.2.34) يحدد بيانات إضافية لكائن القلم. يتم تحديد محتويات هذا الحقل بناءً على قيمة حقل PenDataFlags.

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


يحصل أو يضبط كائن EmfPlusPenOptionalData اختياري (section 2.2.2.34) يحدد بيانات إضافية لكائن القلم. يتم تحديد محتويات هذا الحقل بناءً على قيمة حقل PenDataFlags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |

