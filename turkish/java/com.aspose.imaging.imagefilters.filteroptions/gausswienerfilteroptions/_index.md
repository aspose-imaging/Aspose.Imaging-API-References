---
title: "GaussWienerFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü bulanıklaştırmayı gidermek için Gauss Wiener filtre seçenekleri."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends GaussianDeconvolutionFilterOptions
```

Görüntü bulanıklaştırmayı gidermek için Gauss Wiener filtre seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GaussWienerFilterOptions(int size, double sigma)](#GaussWienerFilterOptions-int-double-) | Yeni bir [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions) sınıf örneği başlatır. |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Yeni bir [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions) sınıf örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
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

### GaussWienerFilterOptions(int size, double sigma) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int size, double sigma)
```


Yeni bir [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions) sınıf örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Gauss çekirdeği boyutu. |
| sigma | double | Gauss çekirdeği sigma değeri. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Yeni bir [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions) sınıf örneği başlatır.

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Çekirdeği alır.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - çekirdek.
