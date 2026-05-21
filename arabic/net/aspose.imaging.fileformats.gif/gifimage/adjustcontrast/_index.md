---
title: "GifImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. تضبط تباين الصورة معززةً أو مخفضةً الفرق في السطوع بين البكسلات. تُعدل هذه الطريقة النطاق اللوني العام للصورة، مما يجعل المناطق الداكنة أكثر ظلمة والمناطق الفاتحة أكثر إشراقاً لتحسين الوضوح البصري والتفاصيل."
type: docs
weight: 220
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/adjustcontrast/
---
## GifImage.AdjustContrast method

يضبط تباين الصورة، معززًا أو مخفضًا الفرق في السطوع بين البكسلات. تقوم هذه الطريقة بتعديل النطاق اللوني العام للصورة، مما يجعل المناطق الداكنة أظلم والأجزاء الفاتحة أفتح لتحسين الوضوح البصري والتفاصيل.

```csharp
public override void AdjustContrast(float contrast)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التباين | فردي | قيمة التباين (في النطاق [-100; 100]) |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | Can't change contrast. Frame index: " + frameIndex |

## أمثلة

المثال التالي يُجري تصحيح التباين لصورة GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // حدد قيمة التباين. القيم المقبولة للتباين هي في النطاق [-100f, 100f].
    gifImage.AdjustContrast(50f);
    gifImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


