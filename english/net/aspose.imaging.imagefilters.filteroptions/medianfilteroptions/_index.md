---
title: Class MedianFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions class. Median filter
type: docs
weight: 10030
url: /net/aspose.imaging.imagefilters.filteroptions/medianfilteroptions/
---
## MedianFilterOptions class

Median filter

```csharp
public class MedianFilterOptions : FilterOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MedianFilterOptions](medianfilteroptions/)(int) | Initializes a new instance of the `MedianFilterOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.imaging.imagefilters.filteroptions/medianfilteroptions/size/) { get; set; } | Gets or sets the size. |

## Examples

The following example applies various types of filters to a raster image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Apply a median filter with a rectangle size of 5 to the entire image.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Apply a bilateral smoothing filter with a kernel size of 5 to the entire image.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Apply a Gaussian blur filter with a radius of 5 and a sigma value of 4.0 to the entire image.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Apply a Gauss-Wiener filter with a radius of 5 and a smooth value of 4.0 to the entire image.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Apply a motion wiener filter with a length of 5, a smooth value of 4.0 and an angle of 90.0 degrees to the entire image.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Apply a sharpen filter with a kernel size of 5 and a sigma value of 4.0 to the entire image.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### See Also

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


