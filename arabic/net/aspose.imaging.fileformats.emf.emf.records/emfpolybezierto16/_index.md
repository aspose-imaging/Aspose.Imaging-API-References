---
title: "الفئة EmfPolyBezierTo16"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyBezierTo16. السجل EMR_POLYBEZIERTO16 يحدد منحنى أو أكثر بيزيير بناءً على الموضع الحالي"
type: docs
weight: 4090
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---
## EmfPolyBezierTo16 class

سجل EMR_POLYBEZIERTO16 يحدد منحنى بيزيه واحد أو أكثر بناءً على الموضع الحالي.

```csharp
public sealed class EmfPolyBezierTo16 : EmfPolyShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPolyBezierTo16](emfpolybezierto16/#constructor)() | تهيئة نسخة جديدة من الفئة `EmfPolyBezierTo16`. |
| [EmfPolyBezierTo16](emfpolybezierto16/#constructor_1)(EmfRecord) | تهيئة نسخة جديدة من الفئة `EmfPolyBezierTo16`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolyshape/apoints/) { get; set; } | يحصل أو يعيّن مصفوفة من كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد بيانات النقاط، بوحدات منطقية. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL 128‑بت ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل المحيط بوحدات الجهاز. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يتم تعريف منحنيات بيزيير المكعبة باستخدام نقاط النهاية ونقاط التحكم المحددة في الحقل aPoints. يتم رسم المنحنى الأول من النقطة الأولى إلى النقطة الرابعة، باستخدام النقطة الثانية والثالثة كنقاط تحكم. كل منحنى لاحق في التسلسل يحتاج إلى ثلاث نقاط إضافية بالضبط: تُستخدم نقطة النهاية للمنحنى السابق كنقطة بداية، والنقطتان التاليتان في التسلسل كنقاط تحكم، والنقطة الثالثة هي نقطة النهاية. SHOULD أن تُرسم منحنيات بيزيير المكعبة باستخدام القلم الحالي.

### انظر أيضًا

* class [EmfPolyShape](../emfpolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


