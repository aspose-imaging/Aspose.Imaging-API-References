---
title: "تعداد EmfPlusPenDataFlags"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusPenDataFlags enum. تحدد أعلام PenData خصائص أقلام الرسومات بما في ذلك وجود حقول بيانات اختيارية. يمكن دمج هذه الأعلام لتحديد خيارات متعددة."
type: docs
weight: 5120
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/
---
## EmfPlusPenDataFlags enumeration

تحدد أعلام PenData خصائص أقلام الرسومات، بما في ذلك وجود حقول بيانات اختيارية. يمكن دمج هذه الأعلام لتحديد خيارات متعددة.

```csharp
[Flags]
public enum EmfPlusPenDataFlags
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| PenDataTransform | `1` | إذا تم تعيينه، يجب تحديد مصفوفة تحويل 2x3 في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/). |
| PenDataStartCap | `2` | إذا تم تعيينه، يجب تحديد نمط قبعة الخط الابتدائية في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/). |
| PenDataEndCap | `4` | يشير إلى ما إذا كان يجب تحديد نمط قبعة الخط النهائية في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/). |
| PenDataJoin | `8` | يشير إلى ما إذا كان يجب تحديد نوع وصل الخط في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/). |
| PenDataMiterLimit | `10` | يشير إلى ما إذا كان يجب تحديد حد الميتر في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/). |
| PenDataLineStyle | `20` | يشير إلى ما إذا كان يجب تحديد نمط الخط في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/). |
| PenDataDashedLineCap | `40` | يشير إلى ما إذا كان يجب تحديد قبعة الخط المتقطعة في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/). |
| PenDataDashedLineOffset | `80` | يشير إلى ما إذا كان يجب تحديد إزاحة الخط المتقطع في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/). |
| PenDataDashedLine | `100` | يشير إلى ما إذا كان يجب تحديد كائن [`EmfPlusDashedLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataNonCenter | `200` | يشير إلى ما إذا كان يجب تحديد محاذاة القلم في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataCompoundLine | `400` | يشير إلى ما إذا كان طول ومحتوى كائن [`EmfPlusCompoundLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) موجودين في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataCustomStartCap | `800` | يشير إلى ما إذا كان يجب تحديد كائن [`EmfPlusCustomStartCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |
| PenDataCustomEndCap | `1000` | يشير إلى ما إذا كان يجب تحديد كائن [`EmfPlusCustomEndCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) في حقل OptionalData لكائن [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) object. |

## ملاحظات

يتم تحديد أقلام الرسومات بواسطة كائنات [`EmfPlusPen`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen/) objects.

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


