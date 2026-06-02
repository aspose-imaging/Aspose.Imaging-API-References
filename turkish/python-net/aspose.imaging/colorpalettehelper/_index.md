---
title: "ColorPaletteHelper Sınıfı"
type: docs
weight: 1200
url: /tr/python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | 4 bit renk paletini oluşturur. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | 4 bit gri tonlamalı paleti oluşturur. |
| [create_8_bit()](#create_8_bit__3) | 8 bit renk paletini oluşturur. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | 8 bit gri tonlamalı paleti oluşturur. |
| [create_grayscale(bits)](#create_grayscale_bits_5) | Belirtilen bit sayısının gri tonlamalı paletini alır. İzin verilen bit değerleri 1, 2, 4, 8'dir. |
| [create_monochrome()](#create_monochrome__6) | Yalnızca 2 renk içeren bir monokrom renk paleti oluşturur. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet, daha iyi indeksli görüntü kalitesi için optimize edilecek veya PaletteMiningMethod.UseCurrentPalette kullanıldığında "AS IS" alınacaktır. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet, daha iyi indeksli görüntü kalitesi için optimize edilecek veya PaletteMiningMethod.UseCurrentPalette kullanıldığında "AS IS" alınacaktır. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır. |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | İlk görüntü renk değerlerinin üst bitlerinden oluşan 256 renkli paleti al. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | Tekdüzen 256 renkli paleti al. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | Belirtilen paletin şeffaf renkleri olup olmadığını belirler. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

4 bit renk paletini oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 4 bitlik renk paleti. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

4 bit gri tonlamalı paleti oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| min_is_white | bool | eğer <c>true</c> olarak ayarlanırsa palet beyaz renkle başlar, aksi takdirde siyah renkle başlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 4 bitlik gri tonlamalı palet. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

8 bit renk paletini oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 8 bitlik renk paleti. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

8 bit gri tonlamalı paleti oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| min_is_white | bool | eğer <c>true</c> olarak ayarlanırsa palet beyaz renkle başlar, aksi takdirde siyah renkle başlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 8 bitlik gri tonlamalı palet. |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

Belirtilen bit sayısının gri tonlamalı paletini alır. İzin verilen bit değerleri 1, 2, 4, 8'dir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bitler | int | Bit sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Gri tonlamalı palet. |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

Yalnızca 2 renk içeren bir monokrom renk paleti oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Monokrom görüntüler için renk paleti. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster görüntü. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları. |
| entries_count | int | İstenen giriş sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | En sık kullanılan renklerle _image_ öğesinden başlayan ve _entriesCount_ giriş içeren renk paleti. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster görüntü. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları. |
| entries_count | int | İstenen giriş sayısı. |
| use_image_palette | bool | Ayarlanırsa, mevcutsa kendi görüntü paletini kullanacaktır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | En sık kullanılan renklerle _image_ öğesinden başlayan ve _entriesCount_ giriş içeren renk paleti. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster görüntü. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları. |
| entries_count | int | İstenen giriş sayısı. |
| use_image_palette | bool | Ayarlanırsa, mevcutsa kendi görüntü paletini kullanacaktır. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Yarı saydam alfa değişimi için arka plan rengi olarak kullanılacak renk. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | En sık kullanılan renklerle _image_ öğesinden başlayan ve _entriesCount_ giriş içeren renk paleti. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster görüntü. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları. |
| entries_count | int | İstenen giriş sayısı. |
| use_image_palette | bool | Ayarlanırsa, mevcutsa kendi görüntü paletini kullanacaktır. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Yarı saydam alfa değişimi için arka plan rengi olarak kullanılacak renk. |
| keep_transparency | bool | Ayarlanırsa, görüntü renklerinin alfa kanal bitlerini dikkate alacaktır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | En sık kullanılan renklerle _image_ öğesinden başlayan ve _entriesCount_ giriş içeren renk paleti. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster görüntü. |
| entries_count | int | İstenen giriş sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | En sık kullanılan renklerle _image_ öğesinden başlayan ve _entriesCount_ giriş içeren renk paleti. |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet, daha iyi indeksli görüntü kalitesi için optimize edilecek veya PaletteMiningMethod.UseCurrentPalette kullanıldığında "AS IS" alınacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster görüntü. |
| entries_count | int | İstenen giriş sayısı. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Palet çıkarma yöntemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | En sık kullanılan renklerle _image_ öğesinden başlayan ve _entriesCount_ giriş içeren renk paleti. |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet, daha iyi indeksli görüntü kalitesi için optimize edilecek veya PaletteMiningMethod.UseCurrentPalette kullanıldığında "AS IS" alınacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster görüntü. |
| entries_count | int | İstenen giriş sayısı. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Palet çıkarma yöntemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | En sık kullanılan renklerle _image_ öğesinden başlayan ve _entriesCount_ giriş içeren renk paleti. |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster görüntü. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları. |
| entries_count | int | İstenen giriş sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | En sık kullanılan renklerle _image_ öğesinden başlayan ve _entriesCount_ giriş içeren renk paleti. |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster görüntü. |
| entries_count | int | İstenen giriş sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | En sık kullanılan renklerle _image_ öğesinden başlayan ve _entriesCount_ giriş içeren renk paleti. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

İlk görüntü renk değerlerinin üst bitlerinden oluşan 256 renkli paleti al.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Görüntü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Bu [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

Tekdüzen 256 renkli paleti al.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Görüntü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Bu [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

Belirtilen paletin şeffaf renkleri olup olmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Palet. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer belirtilen palet şeffaf renklere sahipse; aksi takdirde <c>false</c>. |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# 100 x 100 piksel boyutunda bir BMP görüntüsü oluştur.
with BmpImage(100, 100) as bmpImage:
	# Görüntünün sol üst köşesinden sağ alt köşesine uzanan lineer degrade.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Tüm görüntüyü lineer degrade fırçası ile doldur.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece paletli bir görüntü
	# paletsiz bir bmp'den neredeyse görsel olarak ayırt edilemez olur
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8-bit palet en fazla 256 renk içerir.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# Çıktı şu şekilde görünür:
# Paletli görüntünün boyutu 11078 bayttır.
# Paletsiz görüntünün boyutu 40054 bayttır.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# png görüntüsü yükler        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Dizine dayalı renk türünü kullan
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Maksimum sıkıştırmayı kullan
	png_options.compression_level = 9
	# Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece bir görüntü
	# paletli, paletsiz bir görüntüden neredeyse görsel olarak ayırt edilemez.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# Çıktı dosya boyutu önemli ölçüde azaltılmalıdır.

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# BmpOptions oluştur
	saveOptions = BmpOptions()

	# Çıktı görüntüsünün boyutunu azaltmak için piksel başına 8 bit kullan.
	saveOptions.bits_per_pixel = 8

	# Görüntü piksellerinin en yüksek sayısını kapsayan en yakın 8-bit renk paletini ayarla, böylece paletli bir görüntü
	# neredeyse görsel olarak paletlenmemiş birine fark edilemez.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Sıkıştırma olmadan kaydet.
	# Çıktı görüntüsünün boyutunu azaltmak için RLE-8 sıkıştırmasını da kullanabilirsiniz.
	saveOptions.compression = BitmapCompression.RGB

	# Yatay ve dikey çözünürlüğü 96 dpi olarak ayarlayın.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

