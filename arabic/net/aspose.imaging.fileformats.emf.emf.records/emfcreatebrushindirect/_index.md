---
title: "الفئة EmfCreateBrushIndirect"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect. سجل EMR_CREATEBRUSHINDIRECT يحدد فرشاة منطقية لعمليات الرسومات."
type: docs
weight: 3560
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
## EmfCreateBrushIndirect class

سجل EMR_CREATEBRUSHINDIRECT يعرف فرشاة منطقية لعمليات الرسوم.

يمكن اختيار كائن الفرشاة المنطقية المحدد بهذا السجل إلى سياق جهاز التشغيل بواسطة سجل EMR_SELECTOBJECT (القسم 2.3.8.5)، الذي يحدد الفرشاة المنطقية المستخدمة في عمليات الرسومات اللاحقة.

```csharp
public sealed class EmfCreateBrushIndirect : EmfObjectCreationRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCreateBrushIndirect](emfcreatebrushindirect/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfCreateBrushIndirect`. |
| [EmfCreateBrushIndirect](emfcreatebrushindirect/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfCreateBrushIndirect`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/ihbrush/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن الفرشاة المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديلّه. |
| [LogBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/logbrush/) { get; set; } | يحصل أو يعيّن كائن LogBrushEx (القسم 2.2.12) يحدد نمط ولون ونمط الفرشاة المنطقية. يجب أن يكون حقل BrushStyle في هذا الكائن إما BS_SOLID أو BS_HATCHED أو BS_NULL. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


