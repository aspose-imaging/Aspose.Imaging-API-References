---
title: "Класс JpegExifData"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.JpegExifData

**Inheritance:** IImageMetadataFormat, ExifData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | Инициализирует новый экземпляр класса [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/). |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | Инициализирует новый экземпляр класса [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) с данными из массива. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | Инициализирует новый экземпляр класса [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) с данными из массива. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_4) | Инициализирует новый экземпляр класса [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) с данными из массива. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | Максимальный разрешенный размер сегмента EXIF в байтах. |
| aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает значение диафрагмы. |
| artist | string | r/w | Получает или задает исполнителя. |
| bits_per_sample | int[] | r/w | Получает или задает количество бит на образец. |
| body_serial_number | string | r/w | Получает или задает серийный номер корпуса камеры. |
| brightness_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Получает или задает значение яркости. |
| camera_owner_name | string | r/w | Получает или задает имя владельца камеры |
| cfa_pattern | System.Byte | r/w | Получает или задает шаблон CFA. |
| color_space | [ExifColorSpace](/imaging/python-net/aspose.imaging.exif.enums/exifcolorspace/) | r/w | Получает или задает цветовое пространство. |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает теги, которые относятся к общей секции. Это применимо только к jpeg‑изображениям, в формате tiff вместо этого используются tiffOptions |
| components_configuration | System.Byte | r/w | Получает или задает конфигурацию компонентов. |
| compressed_bits_per_pixel | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает сжатые биты на пиксель. |
| сжатие | int | r/w | Получает или задает сжатие. |
| contrast | [ExifContrast](/imaging/python-net/aspose.imaging.exif.enums/exifcontrast/) | r/w | Получает или задает контраст. |
| авторские права | string | r/w | Получает или задает авторские права. |
| custom_rendered | [ExifCustomRendered](/imaging/python-net/aspose.imaging.exif.enums/exifcustomrendered/) | r/w | Получает или задает пользовательскую отрисовку. |
| дата_время | string | r/w | Получает или задает дату и время. |
| date_time_digitized | string | r/w | Получает или задает дату и время оцифровки. |
| date_time_original | string | r/w | Получает или задает оригинальную дату и время. |
| device_setting_description | System.Byte | r/w | Получает или задает описание настроек устройства |
| digital_zoom_ratio | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает коэффициент цифрового увеличения. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает теги, которые принадлежат только разделу EXIF. |
| exif_version | System.Byte | r/w | Получает или задает версию EXIF. |
| exposure_bias_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Получает или задает значение смещения экспозиции. |
| exposure_index | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает индекс экспозиции. |
| exposure_mode | [ExifExposureMode](/imaging/python-net/aspose.imaging.exif.enums/exifexposuremode/) | r/w | Получает или задает режим экспозиции. |
| exposure_program | [ExifExposureProgram](/imaging/python-net/aspose.imaging.exif.enums/exifexposureprogram/) | r/w | Получает или задает программу экспозиции. |
| exposure_time | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает время экспозиции. |
| f_number | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает значение F-числа. |
| file_source | [ExifFileSource](/imaging/python-net/aspose.imaging.exif.enums/exiffilesource/) | r/w | Получает или задает тип источника файла. |
| flash | [ExifFlash](/imaging/python-net/aspose.imaging.exif.enums/exifflash/) | r/w | Получает или задает вспышку. |
| flash_energy | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает энергию вспышки. |
| flashpix_version | System.Byte | r/w | Получает или задает версию flash pix. |
| focal_length | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает фокусное расстояние. |
| focal_length_in_35_mm_film | int | r/w | Получает или задает фокусное расстояние в пленке 35 мм. |
| focal_plane_resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Получает или задает единицу разрешения фокальной плоскости. |
| focal_plane_x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси X фокальной плоскости. |
| focal_plane_y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси Y фокальной плоскости. |
| gain_control | [ExifGainControl](/imaging/python-net/aspose.imaging.exif.enums/exifgaincontrol/) | r/w | Получает или задает степень общей регулировки усиления изображения. |
| gamma | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает гамму. |
| gps_altitude | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает высоту GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/imaging/python-net/aspose.imaging.exif.enums/exifgpsaltituderef/) | r/w | Получает или задает высоту GPS, используемую в качестве эталонной высоты. |
| gps_area_information | System.Byte | r/w | Получает или задает информацию о области GPS. |
| gps_date_stamp | string | r/w | Получает или задает строку GPS, содержащую информацию о дате и времени записи относительно UTC (координированного всемирного времени). |
| gps_dest_bearing | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает азимут GPS к целевой точке. |
| gps_dest_bearing_ref | string | r/w | Получает или задает ссылку GPS, используемую для указания азимута к целевой точке. |
| gps_dest_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает расстояние GPS до целевой точки. |
| gps_dest_distance_ref | string | r/w | Получает или задает единицу измерения GPS, используемую для выражения расстояния до целевой точки. |
| gps_dest_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает широту GPS целевой точки. |
| gps_dest_latitude_ref | string | r/w | Получает или задает значение GPS, указывающее, находится ли широта целевой точки в северном или южном полушарии. |
| gps_dest_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает долготу GPS целевой точки. |
| gps_dest_longitude_ref | string | r/w | Получает или задает значение GPS, указывающее, находится ли долгота целевой точки в восточном или западном полушарии. |
| gps_differential | int | r/w | Получает или задает значение GPS, указывающее, применяется ли дифференциальная коррекция к GPS-приемнику. |
| gps_img_direction | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает направление GPS изображения при его захвате. |
| gps_img_direction_ref | string | r/w | Получает или задает ссылку GPS, используемую для указания направления изображения при его захвате. |
| gps_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает широту GPS. |
| gps_latitude_ref | string | r/w | Получает или задает, является ли широта GPS северной или южной. |
| gps_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает долготу GPS. |
| gps_longitude_ref | string | r/w | Получает или задает, является ли долгота GPS восточной или западной. |
| gps_map_datum | string | r/w | Получает или задает геодезические данные GPS, используемые GPS‑приемником. |
| gps_measure_mode | string | r/w | Получает или задает режим измерения GPS. |
| gps_processing_method | System.Byte | r/w | Получает или задает строку GPS, содержащую название метода, используемого для определения местоположения. |
| gps_satellites | string | r/w | Получает или задает спутники GPS, используемые для измерений. |
| gps_speed | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает скорость движения GPS‑приемника. |
| gps_speed_ref | string | r/w | Получает или задает единицу измерения скорости движения GPS‑приемника. |
| gps_status | string | r/w | Получает или задает статус GPS‑приемника при записи изображения. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает теги, относящиеся только к разделу GPS. |
| gps_timestamp | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает время GPS в формате UTC (координированное всемирное время). |
| gps_track | string | r/w | Получает или задает направление движения GPS‑приемника. |
| gps_track_ref | string | r/w | Получает или задает ссылку, определяющую направление движения GPS‑приемника. |
| gps_version_id | System.Byte | r/w | Получает или задает идентификатор версии GPS. |
| gpsdop | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает GPS DOP (степень точности данных). |
| описание_изображения | string | r/w | Получает или задает описание изображения. |
| длина_изображения | int | r/w | Получает или задает длину изображения. |
| image_unique_id | string | r/w | Получает или задает уникальный идентификатор изображения. |
| ширина_изображения | int | r/w | Получает или задает ширину изображения. |
| is_big_endian | bool | r/w | Получает или задает значение, указывающее, является ли поток данных EXIF, созданный из, big endian. |
| iso_speed | int | r/w | Получает или задает значение ISO‑скорости. |
| iso_speed_latitude_yyy | int | r/w | Получает или задает значение широты ISO‑скорости yyy камеры или входного устройства, определённое в ISO 12232. |
| iso_speed_latitude_zzz | int | r/w | Получает или задает значение широты ISO‑скорости zzz камеры или входного устройства, определённое в ISO 12232. |
| iso_speed_value | int | r/w | Получает или задает значение ISO‑скорости. |
| lens_make | string | r/w | Получает или задает производителя объектива. |
| lens_model | string | r/w | Получает или задает модель объектива. |
| lens_serial_number | string | r/w | Получает или задает серийный номер объектива. |
| lens_specification | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает спецификацию объектива |
| light_source | [ExifLightSource](/imaging/python-net/aspose.imaging.exif.enums/exiflightsource/) | r/w | Получает или задает источник света. |
| make | string | r/w | Получает или задает производителя записывающего оборудования. |
| maker_note_data | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r | Получает данные примечаний производителя. |
| maker_note_raw_data | System.Byte | r/w | Получает или задает необработанные данные примечаний производителя. |
| maker_notes | [MakerNote[]](/imaging/python-net/aspose.imaging.exif/makernote/) | r | Получает примечания производителя. |
| max_aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает значение максимальной диафрагмы. |
| metering_mode | [ExifMeteringMode](/imaging/python-net/aspose.imaging.exif.enums/exifmeteringmode/) | r/w | Получает или задает режим измерения. |
| модель | string | r/w | Получает или задает модель. |
| oecf | System.Byte | r/w | Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524. |
| orientation | [ExifOrientation](/imaging/python-net/aspose.imaging.exif.enums/exiforientation/) | r/w | Получает или задает ориентацию. |
| photographic_sensitivity | int | r/w | Получает или задает фоточувствительность. |
| фотометрическая_интерпретация | int | r/w | Получает или задает фотометрическую интерпретацию. |
| pixel_x_dimension | int | r/w | Получает или задает размер пикселя по оси X. |
| pixel_y_dimension | int | r/w | Получает или задает размер пикселя по оси Y. |
| планарная_конфигурация | int | r/w | Получает или задает планарную конфигурацию. |
| primary_chromaticities | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает хроматичность трех основных цветов изображения. |
| properties | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает все теги EXIF (включая общие и GPS-теги). |
| recommended_exposure_index | int | r/w | Получает или задает рекомендуемый индекс экспозиции. |
| reference_black_white | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает эталонный черный и белый. |
| related_sound_file | string | r/w | Получает или задает связанный звуковой файл. |
| resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Получает или задает единицу разрешения. |
| образцов_на_пиксель | int | r/w | Получает или задает количество образцов на пиксель. |
| saturation | [ExifSaturation](/imaging/python-net/aspose.imaging.exif.enums/exifsaturation/) | r/w | Получает или задает насыщенность. |
| scene_capture_type | [ExifSceneCaptureType](/imaging/python-net/aspose.imaging.exif.enums/exifscenecapturetype/) | r/w | Получает или задает тип захвата сцены. |
| scene_type | System.Byte | r/w | Получает или задает тип сцены. |
| sensing_method | [ExifSensingMethod](/imaging/python-net/aspose.imaging.exif.enums/exifsensingmethod/) | r/w | Получает или задает метод измерения. |
| sensitivity_type | int | r/w | Получает или задает тип чувствительности. |
| sharpness | int | r/w | Получает или задает резкость. |
| shutter_speed_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Получает или задает значение скорости затвора. |
| программное обеспечение | string | r/w | Получает или задает программное обеспечение. |
| spatial_frequency_response | System.Byte | r/w | Получает или задает пространственную частотную характеристику. |
| spectral_sensitivity | string | r/w | Получает или задает спектральную чувствительность. |
| standard_output_sensitivity | int | r/w | Получает или задает стандартную чувствительность выхода |
| subject_area | int[] | r/w | Получает или задает область объекта. |
| subject_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает расстояние до объекта. |
| subject_distance_range | [ExifSubjectDistanceRange](/imaging/python-net/aspose.imaging.exif.enums/exifsubjectdistancerange/) | r/w | Получает или задает диапазон расстояний до объекта. |
| subject_location | int[] | r/w | Получает или задает местоположение объекта. |
| subsec_time | string | r/w | Получает или задает доли секунды для тега DateTime. |
| subsec_time_digitized | string | r/w | Получает или задает доли секунды для тега DateTimeDigitized. |
| subsec_time_original | string | r/w | Получает или задает доли секунды для тега DateTimeOriginal. |
| thumbnail | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r/w | Получает или задает миниатюрное изображение. |
| transfer_function | int[] | r/w | Получает или задает функцию передачи. |
| user_comment | string | r/w | Получает или задает комментарий пользователя. |
| white_balance | [ExifWhiteBalance](/imaging/python-net/aspose.imaging.exif.enums/exifwhitebalance/) | r/w | Получает или задает баланс белого. |
| white_point | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает хроматичность белой точки изображения. |
| x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси X. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает коэффициенты матрицы для преобразования данных изображения из RGB в YCbCr. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/imaging/python-net/aspose.imaging.exif.enums/exifycbcrpositioning/) | r/w | Получает или задает положение компонентов хроминанс относительно компонента яркости. |
| y_cb_cr_sub_sampling | int[] | r/w | Получает или задает коэффициент дискретизации компонентов хроминанс относительно компонента яркости. |
| y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tag_value(key)](#get_tag_value_key_1) | Получает значение тега. |
| [load_from_bytes(binary_data)](#load_from_bytes_binary_data_2) | Создает новый экземпляр класса [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) путем загрузки его из массива байтов. |
| [remove_tag(tag)](#remove_tag_tag_3) | Удалить тег из контейнера |
| [remove_tag(tag_id)](#remove_tag_tag_id_4) | Удалить тег из контейнера |
| [remove_tag_id(tag_id)](#remove_tag_id_tag_id_5) | Удалить тег из контейнера |
| [serialize_exif_data()](#serialize_exif_data__6) | Сериализует данные EXIF. Записывает значения тегов и их содержимое. Наибольшее влияние на размер оказывает содержимое тега миниатюры. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

Инициализирует новый экземпляр класса [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/).

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

Инициализирует новый экземпляр класса [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) с данными из массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Общие теги. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Теги EXIF. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Теги GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

Инициализирует новый экземпляр класса [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) с данными из массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Массив тегов EXIF вместе с общими тегами и тегами GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_4}


```
 JpegExifData(exifdata) 
```

Инициализирует новый экземпляр класса [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) с данными из массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| exifdata | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Массив тегов EXIF вместе с общими тегами и тегами GPS. |

### Method: get_tag_value(key) {#get_tag_value_key_1}


```
 get_tag_value(key) 
```

Получает значение тега.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | Ключ тега. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Тип TiffDataType |


### Method: load_from_bytes(binary_data)  [static] {#load_from_bytes_binary_data_2}


```
 load_from_bytes(binary_data) 
```

Создает новый экземпляр класса [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) путем загрузки его из массива байтов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| binary_data | System.Byte | Бинарные данные. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Загруженный экземпляр ExifData. |


### Method: remove_tag(tag) {#remove_tag_tag_3}


```
 remove_tag(tag) 
```

Удалить тег из контейнера

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | Тег для удаления |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_4}


```
 remove_tag(tag_id) 
```

Удалить тег из контейнера

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_id | int | Идентификатор тега для удаления. |

### Method: remove_tag_id(tag_id) {#remove_tag_id_tag_id_5}


```
 remove_tag_id(tag_id) 
```

Удалить тег из контейнера

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_id | int | Идентификатор тега для удаления. |

### Method: serialize_exif_data() {#serialize_exif_data__6}


```
 serialize_exif_data() 
```

Сериализует данные EXIF. Записывает значения тегов и их содержимое. Наибольшее влияние на размер оказывает содержимое тега миниатюры.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Сериализованные данные EXIF. |


