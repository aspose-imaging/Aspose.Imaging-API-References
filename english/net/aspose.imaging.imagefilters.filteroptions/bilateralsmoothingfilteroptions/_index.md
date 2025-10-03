---
title: Class BilateralSmoothingFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions class. The Bilateral Smoothing Filter Options
type: docs
weight: 9930
url: /net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
## BilateralSmoothingFilterOptions class

The Bilateral Smoothing Filter Options.

```csharp
public class BilateralSmoothingFilterOptions : FilterOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [BilateralSmoothingFilterOptions](bilateralsmoothingfilteroptions/#constructor)() | Initializes a new instance of the `BilateralSmoothingFilterOptions` class. |
| [BilateralSmoothingFilterOptions](bilateralsmoothingfilteroptions/#constructor_1)(int) | Initializes a new instance of the `BilateralSmoothingFilterOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [ColorFactor](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/colorfactor/) { get; set; } | Gets or sets the color factor. |
| [ColorPower](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/colorpower/) { get; set; } | Gets or sets the color power. |
| [Size](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/size/) { get; set; } | Gets or sets the size of the kernel. |
| [SpatialFactor](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/spatialfactor/) { get; set; } | Gets or sets the spatial factor. |
| [SpatialPower](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/spatialpower/) { get; set; } | Gets or sets the spatial power. |

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


