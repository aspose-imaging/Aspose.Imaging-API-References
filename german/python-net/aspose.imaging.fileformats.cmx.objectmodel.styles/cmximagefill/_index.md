---
title: "CmxImageFill Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---

**Summary:** Image fill info

**Module:** [aspose.imaging.fileformats.cmx.objectmodel.styles](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/)

**Full Name:** aspose.imaging.fileformats.cmx.objectmodel.styles.CmxImageFill

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CmxImageFill()](#CmxImageFill__1) | Initialisiert eine neue Instanz der CmxImageFill-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| images | [CmxRasterImage[]](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/) | r/w | Liest oder setzt die Bilder. |
| is_relative | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Größenwerte der Muster relativ sind. |
| offset_type | [TileOffsetTypes](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.enums/tileoffsettypes/) | r/w | Liest oder setzt den Typ des Versatzes zwischen benachbarten Kacheln. |
| pattern_height | float | r/w | Liest oder setzt die Höhe des Musters.<br/>            Verwendet die übliche Dokumentabstandseinheit, falls [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) <c>false</c> ist,<br/>            andernfalls hat sie die Dimension des Bildpixel-Höhenanteils. |
| pattern_width | float | r/w | Liest oder setzt die Breite des Musters.<br/>            Verwendet die übliche Dokumentabstandseinheit, falls [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) <c>false</c> ist,<br/>            andernfalls hat sie die Dimension des Bildpixel-Breitenanteils. |
| procedure | [CmxProcedure](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure/) | r/w | Liest oder setzt das Verfahren. |
| rcp_offset | float | r/w | Liest oder setzt den relativen Versatz zwischen Kachelreihen oder -spalten (abhängig von [CmxImageFill.offset_type](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/)).<br/>            Die Dimension ist ein Bruchteil der Höhe oder Breite. |
| rotate180 | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [CmxImageSpec](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/) umgedreht ist. |
| tile_offset_x | float | r/w | Liest oder setzt den Kachelversatz X. |
| tile_offset_y | float | r/w | Liest oder setzt den Kachelversatz Y. |


### Constructor: CmxImageFill() {#CmxImageFill__1}


```
 CmxImageFill() 
```

Initialisiert eine neue Instanz der CmxImageFill-Klasse

