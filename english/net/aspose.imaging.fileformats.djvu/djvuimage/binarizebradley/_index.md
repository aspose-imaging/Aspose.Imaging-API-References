---
title: DjvuImage.BinarizeBradley
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. Binarization using Bradleys adaptive thresholding algorithm with integral image thresholding is a method that calculates a local threshold for each pixel based on a local neighborhood. It adapts to variations in illumination across the image making it suitable for images with uneven lighting conditions. By computing the threshold using integral images it efficiently handles large neighborhoods making it applicable to realtime applications. This technique is commonly used in document processing OCR Optical Character Recognition and image segmentation tasks where accurate binarization is essential for subsequent analysis
type: docs
weight: 180
url: /net/aspose.imaging.fileformats.djvu/djvuimage/binarizebradley/
---
## DjvuImage.BinarizeBradley method

Binarization using Bradley's adaptive thresholding algorithm with integral image thresholding is a method that calculates a local threshold for each pixel based on a local neighborhood. It adapts to variations in illumination across the image, making it suitable for images with uneven lighting conditions. By computing the threshold using integral images, it efficiently handles large neighborhoods, making it applicable to real-time applications. This technique is commonly used in document processing, OCR (Optical Character Recognition), and image segmentation tasks where accurate binarization is essential for subsequent analysis.

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | Double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | Int32 | The size of s x s window of pixels centered around this pixel |

## Examples

The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Binarize the image with a brightness difference of 5. The brightness is a difference between a pixel and the average of an 10 x 10 window of pixels centered around this pixel.
    djvuImage.BinarizeBradley(5, 10);
    djvuImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


