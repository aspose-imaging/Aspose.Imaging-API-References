---
title: "الفئة EmfPlusHatchBrushData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusHatchBrushData فئة. كائن EmfPlusHatchBrushData يحدد نمط الترصيع لفرشاة رسومية"
type: docs
weight: 5600
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
## EmfPlusHatchBrushData class

كائن EmfPlusHatchBrushData يحدد نمط التظليل لفرشاة رسومية.

```csharp
public sealed class EmfPlusHatchBrushData : EmfPlusBaseBrushData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusHatchBrushData](emfplushatchbrushdata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/backargb32color/) { get; set; } | يحصل أو يعيّن كائن EmfPlusArgb 32-بت يحدد اللون المستخدم لطلاء خلفية نمط الترصيع. |
| [ForeArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/foreargb32color/) { get; set; } | يحصل أو يعيّن كائن EmfPlusArgb 32-بت يحدد اللون المستخدم لرسم خطوط نمط الترصيع. |
| [HatchStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/hatchstyle/) { get; set; } | يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد نمط الترصيع للفرشاة. يجب أن يكون معرفًا في تعداد [`EmfPlusHatchStyle`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfplushatchstyle/). |

## ملاحظات

يتم تحديد فرش الرسومات بواسطة كائنات [`EmfPlusBrush`](../emfplusbrush/) (القسم 2.2.1.1). فرش الترصيع يطبع خلفية ويرسم نمطًا من الخطوط والنقاط والشرطات والمربعات وخطوط الترصيع المتقاطع فوق هذه الخلفية. يحدد فرش الترصيع لونين: أحدهما للخلفية والآخر للنمط فوق الخلفية. يُطلق على لون الخلفية اسم لون الخلفية، ويُطلق على لون النمط اسم لون المقدمة.

### انظر أيضًا

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


