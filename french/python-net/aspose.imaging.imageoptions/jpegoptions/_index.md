---
title: "Classe JpegOptions"
type: docs
weight: 160
url: /fr/python-net/aspose.imaging.imageoptions/jpegoptions/
---

**Summary:** Create high-quality JPEG images effortlessly with our API, offering adjustable<br/>            levels of compression to optimize storage size without compromising image quality.<br/>            Benefit from support for various compression types, near lossless coding,<br/>            RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP<br/>            containers, ensuring versatile and customizable options for your image creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.JpegOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IHasJpegExifData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Initialise une nouvelle instance de la classe [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Initialise une nouvelle instance de la classe [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_channel | System.Byte | r/w | Obtient ou définit le nombre de bits par canal pour une image jpeg sans perte. Nous supportons maintenant de 2 à 8 bits par canal. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | Le profil couleur CMYK de destination pour les images jpeg CMYK. À utiliser lors de l'enregistrement des images. Doit être associé au profil RGBColorProfile pour une conversion de couleur correcte. |
| color_type | [JpegCompressionColorMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Obtient ou définit le type de couleur pour l'image jpeg. |
| commentaire | string | r/w | Obtient ou définit le commentaire du fichier jpeg. |
| compression_type | [JpegCompressionMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressionmode/) | r/w | Obtient ou définit le type de compression. |
| default_memory_allocation_limit | int | r/w | Obtient ou définit la limite d'allocation mémoire par défaut. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | Obtenez ou définissez le conteneur de données Exif. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| horizontal_sampling | System.Byte | r/w | Obtient ou définit les sous-échantillonnages horizontaux pour chaque composant. |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | Obtient ou définit le jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Obtient ou définit la limite de différence JPEG-LS pour le codage quasi-sans perte (paramètre NEAR de la spécification JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Obtient ou définit le mode d'entrelacement JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Obtient ou définit les paramètres prédéfinis JPEG-LS. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| preblend_alpha_if_present | bool | r/w | Obtient ou définit une valeur indiquant si les composantes rouge, verte et bleue doivent être mélangées avec une couleur d'arrière-plan, si le canal alpha est présent. |
| quality | int | r/w | Obtient ou définit la qualité de l'image. |
| rd_opt_settings | [RdOptimizerSettings](/imaging/python-net/aspose.imaging.imageoptions/rdoptimizersettings/) | r/w | Obtient ou définit les paramètres de l'optimiseur RD. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| resolution_unit | [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | r/w | Obtient ou définit l'unité de résolution. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | Le profil couleur RGB de destination pour les images jpeg CMYK. À utiliser lors de l'enregistrement des images. Doit être associé au profil CMYKColorProfile pour une conversion de couleur correcte. |
| sample_rounding_mode | [SampleRoundingMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/) | r/w | Obtient ou définit le mode d'arrondi d'échantillon pour adapter une valeur de 8 bits à une valeur de n bits. _JpegOptions.BitsPerChannel_ |
| scaled_quality | int | r | La qualité mise à l'échelle. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| vertical_sampling | System.Byte | r/w | Obtient ou définit les sous-échantillonnages verticaux pour chaque composant. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un clone membre à membre de cette instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Initialise une nouvelle instance de la classe [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Initialise une nouvelle instance de la classe [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | Les options JPEG. |

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

