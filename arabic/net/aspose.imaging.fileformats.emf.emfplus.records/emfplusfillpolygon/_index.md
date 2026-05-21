---
title: "الفئة EmfPlusFillPolygon"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillPolygon. سجل EmfPlusFillPolygon يحدد تعبئة داخل المضلع."
type: docs
weight: 6220
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
## EmfPlusFillPolygon class

السجل EmfPlusFillPolygon يحدد تعبئة داخل مضلع.

```csharp
public sealed class EmfPlusFillPolygon : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusFillPolygon](emfplusfillpolygon/)(EmfPlusRecord) | ينشئ مثيلاً جديداً من الفئة `EmfPlusFillPolygon`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/brushid/) { get; set; } | يحصل أو يعيّن معرف الفرشاة: عدد صحيح غير موقع 32‑بت يحدد الفرشاة، محتواها يحدد بواسطة بت S في حقل Flags. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة لونًا. إذا تم تعيينها، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم تُحدد، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscompressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مضغوطًا. إذا تم ضبطه، فإن PointData يحدد المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا لم يتم ضبطه، فإن PointData يحدد المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. |
| [IsRelative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/isrelative/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه المثيلة نسبية. إذا تم الضبط، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا تم الإلغاء، يحدد PointData مواقع مطلقة وفقًا لعلامة C flag. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/pointdata/) { get; set; } | يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقاط التي تحدد رؤوس المضلع. النقطتان الأوليتان في المصفوفة تحددان الجانب الأول من المضلع. كل نقطة إضافية تحدد جانبًا جديدًا، تشمل رؤوسه النقطة والنقطة السابقة. إذا لم تتطابق النقطة الأخيرة مع الأولى، فإنهما يحددان الجانب الأخير من المضلع. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


