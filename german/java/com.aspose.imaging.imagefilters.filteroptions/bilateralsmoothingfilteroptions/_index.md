---
title: "BilateralSmoothingFilterOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Bilateral Smoothing-Filteroptionen."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

Die Bilateral Smoothing-Filteroptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | Initialisiert eine neue Instanz der `BilateralSmoothingFilterOptions` Klasse. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | Initialisiert eine neue Instanz der `BilateralSmoothingFilterOptions` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Liest oder setzt die Größe des Kernels. |
| [setSize(int value)](#setSize-int-) | Liest oder setzt die Größe des Kernels. |
| [getSpatialFactor()](#getSpatialFactor--) | Liest oder setzt den räumlichen Faktor. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | Liest oder setzt den räumlichen Faktor. |
| [getSpatialPower()](#getSpatialPower--) | Liest oder setzt die räumliche Leistung. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | Liest oder setzt die räumliche Leistung. |
| [getColorFactor()](#getColorFactor--) | Liest oder setzt den Farb­faktor. |
| [setColorFactor(double value)](#setColorFactor-double-) | Liest oder setzt den Farb­faktor. |
| [getColorPower()](#getColorPower--) | Liest oder setzt die Farb­leistung. |
| [setColorPower(double value)](#setColorPower-double-) | Liest oder setzt die Farb­leistung. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Gaußschen Weichzeichner mit einem Radius von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Gauss-Wiener-Filter mit einem Radius von 5 und einem Glättungswert von 4,0 auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Bewegungs-Wiener-Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Schärfungsfilter mit einer Kernelgröße von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
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


Initialisiert eine neue Instanz der `BilateralSmoothingFilterOptions` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Größe | int | Größe des Kernels. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


Initialisiert eine neue Instanz der `BilateralSmoothingFilterOptions` Klasse.

### getSize() {#getSize--}
```
public int getSize()
```


Liest oder setzt die Größe des Kernels.

Wert: Die Größe des Kernels.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Liest oder setzt die Größe des Kernels.

Wert: Die Größe des Kernels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


Liest oder setzt den räumlichen Faktor.

Wert: Der räumliche Faktor.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


Liest oder setzt den räumlichen Faktor.

Wert: Der räumliche Faktor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


Liest oder setzt die räumliche Leistung.

Wert: Die räumliche Leistung.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


Liest oder setzt die räumliche Leistung.

Wert: Die räumliche Leistung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


Liest oder setzt den Farb­faktor.

Wert: Der Farb­faktor.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


Liest oder setzt den Farb­faktor.

Wert: Der Farb­faktor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


Liest oder setzt die Farb­leistung.

Wert: Die Farb­leistung.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


Liest oder setzt die Farb­leistung.

Wert: Die Farb­leistung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

