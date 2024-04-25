---
title: GaussWienerFilterOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Gauss Wiener Filter Options Deblur gauss
type: docs
weight: 9770
url: /fr/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
## GaussWienerFilterOptions class

Gauss Wiener Filter Options Deblur gauss

```csharp
public class GaussWienerFilterOptions : DeconvolutionFilterOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor)() | Initialise une nouvelle instance du[`GaussWienerFilterOptions`](../gausswienerfilteroptions) classe. Avec les paramètres par défaut. |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor_1)(int, double) | Initialise une nouvelle instance du[`GaussWienerFilterOptions`](../gausswienerfilteroptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness) { get; set; } | Obtient ou définit la luminosité. plage recommandée 1 - 1,5 valeur par défaut = 1,15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale) { get; set; } | Obtient ou définit une valeur indiquant si cette[`DeconvolutionFilterOptions`](../deconvolutionfilteroptions)est en niveaux de gris. Renvoie le mode niveaux de gris ou le mode RVB. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded) { get; } | Obtient une valeur indiquant si cette instance est partiellement chargée. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/radius) { get; set; } | Obtient ou définit le rayon. |
| [Smooth](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/smooth) { get; set; } | Obtient ou définit le lissage. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr) { get; set; } | Obtient ou définit le SNR (rapport signal sur bruit) plage recommandée 0,002 - 0,009, valeur par défaut = 0,007 |

### Exemples

L'exemple suivant applique différents types de filtres à une image raster.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applique un filtre médian avec une taille de rectangle de 5 à l'image entière.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'image entière.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'image entière.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'image entière.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Appliquez un filtre de mouvement Wiener avec une longueur de 5, une valeur lisse de 4,0 et un angle de 90,0 degrés à l'image entière.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Appliquez un filtre de netteté avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'image entière.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### Voir également

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions)
* espace de noms [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
