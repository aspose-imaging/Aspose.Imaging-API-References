---
title: "فئة AutoWhiteBalanceFilterOptions"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | ينشئ مثيلاً جديداً من الفئة [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| low_percentile | int | r | النسبة المئوية المنخفضة لنقطة الأسود، تُستخدم لحماية الظلال (الافتراضي: 3). |
| max_scale | float | r | يحصل على عامل التحجيم الأقصى لكل قناة.<br/>            يحد من تضخيم أي قناة لتجنب التحولات اللونية المفرطة. |
| protected_dark_offset | int | r | الإزاحة من النسبة المئوية المنخفضة التي أدناه لا يتم تمديد البكسلات الداكنة (حماية). |
| target_high_percentile | int | r | يحصل على النسبة المئوية العليا المستهدفة لتوسيع التباين.<br/>            يحدد أي نسبة إضاءة سيتم ربطها بالقيمة المستهدفة. |
| target_value | int | r | يحصل على القيمة المستهدفة للنسبة المئوية العليا.<br/>            ستُستخدم هذه القيمة كمرجع أبيض لتوسيع التباين. |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

ينشئ مثيلاً جديداً من الفئة [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| low_percentile | int | النسبة المئوية المنخفضة لنقطة الأسود، تُستخدم لحماية الظلال (الافتراضي: 3). |
| target_high_percentile | int | النسبة المئوية العليا المستهدفة لتوسيع التباين (القيمة الافتراضية 97). |
| target_value | int | القيمة المستهدفة للنسبة المئوية العليا (القيمة الافتراضية 255). |
| max_scale | float | عامل التحجيم الأقصى لكل قناة (القيمة الافتراضية 1.4f). |
| protected_dark_offset | int | الإزاحة من النسبة المئوية المنخفضة التي أدناه لا يتم تمديد البكسلات الداكنة (حماية). |

