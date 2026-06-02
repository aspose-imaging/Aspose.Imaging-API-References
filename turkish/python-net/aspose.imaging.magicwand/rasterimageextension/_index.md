---
title: "RasterImageExtension Sınıfı"
type: docs
weight: 110
url: /tr/python-net/aspose.imaging.magicwand/rasterimageextension/
---

**Summary:** Class with masks extension methods for [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.RasterImageExtension

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [apply_mask(image, mask)](#apply_mask_image_mask_1) | [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) öğesini [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) üzerine uygular. |
| [select_mask(source, settings)](#select_mask_source_settings_2) | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) temelinde, referans noktasının rengine benzer renklere sahip piksellerin seçimiyle bir [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) oluşturur. |


### Method: apply_mask(image, mask)  [static] {#apply_mask_image_mask_1}


```
 apply_mask(image, mask) 
```

[IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) öğesini [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) üzerine uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Maskenin uygulanacağı görüntü. |
| mask | [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) | Uygulanacak maske. |

### Method: select_mask(source, settings)  [static] {#select_mask_source_settings_2}


```
 select_mask(source, settings) 
```

[MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) temelinde, referans noktasının rengine benzer renklere sahip piksellerin seçimiyle bir [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Algoritmanın çalışacağı raster görüntü. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Seçimi işlemek için kullanılan ayarlar, referans noktasını içerir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


