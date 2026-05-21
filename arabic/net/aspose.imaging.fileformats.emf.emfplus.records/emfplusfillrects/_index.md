---
title: "الفئة EmfPlusFillRects"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillRects الفئة. السجل EmfPlusFillRects يحدد تعبئة داخل سلسلة من المستطيلات."
type: docs
weight: 6230
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
## EmfPlusFillRects class

السجل EmfPlusFillRects يحدد تعبئة داخل مجموعة من المستطيلات.

```csharp
public sealed class EmfPlusFillRects : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusFillRects](emfplusfillrects/)(EmfPlusRecord) | يقوم بإنشاء نسخة جديدة من الفئة `EmfPlusFillRects`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/brushid/) { get; set; } | يحصل أو يعيّن معرف الفرشاة: عدد صحيح غير موقع 32‑بت يحدد الفرشاة، محتواها يحدد بواسطة بت S في حقل Flags. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillRects` مضغوطًا. إذا كان مضبوطًا، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا كان غير مضبوط، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/iscolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه المثيلة لونًا. إذا تم الضبط، BrushId يحدد لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا تم الإلغاء، BrushId يحتوي على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/rectdata/) { get; set; } | يحصل أو يعيّن بيانات المستطيل مصفوفة من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تحدد بيانات المستطيل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


