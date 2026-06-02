---
title: "EmfOptions 类"
type: docs
weight: 90
url: /zh/python-net/aspose.imaging.imageoptions/emfoptions/
---

**Summary:** The Emf options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.EmfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, MetafileOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfOptions()](#EmfOptions__1) | 初始化一个新的 EmfOptions 类实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| compress | bool | r/w | 获取或设置一个值，指示此 [ICompressedOptions](/imaging/python-net/aspose.fileformats.core.imageoptions/icompressedoptions/) 是否已压缩。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 实例。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 Xmp 数据。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: EmfOptions() {#EmfOptions__1}


```
 EmfOptions() 
```

初始化一个新的 EmfOptions 类实例

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
| bool | 如果 _metadata_ 不为 null 且 [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) 实例 <br/>            支持和/或实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例，则为 true；否则为 false。 |


## **Examples**
### The following example shows how to convert a emz images to emf format {#example_191}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import EmfRasterizationOptions, EmfOptions
from os.path import join

file: str = "example.emz"
base_folder: str = join("D:", "Compressed")
input_file: str = join(base_folder, file)
out_file: str = input_file + ".emf"
with Image.load(input_file) as image:
	obj_init = EmfRasterizationOptions()
	obj_init.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = EmfOptions()
	obj_init2.vector_rasterization_options = obj_init
	image.save(out_file, obj_init2)


```

### The following example shows how to convert a emf images to emz format {#example_194}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import EmfRasterizationOptions, EmfOptions

file = "input.emf"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".emz"
with Image.load(input_file) as image:
	vector_rasterization_options = EmfRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = EmfOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)


```

