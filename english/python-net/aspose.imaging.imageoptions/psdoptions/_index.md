---
title: PsdOptions Class
type: docs
weight: 250
url: /python-net/aspose.imaging.imageoptions/psdoptions/
---

The psd file format create options.

**Namespace:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Class Name:** aspose.imaging.imageoptions.PsdOptions

**Assembly:**  Aspose.Imaging Version: 23.5.0

The PsdOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|PsdOptions()|Initializes a new instance of the [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) class.|
|PsdOptions(options)|Initializes a new instance of the PsdOptions class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|xmp_data|Get or set XMP data container|
|source|Gets or sets the source to create image in.|
|palette|Gets or sets the color palette.|
|resolution_settings|Gets or sets the resolution settings.|
|vector_rasterization_options|Gets or sets the vector rasterization options.|
|buffer_size_hint|Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.|
|multi_page_options|The multipage options|
|full_frame|Gets or sets a value indicating whether [full frame].|
|version|Gets or sets the psd file version.|
|compression_method|Gets or sets the psd compression method.|
|psd_version|Gets or sets the file format version. It can be PSD or PSB.|
|color_mode|Gets or sets the psd color mode.|
|channel_bits_count|Gets or sets the bits count per color channel.|
|channels_count|Gets or sets the color channels count.|
|remove_global_text_engine_resource|Gets or sets a value indicating whether - Remove the global text engine resource - Used for some text-layered psd files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related).<br/>            After using this option, user need to Make next in opened in Photoshop file: Menu "Text" -> "Process absent fonts". After that operation all text will appear again.<br/>            Please note, that this operation may cause some final layout changes.|
|refresh_image_preview_data|Gets or sets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers.<br/>            Please note, text layers drawing to final layout is not supported for Compact Framework platform|
|vectorization_options|Gets or sets the PSD vectorization options.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|clone()|Clones this instance.|
