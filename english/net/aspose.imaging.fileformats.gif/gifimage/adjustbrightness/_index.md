---
title: GifImage.AdjustBrightness
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Adjusts the brightness of the image according to the specified brightness parameter. This method modifies the brightness of the entire image uniformly enhancing or reducing the overall luminance to achieve the desired effect
type: docs
weight: 210
url: /net/aspose.imaging.fileformats.gif/gifimage/adjustbrightness/
---
## GifImage.AdjustBrightness method

Adjusts the brightness of the image according to the specified *brightness* parameter. This method modifies the brightness of the entire image uniformly, enhancing or reducing the overall luminance to achieve the desired effect.

```csharp
public override void AdjustBrightness(int brightness)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightness | Int32 | Brightness value. |

## Examples

The following example performs brightness correction of a GIF image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Set the brightness value. The accepted values of brightness are in the range [-255, 255].
    gifImage.AdjustBrightness(50);
    gifImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


