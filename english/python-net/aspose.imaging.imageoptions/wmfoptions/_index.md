---
title: WmfOptions Class
type: docs
weight: 370
url: /python-net/aspose.imaging.imageoptions/wmfoptions/
---

**Summary:** The wmf options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfOptions

**Inheritance:** IHasXmpData, IHasMetadata, MetafileOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfOptions()](#WmfOptions__1) | Initializes a new instance of the WmfOptions class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| compress | bool | r/w | Gets or sets a value indicating whether this [ICompressedOptions](/imaging/python-net/aspose.fileformats.core.imageoptions/icompressedoptions/) is compressed. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets Xmp data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a memberwise clone of this instance. |


### Constructor: WmfOptions() {#WmfOptions__1}


```
 WmfOptions() 
```

Initializes a new instance of the WmfOptions class

### Method: clone() {#clone__1}


```
 clone() 
```

Creates a memberwise clone of this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | A memberwise clone of this instance. |


## **Examples**
### The following example shows how to convert a wmz images to wmf fromat {#example_159}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import WmfRasterizationOptions, WmfOptions
from os.path import join

file: str = "example.wmz"
base_folder: str = join("D:", "Compressed")
input_file: str = join(base_folder, file)
out_file: str = input_file + ".wmf"
with Image.load(input_file) as image:
	obj_init = WmfRasterizationOptions()
	obj_init.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = WmfOptions()
	obj_init2.vector_rasterization_options = obj_init
	image.save(out_file, obj_init2)


```

