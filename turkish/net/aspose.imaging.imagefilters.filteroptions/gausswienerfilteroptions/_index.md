---
title: GaussWienerFilterOptions
second_title: Aspose.Imaging for .NET API Referansı
description: Gauss Wiener Filtre Seçenekleri Deblur gauss
type: docs
weight: 9770
url: /tr/net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
## GaussWienerFilterOptions class

Gauss Wiener Filtre Seçenekleri Deblur gauss

```csharp
public class GaussWienerFilterOptions : DeconvolutionFilterOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor)() | Yeni bir örneğini başlatır[`GaussWienerFilterOptions`](../gausswienerfilteroptions) class. Varsayılan ayarlarla. |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor_1)(int, double) | Yeni bir örneğini başlatır[`GaussWienerFilterOptions`](../gausswienerfilteroptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness) { get; set; } | Parlaklığı alır veya ayarlar. önerilen aralık 1 - 1.5 varsayılan değer = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`DeconvolutionFilterOptions`](../deconvolutionfilteroptions)gri tonlamalıdır. Gri tonlama modunu veya RGB modunu döndürür. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded) { get; } | Bu örneğin kısmi yüklenip yüklenmediğini gösteren bir değer alır. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/radius) { get; set; } | Yarıçapı alır veya ayarlar. |
| [Smooth](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/smooth) { get; set; } | Düzgünlüğü alır veya ayarlar. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr) { get; set; } | SNR(sinyal-gürültü oranı) önerilen aralığı 0,002 - 0,009 alır veya ayarlar, varsayılan değer = 0,007 |

### Örnekler

Aşağıdaki örnek, bir tarama görüntüsüne çeşitli filtre türleri uygular.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Tüm görüntüye dikdörtgen boyutu 5 olan bir medyan filtresi uygulayın.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Tüm görüntüye çekirdek boyutu 5 olan iki taraflı bir yumuşatma filtresi uygulayın.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Tüm görüntüye yarıçapı 5 ve sigma değeri 4.0 olan bir Gauss bulanıklaştırma filtresi uygulayın.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Tüm görüntüye yarıçapı 5 ve düzgün değeri 4.0 olan bir Gauss-Wiener filtresi uygulayın.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Görüntünün tamamına 5 uzunluğunda, 4,0 düzgün değerinde ve 90,0 derecelik bir açıda bir hareket wiener filtresi uygulayın.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Tüm görüntüye çekirdek boyutu 5 ve sigma değeri 4.0 olan bir keskinleştirme filtresi uygulayın.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### Ayrıca bakınız

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions)
* ad alanı [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
