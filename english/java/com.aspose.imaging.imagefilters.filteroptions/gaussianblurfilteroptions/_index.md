---
title: GaussianBlurFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: The Gaussian blur filter options.
type: docs
weight: 16
url: /java/com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions, com.aspose.internal.imagefilters.convolution.ISquareConvolutionKernel
```
public class GaussianBlurFilterOptions extends ConvolutionFilterOptions implements IGaussianBlurOptions, ISquareConvolutionKernel
```

The Gaussian blur filter options.
## Constructors

| Constructor | Description |
| --- | --- |
| [GaussianBlurFilterOptions(int size, double sigma)](#GaussianBlurFilterOptions-int-double-) | Initializes a new instance of the [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) class. |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions--) | Initializes a new instance of the [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getKernel()](#getKernel--) | Gets the Gaussian kernel size. |
| [getSize()](#getSize--) | Gets the Gaussian kernel size. |
| [setSize(int value)](#setSize-int-) | The Gaussian kernel size. |
| [getSigma()](#getSigma--) | Gets the Gaussian kernel sigma (smoothing). |
| [setSigma(double value)](#setSigma-double-) | The Gaussian kernel sigma (smoothing). |
| [getRadius()](#getRadius--) | Gets the radius of Gaussian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | The radius of Gaussian ISquareConvolutionKernel. |

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

### GaussianBlurFilterOptions(int size, double sigma) {#GaussianBlurFilterOptions-int-double-}
```
public GaussianBlurFilterOptions(int size, double sigma)
```


Initializes a new instance of the [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int | The Gaussian kernel size.. |
| sigma | double | The Gaussian kernel sigma. |

### GaussianBlurFilterOptions() {#GaussianBlurFilterOptions--}
```
public GaussianBlurFilterOptions()
```


Initializes a new instance of the [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) class.

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Gets the Gaussian kernel size.

**Returns:**
double[][] - the Gaussian kernel size.
### getSize() {#getSize--}
```
public int getSize()
```


Gets the Gaussian kernel size. Must be a positive non-zero odd value.

**Returns:**
int - the Gaussian kernel size.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


The Gaussian kernel size. Must be a positive non-zero odd value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the Gaussian kernel size. |

### getSigma() {#getSigma--}
```
public double getSigma()
```


Gets the Gaussian kernel sigma (smoothing). Must be a positive non-zero value.

**Returns:**
double - the Gaussian kernel sigma (smoothing).
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


The Gaussian kernel sigma (smoothing). Must be a positive non-zero value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | the Gaussian kernel sigma (smoothing). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Gets the radius of Gaussian ISquareConvolutionKernel.

**Returns:**
int - the radius of Gaussian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


The radius of Gaussian ISquareConvolutionKernel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the radius of Gaussian ISquareConvolutionKernel. |

