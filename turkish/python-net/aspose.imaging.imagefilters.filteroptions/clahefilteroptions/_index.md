---
title: "ClaheFilterOptions Sınıfı"
type: docs
weight: 50
url: /tr/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | Belirtilen parametrelerle [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/) sınıfının yeni bir örneğini başlatır.<br/>             |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| clip_limit | float | r | Kontrast sınırlama eşiğini alır.<br/>            Daha yüksek değerler daha fazla kontrast sağlar; daha düşük değerler gürültü yükselmesini önlemek için iyileştirmeyi sınırlar. |
| is_grayscale | bool | r | Filtrenin gri tonlamalı modda çalışıp çalışmadığını gösteren bir değer alır. |
| tiles_number_horizontal | int | r | Yatay yönde döşemelerin sayısını alır.<br/>            Görüntünün yerel kontrast eşitlemesi için yatay olarak kaç bölgeye ayrıldığını belirler. |
| tiles_number_vertical | int | r | Dikey yönde döşemelerin sayısını alır.<br/>            Görüntünün yerel kontrast eşitlemesi için dikey olarak kaç bölgeye ayrıldığını belirler. |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

Belirtilen parametrelerle [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/) sınıfının yeni bir örneğini başlatır.<br/>            

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| is_grayscale | bool | Filtre'nin gri tonlamalı modda çalışıp çalışmayacağını gösterir. |
| tiles_number_horizontal | int | Yatayda döşeme sayısı. Varsayılan değer 8. |
| tiles_number_vertical | int | Dikeyde döşeme sayısı. Varsayılan değer 8. |
| clip_limit | float | Kontrast sınırlama eşiği. Varsayılan değer 4.0. |

