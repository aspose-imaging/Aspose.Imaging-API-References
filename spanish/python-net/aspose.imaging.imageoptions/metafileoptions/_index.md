---
title: "Clase MetafileOptions"
type: docs
weight: 170
url: /es/python-net/aspose.imaging.imageoptions/metafileoptions/
---

**Summary:** The Metafiles base options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.MetafileOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [MetafileOptions()](#MetafileOptions__1) | Inicializa una nueva instancia de la clase [MetafileOptions](/imaging/python-net/aspose.imaging.imageoptions/metafileoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| [compress](#compress1) | bool | r/w | Obtiene o establece un valor que indica si este [ICompressedOptions](/imaging/python-net/aspose.fileformats.core.imageoptions/icompressedoptions/) está comprimido. |
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


### Constructor: MetafileOptions() {#MetafileOptions__1}


```
 MetafileOptions() 
```

Inicializa una nueva instancia de la clase [MetafileOptions](/imaging/python-net/aspose.imaging.imageoptions/metafileoptions/).

### Property: compress {#compress1}

Obtiene o establece un valor que indica si este [ICompressedOptions](/imaging/python-net/aspose.fileformats.core.imageoptions/icompressedoptions/) está comprimido.

**See also:**

**[Example # 1](#example_194)**: The following example shows how to convert a emf images to emz format

**[Example # 2](#example_195)**: The following example shows how to convert a wmf images to wmz format


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
### The following example shows how to convert a emf images to emz format {#example_194}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import EmfRasterizationOptions, EmfOptions

file = "input.emf"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".emz"
with Image.load(input_file) as image:
	vector_rasterization_options = EmfRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = EmfOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)


```

### The following example shows how to convert a wmf images to wmz format {#example_195}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import WmfRasterizationOptions, WmfOptions

file = "castle.wmf"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".wmz"
with Image.load(input_file) as image:
	vector_rasterization_options = WmfRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = WmfOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)            


```

