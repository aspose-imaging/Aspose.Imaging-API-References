---
title: "MotionWienerFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات مرشح إزالة الضبابية الحركية."
type: docs
weight: 23
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends GaussianDeconvolutionFilterOptions
```

خيارات مرشح إزالة الضبابية الحركية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MotionWienerFilterOptions(int size, double sigma, double angle)](#MotionWienerFilterOptions-int-double-double-) | يُنشئ مثلاً جديدًا من الفئة [MotionWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAngle()](#getAngle--) | يحصل على الزاوية بالدرجات. |
| [setAngle(double value)](#setAngle-double-) | يضبط الزاوية بالدرجات. |
| [getKernel()](#getKernel--) | يحصل على النواة. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح متوسط بحجم مستطيل 5 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح تمهيد ثنائي الجانب بحجم نواة 5 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح غاوس-واينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح واينر حركي بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // طبق مرشح شحذ بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بأكملها.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### MotionWienerFilterOptions(int size, double sigma, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int size, double sigma, double angle)
```


يُنشئ مثلاً جديدًا من الفئة [MotionWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الحجم | int | حجم نواة Gaussian. |
| سيغما | double | سيغما نواة Gaussian. |
| angle | double | الزاوية بالدرجات. |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


يحصل على الزاوية بالدرجات.

القيمة: الزاوية.

**Returns:**
double - الزاوية بالدرجات.
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


يضبط الزاوية بالدرجات.

القيمة: الزاوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | الزاوية بالدرجات. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


يحصل على النواة.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - النواة.
