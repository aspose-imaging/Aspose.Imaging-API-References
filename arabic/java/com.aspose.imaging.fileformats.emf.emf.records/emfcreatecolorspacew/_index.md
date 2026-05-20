---
title: "EmfCreateColorSpaceW"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_CREATECOLORSPACEW ينشئ كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف Unicode."
type: docs
weight: 37
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

سجل EMR_CREATECOLORSPACEW ينشئ كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف Unicode.

يمكن اختيار كائن مساحة اللون المنطقي المحدد بواسطة هذا السجل إلى سياق جهاز التشغيل بواسطة سجل EMR\_SETCOLORSPACE (القسم 2.3.8.7)، الذي يحدد مساحة اللون المنطقية المستخدمة في عمليات الرسومات اللاحقة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfCreateColorSpaceW`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhCS()](#getIhCS--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [getLcs()](#getLcs--) | الحصول أو تعيين كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) الذي يمكنه تحديد اسم ملف تعريف اللون في أحرف Unicode UTF16-LE |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | الحصول أو تعيين كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) الذي يمكنه تحديد اسم ملف تعريف اللون في أحرف Unicode UTF16-LE |
| [getDwFlags()](#getDwFlags--) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يوفر معلومات حول البيانات في هذا السجل. |
| [setDwFlags(int value)](#setDwFlags-int-) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يوفر معلومات حول البيانات في هذا السجل. |
| [getCbData()](#getCbData--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم حقل Data بالبايت. |
| [setCbData(int value)](#setCbData-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم حقل Data بالبايت. |
| [getData()](#getData--) | الحصول أو تعيين مصفوفة اختيارية من البايتات تحدد بيانات ملف تعريف اللون. |
| [setData(byte[] value)](#setData-byte---) | الحصول أو تعيين مصفوفة اختيارية من البايتات تحدد بيانات ملف تعريف اللون. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfCreateColorSpaceW`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpaceW getLcs()
```


الحصول أو تعيين كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) الذي يمكنه تحديد اسم ملف تعريف اللون في أحرف Unicode UTF16-LE

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


الحصول أو تعيين كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) الذي يمكنه تحديد اسم ملف تعريف اللون في أحرف Unicode UTF16-LE

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يوفر معلومات حول البيانات في هذا السجل.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يوفر معلومات حول البيانات في هذا السجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم حقل Data بالبايت.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم حقل Data بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


الحصول أو تعيين مصفوفة اختيارية من البايتات تحدد بيانات ملف تعريف اللون.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


الحصول أو تعيين مصفوفة اختيارية من البايتات تحدد بيانات ملف تعريف اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

