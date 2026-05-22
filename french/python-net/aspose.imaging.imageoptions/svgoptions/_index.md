---
title: "SvgOptions Classe"
type: docs
weight: 300
url: /fr/python-net/aspose.imaging.imageoptions/svgoptions/
---

**Summary:** Create Scalar Vector Graphics (SVG) image files with our API, utilizing versatile<br/>            options for color types and compression levels. Seamlessly customize your<br/>            SVG images with precision, ensuring optimal quality and compatibility for your design needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.SvgOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgOptions()](#SvgOptions__1) | Initialise une nouvelle instance de [SvgOptions](/imaging/python-net/aspose.imaging.imageoptions/svgoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| callback | [ISvgResourceKeeperCallback](/imaging/python-net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/) | r/w | Obtient ou définit la stratégie de stockage des ressources intégrées de [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) telles que les polices, les rasters imbriqués. |
| color_type | [SvgColorMode](/imaging/python-net/aspose.imaging.fileformats.svg/svgcolormode/) | r/w | Obtient ou définit le type de couleur pour l'image SVG. |
| [compress](#compress1) | bool | r/w | Obtient ou définit une valeur indiquant si l'image de sortie doit être compressée. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit les données Exif. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| [text_as_shapes](#text_as_shapes2) | bool | r/w | Obtient ou définit une valeur indiquant si le texte doit être rendu sous forme de formes. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un clone membre à membre de cette instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: SvgOptions() {#SvgOptions__1}


```
 SvgOptions() 
```

Initialise une nouvelle instance de [SvgOptions](/imaging/python-net/aspose.imaging.imageoptions/svgoptions/).

### Property: compress {#compress1}

Obtient ou définit une valeur indiquant si l'image de sortie doit être compressée.

**See also:**

**[Example # 1](#example_196)**: The following example shows how to convert a svg images to svgz format


### Property: text_as_shapes {#text_as_shapes2}

Obtient ou définit une valeur indiquant si le texte doit être rendu sous forme de formes.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


### Method: clone() {#clone__1}


```
 clone() 
```

Crée un clone membre à membre de cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Un clone membre à membre de cette instance. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Les métadonnées. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai, si l'instance [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) prend en charge et/ou implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) ; sinon, faux. |


## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Le texte sera converti en formes.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# La couleur d'arrière-plan de la surface de dessin.
	rasterizationOptions.background_color = Color.white_smoke
	# La taille de la page.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Si un emf intégré existe, alors rendre l'emf ; sinon rendre le wmf.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

### The following example shows how to convert a svgz images to svg fromat {#example_193}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import SvgRasterizationOptions, SvgOptions
from os.path import join

file: str = "example.svgz"
base_folder: str = join("D:", "Compressed")
input_file: str = join(base_folder, file)
out_file: str = input_file + ".svg"
with Image.load(input_file) as image:
	obj_init = SvgRasterizationOptions()
	obj_init.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = SvgOptions()
	obj_init2.vector_rasterization_options = obj_init
	image.save(out_file, obj_init2)


```

### The following example shows how to convert a svg images to svgz format {#example_196}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import SvgRasterizationOptions, SvgOptions

file = "juanmontoya_lingerie.svg"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".svgz"
with Image.load(input_file) as image:
	vector_rasterization_options = SvgRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = SvgOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)            


```

