---
title: EmfPlusRegionNode.RegionNodeData
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusRegionNode property. Gets or sets an optional variablelength data that defines the region node data object specified in the Type field. The content and format of the data can be different for every region node type. This field MUST NOT be present if the node type is RegionNodeDataTypeEmpty or RegionNodeDataTypeInfinite This object is generic and is used to specify different types of region node data including An EmfPlusRegionNodePath object section 2.2.2.42 for a terminal node An EmfPlusRectF object section 2.2.2.39 for a terminal node and An EmfPlusRegionNodeChildNodes object section 2.2.2.41 for a nonterminal node
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/regionnodedata/
---
## EmfPlusRegionNode.RegionNodeData property

Gets or sets an optional, variable-length data that defines the region node data object specified in the Type field. The content and format of the data can be different for every region node type. This field MUST NOT be present if the node type is RegionNodeDataTypeEmpty or RegionNodeDataTypeInfinite This object is generic and is used to specify different types of region node data, including: An EmfPlusRegionNodePath object (section 2.2.2.42), for a terminal node; An EmfPlusRectF object (section 2.2.2.39), for a terminal node; and An EmfPlusRegionNodeChildNodes object (section 2.2.2.41), for a non-terminal node.

```csharp
public EmfPlusStructureObjectType RegionNodeData { get; set; }
```

### See Also

* class [EmfPlusStructureObjectType](../../emfplusstructureobjecttype/)
* class [EmfPlusRegionNode](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfplusregionnode/)
* assembly [Aspose.Imaging](../../../)


