---
title: "الفئة EmfCommentBeginGroup"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentBeginGroup فئة. السجل EMR_COMMENT_BEGINGROUP يحدد بداية مجموعة من سجلات الرسم."
type: docs
weight: 3450
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
## EmfCommentBeginGroup class

سجل EMR_COMMENT_BEGINGROUP يحدد بداية مجموعة من سجلات الرسم.

```csharp
public sealed class EmfCommentBeginGroup : EmfCommentPublicRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCommentBeginGroup](emfcommentbegingroup/)(EmfRecord) | ينشئ مثيلاً جديداً من الفئة `EmfCommentBeginGroup`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد هذا السجل التعليقي على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي السلسلة ASCII "CIDG"، تحدد هذا كسجل EMR_COMMENT_PUBLIC. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding إذا كان موجوداً. |
| [Description](../../aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/description/) { get; set; } | يحصل أو يضبط سلسلة يونيكود اختيارية منتهية بصفر تصف هذه المجموعة من السجلات. |
| [NDescription](../../aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/ndescription/) { get; set; } | يحصل أو يضبط عدد أحرف اليونيكود في سلسلة الوصف الاختيارية التي تلي. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام. يجب أن يكون هذا أحد القيم المذكورة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة. |
| [Rectangle](../../aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/rectangle/) { get; set; } | يحصل أو يضبط كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الإخراج بالإحداثيات المنطقية. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


