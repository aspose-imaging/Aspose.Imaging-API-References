---
title: "GaussianBlurFilterOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options du filtre de flou gaussien."
type: docs
weight: 19
url: /fr/java/com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions, com.aspose.internal.imagefilters.convolution.ISquareConvolutionKernel
```
public class GaussianBlurFilterOptions extends ConvolutionFilterOptions implements IGaussianBlurOptions, ISquareConvolutionKernel
```

Les options du filtre de flou gaussien.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GaussianBlurFilterOptions(int size, double sigma)](#GaussianBlurFilterOptions-int-double-) | Initialise une nouvelle instance de la classe [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions--) | Initialise une nouvelle instance de la classe [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getKernel()](#getKernel--) | Obtient la taille du noyau gaussien. |
| [getSize()](#getSize--) | Obtient la taille du noyau gaussien. |
| [setSize(int value)](#setSize-int-) | La taille du noyau gaussien. |
| [getSigma()](#getSigma--) | Obtient le sigma du noyau gaussien (lissage). |
| [setSigma(double value)](#setSigma-double-) | Le Gaussian kernel sigma (lissage). |
| [getRadius()](#getRadius--) | Obtient le rayon du Gaussian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | Le rayon du Gaussian ISquareConvolutionKernel. |

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

### GaussianBlurFilterOptions(int size, double sigma) {#GaussianBlurFilterOptions-int-double-}
```
public GaussianBlurFilterOptions(int size, double sigma)
```


Initialise une nouvelle instance de la classe [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taille | int | La taille du Gaussian kernel.. |
| sigma | double | Le sigma du noyau gaussien. |

### GaussianBlurFilterOptions() {#GaussianBlurFilterOptions--}
```
public GaussianBlurFilterOptions()
```


Initialise une nouvelle instance de la classe [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Obtient la taille du noyau gaussien.

**Returns:**
double[][] - la taille du Gaussian kernel.
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

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Obtient le rayon du Gaussian ISquareConvolutionKernel.

**Returns:**
int - le rayon du Gaussian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Le rayon du Gaussian ISquareConvolutionKernel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le rayon du Gaussian ISquareConvolutionKernel. |

