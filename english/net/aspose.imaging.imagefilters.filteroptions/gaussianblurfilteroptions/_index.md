---
title: Class GaussianBlurFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions class. The Gaussian blur filter options
type: docs
weight: 10000
url: /net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
## GaussianBlurFilterOptions class

The Gaussian blur filter options.

```csharp
public class GaussianBlurFilterOptions : ConvolutionFilterOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [GaussianBlurFilterOptions](gaussianblurfilteroptions/#constructor)() | Initializes a new instance of the `GaussianBlurFilterOptions` class. |
| [GaussianBlurFilterOptions](gaussianblurfilteroptions/#constructor_1)(int, double) | Initializes a new instance of the `GaussianBlurFilterOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bias](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/bias/) { get; set; } | Gets or sets the bias. |
| [BordersProcessing](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/bordersprocessing/) { get; set; } | Gets or sets a value indicating whether [borders processing]. |
| [Factor](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/factor/) { get; set; } | Gets or sets the factor. |
| [IgnoreAlpha](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/ignorealpha/) { get; set; } | Gets or sets a value indicating whether [ignore alpha]. |
| override [Kernel](../../aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/kernel/) { get; } | Gets the Gaussian kernel. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/radius/) { get; set; } | Gets the radius of Gausseian ISquareConvolutionKernel. |
| virtual [Sigma](../../aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/sigma/) { get; set; } | Gets the Gaussian kernel sigma (smoothing). Must be a positive non-zero value. |
| virtual [Size](../../aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/size/) { get; set; } | Gets the Gaussian kernel size. Must be a positive non-zero odd value. |

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

* class [ConvolutionFilterOptions](../convolutionfilteroptions/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


