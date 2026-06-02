---
title: "Classe ApngOptions"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.imageoptions/apngoptions/
---

**Summary:** The API for Animated PNG (Animated Portable Network Graphics) image file format<br/>            creation is a dynamic tool for developers seeking to generate captivating<br/>            animated images. With customizable options such as frame duration and the<br/>            number of times to loop, this API allows for fine-tuning animated content<br/>            according to specific needs. Whether creating engaging web graphics or<br/>            interactive visuals, you can leverage this API to seamlessly incorporate<br/>            APNG images with precise control over animation parameters.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.ApngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, PngOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ApngOptions()](#ApngOptions__1) | Initialise une nouvelle instance de la classe [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | Le niveau de compression par défaut. |
| bit_depth | System.Byte | r/w | Obtient ou définit les valeurs de profondeur de bits dans la plage de 1, 2, 4, 8, 16.<br/>            <br/><br/>            Respectez les limites suivantes :<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) prend en charge une profondeur de bits de 1, 2, 4, 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) prennent en charge une profondeur de bits de 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) prennent en charge une profondeur de bits de 8, 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Obtient ou définit le type de couleur. |
| compression_level | int | r/w | Obtient ou définit le niveau de compression du [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [default_frame_time](#default_frame_time1) | int | r/w | Obtient ou définit la durée d'image par défaut. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit l'instance Exif. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Obtient ou définit le type de filtre utilisé lors du processus d'enregistrement du fichier png. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| [num_plays](#num_plays2) | int | r/w | Obtient ou définit le nombre de répétitions de l'animation.<br/>            0 indique une boucle infinie. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | Obtient ou définit le niveau de compression du [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| progressive | bool | r/w | Obtient ou définit une valeur indiquant si un [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) est progressif. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit les données Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un clone membre à membre de cette instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: ApngOptions() {#ApngOptions__1}


```
 ApngOptions() 
```

Initialise une nouvelle instance de la classe [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/).

### Property: default_frame_time {#default_frame_time1}

Obtient ou définit la durée d'image par défaut.

**See also:**

**[Example # 1](#example_198)**: The following example shows how to export apng APNG file format from other no...


### Property: num_plays {#num_plays2}

Obtient ou définit le nombre de répétitions de l'animation.<br/>            0 indique une boucle infinie.

**See also:**

**[Example # 1](#example_197)**: The following example shows how to export to APNG file format.


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
| bool | Vrai si _metadata_ n'est pas nul et que l'instance [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/>            prend en charge et/ou implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) ; sinon, faux. |


## **Examples**
### The following example shows how to export to APNG file format. {#example_197}
``` python

import aspose.pycore as aspycore
from aspose.imaging import *
from aspose.imaging.imageoptions import *

with Image.load("Animation1.webp") as image:
	# Exporter vers une animation APNG avec des cycles d'animation illimités par défaut
	image.save("Animation1.webp.png", ApngOptions())
	# Configuration des cycles d'animation
	obj_init = ApngOptions()
	# 5 cycles
	obj_init.num_plays = 5
	image.save("Animation2.webp.png", obj_init)


```

### The following example shows how to export apng APNG file format from other non-animated multi-page format. {#example_198}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import ApngOptions

with Image.load("img4.tif") as image:
	# Configuration de la durée du cadre par défaut
	obj_init = ApngOptions()
	# 500 ms
	obj_init.default_frame_time = 500
	image.save("img4.tif.500ms.png", obj_init)
	obj_init2 = ApngOptions()
	# 250 ms
	obj_init2.default_frame_time = 250
	image.save("img4.tif.250ms.png", obj_init2)


```

