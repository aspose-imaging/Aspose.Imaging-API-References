---
title: GaussWienerFilterOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Opciones de filtro Gauss Wiener Desenfoque gauss
type: docs
weight: 9770
url: /es/net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
## GaussWienerFilterOptions class

Opciones de filtro Gauss Wiener Desenfoque gauss

```csharp
public class GaussWienerFilterOptions : DeconvolutionFilterOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor)() | Inicializa una nueva instancia del[`GaussWienerFilterOptions`](../gausswienerfilteroptions) class. Con configuración predeterminada. |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor_1)(int, double) | Inicializa una nueva instancia del[`GaussWienerFilterOptions`](../gausswienerfilteroptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness) { get; set; } | Obtiene o establece el brillo. rango recomendado 1 - 1.5 valor predeterminado = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale) { get; set; } | Obtiene o establece un valor que indica si este[`DeconvolutionFilterOptions`](../deconvolutionfilteroptions)es escala de grises. Devuelve el modo de escala de grises o el modo RGB. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded) { get; } | Obtiene un valor que indica si esta instancia está parcialmente cargada. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/radius) { get; set; } | Obtiene o establece el radio. |
| [Smooth](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/smooth) { get; set; } | Obtiene o establece el suavizado. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr) { get; set; } | Obtiene o establece la SNR (relación señal-ruido) rango recomendado 0,002 - 0,009, valor predeterminado = 0,007 |

### Ejemplos

El siguiente ejemplo aplica varios tipos de filtros a una imagen ráster.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Aplicar un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Aplicar un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Aplicar un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4,0 a toda la imagen.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Aplicar un filtro de Gauss-Wiener con un radio de 5 y un valor suave de 4,0 a toda la imagen.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Aplicar un filtro Wiener de movimiento con una longitud de 5, un valor suave de 4,0 y un ángulo de 90,0 grados a toda la imagen.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Aplicar un filtro de nitidez con un tamaño de núcleo de 5 y un valor sigma de 4,0 a toda la imagen.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### Ver también

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions)
* espacio de nombres [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
