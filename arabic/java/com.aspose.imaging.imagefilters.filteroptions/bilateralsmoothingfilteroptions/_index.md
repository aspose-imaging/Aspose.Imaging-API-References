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
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | ينشئ مثالًا جديدًا من الفئة `BilateralSmoothingFilterOptions`. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | ينشئ مثالًا جديدًا من الفئة `BilateralSmoothingFilterOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يحصل أو يضبط حجم النواة. |
| [setSize(int value)](#setSize-int-) | يحصل أو يضبط حجم النواة. |
| [getSpatialFactor()](#getSpatialFactor--) | يحصل أو يضبط العامل المكاني. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | يحصل أو يضبط العامل المكاني. |
| [getSpatialPower()](#getSpatialPower--) | يحصل أو يضبط القوة المكانية. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | يحصل أو يضبط القوة المكانية. |
| [getColorFactor()](#getColorFactor--) | يحصل أو يضبط عامل اللون. |
| [setColorFactor(double value)](#setColorFactor-double-) | يحصل أو يضبط عامل اللون. |
| [getColorPower()](#getColorPower--) | يحصل أو يضبط قوة اللون. |
| [setColorPower(double value)](#setColorPower-double-) | يحصل أو يضبط قوة اللون. |

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

### BilateralSmoothingFilterOptions(int size) {#BilateralSmoothingFilterOptions-int-}
```
public BilateralSmoothingFilterOptions(int size)
```


ينشئ مثالًا جديدًا من الفئة `BilateralSmoothingFilterOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | int | حجم النواة. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


ينشئ مثالًا جديدًا من الفئة `BilateralSmoothingFilterOptions`.

### getSize() {#getSize--}
```
public int getSize()
```


يحصل أو يضبط حجم النواة.

القيمة: حجم النواة.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


يحصل أو يضبط حجم النواة.

القيمة: حجم النواة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


يحصل أو يضبط العامل المكاني.

القيمة: العامل المكاني.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


يحصل أو يضبط العامل المكاني.

القيمة: العامل المكاني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


يحصل أو يضبط القوة المكانية.

القيمة: القوة المكانية.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


يحصل أو يضبط القوة المكانية.

القيمة: القوة المكانية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


يحصل أو يضبط عامل اللون.

القيمة: عامل اللون.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


يحصل أو يضبط عامل اللون.

القيمة: عامل اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


يحصل أو يضبط قوة اللون.

القيمة: قوة اللون.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


يحصل أو يضبط قوة اللون.

القيمة: قوة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double |  |

