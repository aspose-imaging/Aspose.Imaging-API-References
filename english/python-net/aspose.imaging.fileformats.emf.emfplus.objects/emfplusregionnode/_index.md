---
title: EmfPlusRegionNode Class
type: docs
weight: 600
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | Initializes a new instance of the EmfPlusRegionNode class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | Gets or sets an optional, variable-length data that defines the region node<br/>            data object specified in the Type field. The content and<br/>            format of the data can be different for every region<br/>            node type. This field MUST NOT be present if the node<br/>            type is RegionNodeDataTypeEmpty or RegionNodeDataTypeInfinite<br/>            This object is generic and is used to specify different types of region node data, including:<br/>            An EmfPlusRegionNodePath object (section 2.2.2.42), for a terminal node;<br/>            An EmfPlusRectF object (section 2.2.2.39), for a terminal node; and<br/>            An EmfPlusRegionNodeChildNodes object (section 2.2.2.41), for a non-terminal node. |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | Gets or sets 32-bit unsigned integer that specifies the type of<br/>            data in the RegionNodeData field. This value MUST be defined in the<br/>            RegionNodeDataType enumeration (section 2.1.1.27). |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

Initializes a new instance of the EmfPlusRegionNode class

