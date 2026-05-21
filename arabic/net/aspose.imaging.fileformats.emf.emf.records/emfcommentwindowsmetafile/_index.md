---
title: "Class EmfCommentWindowsMetaFile"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentWindowsMetaFile class. سجل EMR_COMMENT_WINDOWS_METAFILE يحدد صورة في ملف WMF مدمج."
type: docs
weight: 3540
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
## EmfCommentWindowsMetaFile class

سجل EMR_COMMENT_WINDOWS_METAFILE يحدد صورة في ملف ميتا WMF مدمج.

```csharp
public sealed class EmfCommentWindowsMetaFile : EmfCommentPublicRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCommentWindowsMetaFile](emfcommentwindowsmetafile/)(EmfRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfCommentWindowsMetaFile`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Checksum](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/checksum/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32-بت يحدد قيمة التحقق لهذا السجل. |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد هذا السجل التعليقي على أنه يحدد بيانات عامة. القيمة 0x43494447، التي هي السلسلة ASCII "CIDG"، تحدد هذا كسجل EMR_COMMENT_PUBLIC. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding إذا كان موجوداً. |
| [Flags](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/flags/) { get; set; } | يحصل أو يعيّن قيمة 32-بت يجب أن تكون 0x00000000 ويجب تجاهلها. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد نوع سجل التعليق العام. يجب أن يكون هذا أحد القيم المذكورة في الجدول السابق، والتي تم تحديدها في تعداد EmrComment (القسم 2.1.10)، ما لم يتم تنفيذ أنواع إضافية من سجلات التعليق العام على خادم الطباعة. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [Version](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/version/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقّع 16-بت يحدد إصدار ملف WMF metafile من حيث الدعم للصور النقطية المستقلة عن الجهاز (DIBs)، من تعداد WMF MetafileVersion ([MS-WMF] القسم 2.1.1.19). |
| [WinMetafile](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafile/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على ملف WMF metafile. |
| [WinMetafileSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafilesize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32-بت يحدد الحجم، بالبايت، لملف WMF metafile في حقل WinMetafile. |

### انظر أيضًا

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


