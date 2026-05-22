---
title: "IcoOptions 类"
type: docs
weight: 140
url: /zh/python-net/aspose.imaging.imageoptions/icooptions/
---

**Summary:** Create custom ICO image files for application icons effortlessly with our API,<br/>            empowering you to represent your software seamlessly. Our API supports PNG and<br/>            BMP image frames with various bits per pixel values, ensuring versatility and<br/>            compatibility for your icon creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.IcoOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [IcoOptions()](#IcoOptions__1) | 初始化一个新的 [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) 类实例，ICO 帧格式等于 Png，<br/>            bitsPerPixel 等于 32。 |
| [IcoOptions(format, bits_per_pixel)](#IcoOptions_format_bits_per_pixel_2) | 初始化一个新的 [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | 获取或设置每像素位数值。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r/w | 获取或设置 ICO 帧格式。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: IcoOptions() {#IcoOptions__1}


```
 IcoOptions() 
```

初始化一个新的 [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) 类实例，ICO 帧格式等于 Png，<br/>            bitsPerPixel 等于 32。

### Constructor: IcoOptions(format, bits_per_pixel) {#IcoOptions_format_bits_per_pixel_2}


```
 IcoOptions(format, bits_per_pixel) 
```

初始化一个新的 [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | ICO 帧格式。<br/>            请注意，ICO 图像仅支持 [FileFormat.PNG](/imaging/python-net/aspose.imaging/fileformat/) 和 [FileFormat.BMP](/imaging/python-net/aspose.imaging/fileformat/) 图像作为条目。 |
| bits_per_pixel | int | 每像素位数值。 |

### Method: clone() {#clone__1}


```
 clone() 
```

创建此实例的成员逐个克隆。

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 此实例的成员逐个克隆。 |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


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
| bool | 如果 [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) 实例支持和/或实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例，则为 true；否则为 false。 |


