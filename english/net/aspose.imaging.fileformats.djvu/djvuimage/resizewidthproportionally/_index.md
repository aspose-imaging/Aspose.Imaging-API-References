---
title: DjvuImage.ResizeWidthProportionally
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. The ResizeWidthProportionally method offers a convenient solution to adjust the width of your image while maintaining its aspect ratio. By proportionally resizing the width you can ensure that your images remain visually appealing and consistent across different devices and screen sizes enhancing their versatility and usability in various contexts
type: docs
weight: 280
url: /net/aspose.imaging.fileformats.djvu/djvuimage/resizewidthproportionally/
---
## DjvuImage.ResizeWidthProportionally method

The `ResizeWidthProportionally` method offers a convenient solution to adjust the width of your image while maintaining its aspect ratio. By proportionally resizing the width, you can ensure that your images remain visually appealing and consistent across different devices and screen sizes, enhancing their versatility and usability in various contexts.

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| resizeType | ResizeType | Type of the resize. |

## Examples

This example loads a DJVU image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Scale up by 2 times using Bilinear resampling.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Scale down by 2 times using Bilinear resampling.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


