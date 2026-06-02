---
title: "MotionWienerFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Hareket bulanıklaştırma giderme filtre seçenekleri."
type: docs
weight: 23
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends GaussianDeconvolutionFilterOptions
```

Hareket bulanıklaştırma giderme filtre seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MotionWienerFilterOptions(int size, double sigma, double angle)](#MotionWienerFilterOptions-int-double-double-) | Yeni bir [MotionWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAngle()](#getAngle--) | Açıyı derece cinsinden alır. |
| [setAngle(double value)](#setAngle-double-) | Açıyı derece cinsinden ayarlar. |
| [getKernel()](#getKernel--) | Çekirdeği alır. |

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

### MotionWienerFilterOptions(int size, double sigma, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int size, double sigma, double angle)
```


Yeni bir [MotionWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Gauss çekirdeği boyutu. |
| sigma | double | Gauss çekirdeği sigma değeri. |
| angle | double | Derece cinsinden açı. |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Açıyı derece cinsinden alır.

Değer: Açı.

**Returns:**
double - derece cinsinden açı.
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Açıyı derece cinsinden ayarlar.

Değer: Açı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | derece cinsinden açı. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Çekirdeği alır.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - çekirdek.
