---
title: "MedianFilterOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Medianfilter"
type: docs
weight: 22
url: /de/java/com.aspose.imaging.imagefilters.filteroptions/medianfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class MedianFilterOptions extends FilterOptionsBase
```

Medianfilter
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MedianFilterOptions(int size)](#MedianFilterOptions-int-) | Initialisiert eine neue Instanz der Klasse `MedianFilterOptions`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Liest oder setzt die Größe. |
| [setSize(int value)](#setSize-int-) | Liest oder setzt die Größe. |

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

### MedianFilterOptions(int size) {#MedianFilterOptions-int-}
```
public MedianFilterOptions(int size)
```


Initialisiert eine neue Instanz der Klasse `MedianFilterOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Größe | int | Die Größe des Filterrechtecks. |

### getSize() {#getSize--}
```
public int getSize()
```


Liest oder setzt die Größe.

Wert: Die Größe des Filterrechtecks.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Liest oder setzt die Größe.

Wert: Die Größe des Filterrechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

