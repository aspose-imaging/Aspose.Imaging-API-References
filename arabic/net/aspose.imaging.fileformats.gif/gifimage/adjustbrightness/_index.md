---
title: "GifImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. تضبط سطوع الصورة وفقاً للمعامل المحدد للسطوع. تُعدل هذه الطريقة سطوع الصورة بالكامل بشكل موحد، إما بزيادة أو خفض الإضاءة العامة لتحقيق التأثير المطلوب."
type: docs
weight: 210
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/adjustbrightness/
---
## GifImage.AdjustBrightness method

يضبط سطوع الصورة وفقًا للمعامل *brightness* المحدد. تقوم هذه الطريقة بتعديل سطوع الصورة بالكامل بشكل موحد، معززةً أو مخفضةً الإضاءة العامة لتحقيق التأثير المطلوب.

```csharp
public override void AdjustBrightness(int brightness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| السطوع | Int32 | قيمة السطوع. |

## أمثلة

المثال التالي يُجري تصحيح السطوع لصورة GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع هي في النطاق [-255, 255].
    gifImage.AdjustBrightness(50);
    gifImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


