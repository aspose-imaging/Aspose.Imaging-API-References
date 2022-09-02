---
title: GaussWienerFilterOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Opzioni filtro Wiener Gauss Sfocatura gauss
type: docs
weight: 9770
url: /it/net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
## GaussWienerFilterOptions class

Opzioni filtro Wiener Gauss Sfocatura gauss

```csharp
public class GaussWienerFilterOptions : DeconvolutionFilterOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor)() | Inizializza una nuova istanza di[`GaussWienerFilterOptions`](../gausswienerfilteroptions) classe. Con impostazioni predefinite. |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor_1)(int, double) | Inizializza una nuova istanza di[`GaussWienerFilterOptions`](../gausswienerfilteroptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness) { get; set; } | Ottiene o imposta la luminosità. intervallo consigliato 1 - 1,5 valore predefinito = 1,15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale) { get; set; } | Ottiene o imposta un valore che indica se questo[`DeconvolutionFilterOptions`](../deconvolutionfilteroptions)è in scala di grigi. Ritorna alla modalità scala di grigi o alla modalità RGB. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded) { get; } | Ottiene un valore che indica se questa istanza è stata caricata parzialmente. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/radius) { get; set; } | Ottiene o imposta il raggio. |
| [Smooth](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/smooth) { get; set; } | Ottiene o imposta lo smooth. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr) { get; set; } | Ottiene o imposta l'SNR(rapporto segnale-rumore) intervallo consigliato 0,002 - 0,009, valore predefinito = 0,007 |

### Esempi

L'esempio seguente applica vari tipi di filtri a un'immagine raster.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applica un filtro mediano con una dimensione del rettangolo di 5 all'intera immagine.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applica un filtro levigante bilaterale con una dimensione del kernel di 5 all'intera immagine.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applica un filtro sfocatura gaussiana con un raggio di 5 e un valore sigma di 4,0 all'intera immagine.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applica un filtro Gauss-Wiener con un raggio di 5 e un valore uniforme di 4,0 all'intera immagine.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applica un filtro motion wiener con una lunghezza di 5, un valore uniforme di 4,0 e un angolo di 90,0 gradi all'intera immagine.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Applica un filtro di nitidezza con una dimensione del kernel di 5 e un valore sigma di 4.0 all'intera immagine.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### Guarda anche

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions)
* spazio dei nomi [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
