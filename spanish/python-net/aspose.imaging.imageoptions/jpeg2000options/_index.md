---
title: "Clase Jpeg2000Options"
type: docs
weight: 150
url: /es/python-net/aspose.imaging.imageoptions/jpeg2000options/
---

**Summary:** Create JPEG2000 (JP2) image files with our API, utilizing advanced wavelet technology<br/>            for coding lossless content. Benefit from support for various codecs, including<br/>            irreversible and lossless compression, as well as XMP metadata containers, ensuring<br/>            versatility and high-quality image creation tailored to your needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Jpeg2000Options

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Inicializa una nueva instancia de la clase [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/). |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Inicializa una nueva instancia de la clase [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| [codec](#codec1) | [Jpeg2000Codec](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000codec/) | r/w | Obtiene o establece el códec JPEG2000 |
| comentarios | string[] | r/w | Obtiene o establece los marcadores de comentarios Jpeg. |
| compression_ratios | int[] | r/w | Obtiene o establece la matriz de relaciones de compresión.<br/>            Diferentes relaciones de compresión para capas sucesivas.<br/>            La tasa especificada para cada nivel de calidad es el factor de compresión deseado<br/>            factor de compresión.<br/>            Se requieren relaciones decrecientes. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece los datos Exif. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| [irreversible](#irreversible2) | bool | r/w | Obtiene o establece un valor que indica si se usa la DWT irreversible 9-7 (true) o se usa compresión DWT sin pérdida 5-3 (predeterminado). |
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


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Inicializa una nueva instancia de la clase [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/).

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Inicializa una nueva instancia de la clase [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | Las opciones de formato de archivo Jpeg2000 de las que copiar la configuración. |

### Property: codec {#codec1}

Obtiene o establece el códec JPEG2000

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


### Property: irreversible {#irreversible2}

Obtiene o establece un valor que indica si se usa la DWT irreversible 9-7 (true) o se usa compresión DWT sin pérdida 5-3 (predeterminado).

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


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
### This example shows how to create a JPEG2000 image with the desired options and save it to a file. {#example_161}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Jpeg2000Image
from os.path import join as path_join     


dir_ = "c:\\temp"
create_options = Jpeg2000Options()
# Utilizar la Transformada Wavelet Discreta irreversible 9-7
create_options.irreversible = True
# JP2 es el formato "contenedor" para los codestreams JPEG 2000.
# J2K son datos comprimidos en bruto, sin un contenedor.
create_options.codec = Jpeg2000Codec.J2K
# Crear una imagen JPEG2000 de 100x100 px.
with Jpeg2000Image(100, 100, create_options) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# Rellene toda la imagen de rojo.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# Guardar en un archivo
	jpeg2000_image.save(path_join(dir_, "sample.output.j2k"))


```

### This example shows how to create a PNG image and save it to JPEG2000 with the desired options. {#example_163}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec
from aspose.imaging.fileformats.png import PngImage
from os.path import join as path_join


dir_ = "c:\\temp"
# Cree una imagen PNG de 100x100 px.
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# Rellene toda la imagen de rojo.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	save_options = Jpeg2000Options()
	# Utilizar la Transformada Wavelet Discreta irreversible 9-7
	save_options.irreversible = True
	# JP2 es el formato "contenedor" para los codestreams JPEG 2000.
	# J2K son datos comprimidos en bruto, sin un contenedor.
	save_options.codec = Jpeg2000Codec.J2K
	# Guardar en un archivo
	png_image.save(path_join(dir_, "output.j2k"), save_options)


```

