---
title: BilateralSmoothingFilterOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die bilateralen Glättungsfilteroptionen.
type: docs
weight: 9730
url: /de/net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
## BilateralSmoothingFilterOptions class

Die bilateralen Glättungsfilteroptionen.

```csharp
public class BilateralSmoothingFilterOptions : FilterOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [BilateralSmoothingFilterOptions](bilateralsmoothingfilteroptions#constructor)() | Initialisiert eine neue Instanz von[`BilateralSmoothingFilterOptions`](../bilateralsmoothingfilteroptions) Klasse. |
| [BilateralSmoothingFilterOptions](bilateralsmoothingfilteroptions#constructor_1)(int) | Initialisiert eine neue Instanz von[`BilateralSmoothingFilterOptions`](../bilateralsmoothingfilteroptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorFactor](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/colorfactor) { get; set; } | Liest oder setzt den Farbfaktor. |
| [ColorPower](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/colorpower) { get; set; } | Ruft die Farbstärke ab oder legt sie fest. |
| [Size](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/size) { get; set; } | Ruft die Größe des Kernels ab oder legt sie fest. |
| [SpatialFactor](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/spatialfactor) { get; set; } | Ruft den räumlichen Faktor ab oder legt ihn fest. |
| [SpatialPower](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/spatialpower) { get; set; } | Ruft die räumliche Stärke ab oder legt sie fest. |

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

* class [FilterOptionsBase](../filteroptionsbase)
* namensraum [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
