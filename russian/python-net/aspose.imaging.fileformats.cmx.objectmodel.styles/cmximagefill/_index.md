---
title: "Класс CmxImageFill"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---

**Summary:** Image fill info

**Module:** [aspose.imaging.fileformats.cmx.objectmodel.styles](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/)

**Full Name:** aspose.imaging.fileformats.cmx.objectmodel.styles.CmxImageFill

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmxImageFill()](#CmxImageFill__1) | Инициализирует новый экземпляр класса CmxImageFill |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| images | [CmxRasterImage[]](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/) | r/w | Получает или задает изображения. |
| is_relative | bool | r/w | Получает или задает значение, указывающее, являются ли значения размеров шаблонов относительными. |
| offset_type | [TileOffsetTypes](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.enums/tileoffsettypes/) | r/w | Получает или задает тип смещения между соседними плитками. |
| pattern_height | float | r/w | Получает или задает высоту шаблона.<br/>            Использует общую единицу измерения расстояния документа, если [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) равно <c>false</c>,<br/>            иначе имеет размерность доли высоты пикселя изображения. |
| pattern_width | float | r/w | Получает или задает ширину шаблона.<br/>            Использует общую единицу измерения расстояния документа, если [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) равно <c>false</c>,<br/>            иначе имеет размерность доли ширины пикселя изображения. |
| procedure | [CmxProcedure](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure/) | r/w | Получает или задает процедуру. |
| rcp_offset | float | r/w | Получает или задает относительное смещение между строками или столбцами плиток (зависит от [CmxImageFill.offset_type](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/)).<br/>            Размерность — доли высоты или ширины. |
| rotate180 | bool | r/w | Получает или задает значение, указывающее, является ли этот [CmxImageSpec](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/) перевёрнутым вверх дном. |
| tile_offset_x | float | r/w | Получает или задает смещение плитки по X. |
| tile_offset_y | float | r/w | Получает или задает смещение плитки по Y. |


### Constructor: CmxImageFill() {#CmxImageFill__1}


```
 CmxImageFill() 
```

Инициализирует новый экземпляр класса CmxImageFill

