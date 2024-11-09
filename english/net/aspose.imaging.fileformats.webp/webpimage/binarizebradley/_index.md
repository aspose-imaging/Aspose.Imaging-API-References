---
title: WebPImage.BinarizeBradley
second_title: Aspose.Imaging for .NET API Reference
description: WebPImage method. Apply binarization to the image using Bradleys adaptive thresholding algorithm with integral image thresholding. This method dynamically computes local thresholds based on the images neighborhood enhancing adaptability to varying lighting conditions and ensuring robust segmentation for subsequent processing tasks within your application
type: docs
weight: 120
url: /net/aspose.imaging.fileformats.webp/webpimage/binarizebradley/
---
## WebPImage.BinarizeBradley method

Apply binarization to the image using Bradley's adaptive thresholding algorithm with integral image thresholding. This method dynamically computes local thresholds based on the image's neighborhood, enhancing adaptability to varying lighting conditions and ensuring robust segmentation for subsequent processing tasks within your application.

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | Double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | Int32 | The size of s x s window of pixels centered around this pixel |

### See Also

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


