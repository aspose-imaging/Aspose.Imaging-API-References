---
title: EmfPlusSetTsGraphics Class
type: docs
weight: 580
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

**Aspose.Imaging Version:** 23.6

The EmfPlusSetTsGraphics type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_0) | Initializes a new instance of the [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| basic_vga_colors | bool | r | Gets a value indicating whether [basic vga colors].<br/>            If set, the palette contains only the basic VGA colors. |
| have_palette | bool | r | Gets a value indicating whether [have palette].<br/>            If set, this record contains an EmfPlusPalette object (section 2.2.2.28) in the<br/>            Palette field following the graphics state data. |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Gets or sets an 8-bit unsigned integer that specifies the quality of line rendering,<br/>            including the type of line anti-aliasing. It MUST be defined in the SmoothingMode<br/>            enumeration (section 2.1.1.28). |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Gets or sets an 8-bit unsigned integer that specifies the quality of text<br/>            rendering, including the type of text anti-aliasing. It MUST be defined in the<br/>            TextRenderingHint enumeration (section 2.1.1.32). |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Gets or sets an 8-bit unsigned integer that specifies how source colors are<br/>            combined with background colors. It MUST be a value in the CompositingMode<br/>            enumeration (section 2.1.1.5). |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | Gets or sets an 8-bit unsigned integer that specifies the degree of<br/>            smoothing to apply to lines, curves and the edges of filled areas to make them appear more<br/>            continuous or sharply defined. It MUST be a value in the CompositingQuality enumeration (section 2.1.1.6). |
| render_origin_x | short | r/w | Gets or sets a 16-bit signed integer, which is the horizontal coordinate of the<br/>            origin for rendering halftoning and dithering matrixes. |
| render_origin_y | short | r/w | Gets or sets a 16-bit signed integer, which is the vertical coordinate of the origin<br/>            for rendering halftoning and dithering matrixes. |
| text_contrast | short | r/w | Gets or sets a 16-bit unsigned integer that specifies the gamma correction value<br/>            used for rendering anti-aliased and ClearType text. This value MUST be in the range 0 to 12, inclusive. |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | Gets or sets an 8-bit unsigned integer that specifies how scaling, including stretching<br/>            and shrinking, is performed. It MUST be a value in the FilterType enumeration (section 2.1.1.11). |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Gets or sets an 8-bit unsigned integer that specifies the overall quality of the image<br/>            and text-rendering process. It MUST be a value in the PixelOffsetMode enumeration (section 2.1.1.26). |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix) | r/w | Gets or sets an 192-bit EmfPlusTransformMatrix object (section 2.2.2.47) that<br/>            specifies the world space to device space transforms. |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Gets or sets an optional EmfPlusPalette object. |

### EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_0}


```
 EmfPlusSetTsGraphics(source) 
```

Initializes a new instance of the [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

