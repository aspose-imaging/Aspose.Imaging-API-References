---
title: "SharpenFilterOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options du filtre d'accentuation."
type: docs
weight: 25
url: /fr/java/com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions)
```
public class SharpenFilterOptions extends GaussianBlurFilterOptions
```

Les options du filtre d'accentuation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SharpenFilterOptions(int size, double sigma)](#SharpenFilterOptions-int-double-) | Initialise une nouvelle instance de la classe [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions). |
| [SharpenFilterOptions()](#SharpenFilterOptions--) | Initialise une nouvelle instance de la classe [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getKernel()](#getKernel--) | Obtient le noyau. |
| [getSize()](#getSize--) | Obtient la taille du noyau gaussien. |
| [setSize(int value)](#setSize-int-) | La taille du noyau gaussien. |
| [getSigma()](#getSigma--) | Obtient le sigma du noyau gaussien (lissage). |
| [setSigma(double value)](#setSigma-double-) | Le Gaussian kernel sigma (lissage). |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre médian avec une taille de rectangle de 5 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
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


Initialise une nouvelle instance de la classe [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taille | int | La taille du noyau. |
| sigma | double | Le sigma. |

### SharpenFilterOptions() {#SharpenFilterOptions--}
```
public SharpenFilterOptions()
```


Initialise une nouvelle instance de la classe [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions).

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Obtient le noyau.

**Returns:**
double[][] - le noyau.
### getSize() {#getSize--}
```
public int getSize()
```


Obtient la taille du Gaussian kernel. Doit être une valeur impaire positive non nulle.

**Returns:**
int - la taille du Gaussian kernel.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


La taille du Gaussian kernel. Doit être une valeur impaire positive non nulle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la taille du Gaussian kernel. |

### getSigma() {#getSigma--}
```
public double getSigma()
```


Obtient le Gaussian kernel sigma (lissage). Doit être une valeur positive non nulle.

**Returns:**
double - le Gaussian kernel sigma (lissage).
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


Le Gaussian kernel sigma (lissage). Doit être une valeur positive non nulle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | le Gaussian kernel sigma (lissage). |

