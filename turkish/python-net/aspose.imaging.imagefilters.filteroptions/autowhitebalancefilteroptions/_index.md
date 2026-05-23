---
title: "AutoWhiteBalanceFilterOptions Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | Yeni bir [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| low_percentile | int | r | Siyah nokta için düşük yüzde dilimi, karanlık koruması için kullanılır (varsayılan: 3). |
| max_scale | float | r | Her kanal için maksimum ölçekleme faktörünü alır.<br/>            Herhangi bir kanalın aşırı renk kaymalarını önlemek için amplifikasyonunu sınırlar. |
| protected_dark_offset | int | r | Düşük yüzde diliminden aşağı, karanlık piksellerin gerilmediği ofset (koruma). |
| target_high_percentile | int | r | Kontrast germe için hedef yüksek persentili alır.<br/>            Hangi parlaklık persentilinin hedef değere eşleneceğini belirler. |
| target_value | int | r | Yüksek persentil için hedef değeri alır.<br/>            Bu değer, kontrast germe için beyaz referans olarak kullanılacaktır. |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

Yeni bir [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| low_percentile | int | Siyah nokta için düşük yüzde dilimi, karanlık koruması için kullanılır (varsayılan: 3). |
| target_high_percentile | int | Kontrast germe için hedef yüksek persentil (varsayılan 97). |
| target_value | int | Yüksek persentil için hedef değer (varsayılan 255). |
| max_scale | float | Her kanal için maksimum ölçekleme faktörü (varsayılan 1.4f). |
| protected_dark_offset | int | Düşük yüzde diliminden aşağı, karanlık piksellerin gerilmediği ofset (koruma). |

