---
title: RasterCachedImage.BinarizeBradley
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Binarization of an image using Bradleys adaptive thresholding algorithm using the integral image thresholding
type: docs
weight: 70
url: /net/aspose.imaging/rastercachedimage/binarizebradley/
---
## BinarizeBradley(double, int) {#binarizebradley_1}

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | Double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | Int32 | The size of s x s window of pixels centered around this pixel |

## Examples

The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Binarize the image with a brightness difference of 5.
    // The brightness is a difference between a pixel and the average of an 10 x 10 window of pixels centered around this pixel.
    rasterImage.BinarizeBradley(5, 10);
    rasterImage.Save(dir + "sample.BinarizeBradley5_10x10.png");
}
```

### See Also

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)

---

## BinarizeBradley(double) {#binarizebradley}

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

```csharp
public override void BinarizeBradley(double brightnessDifference)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | Double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |

## Examples

The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Binarize the image with a brightness difference of 5. 
    // The brightness is a difference between a pixel and the average of an s x s window of pixels centered around this pixel.
    // The size of window will be calibrated automatically.
    rasterImage.BinarizeBradley(5);
    rasterImage.Save(dir + "sample.BinarizeBradley5.png");
}
```

### See Also

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


