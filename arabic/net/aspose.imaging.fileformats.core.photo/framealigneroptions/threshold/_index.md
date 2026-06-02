---
title: "FrameAlignerOptions.Threshold"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية FrameAlignerOptions. تحصل أو تعين العتبة"
type: docs
weight: 50
url: /ar/net/aspose.imaging.fileformats.core.photo/framealigneroptions/threshold/
---
## FrameAlignerOptions.Threshold property

يحصل أو يضبط العتبة.

```csharp
public float Threshold { get; set; }
```

### Property Value

العتبة.

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

* class [FrameAlignerOptions](../)
* namespace [Aspose.Imaging.FileFormats.Core.Photo](../../framealigneroptions/)
* assembly [Aspose.Imaging](../../../)


