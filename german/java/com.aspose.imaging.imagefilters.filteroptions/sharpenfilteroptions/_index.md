---
title: "SharpenFilterOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Schärfungs-Filteroptionen."
type: docs
weight: 25
url: /de/java/com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions)
```
public class SharpenFilterOptions extends GaussianBlurFilterOptions
```

Die Schärfungs-Filteroptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SharpenFilterOptions(int size, double sigma)](#SharpenFilterOptions-int-double-) | Initialisiert eine neue Instanz der [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) Klasse. |
| [SharpenFilterOptions()](#SharpenFilterOptions--) | Initialisiert eine neue Instanz der [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getKernel()](#getKernel--) | Ruft den Kernel ab. |
| [getSize()](#getSize--) | Liefert die Größe des Gauß‑Kernels. |
| [setSize(int value)](#setSize-int-) | Die Größe des Gaußschen Kernels. |
| [getSigma()](#getSigma--) | Liefert das Sigma des Gauß‑Kernels (Glättung). |
| [setSigma(double value)](#setSigma-double-) | Der gaußsche Kernel‑Sigma (Glättung). |

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

### SharpenFilterOptions(int size, double sigma) {#SharpenFilterOptions-int-double-}
```
public SharpenFilterOptions(int size, double sigma)
```


Initialisiert eine neue Instanz der [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Größe | int | Die Größe des Kerns. |
| Sigma | double | Das Sigma. |

### SharpenFilterOptions() {#SharpenFilterOptions--}
```
public SharpenFilterOptions()
```


Initialisiert eine neue Instanz der [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) Klasse.

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Ruft den Kernel ab.

**Returns:**
double[][] – der Kernel.
### getSize() {#getSize--}
```
public int getSize()
```


Liefert die Größe des gaußschen Kernels. Muss ein positiver, von Null verschiedener, ungerader Wert sein.

**Returns:**
int - die Größe des gaußschen Kernels.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Die Größe des gaußschen Kernels. Muss ein positiver, von Null verschiedener, ungerader Wert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Größe des gaußschen Kernels. |

### getSigma() {#getSigma--}
```
public double getSigma()
```


Liefert den gaußschen Kernel‑Sigma (Glättung). Muss ein positiver, von Null verschiedener Wert sein.

**Returns:**
double - der gaußsche Kernel‑Sigma (Glättung).
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


Der gaußsche Kernel‑Sigma (Glättung). Muss ein positiver, von Null verschiedener Wert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | der gaußsche Kernel‑Sigma (Glättung). |

