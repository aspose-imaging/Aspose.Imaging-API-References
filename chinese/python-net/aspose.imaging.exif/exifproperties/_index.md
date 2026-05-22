---
title: "ExifProperties 枚举"
type: docs
weight: 190
url: /zh/python-net/aspose.imaging.exif/exifproperties/
---

Exif 标签列表

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifProperties

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| APERTURE_VALUE | 镜头光圈值。 |
| ARTIST | 此标签记录相机所有者、摄影师或图像创建者的名称。未指定详细格式，但建议按以下示例编写信息，以便于互操作性。当字段留空时，视为未知。例）"Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | 每个图像组件的位数。根据此标准，图像的每个组件为 8 位，因此此标签的值为 8。 |
| BODY_SERIAL_NUMBER | 包含相机机身序列号 |
| BRIGHTNESS_VALUE | 亮度值。 |
| CAMERA_OWNER_NAME | 包含相机所有者名称 |
| CFA_PATTERN | 指示在使用单芯片彩色区域传感器时图像传感器的颜色滤光阵列 (CFA) 几何图案。它不适用于所有感测方法。 |
| COLOR_SPACE | 颜色空间信息标签 (ColorSpace) 始终记录为颜色空间指定符。 |
| COMPONENTS_CONFIGURATION | 组件配置。 |
| COMPRESSED_BITS_PER_PIXEL | 特定于压缩数据；说明每像素的压缩位数。 |
| 压缩 | 用于图像数据的压缩方案。当主图像已进行 JPEG 压缩时，此指定不是必需的，且会被省略。 |
| 对比度 | 此标签指示相机拍摄图像时所应用的对比度处理方向。 |
| 版权 | 版权信息。在本标准中，此标签用于<br/>                指示摄影师和编辑的版权。它是<br/>                声称图像权利的个人或组织的版权声明。互操作性版权<br/>                声明应包括日期和权利，并写入此<br/>                字段；例如，"Copyright, John Smith, 19xx. All rights<br/>                reserved."。在本标准中，该字段记录摄影师和编辑的版权，分别记录在<br/>                声明的不同部分。当摄影师和编辑的版权有明确区分时，应该<br/>                按摄影师随后编辑版权的顺序书写，<br/>                以 NULL 分隔（在此情况下由于声明也以<br/>                NULL 结束，有两个 NULL 代码）。当仅提供摄影师<br/>                版权时，以一个 NULL 代码终止。当仅提供编辑版权时，摄影师版权部分<br/>                包含一个空格后跟终止的 NULL 代码，然后提供编辑版权。当字段留空时，视为未知。 |
| 自定义渲染 | 此标签指示对图像数据使用特殊处理，例如面向输出的渲染。当执行特殊处理时，读取器应禁用或尽量减少任何进一步的处理。 |
| 日期时间 | 图像创建的日期和时间。在 Exif 标准中，它是文件更改的日期和时间。 |
| 数字化日期时间 | 数字化的日期时间。 |
| 原始日期时间 | 原始图像数据生成的日期和时间。 |
| 设备设置描述 | 此标签指示特定相机型号的拍摄条件信息。该标签仅用于在读取器中指示拍摄条件。 |
| 数字变焦比例 | 此标签指示拍摄图像时的数字变焦比例。如果记录值的分子为 0，则表示未使用数字变焦。 |
| EXIF_IFD_POINTER | 指向 Exif IFD 的指针。互操作性方面，Exif IFD 与 TIFF 中指定的 IFD 结构相同。然而，通常它不包含图像数据，如同 TIFF 的情况。 |
| EXIF_VERSION | Exif 版本。 |
| 曝光补偿值 | 曝光补偿值。 |
| 曝光指数 | 指示在捕获图像时相机或输入设备所选的曝光指数。 |
| EXPOSURE_MODE | 此标签指示拍摄图像时设置的曝光模式。在自动包围模式下，相机会以不同的曝光设置拍摄同一场景的一系列帧。 |
| EXPOSURE_PROGRAM | 相机在拍摄照片时用于设置曝光的程序类。 |
| EXPOSURE_TIME | 曝光时间，以秒为单位。 |
| FILE_SOURCE | 文件来源。 |
| FLASH | 指示拍摄图像时闪光灯的状态。 |
| FLASHPIX_VERSION | FPXR 文件支持的 Flashpix 格式版本。 |
| FLASH_ENERGY | 指示捕获图像时的闪光能量，单位为光束烛光功率秒（BCPS）。 |
| FOCAL_LENGTH | 镜头的实际焦距，单位为毫米。 |
| FOCAL_LENGTH_IN_35_MM_FILM | 此标签指示在假设为 35mm 胶片相机时的等效焦距，单位为毫米。值为 0 表示焦距未知。请注意，此标签与 FocalLength 标签不同。 |
| FOCAL_PLANE_RESOLUTION_UNIT | 指示用于测量 FocalPlaneXResolution 和 FocalPlaneYResolution 的单位。该值与 ResolutionUnit 相同。 |
| FOCAL_PLANE_X_RESOLUTION | 指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像宽度（X）方向上的像素数量。 |
| FOCAL_PLANE_Y_RESOLUTION | 指示相机焦平面上每个 FocalPlaneResolutionUnit 在图像高度（Y）方向上的像素数量。 |
| F_NUMBER | F数。 |
| GAIN_CONTROL | 此标签指示整体图像增益调整的程度。 |
| GAMMA | 伽马值 |
| GPSDOP | 指示 GPS DOP（数据精度等级）。在二维测量期间写入 HDOP 值，<br/>                并在三维测量期间写入 PDOP。 |
| GPS_ALTITUDE | 指示基于 GPSAltitudeRef 中参考的海拔。海拔以一个 RATIONAL 值表示。<br/>                参考单位为米。 |
| GPS_ALTITUDE_REF | 指示用作参考海拔的高度。如果参考为海平面且海拔高于海平面，<br/>                则给出 0。如果海拔低于海平面，则给出 1，并在 GPSAltitude 标签中将海拔表示为绝对值。 |
| GPS_AREA_INFORMATION | 记录 GPS 区域名称的字符字符串。第一个字节指示<br/>                所使用的字符编码，随后是 GPS 区域的名称。 |
| GPS_DATE_STAMP | 记录相对于 UTC<br/>                （协调世界时）的日期和时间信息。格式为 YYYY:MM:DD。 |
| GPS_DEST_BEARING | 指示到目的地点的方位。取值范围为 0.00 到 359.99。 |
| GPS_DEST_BEARING_REF | 指示用于给出目的地点方位的参考。'T' 表示真方向，'M' 表示<br/>                磁方向。 |
| GPS_DEST_DISTANCE | 指示到目的地点的距离。 |
| GPS_DEST_DISTANCE_REF | 指示用于表示到目的地点距离的单位。'K'、'M' 和 'N' 分别代表公里、英里<br/>                和节。 |
| GPS_DEST_LATITUDE | 指示目标点的纬度。纬度以三个 RATIONAL 值表示，分别提供<br/>                度、分和秒。如果纬度以度、分、秒表示，典型的格式为 dd/1,mm/1,ss/1。当使用度和分且例如分的分数保留到小数点后两位时，格式为 dd/1,mmmm/100,0/1。 |
| GPS_DEST_LATITUDE_REF | 指示目标点的纬度是北纬还是南纬。ASCII 值 'N' 表示北纬，'S' 表示南纬。 |
| GPS_DEST_LONGITUDE | 指示目标点的经度。经度以三个 RATIONAL 值表示，分别提供<br/>                度、分和秒。如果经度以度、分、秒表示，典型的格式为 ddd/1,mm/1,ss/1。当使用度和分且例如分的分数保留到小数点后两位时，格式为 ddd/1,mmmm/100,0/1。 |
| GPS_DEST_LONGITUDE_REF | 指示目标点的经度是东经还是西经。ASCII 'E' 表示东经，'W' 表示西经。 |
| GPS_DIFFERENTIAL | 指示是否对 GPS 接收器应用差分校正。 |
| GPS_IFD_POINTER | gps ifd 指针。 |
| GPS_IMG_DIRECTION | 指示图像拍摄时的方向。取值范围为 0.00 到 359.99。 |
| GPS_IMG_DIRECTION_REF | 指示拍摄时给出图像方向的参考。'T' 表示真北方向，'M' 表示磁北方向。 |
| GPS_LATITUDE | 指示纬度。纬度以三个 RATIONAL 值表示，分别提供度、分和秒。如果纬度以度、分、秒表示，典型的格式为 dd/1,mm/1,ss/1。当使用度和分且例如分的分数保留到小数点后两位时，格式为 dd/1,mmmm/100,0/1。 |
| GPS_LATITUDE_REF | 指示纬度是北纬还是南纬。 |
| GPS_LONGITUDE | 指示经度。经度以三个 RATIONAL 值表示，分别提供度、分和秒。如果经度以度、分、秒表示，典型的格式为 ddd/1,mm/1,ss/1。当使用度和分且例如分的分数保留到小数点后两位时，格式为 ddd/1,mmmm/100,0/1。 |
| GPS_LONGITUDE_REF | 指示经度是东经还是西经。 |
| GPS_MAP_DATUM | 指示 GPS 接收器使用的测地测量数据。 |
| GPS_MEASURE_MODE | 指示 GPS 测量模式。- 2 维或 3 维。 |
| GPS_PROCESSING_METHOD | 记录用于定位的方法名称的字符字符串。<br/>                第一个字节指示使用的字符编码，随后是方法名称<br/>                。 |
| GPS_SATELLITES | 指示用于测量的 GPS 卫星。此标签可用于描述卫星数量、<br/>                它们的 ID 编号、高程角、方位角、信噪比以及其他以 ASCII 记号表示的信息。格式未<br/>                指定。如果 GPS 接收器无法进行测量，则该标签的值应设为 NULL。 |
| GPS_SPEED | 指示 GPS 接收器移动的速度。 |
| GPS_SPEED_REF | 指示用于表示 GPS 接收器移动速度的单位。'K'、'M' 和 'N' 分别代表每小时公里数、每小时英里数和节。 |
| GPS_STATUS | 指示拍摄图像时 GPS 接收器的状态。 |
| GPS_TIMESTAMP | 指示时间为 UTC（协调世界时）。时间戳以三个有理数值表示，<br/>                分别给出小时、分钟和秒。 |
| GPS_TRACK | 指示 GPS 接收器移动的方向。取值范围为 0.00 到 359.99。 |
| GPS_TRACK_REF | 指示给出 GPS 接收器移动方向的参考。'T' 表示真北方向，'M' 为<br/>                磁北方向。 |
| GPS_VERSION_ID | 指示 GPSInfoIFD 的版本。 |
| IMAGE_DESCRIPTION | 提供图像标题的字符字符串。它可以是诸如 "1988 company picnic" 之类的注释。 |
| IMAGE_LENGTH | 图像数据的行数。 |
| IMAGE_UNIQUE_ID | 图像唯一标识。 |
| IMAGE_WIDTH | 图像数据的列数，等于每行的像素数。 |
| ISO_SPEED | 关于 ISO 12232 中定义的 ISO 速度值的信息 |
| ISO_SPEED_LATITUDE_YYY | 此标签指示 ISO 12232 中定义的 ISO 速度纬度 yyy 值 |
| ISO_SPEED_LATITUDE_ZZZ | 此标签指示 ISO 12232 中定义的 ISO 速度纬度 zzz 值 |
| JPEG_INTERCHANGE_FORMAT | JPEG 压缩缩略图数据的起始字节（SOI）的偏移量。此字段不用于主图像的 JPEG 数据。 |
| JPEG_INTERCHANGE_FORMAT_LENGTH | JPEG 压缩缩略图数据的字节数。此字段不用于主图像的 JPEG 数据。JPEG 缩略图不被分割，而是作为从 SOI 到 EOI 的连续 JPEG 位流记录。不应记录 Appn 和 COM 标记。压缩缩略图的记录不得超过 64 Kbytes，包括在 APP1 中记录的所有其他数据。 |
| LENS_MAKE | 此标签记录镜头制造商 |
| LENS_MODEL | 此标签记录镜头的型号名称和型号编号 |
| LENS_SERIAL_NUMBER | 此标签记录可换镜头的序列号 |
| LENS_SPECIFICATION | 此标签记录最小焦距、最大焦距、最小焦距时的最小光圈值以及最大焦距时的最小光圈值 |
| LIGHT_SOURCE | 光源类型。 |
| MAKE | 记录设备的制造商。即生成图像的数码相机、扫描仪、视频数字化仪或其他设备的制造商。当此字段留空时，视为未知。 |
| MAKER_NOTE | 用于Exif写入器制造商记录任何所需信息的标签。内容由制造商自行决定，但此标签不应用于其预期目的之外的任何用途。 |
| MAX_APERTURE_VALUE | 最大光圈值。 |
| METERING_MODE | 测光模式。 |
| MODEL | 设备的型号名称或型号编号。这是生成图像的数码相机、扫描仪、视频数字化仪或其他设备的型号名称或编号。当该字段留空时，视为未知。 |
| OECF | 指示 ISO 14524 中指定的光电转换函数（OECF）。 |
| ORIENTATION | 以行列方式查看的图像方向。 |
| PHOTOGRAPHIC_SENSITIVITY | 指示相机或输入设备在 ISO 12232 中规定的 ISO 速度和 ISO 维度。 |
| PHOTOMETRIC_INTERPRETATION | 像素组成。 |
| PIXEL_X_DIMENSION | 特定于压缩数据的信息。当记录压缩文件时，无论是否存在填充数据或重新启动标记，都应在此标签中记录有效图像的宽度。 |
| PIXEL_Y_DIMENSION | 特定于压缩数据的信息。当记录压缩文件时，应在此标签中记录有效图像的高度。 |
| PLANAR_CONFIGURATION | 指示像素组件是以块状（chunky）还是平面（planar）格式记录。如果此字段不存在，则假定 TIFF 的默认值为 1（块状）。 |
| PRIMARY_CHROMATICITIES | 图像三原色的色度。通常此标签不是必需的，因为颜色空间已在颜色空间信息的 ColorSpace 标签中指定。 |
| RECOMMENDED_EXPOSURE_INDEX | 指示推荐的曝光指数 |
| REFERENCE_BLACK_WHITE | 参考黑点值和参考白点<br/>                值。TIFF 中未给出默认值，但以下值在此作为默认值提供。<br/>                颜色空间已声明<br/>                在颜色空间信息标签中，默认值为<br/>                该值提供最佳图像特性<br/>                互操作性条件 |
| RELATED_SOUND_FILE | 相关的声音文件。 |
| RESOLUTION_UNIT | 用于测量 XResolution 和 YResolution 的单位。 XResolution 和 YResolution 使用相同的单位。 如果图像分辨率未知，则指定为 2（英寸）。 |
| ROWS_PER_STRIP | 每条带的行数。 当图像被划分为条带时，这是单个条带在图像中的行数。 |
| SAMPLES_PER_PIXEL | 每像素的组件数量。 由于此标准适用于 RGB 和 YCbCr 图像，此标签的值设为 3。 |
| SATURATION | 此标签指示相机拍摄图像时所应用的饱和度处理方向。 |
| SCENE_CAPTURE_TYPE | 此标签指示拍摄场景的类型。它也可用于记录拍摄图像的模式。 |
| SCENE_TYPE | 指示场景的类型。如果 DSC 记录了图像，则此标签值应始终设为 1，表示图像是直接拍摄的。 |
| SENSING_METHOD | 指示相机或输入设备的图像传感器类型。 |
| SENSITIVITY_TYPE | 摄影感光度类型 |
| SHARPNESS | 此标签指示相机拍摄图像时所应用的锐度处理方向 |
| SHUTTER_SPEED_VALUE | 快门速度值。 |
| SOFTWARE | 此标签记录用于生成图像的相机或图像输入设备的软件或固件的名称和版本。未指定详细格式，但建议遵循下面示例。当字段留空时，视为未知。 |
| SPATIAL_FREQUENCY_RESPONSE | 此标签记录相机或输入设备的空间频率表以及在图像宽度、图像高度和对角方向上的 SFR 值，遵循 ISO 12233 的规定。 |
| SPECTRAL_SENSITIVITY | 指示所使用相机每个通道的光谱灵敏度。 |
| STANDARD_OUTPUT_SENSITIVITY | 指示相机的标准输出灵敏度。 |
| STRIP_BYTE_COUNTS | 每个条带的总字节数。 |
| STRIP_OFFSETS | 对于每个条带，给出该条带的字节偏移量。建议选择使条带字节数不超过 64 Kbytes。<br/>                辅助标签。 |
| SUBJECT_AREA | 此标签指示整体场景中主体的位置信息和面积。 |
| SUBJECT_DISTANCE | 到主体的距离，以米为单位。 |
| SUBJECT_DISTANCE_RANGE | 此标签指示到主体的距离。 |
| SUBJECT_LOCATION | 指示场景中主体的位置。该标签的值表示主体中心相对于左边缘的像素位置，位于根据 Rotation 标签进行旋转处理之前。 |
| SUBSEC_TIME | 用于记录 DateTime 标签的秒以下小数的标签。 |
| SUBSEC_TIME_DIGITIZED | 用于记录 DateTimeDigitized 标签的秒以下小数的标签。 |
| SUBSEC_TIME_ORIGINAL | 用于记录 DateTimeOriginal 标签的秒分数的标签。 |
| TRANSFER_FUNCTION | 图像的传输函数，以表格形式描述。通常不需要此标签，因为颜色空间已在颜色空间信息 ColorSpace 标签中指定。 |
| USER_COMMENT | 供 Exif 用户在图像上写入关键字或注释的标签，除了 ImageDescription 中的内容，并且不受 ImageDescription 标签字符编码限制。 |
| WHITE_BALANCE | 此标签指示拍摄图像时设置的白平衡模式。 |
| WHITE_POINT | 图像白点的色度。通常不需要此标签，因为颜色空间已在颜色空间信息 ColorSpace 标签中指定。 |
| X_RESOLUTION | 在 ImageWidth 方向上，每个 ResolutionUnit 的像素数。当图像分辨率未知时，指定为 72 [dpi]。 |
| Y_CB_CR_COEFFICIENTS | 从 RGB 到 YCbCr 图像数据转换的矩阵系数。 |
| Y_CB_CR_POSITIONING | 色度分量相对于<br/>                亮度分量的位置。此字段仅用于<br/>                JPEG 压缩数据或未压缩的 YCbCr 数据。TIFF<br/>                默认值为 1（居中）；但当 Y:Cb:Cr = 4:2:2 时，标准建议使用 2（并列）来<br/>                记录数据，以提高在电视系统上观看时的图像质量。若此字段不存在，读取器应<br/>                假定 TIFF 默认值。对于 Y:Cb:Cr = 4:2:0 的情况，推荐使用 TIFF 默认（居中）。如果读取器<br/>                没有支持两种 YCbCrPositioning 的能力，则应无论该字段的值如何，都遵循 TIFF 默认。最好读取器能够"<br/>                同时支持居中和并列定位。 |
| Y_CB_CR_SUB_SAMPLING | 色度分量相对于亮度分量的采样比例。 |
| Y_RESOLUTION | 在 ImageLength 方向上，每个 ResolutionUnit 的像素数。指定的值与 XResolution 相同。 |
