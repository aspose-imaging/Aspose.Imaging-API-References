---
title: DjvuImage.ResizeHeightProportionally
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. The ResizeHeightProportionally method allows you to adjust the height of your image while preserving its aspect ratio. This ensures that your image maintains its proportions preventing distortion and preserving its visual integrity. Whether youre optimizing images for web pages mobile apps or print media this method ensures that your images look their best across different platforms and devices
type: docs
weight: 270
url: /net/aspose.imaging.fileformats.djvu/djvuimage/resizeheightproportionally/
---
## DjvuImage.ResizeHeightProportionally method

The `ResizeHeightProportionally` method allows you to adjust the height of your image while preserving its aspect ratio. This ensures that your image maintains its proportions, preventing distortion and preserving its visual integrity. Whether you're optimizing images for web pages, mobile apps, or print media, this method ensures that your images look their best across different platforms and devices.

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | Type of the resize. |

## Examples

This example loads a DJVU image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


