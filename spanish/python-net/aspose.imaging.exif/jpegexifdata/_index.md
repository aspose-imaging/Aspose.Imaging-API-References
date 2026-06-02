---
title: "Clase JpegExifData"
type: docs
weight: 40
url: /es/python-net/aspose.imaging.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.JpegExifData

**Inheritance:** IImageMetadataFormat, ExifData

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | Inicializa una nueva instancia de la clase [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/). |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | Inicializa una nueva instancia de la clase [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) con datos del arreglo. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | Inicializa una nueva instancia de la clase [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) con datos del arreglo. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_4) | Inicializa una nueva instancia de la clase [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) con datos del arreglo. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | El tamaño máximo permitido del segmento EXIF en bytes. |
| aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el valor de la apertura. |
| artist | string | r/w | Obtiene o establece el artista. |
| bits_per_sample | int[] | r/w | Obtiene o establece los bits por muestra. |
| body_serial_number | string | r/w | Obtiene o establece el número de serie del cuerpo de la cámara. |
| brightness_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Obtiene o establece el valor de brillo. |
| camera_owner_name | string | r/w | Obtiene o establece el nombre del propietario de la cámara |
| cfa_pattern | System.Byte | r/w | Obtiene o establece el patrón CFA. |
| color_space | [ExifColorSpace](/imaging/python-net/aspose.imaging.exif.enums/exifcolorspace/) | r/w | Obtiene o establece el espacio de color. |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece etiquetas, que pertenecen a la sección común. Esto se aplica solo a imágenes jpeg; en formato tiff se utilizan tiffOptions en su lugar |
| components_configuration | System.Byte | r/w | Obtiene o establece la configuración de componentes. |
| compressed_bits_per_pixel | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece los bits comprimidos por píxel. |
| compresión | int | r/w | Obtiene o establece la compresión. |
| contrast | [ExifContrast](/imaging/python-net/aspose.imaging.exif.enums/exifcontrast/) | r/w | Obtiene o establece el contraste. |
| derechos de autor | string | r/w | Obtiene o establece los derechos de autor. |
| custom_rendered | [ExifCustomRendered](/imaging/python-net/aspose.imaging.exif.enums/exifcustomrendered/) | r/w | Obtiene o establece el renderizado personalizado. |
| fecha_hora | string | r/w | Obtiene o establece la fecha y hora. |
| date_time_digitized | string | r/w | Obtiene o establece la fecha y hora de digitalización. |
| date_time_original | string | r/w | Obtiene o establece la fecha y hora original. |
| device_setting_description | System.Byte | r/w | Obtiene o establece la descripción de la configuración del dispositivo |
| digital_zoom_ratio | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la relación de zoom digital. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece etiquetas que pertenecen solo a la sección EXIF. |
| exif_version | System.Byte | r/w | Obtiene o establece la versión EXIF. |
| exposure_bias_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Obtiene o establece el valor de sesgo de exposición. |
| exposure_index | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el índice de exposición. |
| exposure_mode | [ExifExposureMode](/imaging/python-net/aspose.imaging.exif.enums/exifexposuremode/) | r/w | Obtiene o establece el modo de exposición. |
| exposure_program | [ExifExposureProgram](/imaging/python-net/aspose.imaging.exif.enums/exifexposureprogram/) | r/w | Obtiene o establece el programa de exposición. |
| exposure_time | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el tiempo de exposición. |
| f_number | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el número F. |
| file_source | [ExifFileSource](/imaging/python-net/aspose.imaging.exif.enums/exiffilesource/) | r/w | Obtiene o establece el tipo de origen del archivo. |
| flash | [ExifFlash](/imaging/python-net/aspose.imaging.exif.enums/exifflash/) | r/w | Obtiene o establece el flash. |
| flash_energy | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la energía del flash. |
| flashpix_version | System.Byte | r/w | Obtiene o establece la versión flash pix. |
| focal_length | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la distancia focal. |
| focal_length_in_35_mm_film | int | r/w | Obtiene o establece la distancia focal en película de 35 mm. |
| focal_plane_resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Obtiene o establece la unidad de resolución del plano focal. |
| focal_plane_x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución X del plano focal. |
| focal_plane_y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución Y del plano focal. |
| gain_control | [ExifGainControl](/imaging/python-net/aspose.imaging.exif.enums/exifgaincontrol/) | r/w | Obtiene o establece el grado de ajuste general de ganancia de la imagen. |
| gamma | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la gamma. |
| gps_altitude | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la altitud GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/imaging/python-net/aspose.imaging.exif.enums/exifgpsaltituderef/) | r/w | Obtiene o establece la altitud GPS utilizada como altitud de referencia. |
| gps_area_information | System.Byte | r/w | Obtiene o establece la información del área GPS. |
| gps_date_stamp | string | r/w | Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado). |
| gps_dest_bearing | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la dirección GPS al punto de destino. |
| gps_dest_bearing_ref | string | r/w | Obtiene o establece la referencia GPS utilizada para dar la dirección al punto de destino. |
| gps_dest_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la distancia GPS al punto de destino. |
| gps_dest_distance_ref | string | r/w | Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino. |
| gps_dest_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la latitud GPS del punto de destino. |
| gps_dest_latitude_ref | string | r/w | Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur. |
| gps_dest_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la longitud GPS del punto de destino. |
| gps_dest_longitude_ref | string | r/w | Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste. |
| gps_differential | int | r/w | Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS. |
| gps_img_direction | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la dirección GPS de la imagen cuando fue capturada. |
| gps_img_direction_ref | string | r/w | Obtiene o establece la referencia GPS para dar la dirección de la imagen cuando se captura. |
| gps_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la latitud GPS. |
| gps_latitude_ref | string | r/w | Obtiene o establece si la latitud GPS es norte o sur. |
| gps_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la longitud GPS. |
| gps_longitude_ref | string | r/w | Obtiene o establece si la longitud GPS es este u oeste. |
| gps_map_datum | string | r/w | Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS. |
| gps_measure_mode | string | r/w | Obtiene o establece el modo de medición GPS. |
| gps_processing_method | System.Byte | r/w | Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización. |
| gps_satellites | string | r/w | Obtiene o establece los satélites GPS utilizados para las mediciones. |
| gps_speed | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la velocidad del movimiento del receptor GPS. |
| gps_speed_ref | string | r/w | Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. |
| gps_status | string | r/w | Obtiene o establece el estado del receptor GPS cuando se registra la imagen. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece etiquetas, que pertenecen solo a la sección GPS. |
| gps_timestamp | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado). |
| gps_track | string | r/w | Obtiene o establece la dirección del movimiento del receptor GPS. |
| gps_track_ref | string | r/w | Obtiene o establece la referencia para indicar la dirección del movimiento del receptor GPS. |
| gps_version_id | System.Byte | r/w | Obtiene o establece el identificador de versión GPS. |
| gpsdop | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el DOP GPS (grado de precisión de los datos). |
| descripción_imagen | string | r/w | Obtiene o establece la descripción de la imagen. |
| longitud_imagen | int | r/w | Obtiene o establece la longitud de la imagen. |
| image_unique_id | string | r/w | Obtiene o establece el identificador único de la imagen. |
| anchura_imagen | int | r/w | Obtiene o establece la anchura de la imagen. |
| is_big_endian | bool | r/w | Obtiene o establece un valor que indica si los datos EXIF del flujo creados son big endian. |
| iso_speed | int | r/w | Obtiene o establece la velocidad ISO. |
| iso_speed_latitude_yyy | int | r/w | Obtiene o establece el valor de latitud yyy de la velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232. |
| iso_speed_latitude_zzz | int | r/w | Obtiene o establece el valor de latitud zzz de la velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232. |
| iso_speed_value | int | r/w | Obtiene o establece el valor de velocidad iso. |
| lens_make | string | r/w | Obtiene o establece el fabricante del objetivo. |
| lens_model | string | r/w | Obtiene o establece el modelo del objetivo. |
| lens_serial_number | string | r/w | Obtiene o establece el número de serie del objetivo. |
| lens_specification | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la especificación del objetivo. |
| light_source | [ExifLightSource](/imaging/python-net/aspose.imaging.exif.enums/exiflightsource/) | r/w | Obtiene o establece la fuente de luz. |
| make | string | r/w | Obtiene o establece el fabricante del equipo de grabación. |
| maker_note_data | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r | Obtiene los datos de la nota del fabricante. |
| maker_note_raw_data | System.Byte | r/w | Obtiene o establece los datos sin procesar de la nota del fabricante. |
| maker_notes | [MakerNote[]](/imaging/python-net/aspose.imaging.exif/makernote/) | r | Obtiene las notas del fabricante. |
| max_aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el valor máximo de apertura. |
| metering_mode | [ExifMeteringMode](/imaging/python-net/aspose.imaging.exif.enums/exifmeteringmode/) | r/w | Obtiene o establece el modo de medición. |
| modelo | string | r/w | Obtiene o establece el modelo. |
| oecf | System.Byte | r/w | Obtiene o establece la Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524. |
| orientation | [ExifOrientation](/imaging/python-net/aspose.imaging.exif.enums/exiforientation/) | r/w | Obtiene o establece la orientación. |
| photographic_sensitivity | int | r/w | Obtiene o establece la sensibilidad fotográfica. |
| interpretación_fotométrica | int | r/w | Obtiene o establece la interpretación fotométrica. |
| pixel_x_dimension | int | r/w | Obtiene o establece la dimensión x del píxel. |
| pixel_y_dimension | int | r/w | Obtiene o establece la dimensión y del píxel. |
| configuración_planar | int | r/w | Obtiene o establece la configuración planar. |
| primary_chromaticities | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la cromaticidad de los tres colores primarios de la imagen. |
| properties | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS). |
| recommended_exposure_index | int | r/w | Obtiene o establece el índice de exposición recomendado. |
| reference_black_white | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el negro y blanco de referencia. |
| related_sound_file | string | r/w | Obtiene o establece el archivo de sonido relacionado. |
| resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Obtiene o establece la unidad de resolución. |
| muestras_por_píxel | int | r/w | Obtiene o establece las muestras por píxel. |
| saturation | [ExifSaturation](/imaging/python-net/aspose.imaging.exif.enums/exifsaturation/) | r/w | Obtiene o establece la saturación. |
| scene_capture_type | [ExifSceneCaptureType](/imaging/python-net/aspose.imaging.exif.enums/exifscenecapturetype/) | r/w | Obtiene o establece el tipo de captura de escena. |
| scene_type | System.Byte | r/w | Obtiene o establece el tipo de escena. |
| sensing_method | [ExifSensingMethod](/imaging/python-net/aspose.imaging.exif.enums/exifsensingmethod/) | r/w | Obtiene o establece el método de detección. |
| sensitivity_type | int | r/w | Obtiene o establece el tipo de sensibilidad. |
| sharpness | int | r/w | Obtiene o establece la nitidez. |
| shutter_speed_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Obtiene o establece el valor de velocidad de obturación. |
| software | string | r/w | Obtiene o establece el software. |
| spatial_frequency_response | System.Byte | r/w | Obtiene o establece la respuesta de frecuencia espacial. |
| spectral_sensitivity | string | r/w | Obtiene o establece la sensibilidad espectral. |
| standard_output_sensitivity | int | r/w | Obtiene o establece la sensibilidad de salida estándar |
| subject_area | int[] | r/w | Obtiene o establece el área del sujeto. |
| subject_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la distancia del sujeto. |
| subject_distance_range | [ExifSubjectDistanceRange](/imaging/python-net/aspose.imaging.exif.enums/exifsubjectdistancerange/) | r/w | Obtiene o establece el rango de distancia del sujeto. |
| subject_location | int[] | r/w | Obtiene o establece la ubicación del sujeto. |
| subsec_time | string | r/w | Obtiene o establece las fracciones de segundo para la etiqueta DateTime. |
| subsec_time_digitized | string | r/w | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized. |
| subsec_time_original | string | r/w | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal. |
| thumbnail | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r/w | Obtiene o establece la imagen en miniatura. |
| transfer_function | int[] | r/w | Obtiene o establece la función de transferencia. |
| user_comment | string | r/w | Obtiene o establece el comentario del usuario. |
| white_balance | [ExifWhiteBalance](/imaging/python-net/aspose.imaging.exif.enums/exifwhitebalance/) | r/w | Obtiene o establece el balance de blancos. |
| white_point | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la cromaticidad del punto blanco de la imagen. |
| x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución x. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/imaging/python-net/aspose.imaging.exif.enums/exifycbcrpositioning/) | r/w | Obtiene o establece la posición de los componentes de crominancia en relación con el componente de luminancia. |
| y_cb_cr_sub_sampling | int[] | r/w | Obtiene o establece la proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia. |
| y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución y. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_tag_value(key)](#get_tag_value_key_1) | Obtiene el valor de la etiqueta. |
| [load_from_bytes(binary_data)](#load_from_bytes_binary_data_2) | Crea una nueva instancia de la clase [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) cargándola desde el arreglo de bytes. |
| [remove_tag(tag)](#remove_tag_tag_3) | Eliminar etiqueta del contenedor |
| [remove_tag(tag_id)](#remove_tag_tag_id_4) | Eliminar etiqueta del contenedor |
| [remove_tag_id(tag_id)](#remove_tag_id_tag_id_5) | Eliminar etiqueta del contenedor |
| [serialize_exif_data()](#serialize_exif_data__6) | Serializa los datos EXIF. Escribe los valores y contenidos de las etiquetas. La etiqueta de tamaño que más influye es el contenido de la etiqueta Miniatura. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

Inicializa una nueva instancia de la clase [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/).

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

Inicializa una nueva instancia de la clase [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) con datos del arreglo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Las etiquetas comunes. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Las etiquetas EXIF. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Las etiquetas GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

Inicializa una nueva instancia de la clase [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) con datos del arreglo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Arreglo de etiquetas EXIF junto con etiquetas comunes y GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_4}


```
 JpegExifData(exifdata) 
```

Inicializa una nueva instancia de la clase [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) con datos del arreglo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| exifdata | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Arreglo de etiquetas EXIF junto con etiquetas comunes y GPS. |

### Method: get_tag_value(key) {#get_tag_value_key_1}


```
 get_tag_value(key) 
```

Obtiene el valor de la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | La clave de la etiqueta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | El TiffDataType |


### Method: load_from_bytes(binary_data)  [static] {#load_from_bytes_binary_data_2}


```
 load_from_bytes(binary_data) 
```

Crea una nueva instancia de la clase [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) cargándola desde el arreglo de bytes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| binary_data | System.Byte | Los datos binarios. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | La instancia cargada de ExifData. |


### Method: remove_tag(tag) {#remove_tag_tag_3}


```
 remove_tag(tag) 
```

Eliminar etiqueta del contenedor

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | La etiqueta a eliminar |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_4}


```
 remove_tag(tag_id) 
```

Eliminar etiqueta del contenedor

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_id | int | El identificador de la etiqueta a eliminar. |

### Method: remove_tag_id(tag_id) {#remove_tag_id_tag_id_5}


```
 remove_tag_id(tag_id) 
```

Eliminar etiqueta del contenedor

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_id | int | El identificador de la etiqueta a eliminar. |

### Method: serialize_exif_data() {#serialize_exif_data__6}


```
 serialize_exif_data() 
```

Serializa los datos EXIF. Escribe los valores y contenidos de las etiquetas. La etiqueta de tamaño que más influye es el contenido de la etiqueta Miniatura.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | Los datos EXIF serializados. |


