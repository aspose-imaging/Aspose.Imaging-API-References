---
title: "AdjustPalette 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.palettehelper/adjustpalette/
---

**Summary:** Color palette adjustment class

**Module:** [aspose.imaging.palettehelper](/imaging/python-net/aspose.imaging.palettehelper/)

**Full Name:** aspose.imaging.palettehelper.AdjustPalette

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [AdjustPalette()](#AdjustPalette__1) | 初始化 AdjustPalette 类的新实例 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_close_image_palette(image, entries_count, color_quantization_method, color_compare_method)](#get_close_image_palette_image_entries_count_color_quantization_method_color_compare_method_1) | 获取接近的图像调色板。 |


### Constructor: AdjustPalette() {#AdjustPalette__1}


```
 AdjustPalette() 
```

初始化 AdjustPalette 类的新实例

### Method: get_close_image_palette(image, entries_count, color_quantization_method, color_compare_method)  [static] {#get_close_image_palette_image_entries_count_color_quantization_method_color_compare_method_1}


```
 get_close_image_palette(image, entries_count, color_quantization_method, color_compare_method) 
```

获取接近的图像调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 图像。 |
| entries_count | int | 条目计数。 |
| color_quantization_method | [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | 颜色量化方法。 |
| color_compare_method | [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | 颜色比较方法。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 针对图像调色板进行优化 |


