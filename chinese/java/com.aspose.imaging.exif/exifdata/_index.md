---
title: "ExifData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EXIF 数据容器。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.exif/exifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller)

**All Implemented Interfaces:**
[com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class ExifData extends TiffDataTypeController implements IImageMetadataFormat
```

EXIF 数据容器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExifData()](#ExifData--) | 初始化 `ExifData` 类的新实例。 |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 使用数组中的数据初始化 `ExifData` 类的新实例。 |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | 使用数组中的数据初始化 `ExifData` 类的新实例。 |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | 使用数组中的数据初始化 [ExifData](../../com.aspose.imaging.exif/exifdata) 类的新实例。 |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | 初始化 [ExifData](../../com.aspose.imaging.exif/exifdata) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | 获取或设置一个值，指示创建自该流的 EXIF 数据是否为大端序。 |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | 获取或设置一个值，指示创建自该流的 EXIF 数据是否为大端序。 |
| [getMake()](#getMake--) | 获取记录设备的制造商。 |
| [setMake(String value)](#setMake-java.lang.String-) | 设置记录设备的制造商。 |
| [getApertureValue()](#getApertureValue--) | 获取或设置光圈值。 |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置光圈值。 |
| [getBodySerialNumber()](#getBodySerialNumber--) | 获取或设置相机机身序列号。 |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | 获取或设置相机机身序列号。 |
| [getBrightnessValue()](#getBrightnessValue--) | 获取或设置亮度值。 |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | 获取或设置亮度值。 |
| [getCFAPattern()](#getCFAPattern--) | 获取或设置 CFA 模式。 |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | 获取或设置 CFA 模式。 |
| [getCameraOwnerName()](#getCameraOwnerName--) | 获取或设置相机所有者名称 |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | 获取或设置相机所有者名称 |
| [getColorSpace()](#getColorSpace--) | 获取或设置色彩空间。 |
| [setColorSpace(int value)](#setColorSpace-int-) | 获取或设置色彩空间。 |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | 获取或设置组件配置。 |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | 获取或设置组件配置。 |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | 获取或设置每像素压缩位数。 |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置每像素压缩位数。 |
| [getContrast()](#getContrast--) | 获取或设置对比度。 |
| [setContrast(int value)](#setContrast-int-) | 获取或设置对比度。 |
| [getCustomRendered()](#getCustomRendered--) | 获取或设置自定义渲染。 |
| [setCustomRendered(int value)](#setCustomRendered-int-) | 获取或设置自定义渲染。 |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | 获取或设置数字化日期时间。 |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | 获取或设置数字化日期时间。 |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | 获取或设置原始日期时间。 |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | 获取或设置原始日期时间。 |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | 获取或设置设备设置描述 |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | 获取或设置设备设置描述 |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | 获取或设置数字变焦比例。 |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置数字变焦比例。 |
| [getExifVersion()](#getExifVersion--) | 获取或设置 EXIF 版本。 |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | 获取或设置 EXIF 版本。 |
| [getExposureBiasValue()](#getExposureBiasValue--) | 获取或设置曝光偏差值。 |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | 获取或设置曝光偏差值。 |
| [getExposureIndex()](#getExposureIndex--) | 获取或设置曝光指数。 |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置曝光指数。 |
| [getExposureMode()](#getExposureMode--) | 获取或设置曝光模式。 |
| [setExposureMode(int value)](#setExposureMode-int-) | 获取或设置曝光模式。 |
| [getExposureProgram()](#getExposureProgram--) | 获取或设置曝光程序。 |
| [setExposureProgram(int value)](#setExposureProgram-int-) | 获取或设置曝光程序。 |
| [getExposureTime()](#getExposureTime--) | 获取或设置曝光时间。 |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置曝光时间。 |
| [getFNumber()](#getFNumber--) | 获取或设置光圈值。 |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置光圈值。 |
| [getFileSource()](#getFileSource--) | 获取或设置文件来源类型。 |
| [setFileSource(byte value)](#setFileSource-byte-) | 获取或设置文件来源类型。 |
| [getFlash()](#getFlash--) | 获取或设置闪光灯。 |
| [setFlash(int value)](#setFlash-int-) | 获取或设置闪光灯。 |
| [getFlashEnergy()](#getFlashEnergy--) | 获取或设置闪光能量。 |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置闪光能量。 |
| [getFlashpixVersion()](#getFlashpixVersion--) | 获取或设置闪光像素版本。 |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | 获取或设置闪光像素版本。 |
| [getFocalLength()](#getFocalLength--) | 获取或设置焦距。 |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置焦距。 |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | 获取或设置 35 mm 胶片中的焦距。 |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | 获取或设置 35 mm 胶片中的焦距。 |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | 获取或设置焦平面分辨率单位。 |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | 获取或设置焦平面分辨率单位。 |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | 获取或设置焦平面 X 分辨率。 |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置焦平面 X 分辨率。 |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | 获取或设置焦平面 Y 分辨率。 |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置焦平面 Y 分辨率。 |
| [getGPSAltitude()](#getGPSAltitude--) | 获取或设置 GPS 海拔。 |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置 GPS 海拔。 |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | 获取或设置用作参考海拔的 GPS 海拔。 |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | 获取或设置用作参考海拔的 GPS 海拔。 |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | 获取或设置 GPS 区域信息。 |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | 获取或设置 GPS 区域信息。 |
| [getGPSDOP()](#getGPSDOP--) | 获取或设置 GPS DOP（数据精度等级）。 |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置 GPS DOP（数据精度等级）。 |
| [getGPSDestBearing()](#getGPSDestBearing--) | 获取或设置指向目的地点的 GPS 方位角。 |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置指向目的地点的 GPS 方位角。 |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | 获取或设置用于给出指向目的地点方位角的 GPS 参考。 |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | 获取或设置用于给出指向目的地点方位角的 GPS 参考。 |
| [getGPSDestDistance()](#getGPSDestDistance--) | 获取或设置到目的地点的 GPS 距离。 |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置到目的地点的 GPS 距离。 |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | 获取或设置用于表示到目的地点距离的 GPS 单位。 |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | 获取或设置用于表示到目的地点距离的 GPS 单位。 |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | 获取或设置目的地点的 GPS 纬度。 |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置目的地点的 GPS 纬度。 |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | 获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。 |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | 获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。 |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | 获取或设置目的地点的 GPS 经度。 |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置目的地点的 GPS 经度。 |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | 获取或设置指示目的地点经度是东经还是西经的 GPS 值。 |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | 获取或设置指示目的地点经度是东经还是西经的 GPS 值。 |
| [getGPSDifferential()](#getGPSDifferential--) | 获取或设置指示是否对 GPS 接收器应用差分校正的 GPS 值。 |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | 获取或设置指示是否对 GPS 接收器应用差分校正的 GPS 值。 |
| [getGPSImgDirection()](#getGPSImgDirection--) | 获取或设置图像拍摄时的 GPS 方向。 |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置图像拍摄时的 GPS 方向。 |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | 获取或设置用于给出图像拍摄时方向的 GPS 参考。 |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | 获取或设置用于给出图像拍摄时方向的 GPS 参考。 |
| [getGPSDateStamp()](#getGPSDateStamp--) | 获取或设置记录相对于 UTC（协调世界时）的日期和时间信息的 GPS 字符串。 |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | 获取或设置记录相对于 UTC（协调世界时）的日期和时间信息的 GPS 字符串。 |
| [getGPSLatitude()](#getGPSLatitude--) | 获取或设置 GPS 纬度。 |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置 GPS 纬度。 |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | 获取或设置 GPS 纬度是北纬还是南纬。 |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | 获取或设置 GPS 纬度是北纬还是南纬。 |
| [getGPSLongitude()](#getGPSLongitude--) | 获取或设置 GPS 经度。 |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置 GPS 经度。 |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | 获取或设置 GPS 经度是东经还是西经。 |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | 获取或设置 GPS 经度是东经还是西经。 |
| [getGPSMapDatum()](#getGPSMapDatum--) | 获取或设置 GPS 接收器使用的 GPS 大地测量数据。 |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | 获取或设置 GPS 接收器使用的 GPS 大地测量数据。 |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | 获取或设置 GPS 测量模式。 |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | 获取或设置 GPS 测量模式。 |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | 获取或设置记录用于定位方法名称的 GPS 字符串。 |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | 获取或设置记录用于定位方法名称的 GPS 字符串。 |
| [getGPSSatellites()](#getGPSSatellites--) | 获取或设置用于测量的 GPS 卫星。 |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | 获取或设置用于测量的 GPS 卫星。 |
| [getGPSSpeed()](#getGPSSpeed--) | 获取或设置 GPS 接收器移动的速度。 |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置 GPS 接收器移动的速度。 |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | 获取或设置用于表示 GPS 接收器移动速度的单位。 |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | 获取或设置用于表示 GPS 接收器移动速度的单位。 |
| [getGPSStatus()](#getGPSStatus--) | 获取或设置图像记录时 GPS 接收器的状态。 |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | 获取或设置图像记录时 GPS 接收器的状态。 |
| [getGPSTimestamp()](#getGPSTimestamp--) | 获取或设置 GPS 时间（UTC，协调世界时）。 |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置 GPS 时间（UTC，协调世界时）。 |
| [getGPSTrack()](#getGPSTrack--) | 获取或设置 GPS 接收器移动的方向。 |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | 获取或设置 GPS 接收器移动的方向。 |
| [getGPSTrackRef()](#getGPSTrackRef--) | 获取或设置提供 GPS 接收器移动方向的参考。 |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | 获取或设置提供 GPS 接收器移动方向的参考。 |
| [getGPSVersionID()](#getGPSVersionID--) | 获取或设置 GPS 版本标识符。 |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | 获取或设置 GPS 版本标识符。 |
| [getGainControl()](#getGainControl--) | 获取或设置整体图像增益调整的程度。 |
| [setGainControl(int value)](#setGainControl-int-) | 获取或设置整体图像增益调整的程度。 |
| [getGamma()](#getGamma--) | 获取或设置伽马值。 |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置伽马值。 |
| [getISOSpeed()](#getISOSpeed--) | 获取或设置 ISO 速度 |
| [setISOSpeed(long value)](#setISOSpeed-long-) | 获取或设置 ISO 速度 |
| [getISOSpeedValue()](#getISOSpeedValue--) | 获取 ISO 速度值。 |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | 设置 ISO 速度值。 |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。 |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。 |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。 |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。 |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | 获取或设置摄影灵敏度。 |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | 获取或设置摄影灵敏度。 |
| [getImageUniqueID()](#getImageUniqueID--) | 获取或设置图像唯一标识符。 |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | 获取或设置图像唯一标识符。 |
| [getLensMake()](#getLensMake--) | 获取或设置镜头制造商。 |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | 获取或设置镜头制造商。 |
| [getLensModel()](#getLensModel--) | 获取或设置镜头型号。 |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | 获取或设置镜头型号。 |
| [getLensSerialNumber()](#getLensSerialNumber--) | 获取或设置镜头序列号。 |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | 获取或设置镜头序列号。 |
| [getLensSpecification()](#getLensSpecification--) | 获取或设置镜头规格。 |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置镜头规格。 |
| [getLightSource()](#getLightSource--) | 获取或设置光源。 |
| [setLightSource(int value)](#setLightSource-int-) | 获取或设置光源。 |
| [getMakerNoteData()](#getMakerNoteData--) | 获取制造商注释数据。 |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | 获取或设置制造商注释原始数据。 |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | 获取或设置制造商注释原始数据。 |
| [getMakerNotes()](#getMakerNotes--) | 获取制造商注释。 |
| [getMaxApertureValue()](#getMaxApertureValue--) | 获取或设置最大光圈值。 |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置最大光圈值。 |
| [getMeteringMode()](#getMeteringMode--) | 获取或设置测光模式。 |
| [setMeteringMode(int value)](#setMeteringMode-int-) | 获取或设置测光模式。 |
| [getOECF()](#getOECF--) | 获取或设置 ISO 14524 中指定的光电转换函数 (OECF)。 |
| [setOECF(byte[] value)](#setOECF-byte---) | 获取或设置 ISO 14524 中指定的光电转换函数 (OECF)。 |
| [getOrientation()](#getOrientation--) | 获取方向 [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation)。 |
| [setOrientation(int value)](#setOrientation-int-) | 设置方向 [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation)。 |
| [getPixelXDimension()](#getPixelXDimension--) | 获取或设置像素 x 维度. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | 获取或设置像素 x 维度. |
| [getPixelYDimension()](#getPixelYDimension--) | 获取或设置像素 y 维度. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | 获取或设置像素 y 维度. |
| [getProperties()](#getProperties--) | 获取或设置所有 EXIF 标记（包括常用标记和 GPS 标记）. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 获取或设置所有 EXIF 标记（包括常用标记和 GPS 标记）. |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | 获取或设置推荐的曝光指数. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | 获取或设置推荐的曝光指数. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | 获取或设置相关的声音文件. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | 获取或设置相关的声音文件. |
| [getSaturation()](#getSaturation--) | 获取或设置饱和度. |
| [setSaturation(int value)](#setSaturation-int-) | 获取或设置饱和度. |
| [getSceneCaptureType()](#getSceneCaptureType--) | 获取或设置场景捕获类型. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | 获取或设置场景捕获类型. |
| [getSceneType()](#getSceneType--) | 获取或设置场景类型. |
| [setSceneType(byte value)](#setSceneType-byte-) | 获取或设置场景类型. |
| [getSensingMethod()](#getSensingMethod--) | 获取或设置感应方法. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | 获取或设置感应方法. |
| [getSensitivityType()](#getSensitivityType--) | 获取或设置灵敏度类型. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | 获取或设置灵敏度类型. |
| [getSharpness()](#getSharpness--) | 获取或设置锐度. |
| [setSharpness(int value)](#setSharpness-int-) | 获取或设置锐度. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | 获取或设置快门速度值. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | 获取或设置快门速度值. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | 获取或设置空间频率响应. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | 获取或设置空间频率响应. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | 获取或设置光谱灵敏度. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | 获取或设置光谱灵敏度. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | 获取标准输出灵敏度 |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | 设置标准输出灵敏度 |
| [getSubjectArea()](#getSubjectArea--) | 获取或设置主体区域. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | 获取或设置主体区域. |
| [getSubjectDistance()](#getSubjectDistance--) | 获取或设置主体距离. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | 获取或设置主体距离. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | 获取或设置主体距离范围. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | 获取或设置主体距离范围. |
| [getSubjectLocation()](#getSubjectLocation--) | 获取或设置主体位置. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | 获取或设置主体位置. |
| [getSubsecTime()](#getSubsecTime--) | 获取或设置 DateTime 标记的秒分数. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | 获取或设置 DateTime 标记的秒分数. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | 获取或设置 DateTimeDigitized 标记的秒分数. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | 获取或设置 DateTimeDigitized 标记的秒分数. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | 获取或设置 DateTimeOriginal 标记的秒分数. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | 获取或设置 DateTimeOriginal 标记的秒分数. |
| [getUserComment()](#getUserComment--) | 获取或设置用户评论. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | 获取或设置用户评论. |
| [getWhiteBalance()](#getWhiteBalance--) | 获取或设置白平衡. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | 获取或设置白平衡. |
| [getWhitePoint()](#getWhitePoint--) | 获取或设置图像白点的色度。 |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | 获取或设置图像白点的色度。 |
| [getCommonTags()](#getCommonTags--) | 获取或设置属于公共部分的标签。 |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 获取或设置属于公共部分的标签。 |
| [getExifTags()](#getExifTags--) | 获取或设置仅属于 EXIF 部分的标签。 |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 获取或设置仅属于 EXIF 部分的标签。 |
| [getGPSTags()](#getGPSTags--) | 获取或设置仅属于 GPS 部分的标签。 |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | 获取或设置仅属于 GPS 部分的标签。 |
| [getThumbnail()](#getThumbnail--) | 获取缩略图。 |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | 设置缩略图。 |
| [getXResolutionInt()](#getXResolutionInt--) | 获取 X 方向分辨率。 |
| [setXResolution(int value)](#setXResolution-int-) | 设置 X 方向分辨率。 |
| [getYResolutionInt()](#getYResolutionInt--) | 获取 Y 方向分辨率。 |
| [setYResolution(int value)](#setYResolution-int-) | 设置 Y 方向分辨率。 |
| [removeTag(int tagId)](#removeTag-int-) | 从容器中移除标签 |
| [getTagValue(int key)](#getTagValue-int-) | 获取标签值。 |

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


初始化 `ExifData` 类的新实例。

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


使用数组中的数据初始化 `ExifData` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 包含公共标签和 GPS 标签的 EXIF 标签数组。 |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


使用数组中的数据初始化 `ExifData` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | 公共标签。 |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | EXIF 标签。 |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | GPS 标签。 |

### ExifData(ExifData exifdata) {#ExifData-com.aspose.imaging.exif.ExifData-}
```
public ExifData(ExifData exifdata)
```


使用数组中的数据初始化 [ExifData](../../com.aspose.imaging.exif/exifdata) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | 包含公共标签和 GPS 标签的 EXIF 标签数组。 |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


初始化 [ExifData](../../com.aspose.imaging.exif/exifdata) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| binaryData | byte[] | 二进制数据。 |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


获取或设置一个值，指示创建自该流的 EXIF 数据是否为大端序。

值：`true` 表示从中创建的流 EXIF 数据为大端序；否则为 `false`。

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


获取或设置一个值，指示创建自该流的 EXIF 数据是否为大端序。

值：`true` 表示从中创建的流 EXIF 数据为大端序；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMake() {#getMake--}
```
public final String getMake()
```


获取记录设备的制造商。

值：记录设备的制造商。

**Returns:**
java.lang.String - 记录设备的制造商。
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


设置记录设备的制造商。

值：记录设备的制造商。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 记录设备的制造商。 |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


获取或设置光圈值。

值：光圈值。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


获取或设置光圈值。

值：光圈值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


获取或设置相机机身序列号。

值：机身序列号。

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


获取或设置相机机身序列号。

值：机身序列号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


获取或设置亮度值。

值：亮度值。

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


获取或设置亮度值。

值：亮度值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


获取或设置 CFA 模式。

值：CFA 模式。

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


获取或设置 CFA 模式。

值：CFA 模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


获取或设置相机所有者名称

值：相机所有者的名称。

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


获取或设置相机所有者名称

值：相机所有者的名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


获取或设置色彩空间。

值：色彩空间。

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


获取或设置色彩空间。

值：色彩空间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


获取或设置组件配置。

值：组件配置。

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


获取或设置组件配置。

值：组件配置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


获取或设置每像素压缩位数。

值：每像素压缩位数。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


获取或设置每像素压缩位数。

值：每像素压缩位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getContrast() {#getContrast--}
```
public int getContrast()
```


获取或设置对比度。

值：对比度。

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


获取或设置对比度。

值：对比度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


获取或设置自定义渲染。

值：自定义渲染。

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


获取或设置自定义渲染。

值：自定义渲染。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


获取或设置数字化日期时间。

值：数字化日期时间。

**Returns:**
java.lang.String
### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


获取或设置数字化日期时间。

值：数字化日期时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


获取或设置原始日期时间。

值：原始日期时间。

**Returns:**
java.lang.String
### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


获取或设置原始日期时间。

值：原始日期时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


获取或设置设备设置描述

值：设备设置描述。

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


获取或设置设备设置描述

值：设备设置描述。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


获取或设置数字变焦比例。

值：数字变焦比例。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


获取或设置数字变焦比例。

值：数字变焦比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


获取或设置 EXIF 版本。

值：EXIF 版本。

**Returns:**
byte[]
### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


获取或设置 EXIF 版本。

值：EXIF 版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


获取或设置曝光偏差值。

值：曝光偏差值。

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


获取或设置曝光偏差值。

值：曝光偏差值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


获取或设置曝光指数。

值：曝光指数。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


获取或设置曝光指数。

值：曝光指数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


获取或设置曝光模式。

值：曝光模式。

**Returns:**
int
### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


获取或设置曝光模式。

值：曝光模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


获取或设置曝光程序。

值：曝光程序。

**Returns:**
int
### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


获取或设置曝光程序。

值：曝光程序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


获取或设置曝光时间。

值：曝光时间。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


获取或设置曝光时间。

值：曝光时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


获取或设置光圈值。

值：光圈值。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFNumber(TiffRational value) {#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


获取或设置光圈值。

值：光圈值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


获取或设置文件来源类型。

值：文件来源类型。

**Returns:**
byte
### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


获取或设置文件来源类型。

值：文件来源类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getFlash() {#getFlash--}
```
public int getFlash()
```


获取或设置闪光灯。

值：闪光灯。

**Returns:**
int
### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


获取或设置闪光灯。

值：闪光灯。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


获取或设置闪光能量。

值：闪光能量。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


获取或设置闪光能量。

值：闪光能量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


获取或设置闪光像素版本。

值：闪光像素版本。

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


获取或设置闪光像素版本。

值：闪光像素版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


获取或设置焦距。

值：焦距长度。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


获取或设置焦距。

值：焦距长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


获取或设置 35 mm 胶片中的焦距。

值：35 mm 胶片等效焦距。

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


获取或设置 35 mm 胶片中的焦距。

值：35 mm 胶片等效焦距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


获取或设置焦平面分辨率单位。

值：焦平面分辨率单位。

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


获取或设置焦平面分辨率单位。

值：焦平面分辨率单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


获取或设置焦平面 X 分辨率。

Value: 焦平面 x 分辨率。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


获取或设置焦平面 X 分辨率。

Value: 焦平面 x 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


获取或设置焦平面 Y 分辨率。

Value: 焦平面 y 分辨率。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


获取或设置焦平面 Y 分辨率。

Value: 焦平面 y 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


获取或设置 GPS 海拔。

Value: GPS 海拔。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


获取或设置 GPS 海拔。

Value: GPS 海拔。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


获取或设置用作参考海拔的 GPS 海拔。

Value: 用作参考海拔的 GPS 海拔。

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


获取或设置用作参考海拔的 GPS 海拔。

Value: 用作参考海拔的 GPS 海拔。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


获取或设置 GPS 区域信息。

Value: GPS 区域信息。

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


获取或设置 GPS 区域信息。

Value: GPS 区域信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


获取或设置 GPS DOP（数据精度等级）。

Value: GPS DOP（数据精度等级）。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


获取或设置 GPS DOP（数据精度等级）。

Value: GPS DOP（数据精度等级）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


获取或设置指向目的地点的 GPS 方位角。

Value: 指向目的点的 GPS 方位。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


获取或设置指向目的地点的 GPS 方位角。

Value: 指向目的点的 GPS 方位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


获取或设置用于给出指向目的地点方位角的 GPS 参考。

Value: 用于给出指向目的点方位的 GPS 参考。

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


获取或设置用于给出指向目的地点方位角的 GPS 参考。

Value: 用于给出指向目的点方位的 GPS 参考。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


获取或设置到目的地点的 GPS 距离。

Value: 到目的点的 GPS 距离。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


获取或设置到目的地点的 GPS 距离。

Value: 到目的点的 GPS 距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


获取或设置用于表示到目的地点距离的 GPS 单位。

Value: 用于表示到目的点距离的 GPS 单位。

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


获取或设置用于表示到目的地点距离的 GPS 单位。

Value: 用于表示到目的点距离的 GPS 单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


获取或设置目的地点的 GPS 纬度。

Value: 目的点的 GPS 纬度。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


获取或设置目的地点的 GPS 纬度。

Value: 目的点的 GPS 纬度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。

Value: 表示目的点纬度是北纬还是南纬的 GPS 值。

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。

Value: 表示目的点纬度是北纬还是南纬的 GPS 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


获取或设置目的地点的 GPS 经度。

Value: 目的点的 GPS 经度。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


获取或设置目的地点的 GPS 经度。

Value: 目的点的 GPS 经度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


获取或设置指示目的地点经度是东经还是西经的 GPS 值。

Value: 表示目的点经度是东经还是西经的 GPS 值。

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


获取或设置指示目的地点经度是东经还是西经的 GPS 值。

Value: 表示目的点经度是东经还是西经的 GPS 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


获取或设置指示是否对 GPS 接收器应用差分校正的 GPS 值。

Value: 表示是否对 GPS 接收机应用差分校正的 GPS 值。

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


获取或设置指示是否对 GPS 接收器应用差分校正的 GPS 值。

Value: 表示是否对 GPS 接收机应用差分校正的 GPS 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


获取或设置图像拍摄时的 GPS 方向。

Value: 拍摄时图像的 GPS 方向。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


获取或设置图像拍摄时的 GPS 方向。

Value: 拍摄时图像的 GPS 方向。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


获取或设置用于给出图像拍摄时方向的 GPS 参考。

Value: 用于给出拍摄时图像方向的 GPS 参考。

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


获取或设置用于给出图像拍摄时方向的 GPS 参考。

Value: 用于给出拍摄时图像方向的 GPS 参考。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


获取或设置记录相对于 UTC（协调世界时）的日期和时间信息的 GPS 字符串。

Value: 记录相对于 UTC（协调世界时）的日期和时间信息的 GPS 字符串。

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


获取或设置记录相对于 UTC（协调世界时）的日期和时间信息的 GPS 字符串。

Value: 记录相对于 UTC（协调世界时）的日期和时间信息的 GPS 字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


获取或设置 GPS 纬度。

Value: GPS 纬度。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


获取或设置 GPS 纬度。

Value: GPS 纬度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


获取或设置 GPS 纬度是北纬还是南纬。

Value: GPS 纬度为北纬或南纬。

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


获取或设置 GPS 纬度是北纬还是南纬。

Value: GPS 纬度为北纬或南纬。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


获取或设置 GPS 经度。

Value: GPS 经度。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


获取或设置 GPS 经度。

Value: GPS 经度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


获取或设置 GPS 经度是东经还是西经。

Value: GPS 经度为东经或西经。

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


获取或设置 GPS 经度是东经还是西经。

Value: GPS 经度为东经或西经。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


获取或设置 GPS 接收器使用的 GPS 大地测量数据。

Value: GPS 接收机使用的 GPS 大地测量数据。

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


获取或设置 GPS 接收器使用的 GPS 大地测量数据。

Value: GPS 接收机使用的 GPS 大地测量数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


获取或设置 GPS 测量模式。

Value: GPS 测量模式。

**Returns:**
java.lang.String
### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


获取或设置 GPS 测量模式。

Value: GPS 测量模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


获取或设置记录用于定位方法名称的 GPS 字符串。

Value: 记录用于定位方法名称的 GPS 字符串。

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


获取或设置记录用于定位方法名称的 GPS 字符串。

Value: 记录用于定位方法名称的 GPS 字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


获取或设置用于测量的 GPS 卫星。

值：用于测量的 GPS 卫星。

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


获取或设置用于测量的 GPS 卫星。

值：用于测量的 GPS 卫星。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


获取或设置 GPS 接收器移动的速度。

值：GPS 接收器移动的速度。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


获取或设置 GPS 接收器移动的速度。

值：GPS 接收器移动的速度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


获取或设置用于表示 GPS 接收器移动速度的单位。

值：用于表示 GPS 接收器移动速度的单位。

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


获取或设置用于表示 GPS 接收器移动速度的单位。

值：用于表示 GPS 接收器移动速度的单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


获取或设置图像记录时 GPS 接收器的状态。

值：记录图像时 GPS 接收器的状态。

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


获取或设置图像记录时 GPS 接收器的状态。

值：记录图像时 GPS 接收器的状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


获取或设置 GPS 时间（UTC，协调世界时）。

值：以 UTC（协调世界时）表示的 GPS 时间。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


获取或设置 GPS 时间（UTC，协调世界时）。

值：以 UTC（协调世界时）表示的 GPS 时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


获取或设置 GPS 接收器移动的方向。

值：GPS 接收器移动的方向。

**Returns:**
java.lang.String
### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


获取或设置 GPS 接收器移动的方向。

值：GPS 接收器移动的方向。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


获取或设置提供 GPS 接收器移动方向的参考。

值：给出 GPS 接收器移动方向的参考。

**Returns:**
java.lang.String
### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


获取或设置提供 GPS 接收器移动方向的参考。

值：给出 GPS 接收器移动方向的参考。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


获取或设置 GPS 版本标识符。

值：GPS 版本标识符。

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


获取或设置 GPS 版本标识符。

值：GPS 版本标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


获取或设置整体图像增益调整的程度。

值：整体图像增益调节的程度。

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


获取或设置整体图像增益调整的程度。

值：整体图像增益调节的程度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


获取或设置伽马值。

值：伽马值。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


获取或设置伽马值。

值：伽马值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


获取或设置 ISO 速度

值：ISO 速度。

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


获取或设置 ISO 速度

值：ISO 速度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


获取 ISO 速度值。

值：iso 速度值。

**Returns:**
long - iso 速度值。
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


设置 ISO 速度值。

值：iso 速度值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long | 该 iso 速度值。 |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。

值：在 ISO 12232 中定义的相机或输入设备的 ISO 速度纬度 yyy 值。

如果没有 ISOSpeed 和 ISOSpeedLatitudeZZZ，则不应记录此标签。

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。

值：在 ISO 12232 中定义的相机或输入设备的 ISO 速度纬度 yyy 值。

如果没有 ISOSpeed 和 ISOSpeedLatitudeZZZ，则不应记录此标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。

值：在 ISO 12232 中定义的相机或输入设备的 ISO 速度纬度 zzz 值。

如果没有 ISOSpeed 和 ISOSpeedLatitudeYYY，则不应记录此标签。

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。

值：在 ISO 12232 中定义的相机或输入设备的 ISO 速度纬度 zzz 值。

如果没有 ISOSpeed 和 ISOSpeedLatitudeYYY，则不应记录此标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


获取或设置摄影灵敏度。

值：摄影灵敏度。

**Returns:**
long
### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


获取或设置摄影灵敏度。

值：摄影灵敏度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


获取或设置图像唯一标识符。

值：图像唯一标识符。

**Returns:**
java.lang.String
### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


获取或设置图像唯一标识符。

值：图像唯一标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


获取或设置镜头制造商。

值：镜头制造商。

**Returns:**
java.lang.String
### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


获取或设置镜头制造商。

值：镜头制造商。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


获取或设置镜头型号。

值：镜头型号。

**Returns:**
java.lang.String
### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


获取或设置镜头型号。

值：镜头型号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


获取或设置镜头序列号。

值：镜头序列号。

**Returns:**
java.lang.String
### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


获取或设置镜头序列号。

值：镜头序列号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


获取或设置镜头规格。

值：镜头规格。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


获取或设置镜头规格。

值：镜头规格。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


获取或设置光源。

值：光源。

**Returns:**
int
### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


获取或设置光源。

值：光源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


获取制造商注释数据。

值：制造商备注数据。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


获取或设置制造商注释原始数据。

值：制造商备注原始数据。

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


获取或设置制造商注释原始数据。

值：制造商备注原始数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


获取制造商注释。

值：制造商备注。

**Returns:**
com.aspose.imaging.exif.MakerNote[] - 制造商备注。

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


获取或设置最大光圈值。

值：最大光圈值。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


获取或设置最大光圈值。

值：最大光圈值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


获取或设置测光模式。

值：测光模式。

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


获取或设置测光模式。

值：测光模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


获取或设置 ISO 14524 中指定的光电转换函数 (OECF)。

值：光电转换函数 (OECF)，在 ISO 14524 中指定。

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


获取或设置 ISO 14524 中指定的光电转换函数 (OECF)。

值：光电转换函数 (OECF)，在 ISO 14524 中指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


获取方向 [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation)。

值：方向。

**Returns:**
int - 方向。
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


设置方向 [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation)。

值：方向。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 方向。 |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


获取或设置像素 x 维度.

值：像素 X 维度。

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


获取或设置像素 x 维度.

值：像素 X 维度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


获取或设置像素 y 维度.

值：像素 Y 维度。

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


获取或设置像素 y 维度.

值：像素 Y 维度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


获取或设置所有 EXIF 标记（包括常用标记和 GPS 标记）.

值：EXIF 标签（包括通用和 GPS 标签）。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


获取或设置所有 EXIF 标记（包括常用标记和 GPS 标记）.

值：EXIF 标签（包括通用和 GPS 标签）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


获取或设置推荐的曝光指数.

值：推荐曝光指数。

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


获取或设置推荐的曝光指数.

值：推荐曝光指数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


获取或设置相关的声音文件.

值：相关声音文件。

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


获取或设置相关的声音文件.

值：相关声音文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


获取或设置饱和度.

值：饱和度。

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


获取或设置饱和度.

值：饱和度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


获取或设置场景捕获类型.

值：场景捕获类型。

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


获取或设置场景捕获类型.

值：场景捕获类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


获取或设置场景类型.

值：场景类型。

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


获取或设置场景类型.

值：场景类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


获取或设置感应方法.

值：感测方法。

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


获取或设置感应方法.

值：感测方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


获取或设置灵敏度类型.

值：灵敏度类型。

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


获取或设置灵敏度类型.

值：灵敏度类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


获取或设置锐度.

值：锐度。

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


获取或设置锐度.

值：锐度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


获取或设置快门速度值.

值：快门速度值。

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


获取或设置快门速度值.

值：快门速度值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


获取或设置空间频率响应.

值：空间频率响应。

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


获取或设置空间频率响应.

值：空间频率响应。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


获取或设置光谱灵敏度.

值：光谱灵敏度。

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


获取或设置光谱灵敏度.

值：光谱灵敏度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


获取标准输出灵敏度

值： 标准输出灵敏度。

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


设置标准输出灵敏度

值： 标准输出灵敏度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


获取或设置主体区域.

值： 主题区域。

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


获取或设置主体区域.

值： 主题区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


获取或设置主体距离.

值： 主题距离。

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


获取或设置主体距离.

值： 主题距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


获取或设置主体距离范围.

值： 主题距离范围。

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


获取或设置主体距离范围.

值： 主题距离范围。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


获取或设置主体位置.

值： 主题位置。

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


获取或设置主体位置.

值： 主题位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


获取或设置 DateTime 标记的秒分数.

值： DateTime 标记的秒分数。

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


获取或设置 DateTime 标记的秒分数.

值： DateTime 标记的秒分数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


获取或设置 DateTimeDigitized 标记的秒分数.

值： DateTimeDigitized 标记的秒分数。

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


获取或设置 DateTimeDigitized 标记的秒分数.

值： DateTimeDigitized 标记的秒分数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


获取或设置 DateTimeOriginal 标记的秒分数.

值： DateTimeOriginal 标记的秒分数。

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


获取或设置 DateTimeOriginal 标记的秒分数.

值： DateTimeOriginal 标记的秒分数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


获取或设置用户评论.

值： 用户评论。

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


获取或设置用户评论.

值： 用户评论。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


获取或设置白平衡.

值： 白平衡。

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


获取或设置白平衡.

值： 白平衡。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


获取或设置图像白点的色度。

值： 图像白点的色度。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


获取或设置图像白点的色度。

值： 图像白点的色度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


获取或设置属于公共部分的标签。此仅适用于 jpeg 图像，在 tiff 格式中使用 tiffOptions。

值： 公共部分标签。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


获取或设置属于公共部分的标签。此仅适用于 jpeg 图像，在 tiff 格式中使用 tiffOptions。

值： 公共部分标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


获取或设置仅属于 EXIF 部分的标签。

值： EXIF 部分标签。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


获取或设置仅属于 EXIF 部分的标签。

值： EXIF 部分标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


获取或设置仅属于 GPS 部分的标签。

值： GPS 标签。

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


获取或设置仅属于 GPS 部分的标签。

值： GPS 标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getThumbnail() {#getThumbnail--}
```
public final RasterImage getThumbnail()
```


获取缩略图。

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the thumbnail image.
### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.imaging.RasterImage-}
```
public final void setThumbnail(RasterImage value)
```


设置缩略图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.imaging/rasterimage) | 缩略图像。 |

### getXResolutionInt() {#getXResolutionInt--}
```
public final int getXResolutionInt()
```


获取 X 方向分辨率。

值： x 分辨率。

**Returns:**
int - x 分辨率。
### setXResolution(int value) {#setXResolution-int-}
```
public final void setXResolution(int value)
```


设置 X 方向分辨率。

值： x 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | x 分辨率。 |

### getYResolutionInt() {#getYResolutionInt--}
```
public final int getYResolutionInt()
```


获取 Y 方向分辨率。

值： y 分辨率。

**Returns:**
int - y 分辨率。
### setYResolution(int value) {#setYResolution-int-}
```
public final void setYResolution(int value)
```


设置 Y 方向分辨率。

值： y 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | y 分辨率。 |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


从容器中移除标签

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tagId | int | 要删除的标签标识符。 |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


获取标签值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | int | 标签键 [ExifProperties](../../com.aspose.imaging.exif/exifproperties)。 |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
