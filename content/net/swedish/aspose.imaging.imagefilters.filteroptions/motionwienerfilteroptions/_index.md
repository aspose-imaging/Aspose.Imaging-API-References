---
title: MotionWienerFilterOptions
second_title: Aspose.Imaging för .NET API-referens
description: Deconvolution filter options deblur motion
type: docs
weight: 9800
url: /sv/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---
## MotionWienerFilterOptions class

Deconvolution filter options deblur motion

```csharp
public class MotionWienerFilterOptions : DeconvolutionFilterOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MotionWienerFilterOptions](motionwienerfilteroptions)(int, double, double) | Initierar en ny instans av[`MotionWienerFilterOptions`](../motionwienerfilteroptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/angle) { get; set; } | Hämtar eller ställer in vinkeln i gradus. |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness) { get; set; } | Hämtar eller ställer in ljusstyrkan. rekommenderat område 1 - 1,5 standardvärde = 1,15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`DeconvolutionFilterOptions`](../deconvolutionfilteroptions)är gråskala. Återgå gråskaleläge eller RGB-läge. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded) { get; } | Får ett värde som indikerar om denna instans är delvis laddad. |
| [Length](../../aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/length) { get; set; } | Hämtar eller ställer in längden. |
| [Smooth](../../aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/smooth) { get; set; } | Får eller ställer in den jämna. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr) { get; set; } | Hämtar eller ställer in SNR(signal-to-noise ratio) rekommenderat område 0,002 - 0,009, standardvärde = 0,007 |

### Exempel

Följande exempel tillämpar olika typer av filter på en rasterbild.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Använd ett medianfilter med en rektangelstorlek på 5 på hela bilden.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applicera ett Gaussiskt oskärpafilter med en radie på 5 och ett sigmavärde på 4,0 på hela bilden.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applicera ett Gauss-Wiener-filter med en radie på 5 och ett jämnt värde på 4,0 på hela bilden.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applicera ett motion wiener-filter med en längd på 5, ett jämnt värde på 4,0 och en vinkel på 90,0 grader på hela bilden.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Använd ett skärpa filter med en kärnstorlek på 5 och ett sigmavärde på 4,0 på hela bilden.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### Se även

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions)
* namnutrymme [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
