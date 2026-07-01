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
| [ExifData()](#ExifData--) | ينشئ مثيلًا جديدًا من الفئة `ExifData`. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | ينشئ مثيلًا جديدًا من الفئة `ExifData` باستخدام بيانات من مصفوفة. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | ينشئ مثيلًا جديدًا من الفئة `ExifData` باستخدام بيانات من مصفوفة. |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | ينشئ مثيلًا جديدًا من الفئة [ExifData](../../com.aspose.imaging.exif/exifdata) باستخدام بيانات من مصفوفة. |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | ينشئ مثيلًا جديدًا من الفئة [ExifData](../../com.aspose.imaging.exif/exifdata). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت بيانات EXIF الخاصة بالتدفق التي تم إنشاؤها من بتنسيق big endian. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت بيانات EXIF الخاصة بالتدفق التي تم إنشاؤها من بتنسيق big endian. |
| [getMake()](#getMake--) | يحصل على الشركة المصنعة لمعدات التسجيل. |
| [setMake(String value)](#setMake-java.lang.String-) | يضبط الشركة المصنعة لمعدات التسجيل. |
| [getApertureValue()](#getApertureValue--) | يحصل أو يضبط قيمة الفتحة. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط قيمة الفتحة. |
| [getBodySerialNumber()](#getBodySerialNumber--) | يحصل أو يضبط الرقم التسلسلي لجسم الكاميرا. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | يحصل أو يضبط الرقم التسلسلي لجسم الكاميرا. |
| [getBrightnessValue()](#getBrightnessValue--) | يحصل أو يضبط قيمة السطوع. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | يحصل أو يضبط قيمة السطوع. |
| [getCFAPattern()](#getCFAPattern--) | يحصل أو يضبط نمط CFA. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | يحصل أو يضبط نمط CFA. |
| [getCameraOwnerName()](#getCameraOwnerName--) | يحصل أو يضبط اسم مالك الكاميرا |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | يحصل أو يضبط اسم مالك الكاميرا |
| [getColorSpace()](#getColorSpace--) | يحصل أو يضبط مساحة اللون. |
| [setColorSpace(int value)](#setColorSpace-int-) | يحصل أو يضبط مساحة اللون. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | يحصل أو يضبط تكوين المكونات. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | يحصل أو يضبط تكوين المكونات. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | يحصل أو يضبط عدد البتات المضغوطة لكل بكسل. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط عدد البتات المضغوطة لكل بكسل. |
| [getContrast()](#getContrast--) | يحصل أو يضبط التباين. |
| [setContrast(int value)](#setContrast-int-) | يحصل أو يضبط التباين. |
| [getCustomRendered()](#getCustomRendered--) | يحصل أو يضبط النتيجة المخصصة. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | يحصل أو يضبط النتيجة المخصصة. |
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
| [getExposureBiasValue()](#getExposureBiasValue--) | يحصل أو يضبط قيمة تحيز التعرض. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | يحصل أو يضبط قيمة تحيز التعرض. |
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
| [getFlashpixVersion()](#getFlashpixVersion--) | يحصل أو يضبط نسخة flash pix. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | يحصل أو يضبط نسخة flash pix. |
| [getFocalLength()](#getFocalLength--) | الحصول أو تعيين البُعد البؤري. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | الحصول أو تعيين البُعد البؤري. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | الحصول أو تعيين البُعد البؤري في فيلم 35 مم. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | الحصول أو تعيين البُعد البؤري في فيلم 35 مم. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | الحصول أو تعيين وحدة دقة سطح البؤرة. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | الحصول أو تعيين وحدة دقة سطح البؤرة. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | الحصول أو تعيين دقة السطح البؤري س. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | الحصول أو تعيين دقة السطح البؤري س. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | الحصول أو تعيين دقة السطح البؤري ص. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | الحصول أو تعيين دقة السطح البؤري ص. |
| [getGPSAltitude()](#getGPSAltitude--) | الحصول أو تعيين ارتفاع نظام تحديد المواقع. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | الحصول أو تعيين ارتفاع نظام تحديد المواقع. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | الحصول أو تعيين ارتفاع نظام تحديد المواقع المستخدم كارتفاع مرجعي. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | الحصول أو تعيين ارتفاع نظام تحديد المواقع المستخدم كارتفاع مرجعي. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | الحصول أو تعيين معلومات منطقة نظام تحديد المواقع. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | الحصول أو تعيين معلومات منطقة نظام تحديد المواقع. |
| [getGPSDOP()](#getGPSDOP--) | الحصول أو تعيين DOP لنظام تحديد المواقع (درجة دقة البيانات). |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | الحصول أو تعيين DOP لنظام تحديد المواقع (درجة دقة البيانات). |
| [getGPSDestBearing()](#getGPSDestBearing--) | الحصول أو تعيين اتجاه نظام تحديد المواقع إلى نقطة الوجهة. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | الحصول أو تعيين اتجاه نظام تحديد المواقع إلى نقطة الوجهة. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | الحصول أو تعيين المرجع لنظام تحديد المواقع المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | الحصول أو تعيين المرجع لنظام تحديد المواقع المستخدم لتحديد الاتجاه إلى نقطة الوجهة. |
| [getGPSDestDistance()](#getGPSDestDistance--) | الحصول أو تعيين مسافة نظام تحديد المواقع إلى نقطة الوجهة. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | الحصول أو تعيين مسافة نظام تحديد المواقع إلى نقطة الوجهة. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | الحصول أو تعيين الوحدة لنظام تحديد المواقع المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | الحصول أو تعيين الوحدة لنظام تحديد المواقع المستخدمة للتعبير عن المسافة إلى نقطة الوجهة. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | الحصول أو تعيين خط العرض لنظام تحديد المواقع لنقطة الوجهة. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | الحصول أو تعيين خط العرض لنظام تحديد المواقع لنقطة الوجهة. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | الحصول أو تعيين القيمة لنظام تحديد المواقع التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | الحصول أو تعيين القيمة لنظام تحديد المواقع التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | الحصول أو تعيين خط الطول لنظام تحديد المواقع لنقطة الوجهة. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | الحصول أو تعيين خط الطول لنظام تحديد المواقع لنقطة الوجهة. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | الحصول أو تعيين القيمة لنظام تحديد المواقع التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | الحصول أو تعيين القيمة لنظام تحديد المواقع التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا. |
| [getGPSDifferential()](#getGPSDifferential--) | الحصول أو تعيين قيمة نظام تحديد المواقع التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على مستقبل نظام تحديد المواقع. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | الحصول أو تعيين قيمة نظام تحديد المواقع التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على مستقبل نظام تحديد المواقع. |
| [getGPSImgDirection()](#getGPSImgDirection--) | الحصول أو تعيين اتجاه نظام تحديد المواقع للصورة عند التقاطها. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | الحصول أو تعيين اتجاه نظام تحديد المواقع للصورة عند التقاطها. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | الحصول أو تعيين المرجع لنظام تحديد المواقع لتحديد اتجاه الصورة عند التقاطها. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | الحصول أو تعيين المرجع لنظام تحديد المواقع لتحديد اتجاه الصورة عند التقاطها. |
| [getGPSDateStamp()](#getGPSDateStamp--) | الحصول أو تعيين سلسلة الأحرف لنظام تحديد المواقع التي تسجل معلومات التاريخ والوقت بالنسبة لتوقيت UTC (التوقيت العالمي المنسق). |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | الحصول أو تعيين سلسلة الأحرف لنظام تحديد المواقع التي تسجل معلومات التاريخ والوقت بالنسبة لتوقيت UTC (التوقيت العالمي المنسق). |
| [getGPSLatitude()](#getGPSLatitude--) | الحصول أو تعيين خط العرض لنظام تحديد المواقع. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | الحصول أو تعيين خط العرض لنظام تحديد المواقع. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | الحصول أو تعيين ما إذا كان خط عرض نظام تحديد المواقع شماليًا أم جنوبيًا. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | الحصول أو تعيين ما إذا كان خط عرض نظام تحديد المواقع شماليًا أم جنوبيًا. |
| [getGPSLongitude()](#getGPSLongitude--) | الحصول أو تعيين خط الطول لنظام تحديد المواقع. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | الحصول أو تعيين خط الطول لنظام تحديد المواقع. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | الحصول أو تعيين ما إذا كان خط طول نظام تحديد المواقع شرقًا أم غربًا. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | الحصول أو تعيين ما إذا كان خط طول نظام تحديد المواقع شرقًا أم غربًا. |
| [getGPSMapDatum()](#getGPSMapDatum--) | يحصل أو يضبط بيانات المسح الجيوديسي لنظام GPS المستخدمة بواسطة مستقبل GPS. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | يحصل أو يضبط بيانات المسح الجيوديسي لنظام GPS المستخدمة بواسطة مستقبل GPS. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | يحصل أو يضبط وضع قياس GPS. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | يحصل أو يضبط وضع قياس GPS. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | يحصل أو يضبط سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | يحصل أو يضبط سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع. |
| [getGPSSatellites()](#getGPSSatellites--) | يحصل أو يضبط أقمار GPS المستخدمة للقياسات. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | يحصل أو يضبط أقمار GPS المستخدمة للقياسات. |
| [getGPSSpeed()](#getGPSSpeed--) | يحصل أو يضبط سرعة حركة مستقبل GPS. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط سرعة حركة مستقبل GPS. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS. |
| [getGPSStatus()](#getGPSStatus--) | يحصل أو يضبط حالة مستقبل GPS عند تسجيل الصورة. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | يحصل أو يضبط حالة مستقبل GPS عند تسجيل الصورة. |
| [getGPSTimestamp()](#getGPSTimestamp--) | يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق). |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق). |
| [getGPSTrack()](#getGPSTrack--) | يحصل أو يضبط اتجاه حركة مستقبل GPS. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | يحصل أو يضبط اتجاه حركة مستقبل GPS. |
| [getGPSTrackRef()](#getGPSTrackRef--) | يحصل أو يضبط المرجع لتحديد اتجاه حركة مستقبل GPS. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | يحصل أو يضبط المرجع لتحديد اتجاه حركة مستقبل GPS. |
| [getGPSVersionID()](#getGPSVersionID--) | يحصل أو يضبط معرف إصدار GPS. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | يحصل أو يضبط معرف إصدار GPS. |
| [getGainControl()](#getGainControl--) | يحصل أو يضبط درجة تعديل التعزيز الكلي للصورة. |
| [setGainControl(int value)](#setGainControl-int-) | يحصل أو يضبط درجة تعديل التعزيز الكلي للصورة. |
| [getGamma()](#getGamma--) | يحصل أو يضبط قيمة الجاما. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط قيمة الجاما. |
| [getISOSpeed()](#getISOSpeed--) | يحصل أو يضبط سرعة ISO |
| [setISOSpeed(long value)](#setISOSpeed-long-) | يحصل أو يضبط سرعة ISO |
| [getISOSpeedValue()](#getISOSpeedValue--) | يحصل على قيمة سرعة ISO. |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | يضبط قيمة سرعة ISO. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | يحصل أو يضبط قيمة خط العرض yyy لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | يحصل أو يضبط قيمة خط العرض yyy لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | يحصل أو يضبط قيمة خط العرض zzz لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | يحصل أو يضبط قيمة خط العرض zzz لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232. |
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
| [getLensSpecification()](#getLensSpecification--) | يحصل أو يضبط مواصفات العدسة |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط مواصفات العدسة |
| [getLightSource()](#getLightSource--) | يحصل أو يضبط مصدر الضوء. |
| [setLightSource(int value)](#setLightSource-int-) | يحصل أو يضبط مصدر الضوء. |
| [getMakerNoteData()](#getMakerNoteData--) | يحصل على بيانات ملاحظة الصانع. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | يحصل على أو يضبط البيانات الخام لملاحظة الصانع. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | يحصل على أو يضبط البيانات الخام لملاحظة الصانع. |
| [getMakerNotes()](#getMakerNotes--) | يحصل على ملاحظات الصانع. |
| [getMaxApertureValue()](#getMaxApertureValue--) | يحصل على أو يضبط قيمة الفتحة القصوى. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل على أو يضبط قيمة الفتحة القصوى. |
| [getMeteringMode()](#getMeteringMode--) | يحصل على أو يضبط وضع القياس. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | يحصل على أو يضبط وضع القياس. |
| [getOECF()](#getOECF--) | يحصل على أو يضبط وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524. |
| [setOECF(byte[] value)](#setOECF-byte---) | يحصل على أو يضبط وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524. |
| [getOrientation()](#getOrientation--) | يحصل على الاتجاه [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [setOrientation(int value)](#setOrientation-int-) | يضبط الاتجاه [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [getPixelXDimension()](#getPixelXDimension--) | يحصل على أو يضبط بعد بكسل x. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | يحصل على أو يضبط بعد بكسل x. |
| [getPixelYDimension()](#getPixelYDimension--) | يحصل على أو يضبط بعد بكسل y. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | يحصل على أو يضبط بعد بكسل y. |
| [getProperties()](#getProperties--) | يحصل على أو يضبط جميع وسوم EXIF (بما في ذلك الوسوم العامة ووسوم GPS). |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يحصل على أو يضبط جميع وسوم EXIF (بما في ذلك الوسوم العامة ووسوم GPS). |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | يحصل على أو يضبط مؤشر التعرض الموصى به. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | يحصل على أو يضبط مؤشر التعرض الموصى به. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | يحصل على أو يضبط ملف الصوت المرتبط. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | يحصل على أو يضبط ملف الصوت المرتبط. |
| [getSaturation()](#getSaturation--) | يحصل على أو يضبط التشبع. |
| [setSaturation(int value)](#setSaturation-int-) | يحصل على أو يضبط التشبع. |
| [getSceneCaptureType()](#getSceneCaptureType--) | يحصل على أو يضبط نوع التقاط المشهد. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | يحصل على أو يضبط نوع التقاط المشهد. |
| [getSceneType()](#getSceneType--) | يحصل على أو يضبط نوع المشهد. |
| [setSceneType(byte value)](#setSceneType-byte-) | يحصل على أو يضبط نوع المشهد. |
| [getSensingMethod()](#getSensingMethod--) | يحصل على أو يضبط طريقة الاستشعار. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | يحصل على أو يضبط طريقة الاستشعار. |
| [getSensitivityType()](#getSensitivityType--) | يحصل على أو يضبط نوع الحساسية. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | يحصل على أو يضبط نوع الحساسية. |
| [getSharpness()](#getSharpness--) | يحصل على أو يضبط الحدة. |
| [setSharpness(int value)](#setSharpness-int-) | يحصل على أو يضبط الحدة. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | يحصل على أو يضبط قيمة سرعة الغالق. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | يحصل على أو يضبط قيمة سرعة الغالق. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | يحصل على أو يضبط استجابة التردد المكاني. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | يحصل على أو يضبط استجابة التردد المكاني. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | يحصل على أو يضبط الحساسية الطيفية. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | يحصل على أو يضبط الحساسية الطيفية. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | يحصل على حساسية الإخراج القياسية |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | يضبط حساسية الإخراج القياسية |
| [getSubjectArea()](#getSubjectArea--) | يحصل على أو يضبط منطقة الموضوع. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | يحصل على أو يضبط منطقة الموضوع. |
| [getSubjectDistance()](#getSubjectDistance--) | يحصل أو يضبط مسافة الموضوع. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط مسافة الموضوع. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | يحصل أو يضبط نطاق مسافة الموضوع. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | يحصل أو يضبط نطاق مسافة الموضوع. |
| [getSubjectLocation()](#getSubjectLocation--) | يحصل أو يضبط موقع الموضوع. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | يحصل أو يضبط موقع الموضوع. |
| [getSubsecTime()](#getSubsecTime--) | يحصل أو يضبط أجزاء الثواني للعلامة DateTime. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | يحصل أو يضبط أجزاء الثواني للعلامة DateTime. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | يحصل أو يضبط أجزاء الثواني للعلامة DateTimeDigitized. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | يحصل أو يضبط أجزاء الثواني للعلامة DateTimeDigitized. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | يحصل أو يضبط أجزاء الثواني للعلامة DateTimeOriginal. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | يحصل أو يضبط أجزاء الثواني للعلامة DateTimeOriginal. |
| [getUserComment()](#getUserComment--) | يحصل أو يضبط تعليق المستخدم. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | يحصل أو يضبط تعليق المستخدم. |
| [getWhiteBalance()](#getWhiteBalance--) | يحصل أو يضبط توازن اللون الأبيض. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | يحصل أو يضبط توازن اللون الأبيض. |
| [getWhitePoint()](#getWhitePoint--) | يحصل أو يضبط اللونية للنقطة البيضاء في الصورة. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط اللونية للنقطة البيضاء في الصورة. |
| [getCommonTags()](#getCommonTags--) | يحصل أو يضبط العلامات التي تنتمي إلى القسم المشترك. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يحصل أو يضبط العلامات التي تنتمي إلى القسم المشترك. |
| [getExifTags()](#getExifTags--) | يحصل أو يضبط العلامات التي تنتمي إلى قسم EXIF فقط. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يحصل أو يضبط العلامات التي تنتمي إلى قسم EXIF فقط. |
| [getGPSTags()](#getGPSTags--) | يحصل أو يضبط العلامات التي تنتمي إلى قسم GPS فقط. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يحصل أو يضبط العلامات التي تنتمي إلى قسم GPS فقط. |
| [getThumbnail()](#getThumbnail--) | يحصل على صورة المصغرة. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | يضبط صورة المصغرة. |
| [getXResolutionInt()](#getXResolutionInt--) | يحصل على دقة x. |
| [setXResolution(int value)](#setXResolution-int-) | يضبط دقة x. |
| [getYResolutionInt()](#getYResolutionInt--) | يحصل على دقة y. |
| [setYResolution(int value)](#setYResolution-int-) | يضبط دقة y. |
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


ينشئ مثيلًا جديدًا من الفئة `ExifData`.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


ينشئ مثيلًا جديدًا من الفئة `ExifData` باستخدام بيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | مصفوفة من علامات EXIF مع العلامات المشتركة وعلامات GPS. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


ينشئ مثيلًا جديدًا من الفئة `ExifData` باستخدام بيانات من مصفوفة.

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


ينشئ مثيلًا جديدًا من الفئة [ExifData](../../com.aspose.imaging.exif/exifdata) باستخدام بيانات من مصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | مصفوفة من علامات EXIF مع العلامات المشتركة وعلامات GPS. |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


ينشئ مثيلًا جديدًا من الفئة [ExifData](../../com.aspose.imaging.exif/exifdata).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| binaryData | byte[] | البيانات الثنائية. |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت بيانات EXIF الخاصة بالتدفق التي تم إنشاؤها من بتنسيق big endian.

القيمة: `true` إذا كان تدفق بيانات EXIF المُنشأة منه بترتيب بايت كبير؛ وإلا `false`.

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت بيانات EXIF الخاصة بالتدفق التي تم إنشاؤها من بتنسيق big endian.

القيمة: `true` إذا كان تدفق بيانات EXIF المُنشأة منه بترتيب بايت كبير؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

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


يضبط الشركة المصنعة لمعدات التسجيل.

القيمة: الشركة المصنعة لمعدات التسجيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | الشركة المصنعة لمعدات التسجيل. |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


يحصل أو يضبط قيمة الفتحة.

القيمة: قيمة الفتحة.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


يحصل أو يضبط قيمة الفتحة.

القيمة: قيمة الفتحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


يحصل أو يضبط الرقم التسلسلي لجسم الكاميرا.

القيمة: الرقم التسلسلي للجسم.

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


يحصل أو يضبط الرقم التسلسلي لجسم الكاميرا.

القيمة: الرقم التسلسلي للجسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


يحصل أو يضبط قيمة السطوع.

القيمة: قيمة السطوع.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


يحصل أو يضبط قيمة السطوع.

القيمة: قيمة السطوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


يحصل أو يضبط نمط CFA.

القيمة: نمط CFA.

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


يحصل أو يضبط نمط CFA.

القيمة: نمط CFA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


يحصل أو يضبط اسم مالك الكاميرا

القيمة: اسم مالك الكاميرا.

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


يحصل أو يضبط اسم مالك الكاميرا

القيمة: اسم مالك الكاميرا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


يحصل أو يضبط مساحة اللون.

القيمة: مساحة اللون.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


يحصل أو يضبط مساحة اللون.

القيمة: مساحة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


يحصل أو يضبط تكوين المكونات.

القيمة: تكوين المكونات.

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


يحصل أو يضبط تكوين المكونات.

القيمة: تكوين المكونات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


يحصل أو يضبط عدد البتات المضغوطة لكل بكسل.

القيمة: عدد البتات المضغوطة لكل بكسل.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


يحصل أو يضبط عدد البتات المضغوطة لكل بكسل.

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
| value | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


يحصل أو يضبط النتيجة المخصصة.

القيمة: العرض المخصص.

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


يحصل أو يضبط النتيجة المخصصة.

القيمة: العرض المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

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
| value | java.lang.String |  |

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
| value | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


يحصل أو يضبط وصف إعدادات الجهاز

القيمة: وصف إعدادات الجهاز.

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


يحصل أو يضبط وصف إعدادات الجهاز

القيمة: وصف إعدادات الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

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
| value | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


يحصل أو يضبط قيمة تحيز التعرض.

القيمة: قيمة تعويض التعرض.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


يحصل أو يضبط قيمة تحيز التعرض.

القيمة: قيمة تعويض التعرض.

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
| value | int |  |

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
| value | int |  |

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
| value | byte |  |

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
| value | int |  |

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


يحصل أو يضبط نسخة flash pix.

القيمة: إصدار pix الفلاش.

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


يحصل أو يضبط نسخة flash pix.

القيمة: إصدار pix الفلاش.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


الحصول أو تعيين البُعد البؤري.

القيمة: طول البؤري.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


الحصول أو تعيين البُعد البؤري.

القيمة: طول البؤري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


الحصول أو تعيين البُعد البؤري في فيلم 35 مم.

القيمة: البعد البؤري في فيلم 35 مم.

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


الحصول أو تعيين البُعد البؤري في فيلم 35 مم.

القيمة: البعد البؤري في فيلم 35 مم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


الحصول أو تعيين وحدة دقة سطح البؤرة.

القيمة: وحدة دقة مستوى البؤرة.

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


الحصول أو تعيين وحدة دقة سطح البؤرة.

القيمة: وحدة دقة مستوى البؤرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


الحصول أو تعيين دقة السطح البؤري س.

القيمة: دقة مستوى البؤرة X.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


الحصول أو تعيين دقة السطح البؤري س.

القيمة: دقة مستوى البؤرة X.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


الحصول أو تعيين دقة السطح البؤري ص.

القيمة: دقة مستوى البؤرة Y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


الحصول أو تعيين دقة السطح البؤري ص.

القيمة: دقة مستوى البؤرة Y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


الحصول أو تعيين ارتفاع نظام تحديد المواقع.

القيمة: ارتفاع GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


الحصول أو تعيين ارتفاع نظام تحديد المواقع.

القيمة: ارتفاع GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


الحصول أو تعيين ارتفاع نظام تحديد المواقع المستخدم كارتفاع مرجعي.

القيمة: ارتفاع GPS المستخدم كارتفاع مرجعي.

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


الحصول أو تعيين ارتفاع نظام تحديد المواقع المستخدم كارتفاع مرجعي.

القيمة: ارتفاع GPS المستخدم كارتفاع مرجعي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


الحصول أو تعيين معلومات منطقة نظام تحديد المواقع.

القيمة: معلومات منطقة GPS.

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


الحصول أو تعيين معلومات منطقة نظام تحديد المواقع.

القيمة: معلومات منطقة GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


الحصول أو تعيين DOP لنظام تحديد المواقع (درجة دقة البيانات).

القيمة: قيمة GPS DOP (درجة دقة البيانات).

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


الحصول أو تعيين DOP لنظام تحديد المواقع (درجة دقة البيانات).

القيمة: قيمة GPS DOP (درجة دقة البيانات).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


الحصول أو تعيين اتجاه نظام تحديد المواقع إلى نقطة الوجهة.

القيمة: الاتجاه GPS إلى نقطة الوجهة.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


الحصول أو تعيين اتجاه نظام تحديد المواقع إلى نقطة الوجهة.

القيمة: الاتجاه GPS إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


الحصول أو تعيين المرجع لنظام تحديد المواقع المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

القيمة: مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


الحصول أو تعيين المرجع لنظام تحديد المواقع المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

القيمة: مرجع GPS المستخدم لتحديد الاتجاه إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


الحصول أو تعيين مسافة نظام تحديد المواقع إلى نقطة الوجهة.

القيمة: المسافة GPS إلى نقطة الوجهة.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


الحصول أو تعيين مسافة نظام تحديد المواقع إلى نقطة الوجهة.

القيمة: المسافة GPS إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


الحصول أو تعيين الوحدة لنظام تحديد المواقع المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

القيمة: وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


الحصول أو تعيين الوحدة لنظام تحديد المواقع المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

القيمة: وحدة GPS المستخدمة للتعبير عن المسافة إلى نقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


الحصول أو تعيين خط العرض لنظام تحديد المواقع لنقطة الوجهة.

القيمة: خط عرض GPS لنقطة الوجهة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


الحصول أو تعيين خط العرض لنظام تحديد المواقع لنقطة الوجهة.

القيمة: خط عرض GPS لنقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


الحصول أو تعيين القيمة لنظام تحديد المواقع التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


الحصول أو تعيين القيمة لنظام تحديد المواقع التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط عرض نقطة الوجهة شماليًا أم جنوبيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


الحصول أو تعيين خط الطول لنظام تحديد المواقع لنقطة الوجهة.

القيمة: خط طول GPS لنقطة الوجهة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


الحصول أو تعيين خط الطول لنظام تحديد المواقع لنقطة الوجهة.

القيمة: خط طول GPS لنقطة الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


الحصول أو تعيين القيمة لنظام تحديد المواقع التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


الحصول أو تعيين القيمة لنظام تحديد المواقع التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

القيمة: قيمة GPS التي تشير إلى ما إذا كان خط طول نقطة الوجهة شرقًا أم غربًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


الحصول أو تعيين قيمة نظام تحديد المواقع التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على مستقبل نظام تحديد المواقع.

القيمة: قيمة GPS التي تشير إلى ما إذا كان تم تطبيق تصحيح تفاضلي على مستقبل GPS.

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


الحصول أو تعيين قيمة نظام تحديد المواقع التي تشير إلى ما إذا كان التصحيح التفاضلي مطبقًا على مستقبل نظام تحديد المواقع.

القيمة: قيمة GPS التي تشير إلى ما إذا كان تم تطبيق تصحيح تفاضلي على مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


الحصول أو تعيين اتجاه نظام تحديد المواقع للصورة عند التقاطها.

القيمة: اتجاه GPS للصورة عند التقاطها.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


الحصول أو تعيين اتجاه نظام تحديد المواقع للصورة عند التقاطها.

القيمة: اتجاه GPS للصورة عند التقاطها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


الحصول أو تعيين المرجع لنظام تحديد المواقع لتحديد اتجاه الصورة عند التقاطها.

القيمة: مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


الحصول أو تعيين المرجع لنظام تحديد المواقع لتحديد اتجاه الصورة عند التقاطها.

القيمة: مرجع GPS لتحديد اتجاه الصورة عند التقاطها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


الحصول أو تعيين سلسلة الأحرف لنظام تحديد المواقع التي تسجل معلومات التاريخ والوقت بالنسبة لتوقيت UTC (التوقيت العالمي المنسق).

القيمة: سلسلة أحرف GPS التي تسجل معلومات التاريخ والوقت بالنسبة إلى UTC (Coordinated Universal Time).

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


الحصول أو تعيين سلسلة الأحرف لنظام تحديد المواقع التي تسجل معلومات التاريخ والوقت بالنسبة لتوقيت UTC (التوقيت العالمي المنسق).

القيمة: سلسلة أحرف GPS التي تسجل معلومات التاريخ والوقت بالنسبة إلى UTC (Coordinated Universal Time).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


الحصول أو تعيين خط العرض لنظام تحديد المواقع.

القيمة: خط عرض GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


الحصول أو تعيين خط العرض لنظام تحديد المواقع.

القيمة: خط عرض GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


الحصول أو تعيين ما إذا كان خط عرض نظام تحديد المواقع شماليًا أم جنوبيًا.

القيمة: خط عرض GPS هو خط عرض شمالي أو جنوبي.

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


الحصول أو تعيين ما إذا كان خط عرض نظام تحديد المواقع شماليًا أم جنوبيًا.

القيمة: خط عرض GPS هو خط عرض شمالي أو جنوبي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


الحصول أو تعيين خط الطول لنظام تحديد المواقع.

القيمة: خط طول GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


الحصول أو تعيين خط الطول لنظام تحديد المواقع.

القيمة: خط طول GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


الحصول أو تعيين ما إذا كان خط طول نظام تحديد المواقع شرقًا أم غربًا.

القيمة: خط طول GPS هو خط طول شرقي أو غربي.

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


الحصول أو تعيين ما إذا كان خط طول نظام تحديد المواقع شرقًا أم غربًا.

القيمة: خط طول GPS هو خط طول شرقي أو غربي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


يحصل أو يضبط بيانات المسح الجيوديسي لنظام GPS المستخدمة بواسطة مستقبل GPS.

القيمة: بيانات المسح الجيوديسي GPS المستخدمة بواسطة مستقبل GPS.

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


يحصل أو يضبط بيانات المسح الجيوديسي لنظام GPS المستخدمة بواسطة مستقبل GPS.

القيمة: بيانات المسح الجيوديسي GPS المستخدمة بواسطة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

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
| value | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


يحصل أو يضبط سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

القيمة: سلسلة أحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


يحصل أو يضبط سلسلة الأحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

القيمة: سلسلة أحرف GPS التي تسجل اسم الطريقة المستخدمة لتحديد الموقع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


يحصل أو يضبط أقمار GPS المستخدمة للقياسات.

القيمة: أقمار GPS المستخدمة للقياسات.

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


يحصل أو يضبط أقمار GPS المستخدمة للقياسات.

القيمة: أقمار GPS المستخدمة للقياسات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


يحصل أو يضبط سرعة حركة مستقبل GPS.

القيمة: سرعة حركة مستقبل GPS.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


يحصل أو يضبط سرعة حركة مستقبل GPS.

القيمة: سرعة حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS.

القيمة: الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS.

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


يحصل أو يضبط الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS.

القيمة: الوحدة المستخدمة للتعبير عن سرعة حركة مستقبل GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


يحصل أو يضبط حالة مستقبل GPS عند تسجيل الصورة.

القيمة: حالة مستقبل GPS عند تسجيل الصورة.

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


يحصل أو يضبط حالة مستقبل GPS عند تسجيل الصورة.

القيمة: حالة مستقبل GPS عند تسجيل الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق).

القيمة: وقت GPS كـ UTC (Coordinated Universal Time).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


يحصل أو يضبط وقت GPS كـ UTC (التوقيت العالمي المنسق).

القيمة: وقت GPS كـ UTC (Coordinated Universal Time).

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
| value | java.lang.String |  |

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
| value | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


يحصل أو يضبط معرف إصدار GPS.

القيمة: معرف إصدار GPS.

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


يحصل أو يضبط معرف إصدار GPS.

القيمة: معرف إصدار GPS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


يحصل أو يضبط درجة تعديل التعزيز الكلي للصورة.

القيمة: درجة تعديل الكسب الكلي للصورة.

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


يحصل أو يضبط درجة تعديل التعزيز الكلي للصورة.

القيمة: درجة تعديل الكسب الكلي للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


يحصل أو يضبط قيمة الجاما.

القيمة: قيمة الجاما.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


يحصل أو يضبط قيمة الجاما.

القيمة: قيمة الجاما.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


يحصل أو يضبط سرعة ISO

القيمة: سرعة ISO.

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


يحصل أو يضبط سرعة ISO

القيمة: سرعة ISO.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


يحصل على قيمة سرعة ISO.

القيمة: قيمة سرعة iso.

**Returns:**
طويل - قيمة سرعة iso.
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


يضبط قيمة سرعة ISO.

القيمة: قيمة سرعة iso.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | قيمة سرعة iso. |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


يحصل أو يضبط قيمة خط العرض yyy لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال معرف في ISO 12232.

يجب عدم تسجيل هذه العلامة بدون ISOSpeed و ISOSpeedLatitudeZZZ

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


يحصل أو يضبط قيمة خط العرض yyy لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط عرض سرعة ISO yyy لكاميرا أو جهاز إدخال معرف في ISO 12232.

يجب عدم تسجيل هذه العلامة بدون ISOSpeed و ISOSpeedLatitudeZZZ

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


يحصل أو يضبط قيمة خط العرض zzz لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال معرف في ISO 12232.

يجب عدم تسجيل هذه العلامة بدون ISOSpeed و ISOSpeedLatitudeYYY

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


يحصل أو يضبط قيمة خط العرض zzz لسرعة ISO لكاميرا أو جهاز إدخال كما هو معرف في ISO 12232.

القيمة: قيمة خط عرض سرعة ISO zzz لكاميرا أو جهاز إدخال معرف في ISO 12232.

يجب عدم تسجيل هذه العلامة بدون ISOSpeed و ISOSpeedLatitudeYYY

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

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
| value | long |  |

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
| value | java.lang.String |  |

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
| value | java.lang.String |  |

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
| value | java.lang.String |  |

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
| value | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


يحصل أو يضبط مواصفات العدسة

القيمة: مواصفات العدسة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


يحصل أو يضبط مواصفات العدسة

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
| value | int |  |

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


يحصل على أو يضبط البيانات الخام لملاحظة الصانع.

القيمة: البيانات الخام لملاحظة الصانع.

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


يحصل على أو يضبط البيانات الخام لملاحظة الصانع.

القيمة: البيانات الخام لملاحظة الصانع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

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


يحصل على أو يضبط قيمة الفتحة القصوى.

القيمة: قيمة الفتحة القصوى.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


يحصل على أو يضبط قيمة الفتحة القصوى.

القيمة: قيمة الفتحة القصوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


يحصل على أو يضبط وضع القياس.

القيمة: وضع القياس.

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


يحصل على أو يضبط وضع القياس.

القيمة: وضع القياس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


يحصل على أو يضبط وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

القيمة: وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


يحصل على أو يضبط وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

القيمة: وظيفة التحويل الضوئي-الكهربائي (OECF) المحددة في ISO 14524.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

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
| value | int | الاتجاه. |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


يحصل على أو يضبط بعد بكسل x.

القيمة: البُعد السيني للبكسل.

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


يحصل على أو يضبط بعد بكسل x.

القيمة: البُعد السيني للبكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


يحصل على أو يضبط بعد بكسل y.

القيمة: البُعد الصادي للبكسل.

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


يحصل على أو يضبط بعد بكسل y.

القيمة: البُعد الصادي للبكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


يحصل على أو يضبط جميع وسوم EXIF (بما في ذلك الوسوم العامة ووسوم GPS).

القيمة: وسوم EXIF (بما في ذلك الوسوم الشائعة ووسوم GPS).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


يحصل على أو يضبط جميع وسوم EXIF (بما في ذلك الوسوم العامة ووسوم GPS).

القيمة: وسوم EXIF (بما في ذلك الوسوم الشائعة ووسوم GPS).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


يحصل على أو يضبط مؤشر التعرض الموصى به.

القيمة: مؤشر التعرض الموصى به.

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


يحصل على أو يضبط مؤشر التعرض الموصى به.

القيمة: مؤشر التعرض الموصى به.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


يحصل على أو يضبط ملف الصوت المرتبط.

القيمة: ملف الصوت المرتبط.

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


يحصل على أو يضبط ملف الصوت المرتبط.

القيمة: ملف الصوت المرتبط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


يحصل على أو يضبط التشبع.

القيمة: التشبع.

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


يحصل على أو يضبط التشبع.

القيمة: التشبع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


يحصل على أو يضبط نوع التقاط المشهد.

القيمة: نوع التقاط المشهد.

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


يحصل على أو يضبط نوع التقاط المشهد.

القيمة: نوع التقاط المشهد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


يحصل على أو يضبط نوع المشهد.

القيمة: نوع المشهد.

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


يحصل على أو يضبط نوع المشهد.

القيمة: نوع المشهد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


يحصل على أو يضبط طريقة الاستشعار.

القيمة: طريقة الاستشعار.

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


يحصل على أو يضبط طريقة الاستشعار.

القيمة: طريقة الاستشعار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


يحصل على أو يضبط نوع الحساسية.

القيمة: نوع الحساسية.

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


يحصل على أو يضبط نوع الحساسية.

القيمة: نوع الحساسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


يحصل على أو يضبط الحدة.

القيمة: الحدة.

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


يحصل على أو يضبط الحدة.

القيمة: الحدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


يحصل على أو يضبط قيمة سرعة الغالق.

القيمة: قيمة سرعة الغالق.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


يحصل على أو يضبط قيمة سرعة الغالق.

القيمة: قيمة سرعة الغالق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


يحصل على أو يضبط استجابة التردد المكاني.

القيمة: استجابة التردد المكاني.

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


يحصل على أو يضبط استجابة التردد المكاني.

القيمة: استجابة التردد المكاني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


يحصل على أو يضبط الحساسية الطيفية.

القيمة: الحساسية الطيفية.

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


يحصل على أو يضبط الحساسية الطيفية.

القيمة: الحساسية الطيفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


يحصل على حساسية الإخراج القياسية

القيمة: حساسية الإخراج القياسية.

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


يضبط حساسية الإخراج القياسية

القيمة: حساسية الإخراج القياسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


يحصل على أو يضبط منطقة الموضوع.

القيمة: منطقة الموضوع.

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


يحصل على أو يضبط منطقة الموضوع.

القيمة: منطقة الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


يحصل أو يضبط مسافة الموضوع.

القيمة: مسافة الموضوع.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


يحصل أو يضبط مسافة الموضوع.

القيمة: مسافة الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


يحصل أو يضبط نطاق مسافة الموضوع.

القيمة: نطاق مسافة الموضوع.

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


يحصل أو يضبط نطاق مسافة الموضوع.

القيمة: نطاق مسافة الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


يحصل أو يضبط موقع الموضوع.

القيمة: موقع الموضوع.

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


يحصل أو يضبط موقع الموضوع.

القيمة: موقع الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


يحصل أو يضبط أجزاء الثواني للعلامة DateTime.

القيمة: أجزاء الثواني لعلامة DateTime.

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


يحصل أو يضبط أجزاء الثواني للعلامة DateTime.

القيمة: أجزاء الثواني لعلامة DateTime.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


يحصل أو يضبط أجزاء الثواني للعلامة DateTimeDigitized.

القيمة: أجزاء الثواني لعلامة DateTimeDigitized.

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


يحصل أو يضبط أجزاء الثواني للعلامة DateTimeDigitized.

القيمة: أجزاء الثواني لعلامة DateTimeDigitized.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


يحصل أو يضبط أجزاء الثواني للعلامة DateTimeOriginal.

القيمة: أجزاء الثواني لعلامة DateTimeOriginal.

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


يحصل أو يضبط أجزاء الثواني للعلامة DateTimeOriginal.

القيمة: أجزاء الثواني لعلامة DateTimeOriginal.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


يحصل أو يضبط تعليق المستخدم.

القيمة: تعليق المستخدم.

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


يحصل أو يضبط تعليق المستخدم.

القيمة: تعليق المستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


يحصل أو يضبط توازن اللون الأبيض.

القيمة: توازن اللون الأبيض.

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


يحصل أو يضبط توازن اللون الأبيض.

القيمة: توازن اللون الأبيض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


يحصل أو يضبط اللونية للنقطة البيضاء في الصورة.

القيمة: إشباع اللون للنقطة البيضاء في الصورة.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


يحصل أو يضبط اللونية للنقطة البيضاء في الصورة.

القيمة: إشباع اللون للنقطة البيضاء في الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. ينطبق هذا فقط على صور jpeg، وفي تنسيق tiff يتم استخدام tiffOptions بدلاً من ذلك

القيمة: علامات القسم المشترك.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


يحصل أو يعيّن العلامات التي تنتمي إلى القسم المشترك. ينطبق هذا فقط على صور jpeg، وفي تنسيق tiff يتم استخدام tiffOptions بدلاً من ذلك

القيمة: علامات القسم المشترك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


يحصل أو يضبط العلامات التي تنتمي إلى قسم EXIF فقط.

القيمة: علامات قسم EXIF.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


يحصل أو يضبط العلامات التي تنتمي إلى قسم EXIF فقط.

القيمة: علامات قسم EXIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


يحصل أو يضبط العلامات التي تنتمي إلى قسم GPS فقط.

القيمة: علامات GPS.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


يحصل أو يضبط العلامات التي تنتمي إلى قسم GPS فقط.

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


يضبط صورة المصغرة.

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


يضبط دقة x.

القيمة: دقة x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | دقة x. |

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


يضبط دقة y.

القيمة: دقة y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | دقة y. |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


إزالة العلامة من الحاوية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرّف الوسم المراد إزالته. |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


يحصل على قيمة العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| key | int | مفتاح الوسم [ExifProperties](../../com.aspose.imaging.exif/exifproperties). |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
