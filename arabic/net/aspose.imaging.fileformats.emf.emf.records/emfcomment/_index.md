---
title: "الفئة EmfComment"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfComment. سجل EMR_COMMENT يحتوي على بيانات خاصة عشوائية. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3."
type: docs
weight: 3440
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
## EmfComment class

سجل EMR_COMMENT يحتوي على بيانات خاصة عشوائية. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.3.

```csharp
public sealed class EmfComment : EmfCommentRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfComment](emfcomment/)(EmfRecord) | ينشئ مثلاً جديداً من الفئة `EmfComment`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/commentidentifier/) { get; set; } | يحصل أو يعيّن معرف التعليق. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding إذا كان موجوداً. |
| [PrivateData](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/privatedata/) { get; set; } | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحدد البيانات الخاصة. يجب ألا تكون الـ DWORD الأول من هذه البيانات أحد القيم المعرّفة مسبقاً لمعرف التعليق المحددة في القسم 2.3.3. البيانات الخاصة غير معروفة لـ EMF؛ وهي ذات معنى فقط للتطبيقات التي تعرف تنسيق البيانات وكيفية استخدامها. سجلات البيانات الخاصة لـ EMR_COMMENT قد يتم تجاهلها. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


