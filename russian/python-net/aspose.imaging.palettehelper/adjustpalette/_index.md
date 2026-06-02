---
title: "AdjustPalette Class"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.palettehelper/adjustpalette/
---

**Summary:** Color palette adjustment class

**Module:** [aspose.imaging.palettehelper](/imaging/python-net/aspose.imaging.palettehelper/)

**Full Name:** aspose.imaging.palettehelper.AdjustPalette

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AdjustPalette()](#AdjustPalette__1) | Инициализирует новый экземпляр класса AdjustPalette |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_close_image_palette(image, entries_count, color_quantization_method, color_compare_method)](#get_close_image_palette_image_entries_count_color_quantization_method_color_compare_method_1) | Получает близкую палитру изображения. |


### Constructor: AdjustPalette() {#AdjustPalette__1}


```
 AdjustPalette() 
```

Инициализирует новый экземпляр класса AdjustPalette

### Method: get_close_image_palette(image, entries_count, color_quantization_method, color_compare_method)  [static] {#get_close_image_palette_image_entries_count_color_quantization_method_color_compare_method_1}


```
 get_close_image_palette(image, entries_count, color_quantization_method, color_compare_method) 
```

Получает близкую палитру изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение. |
| entries_count | int | Количество записей. |
| color_quantization_method | [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | Метод квантования цвета. |
| color_compare_method | [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | Метод сравнения цвета. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Оптимизировано для палитры изображения |


