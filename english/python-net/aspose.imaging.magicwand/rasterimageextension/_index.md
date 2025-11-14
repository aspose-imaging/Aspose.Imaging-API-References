---
title: RasterImageExtension Class
type: docs
weight: 110
url: /python-net/aspose.imaging.magicwand/rasterimageextension/
---

**Summary:** Class with masks extension methods for [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.RasterImageExtension

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply_mask(image, mask)](#apply_mask_image_mask_1) | Applies [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) to the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [select_mask(source, settings)](#select_mask_source_settings_2) | Creates a [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) with selection of pixels with colors similar to the color of the reference point based on [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/). |


### Method: apply_mask(image, mask)  [static] {#apply_mask_image_mask_1}


```
 apply_mask(image, mask) 
```

Applies [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) to the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image to apply mask to. |
| mask | [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) | The mask to be applied. |

### Method: select_mask(source, settings)  [static] {#select_mask_source_settings_2}


```
 select_mask(source, settings) 
```

Creates a [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) with selection of pixels with colors similar to the color of the reference point based on [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster image for the algorithm to work over. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | The settings used to process the selection, includes the reference point. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


