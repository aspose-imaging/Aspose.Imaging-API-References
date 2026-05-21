---
title: "BilateralSmoothingFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات مرشح التنعيم الثنائي."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

خيارات مرشح التنعيم الثنائي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | ينشئ مثيلًا جديدًا من الفئة `BilateralSmoothingFilterOptions`. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | ينشئ مثيلًا جديدًا من الفئة `BilateralSmoothingFilterOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يسترجع أو يعيّن حجم النواة. |
| [setSize(int value)](#setSize-int-) | يسترجع أو يعيّن حجم النواة. |
| [getSpatialFactor()](#getSpatialFactor--) | يسترجع أو يعيّن العامل المكاني. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | يسترجع أو يعيّن العامل المكاني. |
| [getSpatialPower()](#getSpatialPower--) | يسترجع أو يعيّن القوة المكانية. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | يسترجع أو يعيّن القوة المكانية. |
| [getColorFactor()](#getColorFactor--) | يسترجع أو يعيّن عامل اللون. |
| [setColorFactor(double value)](#setColorFactor-double-) | يسترجع أو يعيّن عامل اللون. |
| [getColorPower()](#getColorPower--) | يسترجع أو يعيّن قوة اللون. |
| [setColorPower(double value)](#setColorPower-double-) | يسترجع أو يعيّن قوة اللون. |

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

### BilateralSmoothingFilterOptions(int size) {#BilateralSmoothingFilterOptions-int-}
```
public BilateralSmoothingFilterOptions(int size)
```


ينشئ مثيلًا جديدًا من الفئة `BilateralSmoothingFilterOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الحجم | int | حجم النواة. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


ينشئ مثيلًا جديدًا من الفئة `BilateralSmoothingFilterOptions`.

### getSize() {#getSize--}
```
public int getSize()
```


يسترجع أو يعيّن حجم النواة.

القيمة: حجم النواة.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


يسترجع أو يعيّن حجم النواة.

القيمة: حجم النواة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


يسترجع أو يعيّن العامل المكاني.

القيمة: العامل المكاني.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


يسترجع أو يعيّن العامل المكاني.

القيمة: العامل المكاني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


يسترجع أو يعيّن القوة المكانية.

القيمة: القوة المكانية.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


يسترجع أو يعيّن القوة المكانية.

القيمة: القوة المكانية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


يسترجع أو يعيّن عامل اللون.

القيمة: عامل اللون.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


يسترجع أو يعيّن عامل اللون.

القيمة: عامل اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


يسترجع أو يعيّن قوة اللون.

القيمة: قوة اللون.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


يسترجع أو يعيّن قوة اللون.

القيمة: قوة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

