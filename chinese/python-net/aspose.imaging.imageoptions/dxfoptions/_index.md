---
title: "DxfOptions 类"
type: docs
weight: 80
url: /zh/python-net/aspose.imaging.imageoptions/dxfoptions/
---

**Summary:** API for Drawing Interchange Format (DXF) vector image creation offers<br/>            tailored solutions for generating AutoCAD drawing files with precision and<br/>            flexibility. Designed specifically for working with text lines and Bezier<br/>            curves, developers can efficiently manipulate these elements, count Bezier<br/>            points, and convert curves into polylines for seamless exporting, ensuring<br/>            compatibility and fidelity in DXF vector images.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DxfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [DxfOptions()](#DxfOptions__1) | 初始化一个新的 DxfOptions 类实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bezier_point_count | System.Byte | r/w | 在将贝塞尔曲线转换为折线时要生成的点数，最少 4。用于当 [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) 和 [DxfOptions.convert_text_beziers](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) 均  	/// 设置为 <c>true</c> 时 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| convert_text_beziers | bool | r/w | 当 [DxfOptions.text_as_lines](/imaging/python-net/aspose.imaging.imageoptions/dxfoptions/) 被设置为 <c>true</c> 时生效。是否将文本轮廓中的贝塞尔曲线转换为多点折线。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| text_as_lines | bool | r/w | 文本是应导出为由折线组成的轮廓（默认），还是可编辑的 Autocad TEXT 实体。<br/>            如果设置了此选项 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: DxfOptions() {#DxfOptions__1}


```
 DxfOptions() 
```

初始化一个新的 DxfOptions 类实例

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


## **Examples**
### This example demonstrates export to Dxf format {#example_3}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DxfOptions
#创建 Image 实例并使用磁盘位置的现有图像文件进行初始化
with Image.load("input.svg") as image:
	options = DxfOptions()
	options.text_as_lines = True
	options.convert_text_beziers = True
	options.bezier_point_count = 20
	image.save("output.dxf", options)


```

