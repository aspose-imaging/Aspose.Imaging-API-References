---
title: SharpenFilterOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Las opciones de filtro Nitidez
type: docs
weight: 9810
url: /es/net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
## SharpenFilterOptions class

Las opciones de filtro Nitidez

```csharp
public class SharpenFilterOptions : ConvolutionFilterOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SharpenFilterOptions](sharpenfilteroptions#constructor)() | Inicializa una nueva instancia del[`SharpenFilterOptions`](../sharpenfilteroptions)class. Con configuración predeterminada. |
| [SharpenFilterOptions](sharpenfilteroptions#constructor_1)(int, double) | Inicializa una nueva instancia del[`SharpenFilterOptions`](../sharpenfilteroptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bias](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/bias) { get; set; } | Obtiene o establece el sesgo. |
| [Factor](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/factor) { get; set; } | Obtiene o establece el factor. |
| [Sigma](../../aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/sigma) { get; set; } | Obtiene o establece el sigma. |
| [Size](../../aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/size) { get; set; } | Obtiene o establece el tamaño. |

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

* class [ConvolutionFilterOptions](../convolutionfilteroptions)
* espacio de nombres [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
