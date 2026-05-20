---
title: "GaussianBlurFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni del filtro di sfocatura gaussiana."
type: docs
weight: 19
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions, com.aspose.internal.imagefilters.convolution.ISquareConvolutionKernel
```
public class GaussianBlurFilterOptions extends ConvolutionFilterOptions implements IGaussianBlurOptions, ISquareConvolutionKernel
```

Le opzioni del filtro di sfocatura gaussiana.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GaussianBlurFilterOptions(int size, double sigma)](#GaussianBlurFilterOptions-int-double-) | Inizializza una nuova istanza della classe [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions--) | Inizializza una nuova istanza della classe [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getKernel()](#getKernel--) | Ottiene la dimensione del kernel Gaussian. |
| [getSize()](#getSize--) | Ottiene la dimensione del kernel Gaussian. |
| [setSize(int value)](#setSize-int-) | La dimensione del kernel gaussiano. |
| [getSigma()](#getSigma--) | Ottiene la sigma del kernel Gaussian (smussatura). |
| [setSigma(double value)](#setSigma-double-) | Il Gaussian kernel sigma (smussatura). |
| [getRadius()](#getRadius--) | Ottiene il raggio di Gaussian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | Il raggio di Gaussian ISquareConvolutionKernel. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro mediano con una dimensione del rettangolo di 5 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro di levigatura bilaterale con una dimensione del kernel di 5 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90.0 gradi all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro di nitidezza con una dimensione del kernel di 5 e un valore sigma di 4.0 all'intera immagine.
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


Inizializza una nuova istanza della classe [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La dimensione del kernel Gaussian.. |
| sigma | double | Il sigma del kernel gaussiano. |

### GaussianBlurFilterOptions() {#GaussianBlurFilterOptions--}
```
public GaussianBlurFilterOptions()
```


Inizializza una nuova istanza della classe [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions).

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Ottiene la dimensione del kernel Gaussian.

**Returns:**
double[][] - la dimensione del kernel Gaussian.
### getSize() {#getSize--}
```
public int getSize()
```


Ottiene la dimensione del kernel Gaussian. Deve essere un valore dispari positivo diverso da zero.

**Returns:**
int - la dimensione del kernel Gaussian.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


La dimensione del kernel Gaussian. Deve essere un valore dispari positivo diverso da zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la dimensione del kernel Gaussian. |

### getSigma() {#getSigma--}
```
public double getSigma()
```


Ottiene il sigma del kernel Gaussian (smussatura). Deve essere un valore positivo diverso da zero.

**Returns:**
double - il sigma del kernel Gaussian (smussatura).
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


Il sigma del kernel Gaussian (smussatura). Deve essere un valore positivo diverso da zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | il sigma del kernel Gaussian (smussatura). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Ottiene il raggio di Gaussian ISquareConvolutionKernel.

**Returns:**
int - il raggio di Gaussian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Il raggio di Gaussian ISquareConvolutionKernel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il raggio di Gaussian ISquareConvolutionKernel. |

