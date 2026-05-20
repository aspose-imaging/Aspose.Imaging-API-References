---
title: "EmfCreateColorSpace"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_CREATECOLORSPACE ينشئ كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا يتكون من أحرف ASCII."
type: docs
weight: 36
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

سجل EMR_CREATECOLORSPACE ينشئ كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف ASCII.

يمكن اختيار كائن مساحة اللون المنطقي المحدد بواسطة هذا السجل إلى سياق جهاز التشغيل بواسطة سجل EMR\_SETCOLORSPACE (القسم 2.3.8.7)، الذي يحدد مساحة اللون المنطقية المستخدمة في عمليات الرسومات اللاحقة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfCreateColorSpace`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhCS()](#getIhCS--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [getLcs()](#getLcs--) | يحصل أو يضبط كائن WMF LogColorSpace ([MS-WMF] القسم 2.2.2.11)، الذي يمكنه تحديد اسم ملف تعريف لون بأحرف ASCII. |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | يحصل أو يضبط كائن WMF LogColorSpace ([MS-WMF] القسم 2.2.2.11)، الذي يمكنه تحديد اسم ملف تعريف لون بأحرف ASCII. |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfCreateColorSpace`.

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
public WmfLogColorSpace getLcs()
```


يحصل أو يضبط كائن WMF LogColorSpace ([MS-WMF] القسم 2.2.2.11)، الذي يمكنه تحديد اسم ملف تعريف لون بأحرف ASCII.

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


يحصل أو يضبط كائن WMF LogColorSpace ([MS-WMF] القسم 2.2.2.11)، الذي يمكنه تحديد اسم ملف تعريف لون بأحرف ASCII.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

