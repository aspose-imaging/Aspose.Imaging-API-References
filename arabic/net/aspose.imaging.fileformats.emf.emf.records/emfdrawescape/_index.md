---
title: "الفئة EmfDrawEscape"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDrawEscape. سجل EMR_DRAWESCAPE يمرر معلومات عشوائية إلى برنامج تشغيل الطابعة. الهدف هو أن تؤدي هذه المعلومات إلى تنفيذ الرسم."
type: docs
weight: 3650
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---
## EmfDrawEscape class

سجل EMR_DRAWESCAPE يمرر معلومات عشوائية إلى برنامج تشغيل الطابعة. الهدف هو أن تؤدي هذه المعلومات إلى تنفيذ الرسم.

```csharp
public sealed class EmfDrawEscape : EmfEscapeRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfDrawEscape](emfdrawescape/)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfDrawEscape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CjIn](../../aspose.imaging.fileformats.emf.emf.records/emfdrawescape/cjin/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي يجب تمريرها إلى برنامج تشغيل الطابعة. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfdrawescape/data/) { get; set; } | يحصل أو يعيّن البيانات التي يجب تمريرها إلى برنامج تشغيل الطابعة. يجب أن تكون هناك بايتات cjIn متاحة. |
| [IEscape](../../aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/iescape/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عملية الهروب (escape) لبرنامج تشغيل الطابعة التي يجب تنفيذها. يجب أن تكون هذه إحدى القيم في تعداد WMF MetafileEscapes ([MSWMF] القسم 2.1.1.17). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfEscapeRecordType](../emfescaperecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


