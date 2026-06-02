---
title: "الفئة EmfPlusDrawPath"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawPath. يُحدِّد سجل EmfPlusDrawPath رسم مسار رسومي."
type: docs
weight: 6110
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
## EmfPlusDrawPath class

سجل EmfPlusDrawPath يحدد رسم مسار رسومي.

```csharp
public sealed class EmfPlusDrawPath : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawPath](emfplusdrawpath/)(EmfPlusRecord) | يُنشئ مثيلًا جديدًا من الفئة `EmfPlusDrawPath`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPath (القسم 2.2.1.6) للرسم في جدول كائنات EMF+. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| [PenId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/penid/) { get; set; } | يحصل أو يعيّن معرف القلم عدد صحيح غير موقع 32‑بت يحدد فهرسًا في جدول كائنات EMF+ لكائن EmfPlusPen (القسم 2.2.1.7) يُستخدم لرسم EmfPlusPath. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


