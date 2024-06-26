---
title: DjvuImage.AdjustContrast
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. Enhance Image contrast to improve visual clarity and highlight details with this method which adjusts the difference in brightness between light and dark areas. By finetuning contrast levels users can achieve more vivid and impactful images enhancing overall image quality and maximizing detail visibility. This adjustment helps to bring out subtle nuances in color and texture resulting in more dynamic and visually appealing images
type: docs
weight: 160
url: /net/aspose.imaging.fileformats.djvu/djvuimage/adjustcontrast/
---
## DjvuImage.AdjustContrast method

Enhance [`Image`](../../../aspose.imaging/image/) contrast to improve visual clarity and highlight details with this method, which adjusts the difference in brightness between light and dark areas. By fine-tuning contrast levels, users can achieve more vivid and impactful images, enhancing overall image quality and maximizing detail visibility. This adjustment helps to bring out subtle nuances in color and texture, resulting in more dynamic and visually appealing images.

```csharp
public override void AdjustContrast(float contrast)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contrast | Single | Contrast value (in range [-100; 100]) |

## Examples

The following example performs contrast correction of a DJVU image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
    djvuImage.AdjustContrast(50f);
    djvuImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


