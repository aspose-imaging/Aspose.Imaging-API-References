---
title: "CmxImageFill Classe"
type: docs
weight: 40
url: /fr/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---

**Summary:** Image fill info

**Module:** [aspose.imaging.fileformats.cmx.objectmodel.styles](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/)

**Full Name:** aspose.imaging.fileformats.cmx.objectmodel.styles.CmxImageFill

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmxImageFill()](#CmxImageFill__1) | Initialise une nouvelle instance de la classe CmxImageFill |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| images | [CmxRasterImage[]](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/) | r/w | Obtient ou définit les images. |
| is_relative | bool | r/w | Obtient ou définit une valeur indiquant si les valeurs de taille des motifs sont relatives. |
| offset_type | [TileOffsetTypes](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.enums/tileoffsettypes/) | r/w | Obtient ou définit le type de décalage entre les tuiles adjacentes. |
| pattern_height | float | r/w | Obtient ou définit la hauteur du motif.<br/>            Utilise l'unité de mesure de distance de document commune au cas où [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) est <c>false</c>,<br/>            sinon possède la dimension de la fraction de hauteur du pixel d'image. |
| pattern_width | float | r/w | Obtient ou définit la largeur du motif.<br/>            Utilise l'unité de mesure de distance de document commune au cas où [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) est <c>false</c>,<br/>            sinon possède la dimension de la fraction de largeur du pixel d'image. |
| procedure | [CmxProcedure](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure/) | r/w | Obtient ou définit la procédure. |
| rcp_offset | float | r/w | Obtient ou définit le décalage relatif entre les lignes ou colonnes de tuiles (dépend de [CmxImageFill.offset_type](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/)).<br/>            La dimension est exprimée en fractions de la hauteur ou de la largeur. |
| rotate180 | bool | r/w | Obtient ou définit une valeur indiquant si ce [CmxImageSpec](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/) est à l'envers. |
| tile_offset_x | float | r/w | Obtient ou définit le décalage de tuile X. |
| tile_offset_y | float | r/w | Obtient ou définit le décalage de tuile Y. |


### Constructor: CmxImageFill() {#CmxImageFill__1}


```
 CmxImageFill() 
```

Initialise une nouvelle instance de la classe CmxImageFill

