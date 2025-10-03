---
title: TiffImage.AdjustBrightness
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Implement brightness adjustment for the image allowing the modification of overall luminance levels. Incorporate this method into your image processing workflow to enhance visibility and improve the visual quality of images within your application
type: docs
weight: 160
url: /net/aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness/
---
## TiffImage.AdjustBrightness method

Implement *brightness* adjustment for the image, allowing the modification of overall luminance levels. Incorporate this method into your image processing workflow to enhance visibility and improve the visual quality of images within your application.

```csharp
public override void AdjustBrightness(int brightness)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightness | Int32 | Brightness value. |

## Examples

The following example performs brightness correction of a TIFF image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Set the brightness value. The accepted values of brightness are in the range [-255, 255].
    tiffImage.AdjustBrightness(50);
    tiffImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


