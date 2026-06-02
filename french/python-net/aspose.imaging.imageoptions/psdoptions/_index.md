---
title: "Classe PsdOptions"
type: docs
weight: 260
url: /fr/python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Initialise une nouvelle instance de la classe [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_2) | Initialise une nouvelle instance de la classe [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| channel_bits_count | int | r/w | Obtient ou définit le nombre de bits par canal de couleur. |
| channels_count | int | r/w | Obtient ou définit le nombre de canaux de couleur. |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | Obtient ou définit le mode couleur du PSD. |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | Obtient ou définit la méthode de compression du PSD. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit les données Exif. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | Obtient ou définit la version du format de fichier. Cela peut être PSD ou PSB. |
| refresh_image_preview_data | bool | r/w | Obtient ou définit une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD.<br/>            Veuillez noter que le rendu des calques de texte dans la mise en page finale n'est pas pris en charge sur la plateforme Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | Obtient ou définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après traitement (principalement lié aux calques de texte avec polices manquantes).<br/>            Après avoir utilisé cette option, l'utilisateur doit effectuer dans le fichier ouvert dans Photoshop : Menu "Text" -> "Process absent fonts". Après cette opération, tout le texte réapparaîtra.<br/>            Veuillez noter que cette opération peut entraîner des modifications de la mise en page finale. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | Obtient ou définit les options de vectorisation du PSD. |
| version | int | r/w | Obtient ou définit la version du fichier PSD. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtenir ou définir le conteneur de données XMP |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Crée un clone membre à membre de cette instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Initialise une nouvelle instance de la classe [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

Initialise une nouvelle instance de la classe [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | Les options. |

### Property: color_mode {#color_mode1}

Obtient ou définit le mode couleur du PSD.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


### Property: compression_method {#compression_method2}

Obtient ou définit la méthode de compression du PSD.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


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
### This example demonstrates the use of `aspose.imaging` API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#Crée une instance de la classe image et l'initialise avec un fichier existant via le chemin du fichier
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Crée une instance de la classe PsdOptions
	psdOptions = PsdOptions()
	#Définir la CompressionMethod sur RLE
	#Remarque : une autre CompressionMethod prise en charge est CompressionMethod.RAW [Pas de compression]
	psdOptions.compression_method = CompressionMethod.RLE
	#Définir le ColorMode sur GRAYSCALE
	#Remarque : d’autres ColorModes pris en charge sont ColorModes.BITMAP et ColorModes.RGB
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#Enregistrez l’image à l’emplacement disque avec les paramètres PsdOptions fournis
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

