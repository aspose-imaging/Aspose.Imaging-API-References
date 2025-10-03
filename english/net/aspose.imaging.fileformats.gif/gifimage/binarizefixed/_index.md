---
title: GifImage.BinarizeFixed
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Binarization of an image with a predefined threshold converts a grayscale or color image into a binary image where each pixel is classified as either black or white based on whether its intensity value exceeds a specified threshold
type: docs
weight: 250
url: /net/aspose.imaging.fileformats.gif/gifimage/binarizefixed/
---
## GifImage.BinarizeFixed method

Binarization of an image with a predefined threshold converts a grayscale or color image into a binary image, where each pixel is classified as either black or white based on whether its intensity value exceeds a specified threshold.

```csharp
public override void BinarizeFixed(byte threshold)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | Byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

## Examples

The following example binarizes a GIF image with the predefined threshold. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage djvuImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Binarize the image with a threshold value of 127.
    // If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
    djvuImage.BinarizeFixed(127);
    djvuImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


