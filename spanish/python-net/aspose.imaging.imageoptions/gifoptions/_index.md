---
title: "Clase GifOptions"
type: docs
weight: 120
url: /es/python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Inicializa una nueva instancia de la clase [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Inicializa una nueva instancia de la clase [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece el color de fondo. |
| background_color_index | System.Byte | r/w | Obtiene o establece el índice de color de fondo del GIF. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| color_resolution | System.Byte | r/w | Obtiene o establece la resolución de color del GIF. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| do_palette_correction | bool | r/w | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece los datos Exif. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| has_trailer | bool | r/w | Obtiene o establece un valor que indica si el GIF tiene trailer. |
| has_transparent_color | System.Nullable`1[[System.Boolean]] | r/w | Obtiene o establece un valor que indica si una imagen GIF tiene color transparente. <br/>            Si el valor devuelto es **None**, esta propiedad es sobrescrita por el contexto de la imagen fuente. |
| interlaced | bool | r/w | True si la imagen debe estar entrelazada. |
| is_palette_sorted | bool | r/w | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| keep_metadata | bool | r/w | Obtiene un valor que indica si conservar los metadatos originales de la imagen al exportar. |
| loops_count | int | r/w | Obtiene o establece el recuento de bucles (Predeterminado 1 bucle) |
| max_diff | int | r/w | Obtiene o establece la diferencia máxima de píxel permitida. Si es mayor que cero, se utilizará compresión con pérdida.<br/>            El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada.<br/>            Funciona mejor cuando solo se introduce poca pérdida, y debido a la limitación del algoritmo de compresión, niveles de pérdida muy altos no proporcionarán tanto beneficio.<br/>            El rango de valores permitidos es [0, 1000]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. |
| pixel_aspect_ratio | System.Byte | r/w | Obtiene o establece la relación de aspecto de píxel del GIF. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtiene o establece la configuración de resolución. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonación por miembros de esta instancia. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Inicializa una nueva instancia de la clase [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Inicializa una nueva instancia de la clase [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) | Las opciones GIF. |

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
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Crea una instancia de MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Crea una instancia de GifOptions y establece sus diversas propiedades, incluida la propiedad Source
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Cree una instancia de Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Obtén los píxeles de la imagen especificando el área como límite de la imagen
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Recorre la matriz y establece el color del píxel indexado alternativo
			for index in range(pixel.length):
				if index % 2 == 0:
					#Establece el color del píxel indexado a amarillo
					pixels[index] = yellow_color
				else:
					#Establece el color del píxel indexado a azul
					pixels[index] = blue_color

			#Aplica los cambios de píxeles a la imagen
			image.save_pixels(image.bounds, pixels)

			# guarde todos los cambios.
			image.save()

	# Escribe MemoryStream en un archivo
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

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

