---
title: "الفئة EmfPlusFillPath"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillPath الفئة. سجل ملء المسار FLAGS عدد صحيح غير موقع 16 بت يوفر معلومات حول كيفية تنفيذ العملية وعن بنية السجل. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X  ObjectId  S بت واحد هذا البت يشير إلى نوع البيانات في حقل BrushId. إذا تم الضبط، BrushId يحدد لونًا ككائن EmfPlusARGB القسم 2.2.2.1. إذا تم الإلغاء، BrushId يحتوي على فهرس كائن EmfPlusBrush القسم 2.2.1.1 في جدول كائنات EMF. X بت واحد محجوز ويجب تجاهله. ObjectId بايت واحد فهرس كائن EmfPlusPath القسم 2.2.1.6 لتعبئته في جدول كائنات EMF. يجب أن تكون القيمة بين الصفر و 63 شاملًا."
type: docs
weight: 6200
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
## EmfPlusFillPath class

سجل تعبئة المسار FLAGS: عدد صحيح غير موقع 16-بت يوفر معلومات حول كيفية تنفيذ العملية، وعن بنية السجل. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X &#x7C; ObjectId &#x7C; S (بت واحد): هذه البت تشير إلى نوع البيانات في حقل BrushId. إذا تم تعيينها، فإن BrushId يحدد لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا كانت غير مفعلة، فإن BrushId يحتوي على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. X (بت واحد): محجوز ويجب تجاهله. ObjectId (بايت واحد): فهرس كائن EmfPlusPath (القسم 2.2.1.6) للتعبئة، في جدول كائنات EMF+. يجب أن تكون القيمة بين 0 و 63 شاملًا.

```csharp
public sealed class EmfPlusFillPath : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusFillPath](emfplusfillpath/)(EmfPlusRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusFillPath`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/brushid/) { get; set; } | يحصل أو يعيّن معرف الفرشاة Brush ID عدد صحيح غير موقع 32-بت يحدد الفرشاة، محتواها يحدد بواسطة البت S في حقل Flags. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/iscolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه المثيلة لونًا. إذا تم الضبط، BrushId يحدد لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا تم الإلغاء، BrushId يحتوي على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPath (القسم 2.2.1.6) لتعبئته في جدول كائنات EMF+. يجب أن تكون القيمة بين الصفر و 63 شاملًا. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


