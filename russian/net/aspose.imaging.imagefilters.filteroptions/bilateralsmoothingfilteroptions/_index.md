---
title: BilateralSmoothingFilterOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры фильтра двустороннего сглаживания.
type: docs
weight: 9730
url: /ru/net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
## BilateralSmoothingFilterOptions class

Параметры фильтра двустороннего сглаживания.

```csharp
public class BilateralSmoothingFilterOptions : FilterOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BilateralSmoothingFilterOptions](bilateralsmoothingfilteroptions#constructor)() | Инициализирует новый экземпляр[`BilateralSmoothingFilterOptions`](../bilateralsmoothingfilteroptions) класс. |
| [BilateralSmoothingFilterOptions](bilateralsmoothingfilteroptions#constructor_1)(int) | Инициализирует новый экземпляр[`BilateralSmoothingFilterOptions`](../bilateralsmoothingfilteroptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ColorFactor](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/colorfactor) { get; set; } | Получает или задает коэффициент цвета. |
| [ColorPower](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/colorpower) { get; set; } | Получает или задает мощность цвета. |
| [Size](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/size) { get; set; } | Получает или устанавливает размер ядра. |
| [SpatialFactor](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/spatialfactor) { get; set; } | Получает или задает пространственный фактор. |
| [SpatialPower](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/spatialpower) { get; set; } | Получает или задает пространственную мощность. |

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

* class [FilterOptionsBase](../filteroptionsbase)
* пространство имен [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
