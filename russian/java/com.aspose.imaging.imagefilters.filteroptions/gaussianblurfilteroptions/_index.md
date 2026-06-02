---
title: "GaussianBlurFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры фильтра гауссового размытия."
type: docs
weight: 19
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions, com.aspose.internal.imagefilters.convolution.ISquareConvolutionKernel
```
public class GaussianBlurFilterOptions extends ConvolutionFilterOptions implements IGaussianBlurOptions, ISquareConvolutionKernel
```

Параметры фильтра гауссового размытия.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GaussianBlurFilterOptions(int size, double sigma)](#GaussianBlurFilterOptions-int-double-) | Инициализирует новый экземпляр класса [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions--) | Инициализирует новый экземпляр класса [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getKernel()](#getKernel--) | Получает размер гауссовского ядра. |
| [getSize()](#getSize--) | Получает размер гауссовского ядра. |
| [setSize(int value)](#setSize-int-) | Размер ядра Гаусса. |
| [getSigma()](#getSigma--) | Получает сигму (сглаживание) гауссовского ядра. |
| [setSigma(double value)](#setSigma-double-) | Сигма гауссовского ядра (сглаживание). |
| [getRadius()](#getRadius--) | Получает радиус гауссовского **ISquareConvolutionKernel**. |
| [setRadius(int value)](#setRadius-int-) | Радиус гауссовского **ISquareConvolutionKernel**. |

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

### GaussianBlurFilterOptions(int size, double sigma) {#GaussianBlurFilterOptions-int-double-}
```
public GaussianBlurFilterOptions(int size, double sigma)
```


Инициализирует новый экземпляр класса [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | int | Размер гауссовского ядра.. |
| sigma | double | Сигма ядра Гаусса. |

### GaussianBlurFilterOptions() {#GaussianBlurFilterOptions--}
```
public GaussianBlurFilterOptions()
```


Инициализирует новый экземпляр класса [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Получает размер гауссовского ядра.

**Returns:**
double[][] - размер гауссовского ядра.
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

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Получает радиус гауссовского **ISquareConvolutionKernel**.

**Returns:**
int - радиус гауссовского **ISquareConvolutionKernel**.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Радиус гауссовского **ISquareConvolutionKernel**.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | радиус гауссовского **ISquareConvolutionKernel**. |

