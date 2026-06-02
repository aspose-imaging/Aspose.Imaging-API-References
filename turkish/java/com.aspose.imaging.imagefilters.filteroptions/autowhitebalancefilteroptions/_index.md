---
title: "AutoWhiteBalanceFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Otomatik Beyaz Denge filtresi için yapılandırma seçenekleri sağlar."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

Auto White Balance filtresi için yapılandırma seçenekleri sağlar. Dijital görüntülerin görünümünü iyileştirmek için kontrast germe parametreleri ve kanal ölçeklemesinin ayarlanmasına olanak tanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | Yeni bir [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions) sınıf örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | Kontrast germe için hedef yüksek persentili alır. |
| [getTargetValue()](#getTargetValue--) | Yüksek persentil için hedef değeri alır. |
| [getMaxScale()](#getMaxScale--) | Her kanal için maksimum ölçekleme faktörünü alır. |
| [getLowPercentile()](#getLowPercentile--) | Karanlık koruma için kullanılan siyah nokta düşük persentili (varsayılan: 3). |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | Karanlık piksellerin gerilmediği düşük persentilin altındaki ofset (koruma). |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


Yeni bir [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions) sınıf örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lowPercentile | int | Karanlık koruma için kullanılan siyah nokta düşük persentili (varsayılan: 3). |
| targetHighPercentile | int | Kontrast germe için hedef yüksek persentil (varsayılan 97). |
| targetValue | int | Yüksek yüzde dilimi için hedef değer (varsayılan 255). |
| maxScale | float | Her kanal için maksimum ölçekleme faktörü (varsayılan 1.4f). |
| protectedDarkOffset | int | Karanlık piksellerin gerilmediği düşük persentilin altındaki ofset (koruma). |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


Kontrast germe için hedef yüksek yüzde dilimini alır. Hangi parlaklık yüzde diliminin hedef değere eşleneceğini belirler.

**Returns:**
int - kontrast germe için hedef yüksek yüzde dilimi.
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


Yüksek yüzde dilimi için hedef değeri alır. Bu değer, kontrast germe için beyaz referans olarak kullanılacaktır.

**Returns:**
int - yüksek yüzde dilimi için hedef değer.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Her kanal için maksimum ölçekleme faktörünü alır. Aşırı renk kaymalarını önlemek için herhangi bir kanalın yükseltmesini kısıtlar.

**Returns:**
float - her kanal için maksimum ölçekleme faktörü.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Karanlık koruma için kullanılan siyah nokta düşük persentili (varsayılan: 3).

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


Karanlık piksellerin gerilmediği düşük persentilin altındaki ofset (koruma).

**Returns:**
int
