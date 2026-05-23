---
title: "ExifData klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifData

**Inheritance:** IImageMetadataFormat, TiffDataTypeController

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ExifData()](#ExifData__1) | Initierar en ny instans av [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) klassen. |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | Initierar en ny instans av [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) klassen med data från en array. |
| [ExifData(exifdata)](#ExifData_exifdata_3) | Initierar en ny instans av [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) klassen med data från en array. |
| [ExifData(exifdata)](#ExifData_exifdata_4) | Initierar en ny instans av [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) klassen med data från en array. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger bländarvärdet. |
| body_serial_number | string | r/w | Hämtar eller anger kamerakroppens serienummer. |
| brightness_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Hämtar eller anger ljusvärdet. |
| camera_owner_name | string | r/w | Hämtar eller anger kamerans ägarnamn |
| cfa_pattern | System.Byte | r/w | Hämtar eller anger CFA-mönstret. |
| color_space | [ExifColorSpace](/imaging/python-net/aspose.imaging.exif.enums/exifcolorspace/) | r/w | Hämtar eller anger färgrymden. |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger taggar som tillhör den gemensamma sektionen. Detta gäller endast för jpeg-bilder, i tiff-format används tiffOptions istället |
| components_configuration | System.Byte | r/w | Hämtar eller anger komponentkonfigurationen. |
| compressed_bits_per_pixel | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger komprimerade bitar per pixel. |
| contrast | [ExifContrast](/imaging/python-net/aspose.imaging.exif.enums/exifcontrast/) | r/w | Hämtar eller anger kontrasten. |
| custom_rendered | [ExifCustomRendered](/imaging/python-net/aspose.imaging.exif.enums/exifcustomrendered/) | r/w | Hämtar eller anger anpassad rendering. |
| date_time_digitized | string | r/w | Hämtar eller anger datum och tid för digitalisering. |
| date_time_original | string | r/w | Hämtar eller anger originaldatum och -tid. |
| device_setting_description | System.Byte | r/w | Hämtar eller anger beskrivning av enhetens inställningar |
| digital_zoom_ratio | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger digitalt zoomförhållande. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger taggar som endast tillhör EXIF‑avsnittet. |
| exif_version | System.Byte | r/w | Hämtar eller anger EXIF‑versionen. |
| exposure_bias_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Hämtar eller anger exponeringsförskjutningsvärdet. |
| exposure_index | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger exponeringsindexet. |
| exposure_mode | [ExifExposureMode](/imaging/python-net/aspose.imaging.exif.enums/exifexposuremode/) | r/w | Hämtar eller anger exponeringsläget. |
| exposure_program | [ExifExposureProgram](/imaging/python-net/aspose.imaging.exif.enums/exifexposureprogram/) | r/w | Hämtar eller anger exponeringsprogrammet. |
| exposure_time | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger exponeringstiden. |
| f_number | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger F‑numret. |
| file_source | [ExifFileSource](/imaging/python-net/aspose.imaging.exif.enums/exiffilesource/) | r/w | Hämtar eller anger filkälltyp. |
| flash | [ExifFlash](/imaging/python-net/aspose.imaging.exif.enums/exifflash/) | r/w | Hämtar eller anger blixten. |
| flash_energy | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger blixtenergin. |
| flashpix_version | System.Byte | r/w | Hämtar eller anger flash‑pix‑versionen. |
| focal_length | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger brännvidden. |
| focal_length_in_35_mm_film | int | r/w | Hämtar eller anger brännvidden i 35 mm‑film. |
| focal_plane_resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Hämtar eller anger fokusplanets upplösningsenhet. |
| focal_plane_x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger fokusplanets x‑upplösning. |
| focal_plane_y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger fokusplanets y‑upplösning. |
| gain_control | [ExifGainControl](/imaging/python-net/aspose.imaging.exif.enums/exifgaincontrol/) | r/w | Hämtar eller anger graden av total bildförstärkningsjustering. |
| gamma | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger gamma. |
| gps_altitude | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS‑höjden. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/imaging/python-net/aspose.imaging.exif.enums/exifgpsaltituderef/) | r/w | Hämtar eller anger GPS‑höjden som används som referenshöjd. |
| gps_area_information | System.Byte | r/w | Hämtar eller anger GPS-områdesinformation. |
| gps_date_stamp | string | r/w | Hämtar eller anger GPS-teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). |
| gps_dest_bearing | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-riktning mot destinationspunkten. |
| gps_dest_bearing_ref | string | r/w | Hämtar eller anger GPS-referensen som används för att ange riktning mot destinationspunkten. |
| gps_dest_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-avståndet till destinationspunkten. |
| gps_dest_distance_ref | string | r/w | Hämtar eller anger GPS-enheten som används för att uttrycka avståndet till destinationspunkten. |
| gps_dest_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-latituden för destinationspunkten. |
| gps_dest_latitude_ref | string | r/w | Hämtar eller anger GPS-värdet som indikerar om latituden för destinationspunkten är nordlig eller sydlig latitud. |
| gps_dest_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-longituden för destinationspunkten. |
| gps_dest_longitude_ref | string | r/w | Hämtar eller anger GPS-värdet som indikerar om longituden för destinationspunkten är östlig eller västlig longitud. |
| gps_differential | int | r/w | Hämtar eller anger ett GPS-värde som indikerar om differentialkorrektion tillämpas på GPS-mottagaren. |
| gps_img_direction | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-riktningen för bilden när den togs. |
| gps_img_direction_ref | string | r/w | Hämtar eller anger GPS-referensen för att ange bildens riktning när den tas. |
| gps_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-latituden. |
| gps_latitude_ref | string | r/w | Hämtar eller anger om GPS-latituden är nordlig eller sydlig. |
| gps_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-longituden. |
| gps_longitude_ref | string | r/w | Hämtar eller anger GPS-longituden är östlig eller västlig longitud. |
| gps_map_datum | string | r/w | Hämtar eller anger GPS:s geodetiska undersökningsdata som används av GPS-mottagaren. |
| gps_measure_mode | string | r/w | Hämtar eller anger GPS-mätningsläget. |
| gps_processing_method | System.Byte | r/w | Hämtar eller anger GPS-teckensträngen som registrerar namnet på metoden som används för positionsbestämning. |
| gps_satellites | string | r/w | Hämtar eller anger GPS-satelliterna som används för mätningar. |
| gps_speed | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger hastigheten för GPS-mottagarens rörelse. |
| gps_speed_ref | string | r/w | Hämtar eller anger enheten som används för att uttrycka GPS-mottagarens rörelsehastighet. |
| gps_status | string | r/w | Hämtar eller anger statusen för GPS-mottagaren när bilden spelas in. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger taggar som endast tillhör GPS‑avsnittet. |
| gps_timestamp | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-tiden som UTC (Coordinated Universal Time). |
| gps_track | string | r/w | Hämtar eller anger riktningen för GPS-mottagarens rörelse. |
| gps_track_ref | string | r/w | Hämtar eller anger referensen för att ange riktningen för GPS-mottagarens rörelse. |
| gps_version_id | System.Byte | r/w | Hämtar eller anger GPS-versionens identifierare. |
| gpsdop | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS DOP (data degree of precision). |
| image_unique_id | string | r/w | Hämtar eller anger bildens unika identifierare. |
| is_big_endian | bool | r/w | Hämtar eller anger ett värde som indikerar om EXIF-data för strömmen som skapats från är big endian. |
| iso_speed | int | r/w | Hämtar eller anger ISO-hastighet |
| iso_speed_latitude_yyy | int | r/w | Hämtar eller anger ISO-hastighetens latitud yyy-värde för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| iso_speed_latitude_zzz | int | r/w | Hämtar eller anger ISO-hastighetens latitud zzz-värde för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| iso_speed_value | int | r/w | Hämtar eller anger iso-hastighetsvärdet. |
| lens_make | string | r/w | Hämtar eller anger tillverkaren av linsen. |
| lens_model | string | r/w | Hämtar eller anger linsmodellen. |
| lens_serial_number | string | r/w | Hämtar eller anger linsens serienummer. |
| lens_specification | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger linsens specifikation |
| light_source | [ExifLightSource](/imaging/python-net/aspose.imaging.exif.enums/exiflightsource/) | r/w | Hämtar eller anger ljuskällan. |
| make | string | r/w | Hämtar tillverkaren av inspelningsutrustningen. |
| maker_note_data | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r | Hämtar tillverkarens noteringsdata. |
| maker_note_raw_data | System.Byte | r/w | Hämtar eller anger den råa tillverkarens noteringsdata. |
| [maker_notes](#maker_notes1) | [MakerNote[]](/imaging/python-net/aspose.imaging.exif/makernote/) | r | Hämtar tillverkarens anteckningar. |
| max_aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger det maximala bländarvärdet. |
| metering_mode | [ExifMeteringMode](/imaging/python-net/aspose.imaging.exif.enums/exifmeteringmode/) | r/w | Hämtar eller anger mätarläget. |
| oecf | System.Byte | r/w | Hämtar eller anger den Opto-Electric Conversion Function (OECF) som specificeras i ISO 14524. |
| orientation | [ExifOrientation](/imaging/python-net/aspose.imaging.exif.enums/exiforientation/) | r/w | Hämtar eller anger orienteringen. |
| photographic_sensitivity | int | r/w | Hämtar eller anger den fotografiska känsligheten. |
| pixel_x_dimension | int | r/w | Hämtar eller anger pixelns x-dimension. |
| pixel_y_dimension | int | r/w | Hämtar eller anger pixelns y-dimension. |
| properties | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar). |
| recommended_exposure_index | int | r/w | Hämtar eller anger det rekommenderade exponeringsindexet. |
| related_sound_file | string | r/w | Hämtar eller anger den relaterade ljudfilen. |
| saturation | [ExifSaturation](/imaging/python-net/aspose.imaging.exif.enums/exifsaturation/) | r/w | Hämtar eller anger mättnaden. |
| scene_capture_type | [ExifSceneCaptureType](/imaging/python-net/aspose.imaging.exif.enums/exifscenecapturetype/) | r/w | Hämtar eller anger scenupptagningstypen. |
| scene_type | System.Byte | r/w | Hämtar eller anger scenens typ. |
| sensing_method | [ExifSensingMethod](/imaging/python-net/aspose.imaging.exif.enums/exifsensingmethod/) | r/w | Hämtar eller anger avkänningsmetoden. |
| sensitivity_type | int | r/w | Hämtar eller anger känslighetstypen. |
| sharpness | int | r/w | Hämtar eller anger skärpan. |
| shutter_speed_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Hämtar eller anger slutartidsvärdet. |
| spatial_frequency_response | System.Byte | r/w | Hämtar eller anger den spatiala frekvensresponsen. |
| spectral_sensitivity | string | r/w | Hämtar eller anger den spektrala känsligheten. |
| standard_output_sensitivity | int | r/w | Hämtar eller anger standardutgångskänsligheten |
| subject_area | int[] | r/w | Hämtar eller anger ämnesområdet. |
| subject_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger ämnesavståndet. |
| subject_distance_range | [ExifSubjectDistanceRange](/imaging/python-net/aspose.imaging.exif.enums/exifsubjectdistancerange/) | r/w | Hämtar eller anger intervallet för ämnesavståndet. |
| subject_location | int[] | r/w | Hämtar eller anger ämnesplatsen. |
| subsec_time | string | r/w | Hämtar eller anger bråkdelen av sekunder för DateTime-taggen. |
| subsec_time_digitized | string | r/w | Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen. |
| subsec_time_original | string | r/w | Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen. |
| thumbnail | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r/w | Hämtar eller anger miniatyrbilden. |
| user_comment | string | r/w | Hämtar eller anger användarkommentaren. |
| white_balance | [ExifWhiteBalance](/imaging/python-net/aspose.imaging.exif.enums/exifwhitebalance/) | r/w | Hämtar eller anger vitbalansen. |
| white_point | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger kromatiken för bildens vita punkt. |
| x_resolution | int | r/w | Hämtar eller anger x-upplösningen. |
| y_resolution | int | r/w | Hämtar eller anger y-upplösningen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tag_value(key)](#get_tag_value_key_1) | Hämtar taggvärdet. |
| [load_from_bytes(binary_data)](#load_from_bytes_binary_data_2) | Skapar en ny instans av klassen [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) genom att ladda den från bytearrayen. |
| [remove_tag(tag)](#remove_tag_tag_3) | Ta bort tagg från behållare |
| [remove_tag(tag_id)](#remove_tag_tag_id_4) | Ta bort tagg från behållare |
| [remove_tag_id(tag_id)](#remove_tag_id_tag_id_5) | Ta bort tagg från behållare |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

Initierar en ny instans av [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) klassen.

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

Initierar en ny instans av [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) klassen med data från en array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | De vanliga taggarna. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | EXIF-taggarna. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | GPS-taggarna. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

Initierar en ny instans av [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) klassen med data från en array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Array av EXIF-taggar tillsammans med vanliga och GPS-taggar. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_4}


```
 ExifData(exifdata) 
```

Initierar en ny instans av [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) klassen med data från en array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exifdata | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Array av EXIF-taggar tillsammans med vanliga och GPS-taggar. |

### Property: maker_notes {#maker_notes1}

Hämtar tillverkarens anteckningar.

**See also:**

**[Example # 1](#example_222)**: Access camera manufacturer maker notes in Jpeg image.


### Method: get_tag_value(key) {#get_tag_value_key_1}


```
 get_tag_value(key) 
```

Hämtar taggvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | Taggnyckeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | TiffDataType |


### Method: load_from_bytes(binary_data)  [static] {#load_from_bytes_binary_data_2}


```
 load_from_bytes(binary_data) 
```

Skapar en ny instans av klassen [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) genom att ladda den från bytearrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| binary_data | System.Byte | De binära data. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Den laddade ExifData‑instansen. |


### Method: remove_tag(tag) {#remove_tag_tag_3}


```
 remove_tag(tag) 
```

Ta bort tagg från behållare

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | Taggen att ta bort |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_4}


```
 remove_tag(tag_id) 
```

Ta bort tagg från behållare

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_id | int | Taggidentifieraren att ta bort. |

### Method: remove_tag_id(tag_id) {#remove_tag_id_tag_id_5}


```
 remove_tag_id(tag_id) 
```

Ta bort tagg från behållare

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_id | int | Taggidentifieraren att ta bort. |

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

