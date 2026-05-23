---
title: "Clase TiffOptions"
type: docs
weight: 330
url: /es/python-net/aspose.imaging.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Por defecto se usa la convención little endian. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | Obtiene o establece la opción de almacenamiento alfa. Las opciones distintas de [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/)<br/>            se utilizan cuando hay más de 3 [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) definidos. |
| artist | string | r/w | Obtiene o establece el artista. |
| bits_per_pixel | int | r | Obtiene los bits por píxel. |
| bits_per_sample | int[] | r/w | Obtiene o establece los bits por muestra. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Obtiene o establece un valor que indica el orden de bytes del TIFF. |
| color_map | int[] | r/w | Obtiene o establece el mapa de colores. |
| [compressed_quality](#compressed_quality1) | int | r/w | Obtiene o establece la calidad de la imagen comprimida.<br/>            Se usa con la compresión Jpeg. |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | Obtiene o establece la compresión. |
| derechos de autor | string | r/w | Obtiene o establece los derechos de autor. |
| fecha_hora | string | r/w | Obtiene o establece la fecha y hora. |
| default_memory_allocation_limit | int | r/w | Obtiene o establece el límite de asignación de memoria predeterminado. |
| disable_icc_export | bool | r/w | Obtiene o establece un valor que indica si la exportación del perfil ICC está deshabilitada (el perfil ICC se aplica a los píxeles de origen de antemano). |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| document_name | string | r/w | Obtiene o establece el nombre del documento. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece datos Exif. |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | Obtiene o establece el puntero al IFD EXIF. |
| extra_samples | int[] | r | Obtiene los valores de muestras extra. |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | Obtiene o establece las opciones fax t4. |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | Obtiene o establece el estándar de archivo TIFF. |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | Obtiene o establece el orden de relleno de bits de bytes. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| half_tone_hints | int[] | r/w | Obtiene o establece las sugerencias de semitono. |
| descripción_imagen | string | r/w | Obtiene o establece la descripción de la imagen. |
| longitud_imagen | int | r/w | Obtiene o establece la longitud de la imagen. |
| anchura_imagen | int | r/w | Obtiene o establece la anchura de la imagen. |
| ink_names | string | r/w | Obtiene o establece los nombres de tinta. |
| is_extra_samples_present | bool | r | Obtiene un valor que indica si las muestras adicionales están presentes. |
| is_tiled | bool | r | Obtiene un valor que indica si la imagen está dividida en mosaicos. |
| is_valid | bool | r | Obtiene un valor que indica si el [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) ha sido configurado correctamente. Utilice el método Validate para encontrar la razón del error. |
| keep_metadata | bool | r/w | Obtiene un valor que indica si conservar los metadatos originales de la imagen al exportar. |
| max_sample_value | int[] | r/w | Obtiene o establece el valor máximo de muestra. |
| min_sample_value | int[] | r/w | Obtiene o establece el valor mínimo de muestra. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Las opciones multipágina |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | Obtiene o establece la orientación. |
| page_name | string | r/w | Obtiene o establece el nombre de la página. |
| page_number | int[] | r/w | Obtiene o establece la etiqueta del número de página. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | Obtiene o establece el fotométrico. |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Obtiene o establece la configuración planar. |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | Obtiene o establece el predictor para la compresión LZW. |
| premultiply_components | bool | r/w | Obtiene o establece un valor que indica si los componentes deben ser premultiplicados. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtiene o establece la configuración de resolución. |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Obtiene o establece la unidad de resolución. |
| rows_per_strip | int | r/w | Obtiene o establece las filas por tira. |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | Obtiene o establece el formato de muestra. |
| samples_per_pixel | int | r | Obtiene las muestras por píxel. Para cambiar el valor de esta propiedad, use el setter de la propiedad [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Obtiene o establece el fabricante del escáner. |
| scanner_model | string | r/w | Obtiene o establece el modelo del escáner. |
| smax_sample_value | int[] | r/w | Obtiene o establece el valor máximo de la muestra. El valor tiene un tipo de campo que mejor coincide con los datos de la muestra (Byte, Short o Long). |
| smin_sample_value | int[] | r/w | Obtiene o establece el valor mínimo de la muestra. El valor tiene un tipo de campo que mejor coincide con los datos de la muestra (Byte, Short o Long). |
| software_type | string | r/w | Obtiene o establece el tipo de software. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| strip_byte_counts | int[] | r/w | Obtiene o establece los recuentos de bytes de la tira. |
| strip_offsets | int[] | r/w | Obtiene o establece los desplazamientos de la tira. |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo. |
| tag_count | int | r | Obtiene el recuento de etiquetas. |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece las etiquetas. |
| target_printer | string | r/w | Obtiene o establece la impresora de destino. |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | Obtiene o establece el umbral. |
| tile_byte_counts | int[] | r/w | Obtiene o establece los recuentos de bytes del mosaico. |
| tile_length | int | r/w | Obtiene o establece la longitud del mosaico. |
| tile_offsets | int[] | r/w | Obtiene o establece los desplazamientos del mosaico. |
| tile_width | int | r/w | Obtiene o establece el ancho del mosaico. |
| total_pages | int | r | Obtiene el total de páginas. |
| valid_tag_count | int | r | Obtiene el recuento de etiquetas válidas. Esto no es el recuento total de etiquetas, sino el número de etiquetas que pueden preservarse. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
| xp_author | string | r/w | Obtiene o establece el autor de la imagen, que es usado por Windows Explorer. |
| xp_comment | string | r/w | Obtiene o establece el comentario de la imagen, que es usado por Windows Explorer. |
| xp_keywords | string | r/w | Obtiene o establece el asunto de la imagen, que es usado por Windows Explorer. |
| xp_subject | string | r/w | Obtiene o establece información sobre la imagen, que es usado por Windows Explorer. |
| xp_title | string | r/w | Obtiene o establece información sobre la imagen, que es usado por Windows Explorer. |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la posición x. |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución x. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece los YCbCrCoefficients. |
| y_cb_cr_subsampling | int[] | r/w | Obtiene o establece los factores de submuestreo para la fotometría YCbCr. |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la posición y. |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución y. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Añade una nueva etiqueta. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Añade las etiquetas. |
| [clone()](#clone__3) | Clona esta instancia. |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Por defecto se usa la convención little endian. |
| [create_with_options(options)](#create_with_options_options_5) | Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [create_with_tags(tags)](#create_with_tags_tags_6) | Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | Obtiene la instancia de la etiqueta por tipo. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | Obtiene el recuento de etiquetas válidas. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | Determina si la etiqueta está presente en las opciones o no. |
| [remove_tag(tag)](#remove_tag_tag_10) | Elimina la etiqueta. |
| [remove_tags(tags)](#remove_tags_tags_11) | Elimina las etiquetas. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| validate() | Valida si las opciones tienen una combinación válida de etiquetas |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Por defecto se usa la convención little endian.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | El formato de archivo tiff esperado. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | El formato de archivo tiff esperado. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | El orden de bytes del formato de archivo tiff a usar. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Las opciones de las que copiar. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Las etiquetas con las que inicializar opciones. |

### Property: compressed_quality {#compressed_quality1}

Obtiene o establece la calidad de la imagen comprimida.<br/>            Se usa con la compresión Jpeg.

**See also:**

**[Example # 1](#example_117)**: This example shows how to create a TIFF image with the Jpeg compression and t...


### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Añade una nueva etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | La etiqueta a agregar. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Añade las etiquetas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Las etiquetas a agregar. |

### Method: clone() {#clone__3}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Devuelve una clonación profunda. |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Por defecto se usa la convención little endian.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | El formato de archivo tiff esperado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Las opciones de las que copiar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Las etiquetas con las que inicializar opciones. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

Obtiene la instancia de la etiqueta por tipo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | La clave de la etiqueta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Instancia de la etiqueta si existe o null de lo contrario. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

Obtiene el recuento de etiquetas válidas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Las etiquetas a validar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El recuento de etiquetas válidas. |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

Determina si la etiqueta está presente en las opciones o no.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | El id de la etiqueta a comprobar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la etiqueta está presente; de lo contrario, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

Elimina la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | La etiqueta a eliminar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true si se eliminó correctamente |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

Elimina las etiquetas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Las etiquetas a eliminar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | **True** si el tamaño de la colección de etiquetas cambió. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


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
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Crea una instancia de un flujo de archivo
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Cree una instancia de TiffOptions y establezca sus diversas propiedades
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Establezca la fuente para la instancia de ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Cree una instancia de Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Crea e inicializa una instancia de la clase Graphics
		graphics = Graphics(image)
		# Limpia la superficie Graphics
		graphics.clear(Color.wheat);
		# Cree una instancia de la clase GraphicsPath
		graphics_path = GraphicsPath()
		# Cree una instancia de la clase Figure
		figure = Figure()
		# Agregue Shapes al objeto Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Agregue el objeto Figure a GraphicsPath
		graphics_path.add_figure(figure)
		# Dibuje la ruta con el objeto Pen de color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# guarde todos los cambios.
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

### This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality. {#example_117}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import TiffOptions   
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat, TiffPhotometrics, TiffCompressions

with aspycore.as_of(Image.load("zeebra.tif"), TiffImage) as image:
	tiff_options = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Establece el modelo de color RGB.
	tiff_options.photometric = TiffPhotometrics.RGB
	# Establece la compresión Jpeg.
	tiff_options.compression = TiffCompressions.JPEG
	tiff_options.compressed_quality = 50
	# Establece 8 bits para cada componente de color.
	tiff_options.bits_per_sample = [8, 8, 8]
	image.save("zeebra.tif-50.tiff", tiff_options)


```

