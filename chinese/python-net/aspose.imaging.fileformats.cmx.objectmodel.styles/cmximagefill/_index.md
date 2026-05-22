---
title: "CmxImageFill 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---

**Summary:** Image fill info

**Module:** [aspose.imaging.fileformats.cmx.objectmodel.styles](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/)

**Full Name:** aspose.imaging.fileformats.cmx.objectmodel.styles.CmxImageFill

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [CmxImageFill()](#CmxImageFill__1) | 初始化 CmxImageFill 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| images | [CmxRasterImage[]](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/) | r/w | 获取或设置图像。 |
| is_relative | bool | r/w | 获取或设置一个值，指示模式大小值是否相对。 |
| offset_type | [TileOffsetTypes](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.enums/tileoffsettypes/) | r/w | 获取或设置相邻瓦片之间偏移的类型。 |
| pattern_height | float | r/w | 获取或设置模式的高度。<br/>            如果 [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) 为 <c>false</c>，则使用通用文档距离度量单位，<br/>            否则为图像像素高度分数的尺寸。 |
| pattern_width | float | r/w | 获取或设置模式的宽度。<br/>            如果 [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) 为 <c>false</c>，则使用通用文档距离度量单位，<br/>            否则为图像像素宽度分数的尺寸。 |
| procedure | [CmxProcedure](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure/) | r/w | 获取或设置过程。 |
| rcp_offset | float | r/w | 获取或设置瓦片行或列之间的相对偏移（取决于 [CmxImageFill.offset_type](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/)）。<br/>            维度是高度或宽度的分数。 |
| rotate180 | bool | r/w | 获取或设置一个值，指示此 [CmxImageSpec](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/) 是否颠倒。 |
| tile_offset_x | float | r/w | 获取或设置瓦片偏移 X。 |
| tile_offset_y | float | r/w | 获取或设置瓦片偏移 Y。 |


### Constructor: CmxImageFill() {#CmxImageFill__1}


```
 CmxImageFill() 
```

初始化 CmxImageFill 类的新实例

