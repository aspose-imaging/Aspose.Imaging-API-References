---
title: "GifImage.Grayscale"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. تحويل الصورة إلى تمثيلها بالأبيض والأسود (تدرج الرمادي) يحول الصورة الملونة إلى نسخة بالأبيض والأسود عن طريق إزالة معلومات اللون مع الحفاظ على الإضاءة. تبسط هذه العملية الصورة إلى درجات من الرمادي مما يجعلها مناسبة لتطبيقات مختلفة مثل الطباعة ومعالجة المستندات وتحليل التدرج الرمادي."
type: docs
weight: 320
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/grayscale/
---
## GifImage.Grayscale method

تحويل الصورة إلى تمثيلها الرمادي يحول الصورة الملونة إلى نسخة رمادية عن طريق إزالة معلومات اللون مع الحفاظ على الإضاءة. تبسط هذه العملية الصورة إلى درجات من الرمادي، مما يجعلها مناسبة لتطبيقات مختلفة مثل الطباعة ومعالجة المستندات والتحليل الرمادي.

```csharp
public override void Grayscale()
```

## أمثلة

المثال التالي يحول صورة GIF ملونة إلى تمثيلها بالأبيض والأسود. صور التدرج الرمادي تتكون حصرياً من درجات الرمادي وتحمل معلومات الشدة فقط.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    gifImage.Grayscale();
    gifImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


