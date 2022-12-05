---
title: MotionWienerFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: Deconvolution filter options     deblur motion
type: docs
weight: 18
url: /java/com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

Deconvolution filter options deblur motion
## Constructors

| Constructor | Description |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | Initializes a new instance of the `MotionWienerFilterOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getLength()](#getLength--) | Gets or sets the length. |
| [setLength(int value)](#setLength-int-) | Gets or sets the length. |
| [getSmooth()](#getSmooth--) | Gets or sets the smooth. |
| [setSmooth(double value)](#setSmooth-double-) | Gets or sets the smooth. |
| [getAngle()](#getAngle--) | Gets or sets the angle in gradus. |
| [setAngle(double value)](#setAngle-double-) | Gets or sets the angle in gradus. |

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

### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


Initializes a new instance of the `MotionWienerFilterOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| length | int | The length. |
| smooth | double | The smooth. |
| angle | double | The angle in gradus. |

### getLength() {#getLength--}
```
public int getLength()
```


Gets or sets the length.

Value: The length.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Gets or sets the length.

Value: The length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Gets or sets the smooth.

Value: The smooth.

**Returns:**
double
### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Gets or sets the smooth.

Value: The smooth.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getAngle() {#getAngle--}
```
public double getAngle()
```


Gets or sets the angle in gradus.

Value: The angle.

**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```


Gets or sets the angle in gradus.

Value: The angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

