---
title: "GaussWienerFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры фильтра Гаусса-Винера для устранения размытия изображения."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends GaussianDeconvolutionFilterOptions
```

Параметры фильтра Гаусса-Винера для устранения размытия изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GaussWienerFilterOptions(int size, double sigma)](#GaussWienerFilterOptions-int-double-) | Инициализирует новый экземпляр класса [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions). |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Инициализирует новый экземпляр класса [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getKernel()](#getKernel--) | Возвращает ядро. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените медианный фильтр с размером прямоугольника 5 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените билатеральный сглаживающий фильтр с размером ядра 5 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените гауссов фильтр размытия с радиусом 5 и значением sigma 4.0 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените фильтр Гаусса-Винера с радиусом 5 и значением smooth 4.0 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените фильтр движения Винера с длиной 5, значением smooth 4.0 и углом 90,0 градусов ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Примените фильтр резкости с размером ядра 5 и значением sigma 4.0 ко всему изображению.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### GaussWienerFilterOptions(int size, double sigma) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int size, double sigma)
```


Инициализирует новый экземпляр класса [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | int | Размер ядра Гаусса. |
| sigma | double | Сигма ядра Гаусса. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Инициализирует новый экземпляр класса [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions).

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Возвращает ядро.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - ядро.
