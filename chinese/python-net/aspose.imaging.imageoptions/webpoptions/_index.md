---
title: "WebPOptions 类"
type: docs
weight: 360
url: /zh/python-net/aspose.imaging.imageoptions/webpoptions/
---

**Summary:** Create modern WebP raster web images using our API, featuring robust support for<br/>            lossless and lossy compression, as well as alpha channels and animation loops.<br/>            Enhance your web content with dynamic visuals while optimizing file sizes<br/>            for improved loading speeds and user experience.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WebPOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [WebPOptions()](#WebPOptions__1) | 初始化 [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| anim_background_color | int | r/w | 获取或设置动画背景的颜色。 |
| anim_loop_count | int | r/w | 获取或设置动画循环计数。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| lossless | bool | r/w | 获取或设置一个值，指示此 [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) 是否为无损。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| quality | float | r/w | 获取或设置质量。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: WebPOptions() {#WebPOptions__1}


```
 WebPOptions() 
```

初始化 [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) 类的新实例。

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


