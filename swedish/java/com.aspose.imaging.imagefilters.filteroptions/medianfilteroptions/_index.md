---
title: "MedianFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Medianfilter"
type: docs
weight: 22
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/medianfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class MedianFilterOptions extends FilterOptionsBase
```

Medianfilter
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MedianFilterOptions(int size)](#MedianFilterOptions-int-) | Initierar en ny instans av klassen `MedianFilterOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSize()](#getSize--) | Hämtar eller anger storleken. |
| [setSize(int value)](#setSize-int-) | Hämtar eller anger storleken. |

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

### MedianFilterOptions(int size) {#MedianFilterOptions-int-}
```
public MedianFilterOptions(int size)
```


Initierar en ny instans av klassen `MedianFilterOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Storleken på filterrektangeln. |

### getSize() {#getSize--}
```
public int getSize()
```


Hämtar eller anger storleken.

Värde: storleken på filterrektangeln.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Hämtar eller anger storleken.

Värde: storleken på filterrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

