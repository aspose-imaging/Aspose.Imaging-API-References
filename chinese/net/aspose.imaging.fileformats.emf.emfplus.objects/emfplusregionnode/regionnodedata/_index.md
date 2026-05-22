---
title: "EmfPlusRegionNode.RegionNodeData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusRegionNode 属性。获取或设置可选的可变长度数据，该数据定义在 Type 字段中指定的区域节点数据对象。每种区域节点类型的数据内容和格式可能不同。如果节点类型为 RegionNodeDataTypeEmpty 或 RegionNodeDataTypeInfinite，则此字段不得出现。此对象是通用的，用于指定不同类型的区域节点数据，包括 Section 2.2.2.42 中的 EmfPlusRegionNodePath 对象（用于终端节点），Section 2.2.2.39 中的 EmfPlusRectF 对象（用于终端节点），以及 Section 2.2.2.41 中的 EmfPlusRegionNodeChildNodes 对象（用于非终端节点）。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/regionnodedata/
---
## EmfPlusRegionNode.RegionNodeData property

获取或设置可选的可变长度数据，该数据定义了 Type 字段中指定的区域节点数据对象。数据的内容和格式可能因不同的区域节点类型而异。如果节点类型为 RegionNodeDataTypeEmpty 或 RegionNodeDataTypeInfinite，则此字段不得出现。此对象是通用的，用于指定不同类型的区域节点数据，包括：用于终端节点的 EmfPlusRegionNodePath 对象（第 2.2.2.42 节）；用于终端节点的 EmfPlusRectF 对象（第 2.2.2.39 节）；以及用于非终端节点的 EmfPlusRegionNodeChildNodes 对象（第 2.2.2.41 节）。

```csharp
public EmfPlusStructureObjectType RegionNodeData { get; set; }
```

### 另请参见

* class [EmfPlusStructureObjectType](../../emfplusstructureobjecttype/)
* class [EmfPlusRegionNode](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfplusregionnode/)
* assembly [Aspose.Imaging](../../../)


