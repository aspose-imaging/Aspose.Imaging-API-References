---
title: "ExifProperties"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Список тегов Exif"
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Список тегов Exif
## Поля

| Поле | Описание |
| --- | --- |
| [ImageWidth](#ImageWidth) | Количество столбцов данных изображения, равное количеству пикселей в строке. |
| [ImageLength](#ImageLength) | Количество строк данных изображения. |
| [BitsPerSample](#BitsPerSample) | Количество бит на компонент изображения. |
| [Compression](#Compression) | Схема сжатия, используемая для данных изображения. |
| [PhotometricInterpretation](#PhotometricInterpretation) | Состав пикселя. |
| [ImageDescription](#ImageDescription) | Строка, содержащая название изображения. |
| [Make](#Make) | Производитель записывающего оборудования. |
| [Model](#Model) | Название модели или номер модели оборудования. |
| [Orientation](#Orientation) | Ориентация изображения, рассматриваемая в терминах строк и столбцов. |
| [SamplesPerPixel](#SamplesPerPixel) | Количество компонентов на пиксель. |
| [XResolution](#XResolution) | Количество пикселей на ResolutionUnit в направлении ImageWidth. |
| [YResolution](#YResolution) | Количество пикселей на ResolutionUnit в направлении ImageLength. |
| [PlanarConfiguration](#PlanarConfiguration) | Указывает, записываются ли компоненты пикселей в виде chunky или planar формата. |
| [ResolutionUnit](#ResolutionUnit) | Единица измерения XResolution и YResolution. |
| [TransferFunction](#TransferFunction) | Функция передачи для изображения, описанная в табличном виде. |
| [Software](#Software) | Этот тег фиксирует название и версию программного обеспечения или прошивки камеры или устройства ввода изображения, использованных для создания изображения. |
| [DateTime](#DateTime) | Дата и время создания изображения. |
| [Artist](#Artist) | Этот тег фиксирует имя владельца камеры, фотографа или создателя изображения. |
| [WhitePoint](#WhitePoint) | Хроматичность белой точки изображения. |
| [PrimaryChromaticities](#PrimaryChromaticities) | Хроматичность трех основных цветов изображения. |
| [YCbCrCoefficients](#YCbCrCoefficients) | Коэффициенты матрицы для преобразования данных изображения из RGB в YCbCr. |
| [YCbCrSubSampling](#YCbCrSubSampling) | Отношение дискретизации компонентов хроминанса к компоненту яркости. |
| [YCbCrPositioning](#YCbCrPositioning) | Позиция компонентов хроминанса относительно компонента яркости. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | Значения эталонной черной и белой точек. |
| [Copyright](#Copyright) | Информация об авторских правах. |
| [ExposureTime](#ExposureTime) | Время экспозиции, указываемое в секундах. |
| [FNumber](#FNumber) | Число F. |
| [ExposureProgram](#ExposureProgram) | Класс программы, используемой камерой для установки экспозиции при съемке. |
| [SpectralSensitivity](#SpectralSensitivity) | Указывает спектральную чувствительность каждого канала используемой камеры. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Указывает скорость ISO и диапазон ISO камеры или входного устройства, как указано в ISO 12232. |
| [OECF](#OECF) | Указывает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524. |
| [ExifVersion](#ExifVersion) | Версия Exif. |
| [DateTimeOriginal](#DateTimeOriginal) | Дата и время создания оригинальных данных изображения. |
| [DateTimeDigitized](#DateTimeDigitized) | Дата и время оцифровки. |
| [ComponentsConfiguration](#ComponentsConfiguration) | Конфигурация компонентов. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Относится к сжатым данным; указывает количество сжатых бит на пиксель. |
| [ShutterSpeedValue](#ShutterSpeedValue) | Значение скорости затвора. |
| [ApertureValue](#ApertureValue) | Значение диафрагмы объектива. |
| [BrightnessValue](#BrightnessValue) | Значение яркости. |
| [ExposureBiasValue](#ExposureBiasValue) | Значение смещения экспозиции. |
| [MaxApertureValue](#MaxApertureValue) | Максимальное значение диафрагмы. |
| [SubjectDistance](#SubjectDistance) | Расстояние до объекта, указываемое в метрах. |
| [MeteringMode](#MeteringMode) | Режим измерения экспозиции. |
| [LightSource](#LightSource) | Тип источника света. |
| [Flash](#Flash) | Указывает состояние вспышки при съёмке изображения. |
| [FocalLength](#FocalLength) | Фактическое фокусное расстояние объектива в мм. |
| [SubjectArea](#SubjectArea) | Этот тег указывает местоположение и область главного объекта в общей сцене. |
| [MakerNote](#MakerNote) | Тег для производителей Exif‑записчиков, позволяющий сохранять любую желаемую информацию. |
| [UserComment](#UserComment) | Тег для пользователей Exif, позволяющий записывать ключевые слова или комментарии к изображению помимо тех, что находятся в ImageDescription, и без ограничений кодировки символов тега ImageDescription. |
| [SubsecTime](#SubsecTime) | Тег, используемый для записи долей секунды в теге DateTime. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | Тег, используемый для записи долей секунды в теге DateTimeOriginal. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | Тег, используемый для записи долей секунды в теге DateTimeDigitized. |
| [FlashpixVersion](#FlashpixVersion) | Версия формата Flashpix, поддерживаемая файлом FPXR. |
| [ColorSpace](#ColorSpace) | Тег информации о цветовом пространстве (ColorSpace) всегда записывается как указатель цветового пространства. |
| [RelatedSoundFile](#RelatedSoundFile) | Связанный звуковой файл. |
| [FlashEnergy](#FlashEnergy) | Указывает энергию вспышки в момент захвата изображения, измеряемую в Beam Candle Power Seconds (BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Этот тег записывает таблицу пространственной частоты камеры или входного устройства и значения SFR в направлениях ширины изображения, высоты изображения и по диагонали, как указано в ISO 12233. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Указывает количество пикселей в направлении ширины изображения (X) на единицу FocalPlaneResolutionUnit на фокальной плоскости камеры. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Указывает количество пикселей в направлении высоты изображения (Y) на единицу FocalPlaneResolutionUnit на фокальной плоскости камеры. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Указывает единицу измерения FocalPlaneXResolution и FocalPlaneYResolution. |
| [SubjectLocation](#SubjectLocation) | Указывает местоположение главного объекта в сцене. |
| [ExposureIndex](#ExposureIndex) | Указывает выбранный индекс экспозиции на камере или входном устройстве в момент захвата изображения. |
| [SensingMethod](#SensingMethod) | Указывает тип сенсора изображения на камере или входном устройстве. |
| [FileSource](#FileSource) | Источник файла. |
| [SceneType](#SceneType) | Указывает тип сцены. |
| [CFAPattern](#CFAPattern) | Указывает геометрический узор цветового фильтра (CFA) сенсора изображения при использовании одночипового цветового сенсора. |
| [CustomRendered](#CustomRendered) | Этот тег указывает использование специальной обработки данных изображения, например рендеринга, ориентированного на вывод. |
| [ExposureMode](#ExposureMode) | Этот тег указывает режим экспозиции, установленный при съёмке изображения. |
| [WhiteBalance](#WhiteBalance) | Этот тег указывает режим баланса белого, установленный при съёмке изображения. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Этот тег указывает коэффициент цифрового увеличения, когда снимок был сделан. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Этот тег указывает эквивалентное фокусное расстояние, предполагая 35‑мм пленочную камеру, в мм. |
| [SceneCaptureType](#SceneCaptureType) | Этот тег указывает тип сцены, которая была снята. |
| [GainControl](#GainControl) | Этот тег указывает степень общей регулировки усиления изображения. |
| [Contrast](#Contrast) | Этот тег указывает направление обработки контраста, применяемой камерой при съемке изображения. |
| [Saturation](#Saturation) | Этот тег указывает направление обработки насыщенности, применяемой камерой при съемке изображения. |
| [Sharpness](#Sharpness) | Этот тег указывает направление обработки резкости, применяемой камерой при съемке изображения |
| [DeviceSettingDescription](#DeviceSettingDescription) | Этот тег указывает информацию об условиях съемки конкретной модели камеры. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Этот тег указывает расстояние до объекта. |
| [ImageUniqueID](#ImageUniqueID) | Уникальный идентификатор изображения. |
| [GPSVersionID](#GPSVersionID) | Указывает версию GPSInfoIFD. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Указывает, является ли широта северной или южной. |
| [GPSLatitude](#GPSLatitude) | Указывает широту. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Указывает, является ли долгота восточной или западной. |
| [GPSLongitude](#GPSLongitude) | Указывает долготу. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Указывает высоту, используемую в качестве эталонной высоты. |
| [GPSAltitude](#GPSAltitude) | Указывает высоту на основе ссылки в GPSAltitudeRef. |
| [GPSTimestamp](#GPSTimestamp) | Указывает время в формате UTC (координированное всемирное время). |
| [GPSSatellites](#GPSSatellites) | Указывает GPS‑спутники, используемые для измерений. |
| [GPSStatus](#GPSStatus) | Указывает статус GPS‑приёмника при записи изображения. |
| [GPSMeasureMode](#GPSMeasureMode) | Указывает режим измерения GPS. |
| [GPSDOP](#GPSDOP) | Указывает GPS DOP (степень точности данных). |
| [GPSSpeedRef](#GPSSpeedRef) | Указывает единицу измерения скорости движения GPS‑приёмника. |
| [GPSSpeed](#GPSSpeed) | Указывает скорость движения GPS‑приёмника. |
| [GPSTrackRef](#GPSTrackRef) | Указывает ссылку для указания направления движения GPS‑приёмника. |
| [GPSTrack](#GPSTrack) | Указывает направление движения GPS‑приёмника. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Указывает ссылку для указания направления изображения при его захвате. |
| [GPSImgDirection](#GPSImgDirection) | Указывает направление изображения при его захвате. |
| [GPSMapDatum](#GPSMapDatum) | Указывает геодезические данные, используемые GPS‑приёмником. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Указывает, является ли широта целевой точки северной или южной. |
| [GPSDestLatitude](#GPSDestLatitude) | Указывает широту целевой точки. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Указывает, является ли долгота целевой точки восточной или западной. |
| [GPSDestLongitude](#GPSDestLongitude) | Указывает долготу целевой точки. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Указывает ссылку, используемую для указания азимута к целевой точке. |
| [GPSDestBearing](#GPSDestBearing) | Указывает азимут к целевой точке. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Указывает единицу измерения расстояния до целевой точки. |
| [GPSDestDistance](#GPSDestDistance) | Указывает расстояние до целевой точки. |
| [GPSProcessingMethod](#GPSProcessingMethod) | Строка, записывающая название метода, используемого для определения местоположения. |
| [GPSAreaInformation](#GPSAreaInformation) | Строка, записывающая название GPS‑области. |
| [GPSDateStamp](#GPSDateStamp) | Строка, записывающая дату и время относительно UTC (координированного всемирного времени). |
| [GPSDifferential](#GPSDifferential) | Указывает, применяется ли дифференциальная коррекция к GPS‑приёмнику. |
| [StripOffsets](#StripOffsets) | Для каждой полосы — смещение в байтах этой полосы. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | Смещение к начальному байту (SOI) данных миниатюры, сжатой в JPEG. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | Количество байтов данных миниатюры, сжатой в JPEG. |
| [ExifIfdPointer](#ExifIfdPointer) | Указатель на Exif IFD. |
| [GPSIfdPointer](#GPSIfdPointer) | Указатель GPS IFD. |
| [RowsPerStrip](#RowsPerStrip) | Количество строк в каждой полосе. |
| [StripByteCounts](#StripByteCounts) | Общее количество байтов в каждой полосе. |
| [PixelXDimension](#PixelXDimension) | Информация, специфичная для сжатых данных. |
| [PixelYDimension](#PixelYDimension) | Информация, специфичная для сжатых данных. |
| [Gamma](#Gamma) | Значение гаммы |
| [SensitivityType](#SensitivityType) | Тип фоточувствительности |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Указывает стандартную чувствительность выхода камеры |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Указывает рекомендуемый индекс экспозиции |
| [ISOSpeed](#ISOSpeed) | Информация о значении скорости ISO, определённом в ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Этот тег указывает значение ширины скорости ISO yyy, определённое в ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Этот тег указывает значение ширины скорости ISO zzz, определённое в ISO 12232 |
| [CameraOwnerName](#CameraOwnerName) | Содержит имя владельца камеры |
| [BodySerialNumber](#BodySerialNumber) | Содержит серийный номер корпуса камеры |
| [LensMake](#LensMake) | Этот тег фиксирует производителя объектива |
| [LensModel](#LensModel) | Этот тег фиксирует название модели и номер модели объектива\`s |
| [LensSerialNumber](#LensSerialNumber) | Этот тег фиксирует серийный номер сменного объектива |
| [LensSpecification](#LensSpecification) | Этот тег отмечает минимальное фокусное расстояние, максимальное фокусное расстояние, минимальное число F при минимальном фокусном расстоянии и минимальное число F при максимальном фокусном расстоянии |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Количество столбцов данных изображения, равное количеству пикселей в строке.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Количество строк данных изображения.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Количество бит на компонент изображения. В этом стандарте каждый компонент изображения составляет 8 бит, поэтому значение этого тега равно 8.

### Compression {#Compression}
```
public static final int Compression
```


Схема сжатия, используемая для данных изображения. Когда основное изображение сжато в JPEG, это обозначение не требуется и опускается.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


Состав пикселя.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


Строка символов, задающая название изображения. Это может быть комментарий, например "1988 company picnic" или подобное.

### Make {#Make}
```
public static final int Make
```


Производитель записывающего оборудования. Это производитель DSC, сканера, видеодигитайзера или другого оборудования, создавшего изображение. Если поле оставлено пустым, считается неизвестным.

### Model {#Model}
```
public static final int Model
```


Название модели или номер модели оборудования. Это название модели или номер DSC, сканера, видеодигитайзера или другого оборудования, создавшего изображение. Если поле оставлено пустым, считается неизвестным.

### Orientation {#Orientation}
```
public static final int Orientation
```


Ориентация изображения, рассматриваемая в терминах строк и столбцов.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Количество компонентов на пиксель. Поскольку этот стандарт применяется к изображениям RGB и YCbCr, значение этого тега равно 3.

### XResolution {#XResolution}
```
public static final int XResolution
```


Количество пикселей на ResolutionUnit в направлении ImageWidth. Когда разрешение изображения неизвестно, назначается 72 [dpi].

### YResolution {#YResolution}
```
public static final int YResolution
```


Количество пикселей на ResolutionUnit в направлении ImageLength. Назначается то же значение, что и XResolution.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Указывает, записываются ли компоненты пикселей в виде chunky или planar формата. Если это поле отсутствует, предполагается значение по умолчанию TIFF: 1 (chunky).

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


Единица измерения XResolution и YResolution. Одна и та же единица используется для обоих параметров. Если разрешение изображения неизвестно, назначается 2 (дюйма).

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


Функция передачи для изображения, описанная в табличном виде. Обычно этот тег не требуется, поскольку цветовое пространство указывается в теге ColorSpace, содержащем информацию о цветовом пространстве.

### Software {#Software}
```
public static final int Software
```


Этот тег фиксирует название и версию программного обеспечения или прошивки камеры или устройства ввода изображения, использованных для создания изображения. Детальный формат не указан, но рекомендуется следовать приведённому ниже примеру. Если поле оставлено пустым, считается неизвестным.

### DateTime {#DateTime}
```
public static final int DateTime
```


Дата и время создания изображения. В стандарте Exif это дата и время изменения файла.

### Artist {#Artist}
```
public static final int Artist
```


Этот тег фиксирует имя владельца камеры, фотографа или создателя изображения. Детальный формат не указан, но рекомендуется записывать информацию, как в примере ниже, для облегчения совместимости. Если поле оставлено пустым, считается неизвестным. (Пример: "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


Хроматичность белой точки изображения. Обычно этот тег не требуется, поскольку цветовое пространство указывается в информационном теге ColorSpace.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


Хроматичность трех основных цветов изображения. Обычно этот тег не требуется, поскольку цветовое пространство указывается в информационном теге ColorSpace.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


Коэффициенты матрицы для преобразования данных изображения из RGB в YCbCr.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


Отношение дискретизации компонентов хроминанса к компоненту яркости.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


Позиция компонентов хроминанс относительно компонента яркости. Это поле предназначено только для данных, сжатых JPEG, или несжатых данных YCbCr. Значение по умолчанию TIFF равно 1 (центрировано); однако когда Y:Cb:Cr = 4:2:2, в данном стандарте рекомендуется использовать значение 2 (совместно расположено) для записи данных, чтобы улучшить качество изображения при просмотре на телевизионных системах. Если это поле отсутствует, считыватель должен предполагать значение по умолчанию TIFF. В случае Y:Cb:Cr = 4:2:0 рекомендуется значение по умолчанию TIFF (центрировано). Если у считывателя нет возможности поддерживать оба типа YCbCrPositioning, он должен следовать значению по умолчанию TIFF независимо от значения в этом поле. Желательно, чтобы считыватели " be able to support both centered and co-sited positioning.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


Значения эталонной черной и эталонной белой точек. В TIFF значения по умолчанию не заданы, но ниже приведены значения, используемые здесь в качестве по умолчанию. Цветовое пространство объявляется в информационном теге о цветовом пространстве, при этом значение по умолчанию — это значение, обеспечивающее оптимальные характеристики изображения и совместимость в этих условиях.

### Copyright {#Copyright}
```
public static final int Copyright
```


Информация об авторском праве. В данном стандарте тег используется для указания авторских прав как фотографа, так и редактора. Это уведомление об авторском праве лица или организации, претендующей на права на изображение. Заявление об авторском праве совместимости, включающее дату и права, должно быть записано в этом поле; например, "Copyright, John Smith, 19xx. All rights reserved." В данном стандарте поле фиксирует авторские права как фотографа, так и редактора, каждый из которых записывается в отдельной части заявления. Когда существует чёткое различие между правами фотографа и редактора, они записываются в порядке: сначала фотограф, затем редактор, разделённые символом NULL (в данном случае, поскольку заявление также заканчивается NULL, присутствуют два кода NULL). Если указаны только права фотографа, они завершаются одним кодом NULL. Если указаны только права редактора, часть прав фотографа состоит из одного пробела, за которым следует завершающий код NULL, после чего указываются права редактора. Если поле оставлено пустым, оно считается неизвестным.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Время экспозиции, указываемое в секундах.

### FNumber {#FNumber}
```
public static final int FNumber
```


Число F.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


Класс программы, используемой камерой для установки экспозиции при съемке.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Указывает спектральную чувствительность каждого канала используемой камеры.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Указывает скорость ISO и диапазон ISO камеры или входного устройства, как указано в ISO 12232.

### OECF {#OECF}
```
public static final int OECF
```


Указывает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


Версия Exif.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


Дата и время создания оригинальных данных изображения.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


Дата и время оцифровки.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


Конфигурация компонентов.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Относится к сжатым данным; указывает количество сжатых бит на пиксель.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


Значение скорости затвора.

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


Значение диафрагмы объектива.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


Значение яркости.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


Значение смещения экспозиции.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


Максимальное значение диафрагмы.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


Расстояние до объекта, указываемое в метрах.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


Режим измерения экспозиции.

### LightSource {#LightSource}
```
public static final int LightSource
```


Тип источника света.

### Flash {#Flash}
```
public static final int Flash
```


Указывает состояние вспышки при съёмке изображения.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


Фактическое фокусное расстояние объектива в мм.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Этот тег указывает местоположение и область главного объекта в общей сцене.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


Тег для производителей записывающих Exif программ, позволяющий сохранять любую желаемую информацию. Содержание определяется производителем, но этот тег не должен использоваться для целей, отличных от предусмотренных.

### UserComment {#UserComment}
```
public static final int UserComment
```


Тег для пользователей Exif, позволяющий записывать ключевые слова или комментарии к изображению помимо тех, что находятся в ImageDescription, и без ограничений кодировки символов тега ImageDescription.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


Тег, используемый для записи долей секунды в теге DateTime.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


Тег, используемый для записи долей секунды в теге DateTimeOriginal.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


Тег, используемый для записи долей секунды в теге DateTimeDigitized.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


Версия формата Flashpix, поддерживаемая файлом FPXR.

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


Тег информации о цветовом пространстве (ColorSpace) всегда записывается как указатель цветового пространства.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


Связанный звуковой файл.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Указывает энергию вспышки в момент захвата изображения, измеряемую в Beam Candle Power Seconds (BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Этот тег записывает таблицу пространственной частоты камеры или входного устройства и значения SFR в направлениях ширины изображения, высоты изображения и по диагонали, как указано в ISO 12233.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Указывает количество пикселей в направлении ширины изображения (X) на единицу FocalPlaneResolutionUnit на фокальной плоскости камеры.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Указывает количество пикселей в направлении высоты изображения (Y) на единицу FocalPlaneResolutionUnit на фокальной плоскости камеры.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Указывает единицу измерения FocalPlaneXResolution и FocalPlaneYResolution. Это значение совпадает со значением ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Указывает расположение главного объекта сцены. Значение этого тега представляет пиксель в центре главного объекта относительно левого края, до обработки вращения согласно тегу Rotation.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Указывает выбранный индекс экспозиции на камере или входном устройстве в момент захвата изображения.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Указывает тип сенсора изображения на камере или входном устройстве.

### FileSource {#FileSource}
```
public static final int FileSource
```


Источник файла.

### SceneType {#SceneType}
```
public static final int SceneType
```


Указывает тип сцены. Если изображение было записано DSC, значение этого тега всегда должно быть 1, что указывает на прямую фотографию.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Указывает геометрический шаблон цветового фильтра массива (CFA) сенсора изображения при использовании одночипового цветового сенсора. Не применяется ко всем методам сенсинга.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


Этот тег указывает на использование специальной обработки данных изображения, например рендеринга, ориентированного на вывод. Когда выполняется специальная обработка, от считывателя ожидается отключить или минимизировать дальнейшую обработку.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


Этот тег указывает режим экспозиции, установленный при съёмке изображения. В режиме авто-бракеттинга камера делает серию кадров одной и той же сцены с разными настройками экспозиции.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Этот тег указывает режим баланса белого, установленный при съёмке изображения.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


Этот тег указывает коэффициент цифрового зума при съёмке изображения. Если числитель записанного значения равен 0, это означает, что цифровой зум не использовался.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


Этот тег указывает эквивалентное фокусное расстояние, предполагая 35‑мм пленочную камеру, в мм. Значение 0 означает, что фокусное расстояние неизвестно. Обратите внимание, что этот тег отличается от тега FocalLength.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


Этот тег указывает тип снятой сцены. Его также можно использовать для записи режима, в котором было сделано изображение.

### GainControl {#GainControl}
```
public static final int GainControl
```


Этот тег указывает степень общей регулировки усиления изображения.

### Contrast {#Contrast}
```
public static final int Contrast
```


Этот тег указывает направление обработки контраста, применяемой камерой при съемке изображения.

### Saturation {#Saturation}
```
public static final int Saturation
```


Этот тег указывает направление обработки насыщенности, применяемой камерой при съемке изображения.

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Этот тег указывает направление обработки резкости, применяемой камерой при съемке изображения

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


Этот тег указывает информацию об условиях съёмки конкретной модели камеры. Тег используется только для указания условий съёмки в считывателе.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Этот тег указывает расстояние до объекта.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


Уникальный идентификатор изображения.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Указывает версию GPSInfoIFD.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Указывает, является ли широта северной или южной.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Указывает широту. Широта выражается тремя значениями RATIONAL, представляющими соответственно градусы, минуты и секунды. Если широта задаётся в градусах, минутах и секундах, типичный формат выглядит как dd/1,mm/1,ss/1. Когда используются градусы и минуты, и, например, дробные части минут задаются с точностью до двух знаков после запятой, формат будет dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Указывает, является ли долгота восточной или западной.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Указывает долготу. Долгота выражается тремя значениями RATIONAL, представляющими соответственно градусы, минуты и секунды. Если долгота задаётся в градусах, минутах и секундах, типичный формат выглядит как ddd/1,mm/1,ss/1. Когда используются градусы и минуты, и, например, дробные части минут задаются с точностью до двух знаков после запятой, формат будет ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Указывает высоту, используемую в качестве эталонной. Если эталоном является уровень моря и высота выше уровня моря, задаётся 0. Если высота ниже уровня моря, задаётся значение 1, а высота указывается как абсолютное значение в теге GPSAltitude.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Указывает высоту в соответствии с эталоном в GPSAltitudeRef. Высота выражается одним значением RATIONAL. Единица измерения — метры.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Указывает время в формате UTC (Coordinated Universal Time). TimeStamp выражается тремя значениями RATIONAL, представляющими часы, минуты и секунды.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Указывает спутники GPS, используемые для измерений. Этот тег может использоваться для описания количества спутников, их идентификационных номеров, угла возвышения, азимута, SNR и другой информации в ASCII‑нотации. Формат не определён. Если GPS‑приёмник не способен выполнять измерения, значение тега должно быть установлено в NULL.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Указывает статус GPS‑приёмника при записи изображения.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Указывает режим измерения GPS. - 2‑ или 3‑мерный.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Указывает GPS DOP (degree of precision данных). Значение HDOP записывается при двухмерных измерениях, а PDOP — при трехмерных измерениях.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Указывает единицу измерения скорости движения GPS‑приёмника. 'K', 'M' и 'N' обозначают километры в час, мили в час и узлы.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Указывает скорость движения GPS‑приёмника.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Указывает ссылку для задания направления движения GPS‑приёмника. 'T' обозначает истинное направление, а 'M' — магнитное направление.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Указывает направление движения GPS‑приёмника. Диапазон значений от 0.00 до 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Указывает ссылку для задания направления изображения при его захвате. 'T' обозначает истинное направление, а 'M' — магнитное направление.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Указывает направление изображения при его захвате. Диапазон значений от 0.00 до 359.99.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Указывает геодезические данные, используемые GPS‑приёмником.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Указывает, находится ли широта целевой точки в северном или южном полушарии. Символ ASCII 'N' обозначает северную широту, а 'S' — южную широту.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Указывает широту целевой точки. Широта выражается тремя значениями RATIONAL, задающими градусы, минуты и секунды соответственно. Если широта задаётся в градусах, минутах и секундах, типичный формат выглядит как dd/1,mm/1,ss/1. Когда используются градусы и минуты, и, например, доли минут задаются с точностью до двух десятичных знаков, формат будет dd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Указывает, находится ли долгота целевой точки в восточном или западном полушарии. Символ ASCII 'E' обозначает восточную долготу, а 'W' — западную долготу.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Указывает долготу целевой точки. Долгота выражается тремя значениями RATIONAL, задающими градусы, минуты и секунды соответственно. Если долгота задаётся в градусах, минутах и секундах, типичный формат выглядит как ddd/1,mm/1,ss/1. Когда используются градусы и минуты, и, например, доли минут задаются с точностью до двух десятичных знаков, формат будет ddd/1,mmmm/100,0/1.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Указывает ссылку, используемую для задания азимута к целевой точке. 'T' обозначает истинное направление, а 'M' — магнитное направление.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Указывает азимут к целевой точке. Диапазон значений от 0.00 до 359.99.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Указывает единицу измерения расстояния до целевой точки. 'K', 'M' и 'N' обозначают километры, мили и узлы.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Указывает расстояние до целевой точки.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


Строка символов, фиксирующая название метода, используемого для определения местоположения. Первый байт указывает используемый код символов, после чего следует название метода.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


Строка символов, фиксирующая название GPS‑области. Первый байт указывает используемый код символов, после чего следует название GPS‑области.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


Строка символов, фиксирующая информацию о дате и времени относительно UTC (Coordinated Universal Time). Формат: YYYY:MM:DD.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Указывает, применяется ли дифференциальная коррекция к GPS‑приёмнику.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


Для каждой полосы — смещение в байтах этой полосы. Рекомендуется выбирать значение так, чтобы количество байтов полосы не превышало 64 КБ. Вспомогательный тег.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


Смещение до стартового байта (SOI) JPEG‑сжатых данных миниатюры. Не используется для основных JPEG‑данных изображения.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


Количество байтов JPEG‑сжатых данных миниатюры. Не используется для основных JPEG‑данных изображения. Миниатюры JPEG не делятся, а записываются как непрерывный JPEG‑битовый поток от SOI до EOI. Маркеры Appn и COM не должны записываться. Сжатые миниатюры должны быть записаны не более чем в 64 КБ, включая все остальные данные, которые должны быть записаны в APP1.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Указатель на Exif IFD. В разделе Interoperability Exif IFD имеет ту же структуру, что и IFD, указанный в TIFF. Однако обычно он не содержит данные изображения, как в случае с TIFF.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


Указатель GPS IFD.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Количество строк в полосе. Это число строк изображения в одной полосе, когда изображение разделено на полосы.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Общее количество байтов в каждой полосе.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Информация, специфичная для сжатых данных. При записи сжатого файла в этом теге должна фиксироваться действительная ширина значимого изображения, независимо от наличия данных заполнения или маркера перезапуска.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Информация, специфичная для сжатых данных. При записи сжатого файла в этом теге должна фиксироваться действительная высота значимого изображения.

### Gamma {#Gamma}
```
public static final int Gamma
```


Значение гаммы

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Тип фоточувствительности

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Указывает стандартную чувствительность выхода камеры

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Указывает рекомендуемый индекс экспозиции

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Информация о значении скорости ISO, определённом в ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Этот тег указывает значение ширины скорости ISO yyy, определённое в ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Этот тег указывает значение ширины скорости ISO zzz, определённое в ISO 12232

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Содержит имя владельца камеры

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Содержит серийный номер корпуса камеры

### LensMake {#LensMake}
```
public static final int LensMake
```


Этот тег фиксирует производителя объектива

### LensModel {#LensModel}
```
public static final int LensModel
```


Этот тег фиксирует название модели и номер модели объектива\`s

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Этот тег фиксирует серийный номер сменного объектива

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Этот тег отмечает минимальное фокусное расстояние, максимальное фокусное расстояние, минимальное число F при минимальном фокусном расстоянии и минимальное число F при максимальном фокусном расстоянии

