---
title: "الفئة EmfModifyWorldTransform"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfModifyWorldTransform الفئة. سجل EMR_MODIFYWORLDTRANSFORM يغيّر تحويل الفضاء العالمي الحالي إلى فضاء الصفحة في سياق جهاز التشغيل."
type: docs
weight: 3940
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
## EmfModifyWorldTransform class

سجل EMR_MODIFYWORLDTRANSFORM يغيّر تحويل الفضاء العالمي الحالي إلى فضاء الصفحة في سياق جهاز التشغيل.

```csharp
public sealed class EmfModifyWorldTransform : EmfTransformRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfModifyWorldTransform](emfmodifyworldtransform/#constructor)() | يُنشئ مثيلاً جديدًا من الفئة `EmfModifyWorldTransform`. |
| [EmfModifyWorldTransform](emfmodifyworldtransform/#constructor_1)(EmfRecord) | يُنشئ مثيلاً جديدًا من الفئة `EmfModifyWorldTransform`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ModifyWorldTransformMode](../../aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/modifyworldtransformmode/) { get; set; } | يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد كيفية استخدام التحويل المحدد في Xform. يجب أن تكون هذه القيمة ضمن تعداد ModifyWorldTransformMode (القسم 2.1.24). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [Xform](../../aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype/xform/) { get; set; } | يحصل أو يعيّن كائن XForm (القسم 2.2.28)، الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة. |

## ملاحظات

لمزيد من المعلومات حول التحويلات والمساحات الإحداثية، راجع [MSDN-WRLDPGSPC]. انظر القسم 2.3.12 لتحديد أنواع سجلات التحويل الأخرى.

### انظر أيضًا

* class [EmfTransformRecordType](../emftransformrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


