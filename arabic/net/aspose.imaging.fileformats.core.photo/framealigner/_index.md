---
title: "الفئة FrameAligner"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Core.Photo.FrameAligner. محاذاة الإطارات"
type: docs
weight: 2330
url: /ar/net/aspose.imaging.fileformats.core.photo/framealigner/
---
## FrameAligner class

محاذاة الإطارات

```csharp
public static class FrameAligner
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Process](../../aspose.imaging.fileformats.core.photo/framealigner/process/)(RasterImage[], FrameAlignerOptions) | يعالج الصور المحددة. |

## أمثلة

يوضح المثال كيفية محاذاة سلسلة من الصور بالنسبة للأولى.

```csharp
[C#]

const int imagesCount = 5;
const bool modify = true;

var images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.Load("DSC_5715.JPG");
images[1] = (RasterImage)Image.Load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.Load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.Load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.Load("manor_plus2ev.jpg");

var results = FrameAligner.Process(images, new FrameAlignerOptions
{
    ModifyImages = modify
});

Console.WriteLine(results[0]);
Console.WriteLine(results[1]);
Console.WriteLine(results[2]);
Console.WriteLine(results[3]);
Console.WriteLine(results[4]);

var i = 0;
foreach (var image in images)
{
    i++;
    var outputFilePath = $"{i}_result.jpg";
    image.Save(outputFilePath);
    image.Dispose();
}
```

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Core.Photo](../../aspose.imaging.fileformats.core.photo/)
* assembly [Aspose.Imaging](../../)


