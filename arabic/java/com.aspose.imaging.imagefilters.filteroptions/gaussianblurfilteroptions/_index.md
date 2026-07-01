---
title: "GaussianBlurFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات مرشح الضبابية الغاوسية."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions, com.aspose.internal.imagefilters.convolution.ISquareConvolutionKernel
```
public class GaussianBlurFilterOptions extends ConvolutionFilterOptions implements IGaussianBlurOptions, ISquareConvolutionKernel
```

خيارات مرشح الضبابية الغاوسية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GaussianBlurFilterOptions(int size, double sigma)](#GaussianBlurFilterOptions-int-double-) | ينشئ مثلاً جديداً من الفئة [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions--) | ينشئ مثلاً جديداً من الفئة [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getKernel()](#getKernel--) | يحصل على حجم نواة Gaussian. |
| [getSize()](#getSize--) | يحصل على حجم نواة Gaussian. |
| [setSize(int value)](#setSize-int-) | حجم نواة Gaussian. |
| [getSigma()](#getSigma--) | يحصل على سيغما نواة Gaussian (التنعيم). |
| [setSigma(double value)](#setSigma-double-) | سيغما نواة Gaussian (التنعيم). |
| [getRadius()](#getRadius--) | يحصل على نصف قطر Gaussian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | نصف قطر Gaussian ISquareConvolutionKernel. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // تطبيق مرشح متوسط بحجم مستطيل 5 على الصورة بالكامل.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // تطبيق مرشح تنعيم ثنائي الجانب بحجم نواة 5 على الصورة بالكامل.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // تطبيق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // تطبيق مرشح غاوس-واينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بالكامل.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // تطبيق مرشح حركة واينر بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بالكامل.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // تطبيق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بالكامل.
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


ينشئ مثلاً جديداً من الفئة [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | int | حجم نواة Gaussian.. |
| sigma | double | قيمة sigma لنواة Gaussian. |

### GaussianBlurFilterOptions() {#GaussianBlurFilterOptions--}
```
public GaussianBlurFilterOptions()
```


ينشئ مثلاً جديداً من الفئة [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


يحصل على حجم نواة Gaussian.

**Returns:**
double[][] - حجم نواة Gaussian.
### getSize() {#getSize--}
```
public int getSize()
```


يحصل على حجم نواة Gaussian. يجب أن تكون قيمة موجبة غير صفرية وفردية.

**Returns:**
int - حجم نواة Gaussian.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


حجم نواة Gaussian. يجب أن تكون قيمة موجبة غير صفرية وفردية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | حجم نواة Gaussian. |

### getSigma() {#getSigma--}
```
public double getSigma()
```


يحصل على سيغما نواة Gaussian (التنعيم). يجب أن تكون قيمة موجبة غير صفرية.

**Returns:**
double - سيغما نواة Gaussian (التنعيم).
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


سيغما نواة Gaussian (التنعيم). يجب أن تكون قيمة موجبة غير صفرية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double | سيغما نواة Gaussian (التنعيم). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


يحصل على نصف قطر Gaussian ISquareConvolutionKernel.

**Returns:**
int - نصف قطر Gaussian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


نصف قطر Gaussian ISquareConvolutionKernel.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | نصف قطر Gaussian ISquareConvolutionKernel. |

