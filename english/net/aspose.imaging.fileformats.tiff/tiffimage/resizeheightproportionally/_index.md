---
title: TiffImage.ResizeHeightProportionally
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Conduct a proportional adjustment of the images height preserving its aspect ratio for consistent visual integrity. Employ this method to dynamically resize images within your application ensuring optimal display across diverse platforms and devices without compromising content quality
type: docs
weight: 340
url: /net/aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally/
---
## TiffImage.ResizeHeightProportionally method

Conduct a proportional adjustment of the image's height, preserving its aspect ratio for consistent visual integrity. Employ this method to dynamically resize images within your application, ensuring optimal display across diverse platforms and devices without compromising content quality.

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | Type of the resize. |

## Examples

This example loads a TIFF image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


