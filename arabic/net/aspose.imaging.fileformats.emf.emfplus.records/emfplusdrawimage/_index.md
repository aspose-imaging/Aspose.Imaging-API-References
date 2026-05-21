---
title: "الفئة EmfPlusDrawImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawImage. يُحدِّد سجل EmfPlusDrawImage رسم صورة مُقاسة."
type: docs
weight: 6080
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
## EmfPlusDrawImage class

سجل EmfPlusDrawImage يحدد رسم صورة مُقاسة.

```csharp
public sealed class EmfPlusDrawImage : EmfPlusDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusDrawImage](emfplusdrawimage/)(EmfPlusRecord) | يُنشئ مثيلًا جديدًا من الفئة `EmfPlusDrawImage`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/compressed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطًا. إذا تم التعيين، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا تم الإلغاء، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/imageattributesid/) { get; set; } | يحصل أو يعيّن معرف سمات الصورة عدد صحيح غير موقع 32‑بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/objectid/) { get; set; } | يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusImage (القسم 2.2.1.4) في جدول كائنات EMF+، والذي يحدد الصورة المراد عرضها. يجب أن تكون القيمة بين الصفر و63 شاملًا. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/rectdata/) { get; set; } | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالصورة. الجزء المحدد من الصورة بحقل SrcRect يُقاس ليتناسب مع هذا المستطيل. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/srcrect/) { get; set; } | يحصل أو يعيّن مستطيل المصدر كائن EmfPlusRectF يحدد جزءًا من الصورة ليُعرض. الجزء المحدد من الصورة بهذا المستطيل يُقاس ليتناسب مع مستطيل الوجهة المحدد بحقل RectData. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/srcunit/) { get; set; } | يحصل أو يعيّن وحدة المصدر عدد صحيح موقّع 32‑بت يحدد وحدات حقل SrcRect. يجب أن تكون القيمة هي العنصر UnitTypePixel من تعداد UnitType (القسم 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

### انظر أيضًا

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


