---
title: JpegOptions Class
type: docs
weight: 160
url: /python-net/aspose.imaging.imageoptions/jpegoptions/
---

The jpeg file format create options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.Imaging Version:** 23.6

The JpegOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [JpegOptions()](#JpegOptions__0) | Initializes a new instance of the [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) class. |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_1) | Initializes a new instance of the [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| default_memory_allocation_limit | int | r/w | Gets or sets the default memory allocation limit. |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | Gets or sets the jfif. |
| comment | string | r/w | Gets or sets the jpeg file comment. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | Get or set exif data container |
| compression_type | [JpegCompressionMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressionmode/) | r/w | Gets or sets the compression type. |
| color_type | [JpegCompressionColorMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Gets or sets the color type for jpeg image. |
| bits_per_channel | byte | r/w | Gets or sets bits per channel for lossless jpeg image. Now we support from 2 to 8 bits per channel. |
| quality | int | r/w | Gets or sets image quality. |
| scaled_quality | int | r | The scaled quality. |
| rd_opt_settings | [RdOptimizerSettings](/imaging/python-net/aspose.imaging.imageoptions/rdoptimizersettings) | r/w | Gets or sets the RD optimizer settings. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | The destination RGB color profile for CMYK jpeg images. Use for saving images. Must be in pair with CMYKColorProfile for correct color conversion. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | The destination CMYK color profile for CMYK jpeg images. Use for saving images. Must be in pair with RGBColorProfile for correct color conversion. |
| jpeg_ls_allowed_lossy_error | int | r/w | Gets or sets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Gets or sets the JPEG-LS interleave mode. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Gets or sets the JPEG-LS preset parameters. |
| horizontal_sampling | byte | r/w | Gets or sets the horizontal subsamplings for each component. |
| vertical_sampling | byte | r/w | Gets or sets the vertical subsamplings for each component. |
| sample_rounding_mode | [SampleRoundingMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/) | r/w | Gets or sets the sample rounding mode to fit an 8-bit value to an n-bit value. <see cref="P:JpegOptions.BitsPerChannel" /> |
| preblend_alpha_if_present | bool | r/w | Gets or sets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present. |
| resolution_unit | [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit) | r/w | Gets or sets the resolution unit. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__2) | Clones this instance. |

### JpegOptions() {#JpegOptions__0}


```
 JpegOptions() 
```

Initializes a new instance of the [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) class.

### JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_1}


```
 JpegOptions(jpeg_options) 
```

Initializes a new instance of the [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions) | The JPEG options. |

### clone() {#clone__2}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


