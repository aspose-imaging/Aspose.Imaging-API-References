---
title: "ExifProperties"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Lista de etiquetas Exif"
type: docs
weight: 11
url: /es/java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Lista de etiquetas Exif
## Campos

| Campo | Descripción |
| --- | --- |
| [ImageWidth](#ImageWidth) | El número de columnas de datos de imagen, igual al número de píxeles por fila. |
| [ImageLength](#ImageLength) | El número de filas de datos de imagen. |
| [BitsPerSample](#BitsPerSample) | El número de bits por componente de imagen. |
| [Compression](#Compression) | El esquema de compresión utilizado para los datos de imagen. |
| [PhotometricInterpretation](#PhotometricInterpretation) | La composición de píxeles. |
| [ImageDescription](#ImageDescription) | Una cadena de caracteres que indica el título de la imagen. |
| [Make](#Make) | El fabricante del equipo de grabación. |
| [Model](#Model) | El nombre del modelo o número de modelo del equipo. |
| [Orientation](#Orientation) | La orientación de la imagen vista en términos de filas y columnas. |
| [SamplesPerPixel](#SamplesPerPixel) | El número de componentes por píxel. |
| [XResolution](#XResolution) | El número de píxeles por ResolutionUnit en la dirección ImageWidth. |
| [YResolution](#YResolution) | El número de píxeles por ResolutionUnit en la dirección ImageLength. |
| [PlanarConfiguration](#PlanarConfiguration) | Indica si los componentes de píxel se registran en formato chunky o planar. |
| [ResolutionUnit](#ResolutionUnit) | La unidad para medir XResolution y YResolution. |
| [TransferFunction](#TransferFunction) | Una función de transferencia para la imagen, descrita en estilo tabular. |
| [Software](#Software) | Esta etiqueta registra el nombre y la versión del software o firmware de la cámara o dispositivo de entrada de imagen utilizado para generar la imagen. |
| [DateTime](#DateTime) | La fecha y hora de creación de la imagen. |
| [Artist](#Artist) | Esta etiqueta registra el nombre del propietario de la cámara, fotógrafo o creador de la imagen. |
| [WhitePoint](#WhitePoint) | La cromaticidad del punto blanco de la imagen. |
| [PrimaryChromaticities](#PrimaryChromaticities) | La cromaticidad de los tres colores primarios de la imagen. |
| [YCbCrCoefficients](#YCbCrCoefficients) | Los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr. |
| [YCbCrSubSampling](#YCbCrSubSampling) | La proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia. |
| [YCbCrPositioning](#YCbCrPositioning) | La posición de los componentes de crominancia en relación con el componente de luminancia. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | El valor del punto negro de referencia y el valor del punto blanco de referencia. |
| [Copyright](#Copyright) | Información de derechos de autor. |
| [ExposureTime](#ExposureTime) | Tiempo de exposición, dado en segundos. |
| [FNumber](#FNumber) | El número F. |
| [ExposureProgram](#ExposureProgram) | La clase del programa utilizado por la cámara para establecer la exposición cuando se toma la foto. |
| [SpectralSensitivity](#SpectralSensitivity) | Indica la sensibilidad espectral de cada canal de la cámara utilizada. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Indica la velocidad ISO y la latitud ISO de la cámara o dispositivo de entrada según lo especificado en ISO 12232. |
| [OECF](#OECF) | Indica la Función de Conversión Opto‑Eléctrica (OECF) especificada en ISO 14524. |
| [ExifVersion](#ExifVersion) | La versión Exif. |
| [DateTimeOriginal](#DateTimeOriginal) | La fecha y hora en que se generaron los datos de imagen originales. |
| [DateTimeDigitized](#DateTimeDigitized) | La fecha y hora de digitalización. |
| [ComponentsConfiguration](#ComponentsConfiguration) | La configuración de los componentes. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Específico de datos comprimidos; indica los bits comprimidos por píxel. |
| [ShutterSpeedValue](#ShutterSpeedValue) | El valor de la velocidad de obturación. |
| [ApertureValue](#ApertureValue) | El valor de la apertura del objetivo. |
| [BrightnessValue](#BrightnessValue) | El valor de brillo. |
| [ExposureBiasValue](#ExposureBiasValue) | El valor del sesgo de exposición. |
| [MaxApertureValue](#MaxApertureValue) | El valor de apertura máxima. |
| [SubjectDistance](#SubjectDistance) | La distancia al sujeto, dada en metros. |
| [MeteringMode](#MeteringMode) | El modo de medición. |
| [LightSource](#LightSource) | El tipo de fuente de luz. |
| [Flash](#Flash) | Indica el estado del flash cuando se tomó la imagen. |
| [FocalLength](#FocalLength) | La distancia focal real del objetivo, en mm. |
| [SubjectArea](#SubjectArea) | Esta etiqueta indica la ubicación y el área del sujeto principal en la escena completa. |
| [MakerNote](#MakerNote) | Una etiqueta para los fabricantes de escritores Exif para registrar cualquier información deseada. |
| [UserComment](#UserComment) | Una etiqueta para los usuarios de Exif para escribir palabras clave o comentarios en la imagen, además de los que están en ImageDescription, y sin las limitaciones de código de caracteres de la etiqueta ImageDescription. |
| [SubsecTime](#SubsecTime) | Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTime. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTimeOriginal. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTimeDigitized. |
| [FlashpixVersion](#FlashpixVersion) | La versión del formato Flashpix compatible con un archivo FPXR. |
| [ColorSpace](#ColorSpace) | La etiqueta de información del espacio de color (ColorSpace) siempre se registra como el especificador del espacio de color. |
| [RelatedSoundFile](#RelatedSoundFile) | El archivo de sonido relacionado. |
| [FlashEnergy](#FlashEnergy) | Indica la energía del estroboscopio en el momento en que se captura la imagen, medida en Beam Candle Power Seconds (BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Esta etiqueta registra la tabla de frecuencia espacial de la cámara o dispositivo de entrada y los valores SFR en la dirección del ancho de la imagen, la altura de la imagen y la dirección diagonal, según lo especificado en ISO 12233. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Indica el número de píxeles en la dirección del ancho de la imagen (X) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Indica el número de píxeles en la dirección de la altura de la imagen (Y) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Indica la unidad para medir FocalPlaneXResolution y FocalPlaneYResolution. |
| [SubjectLocation](#SubjectLocation) | Indica la ubicación del sujeto principal en la escena. |
| [ExposureIndex](#ExposureIndex) | Indica el índice de exposición seleccionado en la cámara o dispositivo de entrada en el momento en que se captura la imagen. |
| [SensingMethod](#SensingMethod) | Indica el tipo de sensor de imagen en la cámara o dispositivo de entrada. |
| [FileSource](#FileSource) | La fuente del archivo. |
| [SceneType](#SceneType) | Indica el tipo de escena. |
| [CFAPattern](#CFAPattern) | Indica el patrón geométrico de la matriz de filtros de color (CFA) del sensor de imagen cuando se utiliza un sensor de área de color de un solo chip. |
| [CustomRendered](#CustomRendered) | Esta etiqueta indica el uso de procesamiento especial en los datos de la imagen, como renderizado orientado a la salida. |
| [ExposureMode](#ExposureMode) | Esta etiqueta indica el modo de exposición configurado cuando se tomó la imagen. |
| [WhiteBalance](#WhiteBalance) | Esta etiqueta indica el modo de balance de blancos configurado cuando se tomó la imagen. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Esta etiqueta indica la relación de zoom digital cuando se tomó la imagen. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Esta etiqueta indica la distancia focal equivalente asumiendo una cámara de película de 35 mm, en mm. |
| [SceneCaptureType](#SceneCaptureType) | Esta etiqueta indica el tipo de escena que se fotografió. |
| [GainControl](#GainControl) | Esta etiqueta indica el grado de ajuste de ganancia general de la imagen. |
| [Contrast](#Contrast) | Esta etiqueta indica la dirección del procesamiento de contraste aplicado por la cámara cuando se tomó la imagen. |
| [Saturation](#Saturation) | Esta etiqueta indica la dirección del procesamiento de saturación aplicado por la cámara cuando se tomó la imagen. |
| [Sharpness](#Sharpness) | Esta etiqueta indica la dirección del procesamiento de nitidez aplicado por la cámara cuando se tomó la imagen |
| [DeviceSettingDescription](#DeviceSettingDescription) | Esta etiqueta indica información sobre las condiciones de captura de una cámara modelo particular. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Esta etiqueta indica la distancia al sujeto. |
| [ImageUniqueID](#ImageUniqueID) | El id único de la imagen. |
| [GPSVersionID](#GPSVersionID) | Indica la versión de GPSInfoIFD. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Indica si la latitud es norte o sur. |
| [GPSLatitude](#GPSLatitude) | Indica la latitud. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Indica si la longitud es este u oeste. |
| [GPSLongitude](#GPSLongitude) | Indica la longitud. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Indica la altitud usada como altitud de referencia. |
| [GPSAltitude](#GPSAltitude) | Indica la altitud basada en la referencia en GPSAltitudeRef. |
| [GPSTimestamp](#GPSTimestamp) | Indica la hora como UTC (Tiempo Universal Coordinado). |
| [GPSSatellites](#GPSSatellites) | Indica los satélites GPS usados para las mediciones. |
| [GPSStatus](#GPSStatus) | Indica el estado del receptor GPS cuando se registra la imagen. |
| [GPSMeasureMode](#GPSMeasureMode) | Indica el modo de medición GPS. |
| [GPSDOP](#GPSDOP) | Indica el GPS DOP (grado de precisión de datos). |
| [GPSSpeedRef](#GPSSpeedRef) | Indica la unidad usada para expresar la velocidad de movimiento del receptor GPS. |
| [GPSSpeed](#GPSSpeed) | Indica la velocidad del movimiento del receptor GPS. |
| [GPSTrackRef](#GPSTrackRef) | Indica la referencia para dar la dirección del movimiento del receptor GPS. |
| [GPSTrack](#GPSTrack) | Indica la dirección del movimiento del receptor GPS. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Indica la referencia para dar la dirección de la imagen cuando se captura. |
| [GPSImgDirection](#GPSImgDirection) | Indica la dirección de la imagen cuando fue capturada. |
| [GPSMapDatum](#GPSMapDatum) | Indica los datos de levantamiento geodésico utilizados por el receptor GPS. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Indica si la latitud del punto de destino es latitud norte o sur. |
| [GPSDestLatitude](#GPSDestLatitude) | Indica la latitud del punto de destino. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Indica si la longitud del punto de destino es longitud este u oeste. |
| [GPSDestLongitude](#GPSDestLongitude) | Indica la longitud del punto de destino. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Indica la referencia utilizada para dar el rumbo al punto de destino. |
| [GPSDestBearing](#GPSDestBearing) | Indica el rumbo al punto de destino. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Indica la unidad utilizada para expresar la distancia al punto de destino. |
| [GPSDestDistance](#GPSDestDistance) | Indica la distancia al punto de destino. |
| [GPSProcessingMethod](#GPSProcessingMethod) | Una cadena de caracteres que registra el nombre del método utilizado para la localización. |
| [GPSAreaInformation](#GPSAreaInformation) | Una cadena de caracteres que registra el nombre del área GPS. |
| [GPSDateStamp](#GPSDateStamp) | Una cadena de caracteres que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado). |
| [GPSDifferential](#GPSDifferential) | Indica si se aplica corrección diferencial al receptor GPS. |
| [StripOffsets](#StripOffsets) | Para cada tira, el desplazamiento en bytes de esa tira. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | El desplazamiento al byte de inicio (SOI) de los datos de miniatura comprimidos en JPEG. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | El número de bytes de los datos de miniatura comprimidos en JPEG. |
| [ExifIfdPointer](#ExifIfdPointer) | Un puntero al IFD Exif. |
| [GPSIfdPointer](#GPSIfdPointer) | El puntero gps ifd. |
| [RowsPerStrip](#RowsPerStrip) | El número de filas por tira. |
| [StripByteCounts](#StripByteCounts) | El número total de bytes en cada tira. |
| [PixelXDimension](#PixelXDimension) | Información específica de los datos comprimidos. |
| [PixelYDimension](#PixelYDimension) | Información específica de los datos comprimidos. |
| [Gamma](#Gamma) | Valor de gamma |
| [SensitivityType](#SensitivityType) | Tipo de sensibilidad fotográfica |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Indica la sensibilidad de salida estándar de la cámara |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Indica el índice de exposición recomendado |
| [ISOSpeed](#ISOSpeed) | Información sobre el valor de velocidad ISO según lo definido en ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Esta etiqueta indica el valor de latitud de velocidad ISO yyy según lo definido en ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Esta etiqueta indica el valor de latitud de velocidad ISO zzz según lo definido en ISO 12232 |
| [CameraOwnerName](#CameraOwnerName) | Contiene el nombre del propietario de la cámara |
| [BodySerialNumber](#BodySerialNumber) | Contiene el número de serie del cuerpo de la cámara |
| [LensMake](#LensMake) | Esta etiqueta registra el fabricante del objetivo |
| [LensModel](#LensModel) | Esta etiqueta registra el nombre del modelo y el número de modelo del objetivo\`s |
| [LensSerialNumber](#LensSerialNumber) | Esta etiqueta registra el número de serie del objetivo intercambiable |
| [LensSpecification](#LensSpecification) | Esta etiqueta indica la distancia focal mínima, la distancia focal máxima, el número F mínimo en la distancia focal mínima y el número F mínimo en la distancia focal máxima |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


El número de columnas de datos de imagen, igual al número de píxeles por fila.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


El número de filas de datos de imagen.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


El número de bits por componente de imagen. En este estándar cada componente de la imagen tiene 8 bits, por lo que el valor para esta etiqueta es 8.

### Compression {#Compression}
```
public static final int Compression
```


El esquema de compresión utilizado para los datos de la imagen. Cuando una imagen principal está comprimida en JPEG, esta designación no es necesaria y se omite.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


La composición de píxeles.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


Una cadena de caracteres que brinda el título de la imagen. Puede ser un comentario como "1988 company picnic" o similar.

### Make {#Make}
```
public static final int Make
```


El fabricante del equipo de grabación. Este es el fabricante del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. Cuando el campo se deja en blanco, se considera desconocido.

### Model {#Model}
```
public static final int Model
```


El nombre o número de modelo del equipo. Este es el nombre o número de modelo del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. Cuando el campo se deja en blanco, se considera desconocido.

### Orientation {#Orientation}
```
public static final int Orientation
```


La orientación de la imagen vista en términos de filas y columnas.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


El número de componentes por píxel. Dado que este estándar se aplica a imágenes RGB y YCbCr, el valor establecido para esta etiqueta es 3.

### XResolution {#XResolution}
```
public static final int XResolution
```


El número de píxeles por ResolutionUnit en la dirección ImageWidth. Cuando la resolución de la imagen es desconocida, se designa 72 [dpi].

### YResolution {#YResolution}
```
public static final int YResolution
```


El número de píxeles por ResolutionUnit en la dirección ImageLength. Se designa el mismo valor que XResolution.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Indica si los componentes de píxel se registran en formato chunk (agrupado) o planar. Si este campo no existe, se asume el valor predeterminado de TIFF de 1 (chunky).

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


La unidad para medir XResolution y YResolution. La misma unidad se utiliza para ambos XResolution y YResolution. Si la resolución de la imagen es desconocida, se designa 2 (pulgadas).

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


Una función de transferencia para la imagen, descrita en estilo tabular. Normalmente esta etiqueta no es necesaria, ya que el espacio de color se especifica en la etiqueta de información del espacio de color ColorSpace.

### Software {#Software}
```
public static final int Software
```


Esta etiqueta registra el nombre y la versión del software o firmware de la cámara o dispositivo de entrada de imagen utilizado para generar la imagen. El formato detallado no está especificado, pero se recomienda seguir el ejemplo que se muestra a continuación. Cuando el campo se deja en blanco, se considera desconocido.

### DateTime {#DateTime}
```
public static final int DateTime
```


La fecha y hora de creación de la imagen. En el estándar Exif, es la fecha y hora en que se modificó el archivo.

### Artist {#Artist}
```
public static final int Artist
```


Esta etiqueta registra el nombre del propietario de la cámara, fotógrafo o creador de la imagen. El formato detallado no está especificado, pero se recomienda que la información se escriba como en el ejemplo a continuación para facilitar la interoperabilidad. Cuando el campo se deja en blanco, se considera desconocido. (Ej. "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


La cromaticidad del punto blanco de la imagen. Normalmente esta etiqueta no es necesaria, ya que el espacio de color se especifica en la etiqueta de información de espacio de color ColorSpace.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


La cromaticidad de los tres colores primarios de la imagen. Normalmente esta etiqueta no es necesaria, ya que el espacio de color se especifica en la etiqueta de información de espacio de color ColorSpace.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


Los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


La proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


La posición de los componentes de crominancia en relación con el componente de luminancia. Este campo está designado solo para datos comprimidos JPEG o datos YCbCr sin comprimir. El valor predeterminado de TIFF es 1 (centrado); pero cuando Y:Cb:Cr = 4:2:2 se recomienda en esta norma que se use 2 (co-situado) para registrar los datos, con el fin de mejorar la calidad de la imagen al verla en sistemas de TV. Cuando este campo no existe, el lector debe asumir el valor predeterminado de TIFF. En el caso de Y:Cb:Cr = 4:2:0, se recomienda el valor predeterminado de TIFF (centrado). Si el lector no tiene la capacidad de soportar ambos tipos de YCbCrPositioning, debe seguir el valor predeterminado de TIFF sin importar el valor de este campo. Es preferible que los lectores \" puedan soportar tanto la posición centrada como la co-situada.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


El valor del punto negro de referencia y el valor del punto blanco de referencia. No se proporcionan valores predeterminados en TIFF, pero los valores a continuación se dan como predeterminados aquí. El espacio de color se declara en una etiqueta de información de espacio de color, siendo el valor predeterminado el que brinda las características óptimas de la imagen Interoperability bajo estas condiciones.

### Copyright {#Copyright}
```
public static final int Copyright
```


Información de derechos de autor. En esta norma la etiqueta se utiliza para indicar tanto los derechos de autor del fotógrafo como del editor. Es el aviso de derechos de autor de la persona u organización que reclama derechos sobre la imagen. La declaración de derechos de autor Interoperability que incluye fecha y derechos debe escribirse en este campo; por ejemplo, \"Copyright, John Smith, 19xx. All rights reserved.\" En esta norma el campo registra tanto los derechos de autor del fotógrafo como del editor, con cada uno registrado en una parte separada de la declaración. Cuando hay una distinción clara entre los derechos de autor del fotógrafo y del editor, deben escribirse en el orden de fotógrafo seguido por los derechos de autor del editor, separados por NULL (en este caso, como la declaración también termina con un NULL, hay dos códigos NULL). Cuando solo se proporciona el derecho de autor del fotógrafo, se termina con un código NULL. Cuando solo se proporciona el derecho de autor del editor, la parte del fotógrafo consiste en un espacio seguido de un código NULL de terminación, y luego se da el derecho de autor del editor. Cuando el campo se deja en blanco, se trata como desconocido.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Tiempo de exposición, dado en segundos.

### FNumber {#FNumber}
```
public static final int FNumber
```


El número F.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


La clase del programa utilizado por la cámara para establecer la exposición cuando se toma la foto.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Indica la sensibilidad espectral de cada canal de la cámara utilizada.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Indica la velocidad ISO y la latitud ISO de la cámara o dispositivo de entrada según lo especificado en ISO 12232.

### OECF {#OECF}
```
public static final int OECF
```


Indica la Función de Conversión Opto‑Eléctrica (OECF) especificada en ISO 14524.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


La versión Exif.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


La fecha y hora en que se generaron los datos de imagen originales.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


La fecha y hora de digitalización.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


La configuración de los componentes.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Específico de datos comprimidos; indica los bits comprimidos por píxel.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


El valor de la velocidad de obturación.

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


El valor de la apertura del objetivo.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


El valor de brillo.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


El valor del sesgo de exposición.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


El valor de apertura máxima.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


La distancia al sujeto, dada en metros.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


El modo de medición.

### LightSource {#LightSource}
```
public static final int LightSource
```


El tipo de fuente de luz.

### Flash {#Flash}
```
public static final int Flash
```


Indica el estado del flash cuando se tomó la imagen.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


La distancia focal real del objetivo, en mm.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Esta etiqueta indica la ubicación y el área del sujeto principal en la escena completa.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


Una etiqueta para que los fabricantes de escritores Exif registren cualquier información deseada. El contenido depende del fabricante, pero esta etiqueta no debe usarse para nada distinto a su propósito previsto.

### UserComment {#UserComment}
```
public static final int UserComment
```


Una etiqueta para los usuarios de Exif para escribir palabras clave o comentarios en la imagen, además de los que están en ImageDescription, y sin las limitaciones de código de caracteres de la etiqueta ImageDescription.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTime.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTimeOriginal.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTimeDigitized.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


La versión del formato Flashpix compatible con un archivo FPXR.

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


La etiqueta de información del espacio de color (ColorSpace) siempre se registra como el especificador del espacio de color.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


El archivo de sonido relacionado.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Indica la energía del estroboscopio en el momento en que se captura la imagen, medida en Beam Candle Power Seconds (BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Esta etiqueta registra la tabla de frecuencia espacial de la cámara o dispositivo de entrada y los valores SFR en la dirección del ancho de la imagen, la altura de la imagen y la dirección diagonal, según lo especificado en ISO 12233.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Indica el número de píxeles en la dirección del ancho de la imagen (X) por FocalPlaneResolutionUnit en el plano focal de la cámara.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Indica el número de píxeles en la dirección de la altura de la imagen (Y) por FocalPlaneResolutionUnit en el plano focal de la cámara.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Indica la unidad para medir FocalPlaneXResolution y FocalPlaneYResolution. Este valor es el mismo que ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Indica la ubicación del sujeto principal en la escena. El valor de esta etiqueta representa el píxel en el centro del sujeto principal relativo al borde izquierdo, antes del procesamiento de rotación según la etiqueta Rotation.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Indica el índice de exposición seleccionado en la cámara o dispositivo de entrada en el momento en que se captura la imagen.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Indica el tipo de sensor de imagen en la cámara o dispositivo de entrada.

### FileSource {#FileSource}
```
public static final int FileSource
```


La fuente del archivo.

### SceneType {#SceneType}
```
public static final int SceneType
```


Indica el tipo de escena. Si una DSC registró la imagen, el valor de esta etiqueta siempre debe establecerse en 1, indicando que la imagen fue fotografiada directamente.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Indica el patrón geométrico de la matriz de filtros de color (CFA) del sensor de imagen cuando se utiliza un sensor de área de color de un solo chip. No se aplica a todos los métodos de detección.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


Esta etiqueta indica el uso de procesamiento especial en los datos de la imagen, como renderizado orientado a la salida. Cuando se realiza procesamiento especial, se espera que el lector desactive o minimice cualquier procesamiento adicional.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


Esta etiqueta indica el modo de exposición configurado cuando se tomó la imagen. En modo de auto-bracketing, la cámara dispara una serie de fotogramas de la misma escena con diferentes ajustes de exposición.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Esta etiqueta indica el modo de balance de blancos configurado cuando se tomó la imagen.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


Esta etiqueta indica la relación de zoom digital cuando se tomó la imagen. Si el numerador del valor registrado es 0, indica que no se utilizó zoom digital.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


Esta etiqueta indica la distancia focal equivalente asumiendo una cámara de película de 35 mm, en mm. Un valor de 0 significa que la distancia focal es desconocida. Tenga en cuenta que esta etiqueta difiere de la etiqueta FocalLength.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


Esta etiqueta indica el tipo de escena que se fotografió. También puede usarse para registrar el modo en que se tomó la imagen.

### GainControl {#GainControl}
```
public static final int GainControl
```


Esta etiqueta indica el grado de ajuste de ganancia general de la imagen.

### Contrast {#Contrast}
```
public static final int Contrast
```


Esta etiqueta indica la dirección del procesamiento de contraste aplicado por la cámara cuando se tomó la imagen.

### Saturation {#Saturation}
```
public static final int Saturation
```


Esta etiqueta indica la dirección del procesamiento de saturación aplicado por la cámara cuando se tomó la imagen.

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Esta etiqueta indica la dirección del procesamiento de nitidez aplicado por la cámara cuando se tomó la imagen

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


Esta etiqueta indica información sobre las condiciones de captura de una cámara de modelo particular. La etiqueta se usa solo para indicar las condiciones de captura en el lector.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Esta etiqueta indica la distancia al sujeto.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


El id único de la imagen.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Indica la versión de GPSInfoIFD.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Indica si la latitud es norte o sur.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Indica la latitud. La latitud se expresa como tres valores RATIONAL que dan los grados, minutos y segundos, respectivamente. Si la latitud se expresa en grados, minutos y segundos, un formato típico sería dd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos decimales, el formato sería dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Indica si la longitud es este u oeste.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Indica la longitud. La longitud se expresa como tres valores RATIONAL que dan los grados, minutos y segundos, respectivamente. Si la longitud se expresa en grados, minutos y segundos, un formato típico sería ddd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos decimales, el formato sería ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Indica la altitud utilizada como altitud de referencia. Si la referencia es el nivel del mar y la altitud está por encima del nivel del mar, se da 0. Si la altitud está por debajo del nivel del mar, se da un valor de 1 y la altitud se indica como un valor absoluto en la etiqueta GPSAltitude.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Indica la altitud basada en la referencia en GPSAltitudeRef. La altitud se expresa como un valor RATIONAL. La unidad de referencia es metros.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Indica la hora como UTC (Tiempo Universal Coordinado). TimeStamp se expresa como tres valores RATIONAL que dan la hora, el minuto y el segundo.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Indica los satélites GPS utilizados para las mediciones. Esta etiqueta puede usarse para describir el número de satélites, su número de identificación, ángulo de elevación, azimut, SNR y otra información en notación ASCII. El formato no está especificado. Si el receptor GPS es incapaz de tomar mediciones, el valor de la etiqueta debe establecerse en NULL.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Indica el estado del receptor GPS cuando se registra la imagen.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Indica el modo de medición GPS. - 2- o 3-dimensional.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Indica el GPS DOP (grado de precisión de los datos). Se escribe un valor HDOP durante la medición bidimensional, y PDOP durante la medición tridimensional.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Indica la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. 'K', 'M' y 'N' representan kilómetros por hora, millas por hora y nudos.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Indica la velocidad del movimiento del receptor GPS.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Indica la referencia para dar la dirección del movimiento del receptor GPS. 'T' denota dirección verdadera y 'M' es dirección magnética.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Indica la dirección del movimiento del receptor GPS. El rango de valores es de 0.00 a 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Indica la referencia para dar la dirección de la imagen al capturarse. 'T' denota dirección verdadera y 'M' es dirección magnética.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Indica la dirección de la imagen al ser capturada. El rango de valores es de 0.00 a 359.99.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Indica los datos de levantamiento geodésico utilizados por el receptor GPS.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Indica si la latitud del punto de destino es norte o sur. El valor ASCII 'N' indica latitud norte, y 'S' es latitud sur.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Indica la latitud del punto de destino. La latitud se expresa como tres valores RATIONAL que dan los grados, minutos y segundos, respectivamente. Si la latitud se expresa en grados, minutos y segundos, un formato típico sería dd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos decimales, el formato sería dd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Indica si la longitud del punto de destino es este u oeste. El ASCII 'E' indica longitud este, y 'W' es longitud oeste.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Indica la longitud del punto de destino. La longitud se expresa como tres valores RATIONAL que dan los grados, minutos y segundos, respectivamente. Si la longitud se expresa en grados, minutos y segundos, un formato típico sería ddd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos decimales, el formato sería ddd/1,mmmm/100,0/1.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Indica la referencia utilizada para dar el rumbo al punto de destino. 'T' denota dirección verdadera y 'M' es dirección magnética.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Indica el rumbo al punto de destino. El rango de valores es de 0.00 a 359.99.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Indica la unidad utilizada para expresar la distancia al punto de destino. 'K', 'M' y 'N' representan kilómetros, millas y nudos.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Indica la distancia al punto de destino.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


Una cadena de caracteres que registra el nombre del método utilizado para la localización. El primer byte indica el código de caracteres usado, y a continuación sigue el nombre del método.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


Una cadena de caracteres que registra el nombre del área GPS. El primer byte indica el código de caracteres usado, y a continuación sigue el nombre del área GPS.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


Una cadena de caracteres que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado). El formato es AAAA:MM:DD.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Indica si se aplica corrección diferencial al receptor GPS.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


Para cada tira, el desplazamiento en bytes de esa tira. Se recomienda seleccionar esto de modo que el número de bytes de la tira no exceda 64 KBytes. Etiqueta Aux.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


El desplazamiento al byte de inicio (SOI) de los datos de miniatura JPEG comprimida. No se usa para los datos JPEG de la imagen principal.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


El número de bytes de los datos de miniatura JPEG comprimida. No se usa para los datos JPEG de la imagen principal. Las miniaturas JPEG no se dividen sino que se registran como una secuencia continua de JPEG desde SOI hasta EOI. No deben registrarse los marcadores Appn y COM. Las miniaturas comprimidas deben registrarse en no más de 64 KBytes, incluyendo todos los demás datos que se registren en APP1.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Un puntero al Exif IFD. Interoperabilidad, el Exif IFD tiene la misma estructura que el IFD especificado en TIFF. Sin embargo, normalmente no contiene datos de imagen como en el caso de TIFF.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


El puntero gps ifd.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


El número de filas por tira. Este es el número de filas en la imagen de una tira cuando la imagen se divide en tiras.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


El número total de bytes en cada tira.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Información específica de datos comprimidos. Cuando se registra un archivo comprimido, el ancho válido de la imagen significativa debe registrarse en esta etiqueta, exista o no datos de relleno o un marcador de reinicio.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Información específica de datos comprimidos. Cuando se registra un archivo comprimido, la altura válida de la imagen significativa debe registrarse en esta etiqueta.

### Gamma {#Gamma}
```
public static final int Gamma
```


Valor de gamma

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Tipo de sensibilidad fotográfica

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Indica la sensibilidad de salida estándar de la cámara

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Indica el índice de exposición recomendado

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Información sobre el valor de velocidad ISO según lo definido en ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Esta etiqueta indica el valor de latitud de velocidad ISO yyy según lo definido en ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Esta etiqueta indica el valor de latitud de velocidad ISO zzz según lo definido en ISO 12232

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Contiene el nombre del propietario de la cámara

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Contiene el número de serie del cuerpo de la cámara

### LensMake {#LensMake}
```
public static final int LensMake
```


Esta etiqueta registra el fabricante del objetivo

### LensModel {#LensModel}
```
public static final int LensModel
```


Esta etiqueta registra el nombre del modelo y el número de modelo del objetivo\`s

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Esta etiqueta registra el número de serie del objetivo intercambiable

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Esta etiqueta indica la distancia focal mínima, la distancia focal máxima, el número F mínimo en la distancia focal mínima y el número F mínimo en la distancia focal máxima

