---
title: "MotionWienerFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Rörelseavskärpningsfilteralternativen."
type: docs
weight: 23
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends GaussianDeconvolutionFilterOptions
```

Rörelseavskärpningsfilteralternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MotionWienerFilterOptions(int size, double sigma, double angle)](#MotionWienerFilterOptions-int-double-double-) | Initierar en ny instans av klassen [MotionWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAngle()](#getAngle--) | Hämtar vinkeln i grader. |
| [setAngle(double value)](#setAngle-double-) | Ställer in vinkeln i grader. |
| [getKernel()](#getKernel--) | Hämtar kärnan. |

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

### MotionWienerFilterOptions(int size, double sigma, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int size, double sigma, double angle)
```


Initierar en ny instans av klassen [MotionWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions) klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Den gaussiska kärnans storlek. |
| sigma | double | Den gaussiska kärnans sigma. |
| angle | double | Vinkeln i grader. |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Hämtar vinkeln i grader.

Värde: Vinkeln.

**Returns:**
double - vinkeln i grader.
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Ställer in vinkeln i grader.

Värde: Vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | vinkeln i grader. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Hämtar kärnan.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - kärnan.
