---
title: GifImage.BinarizeBradley
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Binarization of an image using Bradleys adaptive thresholding algorithm with integral image thresholding is a method for converting a grayscale image into a binary image. This algorithm calculates a local threshold for each pixel based on the average intensity of the surrounding pixels within a specified window. By adaptively adjusting the threshold based on local pixel intensities Bradleys method is effective at handling variations in lighting and contrast across the image
type: docs
weight: 240
url: /net/aspose.imaging.fileformats.gif/gifimage/binarizebradley/
---
## GifImage.BinarizeBradley method

Binarization of an image using Bradley's adaptive thresholding algorithm with integral image thresholding is a method for converting a grayscale image into a binary image. This algorithm calculates a local threshold for each pixel based on the average intensity of the surrounding pixels within a specified window. By adaptively adjusting the threshold based on local pixel intensities, Bradley's method is effective at handling variations in lighting and contrast across the image.

```csharp
public override void BinarizeBradley(double brightnessDifference)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | Double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |

### See Also

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


