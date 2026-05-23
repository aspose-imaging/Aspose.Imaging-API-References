---
title: "Classe ColorPaletteHelper"
type: docs
weight: 1200
url: /it/python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Crea la tavolozza dei colori a 4 bit. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Crea la tavolozza in scala di grigi a 4 bit. |
| [create_8_bit()](#create_8_bit__3) | Crea la tavolozza dei colori a 8 bit. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Crea la tavolozza in scala di grigi a 8 bit. |
| [create_grayscale(bits)](#create_grayscale_bits_5) | Ottiene la tavolozza in scala di grigi del conteggio di bit specificato. I valori di bit consentiti sono 1, 2, 4, 8. |
| [create_monochrome()](#create_monochrome__6) | Crea una tavolozza di colori monocromatica contenente solo 2 colori. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. La tavolozza sarà ottimizzata per una migliore qualità dell'immagine indicizzata o presa "AS IS" quando viene usato PaletteMiningMethod.UseCurrentPalette. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. La tavolozza sarà ottimizzata per una migliore qualità dell'immagine indicizzata o presa "AS IS" quando viene usato PaletteMiningMethod.UseCurrentPalette. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli. |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | Ottieni una tavolozza di 256 colori, composta dai bit più alti dei valori di colore dell'immagine iniziale. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | Ottieni una tavolozza uniforme di 256 colori. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | Determina se la tavolozza specificata contiene colori trasparenti. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Crea la tavolozza dei colori a 4 bit.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori a 4 bit. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Crea la tavolozza in scala di grigi a 4 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| min_is_white | bool | se impostato su <c>true</c> la tavolozza inizia con il colore bianco, altrimenti inizia con il colore nero. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza in scala di grigi a 4 bit. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Crea la tavolozza dei colori a 8 bit.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori a 8 bit. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Crea la tavolozza in scala di grigi a 8 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| min_is_white | bool | se impostato su <c>true</c> la tavolozza inizia con il colore bianco, altrimenti inizia con il colore nero. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza in scala di grigi a 8 bit. |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

Ottiene la tavolozza in scala di grigi del conteggio di bit specificato. I valori di bit consentiti sono 1, 2, 4, 8.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bit | int | Il conteggio dei bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Tavolozza in scala di grigi. |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

Crea una tavolozza di colori monocromatica contenente solo 2 colori.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Tavolozza di colori per immagini monocromatiche. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I limiti dell'immagine di destinazione. |
| entries_count | int | Il conteggio delle voci desiderate. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori che inizia con i colori più frequenti dal _image_ e contiene _entriesCount_ voci. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I limiti dell'immagine di destinazione. |
| entries_count | int | Il conteggio delle voci desiderate. |
| use_image_palette | bool | Se impostato, utilizzerà la propria tavolozza dell'immagine se disponibile. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori che inizia con i colori più frequenti dal _image_ e contiene _entriesCount_ voci. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I limiti dell'immagine di destinazione. |
| entries_count | int | Il conteggio delle voci desiderate. |
| use_image_palette | bool | Se impostato, utilizzerà la propria tavolozza dell'immagine se disponibile. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore da utilizzare come colore di sfondo per la sostituzione alfa semitrasparente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori che inizia con i colori più frequenti dal _image_ e contiene _entriesCount_ voci. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I limiti dell'immagine di destinazione. |
| entries_count | int | Il conteggio delle voci desiderate. |
| use_image_palette | bool | Se impostato, utilizzerà la propria tavolozza dell'immagine se disponibile. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore da utilizzare come colore di sfondo per la sostituzione alfa semitrasparente. |
| keep_transparency | bool | Se impostato, considererà i bit del canale alfa dei colori dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori che inizia con i colori più frequenti dal _image_ e contiene _entriesCount_ voci. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| entries_count | int | Il conteggio delle voci desiderate. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori che inizia con i colori più frequenti dal _image_ e contiene _entriesCount_ voci. |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. La tavolozza sarà ottimizzata per una migliore qualità dell'immagine indicizzata o presa "AS IS" quando viene usato PaletteMiningMethod.UseCurrentPalette.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| entries_count | int | Il conteggio delle voci desiderate. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Il metodo di estrazione della palette. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori che inizia con i colori più frequenti dal _image_ e contiene _entriesCount_ voci. |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. La tavolozza sarà ottimizzata per una migliore qualità dell'immagine indicizzata o presa "AS IS" quando viene usato PaletteMiningMethod.UseCurrentPalette.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| entries_count | int | Il conteggio delle voci desiderate. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Il metodo di estrazione della palette. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori che inizia con i colori più frequenti dal _image_ e contiene _entriesCount_ voci. |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I limiti dell'immagine di destinazione. |
| entries_count | int | Il conteggio delle voci desiderate. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori che inizia con i colori più frequenti dal _image_ e contiene _entriesCount_ voci. |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

Ottiene la tavolozza di colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la tavolozza esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| entries_count | int | Il conteggio delle voci desiderate. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza di colori che inizia con i colori più frequenti dal _image_ e contiene _entriesCount_ voci. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

Ottieni una tavolozza di 256 colori, composta dai bit più alti dei valori di colore dell'immagine iniziale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Il [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

Ottieni una tavolozza uniforme di 256 colori.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Il [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

Determina se la tavolozza specificata contiene colori trasparenti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se la palette specificata ha colori trasparenti; altrimenti, <c>false</c>. |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Crea un'immagine BMP 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Il gradiente lineare dall'angolo in alto a sinistra a quello in basso a destra dell'immagine.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Riempie l'intera immagine con il pennello a gradiente lineare.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Ottieni la tavolozza di colori a 8 bit più vicina che copre il maggior numero possibile di pixel, in modo che un'immagine con palette
	# sia quasi indistinguibile visivamente da un BMP senza palette
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# La palette a 8 bit contiene al massimo 256 colori.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# L'output appare così:
# La dimensione dell'immagine con palette è 11078 byte.
# La dimensione dell'immagine senza palette è 40054 byte.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Carica immagine PNG        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Usa il tipo di colore indicizzato
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Usa compressione massima
	png_options.compression_level = 9
	# Ottieni la tavolozza di colori a 8 bit più vicina, coprendo il maggior numero possibile di pixel, in modo che un'immagine
	# con palette sia quasi indistinguibile visivamente da un'immagine senza palette.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# La dimensione del file di output dovrebbe essere notevolmente ridotta

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

	# Crea BmpOptions
	saveOptions = BmpOptions()

	# Usa 8 bit per pixel per ridurre la dimensione dell'immagine di output.
	saveOptions.bits_per_pixel = 8

	# Imposta la tavolozza di colori a 8 bit più vicina che copre il numero massimo di pixel dell'immagine, in modo che un'immagine con palette
	# è quasi visivamente indistinguibile da una versione non palettizzata.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Salva senza compressione.
	# Puoi anche usare la compressione RLE-8 per ridurre le dimensioni dell'immagine di output.
	saveOptions.compression = BitmapCompression.RGB

	# Imposta la risoluzione orizzontale e verticale a 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

