---
title: "DjvuImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. قم بتحسين تباين Image لتحسين الوضوح البصري وإبراز التفاصيل باستخدام هذه الطريقة التي تضبط الفرق في السطوع بين المناطق الفاتحة والداكنة. من خلال ضبط مستويات التباين بدقة يمكن للمستخدمين الحصول على صور أكثر حيوية وتأثيرًا، مما يعزز جودة الصورة العامة ويزيد من وضوح التفاصيل. يساعد هذا التعديل على إظهار الفروق الدقيقة في اللون والملمس، مما ينتج عنه صور أكثر ديناميكية وجاذبية بصريًا."
type: docs
weight: 160
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/adjustcontrast/
---
## DjvuImage.AdjustContrast method

قم بتحسين تباين [`Image`](../../../aspose.imaging/image/) لتحسين الوضوح البصري وإبراز التفاصيل باستخدام هذه الطريقة التي تضبط الفرق في السطوع بين المناطق الفاتحة والداكنة. من خلال ضبط مستويات التباين بدقة، يمكن للمستخدمين الحصول على صور أكثر حيوية وتأثيرًا، مما يعزز جودة الصورة العامة ويزيد من وضوح التفاصيل. يساعد هذا التعديل على إظهار الفروق الدقيقة في اللون والملمس، مما ينتج عنه صور أكثر ديناميكية وجاذبية بصريًا.

```csharp
public override void AdjustContrast(float contrast)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التباين | فردي | قيمة التباين (في النطاق [-100; 100]) |

## أمثلة

المثال التالي يقوم بإجراء تصحيح التباين لصورة DJVU.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // حدد قيمة التباين. القيم المقبولة للتباين هي في النطاق [-100f, 100f].
    djvuImage.AdjustContrast(50f);
    djvuImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


