---
title: "Clase ColorPaletteHelper"
type: docs
weight: 1200
url: /es/python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Crea la paleta de colores de 4 bits. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Crea la paleta de escala de grises de 4 bits. |
| [create_8_bit()](#create_8_bit__3) | Crea la paleta de colores de 8 bits. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Crea la paleta de escala de grises de 8 bits. |
| [create_grayscale(bits)](#create_grayscale_bits_5) | Obtiene la paleta de escala de grises del recuento de bits especificado. Los valores de bits permitidos son 1, 2, 4, 8. |
| [create_monochrome()](#create_monochrome__6) | Crea una paleta de colores monocromática que contiene solo 2 colores. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. La paleta está a punto de optimizarse para una mejor calidad de imagen indexada o tomarse "AS IS" cuando se usa PaletteMiningMethod.UseCurrentPalette. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. La paleta está a punto de optimizarse para una mejor calidad de imagen indexada o tomarse "AS IS" cuando se usa PaletteMiningMethod.UseCurrentPalette. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos. |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | Obtenga una paleta de 256 colores, compuesta por los bits superiores de los valores de color de la imagen inicial. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | Obtenga una paleta uniforme de 256 colores. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | Determina si la paleta especificada tiene colores transparentes. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Crea la paleta de colores de 4 bits.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores de 4 bits. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Crea la paleta de escala de grises de 4 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| min_is_white | bool | si se establece en <c>true</c> la paleta comienza con color blanco, de lo contrario comienza con color negro. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de escala de grises de 4 bits. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Crea la paleta de colores de 8 bits.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores de 8 bits. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Crea la paleta de escala de grises de 8 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| min_is_white | bool | si se establece en <c>true</c> la paleta comienza con color blanco, de lo contrario comienza con color negro. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de escala de grises de 8 bits. |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

Obtiene la paleta de escala de grises del recuento de bits especificado. Los valores de bits permitidos son 1, 2, 4, 8.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bits | int | El recuento de bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paleta de escala de grises. |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

Crea una paleta de colores monocromática que contiene solo 2 colores.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paleta de colores para imágenes monocromáticas. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la imagen de destino. |
| entries_count | int | El recuento de entradas deseado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores que comienza con los colores más frecuentes de la _image_ y contiene _entriesCount_ entradas. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la imagen de destino. |
| entries_count | int | El recuento de entradas deseado. |
| use_image_palette | bool | Si está configurado, usará su propia paleta de imagen si está disponible. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores que comienza con los colores más frecuentes de la _image_ y contiene _entriesCount_ entradas. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la imagen de destino. |
| entries_count | int | El recuento de entradas deseado. |
| use_image_palette | bool | Si está configurado, usará su propia paleta de imagen si está disponible. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | El color que debe usarse como color de fondo para el reemplazo de alfa semitransparente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores que comienza con los colores más frecuentes de la _image_ y contiene _entriesCount_ entradas. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la imagen de destino. |
| entries_count | int | El recuento de entradas deseado. |
| use_image_palette | bool | Si está configurado, usará su propia paleta de imagen si está disponible. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | El color que debe usarse como color de fondo para el reemplazo de alfa semitransparente. |
| keep_transparency | bool | Si está configurado, considerará los bits del canal alfa de los colores de la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores que comienza con los colores más frecuentes de la _image_ y contiene _entriesCount_ entradas. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| entries_count | int | El recuento de entradas deseado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores que comienza con los colores más frecuentes de la _image_ y contiene _entriesCount_ entradas. |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. La paleta está a punto de optimizarse para una mejor calidad de imagen indexada o tomarse "AS IS" cuando se usa PaletteMiningMethod.UseCurrentPalette.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| entries_count | int | El recuento de entradas deseado. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | El método de extracción de la paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores que comienza con los colores más frecuentes de la _image_ y contiene _entriesCount_ entradas. |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. La paleta está a punto de optimizarse para una mejor calidad de imagen indexada o tomarse "AS IS" cuando se usa PaletteMiningMethod.UseCurrentPalette.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| entries_count | int | El recuento de entradas deseado. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | El método de extracción de la paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores que comienza con los colores más frecuentes de la _image_ y contiene _entriesCount_ entradas. |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la imagen de destino. |
| entries_count | int | El recuento de entradas deseado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores que comienza con los colores más frecuentes de la _image_ y contiene _entriesCount_ entradas. |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

Obtiene la paleta de colores de la imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| entries_count | int | El recuento de entradas deseado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores que comienza con los colores más frecuentes de la _image_ y contiene _entriesCount_ entradas. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

Obtenga una paleta de 256 colores, compuesta por los bits superiores de los valores de color de la imagen inicial.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | El [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

Obtenga una paleta uniforme de 256 colores.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | El [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

Determina si la paleta especificada tiene colores transparentes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la paleta especificada tiene colores transparentes; de lo contrario, <c>false</c>. |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Crea una imagen BMP de 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# El degradado lineal desde la esquina superior izquierda hasta la esquina inferior derecha de la imagen.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Rellena toda la imagen con el pincel de degradado lineal.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Obtén la paleta de colores de 8 bits más cercana que cubra la mayor cantidad posible de píxeles, de modo que una imagen paletizada
	# sea casi indistinguible visualmente de un bmp sin paleta
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# Una paleta de 8 bits contiene como máximo 256 colores.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# La salida se ve así:
# El tamaño de la imagen con paleta es de 11078 bytes.
# El tamaño de la imagen sin paleta es de 40054 bytes.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Carga una imagen png        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Usar tipo de color indexado
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Usar compresión máxima
	png_options.compression_level = 9
	# Obtén la paleta de colores de 8 bits más cercana, cubriendo la mayor cantidad posible de píxeles, de modo que una imagen
	# con paleta sea casi indistinguible visualmente de una imagen sin paleta.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# El tamaño del archivo de salida debería reducirse significativamente

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

	# Crear BmpOptions
	saveOptions = BmpOptions()

	# Usar 8 bits por píxel para reducir el tamaño de la imagen de salida.
	saveOptions.bits_per_pixel = 8

	# Establece la paleta de colores de 8 bits más cercana que cubra el número máximo de píxeles de la imagen, de modo que una imagen paletizada
	# es casi visualmente indistinguible de una que no está paletizada.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Guardar sin compresión.
	# También puedes usar compresión RLE-8 para reducir el tamaño de la imagen de salida.
	saveOptions.compression = BitmapCompression.RGB

	# Establece la resolución horizontal y vertical a 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

