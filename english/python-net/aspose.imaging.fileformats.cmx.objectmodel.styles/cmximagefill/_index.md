---
title: CmxImageFill Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---

**Summary:** Image fill info

**Module:** [aspose.imaging.fileformats.cmx.objectmodel.styles](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/)

**Full Name:** aspose.imaging.fileformats.cmx.objectmodel.styles.CmxImageFill

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmxImageFill()](#CmxImageFill__1) | Initializes a new instance of the CmxImageFill class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| images | [CmxRasterImage[]](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/) | r/w | Gets or sets the images. |
| is_relative | bool | r/w | Gets or sets a value indicating whether patterns size values is relative. |
| offset_type | [TileOffsetTypes](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.enums/tileoffsettypes/) | r/w | Gets or sets the type of the offset between adjacent tiles. |
| pattern_height | float | r/w | Gets or sets the height of the pattern.<br/>            Uses common document distance measure unit in case if [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) is <c>false</c>,<br/>            otherwise has the dimension of the image pixel height fraction. |
| pattern_width | float | r/w | Gets or sets the width of the pattern.<br/>            Uses common document distance measure unit in case if [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) is <c>false</c>,<br/>            otherwise has the dimension of the image pixel width fraction. |
| procedure | [CmxProcedure](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure/) | r/w | Gets or sets the procedure. |
| rcp_offset | float | r/w | Gets or sets the relative offset between tile rows or columns (depends on [CmxImageFill.offset_type](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/)).<br/>            Dimension is fractions of height of width. |
| rotate180 | bool | r/w | Gets or sets a value indicating whether this [CmxImageSpec](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/) is upside down. |
| tile_offset_x | float | r/w | Gets or sets the tile offset X. |
| tile_offset_y | float | r/w | Gets or sets the tile offset Y. |


### Constructor: CmxImageFill() {#CmxImageFill__1}


```
 CmxImageFill() 
```

Initializes a new instance of the CmxImageFill class

