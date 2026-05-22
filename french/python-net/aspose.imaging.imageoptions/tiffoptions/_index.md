---
title: "Classe TiffOptions"
type: docs
weight: 330
url: /fr/python-net/aspose.imaging.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Par défaut, la convention little endian est utilisée. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | Obtient ou définit l'option de stockage alpha. Les options autres que [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/)<br/>            sont utilisées lorsqu'il y a plus de 3 [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) définis. |
| artist | string | r/w | Obtient ou définit l'artiste. |
| bits_per_pixel | int | r | Obtient les bits par pixel. |
| bits_per_sample | int[] | r/w | Obtient ou définit le nombre de bits par échantillon. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Obtient ou définit une valeur indiquant l'ordre des octets TIFF. |
| color_map | int[] | r/w | Obtient ou définit la table de couleurs. |
| [compressed_quality](#compressed_quality1) | int | r/w | Obtient ou définit la qualité de l'image compressée.<br/>            Utilisée avec la compression Jpeg. |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | Obtient ou définit la compression. |
| copyright | string | r/w | Obtient ou définit le copyright. |
| date_time | string | r/w | Obtient ou définit la date et l'heure. |
| default_memory_allocation_limit | int | r/w | Obtient ou définit la limite d'allocation mémoire par défaut. |
| disable_icc_export | bool | r/w | Obtient ou définit une valeur indiquant si l'exportation du profil ICC est désactivée (le profil ICC est appliqué aux pixels source au préalable). |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| document_name | string | r/w | Obtient ou définit le nom du document. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit les données Exif. |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | Obtient ou définit le pointeur vers l’IFD EXIF. |
| extra_samples | int[] | r | Obtient les valeurs des échantillons supplémentaires. |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | Obtient ou définit les options fax t4. |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | Obtient ou définit la norme du fichier TIFF. |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | Obtient ou définit l'ordre de remplissage des bits d'octet. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| half_tone_hints | int[] | r/w | Obtient ou définit les indications de tramage. |
| image_description | string | r/w | Obtient ou définit la description de l'image. |
| image_length | int | r/w | Obtient ou définit la longueur de l'image. |
| image_width | int | r/w | Obtient ou définit la largeur de l'image. |
| ink_names | string | r/w | Obtient ou définit les noms d'encre. |
| is_extra_samples_present | bool | r | Obtient une valeur indiquant si les échantillons supplémentaires sont présents. |
| is_tiled | bool | r | Obtient une valeur indiquant si l'image est découpée en tuiles. |
| is_valid | bool | r | Obtient une valeur indiquant si le [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) a été correctement configuré. Utilisez la méthode Validate pour trouver la raison de l'échec. |
| keep_metadata | bool | r/w | Obtient une valeur indiquant s'il faut conserver les métadonnées d'image originales lors de l'exportation. |
| max_sample_value | int[] | r/w | Obtient ou définit la valeur maximale de l'échantillon. |
| min_sample_value | int[] | r/w | Obtient ou définit la valeur minimale de l'échantillon. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Les options multipages |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | Obtient ou définit l'orientation. |
| page_name | string | r/w | Obtient ou définit le nom de la page. |
| page_number | int[] | r/w | Obtient ou définit l'étiquette du numéro de page. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | Obtient ou définit le photométrique. |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Obtient ou définit la configuration planaire. |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | Obtient ou définit le prédicteur pour la compression LZW. |
| premultiply_components | bool | r/w | Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Obtient ou définit les paramètres de résolution. |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Obtient ou définit l'unité de résolution. |
| rows_per_strip | int | r/w | Obtient ou définit le nombre de lignes par bande. |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | Obtient ou définit le format d'échantillon. |
| samples_per_pixel | int | r | Obtient les échantillons par pixel. Pour modifier la valeur de cette propriété, utilisez le définisseur de propriété [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Obtient ou définit le fabricant du scanner. |
| scanner_model | string | r/w | Obtient ou définit le modèle du scanner. |
| smax_sample_value | int[] | r/w | Obtient ou définit la valeur d'échantillon maximale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long). |
| smin_sample_value | int[] | r/w | Obtient ou définit la valeur d'échantillon minimale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long). |
| software_type | string | r/w | Obtient ou définit le type de logiciel. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| strip_byte_counts | int[] | r/w | Obtient ou définit le nombre d'octets des bandes. |
| strip_offsets | int[] | r/w | Obtient ou définit les décalages des bandes. |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier. |
| tag_count | int | r | Obtient le nombre d'étiquettes. |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit les étiquettes. |
| target_printer | string | r/w | Obtient ou définit l'imprimante cible. |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | Obtient ou définit le seuillage. |
| tile_byte_counts | int[] | r/w | Obtient ou définit le nombre d'octets des tuiles. |
| tile_length | int | r/w | Obtient ou définit la longueur de la tuile. |
| tile_offsets | int[] | r/w | Obtient ou définit les décalages des tuiles. |
| tile_width | int | r/w | Obtient ou définit la largeur de la tuile. |
| total_pages | int | r | Obtient le nombre total de pages. |
| valid_tag_count | int | r | Obtient le nombre d'étiquettes valides. Ce n'est pas le nombre total d'étiquettes mais le nombre d'étiquettes qui peuvent être conservées. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
| xp_author | string | r/w | Obtient ou définit l'auteur de l'image, utilisé par l'Explorateur Windows. |
| xp_comment | string | r/w | Obtient ou définit le commentaire de l'image, utilisé par l'Explorateur Windows. |
| xp_keywords | string | r/w | Obtient ou définit le sujet de l'image, utilisé par l'Explorateur Windows. |
| xp_subject | string | r/w | Obtient ou définit les informations sur l'image, utilisées par l'Explorateur Windows. |
| xp_title | string | r/w | Obtient ou définit les informations sur l'image, utilisées par l'Explorateur Windows. |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la position x. |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la résolution x. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit les coefficients YCbCr. |
| y_cb_cr_subsampling | int[] | r/w | Obtient ou définit les facteurs de sous-échantillonnage pour le photométrique YCbCr. |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la position y. |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la résolution y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Ajoute une nouvelle étiquette. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Ajoute les étiquettes. |
| [clone()](#clone__3) | Clone cette instance. |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Par défaut, la convention little endian est utilisée. |
| [create_with_options(options)](#create_with_options_options_5) | Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [create_with_tags(tags)](#create_with_tags_tags_6) | Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | Obtient l'instance de l'étiquette par type. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | Obtient le nombre d'étiquettes valides. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | Détermine si l'étiquette est présente dans les options ou non. |
| [remove_tag(tag)](#remove_tag_tag_10) | Supprime l'étiquette. |
| [remove_tags(tags)](#remove_tags_tags_11) | Supprime les étiquettes. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| validate() | Valide si les options ont une combinaison valide d'étiquettes |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Par défaut, la convention little endian est utilisée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Le format de fichier tiff attendu. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Le format de fichier tiff attendu. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | L'ordre des octets du format de fichier tiff à utiliser. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Les options à copier depuis. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Les balises avec lesquelles initialiser les options. |

### Property: compressed_quality {#compressed_quality1}

Obtient ou définit la qualité de l'image compressée.<br/>            Utilisée avec la compression Jpeg.

**See also:**

**[Example # 1](#example_117)**: This example shows how to create a TIFF image with the Jpeg compression and t...


### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Ajoute une nouvelle étiquette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | L'étiquette à ajouter. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Ajoute les étiquettes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Les étiquettes à ajouter. |

### Method: clone() {#clone__3}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Renvoie une copie profonde. |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/). Par défaut, la convention little endian est utilisée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Le format de fichier tiff attendu. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Les options à copier depuis. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Les balises avec lesquelles initialiser les options. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

Obtient l'instance de l'étiquette par type.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | La clé de la balise. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Instance de l'étiquette si elle existe ou null sinon. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

Obtient le nombre d'étiquettes valides.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Les étiquettes à valider. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le nombre d'étiquettes valides. |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

Détermine si l'étiquette est présente dans les options ou non.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | L'ID de l'étiquette à vérifier. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'étiquette est présente; sinon, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

Supprime l'étiquette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | L'étiquette à supprimer. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true si supprimé avec succès |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

Supprime les étiquettes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Les étiquettes à supprimer. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** si la taille de la collection d'étiquettes a changé. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


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
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Créez une instance d'un flux de fichier
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Créez une instance de TiffOptions et définissez ses différentes propriétés
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Définissez la source pour l'instance de ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Créez une instance de Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Créez et initialisez une instance de la classe Graphics
		graphics = Graphics(image)
		# Efface la surface Graphics
		graphics.clear(Color.wheat);
		# Créez une instance de la classe GraphicsPath
		graphics_path = GraphicsPath()
		# Créez une instance de la classe Figure
		figure = Figure()
		# Ajoutez des formes à l'objet Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Ajoutez l'objet Figure à GraphicsPath
		graphics_path.add_figure(figure)
		# Dessinez le chemin avec l'objet Pen de couleur Noir
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# enregistrez toutes les modifications.
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

### This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality. {#example_117}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import TiffOptions   
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat, TiffPhotometrics, TiffCompressions

with aspycore.as_of(Image.load("zeebra.tif"), TiffImage) as image:
	tiff_options = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Définir le modèle de couleur RGB.
	tiff_options.photometric = TiffPhotometrics.RGB
	# Définir la compression Jpeg.
	tiff_options.compression = TiffCompressions.JPEG
	tiff_options.compressed_quality = 50
	# Définir 8 bits pour chaque composant de couleur.
	tiff_options.bits_per_sample = [8, 8, 8]
	image.save("zeebra.tif-50.tiff", tiff_options)


```

