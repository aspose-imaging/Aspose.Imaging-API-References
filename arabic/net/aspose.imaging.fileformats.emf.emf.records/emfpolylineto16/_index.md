---
title: "الفئة EmfPolylineTo16"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolylineTo16 الفئة. السجل EMR_POLYLINETO16 يحدد خطًا أو أكثر مستقيمًا بناءً على الموضع الحالي. يتم رسم خط من الموضع الحالي إلى أول نقطة يحددها الحقل aPoints باستخدام القلم الحالي. لكل خط إضافي يتم الرسم من نقطة النهاية للخط السابق إلى النقطة التالية التي يحددها aPoints."
type: docs
weight: 4250
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---
## EmfPolylineTo16 class

سجل EMR_POLYLINETO16 يحدد خطًا مستقيمًا واحدًا أو أكثر بناءً على الموضع الحالي. يتم رسم خط من الموضع الحالي إلى أول نقطة محددة في حقل aPoints باستخدام القلم الحالي. لكل خط إضافي، يتم الرسم من نقطة نهاية الخط السابق إلى النقطة التالية المحددة في aPoints.

```csharp
public sealed class EmfPolylineTo16 : EmfPolyShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPolylineTo16](emfpolylineto16/#constructor)() | يُنشئ مثلاً جديدًا من الفئة `EmfPolylineTo16`. |
| [EmfPolylineTo16](emfpolylineto16/#constructor_1)(EmfRecord) | يُنشئ مثلاً جديدًا من الفئة `EmfPolylineTo16`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolyshape/apoints/) { get; set; } | يحصل أو يعيّن مصفوفة من كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد بيانات النقاط، بوحدات منطقية. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL 128‑بت ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل المحيط بوحدات الجهاز. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfPolyShape](../emfpolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


