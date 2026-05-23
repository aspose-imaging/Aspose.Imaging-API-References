---
title: "Classe ExifData"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifData

**Inheritance:** IImageMetadataFormat, TiffDataTypeController

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [ExifData()](#ExifData__1) | Inizializza una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | Inizializza una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) con dati da un array |
| [ExifData(exifdata)](#ExifData_exifdata_3) | Inizializza una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) con dati da un array |
| [ExifData(exifdata)](#ExifData_exifdata_4) | Inizializza una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) con dati da un array |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il valore dell'apertura. |
| body_serial_number | string | r/w | Ottiene o imposta il numero di serie del corpo della fotocamera. |
| brightness_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Ottiene o imposta il valore della luminosità. |
| camera_owner_name | string | r/w | Ottiene o imposta il nome del proprietario della fotocamera |
| cfa_pattern | System.Byte | r/w | Ottiene o imposta il modello CFA. |
| color_space | [ExifColorSpace](/imaging/python-net/aspose.imaging.exif.enums/exifcolorspace/) | r/w | Ottiene o imposta lo spazio colore. |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta i tag, che appartengono alla sezione comune. Questo vale solo per le immagini jpeg; nel formato tiff vengono utilizzate tiffOptions al suo posto |
| components_configuration | System.Byte | r/w | Ottiene o imposta la configurazione dei componenti. |
| compressed_bits_per_pixel | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta i bit compressi per pixel. |
| contrast | [ExifContrast](/imaging/python-net/aspose.imaging.exif.enums/exifcontrast/) | r/w | Ottiene o imposta il contrasto. |
| custom_rendered | [ExifCustomRendered](/imaging/python-net/aspose.imaging.exif.enums/exifcustomrendered/) | r/w | Ottiene o imposta il rendering personalizzato. |
| date_time_digitized | string | r/w | Ottiene o imposta la data e ora di digitalizzazione. |
| date_time_original | string | r/w | Ottiene o imposta la data e ora originali. |
| device_setting_description | System.Byte | r/w | Ottiene o imposta la descrizione delle impostazioni del dispositivo |
| digital_zoom_ratio | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il rapporto di zoom digitale. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta i tag che appartengono solo alla sezione EXIF. |
| exif_version | System.Byte | r/w | Ottiene o imposta la versione EXIF. |
| exposure_bias_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Ottiene o imposta il valore del bias di esposizione. |
| exposure_index | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'indice di esposizione. |
| exposure_mode | [ExifExposureMode](/imaging/python-net/aspose.imaging.exif.enums/exifexposuremode/) | r/w | Ottiene o imposta la modalità di esposizione. |
| exposure_program | [ExifExposureProgram](/imaging/python-net/aspose.imaging.exif.enums/exifexposureprogram/) | r/w | Ottiene o imposta il programma di esposizione. |
| exposure_time | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il tempo di esposizione. |
| f_number | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il numero F. |
| file_source | [ExifFileSource](/imaging/python-net/aspose.imaging.exif.enums/exiffilesource/) | r/w | Ottiene o imposta il tipo di origine del file. |
| flash | [ExifFlash](/imaging/python-net/aspose.imaging.exif.enums/exifflash/) | r/w | Ottiene o imposta il flash. |
| flash_energy | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'energia del flash. |
| flashpix_version | System.Byte | r/w | Ottiene o imposta la versione flash pix. |
| focal_length | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la lunghezza focale. |
| focal_length_in_35_mm_film | int | r/w | Ottiene o imposta la lunghezza focale nel film da 35 mm. |
| focal_plane_resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Ottiene o imposta l'unità di risoluzione del piano focale. |
| focal_plane_x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione X del piano focale. |
| focal_plane_y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione Y del piano focale. |
| gain_control | [ExifGainControl](/imaging/python-net/aspose.imaging.exif.enums/exifgaincontrol/) | r/w | Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine. |
| gamma | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il gamma. |
| gps_altitude | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'altitudine GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/imaging/python-net/aspose.imaging.exif.enums/exifgpsaltituderef/) | r/w | Ottiene o imposta l'altitudine GPS usata come altitudine di riferimento. |
| gps_area_information | System.Byte | r/w | Ottiene o imposta le informazioni sull'area GPS. |
| gps_date_stamp | string | r/w | Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale). |
| gps_dest_bearing | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'azimut GPS verso il punto di destinazione. |
| gps_dest_bearing_ref | string | r/w | Ottiene o imposta il riferimento GPS usato per fornire l'azimut verso il punto di destinazione. |
| gps_dest_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la distanza GPS al punto di destinazione. |
| gps_dest_distance_ref | string | r/w | Ottiene o imposta l'unità GPS usata per esprimere la distanza al punto di destinazione. |
| gps_dest_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la latitudine GPS del punto di destinazione. |
| gps_dest_latitude_ref | string | r/w | Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud. |
| gps_dest_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la longitudine GPS del punto di destinazione. |
| gps_dest_longitude_ref | string | r/w | Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest. |
| gps_differential | int | r/w | Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS. |
| gps_img_direction | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la direzione GPS dell'immagine al momento della cattura. |
| gps_img_direction_ref | string | r/w | Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura. |
| gps_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la latitudine GPS. |
| gps_latitude_ref | string | r/w | Ottiene o imposta se la latitudine GPS è nord o sud. |
| gps_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la longitudine GPS. |
| gps_longitude_ref | string | r/w | Ottiene o imposta la longitudine GPS (est o ovest). |
| gps_map_datum | string | r/w | Ottiene o imposta i dati di rilevamento geodetico GPS utilizzati dal ricevitore GPS. |
| gps_measure_mode | string | r/w | Ottiene o imposta la modalità di misurazione GPS. |
| gps_processing_method | System.Byte | r/w | Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo utilizzato per la ricerca della posizione. |
| gps_satellites | string | r/w | Ottiene o imposta i satelliti GPS utilizzati per le misurazioni. |
| gps_speed | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la velocità del movimento del ricevitore GPS. |
| gps_speed_ref | string | r/w | Ottiene o imposta l'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS. |
| gps_status | string | r/w | Ottiene o imposta lo stato del ricevitore GPS al momento della registrazione dell'immagine. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta i tag, che appartengono solo alla sezione GPS. |
| gps_timestamp | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'ora GPS come UTC (Tempo Coordinato Universale). |
| gps_track | string | r/w | Ottiene o imposta la direzione del movimento del ricevitore GPS. |
| gps_track_ref | string | r/w | Ottiene o imposta il riferimento per indicare la direzione del movimento del ricevitore GPS. |
| gps_version_id | System.Byte | r/w | Ottiene o imposta l'identificatore di versione GPS. |
| gpsdop | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il DOP GPS (grado di precisione dei dati). |
| image_unique_id | string | r/w | Ottiene o imposta l'identificatore unico dell'immagine. |
| is_big_endian | bool | r/w | Ottiene o imposta un valore che indica se i dati EXIF del flusso creati sono big endian. |
| iso_speed | int | r/w | Ottiene o imposta la velocità ISO |
| iso_speed_latitude_yyy | int | r/w | Ottiene o imposta il valore della latitudine yyy della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| iso_speed_latitude_zzz | int | r/w | Ottiene o imposta il valore della latitudine zzz della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| iso_speed_value | int | r/w | Ottiene o imposta il valore della velocità ISO. |
| lens_make | string | r/w | Ottiene o imposta il produttore dell'obiettivo. |
| lens_model | string | r/w | Ottiene o imposta il modello dell'obiettivo. |
| lens_serial_number | string | r/w | Ottiene o imposta il numero di serie dell'obiettivo. |
| lens_specification | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la specifica dell'obiettivo |
| light_source | [ExifLightSource](/imaging/python-net/aspose.imaging.exif.enums/exiflightsource/) | r/w | Ottiene o imposta la sorgente luminosa. |
| make | string | r/w | Ottiene il produttore dell'attrezzatura di registrazione. |
| maker_note_data | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r | Ottiene i dati delle note del produttore. |
| maker_note_raw_data | System.Byte | r/w | Ottiene o imposta i dati grezzi delle note del produttore. |
| [maker_notes](#maker_notes1) | [MakerNote[]](/imaging/python-net/aspose.imaging.exif/makernote/) | r | Ottiene le note del produttore. |
| max_aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il valore dell'apertura massima. |
| metering_mode | [ExifMeteringMode](/imaging/python-net/aspose.imaging.exif.enums/exifmeteringmode/) | r/w | Ottiene o imposta la modalità di misurazione. |
| oecf | System.Byte | r/w | Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524. |
| orientation | [ExifOrientation](/imaging/python-net/aspose.imaging.exif.enums/exiforientation/) | r/w | Ottiene o imposta l'orientamento. |
| photographic_sensitivity | int | r/w | Ottiene o imposta la sensibilità fotografica. |
| pixel_x_dimension | int | r/w | Ottiene o imposta la dimensione x del pixel. |
| pixel_y_dimension | int | r/w | Ottiene o imposta la dimensione y del pixel. |
| properties | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS). |
| recommended_exposure_index | int | r/w | Ottiene o imposta l'indice di esposizione consigliato. |
| related_sound_file | string | r/w | Ottiene o imposta il file audio correlato. |
| saturation | [ExifSaturation](/imaging/python-net/aspose.imaging.exif.enums/exifsaturation/) | r/w | Ottiene o imposta la saturazione. |
| scene_capture_type | [ExifSceneCaptureType](/imaging/python-net/aspose.imaging.exif.enums/exifscenecapturetype/) | r/w | Ottiene o imposta il tipo di acquisizione della scena. |
| scene_type | System.Byte | r/w | Ottiene o imposta il tipo di scena. |
| sensing_method | [ExifSensingMethod](/imaging/python-net/aspose.imaging.exif.enums/exifsensingmethod/) | r/w | Ottiene o imposta il metodo di rilevamento. |
| sensitivity_type | int | r/w | Ottiene o imposta il tipo di sensibilità. |
| sharpness | int | r/w | Ottiene o imposta la nitidezza. |
| shutter_speed_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Ottiene o imposta il valore della velocità dell'otturatore. |
| spatial_frequency_response | System.Byte | r/w | Ottiene o imposta la risposta in frequenza spaziale. |
| spectral_sensitivity | string | r/w | Ottiene o imposta la sensibilità spettrale. |
| standard_output_sensitivity | int | r/w | Ottiene o imposta la sensibilità di uscita standard |
| subject_area | int[] | r/w | Ottiene o imposta l'area del soggetto. |
| subject_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la distanza del soggetto. |
| subject_distance_range | [ExifSubjectDistanceRange](/imaging/python-net/aspose.imaging.exif.enums/exifsubjectdistancerange/) | r/w | Ottiene o imposta l'intervallo di distanza del soggetto. |
| subject_location | int[] | r/w | Ottiene o imposta la posizione del soggetto. |
| subsec_time | string | r/w | Ottiene o imposta le frazioni di secondo per il tag DateTime. |
| subsec_time_digitized | string | r/w | Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized. |
| subsec_time_original | string | r/w | Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal. |
| thumbnail | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r/w | Ottiene o imposta l'immagine miniatura. |
| user_comment | string | r/w | Ottiene o imposta il commento dell'utente. |
| white_balance | [ExifWhiteBalance](/imaging/python-net/aspose.imaging.exif.enums/exifwhitebalance/) | r/w | Ottiene o imposta il bilanciamento del bianco. |
| white_point | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la cromaticità del punto bianco dell'immagine. |
| x_resolution | int | r/w | Ottiene o imposta la risoluzione x. |
| y_resolution | int | r/w | Ottiene o imposta la risoluzione y. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_tag_value(key)](#get_tag_value_key_1) | Ottiene il valore del tag. |
| [load_from_bytes(binary_data)](#load_from_bytes_binary_data_2) | Crea una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) caricandola dall'array di byte. |
| [remove_tag(tag)](#remove_tag_tag_3) | Rimuovi il tag dal contenitore |
| [remove_tag(tag_id)](#remove_tag_tag_id_4) | Rimuovi il tag dal contenitore |
| [remove_tag_id(tag_id)](#remove_tag_id_tag_id_5) | Rimuovi il tag dal contenitore |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

Inizializza una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/)

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

Inizializza una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) con dati da un array

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | I tag comuni. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | I tag EXIF. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | I tag GPS. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

Inizializza una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) con dati da un array

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Array di tag EXIF insieme a tag comuni e GPS. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_4}


```
 ExifData(exifdata) 
```

Inizializza una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) con dati da un array

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| exifdata | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Array di tag EXIF insieme a tag comuni e GPS. |

### Property: maker_notes {#maker_notes1}

Ottiene le note del produttore.

**See also:**

**[Example # 1](#example_222)**: Access camera manufacturer maker notes in Jpeg image.


### Method: get_tag_value(key) {#get_tag_value_key_1}


```
 get_tag_value(key) 
```

Ottiene il valore del tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | La chiave del tag. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Il TiffDataType |


### Method: load_from_bytes(binary_data)  [static] {#load_from_bytes_binary_data_2}


```
 load_from_bytes(binary_data) 
```

Crea una nuova istanza della classe [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) caricandola dall'array di byte.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| binary_data | System.Byte | I dati binari. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | L'istanza ExifData caricata. |


### Method: remove_tag(tag) {#remove_tag_tag_3}


```
 remove_tag(tag) 
```

Rimuovi il tag dal contenitore

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | Il tag da rimuovere |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_4}


```
 remove_tag(tag_id) 
```

Rimuovi il tag dal contenitore

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_id | int | L'identificatore del tag da rimuovere. |

### Method: remove_tag_id(tag_id) {#remove_tag_id_tag_id_5}


```
 remove_tag_id(tag_id) 
```

Rimuovi il tag dal contenitore

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_id | int | L'identificatore del tag da rimuovere. |

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

