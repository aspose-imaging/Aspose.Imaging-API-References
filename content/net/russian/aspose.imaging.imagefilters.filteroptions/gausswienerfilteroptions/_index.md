---
title: GaussWienerFilterOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры фильтра Винера Гаусса Удаление размытия gauss
type: docs
weight: 9770
url: /ru/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
## GaussWienerFilterOptions class

Параметры фильтра Винера Гаусса Удаление размытия gauss

```csharp
public class GaussWienerFilterOptions : DeconvolutionFilterOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor)() | Инициализирует новый экземпляр[`GaussWienerFilterOptions`](../gausswienerfilteroptions) class. С настройками по умолчанию. |
| [GaussWienerFilterOptions](gausswienerfilteroptions#constructor_1)(int, double) | Инициализирует новый экземпляр[`GaussWienerFilterOptions`](../gausswienerfilteroptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness) { get; set; } | Получает или устанавливает яркость. рекомендуемый диапазон 1–1,5 значение по умолчанию = 1,15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale) { get; set; } | Получает или задает значение, указывающее, является ли это[`DeconvolutionFilterOptions`](../deconvolutionfilteroptions)в градациях серого. Вернуть режим градаций серого или режим RGB. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded) { get; } | Получает значение, указывающее, загружен ли этот экземпляр частично. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/radius) { get; set; } | Получает или задает радиус. |
| [Smooth](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/smooth) { get; set; } | Получает или задает сглаживание. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr) { get; set; } | Получает или задает SNR (отношение сигнал/шум) рекомендуемый диапазон 0,002–0,009, значение по умолчанию = 0,007 |

### Примеры

В следующем примере к растровому изображению применяются различные типы фильтров.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Применяем медианный фильтр с размером прямоугольника 5 ко всему изображению.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Применяем фильтр двустороннего сглаживания с размером ядра 5 ко всему изображению.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Применяем ко всему изображению фильтр размытия по Гауссу с радиусом 5 и значением сигмы 4,0.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Применяем ко всему изображению фильтр Гаусса-Винера с радиусом 5 и значением гладкости 4,0.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Применяем фильтр Винера движения с длиной 5, значением гладкости 4,0 и углом 90,0 градусов ко всему изображению.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Применяем фильтр резкости с размером ядра 5 и значением сигмы 4,0 ко всему изображению.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### Смотрите также

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions)
* пространство имен [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
