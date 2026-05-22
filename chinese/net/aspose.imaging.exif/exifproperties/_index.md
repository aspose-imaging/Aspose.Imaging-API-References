---
title: "Enum ExifProperties"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Exif.ExifProperties 枚举。Exif 标签列表"
type: docs
weight: 1090
url: /zh/net/aspose.imaging.exif/exifproperties/
---
## ExifProperties enumeration

Exif 标记列表

```csharp
public enum ExifProperties : ushort
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ImageWidth | `256` | 图像数据的列数，等于每行的像素数。 |
| ImageLength | `257` | 图像数据的行数。 |
| BitsPerSample | `258` | 每个图像组件的位数。在此标准中，每个组件为 8 位，因此此标签的值为 8。 |
| Compression | `259` | 用于图像数据的压缩方案。当主图像采用 JPEG 压缩时，此指定不是必需的，因而被省略。 |
| PhotometricInterpretation | `262` | 像素组成。 |
| ImageDescription | `270` | 提供图像标题的字符字符串。它可能是诸如“1988 公司野餐”等评论。 |
| Make | `271` | 记录设备的制造商。这是生成图像的 DSC、扫描仪、视频数字化仪或其他设备的制造商。当该字段留空时，视为未知。 |
| Model | `272` | 设备的型号名称或型号编号。这是生成图像的 DSC、扫描仪、视频数字化仪或其他设备的型号名称或编号。当该字段留空时，视为未知。 |
| Orientation | `274` | 以行列方式查看的图像方向。 |
| SamplesPerPixel | `277` | 每像素的组件数量。由于此标准适用于 RGB 和 YCbCr 图像，此标签的取值为 3。 |
| XResolution | `282` | 在 ImageWidth 方向上每个 ResolutionUnit 的像素数。当图像分辨率未知时，指定为 72 [dpi]。 |
| YResolution | `283` | 在 ImageLength 方向上每个 ResolutionUnit 的像素数。指定的值与 XResolution 相同。 |
| PlanarConfiguration | `284` | 指示像素组件是以块状（chunky）还是平面（planar）格式记录。如果此字段不存在，则假定 TIFF 默认值为 1（块状）。 |
| ResolutionUnit | `296` | 用于测量 XResolution 和 YResolution 的单位。XResolution 和 YResolution 使用相同的单位。如果图像分辨率未知，则指定为 2（英寸）。 |
| TransferFunction | `301` | 图像的传递函数，以表格形式描述。通常此标签不是必需的，因为颜色空间已在颜色空间信息的 ColorSpace 标签中指定。 |
| Software | `305` | 此标签记录用于生成图像的相机或图像输入设备的软件或固件的名称和版本。未指定详细格式，但建议遵循下面示例。当字段留空时，视为未知。 |
| DateTime | `306` | 图像创建的日期和时间。在 Exif 标准中，它是文件更改的日期和时间。 |
| Artist | `315` | 此标签记录相机所有者、摄影师或图像创建者的姓名。未指定详细格式，但建议按照下面示例编写信息，以便于互操作性。当字段留空时，视为未知。例如）"Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| WhitePoint | `318` | 图像白点的色度。通常此标签不是必需的，因为颜色空间已在颜色空间信息的 ColorSpace 标签中指定。 |
| PrimaryChromaticities | `319` | 图像三原色的色度。通常此标签不是必需的，因为颜色空间已在颜色空间信息的 ColorSpace 标签中指定。 |
| YCbCrCoefficients | `529` | 从 RGB 到 YCbCr 图像数据的矩阵系数。 |
| YCbCrSubSampling | `530` | 色度分量相对于亮度分量的采样比例。 |
| YCbCrPositioning | `531` | 色度分量相对于亮度分量的位置。此字段仅针对 JPEG 压缩数据或未压缩的 YCbCr 数据指定。TIFF 默认值为 1（居中）；但当 Y:Cb:Cr = 4:2:2 时，本标准建议使用 2（并列）来记录数据，以提高在电视系统上观看时的图像质量。当此字段不存在时，读取器应假定 TIFF 默认值。对于 Y:Cb:Cr = 4:2:0，推荐使用 TIFF 默认值（居中）。如果读取器无法同时支持两种 YCbCrPositioning，则应无论该字段的值如何都遵循 TIFF 默认值。最好读取器能够支持居中和并列两种定位。 |
| ReferenceBlackWhite | `532` | 参考黑点值和参考白点值。TIFF 未给出默认值，但此处提供以下值作为默认。颜色空间在颜色空间信息标签中声明，默认值为在这些条件下提供最佳图像特性的值，以实现互操作性。 |
| Copyright | `33432` | 版权信息。在本标准中，此标签用于指示摄影师和编辑的版权。它是对声称对图像拥有权利的个人或组织的版权声明。互操作性版权声明应包括日期和权利，并写入此字段；例如，"Copyright, John Smith, 19xx. All rights reserved."。在本标准中，该字段记录摄影师和编辑的版权，分别记录在声明的不同部分。当摄影师和编辑的版权有明确区分时，按摄影师在前、编辑在后的顺序书写，并以 NULL 分隔（由于声明也以 NULL 结束，此情况下有两个 NULL 代码）。仅提供摄影师版权时，以一个 NULL 代码结束。仅提供编辑版权时，摄影师版权部分为一个空格加终止的 NULL 代码，然后给出编辑版权。字段留空时，视为未知。 |
| ExposureTime | `33434` | 曝光时间，以秒为单位。 |
| FNumber | `33437` | 光圈值（F 值）。 |
| ExposureProgram | `34850` | 相机在拍摄时用于设置曝光的程序类别。 |
| SpectralSensitivity | `34852` | 指示所使用相机每个通道的光谱灵敏度。 |
| PhotographicSensitivity | `34855` | 指示相机或输入设备的 ISO 速度和 ISO 维度，依据 ISO 12232 标准。 |
| OECF | `34856` | 指示 ISO 14524 中规定的光电转换函数（OECF）。 |
| ExifVersion | `36864` | Exif 版本。 |
| DateTimeOriginal | `36867` | 原始图像数据生成的日期和时间。 |
| DateTimeDigitized | `36868` | 数字化的日期时间。 |
| ComponentsConfiguration | `37121` | 组件的配置。 |
| CompressedBitsPerPixel | `37122` | 特定于压缩数据；说明每像素的压缩位数。 |
| ShutterSpeedValue | `37377` | 快门速度值。 |
| ApertureValue | `37378` | 镜头光圈值。 |
| BrightnessValue | `37379` | 亮度值。 |
| ExposureBiasValue | `37380` | 曝光补偿值。 |
| MaxApertureValue | `37381` | 最大光圈值。 |
| SubjectDistance | `37382` | 到主体的距离，以米为单位。 |
| MeteringMode | `37383` | 测光模式。 |
| LightSource | `37384` | 光源类型。 |
| Flash | `37385` | 指示拍摄时闪光灯的状态。 |
| FocalLength | `37386` | 镜头的实际焦距，单位为毫米。 |
| SubjectArea | `37396` | 此标签指示整体场景中主体的位置信息和区域。 |
| MakerNote | `37500` | 供 Exif 编写器制造商记录任意所需信息的标签。内容由制造商自行决定，但此标签不应用于其预定用途之外的任何其他用途。 |
| UserComment | `37510` | 供 Exif 用户在图像上写入关键字或注释的标签，除 ImageDescription 中的内容外，并且不受 ImageDescription 标签字符编码限制。 |
| SubsecTime | `37520` | 用于记录 DateTime 标签的秒分数的标签。 |
| SubsecTimeOriginal | `37521` | 用于记录 DateTimeOriginal 标签的秒分数的标签。 |
| SubsecTimeDigitized | `37522` | 用于记录 DateTimeDigitized 标签的秒分数的标签。 |
| FlashpixVersion | `40960` | FPXR 文件支持的 Flashpix 格式版本。 |
| ColorSpace | `40961` | 颜色空间信息标签（ColorSpace）始终记录为颜色空间指定符。 |
| RelatedSoundFile | `40964` | 相关的音频文件。 |
| FlashEnergy | `41483` | 指示拍摄时的闪光能量，单位为光束烛光功率秒（BCPS）。 |
| SpatialFrequencyResponse | `41484` | 此标签记录相机或输入设备的空间频率表和 SFR 值，分别沿图像宽度、图像高度和对角线方向，依据 ISO 12233 标准。 |
| FocalPlaneXResolution | `41486` | 指示相机焦平面上每个焦平面分辨率单位在图像宽度（X）方向的像素数。 |
| FocalPlaneYResolution | `41487` | 指示相机焦平面上每个焦平面分辨率单位在图像高度（Y）方向的像素数。 |
| FocalPlaneResolutionUnit | `41488` | 指示用于测量 FocalPlaneXResolution 和 FocalPlaneYResolution 的单位。此值与 ResolutionUnit 相同。 |
| SubjectLocation | `41492` | 指示场景中主体的位置信息。此标签的值表示相对于左边缘的主体中心像素位置，在根据 Rotation 标签进行旋转处理之前。 |
| ExposureIndex | `41493` | 指示在捕获图像时相机或输入设备所选择的曝光指数。 |
| SensingMethod | `41495` | 指示相机或输入设备的图像传感器类型。 |
| FileSource | `41728` | 文件来源。 |
| SceneType | `41729` | 指示场景类型。如果是 DSC 记录的图像，此标签值应始终设为 1，表示图像是直接拍摄的。 |
| CFAPattern | `41730` | 指示在使用单芯片彩色区域传感器时图像传感器的彩色滤光阵列（CFA）几何图案。该信息并不适用于所有感测方式。 |
| CustomRendered | `41985` | 此标签指示对图像数据使用特殊处理，例如针对输出的渲染。当进行特殊处理时，读取器应禁用或尽量减少后续的任何处理。 |
| ExposureMode | `41986` | 此标签指示拍摄时设置的曝光模式。在自动包围曝光模式下，相机会以不同的曝光设置拍摄同一场景的多帧图像。 |
| WhiteBalance | `41987` | 此标签指示拍摄时设置的白平衡模式。 |
| DigitalZoomRatio | `41988` | 此标签指示拍摄时的数码变焦比例。如果记录值的分子为 0，则表示未使用数码变焦。 |
| FocalLengthIn35MmFilm | `41989` | 此标签指示以 35mm 胶片相机为基准的等效焦距，单位为毫米。值为 0 表示焦距未知。请注意，此标签不同于 FocalLength 标签。 |
| SceneCaptureType | `41990` | 此标签指示拍摄的场景类型。它也可用于记录拍摄图像的模式。 |
| GainControl | `41991` | 此标签指示整体图像增益调整的程度。 |
| Contrast | `41992` | 此标签指示拍摄时相机所施加的对比度处理方向。 |
| Saturation | `41993` | 此标签指示拍摄时相机所施加的饱和度处理方向。 |
| Sharpness | `41994` | 此标签指示拍摄时相机所施加的锐度处理方向。 |
| DeviceSettingDescription | `41995` | 此标签指示特定相机型号的拍摄条件信息。该标签仅用于在读取器中指示拍摄条件。 |
| SubjectDistanceRange | `41996` | 此标签指示到主体的距离。 |
| ImageUniqueID | `42016` | 图像唯一标识。 |
| GPSVersionID | `0` | 指示 GPSInfoIFD 的版本。 |
| GPSLatitudeRef | `1` | 指示纬度是北纬还是南纬。 |
| GPSLatitude | `2` | 指示纬度。纬度以三个 RATIONAL 值表示，分别为度、分、秒。如果以度、分、秒表示，典型格式为 dd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为 dd/1,mmmm/100,0/1。 |
| GPSLongitudeRef | `3` | 指示经度是东经还是西经。 |
| GPSLongitude | `4` | 指示经度。经度以三个 RATIONAL 值表示，分别为度、分、秒。如果以度、分、秒表示，典型格式为 ddd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为 ddd/1,mmmm/100,0/1。 |
| GPSAltitudeRef | `5` | 指示用作参考海拔的高度。如果参考是海平面且高度高于海平面，则给出 0。如果高度低于海平面，则给出 1，并在 GPSAltitude 标记中以绝对值表示高度。 |
| GPSAltitude | `6` | 指示基于 GPSAltitudeRef 中参考的高度。高度以一个 RATIONAL 值表示。参考单位为米。 |
| GPSTimestamp | `7` | 指示时间为 UTC（协调世界时）。TimeStamp 以三个 RATIONAL 值表示，分别给出小时、分钟和秒。 |
| GPSSatellites | `8` | 指示用于测量的 GPS 卫星。此标签可用于描述卫星数量、其 ID 编号、仰角、方位角、信噪比以及其他以 ASCII 记号表示的信息。格式未指定。如果 GPS 接收器无法进行测量，则该标签的值应设为 NULL。 |
| GPSStatus | `9` | 指示拍摄图像时 GPS 接收器的状态。 |
| GPSMeasureMode | `10` | 指示 GPS 测量模式。- 二维或三维。 |
| GPSDOP | `11` | 指示 GPS DOP（数据精度等级）。在二维测量时写入 HDOP 值，三维测量时写入 PDOP 值。 |
| GPSSpeedRef | `12` | 指示用于表示 GPS 接收器移动速度的单位。'K'、'M' 和 'N' 分别代表公里每小时、英里每小时和节。 |
| GPSSpeed | `13` | 指示 GPS 接收器的移动速度。 |
| GPSTrackRef | `14` | 指示用于给出 GPS 接收器移动方向的参考。'T' 表示真方向，'M' 表示磁方向。 |
| GPSTrack | `15` | 指示 GPS 接收器的移动方向。取值范围为 0.00 到 359.99。 |
| GPSImgDirectionRef | `16` | 指示用于给出拍摄图像方向的参考。'T' 表示真方向，'M' 表示磁方向。 |
| GPSImgDirection | `17` | 指示拍摄时图像的方向。取值范围为 0.00 到 359.99。 |
| GPSMapDatum | `18` | 指示 GPS 接收器使用的测地测量数据。 |
| GPSDestLatitudeRef | `19` | 指示目的地点的纬度是北纬还是南纬。ASCII 值 'N' 表示北纬，'S' 表示南纬。 |
| GPSDestLatitude | `20` | 指示目的地点的纬度。纬度以三个 RATIONAL 值表示，分别给出度、分、秒。如果纬度以度、分、秒表示，典型格式为 dd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为 dd/1,mmmm/100,0/1。 |
| GPSDestLongitudeRef | `21` | 指示目的地点的经度是东经还是西经。ASCII 'E' 表示东经，'W' 表示西经。 |
| GPSDestLongitude | `22` | 指示目的地点的经度。经度以三个 RATIONAL 值表示，分别给出度、分、秒。如果经度以度、分、秒表示，典型格式为 ddd/1,mm/1,ss/1。当使用度和分且例如分的分数保留两位小数时，格式为 ddd/1,mmmm/100,0/1。 |
| GPSDestBearingRef | `23` | 指示用于给出目的地点方位的参考。'T' 表示真方向，'M' 表示磁方向。 |
| GPSDestBearing | `24` | 指示到目的地点的方位。取值范围为 0.00 到 359.99。 |
| GPSDestDistanceRef | `25` | 指示用于表示到目的地点距离的单位。'K'、'M' 和 'N' 分别代表公里、英里和节。 |
| GPSDestDistance | `26` | 指示到目的地点的距离。 |
| GPSProcessingMethod | `27` | 记录用于定位的方式名称的字符字符串。第一个字节指示使用的字符编码，随后是方法名称。 |
| GPSAreaInformation | `28` | 记录 GPS 区域名称的字符字符串。第一个字节指示使用的字符编码，随后是 GPS 区域的名称。 |
| GPSDateStamp | `29` | 记录相对于 UTC（协调世界时）的日期和时间信息的字符字符串。格式为 YYYY:MM:DD。 |
| GPSDifferential | `30` | 指示是否对 GPS 接收器应用差分校正。 |
| StripOffsets | `273` | 对于每个条带，指示该条带的字节偏移量。建议选择使条带字节数不超过 64 Kbytes。Aux 标记。 |
| JPEGInterchangeFormat | `513` | 指向 JPEG 压缩缩略图数据起始字节 (SOI) 的偏移量。此偏移量不用于主图像的 JPEG 数据。 |
| JPEGInterchangeFormatLength | `514` | JPEG 压缩缩略图数据的字节数。此数据不用于主图像的 JPEG 数据。JPEG 缩略图不被分割，而是以从 SOI 到 EOI 的连续 JPEG 位流记录。Appn 和 COM 标记不应被记录。压缩缩略图必须记录在不超过 64 Kbytes 的范围内，包括所有要记录在 APP1 中的其他数据。 |
| ExifIfdPointer | `34665` | 指向 Exif IFD 的指针。该 IFD 用于互操作性，结构与 TIFF 中指定的 IFD 相同。不过，通常情况下它不包含图像数据，区别于 TIFF 的情况。 |
| GPSIfdPointer | `34853` | gps ifd 指针。 |
| RowsPerStrip | `278` | 每个条带的行数。当图像被划分为条带时，这指的是单个条带在图像中的行数。 |
| StripByteCounts | `279` | 每个条带的总字节数。 |
| PixelXDimension | `40962` | 特定于压缩数据的信息。当记录压缩文件时，应在此标签中记录有效图像的宽度，无论是否存在填充数据或重启标记。 |
| PixelYDimension | `40963` | 特定于压缩数据的信息。当记录压缩文件时，应在此标签中记录有效图像的高度。 |
| Gamma | `42240` | 伽马值 |
| SensitivityType | `34864` | 摄影感光度类型 |
| StandardOutputSensitivity | `34865` | 指示相机的标准输出感光度 |
| RecommendedExposureIndex | `34866` | 指示推荐的曝光指数 |
| ISOSpeed | `34867` | 关于 ISO 12232 中定义的 ISO 速度值的信息 |
| ISOSpeedLatitudeYYY | `34868` | 此标签指示 ISO 12232 中定义的 ISO 速度纬度 yyy 值 |
| ISOSpeedLatitudeZZZ | `34869` | 此标签指示 ISO 12232 中定义的 ISO 速度纬度 zzz 值 |
| CameraOwnerName | `42032` | 包含相机所有者姓名 |
| BodySerialNumber | `42033` | 包含相机机身序列号 |
| LensMake | `42035` | 此标签记录镜头制造商 |
| LensModel | `42036` | 此标签记录镜头`s 型号名称和型号编号 |
| LensSerialNumber | `42037` | 此标签记录可换镜头的序列号 |
| LensSpecification | `42034` | 此标签记录最小焦距、最大焦距、最小焦距对应的最小光圈值以及最大焦距对应的最小光圈值 |

### 另请参见

* namespace [Aspose.Imaging.Exif](../../aspose.imaging.exif/)
* assembly [Aspose.Imaging](../../)


