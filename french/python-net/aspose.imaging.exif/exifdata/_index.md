---
title: "Classe ExifData"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifData

**Inheritance:** IImageMetadataFormat, TiffDataTypeController

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ExifData()](#ExifData__1) | Initialise une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/). |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | Initialise une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) avec des données provenant d'un tableau. |
| [ExifData(exifdata)](#ExifData_exifdata_3) | Initialise une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) avec des données provenant d'un tableau. |
| [ExifData(exifdata)](#ExifData_exifdata_4) | Initialise une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) avec des données provenant d'un tableau. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la valeur d'ouverture. |
| body_serial_number | string | r/w | Obtient ou définit le numéro de série du boîtier de l'appareil. |
| brightness_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Obtient ou définit la valeur de luminosité. |
| camera_owner_name | string | r/w | Obtient ou définit le nom du propriétaire de l'appareil |
| cfa_pattern | System.Byte | r/w | Obtient ou définit le motif CFA. |
| color_space | [ExifColorSpace](/imaging/python-net/aspose.imaging.exif.enums/exifcolorspace/) | r/w | Obtient ou définit l'espace colorimétrique. |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit les balises, qui appartiennent à la section commune. Cela s'applique uniquement aux images jpeg, dans le format tiff les tiffOptions sont utilisés à la place |
| components_configuration | System.Byte | r/w | Obtient ou définit la configuration des composants. |
| compressed_bits_per_pixel | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit les bits compressés par pixel. |
| contrast | [ExifContrast](/imaging/python-net/aspose.imaging.exif.enums/exifcontrast/) | r/w | Obtient ou définit le contraste. |
| custom_rendered | [ExifCustomRendered](/imaging/python-net/aspose.imaging.exif.enums/exifcustomrendered/) | r/w | Obtient ou définit le rendu personnalisé. |
| date_time_digitized | string | r/w | Obtient ou définit la date et l'heure de numérisation. |
| date_time_original | string | r/w | Obtient ou définit la date et l'heure d'origine. |
| device_setting_description | System.Byte | r/w | Obtient ou définit la description des paramètres de l'appareil |
| digital_zoom_ratio | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le rapport de zoom numérique. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit les balises qui appartiennent uniquement à la section EXIF. |
| exif_version | System.Byte | r/w | Obtient ou définit la version EXIF. |
| exposure_bias_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Obtient ou définit la valeur du biais d'exposition. |
| exposure_index | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit l'indice d'exposition. |
| exposure_mode | [ExifExposureMode](/imaging/python-net/aspose.imaging.exif.enums/exifexposuremode/) | r/w | Obtient ou définit le mode d'exposition. |
| exposure_program | [ExifExposureProgram](/imaging/python-net/aspose.imaging.exif.enums/exifexposureprogram/) | r/w | Obtient ou définit le programme d'exposition. |
| exposure_time | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le temps d'exposition. |
| f_number | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le nombre F. |
| file_source | [ExifFileSource](/imaging/python-net/aspose.imaging.exif.enums/exiffilesource/) | r/w | Obtient ou définit le type de source du fichier. |
| flash | [ExifFlash](/imaging/python-net/aspose.imaging.exif.enums/exifflash/) | r/w | Obtient ou définit le flash. |
| flash_energy | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit l'énergie du flash. |
| flashpix_version | System.Byte | r/w | Obtient ou définit la version flash pix. |
| focal_length | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la distance focale. |
| focal_length_in_35_mm_film | int | r/w | Obtient ou définit la distance focale en film 35 mm. |
| focal_plane_resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Obtient ou définit l'unité de résolution du plan focal. |
| focal_plane_x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la résolution X du plan focal. |
| focal_plane_y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la résolution Y du plan focal. |
| gain_control | [ExifGainControl](/imaging/python-net/aspose.imaging.exif.enums/exifgaincontrol/) | r/w | Obtient ou définit le degré d'ajustement global du gain de l'image. |
| gamma | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le gamma. |
| gps_altitude | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit l'altitude GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/imaging/python-net/aspose.imaging.exif.enums/exifgpsaltituderef/) | r/w | Obtient ou définit l'altitude GPS utilisée comme altitude de référence. |
| gps_area_information | System.Byte | r/w | Obtient ou définit les informations de zone GPS. |
| gps_date_stamp | string | r/w | Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné). |
| gps_dest_bearing | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit l'azimut GPS vers le point de destination. |
| gps_dest_bearing_ref | string | r/w | Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination. |
| gps_dest_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la distance GPS jusqu'au point de destination. |
| gps_dest_distance_ref | string | r/w | Obtient ou définit l'unité GPS utilisée pour exprimer la distance jusqu'au point de destination. |
| gps_dest_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la latitude GPS du point de destination. |
| gps_dest_latitude_ref | string | r/w | Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est nord ou sud. |
| gps_dest_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la longitude GPS du point de destination. |
| gps_dest_longitude_ref | string | r/w | Obtient ou définit la valeur GPS indiquant si la longitude du point de destination est est ou ouest. |
| gps_differential | int | r/w | Obtient ou définit une valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS. |
| gps_img_direction | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la direction GPS de l'image lorsqu'elle a été capturée. |
| gps_img_direction_ref | string | r/w | Obtient ou définit la référence GPS pour fournir la direction de l'image lorsqu'elle est capturée. |
| gps_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la latitude GPS. |
| gps_latitude_ref | string | r/w | Obtient ou définit si la latitude GPS est nord ou sud. |
| gps_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la longitude GPS. |
| gps_longitude_ref | string | r/w | Obtient ou définit la longitude GPS, est‑elle à l’est ou à l’ouest. |
| gps_map_datum | string | r/w | Obtient ou définit les données de levé géodésique GPS utilisées par le récepteur GPS. |
| gps_measure_mode | string | r/w | Obtient ou définit le mode de mesure GPS. |
| gps_processing_method | System.Byte | r/w | Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation. |
| gps_satellites | string | r/w | Obtient ou définit les satellites GPS utilisés pour les mesures. |
| gps_speed | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la vitesse du mouvement du récepteur GPS. |
| gps_speed_ref | string | r/w | Obtient ou définit l’unité utilisée pour exprimer la vitesse du mouvement du récepteur GPS. |
| gps_status | string | r/w | Obtient ou définit l’état du récepteur GPS lors de l’enregistrement de l’image. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit les balises, qui appartiennent uniquement à la section GPS. |
| gps_timestamp | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le temps GPS en UTC (Temps Universel Coordonné). |
| gps_track | string | r/w | Obtient ou définit la direction du mouvement du récepteur GPS. |
| gps_track_ref | string | r/w | Obtient ou définit la référence permettant de donner la direction du mouvement du récepteur GPS. |
| gps_version_id | System.Byte | r/w | Obtient ou définit l’identifiant de version GPS. |
| gpsdop | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le DOP GPS (degré de précision des données). |
| image_unique_id | string | r/w | Obtient ou définit l’identifiant unique de l’image. |
| is_big_endian | bool | r/w | Obtient ou définit une valeur indiquant si les données EXIF du flux créées à partir de celui-ci sont en big endian. |
| iso_speed | int | r/w | Obtient ou définit la vitesse ISO |
| iso_speed_latitude_yyy | int | r/w | Obtient ou définit la valeur de latitude yyy de la vitesse ISO d'un appareil photo ou d'un dispositif d'entrée définie dans la norme ISO 12232. |
| iso_speed_latitude_zzz | int | r/w | Obtient ou définit la valeur de latitude zzz de la vitesse ISO d'un appareil photo ou d'un dispositif d'entrée définie dans la norme ISO 12232. |
| iso_speed_value | int | r/w | Obtient ou définit la valeur de la vitesse ISO. |
| lens_make | string | r/w | Obtient ou définit le fabricant de l'objectif. |
| lens_model | string | r/w | Obtient ou définit le modèle de l'objectif. |
| lens_serial_number | string | r/w | Obtient ou définit le numéro de série de l'objectif. |
| lens_specification | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit les spécifications de l'objectif |
| light_source | [ExifLightSource](/imaging/python-net/aspose.imaging.exif.enums/exiflightsource/) | r/w | Obtient ou définit la source lumineuse. |
| make | string | r/w | Obtient le fabricant de l'équipement d'enregistrement. |
| maker_note_data | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r | Obtient les données de note du fabricant. |
| maker_note_raw_data | System.Byte | r/w | Obtient ou définit les données brutes de la note du fabricant. |
| [maker_notes](#maker_notes1) | [MakerNote[]](/imaging/python-net/aspose.imaging.exif/makernote/) | r | Obtient les notes du fabricant. |
| max_aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la valeur d'ouverture maximale. |
| metering_mode | [ExifMeteringMode](/imaging/python-net/aspose.imaging.exif.enums/exifmeteringmode/) | r/w | Obtient ou définit le mode de mesure. |
| oecf | System.Byte | r/w | Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. |
| orientation | [ExifOrientation](/imaging/python-net/aspose.imaging.exif.enums/exiforientation/) | r/w | Obtient ou définit l'orientation. |
| photographic_sensitivity | int | r/w | Obtient ou définit la sensibilité photographique. |
| pixel_x_dimension | int | r/w | Obtient ou définit la dimension x du pixel. |
| pixel_y_dimension | int | r/w | Obtient ou définit la dimension y du pixel. |
| properties | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit toutes les balises EXIF (y compris les balises communes et GPS). |
| recommended_exposure_index | int | r/w | Obtient ou définit l'indice d'exposition recommandé. |
| related_sound_file | string | r/w | Obtient ou définit le fichier audio associé. |
| saturation | [ExifSaturation](/imaging/python-net/aspose.imaging.exif.enums/exifsaturation/) | r/w | Obtient ou définit la saturation. |
| scene_capture_type | [ExifSceneCaptureType](/imaging/python-net/aspose.imaging.exif.enums/exifscenecapturetype/) | r/w | Obtient ou définit le type de capture de scène. |
| scene_type | System.Byte | r/w | Obtient ou définit le type de scène. |
| sensing_method | [ExifSensingMethod](/imaging/python-net/aspose.imaging.exif.enums/exifsensingmethod/) | r/w | Obtient ou définit la méthode de détection. |
| sensitivity_type | int | r/w | Obtient ou définit le type de sensibilité. |
| sharpness | int | r/w | Obtient ou définit la netteté. |
| shutter_speed_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Obtient ou définit la valeur de la vitesse d'obturation. |
| spatial_frequency_response | System.Byte | r/w | Obtient ou définit la réponse en fréquence spatiale. |
| spectral_sensitivity | string | r/w | Obtient ou définit la sensibilité spectrale. |
| standard_output_sensitivity | int | r/w | Obtient ou définit la sensibilité de sortie standard |
| subject_area | int[] | r/w | Obtient ou définit la zone du sujet. |
| subject_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la distance du sujet. |
| subject_distance_range | [ExifSubjectDistanceRange](/imaging/python-net/aspose.imaging.exif.enums/exifsubjectdistancerange/) | r/w | Obtient ou définit la plage de distances du sujet. |
| subject_location | int[] | r/w | Obtient ou définit l'emplacement du sujet. |
| subsec_time | string | r/w | Obtient ou définit les fractions de seconde pour la balise DateTime. |
| subsec_time_digitized | string | r/w | Obtient ou définit les fractions de seconde pour la balise DateTimeDigitized. |
| subsec_time_original | string | r/w | Obtient ou définit les fractions de seconde pour la balise DateTimeOriginal. |
| thumbnail | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r/w | Obtient ou définit l'image miniature. |
| user_comment | string | r/w | Obtient ou définit le commentaire de l'utilisateur. |
| white_balance | [ExifWhiteBalance](/imaging/python-net/aspose.imaging.exif.enums/exifwhitebalance/) | r/w | Obtient ou définit la balance des blancs. |
| white_point | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la chromaticité du point blanc de l'image. |
| x_resolution | int | r/w | Obtient ou définit la résolution x. |
| y_resolution | int | r/w | Obtient ou définit la résolution y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tag_value(key)](#get_tag_value_key_1) | Obtient la valeur de la balise. |
| [load_from_bytes(binary_data)](#load_from_bytes_binary_data_2) | Crée une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) en la chargeant depuis le tableau d'octets. |
| [remove_tag(tag)](#remove_tag_tag_3) | Supprimer la balise du conteneur |
| [remove_tag(tag_id)](#remove_tag_tag_id_4) | Supprimer la balise du conteneur |
| [remove_tag_id(tag_id)](#remove_tag_id_tag_id_5) | Supprimer la balise du conteneur |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

Initialise une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/).

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

Initialise une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) avec des données provenant d'un tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Les balises communes. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Les balises EXIF. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Les balises GPS. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

Initialise une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) avec des données provenant d'un tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Tableau de balises EXIF ainsi que des balises communes et GPS. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_4}


```
 ExifData(exifdata) 
```

Initialise une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) avec des données provenant d'un tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| exifdata | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Tableau de balises EXIF ainsi que des balises communes et GPS. |

### Property: maker_notes {#maker_notes1}

Obtient les notes du fabricant.

**See also:**

**[Example # 1](#example_222)**: Access camera manufacturer maker notes in Jpeg image.


### Method: get_tag_value(key) {#get_tag_value_key_1}


```
 get_tag_value(key) 
```

Obtient la valeur de la balise.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | La clé de la balise. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Le TiffDataType |


### Method: load_from_bytes(binary_data)  [static] {#load_from_bytes_binary_data_2}


```
 load_from_bytes(binary_data) 
```

Crée une nouvelle instance de la classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) en la chargeant depuis le tableau d'octets.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| binary_data | System.Byte | Les données binaires. |

**Returns**

| Type | Description |
| :- | :- |
| [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | L'instance ExifData chargée. |


### Method: remove_tag(tag) {#remove_tag_tag_3}


```
 remove_tag(tag) 
```

Supprimer la balise du conteneur

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | La balise à supprimer |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_4}


```
 remove_tag(tag_id) 
```

Supprimer la balise du conteneur

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag_id | int | L'identifiant de la balise à supprimer. |

### Method: remove_tag_id(tag_id) {#remove_tag_id_tag_id_5}


```
 remove_tag_id(tag_id) 
```

Supprimer la balise du conteneur

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag_id | int | L'identifiant de la balise à supprimer. |

## **Examples**
### Access camera manufacturer maker notes in Jpeg image. {#example_222}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image
from aspose.imaging.fileformats.jpeg import JpegImage

with as_of(Image.load("Sample.jpg"), JpegImage) as image:
	for makerNote in image.exif_data.maker_notes:
		print(f"Name = {makerNote.name}, Value = {makerNote.value}")


```

