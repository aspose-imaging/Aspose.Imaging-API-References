---
title: "BmpOptions Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The API for BMP and DIB raster image format creation options provides developers<br/>            with a versatile toolset for generating custom Bitmap (BMP) and Device<br/>            Independent Bitmap (DIB) images. With this API, you can precisely define<br/>            image characteristics such as bits per pixel, compression level and compression<br/>            type, tailoring the output to meet specific requirements. This feature-rich<br/>            API empowers developers to create high-quality, customized raster images<br/>            with ease and flexibility for diverse applications.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initialisiert eine neue Instanz der Klasse [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) . |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initialisiert eine neue Instanz der Klasse [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | Liest oder setzt die Bit‑pro‑Pixel‑Anzahl des Bildes. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Liest oder setzt den Kompressionstyp. Der Standard‑Kompressionstyp ist [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), der das Speichern eines [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) mit Transparenz ermöglicht. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Liest oder setzt die Exif-Daten. |
| full_frame | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| keep_metadata | bool | r/w | Liest einen Wert, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Die Mehrseiten‑Optionen |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Liest oder setzt die Farbpalette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt eine memberweise Kopie dieser Instanz. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initialisiert eine neue Instanz der Klasse [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) .


**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initialisiert eine neue Instanz der Klasse [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) .

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) | Die BMP-Optionen. |

### Property: bits_per_pixel {#bits_per_pixel1}

Liest oder setzt die Bit‑pro‑Pixel‑Anzahl des Bildes.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 3](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Property: compression {#compression2}

Liest oder setzt den Kompressionstyp. Der Standard‑Kompressionstyp ist [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), der das Speichern eines [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) mit Transparenz ermöglicht.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...

**[Example # 3](#example_208)**: Decompress BMP image which was previously compressed using DXT1 compression a...

**[Example # 4](#example_225)**: The example shows how to export a BMP from a PNG file while keeping the alpha...

**[Example # 5](#example_226)**: The example shows how to export a BMP with the RGB compression type.


### Method: clone() {#clone__1}


```
 clone() 
```

Erstellt eine memberweise Kopie dieser Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Eine memberweise Kopie dieser Instanz. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Versucht, eine _metadata_-Instanz zu setzen, falls diese [Image](/imaging/python-net/aspose.imaging/image/)‑Instanz unterstützt und eine [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑Instanz implementiert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Die Metadaten. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn die [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) Instanz unterstützt und/oder das [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) implementiert; andernfalls false. |


## **Examples**
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Erstelle eine Instanz von `BmpOptions` und setze ihre verschiedenen Eigenschaften
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Erstelle eine Instanz von `FileCreateSource` und weise sie als `source` für die Instanz von `BmpOptions` zu
	#Der zweite `Boolean`-Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Erstelle eine Instanz von Image und initialisiere sie mit einer Instanz von BmpOptions, indem du die Create-Methode aufrufst
	with Image.create(bmp_options, 500, 500) as image:
		#Führe einige Bildverarbeitungen durch
		# Speichere alle Änderungen
		image.save()


```

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Lade ein vorhandenes GIF-Bild als Instanz der Image‑Klasse
with Image.load(path_join(directory, "sample.gif")) as image:
	# Exportiere in das BMP-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Exportiere in das JPEG-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Exportiere in das PNG-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.png"), PngOptions())
	# Exportiere in das TIFF-Dateiformat unter Verwendung der Standardoptionen
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

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

### The following example creates a palettized grayscale BMP image and then saves it to a file. {#example_92}
``` python

from os.path import join as path_join
from aspose.imaging import Image, ColorPaletteHelper, ResolutionSetting, Graphics, Point, Color
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.brushes import LinearGradientBrush

directory = "c:\\temp\\"
createOptions = BmpOptions()

# In einer Datei speichern
createOptions.source = FileCreateSource(path_join(directory, "output.palette8bit.bmp"), False)
	
# Verwende 8 Bit pro Pixel, um die Größe des Ausgabebildes zu reduzieren.
createOptions.bits_per_pixel = 8

# Legen Sie die standardmäßige 8‑Bit‑Graustufen‑Farbpalette fest, die alle Graustufen abdeckt.
# Wenn das verarbeitete Bild nur Graustufen enthält, dann ist seine palettierte Version
# visuell nicht von einer nicht palettierten Version zu unterscheiden.
createOptions.palette = ColorPaletteHelper.create_8_bit_grayscale(False)

# Speichern ohne Kompression.
# Sie können auch die RLE-8-Kompression verwenden, um die Größe des Ausgabebildes zu reduzieren.
createOptions.compression = BitmapCompression.RGB

# Stellen Sie die horizontale und vertikale Auflösung auf 96 dpi ein.
createOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

# Erstellen Sie ein BMP‑Bild mit 100 × 100 px und speichern Sie es in einer Datei.
with Image.create(createOptions, 100, 100) as image:
	graphics = Graphics(image)
	gradientBrush = LinearGradientBrush(Point(0, 0), Point(image.width, image.height), Color.black, Color.white)
	# Füllen Sie das Bild mit einem Graustufen‑Verlauf
	graphics.fill_rectangle(gradientBrush, image.bounds)
	image.save()


```

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

### The example shows how to export a BMP from a PNG file while keeping the alpha channel, save a BMP file with transparency. {#example_225}
``` python
from aspose.imaging import Image
from aspose.imaging.fileformats.png import BmpOptions

source_path = "input.png"
output_path_def = "result_def.bmp"
output_path_def_2 = "result_def-2.bmp"
output_path_bitfields = "result_bitfields.bmp"
# Lade ein PNG‑Bild aus einer Datei.
with Image.load(source_path) as pngImage:
	# BMP-Bild wird standardmäßig mit Transparenzunterstützung gespeichert.
	# Wenn Sie diesen Modus explizit festlegen möchten, sollte die `compression`‑Eigenschaft von BmpOptions auf BitmapCompression.BITFIELDS gesetzt werden.
	# Die Kompressionsmethode BitmapCompression.BITFIELDS ist die Standardkompressionsmethode in den BmpOptions.
	# Das gleiche Ergebnis beim Exportieren eines BMP-Bildes mit Transparenz kann also auf eine der folgenden Arten erzielt werden.
	# Mit impliziten Standardoptionen:
	pngImage.save(output_path_def)
	# Mit expliziten Standardoptionen:
	pngImage.save(output_path_def_2, BmpOptions())
	# Angabe der Kompressionsmethode BitmapCompression.BITFIELDS:
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.BITFIELDS
	pngImage.save(output_path_bitfields, bmp_options)


```

### The example shows how to export a BMP with the RGB compression type. {#example_226}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.imageoptions import BmpOptions

source_path = "input.png"
output_path = "output.png"
# Lade ein PNG‑Bild aus einer Datei.
with Image.load(source_path) as pngImage:
	# BMP-Bild wird standardmäßig mit Transparenzunterstützung gespeichert, was durch die Verwendung der Kompressionsmethode BitmapCompression.BITFIELDS erreicht wird.
	# Um ein BMP-Bild mit der RGB‑Kompressionsmethode zu speichern, sollten die BmpOptions angegeben werden, bei denen die `compression`‑Eigenschaft auf BitmapCompression.RGB gesetzt ist.
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

