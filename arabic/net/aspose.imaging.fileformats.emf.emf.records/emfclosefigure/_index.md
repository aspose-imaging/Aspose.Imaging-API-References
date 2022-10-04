---
title: EmfCloseFigure
second_title: Aspose.Imaging لمرجع NET API
description: هذا السجل يغلق رقمًا مفتوحًا في مسار. يجب أن تغلق معالجة سجل EMR_CLOSEFIGURE الشكل عن طريق رسم line من الموضع الحالي إلى النقطة الأولى من الشكل  ثم يجب توصيل الخطوط باستخدام نمط ربط السطر. إذا تم إغلاق الرقم عن طريق معالجة سجل EMR_LINETO بدلاً من سجل EMR_CLOSEFIGURE  فإن قبعات النهاية هي تُستخدم لإنشاء الزاوية بدلاً من الصلة. تم تحديد EMR_LINETO في section 2.3.5.13. يجب استخدام سجل EMR_CLOSEFIGURE فقط إذا كان هناك افتح path bracket في سياق جهاز التشغيل.
type: docs
weight: 3310
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
## EmfCloseFigure class

هذا السجل يغلق رقمًا مفتوحًا في مسار. يجب أن تغلق معالجة سجل EMR_CLOSEFIGURE الشكل عن طريق رسم line من الموضع الحالي إلى النقطة الأولى من الشكل ، ثم يجب توصيل الخطوط باستخدام نمط ربط السطر. إذا تم إغلاق الرقم عن طريق معالجة سجل EMR_LINETO بدلاً من سجل EMR_CLOSEFIGURE ، فإن قبعات النهاية هي تُستخدم لإنشاء الزاوية بدلاً من الصلة. تم تحديد EMR_LINETO في section 2.3.5.13. يجب استخدام سجل EMR_CLOSEFIGURE فقط إذا كان هناك افتح path bracket في سياق جهاز التشغيل.

```csharp
public sealed class EmfCloseFigure : EmfPathBracketRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfCloseFigure](emfclosefigure)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | الحصول على أو تحديد حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | الحصول على النوع أو تحديده. |

### ملاحظات

ملاحظة: يمكن فتح الشكل حتى إذا كانت النقطة الحالية ونقطة البداية للرقم هي نفسها . بعد معالجة سجل EMR_CLOSEFIGURE ، إضافة خط أو منحنى إلى المسار يجب أن تبدأ شكلًا جديدًا.

### أنظر أيضا

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->