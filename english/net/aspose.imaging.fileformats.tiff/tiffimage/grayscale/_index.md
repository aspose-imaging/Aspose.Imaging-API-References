---
title: TiffImage.Grayscale
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Convert the image to its grayscale representation transforming it into a singlechannel image where each pixel represents intensity. Integrate this method into your image processing pipeline to simplify analysis and enhance compatibility with grayscalebased algorithms facilitating various computer vision and image analysis tasks within your application
type: docs
weight: 270
url: /net/aspose.imaging.fileformats.tiff/tiffimage/grayscale/
---
## TiffImage.Grayscale method

Convert the image to its grayscale representation, transforming it into a single-channel image where each pixel represents intensity. Integrate this method into your image processing pipeline to simplify analysis and enhance compatibility with grayscale-based algorithms, facilitating various computer vision and image analysis tasks within your application.

```csharp
public override void Grayscale()
```

## Examples

The following example transforms a colored TIFF image to its grayscale representation. Grayscale images are composed exclusively of shades of gray and carry only intensity information.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    tiffImage.Grayscale();
    tiffImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


