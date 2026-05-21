---
title: "HdrImageOptions.AlignImages"
second_title: "Aspose.Imaging for .NET API Reference"
description: "HdrImageOptions خاصية. يحصل أو يعيّن قيمة تشير إلى ما إذا كان align images"
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions/alignimages/
---
## HdrImageOptions.AlignImages property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align images].

```csharp
public bool AlignImages { get; set; }
```

### Property Value

`true` إذا كان [align images]؛ وإلا `false`.

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

* class [HdrImageOptions](../)
* namespace [Aspose.Imaging.FileFormats.Core.Photo.Hdr](../../hdrimageoptions/)
* assembly [Aspose.Imaging](../../../)


