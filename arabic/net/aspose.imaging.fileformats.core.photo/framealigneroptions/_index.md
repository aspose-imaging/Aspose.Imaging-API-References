---
title: "الفئة FrameAlignerOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Core.Photo.FrameAlignerOptions. خيارات محاذاة الإطارات"
type: docs
weight: 2340
url: /ar/net/aspose.imaging.fileformats.core.photo/framealigneroptions/
---
## FrameAlignerOptions class

خيارات محاذاة الإطار

```csharp
public class FrameAlignerOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FrameAlignerOptions](framealigneroptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [MaxOffset](../../aspose.imaging.fileformats.core.photo/framealigneroptions/maxoffset/) { get; set; } | يحصل أو يضبط الإزاحة القصوى. |
| [ModifyImages](../../aspose.imaging.fileformats.core.photo/framealigneroptions/modifyimages/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [modify image]. |
| [StandardImageIndex](../../aspose.imaging.fileformats.core.photo/framealigneroptions/standardimageindex/) { get; set; } | يحصل أو يضبط فهرس الصورة القياسية. |
| [Threshold](../../aspose.imaging.fileformats.core.photo/framealigneroptions/threshold/) { get; set; } | يحصل أو يضبط العتبة. |

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


