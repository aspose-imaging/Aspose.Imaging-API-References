---
title: "Clase JpegOptions"
type: docs
weight: 160
url: /es/python-net/aspose.imaging.imageoptions/jpegoptions/
---

**Summary:** Create high-quality JPEG images effortlessly with our API, offering adjustable<br/>            levels of compression to optimize storage size without compromising image quality.<br/>            Benefit from support for various compression types, near lossless coding,<br/>            RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP<br/>            containers, ensuring versatile and customizable options for your image creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.JpegOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IHasJpegExifData, ImageOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Inicializa una nueva instancia de la clase [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Inicializa una nueva instancia de la clase [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bits_per_channel | System.Byte | r/w | Obtiene o establece los bits por canal para una imagen jpeg sin pérdida. Ahora admitimos de 2 a 8 bits por canal. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | El perfil de color CMYK de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar emparejado con RGBColorProfile para una conversión de color correcta. |
| color_type | [JpegCompressionColorMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Obtiene o establece el tipo de color para la imagen jpeg. |
| comentario | string | r/w | Obtiene o establece el comentario del archivo jpeg. |
| compression_type | [JpegCompressionMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressionmode/) | r/w | Obtiene o establece el tipo de compresión. |
| default_memory_allocation_limit | int | r/w | Obtiene o establece el límite de asignación de memoria predeterminado. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | Obtenga o establezca el contenedor de datos Exif. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| horizontal_sampling | System.Byte | r/w | Obtiene o establece los submuestreos horizontales para cada componente. |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | Obtiene o establece el jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Obtiene o establece el límite de diferencia JPEG-LS para codificación casi sin pérdida (parámetro NEAR de la especificación JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Obtiene o establece el modo de entrelazado JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Obtiene o establece los parámetros predefinidos JPEG-LS. |
| keep_metadata | bool | r/w | Obtiene un valor que indica si conservar los metadatos originales de la imagen al exportar. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. |
| preblend_alpha_if_present | bool | r/w | Obtiene o establece un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si el canal alfa está presente. |
| quality | int | r/w | Obtiene o establece la calidad de la imagen. |
| rd_opt_settings | [RdOptimizerSettings](/imaging/python-net/aspose.imaging.imageoptions/rdoptimizersettings/) | r/w | Obtiene o establece la configuración del optimizador RD. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtiene o establece la configuración de resolución. |
| resolution_unit | [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | r/w | Obtiene o establece la unidad de resolución. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | El perfil de color RGB de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar emparejado con CMYKColorProfile para una conversión de color correcta. |
| sample_rounding_mode | [SampleRoundingMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/) | r/w | Obtiene o establece el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits. _JpegOptions.BitsPerChannel_ |
| scaled_quality | int | r | La calidad escalada. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| vertical_sampling | System.Byte | r/w | Obtiene o establece los submuestreos verticales para cada componente. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonación por miembros de esta instancia. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Inicializa una nueva instancia de la clase [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Inicializa una nueva instancia de la clase [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | Las opciones JPEG. |

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

