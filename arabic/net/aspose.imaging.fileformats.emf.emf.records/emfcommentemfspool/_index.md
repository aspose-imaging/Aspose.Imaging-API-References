---
title: EmfCommentEmfSpool
second_title: Aspose.Imaging لمرجع NET API
description: يحتوي سجل EMR_COMMENT_EMFSPOOL على سجلات EMFSPOOL مضمنة. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3.
type: docs
weight: 3370
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
## EmfCommentEmfSpool class

يحتوي سجل EMR_COMMENT_EMFSPOOL على سجلات EMFSPOOL مضمنة. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3.

```csharp
public sealed class EmfCommentEmfSpool : EmfCommentRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfCommentEmfSpool](emfcommentemfspool#constructor)() | يقوم بتهيئة مثيل جديد لملف[`EmfCommentEmfSpool`](../emfcommentemfspool) فئة . |
| [EmfCommentEmfSpool](emfcommentemfspool#constructor_1)(EmfRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfCommentEmfSpool`](../emfcommentemfspool) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/commentidentifier) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يعرف سجل التعليق هذا على أنه يحتوي على سجلات EMFSPOOL. تحدد القيمة 0x00000000 هذا على أنه سجل EMR_COMMENT_EMFSPOOL. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد الحجم بالبايت للحقول CommentIdentifier و CommentRecordParm في حقل RecordBuffer الذي يتبعه . يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding ، إذا كان present |
| [EmfSpoolRecordIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecordidentifier) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد نوع سجل EMR_COMMENT_EMFSPOOL . |
| [EmfSpoolRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecords) { get; set; } | الحصول على أو تعيين صفيف متغير الطول من البايت يحتوي على واحد أو أكثر من سجلات تعريف خط EMFSPOOL (القسم [MS-EMFSPOOL] 2.2.3.3) . |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | الحصول على أو تحديد حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | الحصول على النوع أو تحديده. |

### أنظر أيضا

* class [EmfCommentRecordType](../emfcommentrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->