---
title: EmfPlusRegionNode Class
type: docs
weight: 600
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

The EmfPlusRegionNode object specifies nodes of a graphics region.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusRegionNode type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusRegionNode()|Initializes a new instance of the EmfPlusRegionNode class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|region_node_data|Gets or sets an optional, variable-length data that defines the region node<br/>            data object specified in the Type field. The content and<br/>            format of the data can be different for every region<br/>            node type. This field MUST NOT be present if the node<br/>            type is RegionNodeDataTypeEmpty or RegionNodeDataTypeInfinite<br/>            This object is generic and is used to specify different types of region node data, including:<br/>            An EmfPlusRegionNodePath object (section 2.2.2.42), for a terminal node;<br/>            An EmfPlusRectF object (section 2.2.2.39), for a terminal node; and<br/>            An EmfPlusRegionNodeChildNodes object (section 2.2.2.41), for a non-terminal node.|
|type|Gets or sets 32-bit unsigned integer that specifies the type of<br/>            data in the RegionNodeData field. This value MUST be defined in the<br/>            RegionNodeDataType enumeration (section 2.1.1.27).|
