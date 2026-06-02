---
title: "BilateralSmoothingFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Alternativen för Bilateral Smoothing-filter."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

Alternativen för Bilateral Smoothing-filter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | Initierar en ny instans av klassen `BilateralSmoothingFilterOptions`. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | Initierar en ny instans av klassen `BilateralSmoothingFilterOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSize()](#getSize--) | Hämtar eller anger storleken på kärnan. |
| [setSize(int value)](#setSize-int-) | Hämtar eller anger storleken på kärnan. |
| [getSpatialFactor()](#getSpatialFactor--) | Hämtar eller anger den rumsliga faktorn. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | Hämtar eller anger den rumsliga faktorn. |
| [getSpatialPower()](#getSpatialPower--) | Hämtar eller anger den rumsliga styrkan. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | Hämtar eller anger den rumsliga styrkan. |
| [getColorFactor()](#getColorFactor--) | Hämtar eller anger färgfaktorn. |
| [setColorFactor(double value)](#setColorFactor-double-) | Hämtar eller anger färgfaktorn. |
| [getColorPower()](#getColorPower--) | Hämtar eller anger färgstyrkan. |
| [setColorPower(double value)](#setColorPower-double-) | Hämtar eller anger färgstyrkan. |

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

### BilateralSmoothingFilterOptions(int size) {#BilateralSmoothingFilterOptions-int-}
```
public BilateralSmoothingFilterOptions(int size)
```


Initierar en ny instans av klassen `BilateralSmoothingFilterOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Storlek på kärnan. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


Initierar en ny instans av klassen `BilateralSmoothingFilterOptions`.

### getSize() {#getSize--}
```
public int getSize()
```


Hämtar eller anger storleken på kärnan.

Värde: Storleken på kärnan.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Hämtar eller anger storleken på kärnan.

Värde: Storleken på kärnan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


Hämtar eller anger den rumsliga faktorn.

Värde: Den rumsliga faktorn.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


Hämtar eller anger den rumsliga faktorn.

Värde: Den rumsliga faktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


Hämtar eller anger den rumsliga styrkan.

Värde: Den rumsliga styrkan.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


Hämtar eller anger den rumsliga styrkan.

Värde: Den rumsliga styrkan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


Hämtar eller anger färgfaktorn.

Värde: Färgfaktorn.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


Hämtar eller anger färgfaktorn.

Värde: Färgfaktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


Hämtar eller anger färgstyrkan.

Värde: Färgstyrkan.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


Hämtar eller anger färgstyrkan.

Värde: Färgstyrkan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

