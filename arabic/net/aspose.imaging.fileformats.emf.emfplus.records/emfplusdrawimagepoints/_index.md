---
title: "الفئة EmfPlusDrawImagePoints"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawImagePoints class. سجل EmfPlusDrawImagePoints يحدد رسم صورة مُقاسة داخل متوازي أضلاع."
type: docs
weight: 6090
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

سجل EmfPlusDrawImagePoints يحدد رسم صورة مُقاسة داخل متوازي أضلاع.

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints/)(EmfPlusRecord) | يُهيئ مثيلًا جديدًا للفئة `EmfPlusDrawImagePoints`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [applying an effect]. هذه البتة تشير إلى أن عرض الصورة يتضمن تطبيق تأثير. إذا تم تعيينها، يجب أن يكون كائن من الفئة Effect قد تم تحديده في سجل EmfPlusSerializableObject سابقًا (القسم 2.3.5.2). |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات PointData مضغوطة. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم تعيينها، فإن PointData يحدد مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑bit. إذا لم يتم تعيينها، فإن PointData يحدد مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑bit. ملاحظة: إذا تم تعيين علم P (أدناه)، فإن هذا العلم غير معرف ويجب تجاهله. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحتوي على فهرس كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusImage (القسم 2.2.1.4) في جدول كائنات EMF+، والذي يحدد الصورة المراد عرضها. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata/) { get; set; } | يحصل أو يعيّن مصفوفة من نقاط Count التي تحدد ثلاث نقاط من متوازي أضلاع. تمثل النقاط الثلاث الزاوية العلوية اليسرى، العلوية اليمنى، والسفلية اليسرى لمتوازي الأضلاع. يتم استنتاج النقطة الرابعة من الثلاث نقاط الأولى. الجزء من الصورة المحدد بحقل SrcRect SHOULD يتم تطبيق تحويلات التكبير والقص إذا لزم الأمر لتناسب داخل متوازي الأضلاع. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawImagePoints` نسبيًا. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم تعيينها، فإن PointData يحدد مواقع مطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذا العلم، فإن علم C (أعلاه) غير معرف ويجب تجاهله. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect/) { get; set; } | يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد جزءًا من الصورة ليتم عرضه. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑bit يحدد وحدات حقل SrcRect. يجب أن يكون قيمة UnitPixel من تعداد UnitType (القسم 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

## ملاحظات

يمكن لكائن EmfPlusImage أن يحدد إما صورة نقطية (bitmap) أو ملف تعريف (metafile). يمكن تعديل ألوان الصورة أثناء العرض. يمكن تصحيحها، تعتيمها، تفتيحها، وإزالتها.

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


