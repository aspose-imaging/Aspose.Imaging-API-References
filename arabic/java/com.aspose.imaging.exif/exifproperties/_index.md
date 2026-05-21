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
| [PhotometricInterpretation](#PhotometricInterpretation) | تركيب البكسل. |
| [ImageDescription](#ImageDescription) | سلسلة أحرف تُعطي عنوان الصورة. |
| [Make](#Make) | مصنّع معدات التسجيل. |
| [Model](#Model) | اسم الطراز أو رقم طراز المعدات. |
| [Orientation](#Orientation) | اتجاه الصورة كما يُعرض من حيث الصفوف والأعمدة. |
| [SamplesPerPixel](#SamplesPerPixel) | عدد المكوّنات لكل بكسل. |
| [XResolution](#XResolution) | عدد البكسلات لكل وحدة دقة في اتجاه عرض الصورة. |
| [YResolution](#YResolution) | عدد البكسلات لكل وحدة دقة في اتجاه طول الصورة. |
| [PlanarConfiguration](#PlanarConfiguration) | يُشير إلى ما إذا كانت مكوّنات البكسل مسجّلة بصيغة مجمّعة أو مخططة. |
| [ResolutionUnit](#ResolutionUnit) | الوحدة المستخدمة لقياس XResolution و YResolution. |
| [TransferFunction](#TransferFunction) | دالة تحويل للصورة، موصوفة بأسلوب جدولي. |
| [Software](#Software) | هذا الوسم يسجل اسم وإصدار البرنامج أو البرنامج الثابت للكاميرا أو جهاز إدخال الصورة المستخدم لإنشاء الصورة. |
| [DateTime](#DateTime) | تاريخ ووقت إنشاء الصورة. |
| [Artist](#Artist) | هذا الوسم يسجل اسم مالك الكاميرا أو المصور أو مُنشئ الصورة. |
| [WhitePoint](#WhitePoint) | لون نقطة الأبيض في الصورة. |
| [PrimaryChromaticities](#PrimaryChromaticities) | اللون اللوني للألوان الأساسية الثلاثة في الصورة. |
| [YCbCrCoefficients](#YCbCrCoefficients) | معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr. |
| [YCbCrSubSampling](#YCbCrSubSampling) | نسبة أخذ العينات لمكونات اللون بالنسبة لمكون الإضاءة. |
| [YCbCrPositioning](#YCbCrPositioning) | موضع مكونات اللون بالنسبة لمكون الإضاءة. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | قيمة نقطة الأسود المرجعية وقيمة نقطة الأبيض المرجعية. |
| [Copyright](#Copyright) | معلومات حقوق النشر. |
| [ExposureTime](#ExposureTime) | وقت التعرض، بالثواني. |
| [FNumber](#FNumber) | رقم F. |
| [ExposureProgram](#ExposureProgram) | فئة البرنامج الذي تستخدمه الكاميرا لتعيين التعرض عند التقاط الصورة. |
| [SpectralSensitivity](#SpectralSensitivity) | يشير إلى الحساسية الطيفية لكل قناة من الكاميرا المستخدمة. |
| [PhotographicSensitivity](#PhotographicSensitivity) | يشير إلى سرعة ISO وعرض ISO للكاميرا أو جهاز الإدخال كما هو محدد في ISO 12232. |
| [OECF](#OECF) | يشير إلى دالة التحويل الكهرو-بصري (OECF) المحددة في ISO 14524. |
| [ExifVersion](#ExifVersion) | إصدار Exif. |
| [DateTimeOriginal](#DateTimeOriginal) | التاريخ والوقت عندما تم إنشاء بيانات الصورة الأصلية. |
| [DateTimeDigitized](#DateTimeDigitized) | تاريخ ووقت الرقمنة. |
| [ComponentsConfiguration](#ComponentsConfiguration) | تكوين المكونات. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | خاص بالبيانات المضغوطة؛ يوضح عدد البتات المضغوطة لكل بكسل. |
| [ShutterSpeedValue](#ShutterSpeedValue) | قيمة سرعة الغالق. |
| [ApertureValue](#ApertureValue) | قيمة فتحة العدسة. |
| [BrightnessValue](#BrightnessValue) | قيمة السطوع. |
| [ExposureBiasValue](#ExposureBiasValue) | قيمة انحياز التعرض. |
| [MaxApertureValue](#MaxApertureValue) | قيمة أقصى فتحة. |
| [SubjectDistance](#SubjectDistance) | المسافة إلى الهدف، بالمتر. |
| [MeteringMode](#MeteringMode) | وضع القياس. |
| [LightSource](#LightSource) | نوع مصدر الضوء. |
| [Flash](#Flash) | يشير إلى حالة الفلاش عندما تم التقاط الصورة. |
| [FocalLength](#FocalLength) | البعد البؤري الفعلي للعدسة، بالمليمتر. |
| [SubjectArea](#SubjectArea) | تشير هذه العلامة إلى موقع ومساحة العنصر الرئيسي في المشهد العام. |
| [MakerNote](#MakerNote) | علامة للمصنعين لكتاب Exif لتسجيل أي معلومات مرغوبة. |
| [UserComment](#UserComment) | علامة لمستخدمي Exif لكتابة كلمات مفتاحية أو تعليقات على الصورة بجانب تلك الموجودة في ImageDescription، وبدون قيود ترميز الأحرف لعلامة ImageDescription. |
| [SubsecTime](#SubsecTime) | علامة تُستخدم لتسجيل أجزاء الثواني لعلامة DateTime. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | علامة تُستخدم لتسجيل أجزاء الثواني لعلامة DateTimeOriginal. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | علامة تُستخدم لتسجيل أجزاء الثواني لعلامة DateTimeDigitized. |
| [FlashpixVersion](#FlashpixVersion) | إصدار تنسيق Flashpix المدعوم من ملف FPXR. |
| [ColorSpace](#ColorSpace) | علامة معلومات مساحة اللون (ColorSpace) تُسجل دائمًا كمحدد مساحة اللون. |
| [RelatedSoundFile](#RelatedSoundFile) | ملف الصوت المرتبط. |
| [FlashEnergy](#FlashEnergy) | يشير إلى طاقة الفلاش في وقت التقاط الصورة، مقاسة بوحدات Beam Candle Power Seconds (BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | تسجل هذه العلامة جدول التردد المكاني للكاميرا أو جهاز الإدخال وقيم SFR في اتجاه عرض الصورة، ارتفاع الصورة، والاتجاه القطري، كما هو محدد في ISO 12233. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | يشير إلى عدد البكسلات في اتجاه عرض الصورة (X) لكل وحدة FocalPlaneResolutionUnit على مستوى الطائرة البؤرية للكاميرا. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | يشير إلى عدد البكسلات في اتجاه ارتفاع الصورة (Y) لكل وحدة FocalPlaneResolutionUnit على مستوى الطائرة البؤرية للكاميرا. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | يشير إلى الوحدة المستخدمة لقياس FocalPlaneXResolution و FocalPlaneYResolution. |
| [SubjectLocation](#SubjectLocation) | يشير إلى موقع العنصر الرئيسي في المشهد. |
| [ExposureIndex](#ExposureIndex) | يشير إلى مؤشر التعرض المختار على الكاميرا أو جهاز الإدخال عند التقاط الصورة. |
| [SensingMethod](#SensingMethod) | يشير إلى نوع مستشعر الصورة على الكاميرا أو جهاز الإدخال. |
| [FileSource](#FileSource) | مصدر الملف. |
| [SceneType](#SceneType) | يشير إلى نوع المشهد. |
| [CFAPattern](#CFAPattern) | يشير إلى نمط التصفية اللونية (CFA) الهندسي لمستشعر الصورة عند استخدام مستشعر لون منطقة شريحة واحدة. |
| [CustomRendered](#CustomRendered) | تشير هذه العلامة إلى استخدام معالجة خاصة على بيانات الصورة، مثل العرض الموجه للإخراج. |
| [ExposureMode](#ExposureMode) | تشير هذه العلامة إلى وضع التعرض المحدد عند التقاط الصورة. |
| [WhiteBalance](#WhiteBalance) | تشير هذه العلامة إلى وضع توازن اللون الأبيض المحدد عند التقاط الصورة. |
| [DigitalZoomRatio](#DigitalZoomRatio) | تشير هذه العلامة إلى نسبة التكبير الرقمي عندما تم التقاط الصورة. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | تشير هذه العلامة إلى البعد البؤري المكافئ بافتراض كاميرا فيلم 35 مم، بالمليمتر. |
| [SceneCaptureType](#SceneCaptureType) | تشير هذه العلامة إلى نوع المشهد الذي تم تصويره. |
| [GainControl](#GainControl) | تشير هذه العلامة إلى درجة تعديل الكسب الكلي للصورة. |
| [Contrast](#Contrast) | تشير هذه العلامة إلى اتجاه معالجة التباين التي طبقتها الكاميرا عند التقاط الصورة. |
| [Saturation](#Saturation) | تشير هذه العلامة إلى اتجاه معالجة التشبع التي طبقتها الكاميرا عند التقاط الصورة. |
| [Sharpness](#Sharpness) | تشير هذه العلامة إلى اتجاه معالجة الحدة التي طبقتها الكاميرا عند التقاط الصورة |
| [DeviceSettingDescription](#DeviceSettingDescription) | تشير هذه العلامة إلى معلومات حول ظروف التصوير لكاميرا نموذج معين. |
| [SubjectDistanceRange](#SubjectDistanceRange) | تشير هذه العلامة إلى المسافة إلى الهدف. |
| [ImageUniqueID](#ImageUniqueID) | معرف الصورة الفريد. |
| [GPSVersionID](#GPSVersionID) | يشير إلى إصدار GPSInfoIFD. |
| [GPSLatitudeRef](#GPSLatitudeRef) | يشير إلى ما إذا كان خط العرض شماليًا أم جنوبيًا. |
| [GPSLatitude](#GPSLatitude) | يشير إلى خط العرض. |
| [GPSLongitudeRef](#GPSLongitudeRef) | يشير إلى ما إذا كان خط الطول شرقًا أم غربًا. |
| [GPSLongitude](#GPSLongitude) | يشير إلى خط الطول. |
| [GPSAltitudeRef](#GPSAltitudeRef) | يشير إلى الارتفاع المستخدم كارتفاع مرجعي. |
| [GPSAltitude](#GPSAltitude) | يشير إلى الارتفاع بناءً على المرجع في GPSAltitudeRef. |
| [GPSTimestamp](#GPSTimestamp) | يشير إلى الوقت بتوقيت UTC (التوقيت العالمي المنسق). |
| [GPSSatellites](#GPSSatellites) | يشير إلى أقمار GPS المستخدمة للقياسات. |
| [GPSStatus](#GPSStatus) | يشير إلى حالة مستقبل GPS عندما تم تسجيل الصورة. |
| [GPSMeasureMode](#GPSMeasureMode) | يشير إلى وضع قياس GPS. |
| [GPSDOP](#GPSDOP) | يشير إلى GPS DOP (درجة دقة البيانات). |
| [GPSSpeedRef](#GPSSpeedRef) | يشير إلى الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS. |
| [GPSSpeed](#GPSSpeed) | يشير إلى سرعة حركة مستقبل GPS. |
| [GPSTrackRef](#GPSTrackRef) | يشير إلى المرجع لتحديد اتجاه حركة مستقبل GPS. |
| [GPSTrack](#GPSTrack) | يشير إلى اتجاه حركة مستقبل GPS. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | يشير إلى المرجع لتحديد اتجاه الصورة عند التقاطها. |
| [GPSImgDirection](#GPSImgDirection) | يشير إلى اتجاه الصورة عند التقاطها. |
| [GPSMapDatum](#GPSMapDatum) | يشير إلى بيانات المسح الجيوديسي المستخدمة من قبل مستقبل GPS. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | يشير إلى ما إذا كانت خطوط العرض لنقطة الوجهة شمالية أم جنوبية. |
| [GPSDestLatitude](#GPSDestLatitude) | يشير إلى خط عرض نقطة الوجهة. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | يشير إلى ما إذا كانت خطوط الطول لنقطة الوجهة شرقية أم غربية. |
| [GPSDestLongitude](#GPSDestLongitude) | يشير إلى خط طول نقطة الوجهة. |
| [GPSDestBearingRef](#GPSDestBearingRef) | يشير إلى المرجع المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| [GPSDestBearing](#GPSDestBearing) | يشير إلى الاتجاه إلى نقطة الوجهة. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | يشير إلى الوحدة المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| [GPSDestDistance](#GPSDestDistance) | يشير إلى المسافة إلى نقطة الوجهة. |
| [GPSProcessingMethod](#GPSProcessingMethod) | سلسلة أحرف تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| [GPSAreaInformation](#GPSAreaInformation) | سلسلة أحرف تسجل اسم منطقة GPS. |
| [GPSDateStamp](#GPSDateStamp) | سلسلة أحرف تسجل معلومات التاريخ والوقت بالنسبة إلى التوقيت العالمي المنسق (UTC). |
| [GPSDifferential](#GPSDifferential) | يشير إلى ما إذا كان يتم تطبيق التصحيح التفاضلي على مستقبل GPS. |
| [StripOffsets](#StripOffsets) | لكل شريط، إزاحة البايت لذلك الشريط. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | الإزاحة إلى بايت البداية (SOI) لبيانات الصورة المصغرة المضغوطة بصيغة JPEG. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | عدد بايتات بيانات الصورة المصغرة المضغوطة بصيغة JPEG. |
| [ExifIfdPointer](#ExifIfdPointer) | مؤشر إلى Exif IFD. |
| [GPSIfdPointer](#GPSIfdPointer) | مؤشر gps ifd. |
| [RowsPerStrip](#RowsPerStrip) | عدد الصفوف لكل شريط. |
| [StripByteCounts](#StripByteCounts) | إجمالي عدد البايتات في كل شريط. |
| [PixelXDimension](#PixelXDimension) | معلومات خاصة بالبيانات المضغوطة. |
| [PixelYDimension](#PixelYDimension) | معلومات خاصة بالبيانات المضغوطة. |
| [Gamma](#Gamma) | قيمة جاما |
| [SensitivityType](#SensitivityType) | نوع الحساسية الفوتوغرافية |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | يشير إلى حساسية الإخراج القياسية للكاميرا |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | يشير إلى مؤشر التعرض الموصى به |
| [ISOSpeed](#ISOSpeed) | معلومات حول قيمة سرعة ISO كما هو معرف في ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | تشير هذه العلامة إلى قيمة نطاق سرعة ISO yyy كما هو معرف في ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | تشير هذه العلامة إلى قيمة نطاق سرعة ISO zzz كما هو معرف في ISO 12232 |
| [CameraOwnerName](#CameraOwnerName) | يحتوي على اسم مالك الكاميرا |
| [BodySerialNumber](#BodySerialNumber) | يحتوي على الرقم التسلسلي لجسم الكاميرا |
| [LensMake](#LensMake) | تسجل هذه العلامة شركة تصنيع العدسة |
| [LensModel](#LensModel) | تسجل هذه العلامة اسم نموذج lens\`s ورقم النموذج |
| [LensSerialNumber](#LensSerialNumber) | تسجل هذه العلامة الرقم التسلسلي للعدسة القابلة للتبديل |
| [LensSpecification](#LensSpecification) | تشير هذه العلامة إلى الحد الأدنى للبعد البؤري، الحد الأقصى للبعد البؤري، أصغر رقم F في الحد الأدنى للبعد البؤري وأصغر رقم F في الحد الأقصى للبعد البؤري |
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


نظام الضغط المستخدم لبيانات الصورة. عندما تكون الصورة الأساسية مضغوطة بصيغة JPEG، لا تكون هذه الإشارة ضرورية وتُحذف.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


تركيب البكسل.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


سلسلة أحرف تعطي عنوان الصورة. قد تكون تعليقًا مثل "1988 company picnic" أو ما شابه.

### Make {#Make}
```
public static final int Make
```


مصنّع معدات التسجيل. هذا هو مصنّع الـ DSC أو الماسح الضوئي أو محول الفيديو أو أي معدات أخرى التي أنشأت الصورة. عندما يُترك الحقل فارغًا، يُعامل على أنه غير معروف.

### Model {#Model}
```
public static final int Model
```


اسم النموذج أو رقم النموذج للمعدات. هذا هو اسم النموذج أو رقمه للـ DSC أو الماسح الضوئي أو محول الفيديو أو أي معدات أخرى التي أنشأت الصورة. عندما يُترك الحقل فارغًا، يُعامل على أنه غير معروف.

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


عدد البكسلات لكل وحدة دقة في اتجاه عرض الصورة (ImageWidth). عندما تكون دقة الصورة غير معروفة، يتم تعيين 72 [dpi].

### YResolution {#YResolution}
```
public static final int YResolution
```


عدد البكسلات لكل وحدة دقة في اتجاه طول الصورة (ImageLength). يتم تعيين نفس القيمة كما في XResolution.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


يشير إلى ما إذا كانت مكوّنات البكسل مسجلة بصيغة مجمّعة (chunky) أو مخططة (planar). إذا لم يكن هذا الحقل موجودًا، يُفترض القيمة الافتراضية للـ TIFF وهي 1 (chunky).

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


الوحدة المستخدمة لقياس XResolution و YResolution. تُستخدم نفس الوحدة لكلا القيمتين. إذا كانت دقة الصورة غير معروفة، يتم تعيين 2 (بوصة).

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


دالة نقل للصورة، موصوفة بأسلوب جدولي. عادةً لا تكون هذه العلامة ضرورية، لأن مساحة اللون محددة في علامة معلومات مساحة اللون ColorSpace.

### Software {#Software}
```
public static final int Software
```


تسجل هذه العلامة اسم وإصدار البرنامج أو البرنامج الثابت للكاميرا أو جهاز إدخال الصورة المستخدم لإنشاء الصورة. الصيغة التفصيلية غير محددة، لكن يُنصح باتباع المثال الموضح أدناه. عندما يُترك الحقل فارغًا، يُعامل على أنه غير معروف.

### DateTime {#DateTime}
```
public static final int DateTime
```


تاريخ ووقت إنشاء الصورة. في معيار Exif، هو التاريخ والوقت الذي تم فيه تعديل الملف.

### Artist {#Artist}
```
public static final int Artist
```


تسجل هذه العلامة اسم مالك الكاميرا أو المصور أو منشئ الصورة. الصيغة التفصيلية غير محددة، لكن يُنصح بكتابة المعلومات كما في المثال أدناه لتسهيل التوافقية. عندما يُترك الحقل فارغًا، يُعامل على أنه غير معروف. (مثال: "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


إشباع اللون لنقطة الأبيض في الصورة. عادةً لا تكون هذه العلامة ضرورية، لأن مساحة اللون محددة في علامة معلومات مساحة اللون ColorSpace.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


إشباع اللون للألوان الأساسية الثلاثة في الصورة. عادةً لا تكون هذه العلامة ضرورية، لأن مساحة اللون محددة في علامة معلومات مساحة اللون ColorSpace.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


معاملات المصفوفة للتحويل من بيانات صورة RGB إلى YCbCr.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


نسبة أخذ العينات لمكونات اللون بالنسبة لمكون الإضاءة.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


موضع مكونات التشبع اللوني بالنسبة إلى مكون الإضاءة. يُخصص هذا الحقل فقط لبيانات JPEG المضغوطة أو بيانات YCbCr غير المضغوطة. القيمة الافتراضية في TIFF هي 1 (متمركز)؛ ولكن عندما Y:Cb:Cr = 4:2:2 يُنصح في هذا المعيار باستخدام 2 (متجاور) لتسجيل البيانات، لتحسين جودة الصورة عند عرضها على أنظمة التلفاز. عندما لا يكون هذا الحقل موجودًا، يجب على القارئ افتراض القيمة الافتراضية في TIFF. في حالة Y:Cb:Cr = 4:2:0 يُنصح بالقيمة الافتراضية في TIFF (متمركز). إذا لم يكن القارئ قادرًا على دعم كلا نوعي YCbCrPositioning، يجب عليه اتباع القيمة الافتراضية في TIFF بغض النظر عن القيمة في هذا الحقل. يُفضَّل أن يكون القارئ \" قادرًا على دعم كل من الوضع المتمركز والمتجاور.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


قيمة نقطة الأسود المرجعية وقيمة نقطة الأبيض المرجعية. لا توجد قيم افتراضية في TIFF، ولكن القيم أدناه تُعطى كقيم افتراضية هنا. يتم إعلان مساحة اللون في علامة معلومات مساحة اللون، وتكون القيمة الافتراضية هي القيمة التي توفر الخصائص المثلى للصورة وفقًا لشرط التوافقية.

### Copyright {#Copyright}
```
public static final int Copyright
```


معلومات حقوق النشر. في هذا المعيار تُستخدم العلامة للإشارة إلى حقوق النشر لكل من المصور والمحرر. إنها إشعار حقوق النشر للشخص أو المؤسسة التي تدعي حقوق الصورة. يجب كتابة بيان حقوق النشر للتوافقية بما في ذلك التاريخ والحقوق في هذا الحقل؛ مثال: \"Copyright, John Smith, 19xx. All rights reserved.\" في هذا المعيار يسجل الحقل حقوق النشر لكل من المصور والمحرر، مع تسجيل كل منهما في جزء منفصل من البيان. عندما يكون هناك تمييز واضح بين حقوق النشر للمصور والمحرر، تُكتب بالترتيب: حقوق النشر للمصور تليها حقوق النشر للمحرر، مفصولة بـ NULL (في هذه الحالة، بما أن البيان ينتهي أيضًا بـ NULL، هناك رمزا NULL). عندما تُعطى فقط حقوق النشر للمصور، تُختتم برمز NULL واحد. عندما تُعطى فقط حقوق النشر للمحرر، يتكون جزء حقوق النشر للمصور من مساحة واحدة تليها رمز NULL نهائي، ثم تُعطى حقوق النشر للمحرر. عندما يُترك الحقل فارغًا، يُعامل كغير معروف.

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


فئة البرنامج الذي تستخدمه الكاميرا لتعيين التعرض عند التقاط الصورة.

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


يشير إلى دالة التحويل الكهرو-بصري (OECF) المحددة في ISO 14524.

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


خاص بالبيانات المضغوطة؛ يوضح عدد البتات المضغوطة لكل بكسل.

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


قيمة انحياز التعرض.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


قيمة أقصى فتحة.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


المسافة إلى الهدف، بالمتر.

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


تشير هذه العلامة إلى موقع ومساحة العنصر الرئيسي في المشهد العام.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


علامة للمصنعين لكتاب Exif لتسجيل أي معلومات يرغبون بها. المحتوى متروك للمصنع، ولكن لا ينبغي استخدام هذه العلامة لأي غرض غير الغرض المقصود منها.

### UserComment {#UserComment}
```
public static final int UserComment
```


علامة لمستخدمي Exif لكتابة كلمات مفتاحية أو تعليقات على الصورة بجانب تلك الموجودة في ImageDescription، وبدون قيود ترميز الأحرف لعلامة ImageDescription.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


علامة تُستخدم لتسجيل أجزاء الثواني لعلامة DateTime.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


علامة تُستخدم لتسجيل أجزاء الثواني لعلامة DateTimeOriginal.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


علامة تُستخدم لتسجيل أجزاء الثواني لعلامة DateTimeDigitized.

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


يشير إلى طاقة الفلاش في وقت التقاط الصورة، مقاسة بوحدات Beam Candle Power Seconds (BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


تسجل هذه العلامة جدول التردد المكاني للكاميرا أو جهاز الإدخال وقيم SFR في اتجاه عرض الصورة، ارتفاع الصورة، والاتجاه القطري، كما هو محدد في ISO 12233.

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


يحدد الوحدة المستخدمة لقياس FocalPlaneXResolution وFocalPlaneYResolution. هذه القيمة هي نفسها ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


يحدد موقع العنصر الرئيسي في المشهد. قيمة هذه العلامة تمثل البكسل في مركز العنصر الرئيسي بالنسبة إلى الحافة اليسرى، قبل معالجة الدوران وفقًا لعلامة Rotation.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


يشير إلى مؤشر التعرض المختار على الكاميرا أو جهاز الإدخال عند التقاط الصورة.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


يشير إلى نوع مستشعر الصورة على الكاميرا أو جهاز الإدخال.

### FileSource {#FileSource}
```
public static final int FileSource
```


مصدر الملف.

### SceneType {#SceneType}
```
public static final int SceneType
```


يحدد نوع المشهد. إذا تم تسجيل الصورة بواسطة DSC، يجب دائمًا ضبط قيمة هذه العلامة إلى 1، مما يدل على أن الصورة تم تصويرها مباشرة.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


يحدد نمط التصفية الهندسي (CFA) لمستشعر الصورة عندما يُستخدم مستشعر لون بمنطقة شريحة واحدة. لا ينطبق على جميع طرق الاستشعار.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


تشير هذه العلامة إلى استخدام معالجة خاصة على بيانات الصورة، مثل العرض الموجه للإخراج. عندما تُجرى معالجة خاصة، يُتوقع من القارئ تعطيل أو تقليل أي معالجة إضافية.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


تشير هذه العلامة إلى وضع التعرض المحدد عند التقاط الصورة. في وضع التعدد التلقائي، تلتقط الكاميرا سلسلة من الإطارات لنفس المشهد بإعدادات تعريض مختلفة.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


تشير هذه العلامة إلى وضع توازن اللون الأبيض المحدد عند التقاط الصورة.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


تشير هذه العلامة إلى نسبة التكبير الرقمي عند التقاط الصورة. إذا كان البسط للقيمة المسجلة يساوي 0، فهذا يدل على عدم استخدام التكبير الرقمي.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


تشير هذه العلامة إلى البُعد البؤري المكافئ بافتراض كاميرا فيلم 35 مم، بالملم. قيمة 0 تعني أن البُعد البؤري غير معروف. لاحظ أن هذه العلامة تختلف عن علامة FocalLength.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


تشير هذه العلامة إلى نوع المشهد الذي تم تصويره. يمكن أيضًا استخدامها لتسجيل الوضع الذي تم فيه التقاط الصورة.

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


تشير هذه العلامة إلى معلومات حول ظروف التقاط الصورة لنموذج كاميرا معين. تُستخدم العلامة فقط للإشارة إلى ظروف التقاط الصورة في القارئ.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


تشير هذه العلامة إلى المسافة إلى الهدف.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


معرف الصورة الفريد.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


يشير إلى إصدار GPSInfoIFD.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


يشير إلى ما إذا كان خط العرض شماليًا أم جنوبيًا.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


يحدد خط العرض. يُعبَّر عن خط العرض بثلاث قيم RATIONAL تُعطي الدرجات والدقائق والثواني على التوالي. إذا تم التعبير عن خط العرض بالدرجات والدقائق والثواني، يكون الشكل النموذجي dd/1,mm/1,ss/1. عندما تُستخدم الدرجات والدقائق وعلى سبيل المثال تُعطى كسور الدقائق حتى منزلتين عشريتين، يكون الشكل dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


يشير إلى ما إذا كان خط الطول شرقًا أم غربًا.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


يحدد خط الطول. يُعبَّر عن خط الطول بثلاث قيم RATIONAL تُعطي الدرجات والدقائق والثواني على التوالي. إذا تم التعبير عن خط الطول بالدرجات والدقائق والثواني، يكون الشكل النموذجي ddd/1,mm/1,ss/1. عندما تُستخدم الدرجات والدقائق وعلى سبيل المثال تُعطى كسور الدقائق حتى منزلتين عشريتين، يكون الشكل ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


يحدد الارتفاع المستخدم كارتفاع مرجعي. إذا كان المرجع هو مستوى سطح البحر وكان الارتفاع فوق سطح البحر، تُعطى القيمة 0. إذا كان الارتفاع تحت سطح البحر، تُعطى القيمة 1 ويُشار إلى الارتفاع كقيمة مطلقة في علامة GPSAltitude.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


يحدد الارتفاع بناءً على المرجع في GPSAltitudeRef. يُعبَّر عن الارتفاع بقيمة RATIONAL واحدة. الوحدة المرجعية هي الأمتار.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


يحدد الوقت كـ UTC (التوقيت العالمي المنسق). يُعبَّر عن TimeStamp بثلاث قيم RATIONAL تُعطي الساعة والدقيقة والثانية.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


يحدد أقمار GPS المستخدمة للقياسات. يمكن استخدام هذه العلامة لوصف عدد الأقمار، رقم تعريفها، زاوية الارتفاع، السمت، نسبة الإشارة إلى الضوضاء (SNR) ومعلومات أخرى بصيغة ASCII. الشكل غير محدد. إذا كان مستقبل GPS غير قادر على إجراء القياسات، يجب ضبط قيمة العلامة إلى NULL.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


يشير إلى حالة مستقبل GPS عندما تم تسجيل الصورة.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


يحدد وضع قياس GPS. - ثنائي أو ثلاثي الأبعاد.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


يحدد GPS DOP (درجة دقة البيانات). تُكتب قيمة HDOP أثناء القياس ثنائي الأبعاد، وPDOP أثناء القياس ثلاثي الأبعاد.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


يحدد الوحدة المستخدمة لتعبير سرعة حركة مستقبل GPS. تمثل 'K' و'M' و'N' الكيلومترات في الساعة، والأميال في الساعة، والعقد.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


يشير إلى سرعة حركة مستقبل GPS.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


يشير إلى المرجع المستخدم لتحديد اتجاه حركة مستقبل GPS. 'T' يدل على الاتجاه الحقيقي و'M' هو الاتجاه المغناطيسي.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


يشير إلى اتجاه حركة مستقبل GPS. نطاق القيم من 0.00 إلى 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


يشير إلى المرجع المستخدم لتحديد اتجاه الصورة عند التقاطها. 'T' يدل على الاتجاه الحقيقي و'M' هو الاتجاه المغناطيسي.

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


يشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا. القيمة ASCII 'N' تدل على خط العرض الشمالي، و'S' تدل على خط العرض الجنوبي.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


يشير إلى خط عرض نقطة الوجهة. يُعبَّر عن خط العرض كثلاث قيم RATIONAL تمثل الدرجات والدقائق والثواني على التوالي. إذا تم التعبير عن خط العرض بالدرجات والدقائق والثواني، يكون الشكل النموذجي dd/1,mm/1,ss/1. عندما تُستخدم الدرجات والدقائق وعلى سبيل المثال تُعطى كسور الدقائق بدقة منزلتين عشريتين، يكون الشكل dd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


يشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا. القيمة ASCII 'E' تدل على خط الطول الشرقي، و'W' تدل على خط الطول الغربي.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


يشير إلى خط طول نقطة الوجهة. يُعبَّر عن خط الطول كثلاث قيم RATIONAL تمثل الدرجات والدقائق والثواني على التوالي. إذا تم التعبير عن خط الطول بالدرجات والدقائق والثواني، يكون الشكل النموذجي ddd/1,mm/1,ss/1. عندما تُستخدم الدرجات والدقائق وعلى سبيل المثال تُعطى كسور الدقائق بدقة منزلتين عشريتين، يكون الشكل ddd/1,mmmm/100,0/1.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


يشير إلى المرجع المستخدم لتحديد الاتجاه نحو نقطة الوجهة. 'T' يدل على الاتجاه الحقيقي و'M' هو الاتجاه المغناطيسي.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


يشير إلى الاتجاه نحو نقطة الوجهة. نطاق القيم من 0.00 إلى 359.99.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


يشير إلى الوحدة المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. 'K' و'M' و'N' تمثل الكيلومترات والأميال والعقد.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


يشير إلى المسافة إلى نقطة الوجهة.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


سلسلة أحرف تسجل اسم الطريقة المستخدمة لتحديد الموقع. البايت الأول يشير إلى رمز الحرف المستخدم، ويتبعه اسم الطريقة.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


سلسلة أحرف تسجل اسم منطقة GPS. البايت الأول يشير إلى رمز الحرف المستخدم، ويتبعه اسم منطقة GPS.

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


بالنسبة لكل شريط، إزاحة البايت لذلك الشريط. يُنصح باختيار ذلك بحيث لا يتجاوز عدد بايتات الشريط 64 كيلوبايت. علامة Aux.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


الإزاحة إلى بايت البداية (SOI) لبيانات الصورة المصغرة المضغوطة بصيغة JPEG. لا يُستخدم هذا لبيانات JPEG للصورة الأساسية.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


عدد بايتات بيانات الصورة المصغرة المضغوطة بصيغة JPEG. لا يُستخدم هذا لبيانات JPEG للصورة الأساسية. لا يتم تقسيم الصور المصغرة JPEG بل تُسجل كتيار بت JPEG مستمر من SOI إلى EOI. لا ينبغي تسجيل علامات Appn وCOM. يجب تسجيل الصور المصغرة المضغوطة في حجم لا يتجاوز 64 كيلوبايت، بما في ذلك جميع البيانات الأخرى التي تُسجل في APP1.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


مؤشر إلى Exif IFD. التوافقية، يحتوي Exif IFD على نفس بنية IFD المحددة في TIFF. عادةً، لا يحتوي على بيانات صورة كما هو الحال في TIFF.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


مؤشر gps ifd.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


عدد الصفوف لكل شريط. هذا هو عدد الصفوف في صورة شريط واحد عندما تُقسم الصورة إلى أشرطة.

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


قيمة جاما

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


تشير هذه العلامة إلى قيمة نطاق سرعة ISO yyy كما هو معرف في ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


تشير هذه العلامة إلى قيمة نطاق سرعة ISO zzz كما هو معرف في ISO 12232

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


تسجل هذه العلامة شركة تصنيع العدسة

### LensModel {#LensModel}
```
public static final int LensModel
```


تسجل هذه العلامة اسم نموذج lens\`s ورقم النموذج

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


تسجل هذه العلامة الرقم التسلسلي للعدسة القابلة للتبديل

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


تشير هذه العلامة إلى الحد الأدنى للبعد البؤري، الحد الأقصى للبعد البؤري، أصغر رقم F في الحد الأدنى للبعد البؤري وأصغر رقم F في الحد الأقصى للبعد البؤري

