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

سجل EMR\_CREATECOLORSPACEW ينشئ كائن مساحة ألوان منطقية من ملف تعريف ألوان يحمل اسمًا مكوّنًا من أحرف Unicode.

يمكن اختيار كائن مساحة اللون المنطقي المحدد بواسطة هذا السجل في سياق جهاز التشغيل بواسطة سجل EMR\_SETCOLORSPACE (القسم 2.3.8.7)، الذي يحدد مساحة اللون المنطقية المستخدمة في عمليات الرسوميات اللاحقة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfCreateColorSpaceW`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhCS()](#getIhCS--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [getLcs()](#getLcs--) | يحصل أو يعيّن كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) الذي يمكنه تحديد اسم ملف تعريف اللون بأحرف Unicode UTF16-LE |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | يحصل أو يعيّن كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) الذي يمكنه تحديد اسم ملف تعريف اللون بأحرف Unicode UTF16-LE |
| [getDwFlags()](#getDwFlags--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يوفر معلومات حول البيانات في هذا السجل. |
| [setDwFlags(int value)](#setDwFlags-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يوفر معلومات حول البيانات في هذا السجل. |
| [getCbData()](#getCbData--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم حقل Data بالبايت. |
| [setCbData(int value)](#setCbData-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم حقل Data بالبايت. |
| [getData()](#getData--) | يحصل أو يعيّن مصفوفة اختيارية من البايتات التي تحدد بيانات ملف تعريف اللون. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يعيّن مصفوفة اختيارية من البايتات التي تحدد بيانات ملف تعريف اللون. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfCreateColorSpaceW`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpaceW getLcs()
```


يحصل أو يعيّن كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) الذي يمكنه تحديد اسم ملف تعريف اللون بأحرف Unicode UTF16-LE

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


يحصل أو يعيّن كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) الذي يمكنه تحديد اسم ملف تعريف اللون بأحرف Unicode UTF16-LE

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يوفر معلومات حول البيانات في هذا السجل.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يوفر معلومات حول البيانات في هذا السجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم حقل Data بالبايت.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم حقل Data بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


يحصل أو يعيّن مصفوفة اختيارية من البايتات التي تحدد بيانات ملف تعريف اللون.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


يحصل أو يعيّن مصفوفة اختيارية من البايتات التي تحدد بيانات ملف تعريف اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

