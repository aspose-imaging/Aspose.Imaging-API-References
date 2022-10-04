---
title: EmfCreateBrushIndirect
second_title: Aspose.Imaging لمرجع NET API
description: يحدد سجل EMR_CREATEBRUSHINDIRECT فرشاة منطقية لعمليات الرسومات.
type: docs
weight: 3460
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
## EmfCreateBrushIndirect class

يحدد سجل EMR_CREATEBRUSHINDIRECT فرشاة منطقية لعمليات الرسومات.

يمكن تحديد كائن الفرشاة المنطقية المحدد بواسطة هذا السجل في سياق جهاز التشغيل عن طريق سجل EMR_SELECTOBJECT (القسم 2.3.8.5) ، والذي يحدد الفرشاة المنطقية لاستخدامها في عمليات الرسومات اللاحقة.

```csharp
public sealed class EmfCreateBrushIndirect : EmfObjectCreationRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfCreateBrushIndirect](emfcreatebrushindirect#constructor)() | يقوم بتهيئة مثيل جديد لملف[`EmfCreateBrushIndirect`](../emfcreatebrushindirect) فئة . |
| [EmfCreateBrushIndirect](emfcreatebrushindirect#constructor_1)(EmfRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfCreateBrushIndirect`](../emfcreatebrushindirect) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/ihbrush) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد فهرس كائن الفرشاة المنطقي في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله. |
| [LogBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/logbrush) { get; set; } | الحصول على أو تعيين كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون ونمط للفرشاة المنطقية. يجب أن يكون حقل BrushStyle في هذا الكائن BS_SOLID أو BS_HATCHED أو BS_NULL. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | الحصول على أو تحديد حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | الحصول على النوع أو تحديده. |

### أنظر أيضا

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->