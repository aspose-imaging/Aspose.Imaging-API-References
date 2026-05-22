---
title: "PngOptions Classe"
type: docs
weight: 250
url: /fr/python-net/aspose.imaging.imageoptions/pngoptions/
---

**Summary:** Create high-quality Portable Network Graphics (PNG) raster images effortlessly<br/>            with our API, offering customizable options for compression levels,<br/>            bits per pixel depths, and alpha bits. Seamlessly process XMP metadata containers,<br/>            ensuring comprehensive image metadata management, and empowering you to tailor<br/>            PNG images to your exact specifications with ease.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Initialise une nouvelle instance de la classe [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Initialise une nouvelle instance de la classe [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | Le niveau de compression par défaut. |
| bit_depth | System.Byte | r/w | Obtient ou définit les valeurs de profondeur de bits dans la plage de 1, 2, 4, 8, 16.<br/>            <br/><br/>            Respectez les limites suivantes :<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) prend en charge une profondeur de bits de 1, 2, 4, 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) prennent en charge une profondeur de bits de 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) prennent en charge une profondeur de bits de 8, 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [color_type](#color_type1) | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Obtient ou définit le type de couleur. |
| [compression_level](#compression_level2) | int | r/w | Obtient ou définit le niveau de compression du [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit les données Exif. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | Obtient ou définit le type de filtre utilisé lors du processus d'enregistrement du fichier png. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | Obtient ou définit le niveau de compression du [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [progressive](#progressive3) | bool | r/w | Obtient ou définit une valeur indiquant si un [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) est progressif. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un clone membre à membre de cette instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Initialise une nouvelle instance de la classe [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Initialise une nouvelle instance de la classe [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | Les options PNG. |

### Property: color_type {#color_type1}

Obtient ou définit le type de couleur.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: compression_level {#compression_level2}

Obtient ou définit le niveau de compression du [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: progressive {#progressive3}

Obtient ou définit une valeur indiquant si un [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) est progressif.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


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
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#Crée une instance de flux de fichier
with open(r"C:\temp\output.png", "w+b") as stream:
	#Créez une instance de PngOptions et définissez ses différentes propriétés
	pngOptions = PngOptions()
	#Définissez la source pour PngOptions
	pngOptions.source = StreamSource(stream)
	#Créez une instance de Image
	with Image.create(pngOptions, 500, 500) as image:
		#Créez et initialisez une instance de la classe Graphics
		graphics = Graphics(image)
		#Efface la surface Graphics
		graphics.clear(Color.wheat);
		#Dessinez un arc en spécifiant l'objet Pen de couleur noire, 
		#un Rectangle entourant l'arc, l'angle de départ et l'angle de balayage
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Dessinez un Bézier en spécifiant l'objet Pen de couleur bleue et les points de coordonnées.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Dessinez une courbe en spécifiant l'objet Pen ayant la couleur Verte et un tableau de Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Dessinez une ellipse en utilisant l'objet Pen et un rectangle environnant
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Dessinez une ligne
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Dessinez un segment de tarte
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Dessinez un polygone en spécifiant l'objet Pen ayant la couleur Rouge et un tableau de Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Dessinez un rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Créez un objet SolidBrush et définissez ses différentes propriétés
		brush = SolidBrush()
		brush.color = Color.purple
		#Dessinez un String en utilisant l'objet SolidBrush et Font, à un Point spécifique
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# enregistrez toutes les modifications.
		image.save();

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

