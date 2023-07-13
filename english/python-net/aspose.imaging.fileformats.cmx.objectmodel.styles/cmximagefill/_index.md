---
title: CmxImageFill Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---

Image fill info

**Module:** [aspose.imaging.fileformats.cmx.objectmodel.styles](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/)

**Full Name:** aspose.imaging.fileformats.cmx.objectmodel.styles.CmxImageFill

**Aspose.Imaging Version:** 23.6

The CmxImageFill type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [CmxImageFill()](#CmxImageFill__0) | Initializes a new instance of the CmxImageFill class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| images | [CmxRasterImage[]](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/) | r/w | Gets or sets the images. |
| procedure | [CmxProcedure](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) | r/w | Gets or sets the procedure. |
| tile_offset_x | float | r/w | Gets or sets the tile offset X. |
| tile_offset_y | float | r/w | Gets or sets the tile offset Y. |
| rcp_offset | float | r/w | Gets or sets the relative offset between tile rows or columns (depends on [offset_type](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/)).<br/>            Dimension is fractions of height of width. |
| offset_type | [TileOffsetTypes](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.enums/tileoffsettypes/) | r/w | Gets or sets the type of the offset between adjacent tiles. |
| pattern_width | float | r/w | Gets or sets the width of the pattern.<br/>            Uses common document distance measure unit in case if [is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) is <c>false</c>,<br/>            otherwise has the dimension of the image pixel width fraction. |
| pattern_height | float | r/w | Gets or sets the height of the pattern.<br/>            Uses common document distance measure unit in case if [is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) is <c>false</c>,<br/>            otherwise has the dimension of the image pixel height fraction. |
| is_relative | bool | r/w | Gets or sets a value indicating whether patterns size values is relative. |
| rotate180 | bool | r/w | Gets or sets a value indicating whether this ImageSpec is upside down. |

### CmxImageFill() {#CmxImageFill__0}


```
 CmxImageFill() 
```

Initializes a new instance of the CmxImageFill class

