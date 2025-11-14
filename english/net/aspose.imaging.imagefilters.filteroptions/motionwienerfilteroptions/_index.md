---
title: Class MotionWienerFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions class. The motion debluring filter options
type: docs
weight: 10040
url: /net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---
## MotionWienerFilterOptions class

The motion debluring filter options.

```csharp
public class MotionWienerFilterOptions : GaussianDeconvolutionFilterOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MotionWienerFilterOptions](motionwienerfilteroptions/)(int, double, double) | Initializes a new instance of the `MotionWienerFilterOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [Angle](../../aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/angle/) { get; set; } | Gets or sets the angle in degrees. |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness/) { get; set; } | Gets or sets the brightness. recommended range 1 - 1.5 default value = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale/) { get; set; } | Gets or sets a value indicating whether this [`DeconvolutionFilterOptions`](../deconvolutionfilteroptions/) is grayscale. Return grayscale mode or RGB mode. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded/) { get; } | Gets a value indicating whether this instance is partial loaded. |
| override [Kernel](../../aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/kernel/) { get; } | Gets the kernel. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/radius/) { get; set; } | Gets the radius of Gausseian ISquareConvolutionKernel. |
| [Sigma](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/sigma/) { get; set; } | Gets the Gaussian kernel sigma (smoothing). Must be a positive non-zero value. |
| [Size](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/size/) { get; set; } | Gets the Gaussian kernel size. Must be a positive non-zero odd value. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr/) { get; set; } | Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007 |

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

* class [GaussianDeconvolutionFilterOptions](../gaussiandeconvolutionfilteroptions/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


