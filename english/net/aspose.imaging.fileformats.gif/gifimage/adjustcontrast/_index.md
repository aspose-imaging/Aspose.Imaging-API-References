---
title: GifImage.AdjustContrast
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Adjusts the contrast of the image enhancing or reducing the difference in brightness between pixels. This method modifies the images overall tonal range making darker areas darker and brighter areas brighter to improve visual clarity and detail
type: docs
weight: 220
url: /net/aspose.imaging.fileformats.gif/gifimage/adjustcontrast/
---
## GifImage.AdjustContrast method

Adjusts the contrast of the image, enhancing or reducing the difference in brightness between pixels. This method modifies the image's overall tonal range, making darker areas darker and brighter areas brighter to improve visual clarity and detail.

```csharp
public override void AdjustContrast(float contrast)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contrast | Single | Contrast value (in range [-100; 100]) |

### Exceptions

| exception | condition |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | Can't change contrast. Frame index: " + frameIndex |

## Examples

The following example performs contrast correction of a GIF image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
    gifImage.AdjustContrast(50f);
    gifImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


