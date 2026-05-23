---
title: "ColorPaletteHelper-klass"
type: docs
weight: 1200
url: /sv/python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Skapar 4-bitars färgpalett. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Skapar 4-bitars gråskala-palett. |
| [create_8_bit()](#create_8_bit__3) | Skapar 8-bitars färgpalett. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Skapar 8-bitars gråskala-palett. |
| [create_grayscale(bits)](#create_grayscale_bits_5) | Hämtar den gråskaliga paletten för angivet bitantal. Tillåtna bitvärden är 1, 2, 4, 8. |
| [create_monochrome()](#create_monochrome__6) | Skapar en monokrom färgpalett som endast innehåller 2 färger. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Paletten är på väg att optimeras för bättre indexerad bildkvalitet eller tas "AS IS" när PaletteMiningMethod.UseCurrentPalette används. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Paletten är på väg att optimeras för bättre indexerad bildkvalitet eller tas "AS IS" när PaletteMiningMethod.UseCurrentPalette används. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar. |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | Hämta en 256-färgs palett, sammansatt av de övre bitarna i bildens ursprungliga färgvärden. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | Hämta en enhetlig 256-färgs palett. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | Bestämmer om den angivna paletten har transparenta färger. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Skapar 4-bitars färgpalett.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den 4-bitars färgpaletten. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Skapar 4-bitars gråskala-palett.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| min_is_white | bool | Om den är inställd på <c>true</c> börjar paletten med vit färg, annars börjar den med svart färg. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den 4-bitars gråskaliga paletten. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Skapar 8-bitars färgpalett.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den 8-bitars färgpaletten. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Skapar 8-bitars gråskala-palett.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| min_is_white | bool | Om den är inställd på <c>true</c> börjar paletten med vit färg, annars börjar den med svart färg. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den 8-bitars gråskaliga paletten. |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

Hämtar den gråskaliga paletten för angivet bitantal. Tillåtna bitvärden är 1, 2, 4, 8.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bitar | int | Bitantalet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Gråskalig palett. |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

Skapar en monokrom färgpalett som endast innehåller 2 färger.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpalett för monokroma bilder. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destinationsbildens gränser. |
| entries_count | int | Det önskade antalet poster. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten som börjar med de mest frekventa färgerna från _image_ och innehåller _entriesCount_ poster. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destinationsbildens gränser. |
| entries_count | int | Det önskade antalet poster. |
| use_image_palette | bool | Om den är inställd, kommer den att använda sin egen bildpalett om den finns tillgänglig. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten som börjar med de mest frekventa färgerna från _image_ och innehåller _entriesCount_ poster. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destinationsbildens gränser. |
| entries_count | int | Det önskade antalet poster. |
| use_image_palette | bool | Om den är inställd, kommer den att använda sin egen bildpalett om den finns tillgänglig. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Färgen som ska användas som bakgrundsfärg för halvtransparent alfa-ersättning. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten som börjar med de mest frekventa färgerna från _image_ och innehåller _entriesCount_ poster. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destinationsbildens gränser. |
| entries_count | int | Det önskade antalet poster. |
| use_image_palette | bool | Om den är inställd, kommer den att använda sin egen bildpalett om den finns tillgänglig. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Färgen som ska användas som bakgrundsfärg för halvtransparent alfa-ersättning. |
| keep_transparency | bool | Om den är angiven kommer den att beakta alpha-kanalens bitar i bildens färger. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten som börjar med de mest frekventa färgerna från _image_ och innehåller _entriesCount_ poster. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| entries_count | int | Det önskade antalet poster. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten som börjar med de mest frekventa färgerna från _image_ och innehåller _entriesCount_ poster. |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Paletten är på väg att optimeras för bättre indexerad bildkvalitet eller tas "AS IS" när PaletteMiningMethod.UseCurrentPalette används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| entries_count | int | Det önskade antalet poster. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Palettutvinningsmetoden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten som börjar med de mest frekventa färgerna från _image_ och innehåller _entriesCount_ poster. |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Paletten är på väg att optimeras för bättre indexerad bildkvalitet eller tas "AS IS" när PaletteMiningMethod.UseCurrentPalette används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| entries_count | int | Det önskade antalet poster. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Palettutvinningsmetoden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten som börjar med de mest frekventa färgerna från _image_ och innehåller _entriesCount_ poster. |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Destinationsbildens gränser. |
| entries_count | int | Det önskade antalet poster. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten som börjar med de mest frekventa färgerna från _image_ och innehåller _entriesCount_ poster. |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| entries_count | int | Det önskade antalet poster. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten som börjar med de mest frekventa färgerna från _image_ och innehåller _entriesCount_ poster. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

Hämta en 256-färgs palett, sammansatt av de övre bitarna i bildens ursprungliga färgvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Den [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

Hämta en enhetlig 256-färgs palett.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Den [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

Bestämmer om den angivna paletten har transparenta färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paletten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om den angivna paletten har transparenta färger; annars, <c>false</c>. |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Skapa en BMP-bild 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Den linjära gradienten från övre vänstra till nedre högra hörnet av bilden.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Fyll hela bilden med den linjära gradientpenseln.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Hämta den närmaste 8-bitars färgpaletten som täcker så många pixlar som möjligt, så att en palettiserad bild
	# är nästan visuellt omöjlig att skilja från en bmp utan palett
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8-bitars palett innehåller högst 256 färger.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# Utdata ser ut så här:
# Storleken på bilden med palett är 11078 byte.
# Storleken på bilden utan palett är 40054 byte.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Laddar png-bild        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Använd indexerad färgtyp
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Använd maximal komprimering
	png_options.compression_level = 9
	# Hämta den närmaste 8-bitars färgpaletten, som täcker så många pixlar som möjligt, så att en bild
	# med palett är nästan visuellt omöjlig att skilja från en bild utan palett.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# Utdatafilens storlek bör minskas avsevärt

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

	# Skapa BmpOptions
	saveOptions = BmpOptions()

	# Använd 8 bitar per pixel för att minska storleken på utdatafilen.
	saveOptions.bits_per_pixel = 8

	# Ställ in den närmaste 8-bitars färgpaletten som täcker det maximala antalet bildpixlar, så att en palettiserad bild
	# är nästan visuellt omöjlig att skilja från en icke-paletiserad.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Spara utan komprimering.
	# Du kan också använda RLE-8-komprimering för att minska storleken på den resulterande bilden.
	saveOptions.compression = BitmapCompression.RGB

	# Ställ in horisontell och vertikal upplösning till 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

