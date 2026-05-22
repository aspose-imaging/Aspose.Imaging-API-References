---
title: "AdaptiveWhiteStretchFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Uyarlamalı Beyaz Germe filtresini yapılandırmak için seçenekler sağlar."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

Adaptive White Stretch filtresini yapılandırmak için seçenekler sağlar. Beyaz seviyesini artırmak ve soluk metin veya düşük kontrastlı belge görüntülerinin okunabilirliğini iyileştirmek için histogram germe parametrelerinin özelleştirilmesine izin verir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | AdaptiveWhiteStretchFilter sınıfının yeni bir örneğini başlatır. |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | AdaptiveWhiteStretchFilter sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Filtrenin gri tonlamalı modda çalışıp çalışmadığını gösteren bir değeri alır. |
| [getLowPercentile()](#getLowPercentile--) | Siyah nokta hesaplaması için alt yüzde dilimini alır. |
| [getHighPercentile()](#getHighPercentile--) | Beyaz nokta hesaplaması için üst yüzde dilimini alır. |
| [getTargetWhite()](#getTargetWhite--) | Germe işleminin ulaşmayı hedeflediği beyaz hedef değerini alır. |
| [getMaxScale()](#getMaxScale--) | İzin verilen maksimum parlaklık ölçeğini alır. |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


AdaptiveWhiteStretchFilter sınıfının yeni bir örneğini başlatır.

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


AdaptiveWhiteStretchFilter sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isGrayscale | boolean | Filtrenin gri tonlamalı modda çalışıp çalışmaması gerektiğini gösterir. |
| lowPercentile | int | Siyah nokta için alt yüzde dilimi (ör. 10). |
| highPercentile | int | Beyaz nokta için üst yüzde (ör. 90). |
| targetWhite | int | Hedef beyaz değeri (ör. 240). |
|  | maxScale | float | İzin verilen maksimum parlaklık ölçeği (ör. 1.7). |

--------------------

Algoritma, histogramı beyaz yüzde `targetWhite` değerine yaklaşacak şekilde genişletir, ancak aşırı parlaklığı önlemek için `maxScale` değerini aşmaz. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Filtrenin gri tonlamalı modda çalışıp çalışmadığını gösteren bir değeri alır.

**Returns:**
boolean - filtrenin gri tonlamalı modda çalışıp çalışmadığını gösteren bir değer.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Siyah nokta hesaplaması için alt yüzdeyi alır. Bu yüzde altındaki piksel değerleri, genişletme sırasında siyah olarak kabul edilir.

**Returns:**
int - siyah nokta hesaplaması için alt yüzde.
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


Beyaz nokta hesaplaması için üst yüzdeyi alır. Bu yüzde üzerindeki piksel değerleri, genişletme sırasında beyaz olarak kabul edilir.

**Returns:**
int - beyaz nokta hesaplaması için üst yüzde.
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


Germe işleminin ulaşmayı hedeflediği beyaz hedef değerini alır.

**Returns:**
int - genişletmenin ulaşmayı hedeflediği hedef beyaz değeri.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


İzin verilen maksimum parlaklık ölçeğini alır. Gerçek genişletme, aşırı parlaklığı önlemek için bu faktörü aşmaz.

**Returns:**
float - izin verilen maksimum parlaklık ölçeği.
