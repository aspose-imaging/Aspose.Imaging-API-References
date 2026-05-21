---
title: "الفئة EmfCommentRecordType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentRecordType. أنواع سجلات التعليق تُعرّف صيغًا لتحديد سجلات تضمين بيانات خاصة عشوائية في صيغ ملفات ميتا أخرى وإضافة أوامر جديدة أو ذات غرض خاص."
type: docs
weight: 3520
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
## EmfCommentRecordType class

أنواع سجلات التعليق تعرف صيغًا لتحديد بيانات خاصة عشوائية، ودمج السجلات في صيغ ملفات ميتا أخرى، وإضافة أوامر جديدة أو ذات غرض خاص.

```csharp
public abstract class EmfCommentRecordType : EmfRecord
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/commentidentifier/) { get; set; } | يحصل أو يعيّن معرف التعليق. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الحجم، بالبايت، لحقلي CommentIdentifier وCommentRecordParm في حقل RecordBuffer الذي يلي ذلك. يجب ألا يتضمن حجم نفسه أو حجم حقل AlignmentPadding إذا كان موجوداً. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfRecord](../emfrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


