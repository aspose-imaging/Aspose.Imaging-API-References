---
title: "الفئة EmfCommentEmfSpool"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentEmfSpool. السجل EMR_COMMENT_EMFSPOOL يحتوي على سجلات EMFSPOOL مدمجة. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3."
type: docs
weight: 3470
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
## EmfCommentEmfSpool class

سجل EMR_COMMENT_EMFSPOOL يحتوي على سجلات EMFSPOOL مدمجة. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3.

```csharp
public sealed class EmfCommentEmfSpool : EmfCommentRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCommentEmfSpool](emfcommentemfspool/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfCommentEmfSpool`. |
| [EmfCommentEmfSpool](emfcommentemfspool/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfCommentEmfSpool`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/commentidentifier/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد أن سجل التعليق هذا يحتوي على سجلات EMFSPOOL. القيمة 0x00000000 تحدد أنه سجل EMR_COMMENT_EMFSPOOL. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding إذا كان موجوداً. |
| [EmfSpoolRecordIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecordidentifier/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد نوع سجل EMR_COMMENT_EMFSPOOL. |
| [EmfSpoolRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecords/) { get; set; } | يحصل أو يعيّن مصفوفة بطول متغير من البايتات تحتوي على سجل أو أكثر لتعريف خطوط EMFSPOOL ([MS-EMFSPOOL] القسم 2.2.3.3). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


