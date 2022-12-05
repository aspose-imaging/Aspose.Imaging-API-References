---
title: GaussianBlurFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: The Gaussian blur
type: docs
weight: 16
url: /java/com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions)
```
public class GaussianBlurFilterOptions extends ConvolutionFilterOptions
```

The Gaussian blur
## Constructors

| Constructor | Description |
| --- | --- |
| [GaussianBlurFilterOptions(int radius, double sigma)](#GaussianBlurFilterOptions-int-double-) | Initializes a new instance of the `GaussianBlurFilterOptions` class. |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions--) | Initializes a new instance of the `GaussianBlurFilterOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Gets or sets the radius. |
| [setRadius(int value)](#setRadius-int-) | Gets or sets the radius. |
| [getSigma()](#getSigma--) | Gets or sets the sigma. |
| [setSigma(double value)](#setSigma-double-) | Gets or sets the sigma. |

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

### GaussianBlurFilterOptions(int radius, double sigma) {#GaussianBlurFilterOptions-int-double-}
```
public GaussianBlurFilterOptions(int radius, double sigma)
```


Initializes a new instance of the `GaussianBlurFilterOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | int | The radius. |
| sigma | double | The sigma. |

### GaussianBlurFilterOptions() {#GaussianBlurFilterOptions--}
```
public GaussianBlurFilterOptions()
```


Initializes a new instance of the `GaussianBlurFilterOptions` class. With default settings.

### getRadius() {#getRadius--}
```
public int getRadius()
```


Gets or sets the radius.

Value: The radius.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Gets or sets the radius.

Value: The radius.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSigma() {#getSigma--}
```
public double getSigma()
```


Gets or sets the sigma.

Value: The sigma.

**Returns:**
double
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


Gets or sets the sigma.

Value: The sigma.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

