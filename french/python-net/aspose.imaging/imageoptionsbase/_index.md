---
title: "ImageOptionsBase Classe"
type: docs
weight: 5760
url: /fr/python-net/aspose.imaging/imageoptionsbase/
---

**Summary:** The image base options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageOptionsBase

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit les données Exif. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| [palette](#palette2) | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| [resolution_settings](#resolution_settings3) | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un clone membre à membre de cette instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Property: buffer_size_hint {#buffer_size_hint1}

Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

**See also:**

**[Example # 1](#example_180)**: The following example shows how to set a memory limit when creating a new JPE...


### Property: palette {#palette2}

Obtient ou définit la palette de couleurs.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...

**[Example # 3](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Property: resolution_settings {#resolution_settings3}

Obtient ou définit les paramètres de résolution.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


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
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Créez une image BMP de 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Remplissez toute l'image avec le pinceau de dégradé linéaire.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Obtenez la palette de couleurs 8 bits la plus proche qui couvre le plus grand nombre de pixels possible, afin qu'une image à palette
	# est presque visuellement indiscernable d'un BMP sans palette
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# Une palette 8 bits contient au maximum 256 couleurs.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# La sortie ressemble à ceci :
# La taille de l'image avec palette est de 11078 octets.
# La taille de l'image sans palette est de 40054 octets.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Charge l'image png        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Utilisez le type de couleur indexée
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Utilisez une compression maximale
	png_options.compression_level = 9
	# Obtenez la palette de couleurs 8 bits la plus proche, couvrant le plus grand nombre de pixels possible, afin qu'une image
	# avec palette soit presque visuellement indiscernable d'une image sans palette.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# La taille du fichier de sortie devrait être considérablement réduite

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# Créez BmpOptions
	saveOptions = BmpOptions()

	# Utilisez 8 bits par pixel pour réduire la taille de l'image de sortie.
	saveOptions.bits_per_pixel = 8

	# Définissez la palette de couleurs 8 bits la plus proche qui couvre le nombre maximal de pixels de l'image, afin qu'une image à palette
	# est presque visuellement indiscernable d'une version non palettisée.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Enregistrer sans compression.
	# Vous pouvez également utiliser la compression RLE-8 pour réduire la taille de l'image de sortie.
	saveOptions.compression = BitmapCompression.RGB

	# Définissez la résolution horizontale et verticale à 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

### The following example creates a palettized grayscale BMP image and then saves it to a file. {#example_92}
``` python

from os.path import join as path_join
from aspose.imaging import Image, ColorPaletteHelper, ResolutionSetting, Graphics, Point, Color
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.brushes import LinearGradientBrush

directory = "c:\\temp\\"
createOptions = BmpOptions()

# Enregistrer dans un fichier
createOptions.source = FileCreateSource(path_join(directory, "output.palette8bit.bmp"), False)
	
# Utilisez 8 bits par pixel pour réduire la taille de l'image de sortie.
createOptions.bits_per_pixel = 8

# Définissez la palette de couleurs en niveaux de gris standard 8 bits qui couvre toutes les nuances de gris.
# Si l'image traitée ne contient que des couleurs en niveaux de gris, alors sa version palettisée
# est visuellement indiscernable d'une version non palettisée.
createOptions.palette = ColorPaletteHelper.create_8_bit_grayscale(False)

# Enregistrer sans compression.
# Vous pouvez également utiliser la compression RLE-8 pour réduire la taille de l'image de sortie.
createOptions.compression = BitmapCompression.RGB

# Définissez la résolution horizontale et verticale à 96 dpi.
createOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

# Créez une image BMP de 100 x 100 px et enregistrez‑la dans un fichier.
with Image.create(createOptions, 100, 100) as image:
	graphics = Graphics(image)
	gradientBrush = LinearGradientBrush(Point(0, 0), Point(image.width, image.height), Color.black, Color.white)
	# Remplissez l'image avec un dégradé en niveaux de gris
	graphics.fill_rectangle(gradientBrush, image.bounds)
	image.save()


```

### The following example shows how to set a memory limit when creating a new JPEG image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_180}
``` python
from os.path import join
from aspose.imaging import Image
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode

dir_: str = "c:\\aspose.imaging\\issues\\net\\3404\\"
# Définition d'une limite de mémoire de 50 mégaoctets pour l'image cible créée
create_options = JpegOptions()
create_options.compression_type = JpegCompressionMode.PROGRESSIVE
create_options.buffer_size_hint = 50
create_options.source = FileCreateSource(join(dir_, "createdFile.jpg"), False)
with Aspose.Imaging.Image.create(create_options, 1000, 1000) as image:
	# enregistrer au même emplacement
	image.save()


```

