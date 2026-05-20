---
title: "EmfExtCreateFontIndirectW"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_EXTCREATEFONTINDIRECTW يعرّف خطًا منطقيًا لعمليات الرسومات."
type: docs
weight: 51
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

السجل EMR\_EXTCREATEFONTINDIRECTW يعرّف خطًا منطقيًا لعمليات الرسومات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfExtCreateFontIndirectW`. |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | يُنشئ مثيلًا جديدًا من الفئة `EmfExtCreateFontIndirectW`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن الخط المنطقي في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhFonts(int value)](#setIhFonts-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن الخط المنطقي في جدول كائنات EMF (القسم 3.1.1.1). |
| [getElw()](#getElw--) | يحصل أو يضبط كائن LogFontExDv (القسم 2.2.15)، الذي يحدد الخط المنطقي. |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | يحصل أو يضبط كائن LogFontExDv (القسم 2.2.15)، الذي يحدد الخط المنطقي. |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfExtCreateFontIndirectW`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfExtCreateFontIndirectW`.

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن الخط المنطقي في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن الخط المنطقي في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


يحصل أو يضبط كائن LogFontExDv (القسم 2.2.15)، الذي يحدد الخط المنطقي. قد يكون كائن LogFont 2.2.13 موجودًا بدلاً من ذلك.[90] العملية لتحديد نوع الكائن في هذا الحقل موصوفة أدناه.

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


يحصل أو يضبط كائن LogFontExDv (القسم 2.2.15)، الذي يحدد الخط المنطقي. قد يكون كائن LogFont 2.2.13 موجودًا بدلاً من ذلك.[90] العملية لتحديد نوع الكائن في هذا الحقل موصوفة أدناه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

