---
title: "SharpenFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات مرشح تحسين الحدة."
type: docs
weight: 25
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions)
```
public class SharpenFilterOptions extends GaussianBlurFilterOptions
```

خيارات مرشح تحسين الحدة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SharpenFilterOptions(int size, double sigma)](#SharpenFilterOptions-int-double-) | يُنشئ مثيلًا جديدًا من الفئة [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions). |
| [SharpenFilterOptions()](#SharpenFilterOptions--) | يُنشئ مثيلًا جديدًا من الفئة [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getKernel()](#getKernel--) | يحصل على النواة. |
| [getSize()](#getSize--) | يحصل على حجم نواة Gaussian. |
| [setSize(int value)](#setSize-int-) | حجم نواة Gaussian. |
| [getSigma()](#getSigma--) | يحصل على سيغما نواة Gaussian (التنعيم). |
| [setSigma(double value)](#setSigma-double-) | سيغما نواة Gaussian (التنعيم). |

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

### SharpenFilterOptions(int size, double sigma) {#SharpenFilterOptions-int-double-}
```
public SharpenFilterOptions(int size, double sigma)
```


يُنشئ مثيلًا جديدًا من الفئة [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | int | حجم النواة. |
| sigma | double | سيغما. |

### SharpenFilterOptions() {#SharpenFilterOptions--}
```
public SharpenFilterOptions()
```


يُنشئ مثيلًا جديدًا من الفئة [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions).

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


يحصل على النواة.

**Returns:**
double[][] - النواة.
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

