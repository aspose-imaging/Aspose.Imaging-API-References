---
title: "EmfCreatePalette"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_CREATEPALETTE يعرّف لوحة ألوان منطقية لعمليات الرسوميات."
type: docs
weight: 40
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

سجل EMR_CREATEPALETTE يحدد لوحة ألوان منطقية لعمليات الرسوميات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfCreatePalette`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhPal()](#getIhPal--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس كائن لوحة الألوان المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس كائن لوحة الألوان المنطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [getLogPalette()](#getLogPalette--) | يحصل أو يعيّن كائن LogPalette (القسم 2.2.17). |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | يحصل أو يعيّن كائن LogPalette (القسم 2.2.17). |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfCreatePalette`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس كائن لوحة الألوان المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس كائن لوحة الألوان المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


يحصل أو يعيّن كائن LogPalette (القسم 2.2.17). يجب تعيين حقل Version لهذا الكائن إلى 0x0300. إذا كانت قيمة NumberOfEntries في هذا الكائن صفرًا، يجب أن يفشل معالجة هذا السجل.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


يحصل أو يعيّن كائن LogPalette (القسم 2.2.17). يجب تعيين حقل Version لهذا الكائن إلى 0x0300. إذا كانت قيمة NumberOfEntries في هذا الكائن صفرًا، يجب أن يفشل معالجة هذا السجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

