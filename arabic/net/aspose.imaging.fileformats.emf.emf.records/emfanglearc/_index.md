---
title: "الفئة EmfAngleArc"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfAngleArc. سجل EMR_ANGLEARC يحدد قطعة خط من قوس. يتم رسم قطعة الخط من الموضع الحالي إلى بداية القوس. يُرسم القوس على محيط دائرة ذات نصف قطر ومركز محددين. يتم تعريف طول القوس بواسطة زوايا البداية والامتداد المحددة."
type: docs
weight: 3300
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
## EmfAngleArc class

يسجل EMR_ANGLEARC مقطع خط لقوس. يُرسم مقطع الخط من الموضع الحالي إلى بداية القوس. يُرسم القوس على محيط دائرة ذات نصف قطر ومركز محددين. يُحدد طول القوس بزاوية البدء وزاوية المسح المحددتين.

```csharp
public sealed class EmfAngleArc : EmfDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfAngleArc](emfanglearc/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfAngleArc`. |
| [EmfAngleArc](emfanglearc/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfAngleArc`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Center](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/center/) { get; set; } | يحصل أو يعيّن كائن WMF PointL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد الإحداثيات المنطقية لمركز الدائرة. |
| [Radius](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/radius/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع بحجم 32 بت يحدد نصف قطر الدائرة، بوحدات منطقية. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [StartAngle](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/startangle/) { get; set; } | يحصل أو يعيّن عددًا عائمًا بحجم 32 بت يحدد زاوية بدء القوس، بالدرجات. |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/sweepangle/) { get; set; } | يحصل أو يعيّن عددًا عائمًا بحجم 32 بت يحدد زاوية امتداد القوس، بالدرجات. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


