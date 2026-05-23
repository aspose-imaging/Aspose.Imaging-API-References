---
title: "Clase DxfOptions"
type: docs
weight: 80
url: /es/python-net/aspose.imaging.imageoptions/dxfoptions/
---

**Summary:** API for Drawing Interchange Format (DXF) vector image creation offers<br/>            tailored solutions for generating AutoCAD drawing files with precision and<br/>            flexibility. Designed specifically for working with text lines and Bezier<br/>            curves, developers can efficiently manipulate these elements, count Bezier<br/>            points, and convert curves into polylines for seamless exporting, ensuring<br/>            compatibility and fidelity in DXF vector images.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DxfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [DxfOptions()](#DxfOptions__1) | Inicializa una nueva instancia de la clase DxfOptions. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bezier_point_count | System.Byte | r/w | Cuántos puntos generar al convertir curvas Bézier a polilíneas, mínimo 4. Se usa cuando [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) y [DxfOptions.convert_text_beziers](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) están ambos 	/// establecidos en <c>true</c> |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| convert_text_beziers | bool | r/w | Funciona cuando [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) está establecido en <c>true</c>. Indica si convertir curvas Bézier en contornos de texto a polilíneas multipunto. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece los datos Exif. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| keep_metadata | bool | r/w | Obtiene un valor que indica si conservar los metadatos originales de la imagen al exportar. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtiene o establece la configuración de resolución. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| text_as_lines | bool | r/w | Si el texto debe exportarse como contornos compuestos de polilíneas (por defecto) o como entidades de TEXTO editables de Autocad.<br/>            Si esta opción está establecida |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Crea una clonación por miembros de esta instancia. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: DxfOptions() {#DxfOptions__1}


```
 DxfOptions() 
```

Inicializa una nueva instancia de la clase DxfOptions.

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
### This example demonstrates export to Dxf format {#example_3}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DxfOptions
#Crea una instancia de Image e inicialízala con un archivo de imagen existente en la ubicación del disco.
with Image.load("input.svg") as image:
	options = DxfOptions()
	options.text_as_lines = True
	options.convert_text_beziers = True
	options.bezier_point_count = 20
	image.save("output.dxf", options)


```

