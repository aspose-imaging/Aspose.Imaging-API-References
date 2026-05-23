---
title: "Enumeración ExifProperties"
type: docs
weight: 190
url: /es/python-net/aspose.imaging.exif/exifproperties/
---

Lista de etiquetas Exif

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifProperties

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| APERTURE_VALUE | El valor de apertura del objetivo. |
| ARTIST | Esta etiqueta registra el nombre del propietario de la cámara, fotógrafo o creador de la imagen. El formato detallado no está especificado, pero se recomienda que la información se escriba como en el ejemplo a continuación para facilitar la interoperabilidad. Cuando el campo se deja vacío, se considera desconocido. Ej.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | El número de bits por componente de imagen. En este estándar cada componente de la imagen tiene 8 bits, por lo que el valor para esta etiqueta es 8. |
| BODY_SERIAL_NUMBER | Contiene el número de serie del cuerpo de la cámara |
| BRIGHTNESS_VALUE | El valor de brillo. |
| CAMERA_OWNER_NAME | Contiene el nombre del propietario de la cámara |
| CFA_PATTERN | Indica el patrón geométrico de la matriz de filtros de color (CFA) del sensor de imagen cuando se utiliza un sensor de área de color de un solo chip. No se aplica a todos los métodos de detección. |
| COLOR_SPACE | La etiqueta de información del espacio de color (ColorSpace) siempre se registra como el especificador del espacio de color. |
| COMPONENTS_CONFIGURATION | La configuración de los componentes. |
| COMPRESSED_BITS_PER_PIXEL | Específico de datos comprimidos; indica los bits comprimidos por píxel. |
| COMPRESIÓN | El esquema de compresión utilizado para los datos de la imagen. Cuando una imagen primaria está comprimida en JPEG, esta designación no es necesaria y se omite. |
| CONTRASTE | Esta etiqueta indica la dirección del procesamiento de contraste aplicado por la cámara al capturar la imagen. |
| DERECHOS DE AUTOR | Información de derechos de autor. En este estándar la etiqueta se usa para<br/>                indicar tanto los derechos de autor del fotógrafo como del editor. Es<br/>                el aviso de derechos de autor de la persona u organización que reclama<br/>                derechos sobre la imagen. La declaración de derechos de autor de Interoperabilidad<br/>                que incluye fecha y derechos debe escribirse en este<br/>                campo; por ejemplo, "Copyright, John Smith, 19xx. All rights<br/>                reserved.". En este estándar el campo registra tanto los<br/>                derechos de autor del fotógrafo como del editor, con cada uno registrado en una<br/>                parte separada de la declaración. Cuando hay una clara distinción<br/>                entre los derechos de autor del fotógrafo y del editor, estos deben<br/>                escribirse en el orden de fotógrafo seguido por los derechos de autor del editor,<br/>                separados por NULL (en este caso, dado que la declaración también termina con<br/>                un NULL, hay dos códigos NULL). Cuando solo se proporciona el derecho de autor del fotógrafo,<br/>                se termina con un código NULL. Cuando solo se proporciona el derecho de autor del editor, la parte del derecho de autor del fotógrafo<br/>                consiste en un espacio seguido de un código NULL de terminación, y luego<br/>                se proporciona el derecho de autor del editor. Cuando el campo se deja en blanco, se<br/>                trata como desconocido. |
| RENDERIZADO_PERSONALIZADO | Esta etiqueta indica el uso de procesamiento especial en los datos de la imagen, como renderizado orientado a la salida. Cuando se realiza procesamiento especial, se espera que el lector desactive o minimice cualquier procesamiento adicional. |
| FECHA_HORA | La fecha y hora de creación de la imagen. En el estándar Exif, es la fecha y hora en que el archivo fue modificado. |
| FECHA_HORA_DIGITALIZADA | La fecha y hora de digitalización. |
| FECHA_HORA_ORIGINAL | La fecha y hora en que se generaron los datos originales de la imagen. |
| DESCRIPCIÓN_DE_CONFIGURACIÓN_DEL_DISPOSITIVO | Esta etiqueta indica información sobre las condiciones de captura de una cámara de modelo particular. La etiqueta se usa solo para indicar las condiciones de captura en el lector. |
| RELACIÓN_DE_ZOOM_DIGITAL | Esta etiqueta indica la relación de zoom digital al capturar la imagen. Si el numerador del valor registrado es 0, esto indica que no se utilizó zoom digital. |
| PUNTERO_EXIF_IFD | Un puntero al Exif IFD. En Interoperabilidad, el Exif IFD tiene la misma estructura que el IFD especificado en TIFF. Sin embargo, normalmente no contiene datos de imagen como ocurre en TIFF. |
| VERSIÓN_EXIF | La versión Exif. |
| VALOR_DE_BIAS_DE_EXPOSICIÓN | El valor de sesgo de exposición. |
| ÍNDICE_DE_EXPOSICIÓN | Indica el índice de exposición seleccionado en la cámara o dispositivo de entrada en el momento en que se captura la imagen. |
| EXPOSURE_MODE | Esta etiqueta indica el modo de exposición configurado cuando se tomó la imagen. En modo de auto‑bracketing, la cámara captura una serie de fotogramas de la misma escena con diferentes ajustes de exposición. |
| EXPOSURE_PROGRAM | La clase del programa utilizado por la cámara para establecer la exposición al tomar la foto. |
| EXPOSURE_TIME | Tiempo de exposición, dado en segundos. |
| FILE_SOURCE | La fuente del archivo. |
| FLASH | Indica el estado del flash cuando se tomó la imagen. |
| FLASHPIX_VERSION | La versión del formato Flashpix compatible con un archivo FPXR. |
| FLASH_ENERGY | Indica la energía del estroboscopio en el momento en que se captura la imagen, medida en Beam Candle Power Seconds (BCPS). |
| FOCAL_LENGTH | La distancia focal real del objetivo, en mm. |
| FOCAL_LENGTH_IN_35_MM_FILM | Esta etiqueta indica la distancia focal equivalente asumiendo una cámara de película de 35 mm, en mm. Un valor de 0 significa que la distancia focal es desconocida. Tenga en cuenta que esta etiqueta difiere de la etiqueta FocalLength. |
| FOCAL_PLANE_RESOLUTION_UNIT | Indica la unidad para medir FocalPlaneXResolution y FocalPlaneYResolution. Este valor es el mismo que ResolutionUnit. |
| FOCAL_PLANE_X_RESOLUTION | Indica el número de píxeles en la dirección del ancho de la imagen (X) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| FOCAL_PLANE_Y_RESOLUTION | Indica el número de píxeles en la dirección de la altura de la imagen (Y) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| F_NUMBER | El número F. |
| GAIN_CONTROL | Esta etiqueta indica el grado de ajuste general de ganancia de la imagen. |
| GAMMA | Valor gamma |
| GPSDOP | Indica el GPS DOP (grado de precisión de los datos). Se escribe un valor HDOP durante la medición bidimensional,<br/>                y PDOP durante la medición tridimensional. |
| GPS_ALTITUDE | Indica la altitud basada en la referencia en GPSAltitudeRef. La altitud se expresa como un valor RATIONAL.<br/>                La unidad de referencia es metros. |
| GPS_ALTITUDE_REF | Indica la altitud utilizada como altitud de referencia. Si la referencia es el nivel del mar y la altitud está por encima del nivel del mar,<br/>                se asigna 0. Si la altitud está por debajo del nivel del mar, se asigna un valor de 1 y la altitud se indica como un valor absoluto en<br/>                la etiqueta GPSAltitude. |
| GPS_AREA_INFORMATION | Una cadena de caracteres que registra el nombre del área GPS. El primer byte indica<br/>                el código de caracteres utilizado, y a continuación sigue el nombre del área GPS. |
| GPS_DATE_STAMP | Una cadena de caracteres que registra la información de fecha y hora relativa a UTC<br/>                (Tiempo Universal Coordinado). El formato es YYYY:MM:DD. |
| GPS_DEST_BEARING | Indica la dirección hacia el punto de destino. El rango de valores es de 0.00 a 359.99. |
| GPS_DEST_BEARING_REF | Indica la referencia utilizada para dar la dirección al punto de destino. 'T' denota dirección verdadera y 'M' es<br/>                dirección magnética. |
| GPS_DEST_DISTANCE | Indica la distancia al punto de destino. |
| GPS_DEST_DISTANCE_REF | Indica la unidad utilizada para expresar la distancia al punto de destino. 'K', 'M' y 'N' representan kilómetros, millas<br/>                y nudos. |
| GPS_DEST_LATITUDE | Indica la latitud del punto de destino. La latitud se expresa como tres valores RATIONAL que dan los<br/>                grados, minutos y segundos, respectivamente. Si la latitud se expresa en grados, minutos y segundos, un formato típico<br/>                sería dd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos<br/>                con hasta dos decimales, el formato sería dd/1,mmmm/100,0/1. |
| GPS_DEST_LATITUDE_REF | Indica si la latitud del punto de destino es latitud norte o sur. El valor ASCII 'N' indica latitud norte<br/>                y 'S' indica latitud sur. |
| GPS_DEST_LONGITUDE | Indica la longitud del punto de destino. La longitud se expresa como tres valores RATIONAL que dan los<br/>                grados, minutos y segundos, respectivamente. Si la longitud se expresa en grados, minutos y segundos, un formato típico<br/>                sería ddd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos<br/>                con hasta dos decimales, el formato sería ddd/1,mmmm/100,0/1. |
| GPS_DEST_LONGITUDE_REF | Indica si la longitud del punto de destino es longitud este u oeste. ASCII 'E' indica longitud este,<br/>                y 'W' indica longitud oeste. |
| GPS_DIFFERENTIAL | Indica si se aplica corrección diferencial al receptor GPS. |
| GPS_IFD_POINTER | El puntero gps ifd. |
| GPS_IMG_DIRECTION | Indica la dirección de la imagen cuando se capturó. El rango de valores es de 0.00 a 359.99. |
| GPS_IMG_DIRECTION_REF | Indica la referencia para proporcionar la dirección de la imagen cuando se captura. 'T' denota dirección verdadera y 'M' es<br/>                dirección magnética. |
| GPS_LATITUDE | Indica la latitud. La latitud se expresa como tres valores RATIONAL que dan los grados, minutos y<br/>                segundos, respectivamente. Si la latitud se expresa en grados, minutos y segundos, un formato típico sería<br/>                dd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos<br/>                decimales, el formato sería dd/1,mmmm/100,0/1. |
| GPS_LATITUDE_REF | Indica si la latitud es norte o sur. |
| GPS_LONGITUDE | Indica la longitud. La longitud se expresa como tres valores RATIONAL que dan los grados, minutos y<br/>                segundos, respectivamente. Si la longitud se expresa en grados, minutos y segundos, un formato típico sería<br/>                ddd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos<br/>                decimales, el formato sería ddd/1,mmmm/100,0/1. |
| GPS_LONGITUDE_REF | Indica si la longitud es este u oeste. |
| GPS_MAP_DATUM | Indica los datos de levantamiento geodésico utilizados por el receptor GPS. |
| GPS_MEASURE_MODE | Indica el modo de medición GPS. - 2- o 3- dimensional. |
| GPS_PROCESSING_METHOD | Una cadena de caracteres que registra el nombre del método utilizado para la localización.<br/>                El primer byte indica el código de caracteres usado, y a continuación sigue el nombre<br/>                del método. |
| GPS_SATELLITES | Indica los satélites GPS utilizados para las mediciones. Esta etiqueta puede usarse para describir el número de satélites,<br/>                su número de identificación, ángulo de elevación, azimut, SNR y otra información en notación ASCII. El formato no está<br/>                especificado. Si el receptor GPS no puede realizar mediciones, el valor de la etiqueta deberá establecerse en NULL. |
| GPS_SPEED | Indica la velocidad del movimiento del receptor GPS. |
| GPS_SPEED_REF | Indica la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. 'K', 'M' y 'N' representan kilómetros por<br/>                hora, millas por hora y nudos. |
| GPS_STATUS | Indica el estado del receptor GPS cuando se registra la imagen. |
| GPS_TIMESTAMP | Indica la hora como UTC (Tiempo Universal Coordinado). La marca de tiempo se expresa como tres valores RATIONAL<br/>                que dan la hora, el minuto y el segundo. |
| GPS_TRACK | Indica la dirección del movimiento del receptor GPS. El rango de valores es de 0,00 a 359,99. |
| GPS_TRACK_REF | Indica la referencia para dar la dirección del movimiento del receptor GPS. 'T' denota dirección verdadera y 'M' es<br/>                dirección magnética. |
| GPS_VERSION_ID | Indica la versión de GPSInfoIFD. |
| IMAGE_DESCRIPTION | Una cadena de caracteres que proporciona el título de la imagen. Puede ser un comentario como "picnic de la empresa 1988" o similar. |
| IMAGE_LENGTH | El número de filas de datos de la imagen. |
| IMAGE_UNIQUE_ID | El identificador único de la imagen. |
| IMAGE_WIDTH | El número de columnas de datos de la imagen, igual al número de píxeles por fila. |
| ISO_SPEED | Información sobre el valor de velocidad ISO según lo definido en ISO 12232. |
| ISO_SPEED_LATITUDE_YYY | Esta etiqueta indica el valor de latitud de velocidad ISO yyy según lo definido en ISO 12232. |
| ISO_SPEED_LATITUDE_ZZZ | Esta etiqueta indica el valor de latitud de velocidad ISO zzz según lo definido en ISO 12232. |
| JPEG_INTERCHANGE_FORMAT | El desplazamiento al byte inicial (SOI) de los datos de miniatura JPEG comprimidos. No se utiliza para los datos JPEG de la imagen principal. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | El número de bytes de los datos de miniatura JPEG comprimidos. No se utiliza para los datos JPEG de la imagen principal. Las miniaturas JPEG no se dividen sino que se registran como una secuencia continua de JPEG desde SOI hasta EOI. No se deben registrar los marcadores Appn y COM. Las miniaturas comprimidas deben registrarse en no más de 64 Kbytes, incluyendo todos los demás datos que se registrarán en APP1. |
| LENS_MAKE | Esta etiqueta registra el fabricante del objetivo. |
| LENS_MODEL | Esta etiqueta registra el nombre del modelo y el número de modelo del objetivo. |
| LENS_SERIAL_NUMBER | Esta etiqueta registra el número de serie del objetivo intercambiable. |
| LENS_SPECIFICATION | Esta etiqueta indica la distancia focal mínima, la distancia focal máxima, el número F mínimo en la distancia focal mínima y el número F mínimo en la distancia focal máxima. |
| LIGHT_SOURCE | El tipo de fuente de luz. |
| MAKE | El fabricante del equipo de captura. Este es el fabricante del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. Cuando el campo se deja en blanco, se considera desconocido. |
| MAKER_NOTE | Una etiqueta para los fabricantes de escritores Exif para registrar cualquier información deseada. El contenido depende del fabricante, pero esta etiqueta no debe usarse para nada que no sea su propósito previsto. |
| MAX_APERTURE_VALUE | El valor máximo de apertura. |
| METERING_MODE | El modo de medición. |
| MODEL | El nombre del modelo o número de modelo del equipo. Este es el nombre o número de modelo del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. Cuando el campo se deja en blanco, se considera desconocido. |
| OECF | Indica la Función de Conversión Opto‑Eléctrica (OECF) especificada en ISO 14524. |
| ORIENTATION | La orientación de la imagen vista en términos de filas y columnas. |
| PHOTOGRAPHIC_SENSITIVITY | Indica la velocidad ISO y la latitud ISO de la cámara o dispositivo de entrada según lo especificado en ISO 12232. |
| PHOTOMETRIC_INTERPRETATION | La composición de los píxeles. |
| PIXEL_X_DIMENSION | Información específica de los datos comprimidos. Cuando se registra un archivo comprimido, el ancho válido de la imagen significativa debe registrarse en esta etiqueta, ya sea que haya datos de relleno o un marcador de reinicio. |
| PIXEL_Y_DIMENSION | Información específica de esos datos comprimidos. Cuando se registra un archivo comprimido, la altura válida de la imagen significativa debe registrarse en esta etiqueta. |
| PLANAR_CONFIGURATION | Indica si los componentes de píxeles se registran en formato chunky o planar. Si este campo no existe, se asume el valor predeterminado de TIFF de 1 (chunky). |
| PRIMARY_CHROMATICITIES | La cromaticidad de los tres colores primarios de la imagen. Normalmente esta etiqueta no es necesaria, porque el espacio de color se especifica en la etiqueta de información del espacio de color ColorSpace. |
| RECOMMENDED_EXPOSURE_INDEX | Indica el índice de exposición recomendado |
| REFERENCE_BLACK_WHITE | El valor del punto negro de referencia y del punto blanco de referencia<br/>                valor. No se proporcionan valores predeterminados en TIFF, pero los valores a continuación se dan como predeterminados aquí.<br/>                El espacio de color se declara<br/>                en una etiqueta de información del espacio de color, con el valor predeterminado<br/>                que brinda las características óptimas de la imagen<br/>                Interoperabilidad estas condiciones |
| RELATED_SOUND_FILE | El archivo de sonido relacionado. |
| RESOLUTION_UNIT | La unidad para medir XResolution y YResolution. La misma unidad se usa para XResolution y YResolution. Si la resolución de la imagen es desconocida, se designa 2 (pulgadas). |
| ROWS_PER_STRIP | El número de filas por tira. Este es el número de filas en la imagen de una tira cuando una imagen se divide en tiras. |
| SAMPLES_PER_PIXEL | El número de componentes por píxel. Dado que este estándar se aplica a imágenes RGB y YCbCr, el valor establecido para esta etiqueta es 3. |
| SATURATION | Esta etiqueta indica la dirección del procesamiento de saturación aplicado por la cámara cuando se tomó la imagen. |
| SCENE_CAPTURE_TYPE | Esta etiqueta indica el tipo de escena que se fotografió. También puede usarse para registrar el modo en que se tomó la imagen. |
| SCENE_TYPE | Indica el tipo de escena. Si un DSC registró la imagen, el valor de esta etiqueta siempre debe ser 1, indicando que la imagen fue fotografiada directamente. |
| SENSING_METHOD | Indica el tipo de sensor de imagen en la cámara o dispositivo de entrada. |
| SENSITIVITY_TYPE | Tipo de sensibilidad fotográfica |
| SHARPNESS | Esta etiqueta indica la dirección del procesamiento de nitidez aplicado por la cámara cuando se tomó la imagen |
| SHUTTER_SPEED_VALUE | El valor de la velocidad de obturación. |
| SOFTWARE | Esta etiqueta registra el nombre y la versión del software o firmware de la cámara o dispositivo de entrada de imagen utilizado para generar la imagen. El formato detallado no está especificado, pero se recomienda seguir el ejemplo que se muestra a continuación. Cuando el campo se deja en blanco, se trata como desconocido. |
| SPATIAL_FREQUENCY_RESPONSE | Esta etiqueta registra la tabla de frecuencia espacial de la cámara o dispositivo de entrada y los valores SFR en la dirección del ancho de la imagen, la altura de la imagen y la dirección diagonal, según lo especificado en ISO 12233. |
| SPECTRAL_SENSITIVITY | Indica la sensibilidad espectral de cada canal de la cámara utilizada. |
| STANDARD_OUTPUT_SENSITIVITY | Indica la sensibilidad de salida estándar de la cámara. |
| STRIP_BYTE_COUNTS | El número total de bytes en cada tira. |
| STRIP_OFFSETS | Para cada tira, el desplazamiento de bytes de esa tira. Se recomienda que se seleccione de modo que el número de bytes de la tira no exceda los 64 Kbytes.<br/>                Etiqueta auxiliar. |
| SUBJECT_AREA | Esta etiqueta indica la ubicación y el área del sujeto principal en la escena completa. |
| SUBJECT_DISTANCE | La distancia al sujeto, dada en metros. |
| SUBJECT_DISTANCE_RANGE | Esta etiqueta indica la distancia al sujeto. |
| SUBJECT_LOCATION | Indica la ubicación del sujeto principal en la escena. El valor de esta etiqueta representa el píxel en el centro del sujeto principal relativo al borde izquierdo, antes del procesamiento de rotación según la etiqueta Rotation. |
| SUBSEC_TIME | Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTime. |
| SUBSEC_TIME_DIGITIZED | Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTimeDigitized. |
| SUBSEC_TIME_ORIGINAL | Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTimeOriginal. |
| TRANSFER_FUNCTION | Una función de transferencia para la imagen, descrita en estilo tabular. Normalmente esta etiqueta no es necesaria, ya que el espacio de color se especifica en la etiqueta de información del espacio de color ColorSpace. |
| USER_COMMENT | Una etiqueta para que los usuarios de Exif escriban palabras clave o comentarios en la imagen, además de los que aparecen en ImageDescription, y sin las limitaciones de código de caracteres de la etiqueta ImageDescription. |
| WHITE_BALANCE | Esta etiqueta indica el modo de balance de blancos configurado cuando se tomó la imagen. |
| WHITE_POINT | La cromaticidad del punto blanco de la imagen. Normalmente esta etiqueta no es necesaria, ya que el espacio de color se especifica en la etiqueta de información del espacio de color ColorSpace. |
| X_RESOLUTION | El número de píxeles por ResolutionUnit en la dirección ImageWidth. Cuando la resolución de la imagen es desconocida, se designa 72 [dpi]. |
| Y_CB_CR_COEFFICIENTS | Los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr. |
| Y_CB_CR_POSITIONING | La posición de los componentes de crominancia en relación con el<br/>                componente de luminancia. Este campo se designa solo para<br/>                datos comprimidos JPEG o datos YCbCr sin comprimir. El valor predeterminado de TIFF<br/>                es 1 (centrado); pero cuando Y:Cb:Cr = 4:2:2 se recomienda en esta norma que se use 2 (co‑situado) para<br/>                registrar los datos, con el fin de mejorar la calidad de la imagen al visualizarse<br/>                en sistemas de TV. Cuando este campo no existe, el lector deberá<br/>                asumir el valor predeterminado de TIFF. En el caso de Y:Cb:Cr = 4:2:0, el<br/>                valor predeterminado de TIFF (centrado) es recomendado. Si el lector<br/>                no tiene la capacidad de soportar ambos tipos de<br/>                YCbCrPositioning, deberá seguir el valor predeterminado de TIFF sin importar<br/>                el valor en este campo. Es preferible que los lectores "<br/>                puedan soportar tanto la posición centrada como la co‑situada. |
| Y_CB_CR_SUB_SAMPLING | La proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia. |
| Y_RESOLUTION | El número de píxeles por ResolutionUnit en la dirección ImageLength. Se designa el mismo valor que XResolution. |
