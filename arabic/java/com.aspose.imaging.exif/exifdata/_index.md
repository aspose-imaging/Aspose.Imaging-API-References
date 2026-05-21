---
title: "ExifData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "حاوية بيانات EXIF."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.exif/exifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller)

**All Implemented Interfaces:**
[com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class ExifData extends TiffDataTypeController implements IImageMetadataFormat
```

حاوية بيانات EXIF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ExifData()](#ExifData--) | ينشئ مثيلاً جديدًا للفئة `ExifData`. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | ينشئ مثيلاً جديدًا للفئة `ExifData` مع بيانات من مصفوفة. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | ينشئ مثيلاً جديدًا للفئة `ExifData` مع بيانات من مصفوفة. |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | ينشئ مثيلاً جديدًا للفئة [ExifData](../../com.aspose.imaging.exif/exifdata) مع بيانات من مصفوفة. |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | ينشئ مثيلاً جديدًا للفئة [ExifData](../../com.aspose.imaging.exif/exifdata). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تدفق بيانات EXIF المُنشأ من big endian. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تدفق بيانات EXIF المُنشأ من big endian. |
| [getMake()](#getMake--) | يحصل على الشركة المصنعة لمعدات التسجيل. |
| [setMake(String value)](#setMake-java.lang.String-) | يعيّن الشركة المصنعة لمعدات التسجيل. |
| [getApertureValue()](#getApertureValue--) | يحصل أو يعيّن قيمة الفتحة. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يعيّن قيمة الفتحة. |
| [getBodySerialNumber()](#getBodySerialNumber--) | يحصل أو يعيّن رقم تسلسل جسم الكاميرا. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | يحصل أو يعيّن رقم تسلسل جسم الكاميرا. |
| [getBrightnessValue()](#getBrightnessValue--) | يحصل أو يعيّن قيمة السطوع. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | يحصل أو يعيّن قيمة السطوع. |
| [getCFAPattern()](#getCFAPattern--) | يحصل أو يعيّن نمط CFA. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | يحصل أو يعيّن نمط CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | يحصل أو يعيّن اسم مالك الكاميرا |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | يحصل أو يعيّن اسم مالك الكاميرا |
| [getColorSpace()](#getColorSpace--) | يحصل أو يعيّن مساحة اللون. |
| [setColorSpace(int value)](#setColorSpace-int-) | يحصل أو يعيّن مساحة اللون. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | يحصل أو يعيّن تكوين المكونات. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | يحصل أو يعيّن تكوين المكونات. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | يحصل أو يعيّن عدد البتات المضغوطة لكل بكسل. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يعيّن عدد البتات المضغوطة لكل بكسل. |
| [getContrast()](#getContrast--) | يحصل أو يضبط التباين. |
| [setContrast(int value)](#setContrast-int-) | يحصل أو يضبط التباين. |
| [getCustomRendered()](#getCustomRendered--) | يحصل أو يضبط العرض المخصص. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | يحصل أو يضبط العرض المخصص. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | يحصل أو يضبط تاريخ ووقت الرقمنة. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | يحصل أو يضبط تاريخ ووقت الرقمنة. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | يحصل أو يضبط تاريخ ووقت الأصل. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | يحصل أو يضبط تاريخ ووقت الأصل. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | يحصل أو يضبط وصف إعدادات الجهاز |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | يحصل أو يضبط وصف إعدادات الجهاز |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | يحصل أو يضبط نسبة التكبير الرقمي. |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط نسبة التكبير الرقمي. |
| [getExifVersion()](#getExifVersion--) | يحصل أو يضبط نسخة EXIF. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | يحصل أو يضبط نسخة EXIF. |
| [getExposureBiasValue()](#getExposureBiasValue--) | يحصل أو يضبط قيمة انحياز التعرض. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | يحصل أو يضبط قيمة انحياز التعرض. |
| [getExposureIndex()](#getExposureIndex--) | يحصل أو يضبط مؤشر التعرض. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط مؤشر التعرض. |
| [getExposureMode()](#getExposureMode--) | يحصل أو يضبط وضع التعرض. |
| [setExposureMode(int value)](#setExposureMode-int-) | يحصل أو يضبط وضع التعرض. |
| [getExposureProgram()](#getExposureProgram--) | يحصل أو يضبط برنامج التعرض. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | يحصل أو يضبط برنامج التعرض. |
| [getExposureTime()](#getExposureTime--) | يحصل أو يضبط زمن التعرض. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط زمن التعرض. |
| [getFNumber()](#getFNumber--) | يحصل أو يضبط رقم F. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط رقم F. |
| [getFileSource()](#getFileSource--) | يحصل أو يضبط نوع مصدر الملف. |
| [setFileSource(byte value)](#setFileSource-byte-) | يحصل أو يضبط نوع مصدر الملف. |
| [getFlash()](#getFlash--) | يحصل أو يضبط الفلاش. |
| [setFlash(int value)](#setFlash-int-) | يحصل أو يضبط الفلاش. |
| [getFlashEnergy()](#getFlashEnergy--) | يحصل أو يضبط طاقة الفلاش. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط طاقة الفلاش. |
| [getFlashpixVersion()](#getFlashpixVersion--) | يحصل أو يضبط نسخة فلاش pix. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | يحصل أو يضبط نسخة فلاش pix. |
| [getFocalLength()](#getFocalLength--) | يحصل أو يضبط البعد البؤري. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط البعد البؤري. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | يحصل أو يضبط البعد البؤري في فيلم 35 مم. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | يحصل أو يضبط البعد البؤري في فيلم 35 مم. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | يحصل أو يضبط وحدة دقة المستوى البؤري. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | يحصل أو يضبط وحدة دقة المستوى البؤري. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | يحصل أو يضبط دقة المستوى البؤري X. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة المستوى البؤري X. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | يحصل أو يضبط دقة المستوى البؤري Y. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة المستوى البؤري Y. |
| [getGPSAltitude()](#getGPSAltitude--) | يحصل أو يضبط ارتفاع GPS. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط ارتفاع GPS. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | يحصل أو يضبط ارتفاع GPS المستخدم كارتفاع مرجعي. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | يحصل أو يضبط ارتفاع GPS المستخدم كارتفاع مرجعي. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | يحصل أو يضبط معلومات منطقة GPS. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | يحصل أو يضبط معلومات منطقة GPS. |
| [getGPSDOP()](#getGPSDOP--) | يحصل أو يضبط قيمة DOP لنظام GPS (درجة دقة البيانات). |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط قيمة DOP لنظام GPS (درجة دقة البيانات). |
| [getGPSDestBearing()](#getGPSDestBearing--) | يحصل أو يضبط اتجاه GPS إلى نقطة الوجهة. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط اتجاه GPS إلى نقطة الوجهة. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | يحصل أو يضبط مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | يحصل أو يضبط مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| [getGPSDestDistance()](#getGPSDestDistance--) | يحصل أو يضبط مسافة GPS إلى نقطة الوجهة. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط مسافة GPS إلى نقطة الوجهة. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | يحصل أو يضبط وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | يحصل أو يضبط وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | يحصل أو يضبط خط عرض GPS لنقطة الوجهة. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط خط عرض GPS لنقطة الوجهة. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | يحصل أو يضبط خط طول GPS لنقطة الوجهة. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط خط طول GPS لنقطة الوجهة. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا. |
| [getGPSDifferential()](#getGPSDifferential--) | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان تم تطبيق التصحيح التفاضلي على جهاز استقبال GPS. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان تم تطبيق التصحيح التفاضلي على جهاز استقبال GPS. |
| [getGPSImgDirection()](#getGPSImgDirection--) | يحصل أو يضبط اتجاه GPS للصورة عند التقاطها. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط اتجاه GPS للصورة عند التقاطها. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | يحصل أو يضبط مرجع GPS لتحديد اتجاه الصورة عند التقاطها. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | يحصل أو يضبط مرجع GPS لتحديد اتجاه الصورة عند التقاطها. |
| [getGPSDateStamp()](#getGPSDateStamp--) | يحصل أو يضبط سلسلة الأحرف GPS التي تسجل معلومات التاريخ والوقت بالنسبة لتوقيت UTC (التوقيت العالمي المنسق). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | يحصل أو يضبط سلسلة الأحرف GPS التي تسجل معلومات التاريخ والوقت بالنسبة لتوقيت UTC (التوقيت العالمي المنسق). |
| [getGPSLatitude()](#getGPSLatitude--) | يحصل أو يضبط خط عرض GPS. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط خط عرض GPS. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | يحصل أو يضبط ما إذا كان خط عرض GPS شماليًا أم جنوبيًا. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | يحصل أو يضبط ما إذا كان خط عرض GPS شماليًا أم جنوبيًا. |
| [getGPSLongitude()](#getGPSLongitude--) | يحصل أو يضبط خط طول GPS. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط خط طول GPS. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | يحصل أو يضبط ما إذا كان خط طول GPS شرقًا أم غربًا. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | يحصل أو يضبط ما إذا كان خط طول GPS شرقًا أم غربًا. |
| [getGPSMapDatum()](#getGPSMapDatum--) | يحصل أو يضبط بيانات المسح الجيوديسي لنظام GPS المستخدمة بواسطة جهاز الاستقبال. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | يحصل أو يضبط بيانات المسح الجيوديسي لنظام GPS المستخدمة بواسطة جهاز الاستقبال. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | يحصل أو يضبط وضع قياس GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | يحصل أو يضبط وضع قياس GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | يحصل أو يضبط سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | يحصل أو يضبط سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| [getGPSSatellites()](#getGPSSatellites--) | يحصل أو يضبط أقمار GPS المستخدمة للقياسات. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | يحصل أو يضبط أقمار GPS المستخدمة للقياسات. |
| [getGPSSpeed()](#getGPSSpeed--) | يحصل أو يضبط سرعة حركة جهاز استقبال GPS. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط سرعة حركة جهاز استقبال GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة جهاز استقبال GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة جهاز استقبال GPS. |
| [getGPSStatus()](#getGPSStatus--) | يحصل أو يضبط حالة جهاز استقبال GPS عند تسجيل الصورة. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | يحصل أو يضبط حالة جهاز استقبال GPS عند تسجيل الصورة. |
| [getGPSTimestamp()](#getGPSTimestamp--) | يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق). |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق). |
| [getGPSTrack()](#getGPSTrack--) | يحصل أو يضبط اتجاه حركة مستقبل GPS. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | يحصل أو يضبط اتجاه حركة مستقبل GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | يحصل أو يضبط المرجع لتحديد اتجاه حركة مستقبل GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | يحصل أو يضبط المرجع لتحديد اتجاه حركة مستقبل GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | يحصل أو يضبط معرف نسخة GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | يحصل أو يضبط معرف نسخة GPS. |
| [getGainControl()](#getGainControl--) | يحصل أو يضبط درجة تعديل الكسب الكلي للصورة. |
| [setGainControl(int value)](#setGainControl-int-) | يحصل أو يضبط درجة تعديل الكسب الكلي للصورة. |
| [getGamma()](#getGamma--) | يحصل أو يضبط قيمة جاما. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط قيمة جاما. |
| [getISOSpeed()](#getISOSpeed--) | يحصل أو يضبط سرعة ISO. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | يحصل أو يضبط سرعة ISO. |
| [getISOSpeedValue()](#getISOSpeedValue--) | يحصل على قيمة سرعة ISO. |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | يضبط قيمة سرعة ISO. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | يحصل أو يضبط قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | يحصل أو يضبط قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | يحصل أو يضبط قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | يحصل أو يضبط قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | يحصل أو يضبط الحساسية الفوتوغرافية. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | يحصل أو يضبط الحساسية الفوتوغرافية. |
| [getImageUniqueID()](#getImageUniqueID--) | يحصل أو يضبط المعرف الفريد للصورة. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | يحصل أو يضبط المعرف الفريد للصورة. |
| [getLensMake()](#getLensMake--) | يحصل أو يضبط صانع العدسة. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | يحصل أو يضبط صانع العدسة. |
| [getLensModel()](#getLensModel--) | يحصل أو يضبط طراز العدسة. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | يحصل أو يضبط طراز العدسة. |
| [getLensSerialNumber()](#getLensSerialNumber--) | يحصل أو يضبط الرقم التسلسلي للعدسة. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | يحصل أو يضبط الرقم التسلسلي للعدسة. |
| [getLensSpecification()](#getLensSpecification--) | يحصل أو يضبط مواصفات العدسة. |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط مواصفات العدسة. |
| [getLightSource()](#getLightSource--) | يحصل أو يضبط مصدر الضوء. |
| [setLightSource(int value)](#setLightSource-int-) | يحصل أو يضبط مصدر الضوء. |
| [getMakerNoteData()](#getMakerNoteData--) | يحصل على بيانات ملاحظة الصانع. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | يحصل أو يضبط البيانات الخام لملاحظة الصانع. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | يحصل أو يضبط البيانات الخام لملاحظة الصانع. |
| [getMakerNotes()](#getMakerNotes--) | يحصل على ملاحظات الصانع. |
| [getMaxApertureValue()](#getMaxApertureValue--) | يحصل أو يضبط قيمة الفتحة القصوى. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط قيمة الفتحة القصوى. |
| [getMeteringMode()](#getMeteringMode--) | يحصل أو يضبط وضع القياس. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | يحصل أو يضبط وضع القياس. |
| [getOECF()](#getOECF--) | يحصل أو يضبط وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524. |
| [setOECF(byte[] value)](#setOECF-byte---) | يحصل أو يضبط وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524. |
| [getOrientation()](#getOrientation--) | يحصل على الاتجاه [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [setOrientation(int value)](#setOrientation-int-) | يضبط الاتجاه [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [getPixelXDimension()](#getPixelXDimension--) | الحصول أو تعيين بُعد البكسل x. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | الحصول أو تعيين بُعد البكسل x. |
| [getPixelYDimension()](#getPixelYDimension--) | الحصول أو تعيين بُعد البكسل y. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | الحصول أو تعيين بُعد البكسل y. |
| [getProperties()](#getProperties--) | الحصول أو تعيين جميع علامات EXIF (بما في ذلك العلامات الشائعة وعلامات GPS). |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | الحصول أو تعيين جميع علامات EXIF (بما في ذلك العلامات الشائعة وعلامات GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | الحصول أو تعيين مؤشر التعرض الموصى به. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | الحصول أو تعيين مؤشر التعرض الموصى به. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | الحصول أو تعيين ملف الصوت المرتبط. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | الحصول أو تعيين ملف الصوت المرتبط. |
| [getSaturation()](#getSaturation--) | الحصول أو تعيين التشبع. |
| [setSaturation(int value)](#setSaturation-int-) | الحصول أو تعيين التشبع. |
| [getSceneCaptureType()](#getSceneCaptureType--) | الحصول أو تعيين نوع التقاط المشهد. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | الحصول أو تعيين نوع التقاط المشهد. |
| [getSceneType()](#getSceneType--) | الحصول أو تعيين نوع المشهد. |
| [setSceneType(byte value)](#setSceneType-byte-) | الحصول أو تعيين نوع المشهد. |
| [getSensingMethod()](#getSensingMethod--) | الحصول أو تعيين طريقة الاستشعار. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | الحصول أو تعيين طريقة الاستشعار. |
| [getSensitivityType()](#getSensitivityType--) | الحصول أو تعيين نوع الحساسية. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | الحصول أو تعيين نوع الحساسية. |
| [getSharpness()](#getSharpness--) | الحصول أو تعيين الحدة. |
| [setSharpness(int value)](#setSharpness-int-) | الحصول أو تعيين الحدة. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | الحصول أو تعيين قيمة سرعة الغالق. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | الحصول أو تعيين قيمة سرعة الغالق. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | الحصول أو تعيين استجابة التردد المكاني. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | الحصول أو تعيين استجابة التردد المكاني. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | الحصول أو تعيين الحساسية الطيفية. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | الحصول أو تعيين الحساسية الطيفية. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | الحصول على حساسية الإخراج القياسية |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | تعيين حساسية الإخراج القياسية |
| [getSubjectArea()](#getSubjectArea--) | الحصول أو تعيين منطقة الموضوع. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | الحصول أو تعيين منطقة الموضوع. |
| [getSubjectDistance()](#getSubjectDistance--) | الحصول أو تعيين مسافة الموضوع. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | الحصول أو تعيين مسافة الموضوع. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | الحصول أو تعيين نطاق مسافة الموضوع. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | الحصول أو تعيين نطاق مسافة الموضوع. |
| [getSubjectLocation()](#getSubjectLocation--) | الحصول أو تعيين موقع الموضوع. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | الحصول أو تعيين موقع الموضوع. |
| [getSubsecTime()](#getSubsecTime--) | الحصول أو تعيين أجزاء الثواني لعلامة DateTime. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | الحصول أو تعيين أجزاء الثواني لعلامة DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | الحصول أو تعيين أجزاء الثواني لعلامة DateTimeDigitized. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | الحصول أو تعيين أجزاء الثواني لعلامة DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | الحصول أو تعيين أجزاء الثواني لعلامة DateTimeOriginal. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | الحصول أو تعيين أجزاء الثواني لعلامة DateTimeOriginal. |
| [getUserComment()](#getUserComment--) | الحصول أو تعيين تعليق المستخدم. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | الحصول أو تعيين تعليق المستخدم. |
| [getWhiteBalance()](#getWhiteBalance--) | الحصول أو تعيين توازن اللون الأبيض. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | الحصول أو تعيين توازن اللون الأبيض. |
| [getWhitePoint()](#getWhitePoint--) | يحصل أو يعيّن تشبع نقطة اللون الأبيض في الصورة. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يعيّن تشبع نقطة اللون الأبيض في الصورة. |
| [getCommonTags()](#getCommonTags--) | يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. |
| [getExifTags()](#getExifTags--) | يحصل أو يعيّن العلامات التي تنتمي إلى قسم EXIF فقط. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يحصل أو يعيّن العلامات التي تنتمي إلى قسم EXIF فقط. |
| [getGPSTags()](#getGPSTags--) | يحصل أو يعيّن العلامات التي تنتمي إلى قسم GPS فقط. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يحصل أو يعيّن العلامات التي تنتمي إلى قسم GPS فقط. |
| [getThumbnail()](#getThumbnail--) | يحصل على صورة المصغرة. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | يعيّن صورة المصغرة. |
| [getXResolutionInt()](#getXResolutionInt--) | يحصل على دقة x. |
| [setXResolution(int value)](#setXResolution-int-) | يعيّن دقة x. |
| [getYResolutionInt()](#getYResolutionInt--) | يحصل على دقة y. |
| [setYResolution(int value)](#setYResolution-int-) | يعيّن دقة y. |
| [removeTag(int tagId)](#removeTag-int-) | إزالة العلامة من الحاوية |
| [getTagValue(int key)](#getTagValue-int-) | يحصل على قيمة العلامة. |

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


ينشئ مثيلاً جديدًا للفئة `ExifData`.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


ينشئ مثيلاً جديدًا للفئة `ExifData` مع بيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | مصفوفة من علامات EXIF مع العلامات المشتركة وعلامات GPS. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


ينشئ مثيلاً جديدًا للفئة `ExifData` مع بيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | العلامات المشتركة. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | علامات EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | علامات GPS. |

### ExifData(ExifData exifdata) {#ExifData-com.aspose.imaging.exif.ExifData-}
```
public ExifData(ExifData exifdata)
```


ينشئ مثيلاً جديدًا للفئة [ExifData](../../com.aspose.imaging.exif/exifdata) مع بيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | مصفوفة من علامات EXIF مع العلامات المشتركة وعلامات GPS. |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


ينشئ مثيلاً جديدًا للفئة [ExifData](../../com.aspose.imaging.exif/exifdata).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| binaryData | byte[] | البيانات الثنائية. |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان تدفق بيانات EXIF المُنشأ من big endian.

القيمة: `true` إذا كان تدفق بيانات EXIF المُنشأ منه ذو ترتيب بايت كبير؛ وإلا `false`.

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان تدفق بيانات EXIF المُنشأ من big endian.

القيمة: `true` إذا كان تدفق بيانات EXIF المُنشأ منه ذو ترتيب بايت كبير؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getMake() {#getMake--}
```
public final String getMake()
```


يحصل على الشركة المصنعة لمعدات التسجيل.

القيمة: الشركة المصنعة لمعدات التسجيل.

**Returns:**
java.lang.String - الشركة المصنعة لمعدات التسجيل.
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


يعيّن الشركة المصنعة لمعدات التسجيل.

القيمة: الشركة المصنعة لمعدات التسجيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | الشركة المصنعة لمعدات التسجيل. |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


يحصل أو يعيّن قيمة الفتحة.

القيمة: قيمة الفتحة.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


يحصل أو يعيّن قيمة الفتحة.

القيمة: قيمة الفتحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


يحصل أو يعيّن رقم تسلسل جسم الكاميرا.

القيمة: الرقم التسلسلي للجسم.

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


يحصل أو يعيّن رقم تسلسل جسم الكاميرا.

القيمة: الرقم التسلسلي للجسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


يحصل أو يعيّن قيمة السطوع.

القيمة: قيمة السطوع.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


يحصل أو يعيّن قيمة السطوع.

القيمة: قيمة السطوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


يحصل أو يعيّن نمط CFA.

القيمة: نمط CFA.

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


يحصل أو يعيّن نمط CFA.

القيمة: نمط CFA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


يحصل أو يعيّن اسم مالك الكاميرا

القيمة: اسم مالك الكاميرا.

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


يحصل أو يعيّن اسم مالك الكاميرا

القيمة: اسم مالك الكاميرا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


يحصل أو يعيّن مساحة اللون.

القيمة: مساحة اللون.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


يحصل أو يعيّن مساحة اللون.

القيمة: مساحة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


يحصل أو يعيّن تكوين المكونات.

القيمة: تكوين المكونات.

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


يحصل أو يعيّن تكوين المكونات.

القيمة: تكوين المكونات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


يحصل أو يعيّن عدد البتات المضغوطة لكل بكسل.

القيمة: عدد البتات المضغوطة لكل بكسل.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


يحصل أو يعيّن عدد البتات المضغوطة لكل بكسل.

القيمة: عدد البتات المضغوطة لكل بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getContrast() {#getContrast--}
```
public int getContrast()
```


يحصل أو يضبط التباين.

القيمة: التباين.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


يحصل أو يضبط التباين.

القيمة: التباين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


يحصل أو يضبط العرض المخصص.

القيمة: العرض المخصص.

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


يحصل أو يضبط العرض المخصص.

القيمة: العرض المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


يحصل أو يضبط تاريخ ووقت الرقمنة.

القيمة: تاريخ ووقت الرقمنة.

**Returns:**
java.lang.String
### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


يحصل أو يضبط تاريخ ووقت الرقمنة.

القيمة: تاريخ ووقت الرقمنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


يحصل أو يضبط تاريخ ووقت الأصل.

القيمة: تاريخ ووقت الأصل.

**Returns:**
java.lang.String
### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


يحصل أو يضبط تاريخ ووقت الأصل.

القيمة: تاريخ ووقت الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


يحصل أو يضبط وصف إعدادات الجهاز

القيمة: وصف إعداد الجهاز.

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


يحصل أو يضبط وصف إعدادات الجهاز

القيمة: وصف إعداد الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


يحصل أو يضبط نسبة التكبير الرقمي.

القيمة: نسبة التكبير الرقمي.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


يحصل أو يضبط نسبة التكبير الرقمي.

القيمة: نسبة التكبير الرقمي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


يحصل أو يضبط نسخة EXIF.

القيمة: نسخة EXIF.

**Returns:**
byte[]
### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


يحصل أو يضبط نسخة EXIF.

القيمة: نسخة EXIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


يحصل أو يضبط قيمة انحياز التعرض.

القيمة: قيمة انحياز التعرض.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


يحصل أو يضبط قيمة انحياز التعرض.

القيمة: قيمة انحياز التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


يحصل أو يضبط مؤشر التعرض.

القيمة: فهرس التعرض.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


يحصل أو يضبط مؤشر التعرض.

القيمة: فهرس التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


يحصل أو يضبط وضع التعرض.

القيمة: وضع التعرض.

**Returns:**
int
### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


يحصل أو يضبط وضع التعرض.

القيمة: وضع التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


يحصل أو يضبط برنامج التعرض.

القيمة: برنامج التعرض.

**Returns:**
int
### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


يحصل أو يضبط برنامج التعرض.

القيمة: برنامج التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


يحصل أو يضبط زمن التعرض.

القيمة: زمن التعرض.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


يحصل أو يضبط زمن التعرض.

القيمة: زمن التعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


يحصل أو يضبط رقم F.

القيمة: رقم F.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFNumber(TiffRational value) {#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


يحصل أو يضبط رقم F.

القيمة: رقم F.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


يحصل أو يضبط نوع مصدر الملف.

القيمة: نوع مصدر الملف.

**Returns:**
byte
### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


يحصل أو يضبط نوع مصدر الملف.

القيمة: نوع مصدر الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getFlash() {#getFlash--}
```
public int getFlash()
```


يحصل أو يضبط الفلاش.

القيمة: الفلاش.

**Returns:**
int
### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


يحصل أو يضبط الفلاش.

القيمة: الفلاش.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


يحصل أو يضبط طاقة الفلاش.

القيمة: طاقة الفلاش.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


يحصل أو يضبط طاقة الفلاش.

القيمة: طاقة الفلاش.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


يحصل أو يضبط نسخة فلاش pix.

القيمة: نسخة فلاش pix.

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


يحصل أو يضبط نسخة فلاش pix.

القيمة: نسخة فلاش pix.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


يحصل أو يضبط البعد البؤري.

القيمة: طول البؤري.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


يحصل أو يضبط البعد البؤري.

القيمة: طول البؤري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


يحصل أو يضبط البعد البؤري في فيلم 35 مم.

القيمة: البعد البؤري في فيلم 35 مم.

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


يحصل أو يضبط البعد البؤري في فيلم 35 مم.

القيمة: البعد البؤري في فيلم 35 مم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


يحصل أو يضبط وحدة دقة المستوى البؤري.

القيمة: وحدة دقة المستوى البؤري.

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


يحصل أو يضبط وحدة دقة المستوى البؤري.

القيمة: وحدة دقة المستوى البؤري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


يحصل أو يضبط دقة المستوى البؤري X.

القيمة: دقة المستوى البؤري x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


يحصل أو يضبط دقة المستوى البؤري X.

القيمة: دقة المستوى البؤري x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


يحصل أو يضبط دقة المستوى البؤري Y.

القيمة: دقة المستوى البؤري y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


يحصل أو يضبط دقة المستوى البؤري Y.

القيمة: دقة المستوى البؤري y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


يحصل أو يضبط ارتفاع GPS.

القيمة: ارتفاع GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


يحصل أو يضبط ارتفاع GPS.

القيمة: ارتفاع GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


يحصل أو يضبط ارتفاع GPS المستخدم كارتفاع مرجعي.

القيمة: ارتفاع GPS المستخدم كارتفاع مرجعي.

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


يحصل أو يضبط ارتفاع GPS المستخدم كارتفاع مرجعي.

القيمة: ارتفاع GPS المستخدم كارتفاع مرجعي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


يحصل أو يضبط معلومات منطقة GPS.

القيمة: معلومات منطقة GPS.

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


يحصل أو يضبط معلومات منطقة GPS.

القيمة: معلومات منطقة GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


يحصل أو يضبط قيمة DOP لنظام GPS (درجة دقة البيانات).

القيمة: DOP GPS (درجة دقة البيانات).

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


يحصل أو يضبط قيمة DOP لنظام GPS (درجة دقة البيانات).

القيمة: DOP GPS (درجة دقة البيانات).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


يحصل أو يضبط اتجاه GPS إلى نقطة الوجهة.

القيمة: اتجاه GPS إلى نقطة الوجهة.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


يحصل أو يضبط اتجاه GPS إلى نقطة الوجهة.

القيمة: اتجاه GPS إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


يحصل أو يضبط مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

القيمة: مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


يحصل أو يضبط مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

القيمة: مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


يحصل أو يضبط مسافة GPS إلى نقطة الوجهة.

القيمة: مسافة GPS إلى نقطة الوجهة.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


يحصل أو يضبط مسافة GPS إلى نقطة الوجهة.

القيمة: مسافة GPS إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


يحصل أو يضبط وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

القيمة: وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


يحصل أو يضبط وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

القيمة: وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


يحصل أو يضبط خط عرض GPS لنقطة الوجهة.

القيمة: خط عرض GPS لنقطة الوجهة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


يحصل أو يضبط خط عرض GPS لنقطة الوجهة.

القيمة: خط عرض GPS لنقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


يحصل أو يضبط خط طول GPS لنقطة الوجهة.

القيمة: خط طول GPS لنقطة الوجهة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


يحصل أو يضبط خط طول GPS لنقطة الوجهة.

القيمة: خط طول GPS لنقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان تم تطبيق التصحيح التفاضلي على جهاز استقبال GPS.

القيمة: قيمة GPS التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على جهاز استقبال GPS.

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


يحصل أو يضبط قيمة GPS التي تشير إلى ما إذا كان تم تطبيق التصحيح التفاضلي على جهاز استقبال GPS.

القيمة: قيمة GPS التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على جهاز استقبال GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


يحصل أو يضبط اتجاه GPS للصورة عند التقاطها.

القيمة: اتجاه GPS للصورة عند التقاطها.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


يحصل أو يضبط اتجاه GPS للصورة عند التقاطها.

القيمة: اتجاه GPS للصورة عند التقاطها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


يحصل أو يضبط مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

القيمة: مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


يحصل أو يضبط مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

القيمة: مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


يحصل أو يضبط سلسلة الأحرف GPS التي تسجل معلومات التاريخ والوقت بالنسبة لتوقيت UTC (التوقيت العالمي المنسق).

القيمة: سلسلة الأحرف GPS التي تسجل معلومات التاريخ والوقت بالنسبة إلى UTC (التوقيت العالمي المنسق).

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


يحصل أو يضبط سلسلة الأحرف GPS التي تسجل معلومات التاريخ والوقت بالنسبة لتوقيت UTC (التوقيت العالمي المنسق).

القيمة: سلسلة الأحرف GPS التي تسجل معلومات التاريخ والوقت بالنسبة إلى UTC (التوقيت العالمي المنسق).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


يحصل أو يضبط خط عرض GPS.

القيمة: خط عرض GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


يحصل أو يضبط خط عرض GPS.

القيمة: خط عرض GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


يحصل أو يضبط ما إذا كان خط عرض GPS شماليًا أم جنوبيًا.

القيمة: خط عرض GPS هو شمالي أو جنوبي.

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


يحصل أو يضبط ما إذا كان خط عرض GPS شماليًا أم جنوبيًا.

القيمة: خط عرض GPS هو شمالي أو جنوبي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


يحصل أو يضبط خط طول GPS.

القيمة: خط طول GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


يحصل أو يضبط خط طول GPS.

القيمة: خط طول GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


يحصل أو يضبط ما إذا كان خط طول GPS شرقًا أم غربًا.

القيمة: خط طول GPS هو شرق أو غرب.

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


يحصل أو يضبط ما إذا كان خط طول GPS شرقًا أم غربًا.

القيمة: خط طول GPS هو شرق أو غرب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


يحصل أو يضبط بيانات المسح الجيوديسي لنظام GPS المستخدمة بواسطة جهاز الاستقبال.

القيمة: بيانات المسح الجيوديسي GPS المستخدمة من قبل جهاز استقبال GPS.

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


يحصل أو يضبط بيانات المسح الجيوديسي لنظام GPS المستخدمة بواسطة جهاز الاستقبال.

القيمة: بيانات المسح الجيوديسي GPS المستخدمة من قبل جهاز استقبال GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


يحصل أو يضبط وضع قياس GPS.

القيمة: وضع قياس GPS.

**Returns:**
java.lang.String
### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


يحصل أو يضبط وضع قياس GPS.

القيمة: وضع قياس GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


يحصل أو يضبط سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

القيمة: سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


يحصل أو يضبط سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

القيمة: سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


يحصل أو يضبط أقمار GPS المستخدمة للقياسات.

القيمة: الأقمار الصناعية لنظام GPS المستخدمة للقياسات.

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


يحصل أو يضبط أقمار GPS المستخدمة للقياسات.

القيمة: الأقمار الصناعية لنظام GPS المستخدمة للقياسات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


يحصل أو يضبط سرعة حركة جهاز استقبال GPS.

القيمة: سرعة حركة مستقبل GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


يحصل أو يضبط سرعة حركة جهاز استقبال GPS.

القيمة: سرعة حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة جهاز استقبال GPS.

القيمة: الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS.

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة جهاز استقبال GPS.

القيمة: الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


يحصل أو يضبط حالة جهاز استقبال GPS عند تسجيل الصورة.

القيمة: حالة مستقبل GPS عند تسجيل الصورة.

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


يحصل أو يضبط حالة جهاز استقبال GPS عند تسجيل الصورة.

القيمة: حالة مستقبل GPS عند تسجيل الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق).

القيمة: وقت GPS كـ UTC (التوقيت العالمي المنسق).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق).

القيمة: وقت GPS كـ UTC (التوقيت العالمي المنسق).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


يحصل أو يضبط اتجاه حركة مستقبل GPS.

القيمة: اتجاه حركة مستقبل GPS.

**Returns:**
java.lang.String
### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


يحصل أو يضبط اتجاه حركة مستقبل GPS.

القيمة: اتجاه حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


يحصل أو يضبط المرجع لتحديد اتجاه حركة مستقبل GPS.

القيمة: المرجع لتحديد اتجاه حركة مستقبل GPS.

**Returns:**
java.lang.String
### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


يحصل أو يضبط المرجع لتحديد اتجاه حركة مستقبل GPS.

القيمة: المرجع لتحديد اتجاه حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


يحصل أو يضبط معرف نسخة GPS.

القيمة: معرف إصدار GPS.

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


يحصل أو يضبط معرف نسخة GPS.

القيمة: معرف إصدار GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


يحصل أو يضبط درجة تعديل الكسب الكلي للصورة.

القيمة: درجة تعديل الكسب الكلي للصورة.

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


يحصل أو يضبط درجة تعديل الكسب الكلي للصورة.

القيمة: درجة تعديل الكسب الكلي للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


يحصل أو يضبط قيمة جاما.

القيمة: قيمة الجاما.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


يحصل أو يضبط قيمة جاما.

القيمة: قيمة الجاما.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


يحصل أو يضبط سرعة ISO.

القيمة: سرعة ISO.

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


يحصل أو يضبط سرعة ISO.

القيمة: سرعة ISO.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


يحصل على قيمة سرعة ISO.

القيمة: قيمة سرعة ISO.

**Returns:**
طويل - قيمة سرعة ISO.
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


يضبط قيمة سرعة ISO.

القيمة: قيمة سرعة ISO.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long | قيمة سرعة ISO. |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


يحصل أو يضبط قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال معرفة في ISO 12232.

يجب عدم تسجيل هذه العلامة بدون ISOSpeed و ISOSpeedLatitudeZZZ.

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


يحصل أو يضبط قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال معرفة في ISO 12232.

يجب عدم تسجيل هذه العلامة بدون ISOSpeed و ISOSpeedLatitudeZZZ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


يحصل أو يضبط قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال معرفة في ISO 12232.

يجب عدم تسجيل هذه العلامة بدون ISOSpeed و ISOSpeedLatitudeYYY.

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


يحصل أو يضبط قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال معرفة في ISO 12232.

يجب عدم تسجيل هذه العلامة بدون ISOSpeed و ISOSpeedLatitudeYYY.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


يحصل أو يضبط الحساسية الفوتوغرافية.

القيمة: الحساسية الفوتوغرافية.

**Returns:**
long
### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


يحصل أو يضبط الحساسية الفوتوغرافية.

القيمة: الحساسية الفوتوغرافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


يحصل أو يضبط المعرف الفريد للصورة.

القيمة: المعرف الفريد للصورة.

**Returns:**
java.lang.String
### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


يحصل أو يضبط المعرف الفريد للصورة.

القيمة: المعرف الفريد للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


يحصل أو يضبط صانع العدسة.

القيمة: صانع العدسة.

**Returns:**
java.lang.String
### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


يحصل أو يضبط صانع العدسة.

القيمة: صانع العدسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


يحصل أو يضبط طراز العدسة.

القيمة: طراز العدسة.

**Returns:**
java.lang.String
### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


يحصل أو يضبط طراز العدسة.

القيمة: طراز العدسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


يحصل أو يضبط الرقم التسلسلي للعدسة.

القيمة: الرقم التسلسلي للعدسة.

**Returns:**
java.lang.String
### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


يحصل أو يضبط الرقم التسلسلي للعدسة.

القيمة: الرقم التسلسلي للعدسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


يحصل أو يضبط مواصفات العدسة.

القيمة: مواصفات العدسة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


يحصل أو يضبط مواصفات العدسة.

القيمة: مواصفات العدسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


يحصل أو يضبط مصدر الضوء.

القيمة: مصدر الضوء.

**Returns:**
int
### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


يحصل أو يضبط مصدر الضوء.

القيمة: مصدر الضوء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


يحصل على بيانات ملاحظة الصانع.

القيمة: بيانات ملاحظة الصانع.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


يحصل أو يضبط البيانات الخام لملاحظة الصانع.

القيمة: البيانات الخام لملاحظة الصانع.

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


يحصل أو يضبط البيانات الخام لملاحظة الصانع.

القيمة: البيانات الخام لملاحظة الصانع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


يحصل على ملاحظات الصانع.

القيمة: ملاحظات الصانع.

**Returns:**
com.aspose.imaging.exif.MakerNote[] - ملاحظات الصانع.

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


يحصل أو يضبط قيمة الفتحة القصوى.

القيمة: قيمة الفتحة القصوى.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


يحصل أو يضبط قيمة الفتحة القصوى.

القيمة: قيمة الفتحة القصوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


يحصل أو يضبط وضع القياس.

القيمة: وضع القياس.

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


يحصل أو يضبط وضع القياس.

القيمة: وضع القياس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


يحصل أو يضبط وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

القيمة: وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


يحصل أو يضبط وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

القيمة: وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


يحصل على الاتجاه [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

القيمة: الاتجاه.

**Returns:**
int - الاتجاه.
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


يضبط الاتجاه [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

القيمة: الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الاتجاه. |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


الحصول أو تعيين بُعد البكسل x.

القيمة: البُعد السيني للبكسل.

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


الحصول أو تعيين بُعد البكسل x.

القيمة: البُعد السيني للبكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


الحصول أو تعيين بُعد البكسل y.

القيمة: البُعد الصادي للبكسل.

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


الحصول أو تعيين بُعد البكسل y.

القيمة: البُعد الصادي للبكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


الحصول أو تعيين جميع علامات EXIF (بما في ذلك العلامات الشائعة وعلامات GPS).

القيمة: وسوم EXIF (بما في ذلك الوسوم العامة ووسوم GPS).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


الحصول أو تعيين جميع علامات EXIF (بما في ذلك العلامات الشائعة وعلامات GPS).

القيمة: وسوم EXIF (بما في ذلك الوسوم العامة ووسوم GPS).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


الحصول أو تعيين مؤشر التعرض الموصى به.

القيمة: مؤشر التعرض الموصى به.

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


الحصول أو تعيين مؤشر التعرض الموصى به.

القيمة: مؤشر التعرض الموصى به.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


الحصول أو تعيين ملف الصوت المرتبط.

القيمة: ملف الصوت المرتبط.

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


الحصول أو تعيين ملف الصوت المرتبط.

القيمة: ملف الصوت المرتبط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


الحصول أو تعيين التشبع.

القيمة: التشبع.

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


الحصول أو تعيين التشبع.

القيمة: التشبع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


الحصول أو تعيين نوع التقاط المشهد.

القيمة: نوع التقاط المشهد.

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


الحصول أو تعيين نوع التقاط المشهد.

القيمة: نوع التقاط المشهد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


الحصول أو تعيين نوع المشهد.

القيمة: نوع المشهد.

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


الحصول أو تعيين نوع المشهد.

القيمة: نوع المشهد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


الحصول أو تعيين طريقة الاستشعار.

القيمة: طريقة الاستشعار.

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


الحصول أو تعيين طريقة الاستشعار.

القيمة: طريقة الاستشعار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


الحصول أو تعيين نوع الحساسية.

القيمة: نوع الحساسية.

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


الحصول أو تعيين نوع الحساسية.

القيمة: نوع الحساسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


الحصول أو تعيين الحدة.

القيمة: الحدة.

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


الحصول أو تعيين الحدة.

القيمة: الحدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


الحصول أو تعيين قيمة سرعة الغالق.

القيمة: قيمة سرعة الغالق.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


الحصول أو تعيين قيمة سرعة الغالق.

القيمة: قيمة سرعة الغالق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


الحصول أو تعيين استجابة التردد المكاني.

القيمة: استجابة التردد المكاني.

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


الحصول أو تعيين استجابة التردد المكاني.

القيمة: استجابة التردد المكاني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


الحصول أو تعيين الحساسية الطيفية.

القيمة: الحساسية الطيفية.

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


الحصول أو تعيين الحساسية الطيفية.

القيمة: الحساسية الطيفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


الحصول على حساسية الإخراج القياسية

القيمة: حساسية الإخراج القياسية.

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


تعيين حساسية الإخراج القياسية

القيمة: حساسية الإخراج القياسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


الحصول أو تعيين منطقة الموضوع.

القيمة: مساحة الموضوع.

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


الحصول أو تعيين منطقة الموضوع.

القيمة: مساحة الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


الحصول أو تعيين مسافة الموضوع.

القيمة: مسافة الموضوع.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


الحصول أو تعيين مسافة الموضوع.

القيمة: مسافة الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


الحصول أو تعيين نطاق مسافة الموضوع.

القيمة: نطاق مسافة الموضوع.

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


الحصول أو تعيين نطاق مسافة الموضوع.

القيمة: نطاق مسافة الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


الحصول أو تعيين موقع الموضوع.

القيمة: موقع الموضوع.

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


الحصول أو تعيين موقع الموضوع.

القيمة: موقع الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


الحصول أو تعيين أجزاء الثواني لعلامة DateTime.

القيمة: أجزاء الثواني لعلامة DateTime.

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


الحصول أو تعيين أجزاء الثواني لعلامة DateTime.

القيمة: أجزاء الثواني لعلامة DateTime.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


الحصول أو تعيين أجزاء الثواني لعلامة DateTimeDigitized.

القيمة: أجزاء الثواني لعلامة DateTimeDigitized.

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


الحصول أو تعيين أجزاء الثواني لعلامة DateTimeDigitized.

القيمة: أجزاء الثواني لعلامة DateTimeDigitized.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


الحصول أو تعيين أجزاء الثواني لعلامة DateTimeOriginal.

القيمة: أجزاء الثواني لعلامة DateTimeOriginal.

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


الحصول أو تعيين أجزاء الثواني لعلامة DateTimeOriginal.

القيمة: أجزاء الثواني لعلامة DateTimeOriginal.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


الحصول أو تعيين تعليق المستخدم.

القيمة: تعليق المستخدم.

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


الحصول أو تعيين تعليق المستخدم.

القيمة: تعليق المستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


الحصول أو تعيين توازن اللون الأبيض.

القيمة: توازن اللون الأبيض.

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


الحصول أو تعيين توازن اللون الأبيض.

القيمة: توازن اللون الأبيض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


يحصل أو يعيّن تشبع نقطة اللون الأبيض في الصورة.

القيمة: تشبع اللون لنقطة اللون الأبيض في الصورة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


يحصل أو يعيّن تشبع نقطة اللون الأبيض في الصورة.

القيمة: تشبع اللون لنقطة اللون الأبيض في الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. ينطبق هذا فقط على صور jpeg، وفي تنسيق tiff يتم استخدام tiffOptions بدلاً من ذلك.

القيمة: علامات القسم المشترك.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. ينطبق هذا فقط على صور jpeg، وفي تنسيق tiff يتم استخدام tiffOptions بدلاً من ذلك.

القيمة: علامات القسم المشترك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


يحصل أو يعيّن العلامات التي تنتمي إلى قسم EXIF فقط.

القيمة: علامات قسم EXIF.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


يحصل أو يعيّن العلامات التي تنتمي إلى قسم EXIF فقط.

القيمة: علامات قسم EXIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


يحصل أو يعيّن العلامات التي تنتمي إلى قسم GPS فقط.

القيمة: علامات GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


يحصل أو يعيّن العلامات التي تنتمي إلى قسم GPS فقط.

القيمة: علامات GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getThumbnail() {#getThumbnail--}
```
public final RasterImage getThumbnail()
```


يحصل على صورة المصغرة.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the thumbnail image.
### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.imaging.RasterImage-}
```
public final void setThumbnail(RasterImage value)
```


يعيّن صورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة المصغرة. |

### getXResolutionInt() {#getXResolutionInt--}
```
public final int getXResolutionInt()
```


يحصل على دقة x.

القيمة: دقة x.

**Returns:**
int - دقة x.
### setXResolution(int value) {#setXResolution-int-}
```
public final void setXResolution(int value)
```


يعيّن دقة x.

القيمة: دقة x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | دقة x. |

### getYResolutionInt() {#getYResolutionInt--}
```
public final int getYResolutionInt()
```


يحصل على دقة y.

القيمة: دقة y.

**Returns:**
int - دقة y.
### setYResolution(int value) {#setYResolution-int-}
```
public final void setYResolution(int value)
```


يعيّن دقة y.

القيمة: دقة y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | دقة y. |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


إزالة العلامة من الحاوية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة لإزالتها. |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


يحصل على قيمة العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| key | int | مفتاح العلامة [ExifProperties](../../com.aspose.imaging.exif/exifproperties). |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
