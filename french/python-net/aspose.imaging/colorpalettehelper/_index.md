---
title: "Classe ColorPaletteHelper"
type: docs
weight: 1200
url: /fr/python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Crée la palette de couleurs 4 bits. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Crée la palette de niveaux de gris 4 bits. |
| [create_8_bit()](#create_8_bit__3) | Crée la palette de couleurs 8 bits. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Crée la palette de niveaux de gris 8 bits. |
| [create_grayscale(bits)](#create_grayscale_bits_5) | Obtient la palette de niveaux de gris du nombre de bits spécifié. Les valeurs de bits autorisées sont 1, 2, 4, 8. |
| [create_monochrome()](#create_monochrome__6) | Crée une palette de couleurs monochrome contenant uniquement 2 couleurs. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. La palette est sur le point d'être optimisée pour une meilleure qualité d'image indexée ou prise "EN L'ÉTAT" lorsque PaletteMiningMethod.UseCurrentPalette est utilisé. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. La palette est sur le point d'être optimisée pour une meilleure qualité d'image indexée ou prise "EN L'ÉTAT" lorsque PaletteMiningMethod.UseCurrentPalette est utilisé. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs. |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | Obtenir une palette de 256 couleurs, composée des bits supérieurs des valeurs de couleur de l'image initiale. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | Obtenir une palette uniforme de 256 couleurs. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | Détermine si la palette spécifiée contient des couleurs transparentes. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Crée la palette de couleurs 4 bits.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs 4 bits. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Crée la palette de niveaux de gris 4 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| min_is_white | bool | si réglé sur <c>true</c> la palette commence avec la couleur blanche, sinon elle commence avec la couleur noire. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de niveaux de gris 4 bits. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Crée la palette de couleurs 8 bits.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs 8 bits. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Crée la palette de niveaux de gris 8 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| min_is_white | bool | si réglé sur <c>true</c> la palette commence avec la couleur blanche, sinon elle commence avec la couleur noire. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de niveaux de gris 8 bits. |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

Obtient la palette de niveaux de gris du nombre de bits spécifié. Les valeurs de bits autorisées sont 1, 2, 4, 8.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits | int | Le nombre de bits. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Palette de niveaux de gris. |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

Crée une palette de couleurs monochrome contenant uniquement 2 couleurs.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Palette de couleurs pour images monochromes. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'image de destination. |
| entries_count | int | Le nombre d'entrées souhaité. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs qui commence avec les couleurs les plus fréquentes de l'_image_ et contient _entriesCount_ entrées. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'image de destination. |
| entries_count | int | Le nombre d'entrées souhaité. |
| use_image_palette | bool | Si défini, il utilisera sa propre palette d'image si disponible |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs qui commence avec les couleurs les plus fréquentes de l'_image_ et contient _entriesCount_ entrées. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'image de destination. |
| entries_count | int | Le nombre d'entrées souhaité. |
| use_image_palette | bool | Si défini, il utilisera sa propre palette d'image si disponible |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur qui doit être utilisée comme couleur d'arrière-plan pour le remplacement alpha semi-transparent. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs qui commence avec les couleurs les plus fréquentes de l'_image_ et contient _entriesCount_ entrées. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'image de destination. |
| entries_count | int | Le nombre d'entrées souhaité. |
| use_image_palette | bool | Si défini, il utilisera sa propre palette d'image si disponible |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur qui doit être utilisée comme couleur d'arrière-plan pour le remplacement alpha semi-transparent. |
| keep_transparency | bool | Si elle est définie, elle considérera les bits du canal alpha des couleurs de l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs qui commence avec les couleurs les plus fréquentes de l'_image_ et contient _entriesCount_ entrées. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image raster. |
| entries_count | int | Le nombre d'entrées souhaité. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs qui commence avec les couleurs les plus fréquentes de l'_image_ et contient _entriesCount_ entrées. |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. La palette est sur le point d'être optimisée pour une meilleure qualité d'image indexée ou prise "EN L'ÉTAT" lorsque PaletteMiningMethod.UseCurrentPalette est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image raster. |
| entries_count | int | Le nombre d'entrées souhaité. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | La méthode d'extraction de palette. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs qui commence avec les couleurs les plus fréquentes de l'_image_ et contient _entriesCount_ entrées. |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. La palette est sur le point d'être optimisée pour une meilleure qualité d'image indexée ou prise "EN L'ÉTAT" lorsque PaletteMiningMethod.UseCurrentPalette est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image raster. |
| entries_count | int | Le nombre d'entrées souhaité. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | La méthode d'extraction de palette. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs qui commence avec les couleurs les plus fréquentes de l'_image_ et contient _entriesCount_ entrées. |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'image de destination. |
| entries_count | int | Le nombre d'entrées souhaité. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs qui commence avec les couleurs les plus fréquentes de l'_image_ et contient _entriesCount_ entrées. |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

Obtient la palette de couleurs à partir de l'image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image raster. |
| entries_count | int | Le nombre d'entrées souhaité. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette de couleurs qui commence avec les couleurs les plus fréquentes de l'_image_ et contient _entriesCount_ entrées. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

Obtenir une palette de 256 couleurs, composée des bits supérieurs des valeurs de couleur de l'image initiale.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Le [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

Obtenir une palette uniforme de 256 couleurs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Le [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

Détermine si la palette spécifiée contient des couleurs transparentes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si la palette spécifiée possède des couleurs transparentes ; sinon, <c>false</c>. |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Créez une image BMP de 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Remplissez toute l'image avec le pinceau de dégradé linéaire.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Obtenez la palette de couleurs 8 bits la plus proche qui couvre le plus grand nombre de pixels possible, afin qu'une image à palette
	# est presque visuellement indiscernable d'un BMP sans palette
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# Une palette 8 bits contient au maximum 256 couleurs.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# La sortie ressemble à ceci :
# La taille de l'image avec palette est de 11078 octets.
# La taille de l'image sans palette est de 40054 octets.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Charge l'image png        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Utilisez le type de couleur indexée
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Utilisez une compression maximale
	png_options.compression_level = 9
	# Obtenez la palette de couleurs 8 bits la plus proche, couvrant le plus grand nombre de pixels possible, afin qu'une image
	# avec palette soit presque visuellement indiscernable d'une image sans palette.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# La taille du fichier de sortie devrait être considérablement réduite

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

	# Créez BmpOptions
	saveOptions = BmpOptions()

	# Utilisez 8 bits par pixel pour réduire la taille de l'image de sortie.
	saveOptions.bits_per_pixel = 8

	# Définissez la palette de couleurs 8 bits la plus proche qui couvre le nombre maximal de pixels de l'image, afin qu'une image à palette
	# est presque visuellement indiscernable d'une version non palettisée.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Enregistrer sans compression.
	# Vous pouvez également utiliser la compression RLE-8 pour réduire la taille de l'image de sortie.
	saveOptions.compression = BitmapCompression.RGB

	# Définissez la résolution horizontale et verticale à 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

