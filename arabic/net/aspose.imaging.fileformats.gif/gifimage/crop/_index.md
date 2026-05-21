---
title: "GifImage.Crop"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. قص الصورة باستخدام منطقة مستطيلة محددة. تقوم هذه العملية بإزالة الجزء الخارجي من الصورة وتترك فقط المنطقة المحددة التي يحددها المستطيل"
type: docs
weight: 280
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/crop/
---
## GifImage.Crop method

قم بقص الصورة باستخدام منطقة مستطيلة محددة. تزيل هذه العملية الجزء الخارجي من الصورة، تاركةً فقط المنطقة المختارة المحددة بالمستطيل.

```csharp
public override void Crop(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |

## أمثلة

المثال التالي يقتص صورة GIF. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية في الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(gifImage.Width / 4, gifImage.Height / 4, gifImage.Width / 2, gifImage.Height / 2);
    gifImage.Crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    gifImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


