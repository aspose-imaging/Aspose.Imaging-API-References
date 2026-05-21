---
title: "الفئة EmfCommentMultiFormats"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentMultiFormats. سجل EMR_COMMENT_MULTIFORMATS يحدد صورة بأكثر من تنسيق رسومي."
type: docs
weight: 3500
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
## EmfCommentMultiFormats class

سجل EMR_COMMENT_MULTIFORMATS يحدد صورة بأكثر من تنسيق رسومي.

```csharp
public sealed class EmfCommentMultiFormats : EmfCommentPublicRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCommentMultiFormats](emfcommentmultiformats/)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfCommentMultiFormats`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AFormats](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/aformats/) { get; set; } | يحصل أو يعيّن مصفوفة بطول CountFormats من تنسيقات الرسومات، المحددة بواسطة كائنات EmrFormat (القسم 2.2.4)، بترتيب الأولوية. |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد هذا السجل التعليقي على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي السلسلة ASCII "CIDG"، تحدد هذا كسجل EMR_COMMENT_PUBLIC. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding إذا كان موجوداً. |
| [FormatData](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/formatdata/) { get; set; } | يحصل أو يعيّن مصفوفة بطول متغيّر من بايتات بيانات الصورة لجميع تنسيقات الرسومات المحتواة في هذا السجل. يتم توفير حجم البيانات لكل صورة بواسطة حقل DataSize في كائن EmrFormat المقابل. وبالتالي، يكون الحجم الكلي لهذا الحقل هو مجموع قيم DataSize في جميع كائنات EmrFormat. يتم تحديد تنسيق الرسومات للبيانات لكل صورة بواسطة حقل Signature في كائن EmrFormat المقابل. |
| [OutputRect](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/outputrect/) { get; set; } | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الناتج، بالإحداثيات المنطقية. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام. يجب أن يكون هذا أحد القيم المذكورة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


