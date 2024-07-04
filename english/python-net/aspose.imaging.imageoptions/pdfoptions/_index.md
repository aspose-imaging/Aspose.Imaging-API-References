---
title: PdfOptions Class
type: docs
weight: 230
url: /python-net/aspose.imaging.imageoptions/pdfoptions/
---

**Summary:** The PDF options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfOptions

**Inheritance:** IHasXmpData, IHasMetadata, ImageOptionsBase

**Aspose.Imaging Version:** 24.7.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfOptions()](#PdfOptions__1) | Initializes a new instance of the [PdfOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions) | r/w | The multipage options |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef) | r/w | Gets or sets the size of the page. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. |
| pdf_core_options | [PdfCoreOptions](/imaging/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/) | r/w | The PDF core options |
| pdf_document_info | [PdfDocumentInfo](/imaging/python-net/aspose.imaging.fileformats.pdf/pdfdocumentinfo/) | r/w | Gets or sets metadata for document. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source) | r/w | Gets or sets the source to create image in. |
| use_original_image_resolution | bool | r/w | Gets or sets a value indicating to use the original image DPI resolution |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: PdfOptions() {#PdfOptions__1}


```
 PdfOptions() 
```

Initializes a new instance of the [PdfOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfoptions/) class.

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Returns shallow copy of this instance |


