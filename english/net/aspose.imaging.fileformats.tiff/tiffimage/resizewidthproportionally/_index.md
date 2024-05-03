---
title: TiffImage.ResizeWidthProportionally
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Adjust the width of the image while maintaining its aspect ratio ensuring proportional resizing for optimal visual presentation. Utilize this method to dynamically scale images within your application facilitating consistent and aesthetically pleasing rendering across various display contexts
type: docs
weight: 360
url: /net/aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally/
---
## TiffImage.ResizeWidthProportionally method

Adjust the width of the image while maintaining its aspect ratio, ensuring proportional resizing for optimal visual presentation. Utilize this method to dynamically scale images within your application, facilitating consistent and aesthetically pleasing rendering across various display contexts.

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| resizeType | ResizeType | Type of the resize. |

## Examples

This example loads a TIFF image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


