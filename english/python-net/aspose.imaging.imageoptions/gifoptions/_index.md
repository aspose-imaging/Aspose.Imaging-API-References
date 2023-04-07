---
title: GifOptions Class
type: docs
weight: 110
url: /python-net/api-reference/aspose.imaging.imageoptions/gifoptions/
---

The gif file format creation options.

**Namespace:** [aspose.imaging.imageoptions](/imaging/python-net/api-reference/aspose.imaging.imageoptions/)

**Full Class Name:** aspose.imaging.imageoptions.GifOptions

**Assembly:**  Aspose.Imaging Version: 23.3.0

The GifOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|GifOptions()|Initializes a new instance of the [GifOptions](/imaging/python-net/api-reference/aspose.imaging.imageoptions/gifoptions/) class.|
|GifOptions(gif_options)|Initializes a new instance of the GifOptions class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|xmp_data|Gets or sets the XMP metadata container.|
|source|Gets or sets the source to create image in.|
|palette|Gets or sets the color palette.|
|resolution_settings|Gets or sets the resolution settings.|
|vector_rasterization_options|Gets or sets the vector rasterization options.|
|buffer_size_hint|Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.|
|multi_page_options|The multipage options|
|full_frame|Gets or sets a value indicating whether [full frame].|
|do_palette_correction|Gets or sets a value indicating whether palette correction is applied.|
|loops_count|Gets or sets the loops count (Default 1 loop)|
|color_resolution|Gets or sets the GIF color resolution.|
|is_palette_sorted|Gets or sets a value indicating whether palette entries are sorted.|
|pixel_aspect_ratio|Gets or sets the GIF pixel aspect ratio.|
|background_color_index|Gets or sets the GIF background color index.|
|has_trailer|Gets or sets a value indicating whether GIF has trailer.|
|interlaced|True if image should be interlaced.|
|max_diff|Gets or sets the maximum allowed pixel difference. If greater than zero, lossy compression will be used.<br/>            Recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy.<br/>            It works best when only little loss is introduced, and due to limitation of the compression algorithm very high loss levels won't give as much gain.<br/>            The range of allowed values is [0, 1000].|
|background_color|Gets or sets the background color.|
|has_transparent_color|Gets or sets a value indicating whether GIF image has transparent color.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|clone()|Clones this instance.|
