---
title: "MagicWandTool 类"
type: docs
weight: 100
url: /zh/python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | 处理已加载的像素。 |
| [select(source, settings)](#select_source_settings_2) | 基于 [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) 和源 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)，创建新的 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

处理已加载的像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 像素矩形。 |
| 像素 | int[] | 32 位 ARGB 像素。 |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | 起始像素点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | 结束像素点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

基于 [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) 和源 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)，创建新的 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 用于算法处理的光栅图像。 |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 用于创建掩模的魔棒算法设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


