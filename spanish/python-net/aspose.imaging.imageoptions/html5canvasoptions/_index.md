---
title: "Clase Html5CanvasOptions"
type: docs
weight: 130
url: /es/python-net/aspose.imaging.imageoptions/html5canvasoptions/
---

**Summary:** Create HTML5 Canvas files effortlessly with our API, allowing you to seamlessly<br/>            combine elements like forms, text, images, animations, and links. Benefit from<br/>            robust features including tag identifier and encoding settings support,<br/>            ensuring optimal performance and customization for your web projects.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Html5CanvasOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Html5CanvasOptions()](#Html5CanvasOptions__1) | Inicializa una nueva instancia de la clase [Html5CanvasOptions](/imaging/python-net/aspose.imaging.imageoptions/html5canvasoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| canvas_tag_id | string | r/w | Obtiene o establece el identificador de la etiqueta canvas. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| encoding | string | r/w | Obtiene o establece la codificación. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece los datos Exif. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| full_html_page | bool | r/w | Obtiene o establece un valor que indica si se debe generar la página HTML completa. |
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


### Constructor: Html5CanvasOptions() {#Html5CanvasOptions__1}


```
 Html5CanvasOptions() 
```

Inicializa una nueva instancia de la clase [Html5CanvasOptions](/imaging/python-net/aspose.imaging.imageoptions/html5canvasoptions/).

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
### Any vector image (SVG, WMF, CMX, etc.) can be used as a source for your Canvas images. The following code creates a simple Canvas image. {#example_199}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import Html5CanvasOptions, SvgRasterizationOptions

with Image.load("Sample.svg") as image:
	export_options = Html5CanvasOptions()
	export_options.vector_rasterization_options = SvgRasterizationOptions()
	image.save("Canvas.html", export_options)


```

### You can embed more than one Canvas image within HTML page or update already exsiting page. In order to do that you need to export only the Canvas tag. {#example_200}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import Html5CanvasOptions, SvgRasterizationOptions

with Image.load("Sample.svg") as image:
	options = Html5CanvasOptions()
	options.vector_rasterization_options = SvgRasterizationOptions()
	options.full_html_page = False
	image.save("Canvas.html", options)


```

