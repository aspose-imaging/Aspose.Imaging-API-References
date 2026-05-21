---
title: "GaussianBlurFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Gaussian blur-filteralternativen."
type: docs
weight: 19
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions, com.aspose.internal.imagefilters.convolution.ISquareConvolutionKernel
```
public class GaussianBlurFilterOptions extends ConvolutionFilterOptions implements IGaussianBlurOptions, ISquareConvolutionKernel
```

Gaussian blur-filteralternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GaussianBlurFilterOptions(int size, double sigma)](#GaussianBlurFilterOptions-int-double-) | Initierar en ny instans av klassen [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions--) | Initierar en ny instans av klassen [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getKernel()](#getKernel--) | Hämtar den Gaussiska kärnans storlek. |
| [getSize()](#getSize--) | Hämtar den Gaussiska kärnans storlek. |
| [setSize(int value)](#setSize-int-) | Den gaussiska kärnans storlek. |
| [getSigma()](#getSigma--) | Hämtar den Gaussiska kärnans sigma (utjämning). |
| [setSigma(double value)](#setSigma-double-) | Den Gaussiska kärnans sigma (utjämning). |
| [getRadius()](#getRadius--) | Hämtar radien för Gaussisk ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | Radien för Gaussisk ISquareConvolutionKernel. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett medianfilter med en rektangelstorlek på 5 på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett Gaussiskt oskärpefilter med en radie på 5 och ett sigma‑värde på 4,0 på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett Gauss‑Wiener-filter med en radie på 5 och ett jämnvärde på 4,0 på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett rörelse‑Wiener-filter med en längd på 5, ett jämnvärde på 4,0 och en vinkel på 90,0 grader på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett skärpningsfilter med en kärnstorlek på 5 och ett sigma‑värde på 4,0 på hela bilden.
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


Initierar en ny instans av klassen [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Den Gaussiska kärnans storlek.. |
| sigma | double | Den gaussiska kärnans sigma. |

### GaussianBlurFilterOptions() {#GaussianBlurFilterOptions--}
```
public GaussianBlurFilterOptions()
```


Initierar en ny instans av klassen [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Hämtar den Gaussiska kärnans storlek.

**Returns:**
double[][] - den Gaussiska kärnans storlek.
### getSize() {#getSize--}
```
public int getSize()
```


Hämtar den Gaussiska kärnans storlek. Måste vara ett positivt, icke‑noll, udda värde.

**Returns:**
int - den Gaussiska kärnans storlek.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Den Gaussiska kärnans storlek. Måste vara ett positivt, icke‑noll, udda värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | den Gaussiska kärnans storlek. |

### getSigma() {#getSigma--}
```
public double getSigma()
```


Hämtar den Gaussiska kärnans sigma (utjämning). Måste vara ett positivt, icke‑noll värde.

**Returns:**
double - den Gaussiska kärnans sigma (utjämning).
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


Den Gaussiska kärnans sigma (utjämning). Måste vara ett positivt, icke‑noll värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | den Gaussiska kärnans sigma (utjämning). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Hämtar radien för Gaussisk ISquareConvolutionKernel.

**Returns:**
int - radien för Gaussisk ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Radien för Gaussisk ISquareConvolutionKernel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | radien för Gaussisk ISquareConvolutionKernel. |

