---
title: "GaussianBlurFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gaussian bulanıklaştırma filtre seçenekleri."
type: docs
weight: 19
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions, com.aspose.internal.imagefilters.convolution.ISquareConvolutionKernel
```
public class GaussianBlurFilterOptions extends ConvolutionFilterOptions implements IGaussianBlurOptions, ISquareConvolutionKernel
```

Gaussian bulanıklaştırma filtre seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GaussianBlurFilterOptions(int size, double sigma)](#GaussianBlurFilterOptions-int-double-) | Yeni bir [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) sınıfı örneği başlatır. |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions--) | Yeni bir [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getKernel()](#getKernel--) | Gauss çekirdeği boyutunu alır. |
| [getSize()](#getSize--) | Gauss çekirdeği boyutunu alır. |
| [setSize(int value)](#setSize-int-) | Gauss çekirdeği boyutu. |
| [getSigma()](#getSigma--) | Gauss çekirdeği sigma (yumuşatma) değerini alır. |
| [setSigma(double value)](#setSigma-double-) | Gaussian çekirdek sigma (düzleştirme). |
| [getRadius()](#getRadius--) | Gaussian ISquareConvolutionKernel yarıçapını alır. |
| [setRadius(int value)](#setRadius-int-) | Gaussian ISquareConvolutionKernel yarıçapı. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, dikdörtgen boyutu 5 olan bir medyan filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 olan çift taraflı yumuşatma filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, yarıçapı 5 ve sigma değeri 4.0 olan bir Gaussian bulanıklaştırma filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, yarıçapı 5 ve pürüzsüzlük değeri 4.0 olan bir Gauss-Wiener filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, uzunluğu 5, pürüzsüzlük değeri 4.0 ve açısı 90.0 derece olan bir hareket Wiener filtresi uygula.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 ve sigma değeri 4.0 olan bir keskinleştirme filtresi uygula.
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


Yeni bir [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Gaussian çekirdek boyutu.. |
| sigma | double | Gauss çekirdeği sigma değeri. |

### GaussianBlurFilterOptions() {#GaussianBlurFilterOptions--}
```
public GaussianBlurFilterOptions()
```


Yeni bir [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) sınıfı örneği başlatır.

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Gauss çekirdeği boyutunu alır.

**Returns:**
double[][] - Gaussian çekirdek boyutu.
### getSize() {#getSize--}
```
public int getSize()
```


Gaussian çekirdek boyutunu alır. Pozitif, sıfırdan farklı ve tek bir değer olmalıdır.

**Returns:**
int - Gaussian çekirdek boyutu.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Gaussian çekirdek boyutu. Pozitif, sıfırdan farklı ve tek bir değer olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Gaussian çekirdek boyutu. |

### getSigma() {#getSigma--}
```
public double getSigma()
```


Gaussian çekirdek sigma (düzleştirme) alır. Pozitif, sıfırdan farklı bir değer olmalıdır.

**Returns:**
double - Gaussian çekirdek sigma (düzleştirme).
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


Gaussian çekirdek sigma (düzleştirme). Pozitif, sıfırdan farklı bir değer olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Gaussian çekirdek sigma (düzleştirme). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Gaussian ISquareConvolutionKernel yarıçapını alır.

**Returns:**
int - Gaussian ISquareConvolutionKernel yarıçapı.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Gaussian ISquareConvolutionKernel yarıçapı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Gaussian ISquareConvolutionKernel yarıçapı. |

