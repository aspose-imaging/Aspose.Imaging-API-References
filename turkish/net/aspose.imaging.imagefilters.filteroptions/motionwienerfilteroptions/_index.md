---
title: MotionWienerFilterOptions
second_title: Aspose.Imaging for .NET API Referansı
description: Evrişim filtresi seçenekleri hareket bulanıklığını giderme
type: docs
weight: 9800
url: /tr/net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---
## MotionWienerFilterOptions class

Evrişim filtresi seçenekleri hareket bulanıklığını giderme

```csharp
public class MotionWienerFilterOptions : DeconvolutionFilterOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MotionWienerFilterOptions](motionwienerfilteroptions)(int, double, double) | Yeni bir örneğini başlatır[`MotionWienerFilterOptions`](../motionwienerfilteroptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Angle](../../aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/angle) { get; set; } | Açıyı gradus olarak alır veya ayarlar. |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness) { get; set; } | Parlaklığı alır veya ayarlar. önerilen aralık 1 - 1.5 varsayılan değer = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`DeconvolutionFilterOptions`](../deconvolutionfilteroptions)gri tonlamalıdır. Gri tonlama modunu veya RGB modunu döndürür. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded) { get; } | Bu örneğin kısmi yüklenip yüklenmediğini gösteren bir değer alır. |
| [Length](../../aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/length) { get; set; } | Uzunluğu alır veya ayarlar. |
| [Smooth](../../aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/smooth) { get; set; } | Düzgünlüğü alır veya ayarlar. |
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
