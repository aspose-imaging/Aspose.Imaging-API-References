---
title: "EmfCreatePalette"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_CREATEPALETTE يحدد لوحة ألوان منطقية لعمليات الرسومات."
type: docs
weight: 40
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

سجل EMR\_CREATEPALETTE يحدد لوحة ألوان منطقية لعمليات الرسوميات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا للفئة `EmfCreatePalette`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhPal()](#getIhPal--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن لوحة الألوان المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن لوحة الألوان المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [getLogPalette()](#getLogPalette--) | يحصل أو يضبط كائن LogPalette (القسم 2.2.17). |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | يحصل أو يضبط كائن LogPalette (القسم 2.2.17). |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


ينشئ مثيلًا جديدًا للفئة `EmfCreatePalette`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن لوحة الألوان المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن لوحة الألوان المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


يحصل أو يضبط كائن LogPalette (القسم 2.2.17). يجب ضبط حقل Version لهذا الكائن إلى 0x0300. إذا كانت قيمة NumberOfEntries في هذا الكائن صفرًا، يجب أن تفشل معالجة هذا السجل.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


يحصل أو يضبط كائن LogPalette (القسم 2.2.17). يجب ضبط حقل Version لهذا الكائن إلى 0x0300. إذا كانت قيمة NumberOfEntries في هذا الكائن صفرًا، يجب أن تفشل معالجة هذا السجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

