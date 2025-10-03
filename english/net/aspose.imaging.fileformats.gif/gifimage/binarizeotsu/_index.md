---
title: GifImage.BinarizeOtsu
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Binarization of an image with Otsu thresholding is a method used to automatically determine the optimal threshold value for converting a grayscale image into a binary image. The Otsu thresholding algorithm calculates the threshold that minimizes the intraclass variance of the pixel intensities in the two resulting classes foreground and background. This technique is particularly useful when the optimal threshold value is unknown and needs to be determined adaptively based on the images histogram
type: docs
weight: 260
url: /net/aspose.imaging.fileformats.gif/gifimage/binarizeotsu/
---
## GifImage.BinarizeOtsu method

Binarization of an image with Otsu thresholding is a method used to automatically determine the optimal threshold value for converting a grayscale image into a binary image. The Otsu thresholding algorithm calculates the threshold that minimizes the intra-class variance of the pixel intensities in the two resulting classes (foreground and background). This technique is particularly useful when the optimal threshold value is unknown and needs to be determined adaptively based on the image's histogram.

```csharp
public override void BinarizeOtsu()
```

## Examples

The following example binarizes a GIF image with Otsu thresholding. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Binarize the image with Otsu thresholding.
    gifImage.BinarizeOtsu();
    gifImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


