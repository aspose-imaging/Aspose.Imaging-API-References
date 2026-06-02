---
title: "ColorPaletteHelper‑Klasse"
type: docs
weight: 1200
url: /de/python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Erstellt die 4‑Bit‑Farbpalette. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Erstellt die 4‑Bit‑Graustufenpalette. |
| [create_8_bit()](#create_8_bit__3) | Erstellt die 8‑Bit‑Farbpalette. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Erstellt die 8‑Bit‑Graustufenpalette. |
| [create_grayscale(bits)](#create_grayscale_bits_5) | Liefert die Graustufen-Palette der angegebenen Bit-Anzahl. Erlaubte Bit‑Werte sind 1, 2, 4, 8. |
| [create_monochrome()](#create_monochrome__6) | Erstellt eine monochrome Farbpalette, die nur 2 Farben enthält. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Die Palette wird für eine bessere indizierte Bildqualität optimiert oder unverändert übernommen, wenn PaletteMiningMethod.UseCurrentPalette verwendet wird. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Die Palette wird für eine bessere indizierte Bildqualität optimiert oder unverändert übernommen, wenn PaletteMiningMethod.UseCurrentPalette verwendet wird. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet. |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | Erhalte eine 256‑Farben‑Palette, zusammengesetzt aus den oberen Bits der ursprünglichen Bildfarbwerte. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | Erhalte eine einheitliche 256‑Farben‑Palette. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | Bestimmt, ob die angegebene Palette transparente Farben enthält. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Erstellt die 4‑Bit‑Farbpalette.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die 4‑Bit‑Farbpalette. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Erstellt die 4‑Bit‑Graustufenpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| min_is_white | bool | Wenn auf <c>true</c> gesetzt, beginnt die Palette mit Weiß, andernfalls beginnt sie mit Schwarz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die 4‑Bit‑Graustufen‑Palette. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Erstellt die 8‑Bit‑Farbpalette.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die 8‑Bit‑Farbpalette. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Erstellt die 8‑Bit‑Graustufenpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| min_is_white | bool | Wenn auf <c>true</c> gesetzt, beginnt die Palette mit Weiß, andernfalls beginnt sie mit Schwarz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die 8‑Bit‑Graustufen‑Palette. |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

Liefert die Graustufen-Palette der angegebenen Bit-Anzahl. Erlaubte Bit‑Werte sind 1, 2, 4, 8.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bits | int | Die Bit‑Anzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Graustufen‑Palette. |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

Erstellt eine monochrome Farbpalette, die nur 2 Farben enthält.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Farbpalette für monochrome Bilder. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Begrenzungen des Zielbildes. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette, die mit den häufigsten Farben aus dem _image_ beginnt und _entriesCount_ Einträge enthält. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Begrenzungen des Zielbildes. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |
| use_image_palette | bool | Wenn gesetzt, wird die eigene Bildpalette verwendet, falls verfügbar. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette, die mit den häufigsten Farben aus dem _image_ beginnt und _entriesCount_ Einträge enthält. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Begrenzungen des Zielbildes. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |
| use_image_palette | bool | Wenn gesetzt, wird die eigene Bildpalette verwendet, falls verfügbar. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe, die als Hintergrundfarbe für halbtransparente Alpha‑Ersetzung verwendet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette, die mit den häufigsten Farben aus dem _image_ beginnt und _entriesCount_ Einträge enthält. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Begrenzungen des Zielbildes. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |
| use_image_palette | bool | Wenn gesetzt, wird die eigene Bildpalette verwendet, falls verfügbar. |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe, die als Hintergrundfarbe für halbtransparente Alpha‑Ersetzung verwendet werden soll. |
| keep_transparency | bool | Wenn gesetzt, berücksichtigt es die Alpha‑Kanal‑Bits der Bildfarben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette, die mit den häufigsten Farben aus dem _image_ beginnt und _entriesCount_ Einträge enthält. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette, die mit den häufigsten Farben aus dem _image_ beginnt und _entriesCount_ Einträge enthält. |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Die Palette wird für eine bessere indizierte Bildqualität optimiert oder unverändert übernommen, wenn PaletteMiningMethod.UseCurrentPalette verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Die Palette‑Mining‑Methode. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette, die mit den häufigsten Farben aus dem _image_ beginnt und _entriesCount_ Einträge enthält. |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Die Palette wird für eine bessere indizierte Bildqualität optimiert oder unverändert übernommen, wenn PaletteMiningMethod.UseCurrentPalette verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Die Palette‑Mining‑Methode. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette, die mit den häufigsten Farben aus dem _image_ beginnt und _entriesCount_ Einträge enthält. |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Die Begrenzungen des Zielbildes. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette, die mit den häufigsten Farben aus dem _image_ beginnt und _entriesCount_ Einträge enthält. |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

Ermittelt die Farbpalette aus dem Rasterbild (palettisiert das Bild), falls das Bild keine besitzt. Falls eine Palette existiert, wird sie anstelle von Berechnungen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Rasterbild. |
| entries_count | int | Die gewünschte Anzahl an Einträgen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Farbpalette, die mit den häufigsten Farben aus dem _image_ beginnt und _entriesCount_ Einträge enthält. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

Erhalte eine 256‑Farben‑Palette, zusammengesetzt aus den oberen Bits der ursprünglichen Bildfarbwerte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Die [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

Erhalte eine einheitliche 256‑Farben‑Palette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Das Bild. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Die [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

Bestimmt, ob die angegebene Palette transparente Farben enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Die Palette. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn die angegebene Palette transparente Farben enthält; andernfalls <c>false</c>. |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Erstelle ein BMP‑Bild mit 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Fülle das gesamte Bild mit dem linearen Farbverlaufs‑Pinsel.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Erhalte die nächstgelegene 8‑Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, sodass ein palettiertes Bild
	# fast visuell nicht von einem BMP ohne Palette zu unterscheiden ist.
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# Eine 8‑Bit-Palette enthält höchstens 256 Farben.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# Die Ausgabe sieht folgendermaßen aus:
# Die Größe des Bildes mit Palette beträgt 11078 Byte.
# Die Größe des Bildes ohne Palette beträgt 40054 Byte.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Lädt PNG‑Bild        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Verwende indizierten Farbtyp
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Verwende maximale Kompression
	png_options.compression_level = 9
	# Erhalte die nächstgelegene 8‑Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, sodass ein Bild
	# mit Palette fast visuell nicht von einem Bild ohne Palette zu unterscheiden ist.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# Die Ausgabedateigröße sollte deutlich reduziert werden

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

	# Erstelle BmpOptions
	saveOptions = BmpOptions()

	# Verwende 8 Bit pro Pixel, um die Größe des Ausgabebildes zu reduzieren.
	saveOptions.bits_per_pixel = 8

	# Setze die nächstgelegene 8‑Bit-Farbpalette, die die maximale Anzahl an Bildpixeln abdeckt, sodass ein palettiertes Bild
	# ist fast visuell nicht von einer nicht palettierten Version zu unterscheiden.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Speichern ohne Kompression.
	# Sie können auch die RLE-8-Kompression verwenden, um die Größe des Ausgabebildes zu reduzieren.
	saveOptions.compression = BitmapCompression.RGB

	# Stellen Sie die horizontale und vertikale Auflösung auf 96 dpi ein.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

