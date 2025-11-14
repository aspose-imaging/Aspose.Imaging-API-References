---
title: MotionWienerFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: The motion de-blurring filter options.
type: docs
weight: 23
url: /java/com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends GaussianDeconvolutionFilterOptions
```

The motion de-blurring filter options.
## Constructors

| Constructor | Description |
| --- | --- |
| [MotionWienerFilterOptions(int size, double sigma, double angle)](#MotionWienerFilterOptions-int-double-double-) | Initializes a new instance of the [MotionWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getAngle()](#getAngle--) | Gets the angle in degrees. |
| [setAngle(double value)](#setAngle-double-) | Sets the angle in degrees. |
| [getKernel()](#getKernel--) | Gets the kernel. |

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

### MotionWienerFilterOptions(int size, double sigma, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int size, double sigma, double angle)
```


Initializes a new instance of the [MotionWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int | The Gaussian kernel size. |
| sigma | double | The Gaussian kernel sigma. |
| angle | double | The angle in degrees. |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Gets the angle in degrees.

Value: The angle.

**Returns:**
double - the angle in degrees.
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Sets the angle in degrees.

Value: The angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | the angle in degrees. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Gets the kernel.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - the kernel.
