---
title: "HdrProcessor.Process"
second_title: "Aspose.Imaging for .NET API Reference"
description: "HdrProcessor طريقة. يعالج الصور المحددة"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.core.photo.hdr/hdrprocessor/process/
---
## HdrProcessor.Process method

يعالج الصور المحددة.

```csharp
public static int[] Process(RasterImage[] images, HdrImageOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الصور | RasterImage[] | الصور. |
| الخيارات | HdrImageOptions | الخيارات. |

### قيمة الإرجاع

مصفوفة من بكسلات ARGB

## أمثلة

يوضح المثال كيف يتم تنفيذ معالجة HDR.

```csharp
[C#]

var image1 = "DSC_6912.JPG";
var image2 = "DSC_6913.JPG";
var image3 = "DSC_6914.JPG";
var align = true;

var resultFilePath = $"{image1}_result.jpg";
var images = new RasterImage[3];
images[0] = (RasterImage)Image.Load(image1);
images[1] = (RasterImage)Image.Load(image2);
images[2] = (RasterImage)Image.Load(image3);

try
{
    var pixels = HdrProcessor.Process(images, new HdrImageOptions
    {
        SampleCount = 100,
        SmoothFactor = 200,
        AlignImages = align
    });

    using (var image = new PngImage(images[0].Width, images[0].Height))
    {
        image.SaveArgb32Pixels(image.Bounds, pixels);
        image.Save(resultFilePath);
    }
}
finally
{
    foreach (var image in images)
    {
        image.Dispose();
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [HdrImageOptions](../../hdrimageoptions/)
* class [HdrProcessor](../)
* namespace [Aspose.Imaging.FileFormats.Core.Photo.Hdr](../../hdrprocessor/)
* assembly [Aspose.Imaging](../../../)


