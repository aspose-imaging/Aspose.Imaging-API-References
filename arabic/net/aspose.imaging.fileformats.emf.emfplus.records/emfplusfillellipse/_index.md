---
title: "الفئة EmfPlusFillEllipse"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillEllipse class. سجل EmfPlusFillEllipse يحدد تعبئة داخلية لقطع ناقص."
type: docs
weight: 6190
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
## EmfPlusFillEllipse class

سجل EmfPlusFillEllipse يحدد تعبئة داخل إهليلج.

```csharp
public sealed class EmfPlusFillEllipse : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusFillEllipse](emfplusfillellipse/)(EmfPlusRecord) | يُهيئ مثيلًا جديدًا للفئة `EmfPlusFillEllipse`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/brushid/) { get; set; } | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑bit يحدد الفرشاة، محتواها يحدد بواسطة بت S في حقل Flags. يُستخدم هذا التعريف لتعبئة داخل القطع الناقص. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/iscolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة لونًا. إذا تم تعيينها، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم تُحدد، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/iscompressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه المثيلة مضغوطة. إذا تم التعيين، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا لم يتم التعيين، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/rectdata/) { get; set; } | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF الذي يحدد صندوق الحدود للقطع الناقص |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


