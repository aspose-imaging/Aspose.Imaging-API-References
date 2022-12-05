---
title: BilateralSmoothingFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: The Bilateral Smoothing Filter Options.
type: docs
weight: 11
url: /java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

The Bilateral Smoothing Filter Options.
## Constructors

| Constructor | Description |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | Initializes a new instance of the `BilateralSmoothingFilterOptions` class. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | Initializes a new instance of the `BilateralSmoothingFilterOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Gets or sets the size of the kernel. |
| [setSize(int value)](#setSize-int-) | Gets or sets the size of the kernel. |
| [getSpatialFactor()](#getSpatialFactor--) | Gets or sets the spatial factor. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | Gets or sets the spatial factor. |
| [getSpatialPower()](#getSpatialPower--) | Gets or sets the spatial power. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | Gets or sets the spatial power. |
| [getColorFactor()](#getColorFactor--) | Gets or sets the color factor. |
| [setColorFactor(double value)](#setColorFactor-double-) | Gets or sets the color factor. |
| [getColorPower()](#getColorPower--) | Gets or sets the color power. |
| [setColorPower(double value)](#setColorPower-double-) | Gets or sets the color power. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Apply a median filter with a rectangle size of 5 to the entire image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Apply a bilateral smoothing filter with a kernel size of 5 to the entire image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Apply a Gaussian blur filter with a radius of 5 and a sigma value of 4.0 to the entire image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Apply a Gauss-Wiener filter with a radius of 5 and a smooth value of 4.0 to the entire image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Apply a motion wiener filter with a length of 5, a smooth value of 4.0 and an angle of 90.0 degrees to the entire image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Apply a sharpen filter with a kernel size of 5 and a sigma value of 4.0 to the entire image.
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


Initializes a new instance of the `BilateralSmoothingFilterOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int | Size of the kernal. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


Initializes a new instance of the `BilateralSmoothingFilterOptions` class.

### getSize() {#getSize--}
```
public int getSize()
```


Gets or sets the size of the kernel.

Value: The size of the kernel.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Gets or sets the size of the kernel.

Value: The size of the kernel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


Gets or sets the spatial factor.

Value: The spatial factor.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


Gets or sets the spatial factor.

Value: The spatial factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


Gets or sets the spatial power.

Value: The spatial power.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


Gets or sets the spatial power.

Value: The spatial power.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


Gets or sets the color factor.

Value: The color factor.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


Gets or sets the color factor.

Value: The color factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


Gets or sets the color power.

Value: The color power.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


Gets or sets the color power.

Value: The color power.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

