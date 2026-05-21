---
title: "EmfColorCorrectPalette"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_COLORCORRECTPALETTE يحدد كيفية تصحيح مدخلات كائن لوحة ألوان منطقية باستخدام قيم WCS 1.0."
type: docs
weight: 23
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfColorCorrectPalette extends EmfObjectManipulationRecordType
```

سجل EMR\_COLORCORRECTPALETTE يحدد كيفية تصحيح مدخلات كائن لوحة ألوان منطقية باستخدام قيم WCS 1.0.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfColorCorrectPalette(EmfRecord source)](#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfColorCorrectPalette`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhPalette()](#getIhPalette--) | يحصل على عدد صحيح غير موقّع 32‑بت يحدد فهرس كائن لوحة ألوان منطقية (القسم 2.2.17) في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhPalette(int value)](#setIhPalette-int-) | يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد فهرس كائن لوحة ألوان منطقية (القسم 2.2.17) في جدول كائنات EMF (القسم 3.1.1.1). |
| [getNFirstEntry()](#getNFirstEntry--) | يحصل على عدد صحيح غير موقّع 32‑بت يحدد فهرس أول مدخل لتصحيحه. |
| [setNFirstEntry(int value)](#setNFirstEntry-int-) | يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد فهرس أول مدخل لتصحيحه. |
| [getNPalEntries()](#getNPalEntries--) | يحصل على عدد صحيح غير موقّع 32‑بت يحدد عدد مدخلات لوحة الألوان التي يجب تصحيحها. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد مدخلات لوحة الألوان التي يجب تصحيحها. |
### EmfColorCorrectPalette(EmfRecord source) {#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorCorrectPalette(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfColorCorrectPalette`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIhPalette() {#getIhPalette--}
```
public int getIhPalette()
```


يحصل على عدد صحيح غير موقّع 32‑بت يحدد فهرس كائن لوحة ألوان منطقية (القسم 2.2.17) في جدول كائنات EMF (القسم 3.1.1.1).

**Returns:**
int
### setIhPalette(int value) {#setIhPalette-int-}
```
public void setIhPalette(int value)
```


يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد فهرس كائن لوحة ألوان منطقية (القسم 2.2.17) في جدول كائنات EMF (القسم 3.1.1.1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getNFirstEntry() {#getNFirstEntry--}
```
public int getNFirstEntry()
```


يحصل على عدد صحيح غير موقّع 32‑بت يحدد فهرس أول مدخل لتصحيحه.

**Returns:**
int
### setNFirstEntry(int value) {#setNFirstEntry-int-}
```
public void setNFirstEntry(int value)
```


يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد فهرس أول مدخل لتصحيحه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


يحصل على عدد صحيح غير موقّع 32‑بت يحدد عدد مدخلات لوحة الألوان التي يجب تصحيحها.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد مدخلات لوحة الألوان التي يجب تصحيحها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

