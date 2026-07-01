---
title: "ExifProperties"
second_title: "Aspose.Imaging for Java API 参考"
description: "Exif 标记列表。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Exif 标记列表。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ImageWidth](#ImageWidth) | 图像数据的列数，等于每行的像素数。 |
| [ImageLength](#ImageLength) | 图像数据的行数。 |
| [BitsPerSample](#BitsPerSample) | 每个图像组件的位数。 |
| [Compression](#Compression) | 用于图像数据的压缩方案。 |
| [PhotometricInterpretation](#PhotometricInterpretation) | 像素组成。 |
| [ImageDescription](#ImageDescription) | 提供图像标题的字符字符串。 |
| [Make](#Make) | 记录设备的制造商。 |
| [Model](#Model) | 设备的型号名称或型号编号。 |
| [Orientation](#Orientation) | 以行列方式查看的图像方向。 |
| [SamplesPerPixel](#SamplesPerPixel) | 每个像素的组件数。 |
| [XResolution](#XResolution) | 在 ImageWidth 方向上每个分辨率单位的像素数。 |
| [YResolution](#YResolution) | 在 ImageLength 方向上，每个 ResolutionUnit 的像素数量。 |
| [PlanarConfiguration](#PlanarConfiguration) | 指示像素组件是以块状还是平面格式记录的。 |
| [ResolutionUnit](#ResolutionUnit) | 用于测量 XResolution 和 YResolution 的单位。 |
| [TransferFunction](#TransferFunction) | 图像的传输函数，以表格形式描述。 |
| [Software](#Software) | 此标签记录用于生成图像的相机或图像输入设备的软件或固件的名称和版本。 |
| [DateTime](#DateTime) | 图像创建的日期和时间。 |
| [Artist](#Artist) | 此标签记录相机所有者、摄影师或图像创建者的名称。 |
| [WhitePoint](#WhitePoint) | 图像白点的色度。 |
| [PrimaryChromaticities](#PrimaryChromaticities) | 图像三原色的色度。 |
| [YCbCrCoefficients](#YCbCrCoefficients) | 从 RGB 转换到 YCbCr 图像数据的矩阵系数。 |
| [YCbCrSubSampling](#YCbCrSubSampling) | 相对于亮度分量的色度分量采样比率。 |
| [YCbCrPositioning](#YCbCrPositioning) | 相对于亮度分量的色度分量位置。 |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | 参考黑点值和参考白点值。 |
| [Copyright](#Copyright) | 版权信息。 |
| [ExposureTime](#ExposureTime) | 曝光时间，以秒为单位。 |
| [FNumber](#FNumber) | F 值。 |
| [ExposureProgram](#ExposureProgram) | 相机在拍摄时用于设置曝光的程序类。 |
| [SpectralSensitivity](#SpectralSensitivity) | 指示所使用相机每个通道的光谱灵敏度。 |
| [PhotographicSensitivity](#PhotographicSensitivity) | 指示相机或输入设备在 ISO 12232 中规定的 ISO 速度和 ISO 维度。 |
| [OECF](#OECF) | 指示 ISO 14524 中规定的光电转换函数 (OECF)。 |
| [ExifVersion](#ExifVersion) | Exif 版本。 |
| [DateTimeOriginal](#DateTimeOriginal) | 原始图像数据生成的日期和时间。 |
| [DateTimeDigitized](#DateTimeDigitized) | 数字化的日期时间。 |
| [ComponentsConfiguration](#ComponentsConfiguration) | 组件配置。 |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | 特定于压缩数据；说明每像素的压缩位数。 |
| [ShutterSpeedValue](#ShutterSpeedValue) | 快门速度值。 |
| [ApertureValue](#ApertureValue) | 镜头光圈值。 |
| [BrightnessValue](#BrightnessValue) | 亮度值。 |
| [ExposureBiasValue](#ExposureBiasValue) | 曝光补偿值。 |
| [MaxApertureValue](#MaxApertureValue) | 最大光圈值。 |
| [SubjectDistance](#SubjectDistance) | 到主体的距离，以米为单位。 |
| [MeteringMode](#MeteringMode) | 测光模式。 |
| [LightSource](#LightSource) | 光源类型。 |
| [Flash](#Flash) | 指示拍摄时闪光灯的状态。 |
| [FocalLength](#FocalLength) | 镜头的实际焦距，单位为毫米。 |
| [SubjectArea](#SubjectArea) | 此标签指示整体场景中主体的位置信息和区域。 |
| [MakerNote](#MakerNote) | 供 Exif 编写器制造商记录任意所需信息的标签。 |
| [UserComment](#UserComment) | 供 Exif 用户在图像上写入关键字或注释的标签，除了 ImageDescription 中的内容，并且不受 ImageDescription 标签字符编码限制。 |
| [SubsecTime](#SubsecTime) | 用于记录 DateTime 标签的秒分数的标签。 |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | 用于记录 DateTimeOriginal 标签的秒分数的标签。 |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | 用于记录 DateTimeDigitized 标签的秒分数的标签。 |
| [FlashpixVersion](#FlashpixVersion) | FPXR 文件支持的 Flashpix 格式版本。 |
| [ColorSpace](#ColorSpace) | 颜色空间信息标签（ColorSpace）始终记录为颜色空间指示符。 |
| [RelatedSoundFile](#RelatedSoundFile) | 相关的音频文件。 |
| [FlashEnergy](#FlashEnergy) | 指示拍摄时的闪光能量，单位为束烛光功率秒（BCPS）。 |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | 此标签记录相机或输入设备的空间频率表以及在图像宽度、图像高度和对角方向上的 SFR 值，符合 ISO 12233 的规定。 |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | 指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像宽度（X）方向的像素数量。 |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | 指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像高度（Y）方向的像素数量。 |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | 指示用于测量 FocalPlaneXResolution 和 FocalPlaneYResolution 的单位。 |
| [SubjectLocation](#SubjectLocation) | 指示场景中主体的位置。 |
| [ExposureIndex](#ExposureIndex) | 指示在捕获图像时相机或输入设备上选择的曝光指数。 |
| [SensingMethod](#SensingMethod) | 指示相机或输入设备上的图像传感器类型。 |
| [FileSource](#FileSource) | 文件来源。 |
| [SceneType](#SceneType) | 指示场景类型。 |
| [CFAPattern](#CFAPattern) | 指示在使用单芯片彩色区域传感器时图像传感器的颜色滤光阵列（CFA）几何图案。 |
| [CustomRendered](#CustomRendered) | 此标签指示对图像数据使用特殊处理，例如针对输出的渲染。 |
| [ExposureMode](#ExposureMode) | 此标签指示拍摄图像时设置的曝光模式。 |
| [WhiteBalance](#WhiteBalance) | 此标签指示拍摄图像时设置的白平衡模式。 |
| [DigitalZoomRatio](#DigitalZoomRatio) | 此标签指示拍摄图像时的数字变焦比例。 |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | 此标签指示假设为35mm胶片相机时的等效焦距，单位为毫米。 |
| [SceneCaptureType](#SceneCaptureType) | 此标签指示拍摄的场景类型。 |
| [GainControl](#GainControl) | 此标签指示整体图像增益调整的程度。 |
| [Contrast](#Contrast) | 此标签指示拍摄图像时相机应用的对比度处理方向。 |
| [Saturation](#Saturation) | 此标签指示拍摄图像时相机应用的饱和度处理方向。 |
| [Sharpness](#Sharpness) | 此标签指示拍摄图像时相机应用的锐度处理方向 |
| [DeviceSettingDescription](#DeviceSettingDescription) | 此标签指示特定相机型号的拍摄条件信息。 |
| [SubjectDistanceRange](#SubjectDistanceRange) | 此标签指示到主体的距离。 |
| [ImageUniqueID](#ImageUniqueID) | 图像唯一标识。 |
| [GPSVersionID](#GPSVersionID) | 指示 GPSInfoIFD 的版本。 |
| [GPSLatitudeRef](#GPSLatitudeRef) | 指示纬度是北纬还是南纬。 |
| [GPSLatitude](#GPSLatitude) | 指示纬度。 |
| [GPSLongitudeRef](#GPSLongitudeRef) | 指示经度是东经还是西经。 |
| [GPSLongitude](#GPSLongitude) | 指示经度。 |
| [GPSAltitudeRef](#GPSAltitudeRef) | 指示用作参考高度的海拔。 |
| [GPSAltitude](#GPSAltitude) | 指示基于 GPSAltitudeRef 中参考的海拔高度。 |
| [GPSTimestamp](#GPSTimestamp) | 指示时间为 UTC（协调世界时）。 |
| [GPSSatellites](#GPSSatellites) | 指示用于测量的 GPS 卫星。 |
| [GPSStatus](#GPSStatus) | 指示记录图像时 GPS 接收器的状态。 |
| [GPSMeasureMode](#GPSMeasureMode) | 指示 GPS 测量模式。 |
| [GPSDOP](#GPSDOP) | 指示 GPS DOP（数据精度等级）。 |
| [GPSSpeedRef](#GPSSpeedRef) | 指示用于表示 GPS 接收器移动速度的单位。 |
| [GPSSpeed](#GPSSpeed) | 指示 GPS 接收器移动的速度。 |
| [GPSTrackRef](#GPSTrackRef) | 指示用于给出 GPS 接收器移动方向的参考。 |
| [GPSTrack](#GPSTrack) | 指示 GPS 接收器移动的方向。 |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | 指示在捕获图像时给出图像方向的参考。 |
| [GPSImgDirection](#GPSImgDirection) | 指示捕获时图像的方向。 |
| [GPSMapDatum](#GPSMapDatum) | 指示 GPS 接收器使用的测地测量数据。 |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | 指示目标点的纬度是北纬还是南纬。 |
| [GPSDestLatitude](#GPSDestLatitude) | 指示目标点的纬度。 |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | 指示目标点的经度是东经还是西经。 |
| [GPSDestLongitude](#GPSDestLongitude) | 指示目标点的经度。 |
| [GPSDestBearingRef](#GPSDestBearingRef) | 指示用于给出指向目标点方位的参考。 |
| [GPSDestBearing](#GPSDestBearing) | 指示指向目标点的方位角。 |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | 指示用于表示到目标点距离的单位。 |
| [GPSDestDistance](#GPSDestDistance) | 指示到目标点的距离。 |
| [GPSProcessingMethod](#GPSProcessingMethod) | 记录用于定位的方法名称的字符字符串。 |
| [GPSAreaInformation](#GPSAreaInformation) | 记录 GPS 区域名称的字符字符串。 |
| [GPSDateStamp](#GPSDateStamp) | 记录相对于 UTC（协调世界时）的日期和时间信息的字符字符串。 |
| [GPSDifferential](#GPSDifferential) | 指示是否对 GPS 接收器应用差分校正。 |
| [StripOffsets](#StripOffsets) | 对于每个条带，指示该条带的字节偏移量。 |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | JPEG 压缩缩略图数据的起始字节 (SOI) 的偏移量。 |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | JPEG 压缩缩略图数据的字节数。 |
| [ExifIfdPointer](#ExifIfdPointer) | 指向 Exif IFD 的指针。 |
| [GPSIfdPointer](#GPSIfdPointer) | gps ifd 指针。 |
| [RowsPerStrip](#RowsPerStrip) | 每个条带的行数。 |
| [StripByteCounts](#StripByteCounts) | 每个条带的总字节数。 |
| [PixelXDimension](#PixelXDimension) | 特定于压缩数据的信息。 |
| [PixelYDimension](#PixelYDimension) | 特定于压缩数据的信息。 |
| [Gamma](#Gamma) | 伽马值 |
| [SensitivityType](#SensitivityType) | 摄影感光度类型 |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | 指示相机的标准输出感光度 |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | 指示推荐的曝光指数 |
| [ISOSpeed](#ISOSpeed) | 关于 ISO 12232 中定义的 ISO 速度值的信息 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | 此标签指示 ISO 12232 中定义的 ISO 速度纬度 yyy 值 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | 此标签指示 ISO 12232 中定义的 ISO 速度纬度 zzz 值 |
| [CameraOwnerName](#CameraOwnerName) | 包含相机所有者姓名 |
| [BodySerialNumber](#BodySerialNumber) | 包含相机机身序列号 |
| [LensMake](#LensMake) | 此标签记录镜头制造商 |
| [LensModel](#LensModel) | 此标签记录 lens\`s 的型号名称和型号编号 |
| [LensSerialNumber](#LensSerialNumber) | 此标签记录可更换镜头的序列号 |
| [LensSpecification](#LensSpecification) | 此标签记录最小焦距、最大焦距、最小焦距对应的最小光圈值以及最大焦距对应的最小光圈值 |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


图像数据的列数，等于每行的像素数。

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


图像数据的行数。

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


每个图像组件的位数。根据本标准，图像的每个组件为 8 位，因此此标签的值为 8。

### Compression {#Compression}
```
public static final int Compression
```


用于图像数据的压缩方案。当主图像采用 JPEG 压缩时，此标识不是必需的，会被省略。

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


像素组成。

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


提供图像标题的字符字符串。它可以是诸如“1988 公司野餐”等评论。

### Make {#Make}
```
public static final int Make
```


记录设备的制造商。这是生成图像的 DSC、扫描仪、视频数字化仪或其他设备的制造商。如果该字段留空，则视为未知。

### Model {#Model}
```
public static final int Model
```


设备的型号名称或型号编号。这是生成图像的 DSC、扫描仪、视频数字化仪或其他设备的型号名称或编号。如果该字段留空，则视为未知。

### Orientation {#Orientation}
```
public static final int Orientation
```


以行列方式查看的图像方向。

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


每像素的组件数量。由于本标准适用于 RGB 和 YCbCr 图像，此标签的值设为 3。

### XResolution {#XResolution}
```
public static final int XResolution
```


在 ImageWidth 方向上每个 ResolutionUnit 的像素数。当图像分辨率未知时，指定为 72 [dpi]。

### YResolution {#YResolution}
```
public static final int YResolution
```


在 ImageLength 方向上每个 ResolutionUnit 的像素数。指定的值与 XResolution 相同。

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


指示像素分量是以块状（chunky）还是平面（planar）格式记录。如果此字段不存在，则假定 TIFF 默认值 1（块状）。

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


用于测量 XResolution 和 YResolution 的单位。XResolution 和 YResolution 使用相同的单位。如果图像分辨率未知，则指定为 2（英寸）。

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


图像的传递函数，以表格形式描述。通常不需要此标签，因为颜色空间已在颜色空间信息的 ColorSpace 标签中指定。

### Software {#Software}
```
public static final int Software
```


此标签记录用于生成图像的相机或图像输入设备的软件或固件的名称和版本。未指定详细格式，但建议遵循下方示例。字段留空时视为未知。

### DateTime {#DateTime}
```
public static final int DateTime
```


图像创建的日期和时间。在 Exif 标准中，它是文件被更改的日期和时间。

### Artist {#Artist}
```
public static final int Artist
```


此标签记录相机所有者、摄影师或图像创建者的名称。未指定详细格式，但建议按照下方示例编写，以便互操作性。字段留空时视为未知。（例如：“Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James”）

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


图像白点的色度。通常不需要此标签，因为颜色空间已在颜色空间信息的 ColorSpace 标签中指定。

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


图像三原色的色度。通常不需要此标签，因为颜色空间已在颜色空间信息的 ColorSpace 标签中指定。

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


从 RGB 转换到 YCbCr 图像数据的矩阵系数。

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


相对于亮度分量的色度分量采样比率。

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


色度分量相对于亮度分量的位置。此字段仅针对 JPEG 压缩数据或未压缩的 YCbCr 数据指定。TIFF 默认值为 1（居中）；但当 Y:Cb:Cr = 4:2:2 时，本标准建议使用 2（并列）来记录数据，以提升在电视系统上观看时的图像质量。当此字段不存在时，读取器应假定 TIFF 默认值。对于 Y:Cb:Cr = 4:2:0 的情况，推荐使用 TIFF 默认值（居中）。如果读取器无法同时支持两种 YCbCrPositioning，则应无论该字段的值如何都遵循 TIFF 默认值。最好读取器能够支持居中和并列两种定位方式。

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


参考黑点值和参考白点值。TIFF 未给出默认值，但此处提供以下值作为默认。颜色空间在颜色空间信息标签中声明，默认值为在这些条件下提供最佳图像特性的值。

### Copyright {#Copyright}
```
public static final int Copyright
```


版权信息。在本标准中，此标签用于指示摄影师和编辑的版权。它是对图像拥有权利的个人或组织的版权声明。应在此字段中写入包括日期和权利的互操作性版权声明，例如：“Copyright, John Smith, 19xx. All rights reserved.” 在本标准中，该字段记录摄影师和编辑的版权，每个版权分别记录在声明的不同部分。当摄影师和编辑的版权有明确区分时，按摄影师后编辑的顺序书写，并以 NULL 分隔（由于声明末尾也有一个 NULL，因此有两个 NULL 代码）。仅提供摄影师版权时，以一个 NULL 代码结束。仅提供编辑版权时，摄影师版权部分包含一个空格后跟终止的 NULL 代码，然后给出编辑版权。字段留空时视为未知。

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


曝光时间，以秒为单位。

### FNumber {#FNumber}
```
public static final int FNumber
```


F 值。

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


相机在拍摄时用于设置曝光的程序类。

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


指示所使用相机每个通道的光谱灵敏度。

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


指示相机或输入设备在 ISO 12232 中规定的 ISO 速度和 ISO 维度。

### OECF {#OECF}
```
public static final int OECF
```


指示 ISO 14524 中规定的光电转换函数 (OECF)。

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


Exif 版本。

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


原始图像数据生成的日期和时间。

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


数字化的日期时间。

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


组件配置。

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


特定于压缩数据；说明每像素的压缩位数。

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


快门速度值。

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


镜头光圈值。

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


亮度值。

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


曝光补偿值。

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


最大光圈值。

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


到主体的距离，以米为单位。

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


测光模式。

### LightSource {#LightSource}
```
public static final int LightSource
```


光源类型。

### Flash {#Flash}
```
public static final int Flash
```


指示拍摄时闪光灯的状态。

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


镜头的实际焦距，单位为毫米。

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


此标签指示整体场景中主体的位置信息和区域。

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


供 Exif 编写器制造商记录任意信息的标签。内容由制造商自行决定，但此标签不应用于其预定目的之外的任何用途。

### UserComment {#UserComment}
```
public static final int UserComment
```


供 Exif 用户在图像上写入关键字或注释的标签，除了 ImageDescription 中的内容，并且不受 ImageDescription 标签字符编码限制。

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


用于记录 DateTime 标签的秒分数的标签。

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


用于记录 DateTimeOriginal 标签的秒分数的标签。

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


用于记录 DateTimeDigitized 标签的秒分数的标签。

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


FPXR 文件支持的 Flashpix 格式版本。

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


颜色空间信息标签（ColorSpace）始终记录为颜色空间指示符。

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


相关的音频文件。

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


指示拍摄时的闪光能量，单位为束烛光功率秒（BCPS）。

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


此标签记录相机或输入设备的空间频率表以及在图像宽度、图像高度和对角方向上的 SFR 值，符合 ISO 12233 的规定。

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像宽度（X）方向的像素数量。

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像高度（Y）方向的像素数量。

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


指示用于测量 FocalPlaneXResolution 和 FocalPlaneYResolution 的单位。该值与 ResolutionUnit 相同。

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


指示场景中主体的所在位置。此标签的值表示主体中心像素相对于左边缘的位置，未进行 Rotation 标签所指定的旋转处理之前。

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


指示在捕获图像时相机或输入设备上选择的曝光指数。

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


指示相机或输入设备上的图像传感器类型。

### FileSource {#FileSource}
```
public static final int FileSource
```


文件来源。

### SceneType {#SceneType}
```
public static final int SceneType
```


指示场景类型。如果是 DSC 记录的图像，则此标签值必须始终设为 1，表示图像是直接拍摄的。

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


指示在使用单芯片彩色区域传感器时图像传感器的颜色滤光阵列 (CFA) 几何图案。该信息并不适用于所有感测方法。

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


此标签指示对图像数据进行特殊处理，例如针对输出的渲染。当执行特殊处理时，读取器应禁用或尽量减少后续的任何处理。

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


此标签指示拍摄时设置的曝光模式。在自动包围曝光模式下，相机会以不同的曝光设置拍摄同一场景的一系列帧。

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


此标签指示拍摄图像时设置的白平衡模式。

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


此标签指示拍摄时的数码变焦比例。如果记录值的分子为 0，则表示未使用数码变焦。

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


此标签指示以 35mm 胶片相机为基准的等效焦距，单位为毫米。值为 0 表示焦距未知。请注意，此标签不同于 FocalLength 标签。

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


此标签指示拍摄的场景类型。它也可用于记录图像拍摄时的模式。

### GainControl {#GainControl}
```
public static final int GainControl
```


此标签指示整体图像增益调整的程度。

### Contrast {#Contrast}
```
public static final int Contrast
```


此标签指示拍摄图像时相机应用的对比度处理方向。

### Saturation {#Saturation}
```
public static final int Saturation
```


此标签指示拍摄图像时相机应用的饱和度处理方向。

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


此标签指示拍摄图像时相机应用的锐度处理方向

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


此标签指示特定相机型号的拍摄条件信息。该标签仅用于在读取器中指示拍摄条件。

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


此标签指示到主体的距离。

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


图像唯一标识。

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


指示 GPSInfoIFD 的版本。

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


指示纬度是北纬还是南纬。

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


指示纬度。纬度以三个 RATIONAL 值分别表示度、分、秒。如果以度、分、秒表示，典型格式为 dd/1,mm/1,ss/1。当使用度和分且例如分的小数部分保留两位小数时，格式为 dd/1,mmmm/100,0/1。

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


指示经度是东经还是西经。

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


指示经度。经度以三个 RATIONAL 值表示，分别给出度、分和秒。如果经度以度、分、秒表示，典型格式为 ddd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为 ddd/1,mmmm/100,0/1。

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


指示用作参考高度的海拔。如果参考为海平面且海拔高于海平面，则给出 0。如果海拔低于海平面，则给出 1，并在 GPSAltitude 标记中以绝对值表示海拔。

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


指示基于 GPSAltitudeRef 中参考的海拔。海拔以一个 RATIONAL 值表示。参考单位为米。

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


指示时间为 UTC（协调世界时）。TimeStamp 以三个 RATIONAL 值表示，分别给出小时、分钟和秒。

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


指示用于测量的 GPS 卫星。此标记可用于描述卫星数量、其 ID 编号、仰角、方位角、信噪比以及其他 ASCII 表示的信息。格式未指定。如果 GPS 接收器无法进行测量，则该标记的值应设为 NULL。

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


指示记录图像时 GPS 接收器的状态。

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


指示 GPS 测量模式。- 二维或三维。

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


指示 GPS DOP（数据精度等级）。在二维测量时写入 HDOP 值，三维测量时写入 PDOP 值。

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


指示用于表示 GPS 接收器移动速度的单位。'K'、'M' 和 'N' 分别代表公里每小时、英里每小时和节。

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


指示 GPS 接收器移动的速度。

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


指示给出 GPS 接收器移动方向的参考。'T' 表示真方向，'M' 表示磁方向。

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


指示 GPS 接收器的移动方向。取值范围为 0.00 到 359.99。

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


指示拍摄图像时方向的参考。'T' 表示真方向，'M' 表示磁方向。

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


指示拍摄时图像的方向。取值范围为 0.00 到 359.99。

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


指示 GPS 接收器使用的测地测量数据。

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


指示目的地点的纬度是北纬还是南纬。ASCII 值 'N' 表示北纬，'S' 表示南纬。

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


指示目的地点的纬度。纬度以三个 RATIONAL 值表示，分别给出度、分和秒。如果纬度以度、分、秒表示，典型格式为 dd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为 dd/1,mmmm/100,0/1。

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


指示目的地点的经度是东经还是西经。ASCII 'E' 表示东经，'W' 表示西经。

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


指示目的地点的经度。经度以三个 RATIONAL 值表示，分别给出度、分和秒。如果经度以度、分、秒表示，典型格式为 ddd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为 ddd/1,mmmm/100,0/1。

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


指示用于给出指向目的地点的方位参考。'T' 表示真方向，'M' 表示磁方向。

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


指示指向目的地点的方位。取值范围为 0.00 到 359.99。

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


指示用于表示到目的地点距离的单位。'K'、'M' 和 'N' 分别代表公里、英里和节。

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


指示到目标点的距离。

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


记录用于定位的方式名称的字符字符串。第一个字节指示使用的字符编码，随后是方法名称。

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


记录 GPS 区域名称的字符字符串。第一个字节指示使用的字符编码，随后是 GPS 区域的名称。

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


记录相对于 UTC（协调世界时）的日期和时间信息的字符字符串。格式为 YYYY:MM:DD。

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


指示是否对 GPS 接收器应用差分校正。

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


对于每个条带，给出该条带的字节偏移。建议选择使条带字节数不超过 64 KBytes。Aux 标记。

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


指向 JPEG 压缩缩略图数据起始字节 (SOI) 的偏移。此偏移不用于主图像的 JPEG 数据。

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


JPEG 压缩缩略图数据的字节数。此数据不用于主图像的 JPEG 数据。JPEG 缩略图不分段，而是从 SOI 到 EOI 连续记录为 JPEG 位流。Appn 和 COM 标记不应记录。压缩缩略图必须记录在不超过 64 KBytes 的范围内，包括所有在 APP1 中记录的其他数据。

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


指向 Exif IFD 的指针。互操作性，Exif IFD 的结构与 TIFF 中指定的 IFD 相同。然而，通常情况下，它不像 TIFF 那样包含图像数据。

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


gps ifd 指针。

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


每条带的行数。这是图像在被划分为多条带时，每条带中图像的行数。

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


每个条带的总字节数。

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


特定于压缩数据的信息。当记录压缩文件时，无论是否存在填充数据或重新启动标记，都应在此标签中记录有效的图像宽度。

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


特定于压缩数据的信息。当记录压缩文件时，应在此标签中记录有效的图像高度。

### Gamma {#Gamma}
```
public static final int Gamma
```


伽马值

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


摄影感光度类型

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


指示相机的标准输出感光度

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


指示推荐的曝光指数

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


关于 ISO 12232 中定义的 ISO 速度值的信息

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


此标签指示 ISO 12232 中定义的 ISO 速度纬度 yyy 值

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


此标签指示 ISO 12232 中定义的 ISO 速度纬度 zzz 值

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


包含相机所有者姓名

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


包含相机机身序列号

### LensMake {#LensMake}
```
public static final int LensMake
```


此标签记录镜头制造商

### LensModel {#LensModel}
```
public static final int LensModel
```


此标签记录 lens\`s 的型号名称和型号编号

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


此标签记录可更换镜头的序列号

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


此标签记录最小焦距、最大焦距、最小焦距对应的最小光圈值以及最大焦距对应的最小光圈值

