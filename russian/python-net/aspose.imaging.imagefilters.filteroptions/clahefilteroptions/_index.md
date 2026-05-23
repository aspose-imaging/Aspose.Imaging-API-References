---
title: "Класс ClaheFilterOptions"
type: docs
weight: 50
url: /ru/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | Инициализирует новый экземпляр класса [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            с указанными параметрами. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip_limit | float | r | Получает порог ограничения контраста.<br/>            Более высокие значения позволяют увеличить контраст; более низкие значения ограничивают усиление, чтобы предотвратить усиление шума. |
| is_grayscale | bool | r | Получает значение, указывающее, работает ли фильтр в режиме градаций серого. |
| tiles_number_horizontal | int | r | Получает количество плиток в горизонтальном направлении.<br/>            Определяет, на сколько регионов изображение делится по горизонтали для локального выравнивания контраста. |
| tiles_number_vertical | int | r | Получает количество плиток в вертикальном направлении.<br/>            Определяет, на сколько регионов изображение делится по вертикали для локального выравнивания контраста. |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

Инициализирует новый экземпляр класса [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            с указанными параметрами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| is_grayscale | bool | Указывает, должен ли фильтр работать в режиме градаций серого. |
| tiles_number_horizontal | int | Количество плиток по горизонтали. По умолчанию 8. |
| tiles_number_vertical | int | Количество плиток по вертикали. По умолчанию 8. |
| clip_limit | float | Порог ограничения контраста. По умолчанию 4.0. |

