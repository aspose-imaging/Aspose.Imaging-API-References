---
title: "الفئة EmfCommentEmfPlus"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentEmfPlus. سجل EMR_COMMENT_EMFPLUS يحتوي على سجلات EMF مضمّنة. ملاحظة: الحقول التي لم تُوصف في هذا القسم محددة في القسم 2.3.3."
type: docs
weight: 3460
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
## EmfCommentEmfPlus class

سجل EMR_COMMENT_EMFPLUS يحتوي على سجلات EMF+ مدمجة. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3.

```csharp
public sealed class EmfCommentEmfPlus : EmfCommentRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCommentEmfPlus](emfcommentemfplus/)(EmfRecord) | يُهيّئ مثيلًا جديدًا من الفئة `EmfCommentEmfPlus`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/commentidentifier/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMF+. القيمة 0x2B464D45، التي هي السلسلة ASCII "+FME"، تحدد ذلك كسجل EMR_COMMENT_EMFPLUS. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding إذا كان موجوداً. |
| [EmfPlusRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/emfplusrecords/) { get; set; } | يحصل أو يعيّن مصفوفة من البايتات تحتوي على سجل واحد أو أكثر من سجلات EMF+ ([MS-EMFPLUS] القسم 2.3.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


