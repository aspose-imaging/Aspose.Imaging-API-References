---
title: TiffImage.AdjustContrast
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Enhance the contrast of the Image instance amplifying the differences between its light and dark areas. Integrate this functionality to improve the visual clarity and overall quality of the image within your application
type: docs
weight: 170
url: /net/aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast/
---
## TiffImage.AdjustContrast method

Enhance the contrast of the [`Image`](../../../aspose.imaging/image/) instance, amplifying the differences between its light and dark areas. Integrate this functionality to improve the visual clarity and overall quality of the image within your application.

```csharp
public override void AdjustContrast(float contrast)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contrast | Single | Contrast value (in range [-100; 100]) |

## Examples

The following example performs contrast correction of a TIFF image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
    tiffImage.AdjustContrast(50f);
    tiffImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


