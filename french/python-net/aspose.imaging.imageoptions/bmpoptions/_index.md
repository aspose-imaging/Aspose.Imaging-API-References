---
title: "Classe BmpOptions"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The API for BMP and DIB raster image format creation options provides developers<br/>            with a versatile toolset for generating custom Bitmap (BMP) and Device<br/>            Independent Bitmap (DIB) images. With this API, you can precisely define<br/>            image characteristics such as bits per pixel, compression level and compression<br/>            type, tailoring the output to meet specific requirements. This feature-rich<br/>            API empowers developers to create high-quality, customized raster images<br/>            with ease and flexibility for diverse applications.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initialise une nouvelle instance de la classe [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initialise une nouvelle instance de la classe [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | Obtient ou définit le nombre de bits par pixel de l'image. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Obtient ou définit le type de compression. Le type de compression par défaut est [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), qui permet d'enregistrer un [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) avec transparence. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit les données Exif. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un clone membre à membre de cette instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initialise une nouvelle instance de la classe [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).


**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initialise une nouvelle instance de la classe [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) | Les options BMP. |

### Property: bits_per_pixel {#bits_per_pixel1}

Obtient ou définit le nombre de bits par pixel de l'image.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 3](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Property: compression {#compression2}

Obtient ou définit le type de compression. Le type de compression par défaut est [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/), qui permet d'enregistrer un [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) avec transparence.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...

**[Example # 3](#example_208)**: Decompress BMP image which was previously compressed using DXT1 compression a...

**[Example # 4](#example_225)**: The example shows how to export a BMP from a PNG file while keeping the alpha...

**[Example # 5](#example_226)**: The example shows how to export a BMP with the RGB compression type.


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
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Créez une instance de `BmpOptions` et définissez ses différentes propriétés
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Créez une instance de `FileCreateSource` et assignez‑la comme `source` pour l'instance de `BmpOptions`
	#Le deuxième paramètre `Boolean` détermine si le fichier à créer est is_temporal ou non
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Créez une instance de Image et initialisez‑la avec une instance de BmpOptions en appelant la méthode Create
	with Image.create(bmp_options, 500, 500) as image:
		#effectuer un traitement d'image
		# enregistrer toutes les modifications
		image.save()


```

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Chargez une image gif existante en tant qu'instance de la classe Image
with Image.load(path_join(directory, "sample.gif")) as image:
	# Exportez au format de fichier BMP en utilisant les options par défaut
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Exportez au format de fichier JPEG en utilisant les options par défaut
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Exportez au format de fichier PNG en utilisant les options par défaut
	image.save(path_join(directory, "output.png"), PngOptions())
	# Exportez au format de fichier TIFF en utilisant les options par défaut
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

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

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

### The example shows how to export a BMP from a PNG file while keeping the alpha channel, save a BMP file with transparency. {#example_225}
``` python
from aspose.imaging import Image
from aspose.imaging.fileformats.png import BmpOptions

source_path = "input.png"
output_path_def = "result_def.bmp"
output_path_def_2 = "result_def-2.bmp"
output_path_bitfields = "result_bitfields.bmp"
# Charger une image PNG à partir d'un fichier.
with Image.load(source_path) as pngImage:
	# L'image BMP est enregistrée avec prise en charge de la transparence par défaut.
	# Si vous souhaitez spécifier explicitement ce mode, la propriété `compression` de BmpOptions doit être définie sur BitmapCompression.BITFIELDS.
	# La méthode de compression BitmapCompression.BITFIELDS est la méthode de compression par défaut dans BmpOptions.
	# Ainsi, le même résultat d'exportation d'une image Bmp avec transparence peut être obtenu de l'une des manières suivantes.
	# Avec des options par défaut implicites :
	pngImage.save(output_path_def)
	# Avec des options par défaut explicites :
	pngImage.save(output_path_def_2, BmpOptions())
	# Spécification de la méthode de compression BitmapCompression.BITFIELDS :
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.BITFIELDS
	pngImage.save(output_path_bitfields, bmp_options)


```

### The example shows how to export a BMP with the RGB compression type. {#example_226}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.imageoptions import BmpOptions

source_path = "input.png"
output_path = "output.png"
# Charger une image PNG à partir d'un fichier.
with Image.load(source_path) as pngImage:
	# L'image BMP est enregistrée avec prise en charge de la transparence par défaut, ce qui est réalisé en utilisant la méthode de compression BitmapCompression.BITFIELDS.
	# Pour enregistrer une image BMP avec la méthode de compression RGB, il faut spécifier les BmpOptions avec la propriété `compression` définie sur BitmapCompression.RGB.
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

