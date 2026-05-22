---
title: "EmfPlusRegionNode 类"
type: docs
weight: 600
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | 初始化 EmfPlusRegionNode 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | 获取或设置可选的可变长度数据，用于定义在 Type 字段中指定的区域节点数据对象。数据的内容和<br/>            格式可能因不同的区域节点类型而异。如果节点类型为 RegionNodeDataTypeEmpty 或 RegionNodeDataTypeInfinite，则此字段不得出现。<br/>            此对象是通用的，用于指定不同类型的区域节点数据，包括：<br/>            EmfPlusRegionNodePath 对象（第 2.2.2.42 节），用于终端节点；<br/>            EmfPlusRectF 对象（第 2.2.2.39 节），用于终端节点；以及<br/>            EmfPlusRegionNodeChildNodes 对象（第 2.2.2.41 节），用于非终端节点。 |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | 获取或设置指定 RegionNodeData 字段中数据类型的 32 位无符号整数。此值必须在 RegionNodeDataType 枚举（第 2.1.1.27 节）中定义。 |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

初始化 EmfPlusRegionNode 类的新实例

