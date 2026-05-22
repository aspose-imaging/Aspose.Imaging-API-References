---
title: "BigTiffOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.imageoptions/bigtiffoptions/
---

**Summary:** The API for BigTIFF raster image format creation is specifically designed<br/>            to serve to the unique requirements of applications utilizing large-scale<br/>            imaging data from scanners. This API facilitates the seamless generation<br/>            of BigTIFF format, which combines multiple TIFF images into a single,<br/>            comprehensive image. It ensures efficient processing of extensive image<br/>            data, providing developers with a powerful tool for creating and<br/>            manipulating high-resolution, multi-image formats.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BigTiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, TiffOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [BigTiffOptions(expected_format)](#BigTiffOptions_expected_format_1) | 初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。默认使用小端字节序约定。 |
| [BigTiffOptions(expected_format, byte_order)](#BigTiffOptions_expected_format_byte_order_2) | 初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。 |
| [BigTiffOptions(options)](#BigTiffOptions_options_3) | 初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。 |
| [BigTiffOptions(tags)](#BigTiffOptions_tags_4) | 初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | 获取或设置 alpha 存储选项。除 [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) 之外的选项<br/>            当定义的 [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) 超过 3 时使用。 |
| artist | string | r/w | 获取或设置艺术家。 |
| bits_per_pixel | int | r | 获取每像素的位数。 |
| bits_per_sample | int[] | r/w | 获取或设置每个样本的位数。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | 获取或设置一个值，指示 tiff 字节序。 |
| color_map | int[] | r/w | 获取或设置颜色映射。 |
| compressed_quality | int | r/w | 获取或设置压缩图像质量。<br/>            与 Jpeg 压缩一起使用。 |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | 获取或设置压缩。 |
| 版权 | string | r/w | 获取或设置版权。 |
| date_time | string | r/w | 获取或设置日期和时间。 |
| default_memory_allocation_limit | int | r/w | 获取或设置默认内存分配限制。 |
| disable_icc_export | bool | r/w | 获取或设置一个值，指示是否禁用 ICC 配置文件导出（ICC 配置文件会预先应用于源像素）。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| document_name | string | r/w | 获取或设置文档的名称。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | 获取或设置指向 EXIF IFD 的指针。 |
| extra_samples | int[] | r | 获取额外样本的值。 |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | 获取或设置传真 t4 选项。 |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | 获取或设置 TIFF 文件标准。 |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | 获取或设置字节位填充顺序。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| half_tone_hints | int[] | r/w | 获取或设置半色调提示。 |
| image_description | string | r/w | 获取或设置图像描述。 |
| image_length | int | r/w | 获取或设置图像长度。 |
| image_width | int | r/w | 获取或设置图像宽度。 |
| ink_names | string | r/w | 获取或设置墨水名称。 |
| is_extra_samples_present | bool | r | 获取一个值，指示是否存在额外样本。 |
| is_tiled | bool | r | 获取一个值，指示图像是否已平铺。 |
| is_valid | bool | r | 获取一个值，指示 [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) 是否已正确配置。使用 Validate 方法查找失败原因。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| max_sample_value | int[] | r/w | 获取或设置最大样本值。 |
| min_sample_value | int[] | r/w | 获取或设置最小样本值。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | 获取或设置方向。 |
| page_name | string | r/w | 获取或设置页面名称。 |
| page_number | int[] | r/w | 获取或设置页码标签。 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | 获取或设置光度学。 |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | 获取或设置平面配置。 |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | 获取或设置 LZW 压缩的预测器。 |
| premultiply_components | bool | r/w | 获取或设置一个值，指示组件是否必须预乘。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | 获取或设置分辨率单位。 |
| rows_per_strip | int | r/w | 获取或设置每条带的行数。 |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | 获取或设置样本格式。 |
| samples_per_pixel | int | r | 获取每像素的样本数。要更改此属性值，请使用 [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) 属性设置器。 |
| scanner_manufacturer | string | r/w | 获取或设置扫描仪制造商。 |
| scanner_model | string | r/w | 获取或设置扫描仪型号。 |
| smax_sample_value | int[] | r/w | 获取或设置最大样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。 |
| smin_sample_value | int[] | r/w | 获取或设置最小样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。 |
| software_type | string | r/w | 获取或设置软件类型。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| strip_byte_counts | int[] | r/w | 获取或设置条带字节计数。 |
| strip_offsets | int[] | r/w | 获取或设置条带偏移量。 |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | 获取或设置对该子文件中包含的数据类型的一般指示。 |
| tag_count | int | r | 获取标签计数。 |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置标签。 |
| target_printer | string | r/w | 获取或设置目标打印机。 |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | 获取或设置阈值处理。 |
| tile_byte_counts | int[] | r/w | 获取或设置瓦片字节计数。 |
| tile_length | int | r/w | 获取或设置瓦片长度。 |
| tile_offsets | int[] | r/w | 获取或设置瓦片偏移量。 |
| tile_width | int | r/w | 获取或设置瓦片宽度。 |
| total_pages | int | r | 获取总页数。 |
| valid_tag_count | int | r | 获取有效标签计数。这不是标签的总计数，而是可能被保留的标签数量。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 Xmp 数据。 |
| xp_author | string | r/w | 获取或设置图像作者，该作者用于 Windows Explorer。 |
| xp_comment | string | r/w | 获取或设置图像注释，该注释用于 Windows Explorer。 |
| xp_keywords | string | r/w | 获取或设置图像主题，该主题用于 Windows Explorer。 |
| xp_subject | string | r/w | 获取或设置信息关于图像，该信息用于 Windows Explorer。 |
| xp_title | string | r/w | 获取或设置信息关于图像，该信息用于 Windows Explorer。 |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 x 位置。 |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 x 分辨率。 |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 YCbCrCoefficients。 |
| y_cb_cr_subsampling | int[] | r/w | 获取或设置 YCbCr 光度的子采样因子。 |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 y 位置。 |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | 获取或设置 y 分辨率。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | 添加新标签。 |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | 添加标签。 |
| [clone()](#clone__3) | 克隆此实例。 |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | 初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。默认使用小端字节序约定。 |
| [create_with_options(options)](#create_with_options_options_5) | 初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。 |
| [create_with_tags(tags)](#create_with_tags_tags_6) | 初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。 |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | 按类型获取标签实例。 |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | 获取有效标签计数。 |
| [is_tag_present(tag)](#is_tag_present_tag_9) | 确定标签是否存在于选项中。 |
| [remove_tag(tag)](#remove_tag_tag_10) | 移除标签。 |
| [remove_tags(tags)](#remove_tags_tags_11) | 移除标签。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |
| validate() | 验证选项是否具有有效的标签组合 |


### Constructor: BigTiffOptions(expected_format) {#BigTiffOptions_expected_format_1}


```
 BigTiffOptions(expected_format) 
```

初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。默认使用小端字节序约定。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | 预期的 Tiff 文件格式。 |

### Constructor: BigTiffOptions(expected_format, byte_order) {#BigTiffOptions_expected_format_byte_order_2}


```
 BigTiffOptions(expected_format, byte_order) 
```

初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | 预期的 Tiff 文件格式。 |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | 要使用的 tiff 文件格式字节顺序。 |

### Constructor: BigTiffOptions(options) {#BigTiffOptions_options_3}


```
 BigTiffOptions(options) 
```

初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | 选项来源。 |

### Constructor: BigTiffOptions(tags) {#BigTiffOptions_tags_4}


```
 BigTiffOptions(tags) 
```

初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 用于选项初始化的标签。 |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

添加新标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 要添加的标签。 |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

添加标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 要添加的标签。 |

### Method: clone() {#clone__3}


```
 clone() 
```

克隆此实例。

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 返回深度克隆。 |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。默认使用小端字节序约定。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | 预期的 Tiff 文件格式。 |

**Returns**

| Type | Description |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | 一个新的 BigTiffOptions 对象。 |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | 选项来源。 |

**Returns**

| Type | Description |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | 选项的副本。 |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

初始化一个新的 [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 用于选项初始化的标签。 |

**Returns**

| Type | Description |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | 一个带有标签的新 BigTiffOptions 对象。 |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

按类型获取标签实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | 标签键。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 如果存在则为标签实例，否则为 null。 |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

获取有效标签计数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | 要验证的标签。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 有效标签的计数。 |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

确定标签是否存在于选项中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | 要检查的标签 ID。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 表示标签存在；否则为 <c>false</c>。 |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

移除标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | 要移除的标签。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 成功移除时返回 true |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

移除标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | 要移除的标签。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** 表示标签集合大小已更改。 |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


```
 try_set_metadata(metadata) 
```

尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | 元数据。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果 _metadata_ 不为 null 且 [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) 实例 <br/>            支持和/或实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例，则为 true；否则为 false。 |


