---
title: "EmfSetArcDirection"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EMR_SETARCDIRECTION يحدد اتجاه الرسم الذي سيُستخدم لإخراج القوس والمستطيل."
type: docs
weight: 118
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

سجل EMR\_SETARCDIRECTION يحدد اتجاه الرسم الذي سيُستخدم لإخراج الأقواس والمستطيلات.

يسجل EMR\\_SETARCDIRECTION يؤثر على الاتجاه الذي ترسم به السجلات التالية: - EMR\\_ARC (القسم 2.3.5.2) - EMR\\_ARCTO (القسم 2.3.5.3) - EMR\\_CHORD (القسم 2.3.5.4) - EMR\\_ELLIPSE (القسم 2.3.5.5) - EMR\\_PIE (القسم 2.3.5.15) - EMR\\_RECTANGLE (القسم 2.3.5.34) - EMR\\_ROUNDRECT (القسم 2.3.5.35)
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfSetArcDirection`. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | يُنشئ مثيلاً جديدًا للفئة `EmfSetArcDirection`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد اتجاه القوس. |
| [setArcDirection(int value)](#setArcDirection-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد اتجاه القوس. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfSetArcDirection`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


يُنشئ مثيلاً جديدًا للفئة `EmfSetArcDirection`.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد اتجاه القوس. يجب أن تكون القيمة ضمن تعداد ArcDirection (القسم 2.1.2). الاتجاه الافتراضي هو عكس اتجاه عقارب الساعة.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد اتجاه القوس. يجب أن تكون القيمة ضمن تعداد ArcDirection (القسم 2.1.2). الاتجاه الافتراضي هو عكس اتجاه عقارب الساعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

