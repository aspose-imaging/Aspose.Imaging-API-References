---
title: "Класс AdaptiveWhiteStretchFilterOptions"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | Инициализирует новый экземпляр класса [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| high_percentile | int | r | Получает верхний процентиль для расчёта белой точки.<br/>            Пиксельные значения выше этого процентиля считаются белыми при растягивании. |
| is_grayscale | bool | r | Получает значение, указывающее, работает ли фильтр в режиме градаций серого. |
| low_percentile | int | r | Получает нижний процентиль для расчёта чёрной точки.<br/>            Пиксельные значения ниже этого процентиля считаются чёрными при растягивании. |
| max_scale | float | r | Получает максимальный допустимый масштаб яркости.<br/>            Фактическое растягивание не превысит этот коэффициент, чтобы избежать переосвещения. |
| target_white | int | r | Получает целевое белое значение, к которому стремится растягивание. |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

Инициализирует новый экземпляр класса [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| is_grayscale | bool | Указывает, должен ли фильтр работать в режиме градаций серого. |
| low_percentile | int | Нижний процентиль для чёрной точки (например, 10). |
| high_percentile | int | Верхний процентиль для белой точки (например, 90). |
| target_white | int | Целевое белое значение (например, 240). |
| max_scale | float | Максимальный допустимый масштаб яркости (например, 1.7). |

