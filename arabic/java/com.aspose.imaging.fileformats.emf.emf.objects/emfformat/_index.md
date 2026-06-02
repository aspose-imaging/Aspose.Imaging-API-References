---
title: "EmfFormat"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmrFormat يحتوي على معلومات تحدد تنسيق بيانات الصورة في سجل EMR_COMMENT_MULTIFORMATS القسم 2.3.3.4.3."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

كائن EmrFormat يحتوي على معلومات تحدد تنسيق بيانات الصورة في سجل EMR\_COMMENT\_MULTIFORMATS (القسم 2.3.3.4.3).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSignature()](#getSignature--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد تنسيق بيانات الصورة. |
| [setSignature(int value)](#setSignature-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد تنسيق بيانات الصورة. |
| [getVersion()](#getVersion--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد رقم إصدار التنسيق. |
| [setVersion(int value)](#setVersion-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد رقم إصدار التنسيق. |
| [getSizeData()](#getSizeData--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم البيانات بالبايت. |
| [setSizeData(int value)](#setSizeData-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم البيانات بالبايت. |
| [getOffData()](#getOffData--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الإزاحة إلى البيانات من بداية حقل المعرف في سجل EMR\_COMMENT\_PUBLIC (القسم 2.3.3.4). |
| [setOffData(int value)](#setOffData-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الإزاحة إلى البيانات من بداية حقل المعرف في سجل EMR\_COMMENT\_PUBLIC (القسم 2.3.3.4). |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد تنسيق بيانات الصورة. يجب أن تكون هذه القيمة ضمن تعداد FormatSignature (القسم 2.1.14).

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد تنسيق بيانات الصورة. يجب أن تكون هذه القيمة ضمن تعداد FormatSignature (القسم 2.1.14).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد رقم إصدار التنسيق. إذا كان حقل Signature يحدد PostScript المضمّن (EPS)، يجب أن تكون هذه القيمة 0x00000001؛ وإلا يجب تجاهل هذه القيمة.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد رقم إصدار التنسيق. إذا كان حقل Signature يحدد PostScript المضمّن (EPS)، يجب أن تكون هذه القيمة 0x00000001؛ وإلا يجب تجاهل هذه القيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم البيانات بالبايت.

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم البيانات بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الإزاحة إلى البيانات من بداية حقل المعرف في سجل EMR\_COMMENT\_PUBLIC (القسم 2.3.3.4). يجب أن تكون الإزاحة محاذاة 32 بت.

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الإزاحة إلى البيانات من بداية حقل المعرف في سجل EMR\_COMMENT\_PUBLIC (القسم 2.3.3.4). يجب أن تكون الإزاحة محاذاة 32 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

