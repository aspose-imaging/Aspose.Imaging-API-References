---
title: "EmfSetArcDirection"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_SETARCDIRECTION يحدد اتجاه الرسم الذي سيُستخدم لإخراج القوس والمستطيل."
type: docs
weight: 118
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

السجل EMR\_SETARCDIRECTION يحدد اتجاه الرسم الذي سيُستخدم لإخراج الأقواس والمستطيلات.

السجل EMR_SETARCDIRECTION يؤثر على الاتجاه الذي تُرسم به السجلات التالية: - EMR_ARC (القسم 2.3.5.2) - EMR_ARCTO (القسم 2.3.5.3) - EMR_CHORD (القسم 2.3.5.4) - EMR_ELLIPSE (القسم 2.3.5.5) - EMR_PIE (القسم 2.3.5.15) - EMR_RECTANGLE (القسم 2.3.5.34) - EMR_ROUNDRECT (القسم 2.3.5.35)
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfSetArcDirection`. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | ينشئ مثيلاً جديداً من الفئة `EmfSetArcDirection`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد اتجاه القوس. |
| [setArcDirection(int value)](#setArcDirection-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد اتجاه القوس. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfSetArcDirection`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


ينشئ مثيلاً جديداً من الفئة `EmfSetArcDirection`.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد اتجاه القوس. يجب أن تكون القيمة ضمن تعداد ArcDirection (القسم 2.1.2). الاتجاه الافتراضي هو عكس عقارب الساعة.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد اتجاه القوس. يجب أن تكون القيمة ضمن تعداد ArcDirection (القسم 2.1.2). الاتجاه الافتراضي هو عكس عقارب الساعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

