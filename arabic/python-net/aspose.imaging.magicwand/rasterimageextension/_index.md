---
title: "فئة RasterImageExtension"
type: docs
weight: 110
url: /ar/python-net/aspose.imaging.magicwand/rasterimageextension/
---

**Summary:** Class with masks extension methods for [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.RasterImageExtension

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [apply_mask(image, mask)](#apply_mask_image_mask_1) | يطبق [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) على [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [select_mask(source, settings)](#select_mask_source_settings_2) | ينشئ [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) مع اختيار البكسلات ذات الألوان المشابهة للون نقطة المرجع بناءً على [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/). |


### Method: apply_mask(image, mask)  [static] {#apply_mask_image_mask_1}


```
 apply_mask(image, mask) 
```

يطبق [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) على [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة التي سيُطبق عليها القناع. |
| mask | [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) | القناع الذي سيُطبق. |

### Method: select_mask(source, settings)  [static] {#select_mask_source_settings_2}


```
 select_mask(source, settings) 
```

ينشئ [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) مع اختيار البكسلات ذات الألوان المشابهة للون نقطة المرجع بناءً على [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة نقطية لتعمل الخوارزمية عليها. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | الإعدادات المستخدمة لمعالجة الاختيار، وتضم نقطة المرجع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


