---
title: "Classe GifOptions"
type: docs
weight: 120
url: /fr/python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initialise une nouvelle instance de la classe [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initialise une nouvelle instance de la classe [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit la couleur d'arrière-plan. |
| background_color_index | System.Byte | r/w | Obtient ou définit l'index de la couleur d'arrière-plan du GIF. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| color_resolution | System.Byte | r/w | Obtient ou définit la résolution des couleurs du GIF. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| do_palette_correction | bool | r/w | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit les données Exif. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| has_trailer | bool | r/w | Obtient ou définit une valeur indiquant si le GIF possède un trailer. |
| has_transparent_color | System.Nullable`1[[System.Boolean]] | r/w | Obtient ou définit une valeur indiquant si une image GIF possède une couleur transparente. <br/>            Si la valeur de retour est **None**, cette propriété est remplacée par le contexte de l'image source. |
| interlaced | bool | r/w | Vrai si l'image doit être entrelacée. |
| is_palette_sorted | bool | r/w | Obtient ou définit une valeur indiquant si les entrées de la palette sont triées. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| loops_count | int | r/w | Obtient ou définit le nombre de boucles (1 boucle par défaut) |
| max_diff | int | r/w | Obtient ou définit la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée.<br/>            La valeur recommandée pour une compression avec perte optimale est 80. 30 correspond à une compression très légère, 200 à une compression lourde.<br/>            Elle fonctionne mieux lorsque seule une petite perte est introduite, et en raison des limites de l'algorithme de compression, des niveaux de perte très élevés n'apporteront pas autant de gain.<br/>            L'intervalle des valeurs autorisées est [0, 1000]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| pixel_aspect_ratio | System.Byte | r/w | Obtient ou définit le rapport d'aspect des pixels du GIF. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un clone membre à membre de cette instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initialise une nouvelle instance de la classe [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initialise une nouvelle instance de la classe [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) | Les options GIF. |

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
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Créer une instance de MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Créez une instance de GifOptions et définissez ses différentes propriétés, y compris la propriété Source
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Créez une instance de Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Obtenez les pixels de l'image en spécifiant la zone comme la bordure de l'image
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Parcourez le tableau et définissez la couleur des pixels indexés alternés
			for index in range(pixel.length):
				if index % 2 == 0:
					#Définissez la couleur du pixel indexé sur jaune
					pixels[index] = yellow_color
				else:
					#Définissez la couleur du pixel indexé sur bleu
					pixels[index] = blue_color

			#Appliquez les modifications de pixels à l'image
			image.save_pixels(image.bounds, pixels)

			# enregistrez toutes les modifications.
			image.save()

	# Écrire MemoryStream dans un fichier
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

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

