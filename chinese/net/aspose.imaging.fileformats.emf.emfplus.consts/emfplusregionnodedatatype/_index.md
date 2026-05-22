---
title: "枚举 EmfPlusRegionNodeDataType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusRegionNodeDataType 枚举。RegionNodeDataType 枚举定义了区域节点数据的类型。"
type: docs
weight: 5160
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
## EmfPlusRegionNodeDataType enumeration

RegionNodeDataType 枚举定义了区域节点数据的类型。

```csharp
public enum EmfPlusRegionNodeDataType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| RegionNodeDataTypeAnd | `1` | 指定具有子节点的区域节点。应对由 [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) 对象（第 2.2.2.41 节）指定的左、右子节点执行布尔 AND 操作。 |
| RegionNodeDataTypeOr | `2` | 指定具有子节点的区域节点。应对由 [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) 对象指定的左、右子节点执行布尔 OR 操作。 |
| RegionNodeDataTypeXor | `3` | 指定具有子节点的区域节点。应对由 [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) 对象指定的左、右子节点执行布尔 XOR 操作。 |
| RegionNodeDataTypeExclude | `4` | 指定具有子节点的区域节点。应对由 [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) 对象指定的左、右子节点执行布尔操作，定义为"从区域 2 中排除的区域 1 的部分"。 |
| RegionNodeDataTypeComplement | `5` | 指定一个具有子节点的区域节点。布尔操作，定义为\"区域2中排除区域1的部分\"，应当应用于由[`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/)对象指定的左、右子节点。 |
| RegionNodeDataTypeRect | `268435456` | 指定一个没有子节点的区域节点。RegionNodeData 字段应当使用[`EmfPlusRectF`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/)对象指定一个边界（第 2.2.2.39 节）。 |
| RegionNodeDataTypePath | `268435457` | 指定一个没有子节点的区域节点。RegionNodeData 字段应当使用[`EmfPlusRegionNodePath`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/)对象指定一个边界（第 2.2.2.42 节）。 |
| RegionNodeDataTypeEmpty | `268435458` | 指定一个没有子节点的区域节点。RegionNodeData 字段不应出现。 |
| RegionNodeDataTypeInfinite | `268435459` | 指定一个没有子节点的区域节点，其边界未定义。 |

## 备注

区域节点数据由[`EmfPlusRegionNode`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/)对象指定（第 2.2.2.40 节）。

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


