---
title: "BilateralSmoothingFilterOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры фильтра Bilateral Smoothing."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

Параметры фильтра Bilateral Smoothing.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | Инициализирует новый экземпляр класса `BilateralSmoothingFilterOptions`. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | Инициализирует новый экземпляр класса `BilateralSmoothingFilterOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSize()](#getSize--) | Получает или задает размер ядра. |
| [setSize(int value)](#setSize-int-) | Получает или задает размер ядра. |
| [getSpatialFactor()](#getSpatialFactor--) | Получает или задает пространственный коэффициент. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | Получает или задает пространственный коэффициент. |
| [getSpatialPower()](#getSpatialPower--) | Получает или задает пространственную степень. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | Получает или задает пространственную степень. |
| [getColorFactor()](#getColorFactor--) | Получает или задает цветовой коэффициент. |
| [setColorFactor(double value)](#setColorFactor-double-) | Получает или задает цветовой коэффициент. |
| [getColorPower()](#getColorPower--) | Получает или задает цветовую степень. |
| [setColorPower(double value)](#setColorPower-double-) | Получает или задает цветовую степень. |

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

### BilateralSmoothingFilterOptions(int size) {#BilateralSmoothingFilterOptions-int-}
```
public BilateralSmoothingFilterOptions(int size)
```


Инициализирует новый экземпляр класса `BilateralSmoothingFilterOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | int | Размер ядра. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


Инициализирует новый экземпляр класса `BilateralSmoothingFilterOptions`.

### getSize() {#getSize--}
```
public int getSize()
```


Получает или задает размер ядра.

Значение: Размер ядра.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Получает или задает размер ядра.

Значение: Размер ядра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


Получает или задает пространственный коэффициент.

Значение: Пространственный коэффициент.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


Получает или задает пространственный коэффициент.

Значение: Пространственный коэффициент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


Получает или задает пространственную степень.

Значение: Пространственная степень.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


Получает или задает пространственную степень.

Значение: Пространственная степень.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


Получает или задает цветовой коэффициент.

Значение: Цветовой коэффициент.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


Получает или задает цветовой коэффициент.

Значение: Цветовой коэффициент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


Получает или задает цветовую степень.

Значение: Цветовая степень.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


Получает или задает цветовую степень.

Значение: Цветовая степень.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

