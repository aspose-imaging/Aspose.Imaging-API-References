---
title: "ExifData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Контейнер данных EXIF."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.exif/exifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller)

**All Implemented Interfaces:**
[com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class ExifData extends TiffDataTypeController implements IImageMetadataFormat
```

Контейнер данных EXIF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ExifData()](#ExifData--) | Инициализирует новый экземпляр класса `ExifData`. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Инициализирует новый экземпляр класса `ExifData` с данными из массива. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Инициализирует новый экземпляр класса `ExifData` с данными из массива. |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | Инициализирует новый экземпляр класса [ExifData](../../com.aspose.imaging.exif/exifdata) с данными из массива. |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | Инициализирует новый экземпляр класса [ExifData](../../com.aspose.imaging.exif/exifdata). |
## Методы

| Метод | Описание |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | Получает или задает значение, указывающее, является ли поток EXIF‑данных, из которого создано, big endian. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Получает или задает значение, указывающее, является ли поток EXIF‑данных, из которого создано, big endian. |
| [getMake()](#getMake--) | Получает производителя записывающего оборудования. |
| [setMake(String value)](#setMake-java.lang.String-) | Задает производителя записывающего оборудования. |
| [getApertureValue()](#getApertureValue--) | Получает или задает значение диафрагмы. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает значение диафрагмы. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Получает или задает серийный номер корпуса камеры. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Получает или задает серийный номер корпуса камеры. |
| [getBrightnessValue()](#getBrightnessValue--) | Получает или задает значение яркости. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Получает или задает значение яркости. |
| [getCFAPattern()](#getCFAPattern--) | Получает или задает шаблон CFA. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | Получает или задает шаблон CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Получает или задает имя владельца камеры |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Получает или задает имя владельца камеры |
| [getColorSpace()](#getColorSpace--) | Получает или задает цветовое пространство. |
| [setColorSpace(int value)](#setColorSpace-int-) | Получает или задает цветовое пространство. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Получает или задает конфигурацию компонентов. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Получает или задает конфигурацию компонентов. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Получает или задает сжатые биты на пиксель. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает сжатые биты на пиксель. |
| [getContrast()](#getContrast--) | Получает или задает контраст. |
| [setContrast(int value)](#setContrast-int-) | Получает или задает контраст. |
| [getCustomRendered()](#getCustomRendered--) | Получает или задает пользовательский рендеринг. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Получает или задает пользовательский рендеринг. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Получает или задает дату и время оцифровки. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Получает или задает дату и время оцифровки. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Получает или задает оригинальную дату и время. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Получает или задает оригинальную дату и время. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Получает или задает описание настроек устройства |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Получает или задает описание настроек устройства |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Получает или задает коэффициент цифрового увеличения. |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает коэффициент цифрового увеличения. |
| [getExifVersion()](#getExifVersion--) | Получает или задает версию EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | Получает или задает версию EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Получает или задает значение смещения экспозиции. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Получает или задает значение смещения экспозиции. |
| [getExposureIndex()](#getExposureIndex--) | Получает или задает индекс экспозиции. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает индекс экспозиции. |
| [getExposureMode()](#getExposureMode--) | Получает или задает режим экспозиции. |
| [setExposureMode(int value)](#setExposureMode-int-) | Получает или задает режим экспозиции. |
| [getExposureProgram()](#getExposureProgram--) | Получает или задает программу экспозиции. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Получает или задает программу экспозиции. |
| [getExposureTime()](#getExposureTime--) | Получает или задает время экспозиции. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает время экспозиции. |
| [getFNumber()](#getFNumber--) | Получает или задает значение f-числа. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает значение f-числа. |
| [getFileSource()](#getFileSource--) | Получает или задает тип источника файла. |
| [setFileSource(byte value)](#setFileSource-byte-) | Получает или задает тип источника файла. |
| [getFlash()](#getFlash--) | Получает или задает вспышку. |
| [setFlash(int value)](#setFlash-int-) | Получает или задает вспышку. |
| [getFlashEnergy()](#getFlashEnergy--) | Получает или задает энергию вспышки. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает энергию вспышки. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Получает или задает версию flash pix. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Получает или задает версию flash pix. |
| [getFocalLength()](#getFocalLength--) | Получает или задает фокусное расстояние. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает фокусное расстояние. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | Получает или задает фокусное расстояние в пленке 35 мм. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | Получает или задает фокусное расстояние в пленке 35 мм. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Получает или задает единицу разрешения фокальной плоскости. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Получает или задает единицу разрешения фокальной плоскости. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Получает или задает разрешение по оси X фокальной плоскости. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает разрешение по оси X фокальной плоскости. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Получает или задает разрешение по оси Y фокальной плоскости. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает разрешение по оси Y фокальной плоскости. |
| [getGPSAltitude()](#getGPSAltitude--) | Получает или задает высоту GPS. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает высоту GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Получает или задает высоту GPS, используемую в качестве эталонной высоты. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Получает или задает высоту GPS, используемую в качестве эталонной высоты. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | Получает или задает информацию о области GPS. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | Получает или задает информацию о области GPS. |
| [getGPSDOP()](#getGPSDOP--) | Получает или задает GPS DOP (степень точности данных). |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает GPS DOP (степень точности данных). |
| [getGPSDestBearing()](#getGPSDestBearing--) | Получает или задает GPS-азимут к целевой точке. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает GPS-азимут к целевой точке. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Получает или задает GPS-референцию, используемую для определения азимута к целевой точке. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Получает или задает GPS-референцию, используемую для определения азимута к целевой точке. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Получает или задает GPS-расстояние до целевой точки. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает GPS-расстояние до целевой точки. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Получает или задает GPS-единицу, используемую для выражения расстояния до целевой точки. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Получает или задает GPS-единицу, используемую для выражения расстояния до целевой точки. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Получает или задает GPS-широту целевой точки. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задает GPS-широту целевой точки. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Получает или задает GPS-значение, указывающее, является ли широта целевой точки северной или южной. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Получает или задает GPS-значение, указывающее, является ли широта целевой точки северной или южной. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Получает или задает GPS-долготу целевой точки. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задает GPS-долготу целевой точки. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Получает или задает GPS-значение, указывающее, является ли долгота целевой точки восточной или западной. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Получает или задает GPS-значение, указывающее, является ли долгота целевой точки восточной или западной. |
| [getGPSDifferential()](#getGPSDifferential--) | Получает или задает GPS-значение, указывающее, применяется ли дифференциальная коррекция к GPS-приемнику. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | Получает или задает GPS-значение, указывающее, применяется ли дифференциальная коррекция к GPS-приемнику. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Получает или задает GPS-направление изображения при его захвате. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает GPS-направление изображения при его захвате. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Получает или задает GPS-референцию для определения направления изображения при его захвате. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Получает или задает GPS-референцию для определения направления изображения при его захвате. |
| [getGPSDateStamp()](#getGPSDateStamp--) | Получает или задает GPS-строку, записывающую дату и время относительно UTC (координированного всемирного времени). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | Получает или задает GPS-строку, записывающую дату и время относительно UTC (координированного всемирного времени). |
| [getGPSLatitude()](#getGPSLatitude--) | Получает или задает GPS-широту. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задает GPS-широту. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | Получает или задает, является ли GPS-широта северной или южной. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | Получает или задает, является ли GPS-широта северной или южной. |
| [getGPSLongitude()](#getGPSLongitude--) | Получает или задает GPS-долготу. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задает GPS-долготу. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | Получает или задает, является ли GPS-долгота восточной или западной. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | Получает или задает, является ли GPS-долгота восточной или западной. |
| [getGPSMapDatum()](#getGPSMapDatum--) | Получает или задает GPS-геодезические данные, используемые GPS-приемником. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | Получает или задает GPS-геодезические данные, используемые GPS-приемником. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | Получает или задает режим измерения GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | Получает или задает режим измерения GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Получает или задает GPS-строку, записывающую название метода, используемого для определения местоположения. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Получает или задает GPS-строку, записывающую название метода, используемого для определения местоположения. |
| [getGPSSatellites()](#getGPSSatellites--) | Получает или задает GPS-спутники, используемые для измерений. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Получает или задает GPS-спутники, используемые для измерений. |
| [getGPSSpeed()](#getGPSSpeed--) | Получает или задает скорость движения GPS-приемника. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает скорость движения GPS-приемника. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | Получает или задает единицу, используемую для выражения скорости движения GPS-приемника. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | Получает или задает единицу, используемую для выражения скорости движения GPS-приемника. |
| [getGPSStatus()](#getGPSStatus--) | Получает или задает статус GPS-приемника при записи изображения. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Получает или задает статус GPS-приемника при записи изображения. |
| [getGPSTimestamp()](#getGPSTimestamp--) | Получает или задает GPS-время в формате UTC (координированное всемирное время). |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задает GPS-время в формате UTC (координированное всемирное время). |
| [getGPSTrack()](#getGPSTrack--) | Получает или задает направление движения GPS‑приёмника. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | Получает или задает направление движения GPS‑приёмника. |
| [getGPSTrackRef()](#getGPSTrackRef--) | Получает или задает ссылку для указания направления движения GPS‑приёмника. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | Получает или задает ссылку для указания направления движения GPS‑приёмника. |
| [getGPSVersionID()](#getGPSVersionID--) | Получает или задает идентификатор версии GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | Получает или задает идентификатор версии GPS. |
| [getGainControl()](#getGainControl--) | Получает или задает степень общей регулировки усиления изображения. |
| [setGainControl(int value)](#setGainControl-int-) | Получает или задает степень общей регулировки усиления изображения. |
| [getGamma()](#getGamma--) | Получает или задает гамму. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает гамму. |
| [getISOSpeed()](#getISOSpeed--) | Получает или задает скорость ISO |
| [setISOSpeed(long value)](#setISOSpeed-long-) | Получает или задает скорость ISO |
| [getISOSpeedValue()](#getISOSpeedValue--) | Получает значение скорости ISO. |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | Задаёт значение скорости ISO. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | Получает или задает значение латитуды yyy скорости ISO камеры или входного устройства, определённое в ISO 12232. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | Получает или задает значение латитуды yyy скорости ISO камеры или входного устройства, определённое в ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | Получает или задает значение латитуды zzz скорости ISO камеры или входного устройства, определённое в ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | Получает или задает значение латитуды zzz скорости ISO камеры или входного устройства, определённое в ISO 12232. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Получает или задает фоточувствительность. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Получает или задает фоточувствительность. |
| [getImageUniqueID()](#getImageUniqueID--) | Получает или задает уникальный идентификатор изображения. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Получает или задает уникальный идентификатор изображения. |
| [getLensMake()](#getLensMake--) | Получает или задает производителя объектива. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Получает или задает производителя объектива. |
| [getLensModel()](#getLensModel--) | Получает или задает модель объектива. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Получает или задает модель объектива. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Получает или задает серийный номер объектива. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Получает или задает серийный номер объектива. |
| [getLensSpecification()](#getLensSpecification--) | Получает или задает спецификацию объектива |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задает спецификацию объектива |
| [getLightSource()](#getLightSource--) | Получает или задает источник света. |
| [setLightSource(int value)](#setLightSource-int-) | Получает или задает источник света. |
| [getMakerNoteData()](#getMakerNoteData--) | Получает данные примечаний производителя. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Получает или задает необработанные данные примечаний производителя. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Получает или задает необработанные данные примечаний производителя. |
| [getMakerNotes()](#getMakerNotes--) | Получает примечания производителя. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Получает или задает значение максимальной диафрагмы. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает значение максимальной диафрагмы. |
| [getMeteringMode()](#getMeteringMode--) | Получает или задает режим измерения экспозиции. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Получает или задает режим измерения экспозиции. |
| [getOECF()](#getOECF--) | Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524. |
| [setOECF(byte[] value)](#setOECF-byte---) | Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524. |
| [getOrientation()](#getOrientation--) | Получает ориентацию [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [setOrientation(int value)](#setOrientation-int-) | Задаёт ориентацию [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [getPixelXDimension()](#getPixelXDimension--) | Получает или задает размер пикселя по оси x. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Получает или задает размер пикселя по оси x. |
| [getPixelYDimension()](#getPixelYDimension--) | Получает или задает размер пикселя по оси y. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Получает или задает размер пикселя по оси y. |
| [getProperties()](#getProperties--) | Получает или задает все теги EXIF (включая общие и GPS-теги). |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Получает или задает все теги EXIF (включая общие и GPS-теги). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Получает или задает рекомендуемый индекс экспозиции. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Получает или задает рекомендуемый индекс экспозиции. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | Получает или задает связанный звуковой файл. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | Получает или задает связанный звуковой файл. |
| [getSaturation()](#getSaturation--) | Получает или задает насыщенность. |
| [setSaturation(int value)](#setSaturation-int-) | Получает или задает насыщенность. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Получает или задает тип захвата сцены. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Получает или задает тип захвата сцены. |
| [getSceneType()](#getSceneType--) | Получает или задает тип сцены. |
| [setSceneType(byte value)](#setSceneType-byte-) | Получает или задает тип сцены. |
| [getSensingMethod()](#getSensingMethod--) | Получает или задает метод измерения. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Получает или задает метод измерения. |
| [getSensitivityType()](#getSensitivityType--) | Получает или задает тип чувствительности. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Получает или задает тип чувствительности. |
| [getSharpness()](#getSharpness--) | Получает или задает резкость. |
| [setSharpness(int value)](#setSharpness-int-) | Получает или задает резкость. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Получает или задает значение скорости затвора. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Получает или задает значение скорости затвора. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Получает или задает отклик пространственной частоты. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Получает или задает отклик пространственной частоты. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Получает или задает спектральную чувствительность. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Получает или задает спектральную чувствительность. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Получает стандартную чувствительность вывода |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Задает стандартную чувствительность вывода |
| [getSubjectArea()](#getSubjectArea--) | Получает или задает область объекта. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Получает или задает область объекта. |
| [getSubjectDistance()](#getSubjectDistance--) | Получает или задает расстояние до объекта. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает расстояние до объекта. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Получает или задает диапазон расстояний до объекта. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Получает или задает диапазон расстояний до объекта. |
| [getSubjectLocation()](#getSubjectLocation--) | Получает или задает местоположение объекта. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Получает или задает местоположение объекта. |
| [getSubsecTime()](#getSubsecTime--) | Получает или задает доли секунды для тега DateTime. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | Получает или задает доли секунды для тега DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | Получает или задает доли секунды для тега DateTimeDigitized. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | Получает или задает доли секунды для тега DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | Получает или задает доли секунды для тега DateTimeOriginal. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | Получает или задает доли секунды для тега DateTimeOriginal. |
| [getUserComment()](#getUserComment--) | Получает или задает пользовательский комментарий. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Получает или задает пользовательский комментарий. |
| [getWhiteBalance()](#getWhiteBalance--) | Получает или задает баланс белого. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Получает или задает баланс белого. |
| [getWhitePoint()](#getWhitePoint--) | Получает или задает хроматичность белой точки изображения. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задает хроматичность белой точки изображения. |
| [getCommonTags()](#getCommonTags--) | Получает или задает теги, которые относятся к общему разделу. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Получает или задает теги, которые относятся к общему разделу. |
| [getExifTags()](#getExifTags--) | Получает или задает теги, которые относятся только к разделу EXIF. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Получает или задает теги, которые относятся только к разделу EXIF. |
| [getGPSTags()](#getGPSTags--) | Получает или задает теги, которые относятся только к разделу GPS. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Получает или задает теги, которые относятся только к разделу GPS. |
| [getThumbnail()](#getThumbnail--) | Получает изображение миниатюры. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | Задает изображение миниатюры. |
| [getXResolutionInt()](#getXResolutionInt--) | Получает разрешение по оси X. |
| [setXResolution(int value)](#setXResolution-int-) | Задает разрешение по оси X. |
| [getYResolutionInt()](#getYResolutionInt--) | Получает разрешение по оси Y. |
| [setYResolution(int value)](#setYResolution-int-) | Задает разрешение по оси Y. |
| [removeTag(int tagId)](#removeTag-int-) | Удалить тег из контейнера |
| [getTagValue(int key)](#getTagValue-int-) | Получает значение тега. |

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


Инициализирует новый экземпляр класса `ExifData`.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Инициализирует новый экземпляр класса `ExifData` с данными из массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Массив тегов EXIF вместе с общими тегами и тегами GPS. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Инициализирует новый экземпляр класса `ExifData` с данными из массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Общие теги. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Теги EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Теги GPS. |

### ExifData(ExifData exifdata) {#ExifData-com.aspose.imaging.exif.ExifData-}
```
public ExifData(ExifData exifdata)
```


Инициализирует новый экземпляр класса [ExifData](../../com.aspose.imaging.exif/exifdata) с данными из массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | Массив тегов EXIF вместе с общими тегами и тегами GPS. |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


Инициализирует новый экземпляр класса [ExifData](../../com.aspose.imaging.exif/exifdata).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| binaryData | byte[] | Бинарные данные. |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


Получает или задает значение, указывающее, является ли поток EXIF‑данных, из которого создано, big endian.

Значение: `true`, если поток EXIF‑данных, из которого создано, использует порядок байтов big endian; иначе `false`.

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Получает или задает значение, указывающее, является ли поток EXIF‑данных, из которого создано, big endian.

Значение: `true`, если поток EXIF‑данных, из которого создано, использует порядок байтов big endian; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getMake() {#getMake--}
```
public final String getMake()
```


Получает производителя записывающего оборудования.

Значение: Производитель записывающего оборудования.

**Returns:**
java.lang.String — производитель записывающего оборудования.
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Задает производителя записывающего оборудования.

Значение: Производитель записывающего оборудования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | производитель записывающего оборудования. |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Получает или задает значение диафрагмы.

Значение: Значение диафрагмы.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Получает или задает значение диафрагмы.

Значение: Значение диафрагмы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Получает или задает серийный номер корпуса камеры.

Значение: Серийный номер корпуса.

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Получает или задает серийный номер корпуса камеры.

Значение: Серийный номер корпуса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Получает или задает значение яркости.

Значение: Значение яркости.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Получает или задает значение яркости.

Значение: Значение яркости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


Получает или задает шаблон CFA.

Значение: CFA pattern.

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


Получает или задает шаблон CFA.

Значение: CFA pattern.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Получает или задает имя владельца камеры

Значение: имя владельца камеры.

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Получает или задает имя владельца камеры

Значение: имя владельца камеры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Получает или задает цветовое пространство.

Значение: цветовое пространство.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Получает или задает цветовое пространство.

Значение: цветовое пространство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Получает или задает конфигурацию компонентов.

Значение: конфигурация компонентов.

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Получает или задает конфигурацию компонентов.

Значение: конфигурация компонентов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Получает или задает сжатые биты на пиксель.

Значение: сжатые биты на пиксель.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Получает или задает сжатые биты на пиксель.

Значение: сжатые биты на пиксель.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getContrast() {#getContrast--}
```
public int getContrast()
```


Получает или задает контраст.

Значение: контраст.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Получает или задает контраст.

Значение: контраст.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Получает или задает пользовательский рендеринг.

Значение: пользовательская отрисовка.

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Получает или задает пользовательский рендеринг.

Значение: пользовательская отрисовка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Получает или задает дату и время оцифровки.

Значение: дата и время оцифровки.

**Returns:**
java.lang.String
### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Получает или задает дату и время оцифровки.

Значение: дата и время оцифровки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Получает или задает оригинальную дату и время.

Значение: оригинальная дата и время.

**Returns:**
java.lang.String
### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Получает или задает оригинальную дату и время.

Значение: оригинальная дата и время.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Получает или задает описание настроек устройства

Значение: описание настроек устройства.

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Получает или задает описание настроек устройства

Значение: описание настроек устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Получает или задает коэффициент цифрового увеличения.

Значение: коэффициент цифрового зума.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Получает или задает коэффициент цифрового увеличения.

Значение: коэффициент цифрового зума.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


Получает или задает версию EXIF.

Значение: версия EXIF.

**Returns:**
byte[]
### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


Получает или задает версию EXIF.

Значение: версия EXIF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Получает или задает значение смещения экспозиции.

Значение: значение смещения экспозиции.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Получает или задает значение смещения экспозиции.

Значение: значение смещения экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Получает или задает индекс экспозиции.

Значение: индекс экспозиции.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Получает или задает индекс экспозиции.

Значение: индекс экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Получает или задает режим экспозиции.

Значение: режим экспозиции.

**Returns:**
int
### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Получает или задает режим экспозиции.

Значение: режим экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Получает или задает программу экспозиции.

Значение: программа экспозиции.

**Returns:**
int
### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Получает или задает программу экспозиции.

Значение: программа экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Получает или задает время экспозиции.

Значение: время экспозиции.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Получает или задает время экспозиции.

Значение: время экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


Получает или задает значение f-числа.

Значение: число F.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFNumber(TiffRational value) {#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


Получает или задает значение f-числа.

Значение: число F.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Получает или задает тип источника файла.

Значение: тип источника файла.

**Returns:**
byte
### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Получает или задает тип источника файла.

Значение: тип источника файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFlash() {#getFlash--}
```
public int getFlash()
```


Получает или задает вспышку.

Значение: вспышка.

**Returns:**
int
### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Получает или задает вспышку.

Значение: вспышка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Получает или задает энергию вспышки.

Значение: энергия вспышки.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Получает или задает энергию вспышки.

Значение: энергия вспышки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Получает или задает версию flash pix.

Значение: версия flash pix.

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Получает или задает версию flash pix.

Значение: версия flash pix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Получает или задает фокусное расстояние.

Значение: длина фокуса.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Получает или задает фокусное расстояние.

Значение: длина фокуса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


Получает или задает фокусное расстояние в пленке 35 мм.

Значение: фокусное расстояние в 35 мм пленке.

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


Получает или задает фокусное расстояние в пленке 35 мм.

Значение: фокусное расстояние в 35 мм пленке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Получает или задает единицу разрешения фокальной плоскости.

Значение: единица разрешения фокальной плоскости.

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Получает или задает единицу разрешения фокальной плоскости.

Значение: единица разрешения фокальной плоскости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Получает или задает разрешение по оси X фокальной плоскости.

Значение: разрешение по оси x в фокальной плоскости.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Получает или задает разрешение по оси X фокальной плоскости.

Значение: разрешение по оси x в фокальной плоскости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Получает или задает разрешение по оси Y фокальной плоскости.

Значение: разрешение по оси y в фокальной плоскости.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Получает или задает разрешение по оси Y фокальной плоскости.

Значение: разрешение по оси y в фокальной плоскости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


Получает или задает высоту GPS.

Значение: высота GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


Получает или задает высоту GPS.

Значение: высота GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Получает или задает высоту GPS, используемую в качестве эталонной высоты.

Значение: высота GPS, используемая в качестве эталонной высоты.

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Получает или задает высоту GPS, используемую в качестве эталонной высоты.

Значение: высота GPS, используемая в качестве эталонной высоты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


Получает или задает информацию о области GPS.

Значение: информация о зоне GPS.

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


Получает или задает информацию о области GPS.

Значение: информация о зоне GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


Получает или задает GPS DOP (степень точности данных).

Значение: GPS DOP (степень точности данных).

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


Получает или задает GPS DOP (степень точности данных).

Значение: GPS DOP (степень точности данных).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Получает или задает GPS-азимут к целевой точке.

Значение: азимут GPS к целевой точке.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Получает или задает GPS-азимут к целевой точке.

Значение: азимут GPS к целевой точке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Получает или задает GPS-референцию, используемую для определения азимута к целевой точке.

Значение: ссылка GPS, используемая для определения азимута к целевой точке.

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Получает или задает GPS-референцию, используемую для определения азимута к целевой точке.

Значение: ссылка GPS, используемая для определения азимута к целевой точке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Получает или задает GPS-расстояние до целевой точки.

Значение: расстояние GPS до целевой точки.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Получает или задает GPS-расстояние до целевой точки.

Значение: расстояние GPS до целевой точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Получает или задает GPS-единицу, используемую для выражения расстояния до целевой точки.

Значение: единица измерения GPS, используемая для выражения расстояния до целевой точки.

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Получает или задает GPS-единицу, используемую для выражения расстояния до целевой точки.

Значение: единица измерения GPS, используемая для выражения расстояния до целевой точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Получает или задает GPS-широту целевой точки.

Значение: широта GPS целевой точки.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Получает или задает GPS-широту целевой точки.

Значение: широта GPS целевой точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Получает или задает GPS-значение, указывающее, является ли широта целевой точки северной или южной.

Значение: значение GPS, указывающее, является ли широта целевой точки северной или южной.

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Получает или задает GPS-значение, указывающее, является ли широта целевой точки северной или южной.

Значение: значение GPS, указывающее, является ли широта целевой точки северной или южной.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Получает или задает GPS-долготу целевой точки.

Значение: долгота GPS целевой точки.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Получает или задает GPS-долготу целевой точки.

Значение: долгота GPS целевой точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Получает или задает GPS-значение, указывающее, является ли долгота целевой точки восточной или западной.

Значение: значение GPS, указывающее, является ли долгота целевой точки восточной или западной.

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Получает или задает GPS-значение, указывающее, является ли долгота целевой точки восточной или западной.

Значение: значение GPS, указывающее, является ли долгота целевой точки восточной или западной.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


Получает или задает GPS-значение, указывающее, применяется ли дифференциальная коррекция к GPS-приемнику.

Значение: значение GPS, указывающее, применяется ли дифференциальная коррекция к GPS‑приёмнику.

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


Получает или задает GPS-значение, указывающее, применяется ли дифференциальная коррекция к GPS-приемнику.

Значение: значение GPS, указывающее, применяется ли дифференциальная коррекция к GPS‑приёмнику.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Получает или задает GPS-направление изображения при его захвате.

Значение: направление GPS изображения при его захвате.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Получает или задает GPS-направление изображения при его захвате.

Значение: направление GPS изображения при его захвате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Получает или задает GPS-референцию для определения направления изображения при его захвате.

Значение: ссылка GPS для указания направления изображения при его захвате.

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Получает или задает GPS-референцию для определения направления изображения при его захвате.

Значение: ссылка GPS для указания направления изображения при его захвате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


Получает или задает GPS-строку, записывающую дату и время относительно UTC (координированного всемирного времени).

Значение: строка GPS, записывающая дату и время относительно UTC (координированного всемирного времени).

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


Получает или задает GPS-строку, записывающую дату и время относительно UTC (координированного всемирного времени).

Значение: строка GPS, записывающая дату и время относительно UTC (координированного всемирного времени).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


Получает или задает GPS-широту.

Значение: широта GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


Получает или задает GPS-широту.

Значение: широта GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


Получает или задает, является ли GPS-широта северной или южной.

Значение: широта GPS — северная или южная.

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


Получает или задает, является ли GPS-широта северной или южной.

Значение: широта GPS — северная или южная.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


Получает или задает GPS-долготу.

Значение: долгота GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


Получает или задает GPS-долготу.

Значение: долгота GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


Получает или задает, является ли GPS-долгота восточной или западной.

Значение: долгота GPS — восточная или западная.

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


Получает или задает, является ли GPS-долгота восточной или западной.

Значение: долгота GPS — восточная или западная.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


Получает или задает GPS-геодезические данные, используемые GPS-приемником.

Значение: геодезические данные GPS, используемые GPS‑приёмником.

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


Получает или задает GPS-геодезические данные, используемые GPS-приемником.

Значение: геодезические данные GPS, используемые GPS‑приёмником.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


Получает или задает режим измерения GPS.

Значение: режим измерения GPS.

**Returns:**
java.lang.String
### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


Получает или задает режим измерения GPS.

Значение: режим измерения GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Получает или задает GPS-строку, записывающую название метода, используемого для определения местоположения.

Значение: строка GPS, записывающая название метода, используемого для определения местоположения.

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Получает или задает GPS-строку, записывающую название метода, используемого для определения местоположения.

Значение: строка GPS, записывающая название метода, используемого для определения местоположения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Получает или задает GPS-спутники, используемые для измерений.

Значение: GPS‑спутники, используемые для измерений.

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Получает или задает GPS-спутники, используемые для измерений.

Значение: GPS‑спутники, используемые для измерений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


Получает или задает скорость движения GPS-приемника.

Значение: скорость перемещения GPS‑приёмника.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


Получает или задает скорость движения GPS-приемника.

Значение: скорость перемещения GPS‑приёмника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


Получает или задает единицу, используемую для выражения скорости движения GPS-приемника.

Значение: единица измерения скорости перемещения GPS‑приёмника.

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


Получает или задает единицу, используемую для выражения скорости движения GPS-приемника.

Значение: единица измерения скорости перемещения GPS‑приёмника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Получает или задает статус GPS-приемника при записи изображения.

Значение: состояние GPS‑приёмника при записи изображения.

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Получает или задает статус GPS-приемника при записи изображения.

Значение: состояние GPS‑приёмника при записи изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


Получает или задает GPS-время в формате UTC (координированное всемирное время).

Значение: время GPS в формате UTC (Coordinated Universal Time).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


Получает или задает GPS-время в формате UTC (координированное всемирное время).

Значение: время GPS в формате UTC (Coordinated Universal Time).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


Получает или задает направление движения GPS‑приёмника.

Значение: направление перемещения GPS‑приёмника.

**Returns:**
java.lang.String
### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


Получает или задает направление движения GPS‑приёмника.

Значение: направление перемещения GPS‑приёмника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


Получает или задает ссылку для указания направления движения GPS‑приёмника.

Значение: ссылка для указания направления перемещения GPS‑приёмника.

**Returns:**
java.lang.String
### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


Получает или задает ссылку для указания направления движения GPS‑приёмника.

Значение: ссылка для указания направления перемещения GPS‑приёмника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


Получает или задает идентификатор версии GPS.

Значение: идентификатор версии GPS.

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


Получает или задает идентификатор версии GPS.

Значение: идентификатор версии GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Получает или задает степень общей регулировки усиления изображения.

Значение: степень общей регулировки усиления изображения.

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Получает или задает степень общей регулировки усиления изображения.

Значение: степень общей регулировки усиления изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Получает или задает гамму.

Значение: значение гаммы.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Получает или задает гамму.

Значение: значение гаммы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


Получает или задает скорость ISO

Значение: ISO‑скорость.

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


Получает или задает скорость ISO

Значение: ISO‑скорость.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


Получает значение скорости ISO.

Значение: значение ISO‑скорости.

**Returns:**
long - значение ISO‑скорости.
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


Задаёт значение скорости ISO.

Значение: значение ISO‑скорости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | значение ISO‑скорости. |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


Получает или задает значение латитуды yyy скорости ISO камеры или входного устройства, определённое в ISO 12232.

Значение: значение ISO‑speed latitude yyy камеры или входного устройства, определённое в ISO 12232.

Этот тег не должен записываться без ISOSpeed и ISOSpeedLatitudeZZZ.

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


Получает или задает значение латитуды yyy скорости ISO камеры или входного устройства, определённое в ISO 12232.

Значение: значение ISO‑speed latitude yyy камеры или входного устройства, определённое в ISO 12232.

Этот тег не должен записываться без ISOSpeed и ISOSpeedLatitudeZZZ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


Получает или задает значение латитуды zzz скорости ISO камеры или входного устройства, определённое в ISO 12232.

Значение: значение ISO‑speed latitude zzz камеры или входного устройства, определённое в ISO 12232.

Этот тег не должен записываться без ISOSpeed и ISOSpeedLatitudeYYY.

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


Получает или задает значение латитуды zzz скорости ISO камеры или входного устройства, определённое в ISO 12232.

Значение: значение ISO‑speed latitude zzz камеры или входного устройства, определённое в ISO 12232.

Этот тег не должен записываться без ISOSpeed и ISOSpeedLatitudeYYY.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Получает или задает фоточувствительность.

Значение: фоточувствительность.

**Returns:**
long
### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Получает или задает фоточувствительность.

Значение: фоточувствительность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Получает или задает уникальный идентификатор изображения.

Значение: уникальный идентификатор изображения.

**Returns:**
java.lang.String
### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Получает или задает уникальный идентификатор изображения.

Значение: уникальный идентификатор изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Получает или задает производителя объектива.

Значение: изготовитель объектива.

**Returns:**
java.lang.String
### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Получает или задает производителя объектива.

Значение: изготовитель объектива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Получает или задает модель объектива.

Значение: модель объектива.

**Returns:**
java.lang.String
### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Получает или задает модель объектива.

Значение: модель объектива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Получает или задает серийный номер объектива.

Значение: серийный номер объектива.

**Returns:**
java.lang.String
### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Получает или задает серийный номер объектива.

Значение: серийный номер объектива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Получает или задает спецификацию объектива

Значение: спецификация объектива.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Получает или задает спецификацию объектива

Значение: спецификация объектива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Получает или задает источник света.

Значение: источник света.

**Returns:**
int
### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Получает или задает источник света.

Значение: источник света.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Получает данные примечаний производителя.

Значение: данные maker note.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Получает или задает необработанные данные примечаний производителя.

Значение: необработанные данные maker note.

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Получает или задает необработанные данные примечаний производителя.

Значение: необработанные данные maker note.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Получает примечания производителя.

Значение: примечания производителя.

**Returns:**
com.aspose.imaging.exif.MakerNote[] - примечания производителя.

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


Получает или задает значение максимальной диафрагмы.

Значение: максимальное значение диафрагмы.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Получает или задает значение максимальной диафрагмы.

Значение: максимальное значение диафрагмы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Получает или задает режим измерения экспозиции.

Значение: режим измерения.

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Получает или задает режим измерения экспозиции.

Значение: режим измерения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524.

Значение: опто-электрическая функция преобразования (OECF), указанная в ISO 14524.

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524.

Значение: опто-электрическая функция преобразования (OECF), указанная в ISO 14524.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Получает ориентацию [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Значение: ориентация.

**Returns:**
int - ориентация.
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Задаёт ориентацию [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Значение: ориентация.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | ориентация. |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Получает или задает размер пикселя по оси x.

Значение: размерность пикселя по оси x.

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Получает или задает размер пикселя по оси x.

Значение: размерность пикселя по оси x.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Получает или задает размер пикселя по оси y.

Значение: размерность пикселя по оси y.

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Получает или задает размер пикселя по оси y.

Значение: размерность пикселя по оси y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Получает или задает все теги EXIF (включая общие и GPS-теги).

Значение: теги EXIF (включая общие и GPS-теги).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Получает или задает все теги EXIF (включая общие и GPS-теги).

Значение: теги EXIF (включая общие и GPS-теги).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Получает или задает рекомендуемый индекс экспозиции.

Значение: рекомендованный индекс экспозиции.

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Получает или задает рекомендуемый индекс экспозиции.

Значение: рекомендованный индекс экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


Получает или задает связанный звуковой файл.

Значение: связанный звуковой файл.

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


Получает или задает связанный звуковой файл.

Значение: связанный звуковой файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Получает или задает насыщенность.

Значение: насыщенность.

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Получает или задает насыщенность.

Значение: насыщенность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Получает или задает тип захвата сцены.

Значение: тип захвата сцены.

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Получает или задает тип захвата сцены.

Значение: тип захвата сцены.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Получает или задает тип сцены.

Значение: тип сцены.

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Получает или задает тип сцены.

Значение: тип сцены.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Получает или задает метод измерения.

Значение: метод сенсинга.

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Получает или задает метод измерения.

Значение: метод сенсинга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Получает или задает тип чувствительности.

Значение: тип чувствительности.

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Получает или задает тип чувствительности.

Значение: тип чувствительности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Получает или задает резкость.

Значение: резкость.

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Получает или задает резкость.

Значение: резкость.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Получает или задает значение скорости затвора.

Значение: значение скорости затвора.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Получает или задает значение скорости затвора.

Значение: значение скорости затвора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Получает или задает отклик пространственной частоты.

Значение: пространственная частотная характеристика.

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Получает или задает отклик пространственной частоты.

Значение: пространственная частотная характеристика.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Получает или задает спектральную чувствительность.

Значение: спектральная чувствительность.

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Получает или задает спектральную чувствительность.

Значение: спектральная чувствительность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Получает стандартную чувствительность вывода

Значение: Стандартная чувствительность выхода.

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Задает стандартную чувствительность вывода

Значение: Стандартная чувствительность выхода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Получает или задает область объекта.

Значение: Область объекта.

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Получает или задает область объекта.

Значение: Область объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Получает или задает расстояние до объекта.

Значение: Расстояние до объекта.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Получает или задает расстояние до объекта.

Значение: Расстояние до объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Получает или задает диапазон расстояний до объекта.

Значение: Диапазон расстояний до объекта.

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Получает или задает диапазон расстояний до объекта.

Значение: Диапазон расстояний до объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Получает или задает местоположение объекта.

Значение: Расположение объекта.

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Получает или задает местоположение объекта.

Значение: Расположение объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


Получает или задает доли секунды для тега DateTime.

Значение: Доли секунды для тега DateTime.

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


Получает или задает доли секунды для тега DateTime.

Значение: Доли секунды для тега DateTime.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


Получает или задает доли секунды для тега DateTimeDigitized.

Значение: Доли секунды для тега DateTimeDigitized.

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


Получает или задает доли секунды для тега DateTimeDigitized.

Значение: Доли секунды для тега DateTimeDigitized.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


Получает или задает доли секунды для тега DateTimeOriginal.

Значение: Доли секунды для тега DateTimeOriginal.

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


Получает или задает доли секунды для тега DateTimeOriginal.

Значение: Доли секунды для тега DateTimeOriginal.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Получает или задает пользовательский комментарий.

Значение: Комментарий пользователя.

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Получает или задает пользовательский комментарий.

Значение: Комментарий пользователя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Получает или задает баланс белого.

Значение: Баланс белого.

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Получает или задает баланс белого.

Значение: Баланс белого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Получает или задает хроматичность белой точки изображения.

Значение: Хроматичность белой точки изображения.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Получает или задает хроматичность белой точки изображения.

Значение: Хроматичность белой точки изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Получает или задает теги, которые принадлежат общей секции. Это применяется только к jpeg‑изображениям, в формате tiff вместо этого используются tiffOptions.

Значение: Теги общей секции.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Получает или задает теги, которые принадлежат общей секции. Это применяется только к jpeg‑изображениям, в формате tiff вместо этого используются tiffOptions.

Значение: Теги общей секции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Получает или задает теги, которые относятся только к разделу EXIF.

Значение: Теги секции EXIF.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Получает или задает теги, которые относятся только к разделу EXIF.

Значение: Теги секции EXIF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Получает или задает теги, которые относятся только к разделу GPS.

Значение: Теги GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Получает или задает теги, которые относятся только к разделу GPS.

Значение: Теги GPS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getThumbnail() {#getThumbnail--}
```
public final RasterImage getThumbnail()
```


Получает изображение миниатюры.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the thumbnail image.
### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.imaging.RasterImage-}
```
public final void setThumbnail(RasterImage value)
```


Задает изображение миниатюры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.imaging/rasterimage) | миниатюра изображения. |

### getXResolutionInt() {#getXResolutionInt--}
```
public final int getXResolutionInt()
```


Получает разрешение по оси X.

Значение: Разрешение по оси X.

**Returns:**
int — разрешение по оси X.
### setXResolution(int value) {#setXResolution-int-}
```
public final void setXResolution(int value)
```


Задает разрешение по оси X.

Значение: Разрешение по оси X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | разрешение по оси X. |

### getYResolutionInt() {#getYResolutionInt--}
```
public final int getYResolutionInt()
```


Получает разрешение по оси Y.

Значение: Разрешение по оси Y.

**Returns:**
int — разрешение по оси Y.
### setYResolution(int value) {#setYResolution-int-}
```
public final void setYResolution(int value)
```


Задает разрешение по оси Y.

Значение: Разрешение по оси Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | разрешение по оси Y. |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


Удалить тег из контейнера

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега для удаления. |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


Получает значение тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ тега [ExifProperties](../../com.aspose.imaging.exif/exifproperties). |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
