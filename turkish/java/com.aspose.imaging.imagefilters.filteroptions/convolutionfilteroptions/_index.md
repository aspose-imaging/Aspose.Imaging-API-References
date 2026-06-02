---
title: "ConvolutionFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Konvolüsyon filtre seçenekleri."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

Konvolüsyon filtre seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | factor == 1 ve bias == 0 olan yeni bir [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) sınıfı örneği başlatır. |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | bias == 0 olan yeni bir [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) sınıfı örneği başlatır. |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | Yeni bir [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getKernel()](#getKernel--) | Çekirdeği alır. |
| [getFactor()](#getFactor--) | Faktörü alır. |
| [setFactor(double value)](#setFactor-double-) | Faktörü ayarlar. |
| [getBias()](#getBias--) | bias'ı alır. |
| [setBias(int value)](#setBias-int-) | bias'ı ayarlar. |
| [getIgnoreAlpha()](#getIgnoreAlpha--) | [ignore alpha] gösterip göstermediğini belirten bir değeri alır. |
| [setIgnoreAlpha(boolean value)](#setIgnoreAlpha-boolean-) | [ignore alpha] gösterip göstermediğini belirten bir değeri ayarlar. |
| [getBordersProcessing()](#getBordersProcessing--) | [borders processing] gösterip göstermediğini belirten bir değeri alır. |
| [setBordersProcessing(boolean value)](#setBordersProcessing-boolean-) | [borders processing] gösterip göstermediğini belirten bir değeri ayarlar. |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


factor == 1 ve bias == 0 olan yeni bir [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çekirdek | double[][] | X ekseni yönü için konvolüsyon çekirdeği. |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


bias == 0 olan yeni bir [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çekirdek | double[][] | X ekseni yönü için konvolüsyon çekirdeği. |
| faktör | double | Faktör. |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


Yeni bir [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çekirdek | double[][] | X ekseni yönü için konvolüsyon çekirdeği. |
| faktör | double | Faktör. |
| sapma | int | Sapma değeri. |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Çekirdeği alır.

**Returns:**
double[][] - çekirdek.
### getFactor() {#getFactor--}
```
public final double getFactor()
```


Faktörü alır.

**Returns:**
double - faktör.
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


Faktörü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | faktör. |

### getBias() {#getBias--}
```
public final int getBias()
```


bias'ı alır.

Değer: Sapma.

**Returns:**
int - sapma.
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


bias'ı ayarlar.

Değer: Sapma.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | sapma. |

### getIgnoreAlpha() {#getIgnoreAlpha--}
```
public final boolean getIgnoreAlpha()
```


[ignore alpha] gösterip göstermediğini belirten bir değeri alır.

Değer: `true` ise [ignore alpha]; aksi takdirde, `false`.

**Returns:**
boolean - [ignore alpha] gösterip göstermediğini belirten bir değer.
### setIgnoreAlpha(boolean value) {#setIgnoreAlpha-boolean-}
```
public final void setIgnoreAlpha(boolean value)
```


[ignore alpha] gösterip göstermediğini belirten bir değeri ayarlar.

Değer: `true` ise [ignore alpha]; aksi takdirde, `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | [ignore alpha] gösterip göstermediğini belirten bir değer. |

### getBordersProcessing() {#getBordersProcessing--}
```
public final boolean getBordersProcessing()
```


[borders processing] gösterip göstermediğini belirten bir değeri alır.

Değer: `true` ise [borders processing]; aksi takdirde, `false`.

**Returns:**
boolean - [borders processing] gösterip göstermediğini belirten bir değer.
### setBordersProcessing(boolean value) {#setBordersProcessing-boolean-}
```
public final void setBordersProcessing(boolean value)
```


[borders processing] gösterip göstermediğini belirten bir değeri ayarlar.

Değer: `true` ise [borders processing]; aksi takdirde, `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | [borders processing] gösterip göstermediğini belirten bir değer. |

