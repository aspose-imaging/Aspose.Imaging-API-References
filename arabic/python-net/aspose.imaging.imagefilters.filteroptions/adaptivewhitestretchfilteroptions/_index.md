---
title: "فئة AdaptiveWhiteStretchFilterOptions"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | ينشئ مثيلاً جديداً للفئة [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| high_percentile | int | r | يحصل على النسبة المئوية العليا لحساب نقطة الأبيض.<br/>            تُعتبر قيم البكسل التي فوق هذه النسبة بيضاء أثناء التوسيع. |
| is_grayscale | bool | r | يحصل على قيمة تشير إلى ما إذا كان الفلتر يعمل بوضع التدرج الرمادي. |
| low_percentile | int | r | يحصل على النسبة المئوية السفلى لحساب نقطة الأسود.<br/>            تُعتبر قيم البكسل التي تحت هذه النسبة سوداء أثناء التوسيع. |
| max_scale | float | r | يحصل على أقصى مقياس سطوع مسموح به.<br/>            لن يتجاوز التوسيع الفعلي هذا العامل لتجنب الإضاءة الزائدة. |
| target_white | int | r | يحصل على قيمة الأبيض المستهدفة التي يسعى التوسيع لتحقيقها. |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

ينشئ مثيلاً جديداً للفئة [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| is_grayscale | bool | يشير إلى ما إذا كان يجب أن يعمل المرشح في وضع التدرج الرمادي. |
| low_percentile | int | النسبة المئوية السفلى لنقطة الأسود (مثال: 10). |
| high_percentile | int | النسبة المئوية العليا لنقطة الأبيض (مثال: 90). |
| target_white | int | قيمة الأبيض المستهدفة (مثال: 240). |
| max_scale | float | مقياس السطوع المسموح به كحد أقصى (مثال: 1.7). |

