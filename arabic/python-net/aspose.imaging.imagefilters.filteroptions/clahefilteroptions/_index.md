---
title: "فئة ClaheFilterOptions"
type: docs
weight: 50
url: /ar/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | يُهيئ نسخة جديدة من الفئة [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/> باستخدام المعلمات المحددة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| clip_limit | float | r | يحصل على عتبة تحديد التباين.<br/> القيم الأعلى تسمح بمزيد من التباين؛ القيم الأقل تحد من التعزيز لمنع تضخيم الضوضاء. |
| is_grayscale | bool | r | يحصل على قيمة تشير إلى ما إذا كان الفلتر يعمل بوضع التدرج الرمادي. |
| tiles_number_horizontal | int | r | يحصل على عدد البلاطات في الاتجاه الأفقي.<br/>            يحدد عدد المناطق التي يتم تقسيم الصورة إليها أفقيًا لتسوية التباين المحلي. |
| tiles_number_vertical | int | r | يحصل على عدد البلاطات في الاتجاه العمودي.<br/>            يحدد عدد المناطق التي يتم تقسيم الصورة إليها عموديًا لتسوية التباين المحلي. |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

يُهيئ نسخة جديدة من الفئة [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/> باستخدام المعلمات المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| is_grayscale | bool | يشير إلى ما إذا كان يجب أن يعمل المرشح في وضع التدرج الرمادي. |
| tiles_number_horizontal | int | عدد البلاطات أفقياً. القيمة الافتراضية هي 8. |
| tiles_number_vertical | int | عدد البلاطات عمودياً. القيمة الافتراضية هي 8. |
| clip_limit | float | حد عتبة تحديد التباين. القيمة الافتراضية هي 4.0. |

