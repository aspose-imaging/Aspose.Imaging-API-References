---
title: "الفئة EmfSetColorAdjustment"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetColorAdjustment class. السجل EMR_SETCOLORADJUSTMENT يحدد خصائص تعديل اللون في سياق جهاز التشغيل"
type: docs
weight: 4430
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
## EmfSetColorAdjustment class

سجل EMR_SETCOLORADJUSTMENT يحدد خصائص تعديل اللون في سياق جهاز التشغيل.

```csharp
public sealed class EmfSetColorAdjustment : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetColorAdjustment](emfsetcoloradjustment/)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfSetColorAdjustment`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ColorAdjustment](../../aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/coloradjustment/) { get; set; } | يحصل أو يعيّن كائن ColorAdjustment (القسم 2.2.2) الذي يحدد قيم تعديل اللون. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

تُستخدم قيم تعديل اللون لضبط لون الإدخال للبت ماب المصدر لعمليات الرسومات التي تُجرى بواسطة سجلات EMR_STRETCHBLT و EMR_STRETCHDIBITS عندما يتم تعيين وضع STRETCH_HALFTONE من تعداد StretchMode (القسم 2.1.32). يجب استخدام كائن ColorAdjustment المحدد بهذا السجل في عمليات الرسومات التي تتطلب كائن ColorAdjustment، حتى يتم تحديد كائن ColorAdjustment مختلف بواسطة سجل EMR_SETCOLORADJUSTMENT آخر، أو حتى يتم إزالة الكائن بواسطة سجل EMR_DELETEOBJECT.

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


