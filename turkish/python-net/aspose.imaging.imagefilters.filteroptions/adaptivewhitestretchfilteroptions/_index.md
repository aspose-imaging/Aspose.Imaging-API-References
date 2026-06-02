---
title: "AdaptiveWhiteStretchFilterOptions Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | Yeni bir [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| high_percentile | int | r | Beyaz nokta hesaplaması için üst persentili alır.<br/>            Bu persentilin üzerindeki piksel değerleri germe sırasında beyaz olarak kabul edilir. |
| is_grayscale | bool | r | Filtrenin gri tonlamalı modda çalışıp çalışmadığını gösteren bir değer alır. |
| low_percentile | int | r | Siyah nokta hesaplaması için alt persentili alır.<br/>            Bu persentilin altındaki piksel değerleri germe sırasında siyah olarak kabul edilir. |
| max_scale | float | r | İzin verilen maksimum parlaklık ölçeğini alır.<br/>            Gerçek germe bu faktörü aşmayacak, aşırı aydınlatmadan kaçınılacaktır. |
| target_white | int | r | Germe işleminin ulaşmayı hedeflediği beyaz değeri alır. |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

Yeni bir [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| is_grayscale | bool | Filtre'nin gri tonlamalı modda çalışıp çalışmayacağını gösterir. |
| low_percentile | int | Siyah nokta için alt persentil (ör. 10). |
| high_percentile | int | Beyaz nokta için üst persentil (ör. 90). |
| target_white | int | Hedef beyaz değer (ör. 240). |
| max_scale | float | İzin verilen maksimum parlaklık ölçeği (ör. 1.7). |

