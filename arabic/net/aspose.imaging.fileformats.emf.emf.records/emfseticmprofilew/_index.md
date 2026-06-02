---
title: "الفئة EmfSetIcmProfileW"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetIcmProfileW. سجل EMR_SETICMPROFILEW يحدد ملف تعريف ألوان في ملف يحمل اسمًا مكوّنًا من أحرف يونيكود لإخراج الرسومات."
type: docs
weight: 4480
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
## EmfSetIcmProfileW class

سجل EMR_SETICMPROFILEW يحدد ملف تعريف لون في ملف يحمل اسماً مكوّناً من أحرف Unicode، لإخراج الرسومات.

```csharp
public sealed class EmfSetIcmProfileW : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetIcmProfileW](emfseticmprofilew/)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfSetIcmProfileW`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/cbdata/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات ملف تعريف اللون، إذا كان مرفقًا. |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/cbname/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات في اسم Unicode UTF16-LE لملف تعريف اللون المطلوب. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/data/) { get; set; } | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بالبايت، التي تحدد اسم UTF16-LE والبيانات الخام لملف تعريف اللون المطلوب. |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/dwflags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على أعلام ملف تعريف الألوان. |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/name/) { get; } | يحصل على الاسم |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/rawdata/) { get; } | يحصل على البيانات الخام |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


