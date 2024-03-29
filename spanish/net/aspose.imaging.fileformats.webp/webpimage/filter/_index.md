---
title: Filter
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Filtra el rectángulo especificado.
type: docs
weight: 190
url: /es/net/aspose.imaging.fileformats.webp/webpimage/filter/
---
## WebPImage.Filter method

Filtra el rectángulo especificado.

```csharp
public override void Filter(Rectangle rectangle, FilterOptionsBase options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rectangle | Rectangle | el rectángulo |
| options | FilterOptionsBase | Las opciones. |

### Ejemplos

El siguiente ejemplo aplica varios tipos de filtros a una imagen WEBP.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Aplicar un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    webpImage.Save(dir + "sample.MedianFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Aplicar un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    webpImage.Save(dir + "sample.BilateralSmoothingFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Aplicar un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4,0 a toda la imagen.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.Save(dir + "sample.GaussianBlurFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Aplicar un filtro de Gauss-Wiener con un radio de 5 y un valor suave de 4,0 a toda la imagen.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.Save(dir + "sample.GaussWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Aplicar un filtro Wiener de movimiento con una longitud de 5, un valor suave de 4,0 y un ángulo de 90,0 grados a toda la imagen.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.Save(dir + "sample.MotionWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Aplicar un filtro de nitidez con un tamaño de núcleo de 5 y un valor sigma de 4,0 a toda la imagen.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    webpImage.Save(dir + "sample.SharpenFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ver también

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [FilterOptionsBase](../../../aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
* class [WebPImage](../../webpimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
