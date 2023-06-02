---
title: EmfPlusSetTsGraphics Class
type: docs
weight: 580
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusSetTsGraphics type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusSetTsGraphics(source)|Initializes a new instance of the EmfPlusSetTsGraphics class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|basic_vga_colors|Gets a value indicating whether [basic vga colors].<br/>            If set, the palette contains only the basic VGA colors.|
|have_palette|Gets a value indicating whether [have palette].<br/>            If set, this record contains an EmfPlusPalette object (section 2.2.2.28) in the<br/>            Palette field following the graphics state data.|
|anti_alias_mode|Gets or sets an 8-bit unsigned integer that specifies the quality of line rendering,<br/>            including the type of line anti-aliasing. It MUST be defined in the SmoothingMode<br/>            enumeration (section 2.1.1.28).|
|text_render_hint|Gets or sets an 8-bit unsigned integer that specifies the quality of text<br/>            rendering, including the type of text anti-aliasing. It MUST be defined in the<br/>            TextRenderingHint enumeration (section 2.1.1.32).|
|compositing_mode|Gets or sets an 8-bit unsigned integer that specifies how source colors are<br/>            combined with background colors. It MUST be a value in the CompositingMode<br/>            enumeration (section 2.1.1.5).|
|compositing_quality|Gets or sets an 8-bit unsigned integer that specifies the degree of<br/>            smoothing to apply to lines, curves and the edges of filled areas to make them appear more<br/>            continuous or sharply defined. It MUST be a value in the CompositingQuality enumeration (section 2.1.1.6).|
|render_origin_x|Gets or sets a 16-bit signed integer, which is the horizontal coordinate of the<br/>            origin for rendering halftoning and dithering matrixes.|
|render_origin_y|Gets or sets a 16-bit signed integer, which is the vertical coordinate of the origin<br/>            for rendering halftoning and dithering matrixes.|
|text_contrast|Gets or sets a 16-bit unsigned integer that specifies the gamma correction value<br/>            used for rendering anti-aliased and ClearType text. This value MUST be in the range 0 to 12, inclusive.|
|filter_type|Gets or sets an 8-bit unsigned integer that specifies how scaling, including stretching<br/>            and shrinking, is performed. It MUST be a value in the FilterType enumeration (section 2.1.1.11).|
|pixel_offset|Gets or sets an 8-bit unsigned integer that specifies the overall quality of the image<br/>            and text-rendering process. It MUST be a value in the PixelOffsetMode enumeration (section 2.1.1.26).|
|world_to_device|Gets or sets an 192-bit EmfPlusTransformMatrix object (section 2.2.2.47) that<br/>            specifies the world space to device space transforms.|
|palette|Gets or sets an optional EmfPlusPalette object.|
