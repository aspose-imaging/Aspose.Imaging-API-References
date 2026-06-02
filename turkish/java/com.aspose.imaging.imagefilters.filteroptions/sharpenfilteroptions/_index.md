---
title: "SharpenFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Keskinleştirme filtre seçenekleri."
type: docs
weight: 25
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions)
```
public class SharpenFilterOptions extends GaussianBlurFilterOptions
```

Keskinleştirme filtre seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SharpenFilterOptions(int size, double sigma)](#SharpenFilterOptions-int-double-) | Yeni bir [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) sınıfının bir örneğini başlatır. |
| [SharpenFilterOptions()](#SharpenFilterOptions--) | Yeni bir [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getKernel()](#getKernel--) | Çekirdeği alır. |
| [getSize()](#getSize--) | Gauss çekirdeği boyutunu alır. |
| [setSize(int value)](#setSize-int-) | Gauss çekirdeği boyutu. |
| [getSigma()](#getSigma--) | Gauss çekirdeği sigma (yumuşatma) değerini alır. |
| [setSigma(double value)](#setSigma-double-) | Gaussian çekirdek sigma (düzleştirme). |

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

### SharpenFilterOptions(int size, double sigma) {#SharpenFilterOptions-int-double-}
```
public SharpenFilterOptions(int size, double sigma)
```


Yeni bir [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Çekirdeğin boyutu. |
| sigma | double | Sigma. |

### SharpenFilterOptions() {#SharpenFilterOptions--}
```
public SharpenFilterOptions()
```


Yeni bir [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) sınıfının bir örneğini başlatır.

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Çekirdeği alır.

**Returns:**
double[][] - çekirdek.
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

