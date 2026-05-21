---
title: "الفئة EmfCommentPublicRecordType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentPublicRecordType الفئة. أنواع السجل EMR_COMMENT_PUBLIC تحدد امتدادات لمعالجة EMF."
type: docs
weight: 3510
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
## EmfCommentPublicRecordType class

أنواع سجلات EMR_COMMENT_PUBLIC تحدد امتدادات لمعالجة EMF.

```csharp
public abstract class EmfCommentPublicRecordType : EmfCommentRecordType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد هذا السجل التعليقي على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي السلسلة ASCII "CIDG"، تحدد هذا كسجل EMR_COMMENT_PUBLIC. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding إذا كان موجوداً. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام. يجب أن يكون هذا أحد القيم المذكورة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


