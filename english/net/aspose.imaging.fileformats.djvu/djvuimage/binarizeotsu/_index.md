---
title: DjvuImage.BinarizeOtsu
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. Binarization using Otsu thresholding is a technique that automatically calculates an optimal threshold value based on the images histogram. It separates the image into foreground and background by minimizing the intraclass variance. Otsus method is widely used for segmenting images into binary form particularly when the distribution of pixel intensities is bimodal or multimodal. This approach is beneficial for tasks such as object detection image segmentation and feature extraction where accurate delineation between foreground and background is crucial
type: docs
weight: 200
url: /net/aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu/
---
## DjvuImage.BinarizeOtsu method

Binarization using Otsu thresholding is a technique that automatically calculates an optimal threshold value based on the image's histogram. It separates the image into foreground and background by minimizing the intra-class variance. Otsu's method is widely used for segmenting images into binary form, particularly when the distribution of pixel intensities is bimodal or multimodal. This approach is beneficial for tasks such as object detection, image segmentation, and feature extraction, where accurate delineation between foreground and background is crucial.

```csharp
public override void BinarizeOtsu()
```

## Examples

The following example binarizes a DJVU image with Otsu thresholding. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Binarize the image with Otsu thresholding.
    djvuImage.BinarizeOtsu();
    djvuImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


