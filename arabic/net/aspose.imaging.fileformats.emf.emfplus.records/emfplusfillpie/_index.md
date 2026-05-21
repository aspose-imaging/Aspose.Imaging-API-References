---
title: "الفئة EmfPlusFillPie"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillPie. سجل EmfPlusFillPie يحدد تعبئة جزء من داخل إهليلج."
type: docs
weight: 6210
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
## EmfPlusFillPie class

سجل EmfPlusFillPie يحدد تعبئة جزء من داخل إهليلج.

```csharp
public sealed class EmfPlusFillPie : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusFillPie](emfplusfillpie/)(EmfPlusRecord) | يُهيئ مثيلًا جديدًا من الفئة `EmfPlusFillPie`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/brushid/) { get; set; } | يحصل أو يعيّن معرف الفرشاة: عدد صحيح غير موقع 32‑بت يحدد الفرشاة، محتواها يحدد بواسطة بت S في حقل Flags. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطًا. إذا تم التعيين، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا تم الإلغاء، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/iscolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة لونًا. إذا تم تعيينها، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم تُحدد، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/rectdata/) { get; set; } | يحصل أو يعيّن بيانات المستطيل. إما كائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالإهليلج الذي يحتوي على قطعة الفطيرة. هذا المستطيل يحدد موضع الفطيرة وحجمها وشكلها. نوع الكائن في هذا الحقل يُحدد بواسطة قيمة حقل Flags. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [StartAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/startangle/) { get; set; } | يحصل أو يعيّن زاوية البدء. عدد عائم 32 بت غير سالب يحدد الزاوية بين محور x والنقطة البداية لقطعة الفطيرة. أي قيمة مقبولة، لكن يجب تفسيرها modulo 360، بحيث تكون النتيجة في النطاق من 0.0 شامل إلى 360.0 حصري. |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/sweepangle/) { get; set; } | يحصل أو يعيّن زاوية المسح. عدد عائم 32 بت يحدد مدى القوس الذي يحدد قطعة الفطيرة المراد رسمها، كزاوية بالدرجات مقاسة من النقطة البداية المحددة بقيمة StartAngle. أي قيمة مقبولة، لكن يجب تقييدها بين -360.0 إلى 360.0 شامل. القيمة الموجبة تشير إلى أن المسح يُعرف باتجاه عقارب الساعة، والقيمة السالبة تشير إلى أن المسح يُعرف باتجاه عكس عقارب الساعة. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


