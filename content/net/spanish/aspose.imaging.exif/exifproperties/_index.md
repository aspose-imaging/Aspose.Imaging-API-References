---
title: ExifProperties
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Lista de etiquetas Exif
type: docs
weight: 1080
url: /es/aspose.imaging.exif/exifproperties/
---
## ExifProperties enumeration

Lista de etiquetas Exif

```csharp
public enum ExifProperties : ushort
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ImageWidth | `256` | El número de columnas de datos de imagen, igual al número de píxeles por fila. |
| ImageLength | `257` | El número de filas de datos de imagen. |
| BitsPerSample | `258` | El número de bits por componente de imagen. En este estándar, cada componente de la imagen es de 8 bits, por lo que el valor de esta etiqueta es 8. |
| Compression | `259` | El esquema de compresión utilizado para los datos de la imagen. Cuando una imagen primaria está comprimida en JPEG, esta designación no es necesaria y se omite. |
| PhotometricInterpretation | `262` | La composición de píxeles. |
| ImageDescription | `270` | Una cadena de caracteres que da el título de la imagen. Puede ser un comentario como "picnic de la empresa de 1988" o similar. |
| Make | `271` | El fabricante del equipo de grabación. Este es el fabricante del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. Cuando el campo se deja en blanco, se trata como desconocido. |
| Model | `272` | El nombre del modelo o el número de modelo del equipo. Este es el nombre o número de modelo del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. Cuando el campo se deja en blanco, se trata como desconocido. |
| Orientation | `274` | La orientación de la imagen vista en términos de filas y columnas. |
| SamplesPerPixel | `277` | El número de componentes por píxel. Dado que este estándar se aplica a imágenes RGB e YCbCr, el valor establecido para esta etiqueta es 3. |
| XResolution | `282` | El número de píxeles por unidad de resolución en la dirección ImageWidth. Cuando se desconoce la resolución de la imagen, se designa 72 [dpi]. |
| YResolution | `283` | El número de píxeles por unidad de resolución en la dirección ImageLength. Se designa el mismo valor que XResolution. |
| PlanarConfiguration | `284` | Indica si los componentes de píxeles se registran en un formato grueso o plano. Si este campo no existe, se asume el TIFF predeterminado de 1 (grueso). |
| ResolutionUnit | `296` | La unidad para medir la resolución X y la resolución Y. Se utiliza la misma unidad para XResolution e YResolution. Si se desconoce la resolución de la imagen, se designa 2 (pulgadas). |
| TransferFunction | `301` | Una función de transferencia para la imagen, descrita en estilo tabular. Normalmente, esta etiqueta no es necesaria, ya que el espacio de color se especifica en la información del espacio de color ColorSpace tag. |
| Software | `305` | Esta etiqueta registra el nombre y la versión del software o firmware de la cámara o del dispositivo de entrada de imágenes utilizado para generar la imagen. No se especifica el formato detallado, pero se recomienda seguir el ejemplo que se muestra a continuación. Cuando el campo se deja en blanco, se trata como desconocido. |
| DateTime | `306` | La fecha y hora de creación de la imagen. En el estándar Exif, es la fecha y hora en que se modificó el archivo. |
| Artist | `315` | Esta etiqueta registra el nombre del propietario de la cámara, el fotógrafo o el creador de la imagen. No se especifica el formato detallado, pero se recomienda que la información se escriba como en el ejemplo a continuación para facilitar la interoperabilidad. Cuando el campo se deja en blanco, se trata como desconocido. Ej.) "Propietario de la cámara, John Smith; Fotógrafo, Michael Brown; Creador de la imagen, Ken James" |
| WhitePoint | `318` | La cromaticidad del punto blanco de la imagen. Normalmente, esta etiqueta no es necesaria, ya que el espacio de color se especifica en la información del espacio de color ColorSpace tag. |
| PrimaryChromaticities | `319` | La cromaticidad de los tres colores primarios de la imagen. Normalmente, esta etiqueta no es necesaria, ya que el espacio de color se especifica en la información del espacio de color ColorSpace tag. |
| YCbCrCoefficients | `529` | Los coeficientes de matriz para la transformación de datos de imagen RGB a YCbCr. |
| YCbCrSubSampling | `530` | La relación de muestreo de los componentes de crominancia en relación con el componente de luminancia. |
| YCbCrPositioning | `531` | La posición de los componentes de crominancia en relación con el componente de luminancia . Este campo está designado solo para datos comprimidos en JPEG o datos YCbCr sin comprimir. El TIFF predeterminado es 1 (centrado); pero cuando Y:Cb:Cr = 4:2:2 se recomienda en este estándar que se use 2 (coubicado) para registrar datos, a fin de mejorar la calidad de la imagen cuando se ve en sistemas de TV. Cuando este campo no existe, el lector deberá asumir el valor predeterminado TIFF. En el caso de Y:Cb:Cr = 4:2:0, se recomienda el TIFF predeterminado (centrado). Si el lector no tiene la capacidad de admitir ambos tipos de posicionamiento YCbCr, deberá seguir el valor predeterminado de TIFF independientemente de del valor en este campo. Es preferible que los lectores " puedan admitir el posicionamiento centrado y coubicado. |
| ReferenceBlackWhite | `532` | El valor del punto negro de referencia y el valor del punto blanco de referencia. No se proporcionan valores predeterminados en TIFF, pero los valores a continuación se brindan como predeterminados aquí. El espacio de color se declara en una etiqueta de información de espacio de color, siendo default el valor que proporciona las características óptimas de la imagen Interoperabilidad estas condiciones |
| Copyright | `33432` | Información de derechos de autor. En este estándar, la etiqueta se usa para indicar los derechos de autor del fotógrafo y del editor. Es el aviso de derechos de autor de la persona u organización que reclama los derechos de la imagen. La declaración de derechos de autor de interoperabilidad, incluida la fecha y los derechos, debe escribirse en este campo ; por ejemplo, "Copyright, John Smith, 19xx. Todos los derechos reservados". En este estándar, el campo registra tanto los derechos de autor del fotógrafo como del editor , y cada uno se registra en una parte separada de la declaración. Cuando hay una clara distinción entre los derechos de autor del fotógrafo y del editor, estos deben escribirse en el orden del fotógrafo seguido del derecho de autor del editor, separados por NULL (en este caso, dado que la declaración también termina con un NULL, hay dos códigos NULL ). Cuando solo se proporciona el copyright de Photographer , finaliza con un código NULL. Cuando solo se otorgan los derechos de autor del editor, los derechos de autor del fotógrafo parte consisten en un espacio seguido de un código NULL de terminación, luego se otorgan los derechos de autor del editor. Cuando el campo se deja en blanco, se trata como desconocido. |
| ExposureTime | `33434` | Tiempo de exposición, expresado en segundos. |
| FNumber | `33437` | El número F. |
| ExposureProgram | `34850` | La clase del programa utilizado por la cámara para establecer la exposición cuando se toma la fotografía. |
| SpectralSensitivity | `34852` | Indica la sensibilidad espectral de cada canal de la cámara utilizada. |
| PhotographicSensitivity | `34855` | Indica la velocidad ISO y la latitud ISO de la cámara o dispositivo de entrada según lo especificado en ISO 12232. |
| OECF | `34856` | Indica la función de conversión optoeléctrica (OECF) especificada en ISO 14524. |
| ExifVersion | `36864` | La versión exif. |
| DateTimeOriginal | `36867` | La fecha y hora en que se generaron los datos de la imagen original. |
| DateTimeDigitized | `36868` | La fecha y hora digitalizada. |
| ComponentsConfiguration | `37121` | La configuración de los componentes. |
| CompressedBitsPerPixel | `37122` | Específico para datos comprimidos; indica los bits comprimidos por píxel. |
| ShutterSpeedValue | `37377` | El valor de la velocidad de obturación. |
| ApertureValue | `37378` | El valor de apertura de la lente. |
| BrightnessValue | `37379` | El valor de brillo. |
| ExposureBiasValue | `37380` | El valor de sesgo de exposición. |
| MaxApertureValue | `37381` | El valor máximo de apertura. |
| SubjectDistance | `37382` | La distancia al sujeto, dada en metros. |
| MeteringMode | `37383` | El modo de medición. |
| LightSource | `37384` | La amable fuente de luz. |
| Flash | `37385` | Indica el estado del flash cuando se tomó la imagen. |
| FocalLength | `37386` | La distancia focal real de la lente, en mm. |
| SubjectArea | `37396` | Esta etiqueta indica la ubicación y el área del sujeto principal en la escena general. |
| MakerNote | `37500` | Una etiqueta para que los fabricantes de escritores Exif registren cualquier información deseada. El contenido depende del fabricante, pero esta etiqueta no debe usarse para ningún otro propósito que no sea el previsto. |
| UserComment | `37510` | Una etiqueta para que los usuarios de Exif escriban palabras clave o comentarios en la imagen además de los de ImageDescription, y sin las limitaciones de código de caracteres de la etiqueta ImageDescription. |
| SubsecTime | `37520` | Una etiqueta utilizada para registrar fracciones de segundos para la etiqueta DateTime. |
| SubsecTimeOriginal | `37521` | Una etiqueta utilizada para registrar fracciones de segundos para la etiqueta DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Una etiqueta utilizada para registrar fracciones de segundos para la etiqueta DateTimeDigitized. |
| FlashpixVersion | `40960` | La versión del formato Flashpix compatible con un archivo FPXR. |
| ColorSpace | `40961` | La etiqueta de información del espacio de color (ColorSpace) siempre se registra como el especificador de espacio de color. |
| RelatedSoundFile | `40964` | El archivo de sonido relacionado. |
| FlashEnergy | `41483` | Indica la energía estroboscópica en el momento en que se captura la imagen, medida en Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Esta etiqueta registra la tabla de frecuencia espacial de la cámara o el dispositivo de entrada y los valores SFR en la dirección del ancho de la imagen, la altura de la imagen y la dirección diagonal, como se especifica en ISO 12233. |
| FocalPlaneXResolution | `41486` | Indica el número de píxeles en la dirección del ancho de la imagen (X) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| FocalPlaneYResolution | `41487` | Indica el número de píxeles en la dirección de la altura de la imagen (Y) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| FocalPlaneResolutionUnit | `41488` | Indica la unidad para medir FocalPlaneXResolution y FocalPlaneYResolution. Este valor es el mismo que ResolutionUnit. |
| SubjectLocation | `41492` | Indica la ubicación del sujeto principal en la escena. El valor de esta etiqueta representa el píxel en el centro del sujeto principal en relación con el borde izquierdo, antes del procesamiento de rotación según la etiqueta Rotación. |
| ExposureIndex | `41493` | Indica el índice de exposición seleccionado en la cámara o dispositivo de entrada en el momento de capturar la imagen. |
| SensingMethod | `41495` | Indica el tipo de sensor de imagen en la cámara o dispositivo de entrada. |
| FileSource | `41728` | La fuente del archivo. |
| SceneType | `41729` | Indica el tipo de escena. Si un DSC grabó la imagen, este valor de etiqueta siempre se establecerá en 1, lo que indica que la imagen fue fotografiada directamente. |
| CFAPattern | `41730` | Indica el patrón geométrico de matriz de filtro de color (CFA) del sensor de imagen cuando se utiliza un sensor de área de color de un chip. No se aplica a todos los métodos de detección. |
| CustomRendered | `41985` | Esta etiqueta indica el uso de un procesamiento especial en los datos de la imagen, como la representación orientada a la salida. Cuando se realiza un procesamiento especial, se espera que el lector deshabilite o minimice cualquier procesamiento posterior. |
| ExposureMode | `41986` | Esta etiqueta indica el modo de exposición establecido cuando se tomó la imagen. En el modo de horquillado automático, la cámara toma una serie de fotogramas de la misma escena con diferentes ajustes de exposición. |
| WhiteBalance | `41987` | Esta etiqueta indica el modo de balance de blancos establecido cuando se tomó la imagen. |
| DigitalZoomRatio | `41988` | Esta etiqueta indica la relación de zoom digital cuando se tomó la imagen. Si el numerador del valor registrado es 0, esto indica que no se utilizó el zoom digital. |
| FocalLengthIn35MmFilm | `41989` | Esta etiqueta indica la distancia focal equivalente suponiendo una cámara de película de 35 mm, en mm. Un valor de 0 significa que se desconoce la distancia focal. Tenga en cuenta que esta etiqueta difiere de la etiqueta FocalLength. |
| SceneCaptureType | `41990` | Esta etiqueta indica el tipo de escena que se filmó. También se puede utilizar para registrar el modo en que se tomó la imagen. |
| GainControl | `41991` | Esta etiqueta indica el grado de ajuste general de la ganancia de la imagen. |
| Contrast | `41992` | Esta etiqueta indica la dirección del procesamiento de contraste aplicado por la cámara cuando se tomó la imagen. |
| Saturation | `41993` | Esta etiqueta indica la dirección del procesamiento de saturación aplicado por la cámara cuando se tomó la imagen. |
| Sharpness | `41994` | Esta etiqueta indica la dirección del procesamiento de nitidez aplicado por la cámara cuando se tomó la imagen |
| DeviceSettingDescription | `41995` | Esta etiqueta indica información sobre las condiciones de toma de fotografías de un modelo de cámara en particular. La etiqueta se usa solo para indicar las condiciones de toma de fotografías en el lector. |
| SubjectDistanceRange | `41996` | Esta etiqueta indica la distancia al sujeto. |
| ImageUniqueID | `42016` | ID único de la imagen. |
| GPSVersionID | `0` | Indica la versión de GPSInfoIFD. |
| GPSLatitudeRef | `1` | Indica si la latitud es latitud norte o latitud sur. |
| GPSLatitude | `2` | Indica la latitud. La latitud se expresa como tres valores RACIONALES que dan los grados, minutos y segundos, respectivamente. Si la latitud se expresa en grados, minutos y segundos, un formato típico sería dd/1,mm/1,ss/1. Cuando se utilizan grados y minutos y, por ejemplo, se dan fracciones de minutos hasta dos decimales, el formato sería dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Indica si la longitud es longitud este u oeste. |
| GPSLongitude | `4` | Indica la longitud. La longitud se expresa como tres valores RACIONALES que dan los grados, minutos y segundos, respectivamente. Si la longitud se expresa en grados, minutos y segundos, un formato típico sería ddd/1,mm/1,ss/1. Cuando se utilizan grados y minutos y, por ejemplo, se dan fracciones de minutos hasta dos decimales, el formato sería ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Indica la altitud utilizada como altitud de referencia. Si la referencia es el nivel del mar y la altitud es sobre el nivel del mar, se da 0. Si la altitud está por debajo del nivel del mar, se da un valor de 1 y la altitud se indica como un valor absoluto en la etiqueta GPSAltitude. |
| GPSAltitude | `6` | Indica la altitud basada en la referencia en GPSAltitudeRef. La altitud se expresa como un valor RACIONAL. La unidad de referencia es metros. |
| GPSTimestamp | `7` | Indica la hora como UTC (Tiempo Universal Coordinado). TimeStamp se expresa como tres valores RACIONALES que dan la hora, minuto y segundo. |
| GPSSatellites | `8` | Indica los satélites GPS utilizados para las mediciones. Esta etiqueta se puede utilizar para describir el número de satélites, su número de ID, ángulo de elevación, azimut, SNR y otra información en notación ASCII. El formato no está especificado. Si el receptor GPS no puede tomar medidas, el valor de la etiqueta se establecerá en NULL. |
| GPSStatus | `9` | Indica el estado del receptor GPS cuando se graba la imagen. |
| GPSMeasureMode | `10` | Indica el modo de medición GPS. - 2 o 3 dimensiones. |
| GPSDOP | `11` | Indica el GPS DOP (grado de precisión de los datos). Se escribe un valor HDOP durante la medición bidimensional, y PDOP durante la medición tridimensional. |
| GPSSpeedRef | `12` | Indica la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. 'K' 'M' y 'N' representan kilómetros por hora, millas por hora y nudos. |
| GPSSpeed | `13` | Indica la velocidad de movimiento del receptor GPS. |
| GPSTrackRef | `14` | Indica la referencia para dar la dirección de movimiento del receptor GPS. 'T' denota dirección verdadera y 'M' es dirección magnética. |
| GPSTrack | `15` | Indica la dirección del movimiento del receptor GPS. El rango de valores es de 0.00 a 359.99. |
| GPSImgDirectionRef | `16` | Indica la referencia para dar la dirección de la imagen cuando se captura. 'T' denota dirección verdadera y 'M' es dirección magnética. |
| GPSImgDirection | `17` | Indica la dirección de la imagen cuando fue capturada. El rango de valores es de 0.00 a 359.99. |
| GPSMapDatum | `18` | Indica los datos de levantamiento geodésico utilizados por el receptor GPS. |
| GPSDestLatitudeRef | `19` | Indica si la latitud del punto de destino es latitud norte o sur. El valor ASCII 'N' indica latitud norte y 'S' es latitud sur. |
| GPSDestLatitude | `20` | Indica la latitud del punto de destino. La latitud se expresa como tres valores RACIONALES que dan grados, minutos y segundos, respectivamente. Si la latitud se expresa en grados, minutos y segundos, un formato típico sería dd/1,mm/1,ss/1. Cuando se utilizan grados y minutos y, por ejemplo, se dan fracciones de minutos hasta dos decimales, el formato sería dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Indica si la longitud del punto de destino es longitud este u oeste. ASCII 'E' indica longitud este, y 'W' es longitud oeste. |
| GPSDestLongitude | `22` | Indica la longitud del punto de destino. La longitud se expresa como tres valores RACIONALES que dan grados, minutos y segundos, respectivamente. Si la longitud se expresa en grados, minutos y segundos, un formato típico sería ddd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos hasta dos decimales, el formato sería ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Indica la referencia utilizada para dar el rumbo al punto de destino. 'T' denota dirección verdadera y 'M' es dirección magnética. |
| GPSDestBearing | `24` | Indica el rumbo al punto de destino. El rango de valores es de 0.00 a 359.99. |
| GPSDestDistanceRef | `25` | Indica la unidad utilizada para expresar la distancia al punto de destino. 'K', 'M' y 'N' representan kilómetros, millas y nudos. |
| GPSDestDistance | `26` | Indica la distancia al punto de destino. |
| GPSProcessingMethod | `27` | Una cadena de caracteres que registra el nombre del método utilizado para encontrar la ubicación. El primer byte indica el código de carácter utilizado, seguido del nombre del método. |
| GPSAreaInformation | `28` | Una cadena de caracteres que registra el nombre del área GPS. El primer byte indica el código de carácter utilizado, seguido del nombre de la zona GPS. |
| GPSDateStamp | `29` | Cadena de caracteres que registra información de fecha y hora relativa a UTC (hora universal coordinada). El formato es AAAA:MM:DD. |
| GPSDifferential | `30` | Indica si se aplica corrección diferencial al receptor GPS. |
| StripOffsets | `273` | Para cada tira, el byte de desplazamiento de esa tira. Se recomienda seleccionarlo para que el número de bytes de tira no supere los 64 Kbytes. Etiqueta auxiliar. |
| JPEGInterchangeFormat | `513` | El desplazamiento al byte de inicio (SOI) de los datos de miniatura comprimidos JPEG. Esto no se usa para datos JPEG de imágenes primarias. |
| JPEGInterchangeFormatLength | `514` | El número de bytes de datos de miniatura comprimidos JPEG. Esto no se usa para datos JPEG de imágenes primarias. Las miniaturas JPEG no se dividen, sino que se graban como un flujo continuo de bits JPEG de SOI a EOI. Los marcadores Appn y COM no deben registrarse. Las miniaturas comprimidas deben grabarse en no más de 64 Kbytes, incluidos todos los demás datos que se grabarán en APP1. |
| ExifIfdPointer | `34665` | Un puntero al IFD Exif. Interoperabilidad, Exif IFD tiene la misma estructura que la IFD especificada en TIFF. normalmente, sin embargo, no contiene datos de imagen como en el caso de TIFF. |
| GPSIfdPointer | `34853` | El puntero ifd gps. |
| RowsPerStrip | `278` | El número de filas por tira. Este es el número de filas en la imagen de una tira cuando una imagen se divide en tiras. |
| StripByteCounts | `279` | El número total de bytes en cada tira. |
| PixelXDimension | `40962` | Información específica de los datos comprimidos. Cuando se graba un archivo comprimido, el ancho válido de la imagen significativa se grabará en esta etiqueta, haya o no datos de relleno o un marcador de reinicio. |
| PixelYDimension | `40963` | Información específica de los datos comprimidos. Cuando se graba un archivo comprimido, la altura válida de la imagen significativa se registrará en esta etiqueta |
| Gamma | `42240` | Valor gamma |
| SensitivityType | `34864` | Tipo de sensibilidad fotográfica |
| StandardOutputSensitivity | `34865` | Indica la sensibilidad de salida estándar de camera |
| RecommendedExposureIndex | `34866` | Indica el índice de exposición recomendado |
| ISOSpeed | `34867` | Información sobre el valor de velocidad iso tal como se define en ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Esta etiqueta indica el valor de latitud de velocidad ISO yyy como se define en ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Esta etiqueta indica el valor zzz de latitud de velocidad ISO según se define en ISO 12232 |
| CameraOwnerName | `42032` | Contiene el nombre del propietario de la cámara |
| BodySerialNumber | `42033` | Contiene el número de serie del cuerpo de la cámara |
| LensMake | `42035` | Esta etiqueta registra el fabricante de la lente |
| LensModel | `42036` | Esta etiqueta registra el nombre del modelo de la lente y el número de modelo |
| LensSerialNumber | `42037` | Esta etiqueta registra el número de serie de la lente intercambiable |
| LensSpecification | `42034` | Esta etiqueta indica la distancia focal mínima, la distancia focal máxima, el número F mínimo en la distancia focal mínima y el número F mínimo en la distancia focal máxima |

### Ver también

* espacio de nombres [Aspose.Imaging.Exif](../../aspose.imaging.exif)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
