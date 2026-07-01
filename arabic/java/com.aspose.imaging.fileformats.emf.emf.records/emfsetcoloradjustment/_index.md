---
title: "EmfSetColorAdjustment"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SETCOLORADJUSTMENT يحدد خصائص تعديل اللون في سياق جهاز التشغيل."
type: docs
weight: 122
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

السجل EMR\_SETCOLORADJUSTMENT يحدد خصائص تعديل اللون في سياق جهاز التشغيل.

تُستخدم قيم تعديل اللون لضبط لون الإدخال للصورة المصدر للعمليات الرسومية التي تُنفّذ بواسطة سجلات EMR\\_STRETCHBLT و EMR\\_STRETCHDIBITS عندما يتم تعيين وضع STRETCH\\_HALFTONE من تعداد StretchMode (القسم 2.1.32). يجب استخدام كائن ColorAdjustment المحدد بهذا السجل في العمليات الرسومية التي تتطلب كائن ColorAdjustment، حتى يتم تحديد كائن ColorAdjustment مختلف بواسطة سجل EMR\\_SETCOLORADJUSTMENT آخر، أو حتى يتم إزالة الكائن بواسطة سجل EMR\\_DELETEOBJECT.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديداً من الفئة `EmfSetColorAdjustment`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | يحصل أو يعيّن كائن ColorAdjustment (القسم 2.2.2) الذي يحدد قيم تعديل اللون. |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | يحصل أو يعيّن كائن ColorAdjustment (القسم 2.2.2) الذي يحدد قيم تعديل اللون. |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


يُنشئ مثيلاً جديداً من الفئة `EmfSetColorAdjustment`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


يحصل أو يعيّن كائن ColorAdjustment (القسم 2.2.2) الذي يحدد قيم تعديل اللون.

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


يحصل أو يعيّن كائن ColorAdjustment (القسم 2.2.2) الذي يحدد قيم تعديل اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

