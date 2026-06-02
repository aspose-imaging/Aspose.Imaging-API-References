---
title: "RasterImageExtension 类"
type: docs
weight: 110
url: /zh/python-net/aspose.imaging.magicwand/rasterimageextension/
---

**Summary:** Class with masks extension methods for [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.RasterImageExtension

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [apply_mask(image, mask)](#apply_mask_image_mask_1) | 将 [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemmask/) 应用于 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)。 |
| [select_mask(source, settings)](#select_mask_source_settings_2) | 基于 [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/)，创建一个 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)，用于选择颜色与参考点颜色相似的像素。 |


### Method: apply_mask(image, mask)  [static] {#apply_mask_image_mask_1}


```
 apply_mask(image, mask) 
```

将 [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemmask/) 应用于 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 用于应用遮罩的图像。 |
| mask | [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) | 要应用的掩码。 |

### Method: select_mask(source, settings)  [static] {#select_mask_source_settings_2}


```
 select_mask(source, settings) 
```

基于 [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/)，创建一个 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)，用于选择颜色与参考点颜色相似的像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 用于算法处理的光栅图像。 |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 用于处理选择的设置，包括参考点。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


