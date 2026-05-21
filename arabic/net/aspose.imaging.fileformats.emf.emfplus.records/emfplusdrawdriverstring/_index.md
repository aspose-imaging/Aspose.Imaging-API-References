---
title: "الفئة EmfPlusDrawDriverString"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawDriverString class. سجل EmfPlusDrawDriverString يحدد إخراج النص مع مواضع الأحرف."
type: docs
weight: 6060
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

سجل EmfPlusDrawDriverString يحدد إخراج النص مع مواضع الأحرف.

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring/)(EmfPlusRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusDrawDriverString`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid/) { get; set; } | يحصل أو يعيّن معرف الفرشاة عدد صحيح غير موقع 32 بت يحدد إما لون المقدمة للنص أو فرشاة رسومية، اعتمادًا على قيمة علم S في Flags. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags/) { get; set; } | يحصل أو يعيّن علم خيارات سلاسل السائق عدد صحيح غير موقع 32 بت يحدد التباعد والاتجاه وجودة العرض للسلسلة. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount/) { get; set; } | يحصل أو يعيّن عدد الرموز عدد صحيح غير موقع 32 بت يحدد عدد الرموز في السلسلة. |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos/) { get; set; } | يحصل أو يعيّن مصفوفة مواضع الرموز مصفوفة من كائنات EmfPlusPointF (القسم 2.2.2.36) التي تحدد موضع الإخراج لكل رمز حرف. يجب أن تحتوي على عدد عناصر يساوي GlyphCount، والتي لها تطابق واحد لواحد مع العناصر في مصفوفة Glyphs. يتم حساب مواضع الرموز من موضع الرمز الأول إذا تم تعيين علم DriverStringOptionsRealizedAdvance في أعلام DriverStringOptions. في هذه الحالة، يحدد GlyphPos موضع الرمز الأول فقط. |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs/) { get; set; } | يحصل أو يعيّن مصفوفة الرموز مصفوفة من قيم 16‑بت التي تحدد سلسلة النص المراد رسمها. إذا تم تعيين علم DriverStringOptionsCmapLookup في حقل DriverStringOptionsFlags، فإن كل قيمة في هذه المصفوفة تحدد حرف Unicode. وإلا، فإن كل قيمة تحدد فهرسًا إلى رمز حرف في كائن EmfPlusFont المحدد بواسطة قيمة ObjectId في حقل Flags. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل لونيًا. هذه البتة تشير إلى نوع البيانات في حقل BrushId. إذا تم تعيينها، فإن BrushId يحدد قيمة اللون في كائن EmfPlusARGB (القسم 2.2.2.1). إذا كانت غير مفعلة، فإن BrushId يحتوي على فهرس جدول كائنات EMF+ لكائن EmfPlusBrush (القسم 2.2.1.1). |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent/) { get; set; } | يحصل أو يعيّن علم وجود المصفوفة عدد صحيح غير موقع 32 بت يحدد ما إذا كانت مصفوفة تحويل موجودة في حقل TransformMatrix. 0 - لا توجد مصفوفة. 1 - مصفوفة التحويل موجودة في حقل TransformMatrix. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس جدول كائنات EMF+ لكائن [EmfPlusFont](EmfPlusFont) (القسم 2.2.1.3) لتصيير النص. يجب أن تكون القيمة بين 0 و 63 شاملًا. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix/) { get; set; } | يحصل أو يعيّن مصفوفة التحويل كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد التحويل لتطبيقه على كل قيمة في مصفوفة النص. يتم تحديد وجود هذه البيانات من حقل MatrixPresent. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


