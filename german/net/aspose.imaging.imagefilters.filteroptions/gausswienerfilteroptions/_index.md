---
title: GaussWienerFilterOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Gauß-Wiener-Filteroptionen Deblur gauss
type: docs
weight: 9770
url: /de/net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
## GaussWienerFilterOptions class

Gauß-Wiener-Filteroptionen Deblur gauss

```csharp
public class GaussWienerFilterOptions : DeconvolutionFilterOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor)() | Initialisiert eine neue Instanz von[`GaussWienerFilterOptions`](../gausswienerfilteroptions) class. Mit Standardeinstellungen. |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor_1)(int, double) | Initialisiert eine neue Instanz von[`GaussWienerFilterOptions`](../gausswienerfilteroptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness) { get; set; } | Ruft die Helligkeit ab oder legt sie fest. empfohlener Bereich 1 - 1,5 Standardwert = 1,15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`DeconvolutionFilterOptions`](../deconvolutionfilteroptions)ist Graustufen. Graustufenmodus oder RGB-Modus zurückgeben. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz teilweise geladen ist. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/radius) { get; set; } | Ruft den Radius ab oder legt ihn fest. |
| [Smooth](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/smooth) { get; set; } | Ruft die Glättung ab oder legt sie fest. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr) { get; set; } | Ruft das SNR (Signal-Rausch-Verhältnis) ab oder legt es fest empfohlener Bereich 0,002 - 0,009, Standardwert = 0,007 |

### Beispiele

Im folgenden Beispiel werden verschiedene Filtertypen auf ein Rasterbild angewendet.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild anwenden.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Wende einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Wenden Sie einen Gaußschen Unschärfefilter mit einem Radius von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Einen Gauß-Wiener-Filter mit einem Radius von 5 und einem glatten Wert von 4,0 auf das gesamte Bild anwenden.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Wenden Sie einen Bewegungs-Wiener-Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Einen Schärfefilter mit einer Kernelgröße von 5 und einem Sigmawert von 4,0 auf das gesamte Bild anwenden.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### Siehe auch

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions)
* namensraum [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
