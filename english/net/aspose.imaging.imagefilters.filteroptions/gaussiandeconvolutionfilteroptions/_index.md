---
title: Class GaussianDeconvolutionFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageFilters.FilterOptions.GaussianDeconvolutionFilterOptions class. The deconvolution filter options using Gaussian bluring
type: docs
weight: 10010
url: /net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
## GaussianDeconvolutionFilterOptions class

The deconvolution filter options using Gaussian bluring.

```csharp
public abstract class GaussianDeconvolutionFilterOptions : DeconvolutionFilterOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [GaussianDeconvolutionFilterOptions](gaussiandeconvolutionfilteroptions/)(int, double) | Initializes a new instance of the `GaussianDeconvolutionFilterOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness/) { get; set; } | Gets or sets the brightness. recommended range 1 - 1.5 default value = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale/) { get; set; } | Gets or sets a value indicating whether this [`DeconvolutionFilterOptions`](../deconvolutionfilteroptions/) is grayscale. Return grayscale mode or RGB mode. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded/) { get; } | Gets a value indicating whether this instance is partial loaded. |
| virtual [Kernel](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/kernel/) { get; } | Gets the kernel. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/radius/) { get; set; } | Gets the radius of Gausseian ISquareConvolutionKernel. |
| [Sigma](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/sigma/) { get; set; } | Gets the Gaussian kernel sigma (smoothing). Must be a positive non-zero value. |
| [Size](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/size/) { get; set; } | Gets the Gaussian kernel size. Must be a positive non-zero odd value. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr/) { get; set; } | Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007 |

### See Also

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


