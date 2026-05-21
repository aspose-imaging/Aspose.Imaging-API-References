---
title: "فئة EmfPlusDrawString"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawString فئة. يحدد سجل EmfPlusDrawString إخراج النص مع تنسيق السلسلة."
type: docs
weight: 6140
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
## EmfPlusDrawString class

سجل EmfPlusDrawString يحدد إخراج النص مع تنسيق السلسلة.

```csharp
public sealed class EmfPlusDrawString : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawString](emfplusdrawstring/)(EmfPlusRecord) | يُهيئ نسخة جديدة من الفئة `EmfPlusDrawString`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/brushid/) { get; set; } | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواها يحدد بواسطة بت S في حقل Flags. يُستخدم هذا التعريف لتلوين لون النص الأمامي؛ أي الأحرف نفسها فقط. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [FormatId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/formatid/) { get; set; } | يحصل أو يعيّن معرف التنسيق عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن EmfPlusStringFormat اختياري (القسم 2.2.1.9) في جدول كائنات EMF+. يحدد هذا الكائن معلومات تخطيط النص وتعديلات العرض التي تُطبق على السلسلة. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/iscolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة لونًا. إذا تم تعيينها، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم تُحدد، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| [LayoutRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/layoutrect/) { get; set; } | يحصل أو يعيّن مستطيل التخطيط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المنطقة المحيطة للوجهة التي ستستقبل السلسلة. |
| [Length](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/length/) { get; set; } | يحصل أو يعيّن الطول عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف في السلسلة. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusFont (القسم 2.2.1.3) في جدول كائنات EMF+ لتصيير النص. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [StringData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/stringdata/) { get; set; } | يحصل أو يعيّن بيانات السلسلة مصفوفة من أحرف Unicode 16‑بت التي تحدد السلسلة التي سيتم رسمها. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


