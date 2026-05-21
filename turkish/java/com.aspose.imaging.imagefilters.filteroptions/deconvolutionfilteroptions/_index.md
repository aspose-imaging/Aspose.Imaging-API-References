---
title: "DeconvolutionFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Deconvolution Filter Options soyut sınıfı"
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IComplexConvolutionKernel
```
public class DeconvolutionFilterOptions extends FilterOptionsBase implements IComplexConvolutionKernel
```

Dekonvolüsyon Filtre Seçenekleri, soyut sınıf
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DeconvolutionFilterOptions(double[][] kernel)](#DeconvolutionFilterOptions-double-----) | Yeni bir [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions) sınıf örneği başlatır. |
| [DeconvolutionFilterOptions(Complex[][] kernel)](#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----) | Yeni bir [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions) sınıf örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getKernel()](#getKernel--) | Çekirdeği alır. |
| [getSnr()](#getSnr--) | SNR (signal-to-noise ratio) önerilen aralığını alır veya ayarlar 0.002 - 0.009, varsayılan değer = 0.007 |
| [setSnr(double value)](#setSnr-double-) | SNR (signal-to-noise ratio) önerilen aralığını alır veya ayarlar 0.002 - 0.009, varsayılan değer = 0.007 |
| [getBrightness()](#getBrightness--) | Parlaklığı alır veya ayarlar. |
| [setBrightness(double value)](#setBrightness-double-) | Parlaklığı alır veya ayarlar. |
| [getGrayscale()](#getGrayscale--) | `DeconvolutionFilterOptions` öğesinin gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | `DeconvolutionFilterOptions` öğesinin gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isPartialLoaded()](#isPartialLoaded--) | Bu örneğin kısmen yüklendiğini gösteren bir değeri alır. |
### DeconvolutionFilterOptions(double[][] kernel) {#DeconvolutionFilterOptions-double-----}
```
public DeconvolutionFilterOptions(double[][] kernel)
```


Yeni bir [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions) sınıf örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çekirdek | double[][] | Çekirdek. |

### DeconvolutionFilterOptions(Complex[][] kernel) {#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----}
```
public DeconvolutionFilterOptions(Complex[][] kernel)
```


Yeni bir [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions) sınıf örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kernel | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Çekirdek. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Çekirdeği alır.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - çekirdek.
### getSnr() {#getSnr--}
```
public double getSnr()
```


SNR (signal-to-noise ratio) önerilen aralığını alır veya ayarlar 0.002 - 0.009, varsayılan değer = 0.007

Değer: SNR.

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


SNR (signal-to-noise ratio) önerilen aralığını alır veya ayarlar 0.002 - 0.009, varsayılan değer = 0.007

Değer: SNR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


Parlaklığı alır veya ayarlar. önerilen aralık 1 - 1.5 varsayılan değer = 1.15

Değer: Parlaklık.

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


Parlaklığı alır veya ayarlar. önerilen aralık 1 - 1.5 varsayılan değer = 1.15

Değer: Parlaklık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


Bu `DeconvolutionFilterOptions`'ın gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar. Gri tonlama modu veya RGB modunu döndürür.

Değer: `true` ise gri tonlamalı; aksi takdirde `false`.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


Bu `DeconvolutionFilterOptions`'ın gri tonlamalı olup olmadığını gösteren bir değeri alır veya ayarlar. Gri tonlama modu veya RGB modunu döndürür.

Değer: `true` ise gri tonlamalı; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


Bu örneğin kısmen yüklendiğini gösteren bir değeri alır.

Değer: `true` ise bu örnek kısmen yüklü; aksi takdirde `false`.

**Returns:**
boolean
