---
title: DjvuImage.AdjustBrightness
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. Adjust the brightness of an image using a specified parameter providing control over luminance levels for optimal visual clarity. This method enhances or diminishes the overall brightness of the image allowing for fine adjustments to achieve desired lighting effects. By modulating brightness users can optimize image visibility and enhance detail reproduction for improved viewing experience
type: docs
weight: 150
url: /net/aspose.imaging.fileformats.djvu/djvuimage/adjustbrightness/
---
## DjvuImage.AdjustBrightness method

Adjust the *brightness* of an image using a specified parameter, providing control over luminance levels for optimal visual clarity. This method enhances or diminishes the overall brightness of the image, allowing for fine adjustments to achieve desired lighting effects. By modulating brightness, users can optimize image visibility and enhance detail reproduction for improved viewing experience.

```csharp
public override void AdjustBrightness(int brightness)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightness | Int32 | Brightness value. |

## Examples

The following example performs brightness correction of a DJVU image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Set the brightness value. The accepted values of brightness are in the range [-255, 255].
    djvuImage.AdjustBrightness(50);
    djvuImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


