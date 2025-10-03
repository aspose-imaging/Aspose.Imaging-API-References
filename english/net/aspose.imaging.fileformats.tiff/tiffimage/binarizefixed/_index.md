---
title: TiffImage.BinarizeFixed
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Apply binarization to the image using a predefined threshold converting it into a binary image with distinct foreground and background regions. Incorporate this method into your image processing workflow to facilitate segmentation and feature extraction tasks enhancing the accuracy and efficiency of image analysis within your application
type: docs
weight: 210
url: /net/aspose.imaging.fileformats.tiff/tiffimage/binarizefixed/
---
## TiffImage.BinarizeFixed method

Apply binarization to the image using a predefined threshold, converting it into a binary image with distinct foreground and background regions. Incorporate this method into your image processing workflow to facilitate segmentation and feature extraction tasks, enhancing the accuracy and efficiency of image analysis within your application.

```csharp
public override void BinarizeFixed(byte threshold)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | Byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

## Examples

The following example binarizes a TIFF image with the predefined threshold. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Binarize the image with a threshold value of 127.
    // If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
    tiffImage.BinarizeFixed(127);
    tiffImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


