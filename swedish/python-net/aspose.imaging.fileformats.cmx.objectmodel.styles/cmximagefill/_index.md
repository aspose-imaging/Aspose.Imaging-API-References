---
title: "CmxImageFill-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---

**Summary:** Image fill info

**Module:** [aspose.imaging.fileformats.cmx.objectmodel.styles](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/)

**Full Name:** aspose.imaging.fileformats.cmx.objectmodel.styles.CmxImageFill

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmxImageFill()](#CmxImageFill__1) | Initierar en ny instans av klassen CmxImageFill |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| images | [CmxRasterImage[]](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/) | r/w | Hämtar eller anger bilderna. |
| is_relative | bool | r/w | Hämtar eller anger ett värde som indikerar om mönsterstorleksvärden är relativa. |
| offset_type | [TileOffsetTypes](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.enums/tileoffsettypes/) | r/w | Hämtar eller anger typen av förskjutning mellan intilliggande plattor. |
| pattern_height | float | r/w | Hämtar eller anger höjden på mönstret.<br/>            Använder gemensam dokumentavståndsenhet om [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) är <c>false</c>,<br/>            annars har dimensionen bildpixelhöjdens bråkdel. |
| pattern_width | float | r/w | Hämtar eller anger bredden på mönstret.<br/>            Använder gemensam dokumentavståndsenhet om [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) är <c>false</c>,<br/>            annars har dimensionen bildpixelbreddens bråkdel. |
| procedure | [CmxProcedure](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure/) | r/w | Hämtar eller anger proceduren. |
| rcp_offset | float | r/w | Hämtar eller anger den relativa förskjutningen mellan plattrader eller -kolumner (beror på [CmxImageFill.offset_type](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/)).<br/>            Dimensionen är bråkdelar av höjd eller bredd. |
| rotate180 | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [CmxImageSpec](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/) är upp och ner. |
| tile_offset_x | float | r/w | Hämtar eller anger plattförskjutning X. |
| tile_offset_y | float | r/w | Hämtar eller anger plattförskjutning Y. |


### Constructor: CmxImageFill() {#CmxImageFill__1}


```
 CmxImageFill() 
```

Initierar en ny instans av klassen CmxImageFill

