---
title: EmfPlusRegionNode
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusRegionNode 对象指定图形区域的节点
type: docs
weight: 5720
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
## EmfPlusRegionNode class

EmfPlusRegionNode 对象指定图形区域的节点。

```csharp
public sealed class EmfPlusRegionNode : EmfPlusStructureObjectType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusRegionNode](emfplusregionnode)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [RegionNodeData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/regionnodedata) { get; set; } | 获取或设置一个可选的可变长度数据，该数据定义在 Type 字段中指定的区域节点 数据对象。对于每个区域 节点类型，数据的内容和 格式可能不同。如果节点 类型为 RegionNodeDataTypeEmpty 或 RegionNodeDataTypeInfinite 则该字段不得存在:此对象是通用的，用于指定不同类型的区域节点数据，包括: EmfPlusRegionNodePath 对象（第 2.2.2.42 节），用于终端节点； EmfPlusRectF 对象（第 2.2.2.39 节），用于终端节点；和 EmfPlusRegionNodeChildNodes 对象（第 2.2.2.41 节），用于非终端节点。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/type) { get; set; } | 获取或设置 32 位无符号整数，指定 RegionNodeData 字段中 数据的类型。该值必须在 RegionNodeDataType 枚举（第 2.1.1.27 节）中定义。 |

### 也可以看看

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->