---
title: "AutoWhiteBalanceFilterOptions Класс"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | Инициализирует новый экземпляр класса [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| low_percentile | int | r | Низкий перцентиль для черной точки, используемый для защиты от темных областей (по умолчанию: 3). |
| max_scale | float | r | Получает максимальный коэффициент масштабирования для каждого канала.<br/>            Ограничивает усиление любого канала, чтобы избежать чрезмерных цветовых сдвигов. |
| protected_dark_offset | int | r | Смещение от низкого перцентиля, ниже которого темные пиксели не растягиваются (защита). |
| target_high_percentile | int | r | Получает целевой высокий процентиль для растягивания контраста.<br/>            Определяет, какой процентиль яркости будет сопоставлен с целевым значением. |
| target_value | int | r | Получает целевое значение для высокого процентиля.<br/>            Это значение будет использоваться как белая ссылка для растягивания контраста. |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

Инициализирует новый экземпляр класса [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| low_percentile | int | Низкий перцентиль для черной точки, используемый для защиты от темных областей (по умолчанию: 3). |
| target_high_percentile | int | Целевой высокий процентиль для растягивания контраста (по умолчанию 97). |
| target_value | int | Целевое значение для высокого процентиля (по умолчанию 255). |
| max_scale | float | Максимальный коэффициент масштабирования для каждого канала (по умолчанию 1.4f). |
| protected_dark_offset | int | Смещение от низкого перцентиля, ниже которого темные пиксели не растягиваются (защита). |

