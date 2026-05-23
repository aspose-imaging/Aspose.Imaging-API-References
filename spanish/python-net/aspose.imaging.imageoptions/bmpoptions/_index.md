---
title: "Clase BmpOptions"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The API for BMP and DIB raster image format creation options provides developers<br/>            with a versatile toolset for generating custom Bitmap (BMP) and Device<br/>            Independent Bitmap (DIB) images. With this API, you can precisely define<br/>            image characteristics such as bits per pixel, compression level and compression<br/>            type, tailoring the output to meet specific requirements. This feature-rich<br/>            API empowers developers to create high-quality, customized raster images<br/>            with ease and flexibility for diverse applications.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Inicializa una nueva instancia de la clase [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Inicializa una nueva instancia de la clase [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | Obtiene o establece la cantidad de bits por píxel de la imagen. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Obtiene o establece el tipo de compresión. El tipo de compresión predeterminado es [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), que permite guardar una [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) con transparencia. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece los datos Exif. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| keep_metadata | bool | r/w | Obtiene un valor que indica si conservar los metadatos originales de la imagen al exportar. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtiene o establece la configuración de resolución. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonación por miembros de esta instancia. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Inicializa una nueva instancia de la clase [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).


**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Inicializa una nueva instancia de la clase [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) | Las opciones BMP. |

### Property: bits_per_pixel {#bits_per_pixel1}

Obtiene o establece la cantidad de bits por píxel de la imagen.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 3](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Property: compression {#compression2}

Obtiene o establece el tipo de compresión. El tipo de compresión predeterminado es [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), que permite guardar una [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) con transparencia.

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

Crea una clonación por miembros de esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Una clonación por miembros de esta instancia. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Los metadatos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero, si la instancia [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) admite y/o implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); de lo contrario, falso. |


## **Examples**
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Crea una instancia de `BmpOptions` y establece sus diversas propiedades
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Crea una instancia de `FileCreateSource` y asígnala como `source` para la instancia de `BmpOptions`
	#El segundo parámetro `Boolean` determina si el archivo a crear es_temporal o no
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Crea una instancia de Image e inicialízala con una instancia de BmpOptions llamando al método Create
	with Image.create(bmp_options, 500, 500) as image:
		#realiza algún procesamiento de imagen
		# guarda todos los cambios
		image.save()


```

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Cargar una imagen gif existente como una instancia de la clase Image
with Image.load(path_join(directory, "sample.gif")) as image:
	# Exportar al formato de archivo BMP usando las opciones predeterminadas
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Exportar al formato de archivo JPEG usando las opciones predeterminadas
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Exportar al formato de archivo PNG usando las opciones predeterminadas
	image.save(path_join(directory, "output.png"), PngOptions())
	# Exportar al formato de archivo TIFF usando las opciones predeterminadas
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

# Guardar en un archivo
createOptions.source = FileCreateSource(path_join(directory, "output.palette8bit.bmp"), False)
	
# Usar 8 bits por píxel para reducir el tamaño de la imagen de salida.
createOptions.bits_per_pixel = 8

# Establece la paleta de colores en escala de grises estándar de 8 bits que cubre todos los colores en escala de grises.
# Si la imagen procesada contiene solo colores en escala de grises, entonces su versión paletizada
# es visualmente indistinguible de una que no está paletizada.
createOptions.palette = ColorPaletteHelper.create_8_bit_grayscale(False)

# Guardar sin compresión.
# También puedes usar compresión RLE-8 para reducir el tamaño de la imagen de salida.
createOptions.compression = BitmapCompression.RGB

# Establece la resolución horizontal y vertical a 96 dpi.
createOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

# Crea una imagen BMP de 100 x 100 px y guárdala en un archivo.
with Image.create(createOptions, 100, 100) as image:
	graphics = Graphics(image)
	gradientBrush = LinearGradientBrush(Point(0, 0), Point(image.width, image.height), Color.black, Color.white)
	# Rellena la imagen con un degradado en escala de grises
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
# Cargar una imagen PNG desde un archivo.
with Image.load(source_path) as pngImage:
	# La imagen BMP se guarda con soporte de transparencia de forma predeterminada. 
	# Si desea especificar explícitamente dicho modo, la propiedad `compression` de BmpOptions debe establecerse en BitmapCompression.BITFIELDS.
	# El método de compresión BitmapCompression.BITFIELDS es el método de compresión predeterminado en BmpOptions.
	# Por lo tanto, el mismo resultado de exportar una imagen Bmp con transparencia se puede lograr mediante cualquiera de las siguientes formas.
	# Con opciones predeterminadas implícitas:
	pngImage.save(output_path_def)
	# Con opciones predeterminadas explícitas:
	pngImage.save(output_path_def_2, BmpOptions())
	# Especificando el método de compresión BitmapCompression.BITFIELDS:
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
# Cargar una imagen PNG desde un archivo.
with Image.load(source_path) as pngImage:
	# La imagen BMP se guarda con soporte de transparencia de forma predeterminada, lo que se logra utilizando el método de compresión BitmapCompression.BITFIELDS. 
	# Para guardar una imagen BMP con el método de compresión RGB, se debe especificar BmpOptions con la propiedad `compression` establecida en BitmapCompression.RGB.
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

