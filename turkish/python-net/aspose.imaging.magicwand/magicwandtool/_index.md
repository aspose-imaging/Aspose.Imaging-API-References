---
title: "MagicWandTool Sınıfı"
type: docs
weight: 100
url: /tr/python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Yüklenen pikselleri işler. |
| [select(source, settings)](#select_source_settings_2) | Yeni bir [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) oluşturur, [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) temel alarak ve kaynak [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) kullanarak. |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Yüklenen pikselleri işler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel dikdörtgeni. |
| piksel | int[] | 32 bit ARGB pikselleri. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Başlangıç piksel noktası. (left,top) eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Bitiş piksel noktası. (right,bottom) eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

Yeni bir [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) oluşturur, [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) temel alarak ve kaynak [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) kullanarak.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Algoritmanın çalışacağı raster görüntü. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Maske oluşturmakta kullanılan sihirli değnek algoritması ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


