---
title: "BilateralSmoothingFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "İkili Düzleştirme Filtre Seçenekleri."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

İkili Düzleştirme Filtre Seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | Yeni bir `BilateralSmoothingFilterOptions` sınıfının örneğini başlatır. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | Yeni bir `BilateralSmoothingFilterOptions` sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Çekirdeğin boyutunu alır veya ayarlar. |
| [setSize(int value)](#setSize-int-) | Çekirdeğin boyutunu alır veya ayarlar. |
| [getSpatialFactor()](#getSpatialFactor--) | Uzamsal faktörü alır veya ayarlar. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | Uzamsal faktörü alır veya ayarlar. |
| [getSpatialPower()](#getSpatialPower--) | Uzamsal gücü alır veya ayarlar. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | Uzamsal gücü alır veya ayarlar. |
| [getColorFactor()](#getColorFactor--) | Renk faktörünü alır veya ayarlar. |
| [setColorFactor(double value)](#setColorFactor-double-) | Renk faktörünü alır veya ayarlar. |
| [getColorPower()](#getColorPower--) | Renk gücünü alır veya ayarlar. |
| [setColorPower(double value)](#setColorPower-double-) | Renk gücünü alır veya ayarlar. |

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

### BilateralSmoothingFilterOptions(int size) {#BilateralSmoothingFilterOptions-int-}
```
public BilateralSmoothingFilterOptions(int size)
```


Yeni bir `BilateralSmoothingFilterOptions` sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Çekirdeğin boyutu. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


Yeni bir `BilateralSmoothingFilterOptions` sınıfının örneğini başlatır.

### getSize() {#getSize--}
```
public int getSize()
```


Çekirdeğin boyutunu alır veya ayarlar.

Değer: Çekirdeğin boyutu.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Çekirdeğin boyutunu alır veya ayarlar.

Değer: Çekirdeğin boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


Uzamsal faktörü alır veya ayarlar.

Değer: Uzamsal faktör.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


Uzamsal faktörü alır veya ayarlar.

Değer: Uzamsal faktör.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


Uzamsal gücü alır veya ayarlar.

Değer: Uzamsal güç.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


Uzamsal gücü alır veya ayarlar.

Değer: Uzamsal güç.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


Renk faktörünü alır veya ayarlar.

Değer: Renk faktörü.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


Renk faktörünü alır veya ayarlar.

Değer: Renk faktörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


Renk gücünü alır veya ayarlar.

Değer: Renk gücü.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


Renk gücünü alır veya ayarlar.

Değer: Renk gücü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

