---
title: "JpegExifData 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.JpegExifData

**Inheritance:** IImageMetadataFormat, ExifData

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | 初始化 [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) 类的新实例。 |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | 使用数组中的数据初始化 [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) 类的新实例。 |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | 使用数组中的数据初始化 [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) 类的新实例。 |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_4) | 使用数组中的数据初始化 [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | 允许的最大 EXIF 段大小（字节）。 |
| aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置光圈值。 |
| artist | string | r/w | 获取或设置艺术家。 |
| bits_per_sample | int[] | r/w | 获取或设置每个样本的位数。 |
| body_serial_number | string | r/w | 获取或设置相机机身序列号。 |
| brightness_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | 获取或设置亮度值。 |
| camera_owner_name | string | r/w | 获取或设置相机所有者名称 |
| cfa_pattern | System.Byte | r/w | 获取或设置 CFA 模式。 |
| color_space | [ExifColorSpace](/imaging/python-net/aspose.imaging.exif.enums/exifcolorspace/) | r/w | 获取或设置颜色空间。 |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置标签，这些标签属于通用部分。此仅适用于 jpeg 图像，在 tiff 格式下使用 tiffOptions。 |
| components_configuration | System.Byte | r/w | 获取或设置组件配置。 |
| compressed_bits_per_pixel | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置每像素压缩位数。 |
| 压缩 | int | r/w | 获取或设置压缩。 |
| contrast | [ExifContrast](/imaging/python-net/aspose.imaging.exif.enums/exifcontrast/) | r/w | 获取或设置对比度。 |
| 版权 | string | r/w | 获取或设置版权。 |
| custom_rendered | [ExifCustomRendered](/imaging/python-net/aspose.imaging.exif.enums/exifcustomrendered/) | r/w | 获取或设置自定义渲染。 |
| date_time | string | r/w | 获取或设置日期时间。 |
| date_time_digitized | string | r/w | 获取或设置数字化日期时间。 |
| date_time_original | string | r/w | 获取或设置原始日期时间。 |
| device_setting_description | System.Byte | r/w | 获取或设置设备设置描述 |
| digital_zoom_ratio | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置数字变焦比例。 |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置仅属于 EXIF 部分的标签。 |
| exif_version | System.Byte | r/w | 获取或设置 EXIF 版本。 |
| exposure_bias_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | 获取或设置曝光偏差值。 |
| exposure_index | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置曝光指数。 |
| exposure_mode | [ExifExposureMode](/imaging/python-net/aspose.imaging.exif.enums/exifexposuremode/) | r/w | 获取或设置曝光模式。 |
| exposure_program | [ExifExposureProgram](/imaging/python-net/aspose.imaging.exif.enums/exifexposureprogram/) | r/w | 获取或设置曝光程序。 |
| exposure_time | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置曝光时间。 |
| f_number | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 F-number。 |
| file_source | [ExifFileSource](/imaging/python-net/aspose.imaging.exif.enums/exiffilesource/) | r/w | 获取或设置文件来源类型。 |
| flash | [ExifFlash](/imaging/python-net/aspose.imaging.exif.enums/exifflash/) | r/w | 获取或设置闪光灯。 |
| flash_energy | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置闪光能量。 |
| flashpix_version | System.Byte | r/w | 获取或设置 flash pix 版本。 |
| focal_length | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置焦距。 |
| focal_length_in_35_mm_film | int | r/w | 获取或设置 35 mm 胶片中的焦距。 |
| focal_plane_resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | 获取或设置焦平面分辨率单位。 |
| focal_plane_x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置焦平面 X 分辨率。 |
| focal_plane_y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置焦平面 Y 分辨率。 |
| gain_control | [ExifGainControl](/imaging/python-net/aspose.imaging.exif.enums/exifgaincontrol/) | r/w | 获取或设置整体图像增益调整的程度。 |
| gamma | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置伽马值。 |
| gps_altitude | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 海拔。 |
| gps_altitude_ref | [ExifGPSAltitudeRef](/imaging/python-net/aspose.imaging.exif.enums/exifgpsaltituderef/) | r/w | 获取或设置用作参考海拔的 GPS 海拔。 |
| gps_area_information | System.Byte | r/w | 获取或设置 GPS 区域信息。 |
| gps_date_stamp | string | r/w | 获取或设置相对于 UTC（协调世界时）的 GPS 字符串记录日期和时间信息。 |
| gps_dest_bearing | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置指向目的地点的 GPS 方位角。 |
| gps_dest_bearing_ref | string | r/w | 获取或设置用于指示目的地点方位角的 GPS 参考。 |
| gps_dest_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置到目的地点的 GPS 距离。 |
| gps_dest_distance_ref | string | r/w | 获取或设置用于表示到目的地点距离的 GPS 单位。 |
| gps_dest_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置目的地点的 GPS 纬度。 |
| gps_dest_latitude_ref | string | r/w | 获取或设置指示目的地点纬度是北纬还是南纬的 GPS 值。 |
| gps_dest_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置目的地点的 GPS 经度。 |
| gps_dest_longitude_ref | string | r/w | 获取或设置指示目的地点经度是东经还是西经的 GPS 值。 |
| gps_differential | int | r/w | 获取或设置指示 GPS 接收器是否应用差分校正的 GPS 值。 |
| gps_img_direction | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置图像拍摄时的 GPS 方向。 |
| gps_img_direction_ref | string | r/w | 获取或设置用于指示图像拍摄时方向的 GPS 参考。 |
| gps_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 纬度。 |
| gps_latitude_ref | string | r/w | 获取或设置 GPS 纬度是北纬还是南纬。 |
| gps_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 经度。 |
| gps_longitude_ref | string | r/w | 获取或设置 GPS 经度是东经还是西经. |
| gps_map_datum | string | r/w | 获取或设置 GPS 接收器使用的 GPS 大地测量调查数据. |
| gps_measure_mode | string | r/w | 获取或设置 GPS 测量模式. |
| gps_processing_method | System.Byte | r/w | 获取或设置 记录用于定位方法名称的 GPS 字符串. |
| gps_satellites | string | r/w | 获取或设置 用于测量的 GPS 卫星. |
| gps_speed | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 接收器移动的速度. |
| gps_speed_ref | string | r/w | 获取或设置 用于表示 GPS 接收器移动速度的单位. |
| gps_status | string | r/w | 获取或设置 图像记录时 GPS 接收器的状态. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置 仅属于 GPS 部分的标签. |
| gps_timestamp | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS 时间为 UTC (Coordinated Universal Time). |
| gps_track | string | r/w | 获取或设置 GPS 接收器移动的方向. |
| gps_track_ref | string | r/w | 获取或设置 用于给出 GPS 接收器移动方向的参考. |
| gps_version_id | System.Byte | r/w | 获取或设置 GPS 版本标识符. |
| gpsdop | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 GPS DOP (data degree of precision). |
| image_description | string | r/w | 获取或设置图像描述。 |
| image_length | int | r/w | 获取或设置图像长度。 |
| image_unique_id | string | r/w | 获取或设置 图像唯一标识符. |
| image_width | int | r/w | 获取或设置图像宽度。 |
| is_big_endian | bool | r/w | 获取或设置一个值，指示从中创建的流 EXIF 数据是否为大端序。 |
| iso_speed | int | r/w | 获取或设置 ISO 速度 |
| iso_speed_latitude_yyy | int | r/w | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 yyy 值。 |
| iso_speed_latitude_zzz | int | r/w | 获取或设置相机或输入设备在 ISO 12232 中定义的 ISO 速度纬度 zzz 值。 |
| iso_speed_value | int | r/w | 获取或设置 ISO 速度值。 |
| lens_make | string | r/w | 获取或设置镜头的制造商。 |
| lens_model | string | r/w | 获取或设置镜头型号。 |
| lens_serial_number | string | r/w | 获取或设置镜头序列号。 |
| lens_specification | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置镜头规格 |
| light_source | [ExifLightSource](/imaging/python-net/aspose.imaging.exif.enums/exiflightsource/) | r/w | 获取或设置光源。 |
| make | string | r/w | 获取或设置录音设备的制造商。 |
| maker_note_data | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r | 获取制造商备注数据。 |
| maker_note_raw_data | System.Byte | r/w | 获取或设置制造商备注原始数据。 |
| maker_notes | [MakerNote[]](/imaging/python-net/aspose.imaging.exif/makernote/) | r | 获取制造商备注。 |
| max_aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置最大光圈值。 |
| metering_mode | [ExifMeteringMode](/imaging/python-net/aspose.imaging.exif.enums/exifmeteringmode/) | r/w | 获取或设置测光模式。 |
| model | string | r/w | 获取或设置模型。 |
| oecf | System.Byte | r/w | 获取或设置在 ISO 14524 中指定的光电转换函数（OECF）。 |
| orientation | [ExifOrientation](/imaging/python-net/aspose.imaging.exif.enums/exiforientation/) | r/w | 获取或设置方向。 |
| photographic_sensitivity | int | r/w | 获取或设置摄影灵敏度。 |
| photometric_interpretation | int | r/w | 获取或设置光度解释。 |
| pixel_x_dimension | int | r/w | 获取或设置像素 X 维度。 |
| pixel_y_dimension | int | r/w | 获取或设置像素 Y 维度。 |
| planar_configuration | int | r/w | 获取或设置平面配置。 |
| primary_chromaticities | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置图像三原色的色度。 |
| properties | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置所有 EXIF 标签（包括通用标签和 GPS 标签）。 |
| recommended_exposure_index | int | r/w | 获取或设置推荐曝光指数。 |
| reference_black_white | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置参考黑白。 |
| related_sound_file | string | r/w | 获取或设置相关声音文件。 |
| resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | 获取或设置分辨率单位。 |
| samples_per_pixel | int | r/w | 获取或设置每像素样本数。 |
| saturation | [ExifSaturation](/imaging/python-net/aspose.imaging.exif.enums/exifsaturation/) | r/w | 获取或设置饱和度。 |
| scene_capture_type | [ExifSceneCaptureType](/imaging/python-net/aspose.imaging.exif.enums/exifscenecapturetype/) | r/w | 获取或设置场景捕获类型。 |
| scene_type | System.Byte | r/w | 获取或设置场景类型。 |
| sensing_method | [ExifSensingMethod](/imaging/python-net/aspose.imaging.exif.enums/exifsensingmethod/) | r/w | 获取或设置感应方法。 |
| sensitivity_type | int | r/w | 获取或设置灵敏度类型。 |
| sharpness | int | r/w | 获取或设置清晰度。 |
| shutter_speed_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | 获取或设置快门速度值。 |
| 软件 | string | r/w | 获取或设置软件。 |
| spatial_frequency_response | System.Byte | r/w | 获取或设置空间频率响应。 |
| spectral_sensitivity | string | r/w | 获取或设置光谱灵敏度。 |
| standard_output_sensitivity | int | r/w | 获取或设置标准输出灵敏度 |
| subject_area | int[] | r/w | 获取或设置主体区域。 |
| subject_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置主体距离。 |
| subject_distance_range | [ExifSubjectDistanceRange](/imaging/python-net/aspose.imaging.exif.enums/exifsubjectdistancerange/) | r/w | 获取或设置主体距离范围。 |
| subject_location | int[] | r/w | 获取或设置主体位置。 |
| subsec_time | string | r/w | 获取或设置 DateTime 标记的秒分数。 |
| subsec_time_digitized | string | r/w | 获取或设置 DateTimeDigitized 标记的秒分数。 |
| subsec_time_original | string | r/w | 获取或设置 DateTimeOriginal 标记的秒分数。 |
| thumbnail | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r/w | 获取或设置缩略图。 |
| transfer_function | int[] | r/w | 获取或设置传输函数。 |
| user_comment | string | r/w | 获取或设置用户评论。 |
| white_balance | [ExifWhiteBalance](/imaging/python-net/aspose.imaging.exif.enums/exifwhitebalance/) | r/w | 获取或设置白平衡。 |
| white_point | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置图像白点的色度。 |
| x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 x 分辨率。 |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置从 RGB 到 YCbCr 图像数据转换的矩阵系数。 |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/imaging/python-net/aspose.imaging.exif.enums/exifycbcrpositioning/) | r/w | 获取或设置色度分量相对于亮度分量的位置。 |
| y_cb_cr_sub_sampling | int[] | r/w | 获取或设置色度分量相对于亮度分量的采样比例。 |
| y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 y 分辨率。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_tag_value(key)](#get_tag_value_key_1) | 获取标签值。 |
| [load_from_bytes(binary_data)](#load_from_bytes_binary_data_2) | 通过从字节数组加载，创建 [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) 类的新实例。 |
| [remove_tag(tag)](#remove_tag_tag_3) | 从容器中移除标签 |
| [remove_tag(tag_id)](#remove_tag_tag_id_4) | 从容器中移除标签 |
| [remove_tag_id(tag_id)](#remove_tag_id_tag_id_5) | 从容器中移除标签 |
| [serialize_exif_data()](#serialize_exif_data__6) | 序列化 EXIF 数据。写入标签值和内容。最具影响力的大小标签是缩略图标签内容。 |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

初始化 [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) 类的新实例。

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

使用数组中的数据初始化 [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 通用标签。 |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | EXIF 标签。 |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | GPS 标签。 |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

使用数组中的数据初始化 [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 包含通用和 GPS 标签的 EXIF 标签数组。 |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_4}


```
 JpegExifData(exifdata) 
```

使用数组中的数据初始化 [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| exifdata | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | 包含通用和 GPS 标签的 EXIF 标签数组。 |

### Method: get_tag_value(key) {#get_tag_value_key_1}


```
 get_tag_value(key) 
```

获取标签值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | 标签键。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | TiffDataType |


### Method: load_from_bytes(binary_data)  [static] {#load_from_bytes_binary_data_2}


```
 load_from_bytes(binary_data) 
```

通过从字节数组加载，创建 [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| binary_data | System.Byte | 二进制数据。 |

**Returns**

| Type | Description |
| :- | :- |
| [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | 已加载的 ExifData 实例。 |


### Method: remove_tag(tag) {#remove_tag_tag_3}


```
 remove_tag(tag) 
```

从容器中移除标签

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | 要移除的标签 |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_4}


```
 remove_tag(tag_id) 
```

从容器中移除标签

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_id | int | 要移除的标签标识符。 |

### Method: remove_tag_id(tag_id) {#remove_tag_id_tag_id_5}


```
 remove_tag_id(tag_id) 
```

从容器中移除标签

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_id | int | 要移除的标签标识符。 |

### Method: serialize_exif_data() {#serialize_exif_data__6}


```
 serialize_exif_data() 
```

序列化 EXIF 数据。写入标签值和内容。最具影响力的大小标签是缩略图标签内容。

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 已序列化的 EXIF 数据。 |


