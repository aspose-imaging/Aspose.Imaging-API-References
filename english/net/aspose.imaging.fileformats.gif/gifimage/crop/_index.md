---
title: GifImage.Crop
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Crop the image using a specified rectangle area. This operation removes the outer portion of the image leaving only the selected region defined by the rectangle
type: docs
weight: 280
url: /net/aspose.imaging.fileformats.gif/gifimage/crop/
---
## GifImage.Crop method

Crop the image using a specified rectangle area. This operation removes the outer portion of the image, leaving only the selected region defined by the rectangle.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle. |

## Examples

The following example crops a GIF image. The cropping area is be specified via Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Crop the image. The cropping area is the rectangular central area of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(gifImage.Width / 4, gifImage.Height / 4, gifImage.Width / 2, gifImage.Height / 2);
    gifImage.Crop(area);

    // Save the cropped image to PNG
    gifImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


