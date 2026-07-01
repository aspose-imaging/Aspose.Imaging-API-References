---
title: "ExifProperties"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "قائمة وسوم Exif"
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

قائمة وسوم Exif
## الحقول

| حقل | الوصف |
| --- | --- |
| [ImageWidth](#ImageWidth) | عدد أعمدة بيانات الصورة، يساوي عدد البكسلات في كل صف. |
| [ImageLength](#ImageLength) | عدد صفوف بيانات الصورة. |
| [BitsPerSample](#BitsPerSample) | عدد البتات لكل مكوّن من مكوّنات الصورة. |
| [Compression](#Compression) | نظام الضغط المستخدم لبيانات الصورة. |
| [PhotometricInterpretation](#PhotometricInterpretation) | تكوين البكسل. |
| [ImageDescription](#ImageDescription) | سلسلة أحرف تعطي عنوان الصورة. |
| [Make](#Make) | مصنّع معدات التسجيل. |
| [Model](#Model) | اسم الطراز أو رقم طراز المعدات. |
| [Orientation](#Orientation) | اتجاه الصورة كما يُعرض من حيث الصفوف والأعمدة. |
| [SamplesPerPixel](#SamplesPerPixel) | عدد المكوّنات لكل بكسل. |
| [XResolution](#XResolution) | عدد البكسلات لكل وحدة دقة في اتجاه عرض الصورة. |
| [YResolution](#YResolution) | عدد البكسلات لكل ResolutionUnit في اتجاه ImageLength. |
| [PlanarConfiguration](#PlanarConfiguration) | يشير إلى ما إذا كانت مكونات البكسل مسجلة بتنسيق مجمع أو مسطح. |
| [ResolutionUnit](#ResolutionUnit) | الوحدة لقياس XResolution و YResolution. |
| [TransferFunction](#TransferFunction) | دالة تحويل للصورة، موصوفة بأسلوب جدولي. |
| [Software](#Software) | هذه العلامة تسجل اسم وإصدار البرنامج أو البرنامج الثابت للكاميرا أو جهاز إدخال الصورة المستخدم لإنشاء الصورة. |
| [DateTime](#DateTime) | تاريخ ووقت إنشاء الصورة. |
| [Artist](#Artist) | هذه العلامة تسجل اسم مالك الكاميرا أو المصور أو منشئ الصورة. |
| [WhitePoint](#WhitePoint) | اللونية لنقطة الأبيض في الصورة. |
| [PrimaryChromaticities](#PrimaryChromaticities) | اللونية للألوان الأساسية الثلاثة في الصورة. |
| [YCbCrCoefficients](#YCbCrCoefficients) | معاملات المصفوفة للتحويل من بيانات الصورة RGB إلى YCbCr. |
| [YCbCrSubSampling](#YCbCrSubSampling) | نسبة أخذ العينات لمكونات التشبع بالنسبة لمكون الإضاءة. |
| [YCbCrPositioning](#YCbCrPositioning) | موضع مكونات التشبع بالنسبة لمكون الإضاءة. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | قيمة نقطة الأسود المرجعية وقيمة نقطة الأبيض المرجعية. |
| [Copyright](#Copyright) | معلومات حقوق النشر. |
| [ExposureTime](#ExposureTime) | وقت التعرض، بالثواني. |
| [FNumber](#FNumber) | رقم F. |
| [ExposureProgram](#ExposureProgram) | فئة البرنامج الذي تستخدمه الكاميرا لضبط التعرض عند التقاط الصورة. |
| [SpectralSensitivity](#SpectralSensitivity) | يشير إلى الحساسية الطيفية لكل قناة من الكاميرا المستخدمة. |
| [PhotographicSensitivity](#PhotographicSensitivity) | يشير إلى سرعة ISO وعرض ISO للكاميرا أو جهاز الإدخال كما هو محدد في ISO 12232. |
| [OECF](#OECF) | يشير إلى دالة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524. |
| [ExifVersion](#ExifVersion) | إصدار Exif. |
| [DateTimeOriginal](#DateTimeOriginal) | التاريخ والوقت عندما تم إنشاء بيانات الصورة الأصلية. |
| [DateTimeDigitized](#DateTimeDigitized) | تاريخ ووقت الرقمنة. |
| [ComponentsConfiguration](#ComponentsConfiguration) | تكوين المكونات. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | خاص بالبيانات المضغوطة؛ يحدد عدد البتات المضغوطة لكل بكسل. |
| [ShutterSpeedValue](#ShutterSpeedValue) | قيمة سرعة الغالق. |
| [ApertureValue](#ApertureValue) | قيمة فتحة العدسة. |
| [BrightnessValue](#BrightnessValue) | قيمة السطوع. |
| [ExposureBiasValue](#ExposureBiasValue) | قيمة إزاحة التعرض. |
| [MaxApertureValue](#MaxApertureValue) | قيمة أقصى فتحة. |
| [SubjectDistance](#SubjectDistance) | المسافة إلى الهدف، معطاة بالأمتار. |
| [MeteringMode](#MeteringMode) | وضع القياس. |
| [LightSource](#LightSource) | نوع مصدر الضوء. |
| [Flash](#Flash) | يشير إلى حالة الفلاش عندما تم التقاط الصورة. |
| [FocalLength](#FocalLength) | البعد البؤري الفعلي للعدسة، بالمليمتر. |
| [SubjectArea](#SubjectArea) | تشير هذه العلامة إلى موقع ومساحة الهدف الرئيسي في المشهد العام. |
| [MakerNote](#MakerNote) | علامة للمصنعين لكتاب Exif لتسجيل أي معلومات مرغوبة. |
| [UserComment](#UserComment) | علامة لمستخدمي Exif لكتابة كلمات مفتاحية أو تعليقات على الصورة بجانب تلك الموجودة في ImageDescription، ودون قيود ترميز الأحرف لعلامة ImageDescription. |
| [SubsecTime](#SubsecTime) | علامة تُستخدم لتسجيل أجزاء من الثواني لعلامة DateTime. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | علامة تُستخدم لتسجيل أجزاء من الثواني لعلامة DateTimeOriginal. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | علامة تُستخدم لتسجيل أجزاء من الثواني لعلامة DateTimeDigitized. |
| [FlashpixVersion](#FlashpixVersion) | إصدار تنسيق Flashpix المدعوم من ملف FPXR. |
| [ColorSpace](#ColorSpace) | علامة معلومات مساحة اللون (ColorSpace) تُسجل دائمًا كمحدد مساحة اللون. |
| [RelatedSoundFile](#RelatedSoundFile) | ملف الصوت المرتبط. |
| [FlashEnergy](#FlashEnergy) | يشير إلى طاقة الفلاش في وقت التقاط الصورة، كما تُقاس بوحدات Beam Candle Power Seconds (BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | تسجل هذه العلامة جدول التردد المكاني للكاميرا أو جهاز الإدخال وقيم SFR في اتجاه عرض الصورة، ارتفاعها، والاتجاه القطري، كما هو محدد في ISO 12233. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | يشير إلى عدد البكسلات في اتجاه عرض الصورة (X) لكل وحدة FocalPlaneResolutionUnit على مستوى الطائرة البؤرية للكاميرا. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | يشير إلى عدد البكسلات في اتجاه ارتفاع الصورة (Y) لكل وحدة FocalPlaneResolutionUnit على مستوى الطائرة البؤرية للكاميرا. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | يشير إلى الوحدة المستخدمة لقياس FocalPlaneXResolution وFocalPlaneYResolution. |
| [SubjectLocation](#SubjectLocation) | يشير إلى موقع الهدف الرئيسي في المشهد. |
| [ExposureIndex](#ExposureIndex) | يشير إلى مؤشر التعرض المختار على الكاميرا أو جهاز الإدخال في وقت التقاط الصورة. |
| [SensingMethod](#SensingMethod) | يشير إلى نوع حساس الصورة على الكاميرا أو جهاز الإدخال. |
| [FileSource](#FileSource) | مصدر الملف. |
| [SceneType](#SceneType) | يشير إلى نوع المشهد. |
| [CFAPattern](#CFAPattern) | يشير إلى نمط التصفية اللونية (CFA) الهندسي لحساس الصورة عندما يُستخدم حساس لون أحادي الشريحة. |
| [CustomRendered](#CustomRendered) | تشير هذه العلامة إلى استخدام معالجة خاصة على بيانات الصورة، مثل العرض الموجه للإخراج. |
| [ExposureMode](#ExposureMode) | تشير هذه العلامة إلى وضع التعرض المحدد عند التقاط الصورة. |
| [WhiteBalance](#WhiteBalance) | تشير هذه العلامة إلى وضع توازن اللون الأبيض المحدد عند التقاط الصورة. |
| [DigitalZoomRatio](#DigitalZoomRatio) | تشير هذه العلامة إلى نسبة التكبير الرقمي عند التقاط الصورة. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | تشير هذه العلامة إلى البعد البؤري المكافئ بافتراض كاميرا فيلم 35 مم، بالمليمتر. |
| [SceneCaptureType](#SceneCaptureType) | تشير هذه العلامة إلى نوع المشهد الذي تم تصويره. |
| [GainControl](#GainControl) | تشير هذه العلامة إلى درجة تعديل الكسب الكلي للصورة. |
| [Contrast](#Contrast) | تشير هذه العلامة إلى اتجاه معالجة التباين التي طبقتها الكاميرا عند التقاط الصورة. |
| [Saturation](#Saturation) | تشير هذه العلامة إلى اتجاه معالجة التشبع التي طبقتها الكاميرا عند التقاط الصورة. |
| [Sharpness](#Sharpness) | تشير هذه العلامة إلى اتجاه معالجة الحدة التي طبقتها الكاميرا عند التقاط الصورة |
| [DeviceSettingDescription](#DeviceSettingDescription) | تشير هذه العلامة إلى معلومات حول ظروف التقاط الصورة لنموذج كاميرا معين. |
| [SubjectDistanceRange](#SubjectDistanceRange) | تشير هذه العلامة إلى المسافة إلى الهدف. |
| [ImageUniqueID](#ImageUniqueID) | معرّف الصورة الفريد. |
| [GPSVersionID](#GPSVersionID) | يشير إلى إصدار GPSInfoIFD. |
| [GPSLatitudeRef](#GPSLatitudeRef) | يشير إلى ما إذا كانت دائرة العرض شمالية أم جنوبية. |
| [GPSLatitude](#GPSLatitude) | يشير إلى دائرة العرض. |
| [GPSLongitudeRef](#GPSLongitudeRef) | يشير إلى ما إذا كانت دائرة الطول شرقية أم غربية. |
| [GPSLongitude](#GPSLongitude) | يشير إلى دائرة الطول. |
| [GPSAltitudeRef](#GPSAltitudeRef) | يشير إلى الارتفاع المستخدم كارتفاع مرجعي. |
| [GPSAltitude](#GPSAltitude) | يشير إلى الارتفاع بناءً على المرجع في GPSAltitudeRef. |
| [GPSTimestamp](#GPSTimestamp) | يشير إلى الوقت بتوقيت UTC (التوقيت العالمي المنسق). |
| [GPSSatellites](#GPSSatellites) | يشير إلى أقمار GPS المستخدمة للقياسات. |
| [GPSStatus](#GPSStatus) | يشير إلى حالة مستقبل GPS عندما يتم تسجيل الصورة. |
| [GPSMeasureMode](#GPSMeasureMode) | يشير إلى وضع قياس GPS. |
| [GPSDOP](#GPSDOP) | يشير إلى DOP GPS (درجة دقة البيانات). |
| [GPSSpeedRef](#GPSSpeedRef) | يشير إلى الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS. |
| [GPSSpeed](#GPSSpeed) | يشير إلى سرعة حركة مستقبل GPS. |
| [GPSTrackRef](#GPSTrackRef) | يشير إلى المرجع لتحديد اتجاه حركة مستقبل GPS. |
| [GPSTrack](#GPSTrack) | يشير إلى اتجاه حركة مستقبل GPS. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | يشير إلى المرجع لتحديد اتجاه الصورة عند التقاطها. |
| [GPSImgDirection](#GPSImgDirection) | يشير إلى اتجاه الصورة عند التقاطها. |
| [GPSMapDatum](#GPSMapDatum) | يشير إلى بيانات المسح الجيوديسي المستخدمة من قبل مستقبل GPS. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | يشير إلى ما إذا كانت خط عرض نقطة الوجهة شمالية أم جنوبية. |
| [GPSDestLatitude](#GPSDestLatitude) | يشير إلى خط عرض نقطة الوجهة. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | يشير إلى ما إذا كانت خط طول نقطة الوجهة شرقية أم غربية. |
| [GPSDestLongitude](#GPSDestLongitude) | يشير إلى خط طول نقطة الوجهة. |
| [GPSDestBearingRef](#GPSDestBearingRef) | يشير إلى المرجع المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| [GPSDestBearing](#GPSDestBearing) | يشير إلى الاتجاه إلى نقطة الوجهة. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | يشير إلى الوحدة المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| [GPSDestDistance](#GPSDestDistance) | يشير إلى المسافة إلى نقطة الوجهة. |
| [GPSProcessingMethod](#GPSProcessingMethod) | سلسلة أحرف تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| [GPSAreaInformation](#GPSAreaInformation) | سلسلة أحرف تسجل اسم منطقة GPS. |
| [GPSDateStamp](#GPSDateStamp) | سلسلة أحرف تسجل معلومات التاريخ والوقت بالنسبة إلى UTC (التوقيت العالمي المنسق). |
| [GPSDifferential](#GPSDifferential) | يشير إلى ما إذا كان يتم تطبيق التصحيح التفاضلي على مستقبل GPS. |
| [StripOffsets](#StripOffsets) | لكل شريط، إزاحة البايت لذلك الشريط. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | الإزاحة إلى بايت البداية (SOI) لبيانات الصورة المصغرة المضغوطة بصيغة JPEG. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | عدد البايتات لبيانات الصورة المصغرة المضغوطة بصيغة JPEG. |
| [ExifIfdPointer](#ExifIfdPointer) | مؤشر إلى Exif IFD. |
| [GPSIfdPointer](#GPSIfdPointer) | مؤشر gps ifd. |
| [RowsPerStrip](#RowsPerStrip) | عدد الصفوف لكل شريط. |
| [StripByteCounts](#StripByteCounts) | إجمالي عدد البايتات في كل شريط. |
| [PixelXDimension](#PixelXDimension) | معلومات خاصة بالبيانات المضغوطة. |
| [PixelYDimension](#PixelYDimension) | معلومات خاصة بالبيانات المضغوطة. |
| [Gamma](#Gamma) | قيمة غاما |
| [SensitivityType](#SensitivityType) | نوع الحساسية الفوتوغرافية |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | يشير إلى حساسية الإخراج القياسية للكاميرا |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | يشير إلى مؤشر التعرض الموصى به |
| [ISOSpeed](#ISOSpeed) | معلومات حول قيمة سرعة ISO كما هو معرف في ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | تشير هذه العلامة إلى قيمة خط عرض سرعة ISO yyy كما هو معرف في ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | تشير هذه العلامة إلى قيمة خط عرض سرعة ISO zzz كما هو معرف في ISO 12232 |
| [CameraOwnerName](#CameraOwnerName) | يحتوي على اسم مالك الكاميرا |
| [BodySerialNumber](#BodySerialNumber) | يحتوي على الرقم التسلسلي لجسم الكاميرا |
| [LensMake](#LensMake) | تسجل هذه العلامة مصنع العدسة |
| [LensModel](#LensModel) | تسجل هذه العلامة اسم نموذج العدسة ورقم النموذج |
| [LensSerialNumber](#LensSerialNumber) | تسجل هذه العلامة الرقم التسلسلي للعدسة القابلة للتبديل |
| [LensSpecification](#LensSpecification) | تلاحظ هذه العلامة الحد الأدنى للطول البؤري، الحد الأقصى للطول البؤري، رقم F الأدنى في الحد الأدنى للطول البؤري ورقم F الأدنى في الحد الأقصى للطول البؤري |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


عدد أعمدة بيانات الصورة، يساوي عدد البكسلات في كل صف.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


عدد صفوف بيانات الصورة.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


عدد البتات لكل مكوّن من مكوّنات الصورة. في هذا المعيار كل مكوّن من الصورة هو 8 بت، لذا فإن القيمة لهذه العلامة هي 8.

### Compression {#Compression}
```
public static final int Compression
```


نظام الضغط المستخدم لبيانات الصورة. عندما تكون الصورة الأساسية مضغوطة بصيغة JPEG، لا تكون هذه التسمية ضرورية وتُحذف.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


تكوين البكسل.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


سلسلة أحرف تعطي عنوان الصورة. قد تكون تعليقًا مثل \"1988 company picnic\" أو ما شابه.

### Make {#Make}
```
public static final int Make
```


مصنّع معدات التسجيل. هذا هو مصنّع الـ DSC أو الماسح الضوئي أو محول الفيديو أو أي معدات أخرى التي أنشأت الصورة. عندما يُترك الحقل فارغًا، يُعامل كغير معروف.

### Model {#Model}
```
public static final int Model
```


اسم النموذج أو رقم نموذج المعدات. هذا هو اسم النموذج أو رقم الـ DSC أو الماسح الضوئي أو محول الفيديو أو أي معدات أخرى التي أنشأت الصورة. عندما يُترك الحقل فارغًا، يُعامل كغير معروف.

### Orientation {#Orientation}
```
public static final int Orientation
```


اتجاه الصورة كما يُعرض من حيث الصفوف والأعمدة.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


عدد المكوّنات لكل بكسل. بما أن هذا المعيار ينطبق على صور RGB و YCbCr، فإن القيمة المحددة لهذه العلامة هي 3.

### XResolution {#XResolution}
```
public static final int XResolution
```


The number of pixels per ResolutionUnit in the ImageWidth direction. When the image resolution is unknown, 72 [dpi] is designated.

### YResolution {#YResolution}
```
public static final int YResolution
```


The number of pixels per ResolutionUnit in the ImageLength direction. The same value as XResolution is designated.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Indicates whether pixel components are recorded in a chunky or planar format. If this field does not exist, the TIFF default of 1 (chunky) is assumed.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


The unit for measuring XResolution and YResolution. The same unit is used for both XResolution and YResolution. If the image resolution is unknown, 2 (inches) is designated.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


A transfer function for the image, described in tabular style. Normally this tag is not necessary, since color space is specified in the color space information ColorSpace tag.

### Software {#Software}
```
public static final int Software
```


This tag records the name and version of the software or firmware of the camera or image input device used to generate the image. The detailed format is not specified, but it is recommended that the example shown below be followed. When the field is left blank, it is treated as unknown.

### DateTime {#DateTime}
```
public static final int DateTime
```


The date and time of image creation. In Exif standard, it is the date and time the file was changed.

### Artist {#Artist}
```
public static final int Artist
```


This tag records the name of the camera owner, photographer or image creator. The detailed format is not specified, but it is recommended that the information be written as in the example below for ease of Interoperability. When the field is left blank, it is treated as unknown. (Ex. "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


The chromaticity of the white point of the image. Normally this tag is not necessary, since color space is specified in the colorspace information ColorSpace tag.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


The chromaticity of the three primary colors of the image. Normally this tag is not necessary, since colorspace is specified in the colorspace information ColorSpace tag.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


معاملات المصفوفة للتحويل من بيانات الصورة RGB إلى YCbCr.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


نسبة أخذ العينات لمكونات التشبع بالنسبة لمكون الإضاءة.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


The position of chrominance components in relation to the luminance component. This field is designated only for JPEG compressed data or uncompressed YCbCr data. The TIFF default is 1 (centered); but when Y:Cb:Cr = 4:2:2 it is recommended in this standard that 2 (co-sited) be used to record data, in order to improve the image quality when viewed on TV systems. When this field does not exist, the reader shall assume the TIFF default. In the case of Y:Cb:Cr = 4:2:0, the TIFF default (centered) is recommended. If the reader does not have the capability of supporting both kinds of YCbCrPositioning, it shall follow the TIFF default regardless of the value in this field. It is preferable that readers " be able to support both centered and co-sited positioning.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


The reference black point value and reference white point value. No defaults are given in TIFF, but the values below are given as defaults here. The color space is declared in a color space information tag, with the default being the value that gives the optimal image characteristics Interoperability these conditions

### Copyright {#Copyright}
```
public static final int Copyright
```


Copyright information. In this standard the tag is used to indicate both the photographer and editor copyrights. It is the copyright notice of the person or organization claiming rights to the image. The Interoperability copyright statement including date and rights should be written in this field; e.g., "Copyright, John Smith, 19xx. All rights reserved." In this standard the field records both the photographer and editor copyrights, with each recorded in a separate part of the statement. When there is a clear distinction between the photographer and editor copyrights, these are to be written in the order of photographer followed by editor copyright, separated by NULL (in this case since the statement also ends with a NULL, there are two NULL codes). When only the photographer copyright is given, it is terminated by one NULL code . When only the editor copyright is given, the photographer copyright part consists of one space followed by a terminating NULL code, then the editor copyright is given. When the field is left blank, it is treated as unknown.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


وقت التعرض، بالثواني.

### FNumber {#FNumber}
```
public static final int FNumber
```


رقم F.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


فئة البرنامج الذي تستخدمه الكاميرا لضبط التعرض عند التقاط الصورة.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


يشير إلى الحساسية الطيفية لكل قناة من الكاميرا المستخدمة.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


يشير إلى سرعة ISO وعرض ISO للكاميرا أو جهاز الإدخال كما هو محدد في ISO 12232.

### OECF {#OECF}
```
public static final int OECF
```


يشير إلى دالة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


إصدار Exif.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


التاريخ والوقت عندما تم إنشاء بيانات الصورة الأصلية.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


تاريخ ووقت الرقمنة.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


تكوين المكونات.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


خاص بالبيانات المضغوطة؛ يحدد عدد البتات المضغوطة لكل بكسل.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


قيمة سرعة الغالق.

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


قيمة فتحة العدسة.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


قيمة السطوع.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


قيمة إزاحة التعرض.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


قيمة أقصى فتحة.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


المسافة إلى الهدف، معطاة بالأمتار.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


وضع القياس.

### LightSource {#LightSource}
```
public static final int LightSource
```


نوع مصدر الضوء.

### Flash {#Flash}
```
public static final int Flash
```


يشير إلى حالة الفلاش عندما تم التقاط الصورة.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


البعد البؤري الفعلي للعدسة، بالمليمتر.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


تشير هذه العلامة إلى موقع ومساحة الهدف الرئيسي في المشهد العام.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


A tag for manufacturers of Exif writers to record any desired information. The contents are up to the manufacturer, but this tag should not be used for any other than its intended purpose.

### UserComment {#UserComment}
```
public static final int UserComment
```


علامة لمستخدمي Exif لكتابة كلمات مفتاحية أو تعليقات على الصورة بجانب تلك الموجودة في ImageDescription، ودون قيود ترميز الأحرف لعلامة ImageDescription.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


علامة تُستخدم لتسجيل أجزاء من الثواني لعلامة DateTime.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


علامة تُستخدم لتسجيل أجزاء من الثواني لعلامة DateTimeOriginal.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


علامة تُستخدم لتسجيل أجزاء من الثواني لعلامة DateTimeDigitized.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


إصدار تنسيق Flashpix المدعوم من ملف FPXR.

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


علامة معلومات مساحة اللون (ColorSpace) تُسجل دائمًا كمحدد مساحة اللون.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


ملف الصوت المرتبط.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


يشير إلى طاقة الفلاش في وقت التقاط الصورة، كما تُقاس بوحدات Beam Candle Power Seconds (BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


تسجل هذه العلامة جدول التردد المكاني للكاميرا أو جهاز الإدخال وقيم SFR في اتجاه عرض الصورة، ارتفاعها، والاتجاه القطري، كما هو محدد في ISO 12233.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


يشير إلى عدد البكسلات في اتجاه عرض الصورة (X) لكل وحدة FocalPlaneResolutionUnit على مستوى الطائرة البؤرية للكاميرا.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


يشير إلى عدد البكسلات في اتجاه ارتفاع الصورة (Y) لكل وحدة FocalPlaneResolutionUnit على مستوى الطائرة البؤرية للكاميرا.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. This value is the same as the ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Indicates the location of the main subject in the scene. The value of this tag represents the pixel at the center of the main subject relative to the left edge, prior to rotation processing as per the Rotation tag.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


يشير إلى مؤشر التعرض المختار على الكاميرا أو جهاز الإدخال في وقت التقاط الصورة.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


يشير إلى نوع حساس الصورة على الكاميرا أو جهاز الإدخال.

### FileSource {#FileSource}
```
public static final int FileSource
```


مصدر الملف.

### SceneType {#SceneType}
```
public static final int SceneType
```


Indicates the type of scene. If a DSC recorded the image, this tag value shall always be set to 1, indicating that the image was directly photographed.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Indicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. It does not apply to all sensing methods.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


This tag indicates the use of special processing on image data, such as rendering geared to output. When special processing is performed, the reader is expected to disable or minimize any further processing.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


This tag indicates the exposure mode set when the image was shot. In auto‑bracketing mode, the camera shoots a series of frames of the same scene at different exposure settings.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


تشير هذه العلامة إلى وضع توازن اللون الأبيض المحدد عند التقاط الصورة.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


This tag indicates the digital zoom ratio when the image was shot. If the numerator of the recorded value is 0, this indicates that digital zoom was not used.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. A value of 0 means the focal length is unknown. Note that this tag differs from the FocalLength tag.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


This tag indicates the type of scene that was shot. It can also be used to record the mode in which the image was shot.

### GainControl {#GainControl}
```
public static final int GainControl
```


تشير هذه العلامة إلى درجة تعديل الكسب الكلي للصورة.

### Contrast {#Contrast}
```
public static final int Contrast
```


تشير هذه العلامة إلى اتجاه معالجة التباين التي طبقتها الكاميرا عند التقاط الصورة.

### Saturation {#Saturation}
```
public static final int Saturation
```


تشير هذه العلامة إلى اتجاه معالجة التشبع التي طبقتها الكاميرا عند التقاط الصورة.

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


تشير هذه العلامة إلى اتجاه معالجة الحدة التي طبقتها الكاميرا عند التقاط الصورة

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


This tag indicates information on the picture‑taking conditions of a particular camera model. The tag is used only to indicate the picture‑taking conditions in the reader.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


تشير هذه العلامة إلى المسافة إلى الهدف.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


معرّف الصورة الفريد.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


يشير إلى إصدار GPSInfoIFD.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


يشير إلى ما إذا كانت دائرة العرض شمالية أم جنوبية.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Indicates the latitude. The latitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical format would be dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


يشير إلى ما إذا كانت دائرة الطول شرقية أم غربية.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


يشير إلى خط الطول. يُعبّر عن خط الطول كثلاث قيم RATIONAL تُعطي الدرجات والدقائق والثواني على التوالي. إذا تم التعبير عن خط الطول بالدرجات والدقائق والثواني، فإن الصيغة النموذجية تكون ddd/1,mm/1,ss/1. عندما تُستخدم الدرجات والدقائق وعلى سبيل المثال تُعطى كسور الدقائق بدقة منزلتين عشريتين، تكون الصيغة ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


يشير إلى الارتفاع المستخدم كارتفاع مرجعي. إذا كان المرجع هو مستوى سطح البحر وكان الارتفاع فوق سطح البحر، يُعطى 0. إذا كان الارتفاع تحت سطح البحر، يُعطى القيمة 1 ويُشار إلى الارتفاع كقيمة مطلقة في وسم GPSAltitude.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


يشير إلى الارتفاع بناءً على المرجع في GPSAltitudeRef. يُعبّر عن الارتفاع كقيمة RATIONAL واحدة. وحدة المرجع هي الأمتار.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


يشير إلى الوقت بتوقيت UTC (التوقيت العالمي المنسق). يُعبّر عن TimeStamp كثلاث قيم RATIONAL تُعطي الساعة والدقيقة والثانية.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


يشير إلى أقمار GPS المستخدمة للقياسات. يمكن استخدام هذا الوسم لوصف عدد الأقمار، رقم تعريفها، زاوية الارتفاع، السمت، نسبة الإشارة إلى الضوضاء (SNR) ومعلومات أخرى بصيغة ASCII. الصيغة غير محددة. إذا كان مستقبل GPS غير قادر على إجراء القياسات، يجب ضبط قيمة الوسم إلى NULL.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


يشير إلى حالة مستقبل GPS عندما يتم تسجيل الصورة.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


يشير إلى وضع قياس GPS. - ثنائي أو ثلاثي الأبعاد.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


يشير إلى GPS DOP (درجة دقة البيانات). تُكتب قيمة HDOP أثناء القياس ثنائي الأبعاد، وPDOP أثناء القياس ثلاثي الأبعاد.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


يشير إلى الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS. تمثل الأحرف 'K' و'M' و'N' الكيلومترات في الساعة، والأميال في الساعة، والعقد.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


يشير إلى سرعة حركة مستقبل GPS.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


يشير إلى المرجع لتحديد اتجاه حركة مستقبل GPS. 'T' يدل على الاتجاه الحقيقي و'M' يدل على الاتجاه المغناطيسي.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


يشير إلى اتجاه حركة مستقبل GPS. نطاق القيم من 0.00 إلى 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


يشير إلى المرجع لتحديد اتجاه الصورة عند التقاطها. 'T' يدل على الاتجاه الحقيقي و'M' يدل على الاتجاه المغناطيسي.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


يشير إلى اتجاه الصورة عند التقاطها. نطاق القيم من 0.00 إلى 359.99.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


يشير إلى بيانات المسح الجيوديسي المستخدمة من قبل مستقبل GPS.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


يشير إلى ما إذا كانت خط عرض نقطة الوجهة شمالية أم جنوبية. القيمة ASCII 'N' تدل على خط العرض الشمالي، و'S' تدل على خط العرض الجنوبي.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


يشير إلى خط عرض نقطة الوجهة. يُعبّر عن خط العرض كثلاث قيم RATIONAL تُعطي الدرجات والدقائق والثواني على التوالي. إذا تم التعبير عن خط العرض بالدرجات والدقائق والثواني، فإن الصيغة النموذجية تكون dd/1,mm/1,ss/1. عندما تُستخدم الدرجات والدقائق وعلى سبيل المثال تُعطى كسور الدقائق بدقة منزلتين عشريتين، تكون الصيغة dd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


يشير إلى ما إذا كان خط طول نقطة الوجهة شرقياً أم غربياً. القيمة ASCII 'E' تدل على خط الطول الشرقي، و'W' تدل على خط الطول الغربي.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


يشير إلى خط طول نقطة الوجهة. يُعبّر عن خط الطول كثلاث قيم RATIONAL تُعطي الدرجات والدقائق والثواني على التوالي. إذا تم التعبير عن خط الطول بالدرجات والدقائق والثواني، فإن الصيغة النموذجية تكون ddd/1,mm/1,ss/1. عندما تُستخدم الدرجات والدقائق وعلى سبيل المثال تُعطى كسور الدقائق بدقة منزلتين عشريتين، تكون الصيغة ddd/1,mmmm/100,0/1.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


يشير إلى المرجع المستخدم لتحديد الاتجاه نحو نقطة الوجهة. 'T' يدل على الاتجاه الحقيقي و'M' يدل على الاتجاه المغناطيسي.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


يشير إلى الاتجاه نحو نقطة الوجهة. نطاق القيم من 0.00 إلى 359.99.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


يشير إلى الوحدة المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. تمثل الأحرف 'K' و'M' و'N' الكيلومترات، والأميال، والعقد.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


يشير إلى المسافة إلى نقطة الوجهة.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


سلسلة أحرف تسجل اسم الطريقة المستخدمة لتحديد الموقع. البايت الأول يشير إلى رمز الأحرف المستخدم، ويتبعه اسم الطريقة.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


سلسلة أحرف تسجل اسم منطقة GPS. البايت الأول يشير إلى رمز الأحرف المستخدم، ويتبعه اسم منطقة GPS.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


سلسلة أحرف تسجل معلومات التاريخ والوقت بالنسبة إلى UTC (التوقيت العالمي المنسق). الصيغة هي YYYY:MM:DD.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


يشير إلى ما إذا كان يتم تطبيق التصحيح التفاضلي على مستقبل GPS.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


لكل شريط، إزاحة البايتات لذلك الشريط. يُنصح باختيار ذلك بحيث لا يتجاوز عدد بايتات الشريط 64 كيلوبايت. وسم Aux.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


الإزاحة إلى بايت البداية (SOI) لبيانات الصورة المصغرة المضغوطة بصيغة JPEG. لا يُستخدم هذا لبيانات JPEG للصورة الأساسية.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


عدد بايتات بيانات الصورة المصغرة المضغوطة بصيغة JPEG. لا يُستخدم هذا لبيانات JPEG للصورة الأساسية. لا يتم تقسيم الصور المصغرة JPEG بل تُسجل كتيار بت JPEG مستمر من SOI إلى EOI. لا يجب تسجيل علامات Appn وCOM. يجب أن لا تتجاوز الصور المصغرة المضغوطة 64 كيلوبايت، بما في ذلك جميع البيانات الأخرى التي تُسجل في APP1.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


مؤشر إلى Exif IFD. التوافقية، يحتوي Exif IFD على نفس بنية IFD المحددة في TIFF. عادةً، ومع ذلك، لا يحتوي على بيانات الصورة كما هو الحال في TIFF.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


مؤشر gps ifd.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


عدد الصفوف لكل شريط. هذا هو عدد الصفوف في صورة شريط واحد عندما يتم تقسيم الصورة إلى أشرطة.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


إجمالي عدد البايتات في كل شريط.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


معلومات خاصة بالبيانات المضغوطة. عند تسجيل ملف مضغوط، يجب تسجيل العرض الصالح للصورة ذات المعنى في هذه العلامة، سواء كان هناك بيانات حشو أو علامة إعادة تشغيل.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


معلومات خاصة بالبيانات المضغوطة. عند تسجيل ملف مضغوط، يجب تسجيل الارتفاع الصالح للصورة ذات المعنى في هذه العلامة.

### Gamma {#Gamma}
```
public static final int Gamma
```


قيمة غاما

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


نوع الحساسية الفوتوغرافية

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


يشير إلى حساسية الإخراج القياسية للكاميرا

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


يشير إلى مؤشر التعرض الموصى به

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


معلومات حول قيمة سرعة ISO كما هو معرف في ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


تشير هذه العلامة إلى قيمة خط عرض سرعة ISO yyy كما هو معرف في ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


تشير هذه العلامة إلى قيمة خط عرض سرعة ISO zzz كما هو معرف في ISO 12232

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


يحتوي على اسم مالك الكاميرا

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


يحتوي على الرقم التسلسلي لجسم الكاميرا

### LensMake {#LensMake}
```
public static final int LensMake
```


تسجل هذه العلامة مصنع العدسة

### LensModel {#LensModel}
```
public static final int LensModel
```


تسجل هذه العلامة اسم نموذج العدسة ورقم النموذج

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


تسجل هذه العلامة الرقم التسلسلي للعدسة القابلة للتبديل

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


تلاحظ هذه العلامة الحد الأدنى للطول البؤري، الحد الأقصى للطول البؤري، رقم F الأدنى في الحد الأدنى للطول البؤري ورقم F الأدنى في الحد الأقصى للطول البؤري

