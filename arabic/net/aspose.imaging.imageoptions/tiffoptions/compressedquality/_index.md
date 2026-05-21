---
title: "TiffOptions.CompressedQuality"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffOptions. تحصل أو تعين جودة الصورة المضغوطة. تُستخدم مع ضغط Jpeg"
type: docs
weight: 80
url: /ar/net/aspose.imaging.imageoptions/tiffoptions/compressedquality/
---
## TiffOptions.CompressedQuality property

يحصل أو يعيّن جودة الصورة المضغوطة. يُستخدم مع ضغط JPEG.

```csharp
public int CompressedQuality { get; set; }
```

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة TIFF مع ضغط Jpeg وجودة الصورة المضغوطة المحددة.

```csharp
[C#]

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load("c:\\temp\\zeebra.tif"))
{
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    // حدد نموذج اللون RGB.
    tiffOptions.Photometric = TiffPhotometrics.Rgb;
    // عيّن ضغط Jpeg.
    tiffOptions.Compression = TiffCompressions.Jpeg;
    tiffOptions.CompressedQuality = 50;
    // حدد 8 بتات لكل مكوّن لوني.
    tiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };
    
    image.Save("zeebra.tif-50.tiff", tiffOptions);
}
```

### انظر أيضًا

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


