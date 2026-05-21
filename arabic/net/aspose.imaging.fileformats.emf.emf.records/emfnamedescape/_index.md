---
title: "الفئة EmfNamedEscape"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfNamedEscape الفئة. سجل MR_NAMEDESCAPE يمرّر معلومات عشوائية إلى برنامج تشغيل طابعة محدد."
type: docs
weight: 3960
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
## EmfNamedEscape class

يسلم سجل MR_NAMEDESCAPE معلومات عشوائية إلى برنامج تشغيل طابعة محدد.

```csharp
public sealed class EmfNamedEscape : EmfEscapeRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfNamedEscape](emfnamedescape/)(EmfRecord) | يُنشئ مثلاً جديدًا من الفئة `EmfNamedEscape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CjDriver](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/cjdriver/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات في حقل DriverName. يجب أن تكون هذه القيمة عددًا زوجيًا. |
| [CjIn](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/cjin/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي يتم تمريرها إلى برنامج تشغيل الطابعة. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/data/) { get; set; } | يحصل أو يعيّن البيانات التي يتم تمريرها إلى برنامج تشغيل الطابعة. يجب أن تكون هناك cjIn بايت متاحة. |
| [DriverName](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/drivername/) { get; set; } | يحصل أو يعيّن سلسلة من أحرف Unicode 16‑بت تحدد اسم برنامج تشغيل الطابعة الذي سيتلقى البيانات. يجب أن يكون طول هذه القيمة cjDriver بايت، ويجب أن تنتهي بحرف null. |
| [IEscape](../../aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/iescape/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عملية الهروب (escape) لبرنامج تشغيل الطابعة التي يجب تنفيذها. يجب أن تكون هذه إحدى القيم في تعداد WMF MetafileEscapes ([MSWMF] القسم 2.1.1.17). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfEscapeRecordType](../emfescaperecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


