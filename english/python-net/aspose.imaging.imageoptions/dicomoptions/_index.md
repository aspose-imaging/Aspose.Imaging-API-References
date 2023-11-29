---
title: DicomOptions Class
type: docs
weight: 60
url: /python-net/aspose.imaging.imageoptions/dicomoptions/
---

**Summary:** The DICOM file format creation options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DicomOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.11.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DicomOptions()](#DicomOptions__1) | Initializes a new instance of the [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.fileformats.dicom/colortype/) | r/w | Gets or sets the type of the color. |
| compression | [Compression](/imaging/python-net/aspose.imaging.fileformats.dicom/compression/) | r/w | Gets or sets the compression. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the Xmp data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: DicomOptions() {#DicomOptions__1}


```
 DicomOptions() 
```

Initializes a new instance of the [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) class.

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


## **Examples**
### The following example shows export to DICOM file format (single and multipage). {#example_17}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DicomOptions

fileName = "sample.jpg"
inputFileNameSingle = fileName
inputFileNameMultipage = "multipage.tif"
outputFileNameSingleDcm = "output.dcm"
outputFileNameMultipageDcm = "outputMultipage.dcm"

# The next code sample converts JPEG image to DICOM file format
with Image.load(inputFileNameSingle) as image:
	image.save(outputFileNameSingleDcm, DicomOptions())

# DICOM format supports multipage images. You can convert GIF or TIFF images to DICOM in the same way as JPEG images
with Image.load(inputFileNameMultipage) as image_multiple:
	image_multiple.save(outputFileNameMultipageDcm, DicomOptions())


```

