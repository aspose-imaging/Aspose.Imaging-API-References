---
title: "SharpenFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры фильтра повышения резкости."
type: docs
weight: 25
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions)
```
public class SharpenFilterOptions extends GaussianBlurFilterOptions
```

Параметры фильтра повышения резкости.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SharpenFilterOptions(int size, double sigma)](#SharpenFilterOptions-int-double-) | Инициализирует новый экземпляр класса [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) class. |
| [SharpenFilterOptions()](#SharpenFilterOptions--) | Инициализирует новый экземпляр класса [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) class. |
## Методы

| Метод | Описание |
| --- | --- |
| [getKernel()](#getKernel--) | Возвращает ядро. |
| [getSize()](#getSize--) | Получает размер гауссовского ядра. |
| [setSize(int value)](#setSize-int-) | Размер ядра Гаусса. |
| [getSigma()](#getSigma--) | Получает сигму (сглаживание) гауссовского ядра. |
| [setSigma(double value)](#setSigma-double-) | Сигма гауссовского ядра (сглаживание). |

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

### SharpenFilterOptions(int size, double sigma) {#SharpenFilterOptions-int-double-}
```
public SharpenFilterOptions(int size, double sigma)
```


Инициализирует новый экземпляр класса [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) class.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | int | Размер ядра. |
| sigma | double | Сигма. |

### SharpenFilterOptions() {#SharpenFilterOptions--}
```
public SharpenFilterOptions()
```


Инициализирует новый экземпляр класса [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) class.

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Возвращает ядро.

**Returns:**
double[][] - ядро.
### getSize() {#getSize--}
```
public int getSize()
```


Получает размер гауссовского ядра. Должно быть положительным не нулевым нечётным значением.

**Returns:**
int - размер гауссовского ядра.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Размер гауссовского ядра. Должно быть положительным не нулевым нечётным значением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | размер гауссовского ядра. |

### getSigma() {#getSigma--}
```
public double getSigma()
```


Получает сигму гауссовского ядра (сглаживание). Должно быть положительным не нулевым значением.

**Returns:**
double - сигма гауссовского ядра (сглаживание).
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


Сигма гауссовского ядра (сглаживание). Должно быть положительным не нулевым значением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | сигма гауссовского ядра (сглаживание). |

