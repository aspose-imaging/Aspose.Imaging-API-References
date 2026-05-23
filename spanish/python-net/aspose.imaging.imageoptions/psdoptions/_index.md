---
title: "Clase PsdOptions"
type: docs
weight: 260
url: /es/python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Inicializa una nueva instancia de la clase [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_2) | Inicializa una nueva instancia de la clase [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| channel_bits_count | int | r/w | Obtiene o establece el recuento de bits por canal de color. |
| channels_count | int | r/w | Obtiene o establece el recuento de canales de color. |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | Obtiene o establece el modo de color psd. |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | Obtiene o establece el método de compresión psd. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece los datos Exif. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| keep_metadata | bool | r/w | Obtiene un valor que indica si conservar los metadatos originales de la imagen al exportar. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | Obtiene o establece la versión del formato de archivo. Puede ser PSD o PSB. |
| refresh_image_preview_data | bool | r/w | Obtiene o establece un valor que indica si [refresh image preview data] - opción usada para maximizar la compatibilidad con otros visores de imágenes PSD.<br/>            Tenga en cuenta que el dibujo de capas de texto en el diseño final no es compatible con la plataforma Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | Obtiene o establece un valor que indica si - Eliminar el recurso global del motor de texto - Utilizado para algunos archivos psd con capas de texto, solo en el caso en que no puedan abrirse en Adobe Photoshop después del procesamiento (principalmente relacionado con capas de texto con fuentes ausentes).<br/>            Después de usar esta opción, el usuario debe realizar lo siguiente en el archivo abierto en Photoshop: Menú "Text" -> "Process absent fonts". Después de esa operación todo el texto volverá a aparecer.<br/>            Tenga en cuenta que esta operación puede causar algunos cambios en el diseño final. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtiene o establece la configuración de resolución. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | Obtiene o establece las opciones de vectorización PSD. |
| versión | int | r/w | Obtiene o establece la versión del archivo psd. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtener o establecer el contenedor de datos XMP |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonación por miembros de esta instancia. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Inicializa una nueva instancia de la clase [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

Inicializa una nueva instancia de la clase [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | Las opciones. |

### Property: color_mode {#color_mode1}

Obtiene o establece el modo de color psd.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


### Property: compression_method {#compression_method2}

Obtiene o establece el método de compresión psd.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


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
### This example demonstrates the use of `aspose.imaging` API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#Crea una instancia de la clase image e inicialízala con un archivo existente mediante la ruta del archivo
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Crea una instancia de la clase PsdOptions
	psdOptions = PsdOptions()
	#Establece CompressionMethod como RLE
	#Nota: Otro CompressionMethod compatible es CompressionMethod.RAW [Sin compresión]
	psdOptions.compression_method = CompressionMethod.RLE
	#Establezca el ColorMode a GRAYSCALE
	#Nota: Otros ColorModes compatibles son ColorModes.BITMAP y ColorModes.RGB
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#Guarde la imagen en la ubicación del disco con la configuración de PsdOptions proporcionada
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

