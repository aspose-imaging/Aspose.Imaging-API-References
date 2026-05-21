---
title: "ExifData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Contenedor de datos EXIF."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.exif/exifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller)

**All Implemented Interfaces:**
[com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class ExifData extends TiffDataTypeController implements IImageMetadataFormat
```

Contenedor de datos EXIF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ExifData()](#ExifData--) | Inicializa una nueva instancia de la clase `ExifData`. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inicializa una nueva instancia de la clase `ExifData` con datos del arreglo. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Inicializa una nueva instancia de la clase `ExifData` con datos del arreglo. |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | Inicializa una nueva instancia de la clase [ExifData](../../com.aspose.imaging.exif/exifdata) con datos del arreglo. |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | Inicializa una nueva instancia de la clase [ExifData](../../com.aspose.imaging.exif/exifdata). |
## Métodos

| Método | Descripción |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | Obtiene o establece un valor que indica si los datos EXIF del flujo creado son big endian. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Obtiene o establece un valor que indica si los datos EXIF del flujo creado son big endian. |
| [getMake()](#getMake--) | Obtiene el fabricante del equipo de grabación. |
| [setMake(String value)](#setMake-java.lang.String-) | Establece el fabricante del equipo de grabación. |
| [getApertureValue()](#getApertureValue--) | Obtiene o establece el valor de la apertura. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece el valor de la apertura. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Obtiene o establece el número de serie del cuerpo de la cámara. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Obtiene o establece el número de serie del cuerpo de la cámara. |
| [getBrightnessValue()](#getBrightnessValue--) | Obtiene o establece el valor de brillo. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Obtiene o establece el valor de brillo. |
| [getCFAPattern()](#getCFAPattern--) | Obtiene o establece el patrón CFA. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Obtiene o establece el patrón CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Obtiene o establece el nombre del propietario de la cámara |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Obtiene o establece el nombre del propietario de la cámara |
| [getColorSpace()](#getColorSpace--) | Obtiene o establece el espacio de color. |
| [setColorSpace(int value)](#setColorSpace-int-) | Obtiene o establece el espacio de color. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Obtiene o establece la configuración de componentes. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Obtiene o establece la configuración de componentes. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Obtiene o establece los bits comprimidos por píxel. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece los bits comprimidos por píxel. |
| [getContrast()](#getContrast--) | Obtiene o establece el contraste. |
| [setContrast(int value)](#setContrast-int-) | Obtiene o establece el contraste. |
| [getCustomRendered()](#getCustomRendered--) | Obtiene o establece el renderizado personalizado. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Obtiene o establece el renderizado personalizado. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Obtiene o establece la fecha y hora de digitalización. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Obtiene o establece la fecha y hora de digitalización. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Obtiene o establece la fecha y hora original. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Obtiene o establece la fecha y hora original. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Obtiene o establece la descripción de la configuración del dispositivo |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Obtiene o establece la descripción de la configuración del dispositivo |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Obtiene o establece la relación de zoom digital. |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la relación de zoom digital. |
| [getExifVersion()](#getExifVersion--) | Obtiene o establece la versión EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Obtiene o establece la versión EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Obtiene o establece el valor de sesgo de exposición. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Obtiene o establece el valor de sesgo de exposición. |
| [getExposureIndex()](#getExposureIndex--) | Obtiene o establece el índice de exposición. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece el índice de exposición. |
| [getExposureMode()](#getExposureMode--) | Obtiene o establece el modo de exposición. |
| [setExposureMode(int value)](#setExposureMode-int-) | Obtiene o establece el modo de exposición. |
| [getExposureProgram()](#getExposureProgram--) | Obtiene o establece el programa de exposición. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Obtiene o establece el programa de exposición. |
| [getExposureTime()](#getExposureTime--) | Obtiene o establece el tiempo de exposición. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece el tiempo de exposición. |
| [getFNumber()](#getFNumber--) | Obtiene o establece el número F. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece el número F. |
| [getFileSource()](#getFileSource--) | Obtiene o establece el tipo de origen del archivo. |
| [setFileSource(byte value)](#setFileSource-byte-) | Obtiene o establece el tipo de origen del archivo. |
| [getFlash()](#getFlash--) | Obtiene o establece el flash. |
| [setFlash(int value)](#setFlash-int-) | Obtiene o establece el flash. |
| [getFlashEnergy()](#getFlashEnergy--) | Obtiene o establece la energía del flash. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la energía del flash. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Obtiene o establece la versión pix del flash. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Obtiene o establece la versión pix del flash. |
| [getFocalLength()](#getFocalLength--) | Obtiene o establece la distancia focal. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la distancia focal. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Obtiene o establece la distancia focal en película de 35 mm. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Obtiene o establece la distancia focal en película de 35 mm. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Obtiene o establece la unidad de resolución del plano focal. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Obtiene o establece la unidad de resolución del plano focal. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Obtiene o establece la resolución X del plano focal. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución X del plano focal. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Obtiene o establece la resolución Y del plano focal. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución Y del plano focal. |
| [getGPSAltitude()](#getGPSAltitude--) | Obtiene o establece la altitud GPS. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la altitud GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Obtiene o establece la altitud GPS utilizada como altitud de referencia. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Obtiene o establece la altitud GPS utilizada como altitud de referencia. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Obtiene o establece la información de área GPS. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Obtiene o establece la información de área GPS. |
| [getGPSDOP()](#getGPSDOP--) | Obtiene o establece el DOP GPS (grado de precisión de los datos). |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece el DOP GPS (grado de precisión de los datos). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Obtiene o establece la dirección GPS al punto de destino. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la dirección GPS al punto de destino. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Obtiene o establece la referencia GPS utilizada para proporcionar la dirección al punto de destino. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Obtiene o establece la referencia GPS utilizada para proporcionar la dirección al punto de destino. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Obtiene o establece la distancia GPS al punto de destino. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la distancia GPS al punto de destino. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Obtiene o establece la latitud GPS del punto de destino. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece la latitud GPS del punto de destino. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Obtiene o establece la longitud GPS del punto de destino. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece la longitud GPS del punto de destino. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste. |
| [getGPSDifferential()](#getGPSDifferential--) | Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Obtiene o establece la dirección GPS de la imagen cuando fue capturada. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la dirección GPS de la imagen cuando fue capturada. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Obtiene o establece la referencia GPS para proporcionar la dirección de la imagen cuando se captura. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Obtiene o establece la referencia GPS para proporcionar la dirección de la imagen cuando se captura. |
| [getGPSDateStamp()](#getGPSDateStamp--) | Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado). |
| [getGPSLatitude()](#getGPSLatitude--) | Obtiene o establece la latitud GPS. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece la latitud GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Obtiene o establece si la latitud GPS es norte o sur. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Obtiene o establece si la latitud GPS es norte o sur. |
| [getGPSLongitude()](#getGPSLongitude--) | Obtiene o establece la longitud GPS. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece la longitud GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Obtiene o establece si la longitud GPS es este u oeste. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Obtiene o establece si la longitud GPS es este u oeste. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Obtiene o establece el modo de medición GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Obtiene o establece el modo de medición GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización. |
| [getGPSSatellites()](#getGPSSatellites--) | Obtiene o establece los satélites GPS utilizados para las mediciones. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Obtiene o establece los satélites GPS utilizados para las mediciones. |
| [getGPSSpeed()](#getGPSSpeed--) | Obtiene o establece la velocidad de movimiento del receptor GPS. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la velocidad de movimiento del receptor GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. |
| [getGPSStatus()](#getGPSStatus--) | Obtiene o establece el estado del receptor GPS cuando se registra la imagen. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Obtiene o establece el estado del receptor GPS cuando se registra la imagen. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado). |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado). |
| [getGPSTrack()](#getGPSTrack--) | Obtiene o establece la dirección del movimiento del receptor GPS. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Obtiene o establece la dirección del movimiento del receptor GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Obtiene o establece la referencia para dar la dirección del movimiento del receptor GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Obtiene o establece la referencia para dar la dirección del movimiento del receptor GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | Obtiene o establece el identificador de versión del GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Obtiene o establece el identificador de versión del GPS. |
| [getGainControl()](#getGainControl--) | Obtiene o establece el grado de ajuste general de ganancia de la imagen. |
| [setGainControl(int value)](#setGainControl-int-) | Obtiene o establece el grado de ajuste general de ganancia de la imagen. |
| [getGamma()](#getGamma--) | Obtiene o establece la gamma. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la gamma. |
| [getISOSpeed()](#getISOSpeed--) | Obtiene o establece la velocidad ISO |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Obtiene o establece la velocidad ISO |
| [getISOSpeedValue()](#getISOSpeedValue--) | Obtiene el valor de velocidad ISO. |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | Establece el valor de velocidad ISO. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Obtiene o establece el valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Obtiene o establece el valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Obtiene o establece el valor de latitud zzz de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Obtiene o establece el valor de latitud zzz de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Obtiene o establece la sensibilidad fotográfica. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Obtiene o establece la sensibilidad fotográfica. |
| [getImageUniqueID()](#getImageUniqueID--) | Obtiene o establece el identificador único de la imagen. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Obtiene o establece el identificador único de la imagen. |
| [getLensMake()](#getLensMake--) | Obtiene o establece el fabricante de la lente. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Obtiene o establece el fabricante de la lente. |
| [getLensModel()](#getLensModel--) | Obtiene o establece el modelo de la lente. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Obtiene o establece el modelo de la lente. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Obtiene o establece el número de serie de la lente. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Obtiene o establece el número de serie de la lente. |
| [getLensSpecification()](#getLensSpecification--) | Obtiene o establece la especificación de la lente |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece la especificación de la lente |
| [getLightSource()](#getLightSource--) | Obtiene o establece la fuente de luz. |
| [setLightSource(int value)](#setLightSource-int-) | Obtiene o establece la fuente de luz. |
| [getMakerNoteData()](#getMakerNoteData--) | Obtiene los datos de la nota del fabricante. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Obtiene o establece los datos sin procesar de la nota del fabricante. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Obtiene o establece los datos sin procesar de la nota del fabricante. |
| [getMakerNotes()](#getMakerNotes--) | Obtiene las notas del fabricante. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Obtiene o establece el valor máximo de apertura. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece el valor máximo de apertura. |
| [getMeteringMode()](#getMeteringMode--) | Obtiene o establece el modo de medición. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Obtiene o establece el modo de medición. |
| [getOECF()](#getOECF--) | Obtiene o establece la Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524. |
| [setOECF(byte[] value)](#setOECF-byte---) | Obtiene o establece la Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524. |
| [getOrientation()](#getOrientation--) | Obtiene la orientación [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [setOrientation(int value)](#setOrientation-int-) | Establece la orientación [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [getPixelXDimension()](#getPixelXDimension--) | Obtiene o establece la dimensión x del píxel. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Obtiene o establece la dimensión x del píxel. |
| [getPixelYDimension()](#getPixelYDimension--) | Obtiene o establece la dimensión y del píxel. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Obtiene o establece la dimensión y del píxel. |
| [getProperties()](#getProperties--) | Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS). |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Obtiene o establece el índice de exposición recomendado. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Obtiene o establece el índice de exposición recomendado. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Obtiene o establece el archivo de sonido relacionado. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Obtiene o establece el archivo de sonido relacionado. |
| [getSaturation()](#getSaturation--) | Obtiene o establece la saturación. |
| [setSaturation(int value)](#setSaturation-int-) | Obtiene o establece la saturación. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Obtiene o establece el tipo de captura de escena. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Obtiene o establece el tipo de captura de escena. |
| [getSceneType()](#getSceneType--) | Obtiene o establece el tipo de escena. |
| [setSceneType(byte value)](#setSceneType-byte-) | Obtiene o establece el tipo de escena. |
| [getSensingMethod()](#getSensingMethod--) | Obtiene o establece el método de detección. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Obtiene o establece el método de detección. |
| [getSensitivityType()](#getSensitivityType--) | Obtiene o establece el tipo de sensibilidad. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Obtiene o establece el tipo de sensibilidad. |
| [getSharpness()](#getSharpness--) | Obtiene o establece la nitidez. |
| [setSharpness(int value)](#setSharpness-int-) | Obtiene o establece la nitidez. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Obtiene o establece el valor de velocidad de obturación. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Obtiene o establece el valor de velocidad de obturación. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Obtiene o establece la respuesta de frecuencia espacial. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Obtiene o establece la respuesta de frecuencia espacial. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Obtiene o establece la sensibilidad espectral. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Obtiene o establece la sensibilidad espectral. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Obtiene la sensibilidad de salida estándar |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Establece la sensibilidad de salida estándar |
| [getSubjectArea()](#getSubjectArea--) | Obtiene o establece el área del sujeto. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Obtiene o establece el área del sujeto. |
| [getSubjectDistance()](#getSubjectDistance--) | Obtiene o establece la distancia del sujeto. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Obtiene o establece la distancia del sujeto. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Obtiene o establece el rango de distancia del sujeto. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Obtiene o establece el rango de distancia del sujeto. |
| [getSubjectLocation()](#getSubjectLocation--) | Obtiene o establece la ubicación del sujeto. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Obtiene o establece la ubicación del sujeto. |
| [getSubsecTime()](#getSubsecTime--) | Obtiene o establece las fracciones de segundo para la etiqueta DateTime. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Obtiene o establece las fracciones de segundo para la etiqueta DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal. |
| [getUserComment()](#getUserComment--) | Obtiene o establece el comentario del usuario. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Obtiene o establece el comentario del usuario. |
| [getWhiteBalance()](#getWhiteBalance--) | Obtiene o establece el balance de blancos. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Obtiene o establece el balance de blancos. |
| [getWhitePoint()](#getWhitePoint--) | Obtiene o establece la cromaticidad del punto blanco de la imagen. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | Obtiene o establece la cromaticidad del punto blanco de la imagen. |
| [getCommonTags()](#getCommonTags--) | Obtiene o establece etiquetas, que pertenecen a la sección común. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtiene o establece etiquetas, que pertenecen a la sección común. |
| [getExifTags()](#getExifTags--) | Obtiene o establece etiquetas que pertenecen solo a la sección EXIF. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtiene o establece etiquetas que pertenecen solo a la sección EXIF. |
| [getGPSTags()](#getGPSTags--) | Obtiene o establece etiquetas, que pertenecen solo a la sección GPS. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Obtiene o establece etiquetas, que pertenecen solo a la sección GPS. |
| [getThumbnail()](#getThumbnail--) | Obtiene la imagen en miniatura. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | Establece la imagen en miniatura. |
| [getXResolutionInt()](#getXResolutionInt--) | Obtiene la resolución x. |
| [setXResolution(int value)](#setXResolution-int-) | Establece la resolución x. |
| [getYResolutionInt()](#getYResolutionInt--) | Obtiene la resolución y. |
| [setYResolution(int value)](#setYResolution-int-) | Establece la resolución y. |
| [removeTag(int tagId)](#removeTag-int-) | Eliminar etiqueta del contenedor |
| [getTagValue(int key)](#getTagValue-int-) | Obtiene el valor de la etiqueta. |

## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### ExifData() {#ExifData--}
```
public ExifData()
```


Inicializa una nueva instancia de la clase `ExifData`.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Inicializa una nueva instancia de la clase `ExifData` con datos del arreglo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Matriz de etiquetas EXIF junto con etiquetas comunes y GPS. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Inicializa una nueva instancia de la clase `ExifData` con datos del arreglo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas comunes. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Las etiquetas GPS. |

### ExifData(ExifData exifdata) {#ExifData-com.aspose.imaging.exif.ExifData-}
```
public ExifData(ExifData exifdata)
```


Inicializa una nueva instancia de la clase [ExifData](../../com.aspose.imaging.exif/exifdata) con datos del arreglo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | Matriz de etiquetas EXIF junto con etiquetas comunes y GPS. |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


Inicializa una nueva instancia de la clase [ExifData](../../com.aspose.imaging.exif/exifdata).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| binaryData | byte[] | Los datos binarios. |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


Obtiene o establece un valor que indica si los datos EXIF del flujo creado son big endian.

Valor: `true` si los datos EXIF del flujo creado son big endian; de lo contrario, `false`.

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Obtiene o establece un valor que indica si los datos EXIF del flujo creado son big endian.

Valor: `true` si los datos EXIF del flujo creado son big endian; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getMake() {#getMake--}
```
public final String getMake()
```


Obtiene el fabricante del equipo de grabación.

Valor: El fabricante del equipo de grabación.

**Returns:**
java.lang.String - el fabricante del equipo de grabación.
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Establece el fabricante del equipo de grabación.

Valor: El fabricante del equipo de grabación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | el fabricante del equipo de grabación. |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Obtiene o establece el valor de la apertura.

Valor: El valor de apertura.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Obtiene o establece el valor de la apertura.

Valor: El valor de apertura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Obtiene o establece el número de serie del cuerpo de la cámara.

Valor: El número de serie del cuerpo.

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Obtiene o establece el número de serie del cuerpo de la cámara.

Valor: El número de serie del cuerpo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Obtiene o establece el valor de brillo.

Valor: El valor de brillo.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Obtiene o establece el valor de brillo.

Valor: El valor de brillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Obtiene o establece el patrón CFA.

Valor: El patrón CFA.

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Obtiene o establece el patrón CFA.

Valor: El patrón CFA.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Obtiene o establece el nombre del propietario de la cámara

Valor: El nombre del propietario de la cámara.

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Obtiene o establece el nombre del propietario de la cámara

Valor: El nombre del propietario de la cámara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Obtiene o establece el espacio de color.

Valor: El espacio de color.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Obtiene o establece el espacio de color.

Valor: El espacio de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Obtiene o establece la configuración de componentes.

Valor: La configuración de componentes.

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Obtiene o establece la configuración de componentes.

Valor: La configuración de componentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Obtiene o establece los bits comprimidos por píxel.

Valor: Los bits comprimidos por píxel.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Obtiene o establece los bits comprimidos por píxel.

Valor: Los bits comprimidos por píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getContrast() {#getContrast--}
```
public int getContrast()
```


Obtiene o establece el contraste.

Valor: El contraste.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Obtiene o establece el contraste.

Valor: El contraste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Obtiene o establece el renderizado personalizado.

Valor: El renderizado personalizado.

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Obtiene o establece el renderizado personalizado.

Valor: El renderizado personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Obtiene o establece la fecha y hora de digitalización.

Valor: La fecha y hora de digitalización.

**Returns:**
java.lang.String
### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Obtiene o establece la fecha y hora de digitalización.

Valor: La fecha y hora de digitalización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Obtiene o establece la fecha y hora original.

Valor: La fecha y hora original.

**Returns:**
java.lang.String
### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Obtiene o establece la fecha y hora original.

Valor: La fecha y hora original.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Obtiene o establece la descripción de la configuración del dispositivo

Valor: La descripción de la configuración del dispositivo.

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Obtiene o establece la descripción de la configuración del dispositivo

Valor: La descripción de la configuración del dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Obtiene o establece la relación de zoom digital.

Valor: La relación de zoom digital.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Obtiene o establece la relación de zoom digital.

Valor: La relación de zoom digital.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Obtiene o establece la versión EXIF.

Valor: La versión EXIF.

**Returns:**
byte[]
### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Obtiene o establece la versión EXIF.

Valor: La versión EXIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Obtiene o establece el valor de sesgo de exposición.

Valor: El valor de compensación de exposición.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Obtiene o establece el valor de sesgo de exposición.

Valor: El valor de compensación de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Obtiene o establece el índice de exposición.

Valor: El índice de exposición.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Obtiene o establece el índice de exposición.

Valor: El índice de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Obtiene o establece el modo de exposición.

Valor: El modo de exposición.

**Returns:**
int
### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Obtiene o establece el modo de exposición.

Valor: El modo de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Obtiene o establece el programa de exposición.

Valor: El programa de exposición.

**Returns:**
int
### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Obtiene o establece el programa de exposición.

Valor: El programa de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Obtiene o establece el tiempo de exposición.

Valor: El tiempo de exposición.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Obtiene o establece el tiempo de exposición.

Valor: El tiempo de exposición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Obtiene o establece el número F.

Valor: El número F.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFNumber(TiffRational value) {#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Obtiene o establece el número F.

Valor: El número F.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Obtiene o establece el tipo de origen del archivo.

Valor: El tipo de origen del archivo.

**Returns:**
byte
### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Obtiene o establece el tipo de origen del archivo.

Valor: El tipo de origen del archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getFlash() {#getFlash--}
```
public int getFlash()
```


Obtiene o establece el flash.

Valor: El flash.

**Returns:**
int
### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Obtiene o establece el flash.

Valor: El flash.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Obtiene o establece la energía del flash.

Valor: La energía del flash.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Obtiene o establece la energía del flash.

Valor: La energía del flash.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Obtiene o establece la versión pix del flash.

Valor: La versión pix del flash.

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Obtiene o establece la versión pix del flash.

Valor: La versión pix del flash.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Obtiene o establece la distancia focal.

Valor: La longitud focal.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Obtiene o establece la distancia focal.

Valor: La longitud focal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Obtiene o establece la distancia focal en película de 35 mm.

Valor: La distancia focal en película de 35 mm.

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Obtiene o establece la distancia focal en película de 35 mm.

Valor: La distancia focal en película de 35 mm.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Obtiene o establece la unidad de resolución del plano focal.

Valor: La unidad de resolución del plano focal.

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Obtiene o establece la unidad de resolución del plano focal.

Valor: La unidad de resolución del plano focal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Obtiene o establece la resolución X del plano focal.

Valor: La resolución x del plano focal.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Obtiene o establece la resolución X del plano focal.

Valor: La resolución x del plano focal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Obtiene o establece la resolución Y del plano focal.

Valor: La resolución y del plano focal.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Obtiene o establece la resolución Y del plano focal.

Valor: La resolución y del plano focal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Obtiene o establece la altitud GPS.

Valor: La altitud GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Obtiene o establece la altitud GPS.

Valor: La altitud GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Obtiene o establece la altitud GPS utilizada como altitud de referencia.

Valor: La altitud GPS utilizada como altitud de referencia.

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Obtiene o establece la altitud GPS utilizada como altitud de referencia.

Valor: La altitud GPS utilizada como altitud de referencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Obtiene o establece la información de área GPS.

Valor: La información de área GPS.

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Obtiene o establece la información de área GPS.

Valor: La información de área GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Obtiene o establece el DOP GPS (grado de precisión de los datos).

Valor: El DOP GPS (grado de precisión de los datos).

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Obtiene o establece el DOP GPS (grado de precisión de los datos).

Valor: El DOP GPS (grado de precisión de los datos).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Obtiene o establece la dirección GPS al punto de destino.

Valor: La dirección GPS hacia el punto de destino.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Obtiene o establece la dirección GPS al punto de destino.

Valor: La dirección GPS hacia el punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Obtiene o establece la referencia GPS utilizada para proporcionar la dirección al punto de destino.

Valor: La referencia GPS utilizada para proporcionar la dirección al punto de destino.

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Obtiene o establece la referencia GPS utilizada para proporcionar la dirección al punto de destino.

Valor: La referencia GPS utilizada para proporcionar la dirección al punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Obtiene o establece la distancia GPS al punto de destino.

Valor: La distancia GPS al punto de destino.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Obtiene o establece la distancia GPS al punto de destino.

Valor: La distancia GPS al punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino.

Valor: La unidad GPS utilizada para expresar la distancia al punto de destino.

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino.

Valor: La unidad GPS utilizada para expresar la distancia al punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Obtiene o establece la latitud GPS del punto de destino.

Valor: La latitud GPS del punto de destino.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Obtiene o establece la latitud GPS del punto de destino.

Valor: La latitud GPS del punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur.

Valor: El valor GPS que indica si la latitud del punto de destino es norte o sur.

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur.

Valor: El valor GPS que indica si la latitud del punto de destino es norte o sur.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Obtiene o establece la longitud GPS del punto de destino.

Valor: La longitud GPS del punto de destino.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Obtiene o establece la longitud GPS del punto de destino.

Valor: La longitud GPS del punto de destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste.

Valor: El valor GPS que indica si la longitud del punto de destino es este u oeste.

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste.

Valor: El valor GPS que indica si la longitud del punto de destino es este u oeste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS.

Valor: El valor GPS que indica si se aplica corrección diferencial al receptor GPS.

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS.

Valor: El valor GPS que indica si se aplica corrección diferencial al receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Obtiene o establece la dirección GPS de la imagen cuando fue capturada.

Valor: La dirección GPS de la imagen cuando fue capturada.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Obtiene o establece la dirección GPS de la imagen cuando fue capturada.

Valor: La dirección GPS de la imagen cuando fue capturada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Obtiene o establece la referencia GPS para proporcionar la dirección de la imagen cuando se captura.

Valor: La referencia GPS para proporcionar la dirección de la imagen cuando se captura.

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Obtiene o establece la referencia GPS para proporcionar la dirección de la imagen cuando se captura.

Valor: La referencia GPS para proporcionar la dirección de la imagen cuando se captura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado).

Valor: La cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado).

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado).

Valor: La cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Obtiene o establece la latitud GPS.

Valor: La latitud GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Obtiene o establece la latitud GPS.

Valor: La latitud GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Obtiene o establece si la latitud GPS es norte o sur.

Valor: La latitud GPS es norte o sur.

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Obtiene o establece si la latitud GPS es norte o sur.

Valor: La latitud GPS es norte o sur.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Obtiene o establece la longitud GPS.

Valor: La longitud GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Obtiene o establece la longitud GPS.

Valor: La longitud GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Obtiene o establece si la longitud GPS es este u oeste.

Valor: La longitud GPS es este u oeste.

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Obtiene o establece si la longitud GPS es este u oeste.

Valor: La longitud GPS es este u oeste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS.

Valor: Los datos de levantamiento geodésico GPS utilizados por el receptor GPS.

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS.

Valor: Los datos de levantamiento geodésico GPS utilizados por el receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Obtiene o establece el modo de medición GPS.

Valor: El modo de medición GPS.

**Returns:**
java.lang.String
### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Obtiene o establece el modo de medición GPS.

Valor: El modo de medición GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización.

Valor: La cadena de caracteres GPS que registra el nombre del método utilizado para la localización.

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización.

Valor: La cadena de caracteres GPS que registra el nombre del método utilizado para la localización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Obtiene o establece los satélites GPS utilizados para las mediciones.

Valor: Los satélites GPS utilizados para mediciones.

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Obtiene o establece los satélites GPS utilizados para las mediciones.

Valor: Los satélites GPS utilizados para mediciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Obtiene o establece la velocidad de movimiento del receptor GPS.

Valor: La velocidad del movimiento del receptor GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Obtiene o establece la velocidad de movimiento del receptor GPS.

Valor: La velocidad del movimiento del receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS.

Valor: La unidad utilizada para expresar la velocidad de movimiento del receptor GPS.

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS.

Valor: La unidad utilizada para expresar la velocidad de movimiento del receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Obtiene o establece el estado del receptor GPS cuando se registra la imagen.

Valor: El estado del receptor GPS cuando se registra la imagen.

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Obtiene o establece el estado del receptor GPS cuando se registra la imagen.

Valor: El estado del receptor GPS cuando se registra la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado).

Valor: La hora GPS como UTC (Tiempo Universal Coordinado).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado).

Valor: La hora GPS como UTC (Tiempo Universal Coordinado).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Obtiene o establece la dirección del movimiento del receptor GPS.

Valor: La dirección del movimiento del receptor GPS.

**Returns:**
java.lang.String
### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Obtiene o establece la dirección del movimiento del receptor GPS.

Valor: La dirección del movimiento del receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Obtiene o establece la referencia para dar la dirección del movimiento del receptor GPS.

Valor: La referencia para indicar la dirección del movimiento del receptor GPS.

**Returns:**
java.lang.String
### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Obtiene o establece la referencia para dar la dirección del movimiento del receptor GPS.

Valor: La referencia para indicar la dirección del movimiento del receptor GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Obtiene o establece el identificador de versión del GPS.

Valor: El identificador de versión GPS.

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Obtiene o establece el identificador de versión del GPS.

Valor: El identificador de versión GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Obtiene o establece el grado de ajuste general de ganancia de la imagen.

Valor: El grado de ajuste global de ganancia de la imagen.

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Obtiene o establece el grado de ajuste general de ganancia de la imagen.

Valor: El grado de ajuste global de ganancia de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Obtiene o establece la gamma.

Valor: El valor gamma.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Obtiene o establece la gamma.

Valor: El valor gamma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Obtiene o establece la velocidad ISO

Valor: La velocidad ISO.

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Obtiene o establece la velocidad ISO

Valor: La velocidad ISO.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


Obtiene el valor de velocidad ISO.

Valor: El valor de velocidad ISO.

**Returns:**
largo - el valor de velocidad ISO.
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


Establece el valor de velocidad ISO.

Valor: El valor de velocidad ISO.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | el valor de velocidad ISO. |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Obtiene o establece el valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232.

Valor: El valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232.

Esta etiqueta no debe registrarse sin ISOSpeed e ISOSpeedLatitudeZZZ.

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Obtiene o establece el valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232.

Valor: El valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232.

Esta etiqueta no debe registrarse sin ISOSpeed e ISOSpeedLatitudeZZZ.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Obtiene o establece el valor de latitud zzz de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232.

Valor: El valor de latitud zzz de velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232.

Esta etiqueta no debe registrarse sin ISOSpeed e ISOSpeedLatitudeYYY.

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Obtiene o establece el valor de latitud zzz de velocidad ISO de una cámara o dispositivo de entrada que está definido en ISO 12232.

Valor: El valor de latitud zzz de velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232.

Esta etiqueta no debe registrarse sin ISOSpeed e ISOSpeedLatitudeYYY.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Obtiene o establece la sensibilidad fotográfica.

Valor: La sensibilidad fotográfica.

**Returns:**
long
### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Obtiene o establece la sensibilidad fotográfica.

Valor: La sensibilidad fotográfica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Obtiene o establece el identificador único de la imagen.

Valor: El identificador único de la imagen.

**Returns:**
java.lang.String
### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Obtiene o establece el identificador único de la imagen.

Valor: El identificador único de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Obtiene o establece el fabricante de la lente.

Valor: El fabricante de la lente.

**Returns:**
java.lang.String
### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Obtiene o establece el fabricante de la lente.

Valor: El fabricante de la lente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Obtiene o establece el modelo de la lente.

Valor: El modelo de la lente.

**Returns:**
java.lang.String
### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Obtiene o establece el modelo de la lente.

Valor: El modelo de la lente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Obtiene o establece el número de serie de la lente.

Valor: El número de serie de la lente.

**Returns:**
java.lang.String
### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Obtiene o establece el número de serie de la lente.

Valor: El número de serie de la lente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Obtiene o establece la especificación de la lente

Valor: La especificación de la lente.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Obtiene o establece la especificación de la lente

Valor: La especificación de la lente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Obtiene o establece la fuente de luz.

Valor: La fuente de luz.

**Returns:**
int
### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Obtiene o establece la fuente de luz.

Valor: La fuente de luz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Obtiene los datos de la nota del fabricante.

Valor: Los datos de la nota del fabricante.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Obtiene o establece los datos sin procesar de la nota del fabricante.

Valor: Los datos sin procesar de la nota del fabricante.

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Obtiene o establece los datos sin procesar de la nota del fabricante.

Valor: Los datos sin procesar de la nota del fabricante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Obtiene las notas del fabricante.

Valor: Las notas del fabricante.

**Returns:**
com.aspose.imaging.exif.MakerNote[] - las notas del fabricante.

**Example: Access camera manufacturer maker notes in Jpeg image.**

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Obtiene o establece el valor máximo de apertura.

Valor: El valor máximo de apertura.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Obtiene o establece el valor máximo de apertura.

Valor: El valor máximo de apertura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Obtiene o establece el modo de medición.

Valor: El modo de medición.

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Obtiene o establece el modo de medición.

Valor: El modo de medición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Obtiene o establece la Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524.

Valor: La Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524.

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Obtiene o establece la Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524.

Valor: La Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Obtiene la orientación [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Valor: La orientación.

**Returns:**
int - la orientación.
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Establece la orientación [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Valor: La orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la orientación. |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Obtiene o establece la dimensión x del píxel.

Valor: La dimensión x del píxel.

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Obtiene o establece la dimensión x del píxel.

Valor: La dimensión x del píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Obtiene o establece la dimensión y del píxel.

Valor: La dimensión y del píxel.

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Obtiene o establece la dimensión y del píxel.

Valor: La dimensión y del píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS).

Valor: Las etiquetas EXIF (incluyendo etiquetas comunes y GPS).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS).

Valor: Las etiquetas EXIF (incluyendo etiquetas comunes y GPS).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Obtiene o establece el índice de exposición recomendado.

Valor: El índice de exposición recomendado.

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Obtiene o establece el índice de exposición recomendado.

Valor: El índice de exposición recomendado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Obtiene o establece el archivo de sonido relacionado.

Valor: El archivo de sonido relacionado.

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Obtiene o establece el archivo de sonido relacionado.

Valor: El archivo de sonido relacionado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Obtiene o establece la saturación.

Valor: La saturación.

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Obtiene o establece la saturación.

Valor: La saturación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Obtiene o establece el tipo de captura de escena.

Valor: El tipo de captura de escena.

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Obtiene o establece el tipo de captura de escena.

Valor: El tipo de captura de escena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Obtiene o establece el tipo de escena.

Valor: El tipo de escena.

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Obtiene o establece el tipo de escena.

Valor: El tipo de escena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Obtiene o establece el método de detección.

Valor: El método de detección.

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Obtiene o establece el método de detección.

Valor: El método de detección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Obtiene o establece el tipo de sensibilidad.

Valor: El tipo de sensibilidad.

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Obtiene o establece el tipo de sensibilidad.

Valor: El tipo de sensibilidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Obtiene o establece la nitidez.

Valor: La nitidez.

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Obtiene o establece la nitidez.

Valor: La nitidez.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Obtiene o establece el valor de velocidad de obturación.

Valor: El valor de velocidad de obturación.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Obtiene o establece el valor de velocidad de obturación.

Valor: El valor de velocidad de obturación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Obtiene o establece la respuesta de frecuencia espacial.

Valor: La respuesta de frecuencia espacial.

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Obtiene o establece la respuesta de frecuencia espacial.

Valor: La respuesta de frecuencia espacial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Obtiene o establece la sensibilidad espectral.

Valor: La sensibilidad espectral.

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Obtiene o establece la sensibilidad espectral.

Valor: La sensibilidad espectral.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Obtiene la sensibilidad de salida estándar

Valor: La sensibilidad de salida estándar.

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Establece la sensibilidad de salida estándar

Valor: La sensibilidad de salida estándar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Obtiene o establece el área del sujeto.

Valor: El área del sujeto.

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Obtiene o establece el área del sujeto.

Valor: El área del sujeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Obtiene o establece la distancia del sujeto.

Valor: La distancia del sujeto.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Obtiene o establece la distancia del sujeto.

Valor: La distancia del sujeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Obtiene o establece el rango de distancia del sujeto.

Valor: El rango de distancia del sujeto.

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Obtiene o establece el rango de distancia del sujeto.

Valor: El rango de distancia del sujeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Obtiene o establece la ubicación del sujeto.

Valor: La ubicación del sujeto.

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Obtiene o establece la ubicación del sujeto.

Valor: La ubicación del sujeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTime.

Valor: Las fracciones de segundo para la etiqueta DateTime.

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTime.

Valor: Las fracciones de segundo para la etiqueta DateTime.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized.

Valor: Las fracciones de segundo para la etiqueta DateTimeDigitized.

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized.

Valor: Las fracciones de segundo para la etiqueta DateTimeDigitized.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal.

Valor: Las fracciones de segundo para la etiqueta DateTimeOriginal.

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal.

Valor: Las fracciones de segundo para la etiqueta DateTimeOriginal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Obtiene o establece el comentario del usuario.

Valor: El comentario del usuario.

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Obtiene o establece el comentario del usuario.

Valor: El comentario del usuario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Obtiene o establece el balance de blancos.

Valor: El balance de blancos.

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Obtiene o establece el balance de blancos.

Valor: El balance de blancos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Obtiene o establece la cromaticidad del punto blanco de la imagen.

Valor: La cromaticidad del punto blanco de la imagen.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Obtiene o establece la cromaticidad del punto blanco de la imagen.

Valor: La cromaticidad del punto blanco de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Obtiene o establece etiquetas, que pertenecen a la sección común. Esto se aplica solo a imágenes jpeg, en formato tiff se utilizan tiffOptions en su lugar.

Valor: Las etiquetas de la sección común.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Obtiene o establece etiquetas, que pertenecen a la sección común. Esto se aplica solo a imágenes jpeg, en formato tiff se utilizan tiffOptions en su lugar.

Valor: Las etiquetas de la sección común.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Obtiene o establece etiquetas que pertenecen solo a la sección EXIF.

Valor: Las etiquetas de la sección EXIF.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Obtiene o establece etiquetas que pertenecen solo a la sección EXIF.

Valor: Las etiquetas de la sección EXIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Obtiene o establece etiquetas, que pertenecen solo a la sección GPS.

Valor: Las etiquetas GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Obtiene o establece etiquetas, que pertenecen solo a la sección GPS.

Valor: Las etiquetas GPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getThumbnail() {#getThumbnail--}
```
public final RasterImage getThumbnail()
```


Obtiene la imagen en miniatura.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the thumbnail image.
### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.imaging.RasterImage-}
```
public final void setThumbnail(RasterImage value)
```


Establece la imagen en miniatura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.imaging/rasterimage) | la imagen en miniatura. |

### getXResolutionInt() {#getXResolutionInt--}
```
public final int getXResolutionInt()
```


Obtiene la resolución x.

Valor: La resolución x.

**Returns:**
int - la resolución x.
### setXResolution(int value) {#setXResolution-int-}
```
public final void setXResolution(int value)
```


Establece la resolución x.

Valor: La resolución x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la resolución x. |

### getYResolutionInt() {#getYResolutionInt--}
```
public final int getYResolutionInt()
```


Obtiene la resolución y.

Valor: La resolución y.

**Returns:**
int - la resolución y.
### setYResolution(int value) {#setYResolution-int-}
```
public final void setYResolution(int value)
```


Establece la resolución y.

Valor: La resolución y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la resolución y. |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


Eliminar etiqueta del contenedor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagId | int | El identificador de etiqueta a eliminar. |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


Obtiene el valor de la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | int | La clave de etiqueta [ExifProperties](../../com.aspose.imaging.exif/exifproperties). |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
