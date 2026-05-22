---
title: "类 EmfPlusRegionNode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusRegionNode 类。EmfPlusRegionNode 对象指定图形区域的节点"
type: docs
weight: 5840
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
## EmfPlusRegionNode class

该 EmfPlusRegionNode 对象指定图形区域的节点。

```csharp
public sealed class EmfPlusRegionNode : EmfPlusStructureObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusRegionNode](emfplusregionnode/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [RegionNodeData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/regionnodedata/) { get; set; } | 获取或设置可选的可变长度数据，该数据定义了 Type 字段中指定的区域节点数据对象。数据的内容和格式可能因不同的区域节点类型而异。如果节点类型为 RegionNodeDataTypeEmpty 或 RegionNodeDataTypeInfinite，则此字段不得出现。此对象是通用的，用于指定不同类型的区域节点数据，包括：用于终端节点的 EmfPlusRegionNodePath 对象（第 2.2.2.42 节）；用于终端节点的 EmfPlusRectF 对象（第 2.2.2.39 节）；以及用于非终端节点的 EmfPlusRegionNodeChildNodes 对象（第 2.2.2.41 节）。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/type/) { get; set; } | 获取或设置 32 位无符号整数，指定 RegionNodeData 字段中数据的类型。此值必须在 RegionNodeDataType 枚举中定义（第 2.1.1.27 节）。 |

### 另请参见

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


