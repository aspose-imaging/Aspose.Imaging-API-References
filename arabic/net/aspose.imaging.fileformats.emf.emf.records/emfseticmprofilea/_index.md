---
title: "الفئة EmfSetIcmProfileA"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetIcmProfileA. سجل EMR_SETICMPROFILEA يحدد ملف تعريف ألوان في ملف يحمل اسماً مكوّناً من أحرف ASCII لإخراج الرسومات"
type: docs
weight: 4470
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
## EmfSetIcmProfileA class

سجل EMR_SETICMPROFILEA يحدد ملف تعريف لون في ملف يحمل اسماً مكوّناً من أحرف ASCII، لإخراج الرسومات.

```csharp
public sealed class EmfSetIcmProfileA : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetIcmProfileA](emfseticmprofilea/)(EmfRecord) | ينشئ مثلاً جديداً من الفئة `EmfSetIcmProfileA`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/cbdata/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات ملف تعريف الألوان إذا كانت موجودة في حقل Data. |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/cbname/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات في الاسم ASCII لملف تعريف الألوان المطلوب. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/data/) { get; set; } | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، تحدد الاسم ASCII والبيانات الخام لملف تعريف الألوان المطلوب. |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/dwflags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على أعلام ملف تعريف الألوان. |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/name/) { get; } | يحصل على الاسم |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/rawdata/) { get; } | يحصل على البيانات الخام |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


