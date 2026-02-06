---
title: Class EmfPlusRegionNode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusRegionNode class. The EmfPlusRegionNode object specifies nodes of a graphics region
type: docs
weight: 5840
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
## EmfPlusRegionNode class

The EmfPlusRegionNode object specifies nodes of a graphics region.

```csharp
public sealed class EmfPlusRegionNode : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusRegionNode](emfplusregionnode/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [RegionNodeData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/regionnodedata/) { get; set; } | Gets or sets an optional, variable-length data that defines the region node data object specified in the Type field. The content and format of the data can be different for every region node type. This field MUST NOT be present if the node type is RegionNodeDataTypeEmpty or RegionNodeDataTypeInfinite This object is generic and is used to specify different types of region node data, including: An EmfPlusRegionNodePath object (section 2.2.2.42), for a terminal node; An EmfPlusRectF object (section 2.2.2.39), for a terminal node; and An EmfPlusRegionNodeChildNodes object (section 2.2.2.41), for a non-terminal node. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/type/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the type of data in the RegionNodeData field. This value MUST be defined in the RegionNodeDataType enumeration (section 2.1.1.27). |

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


