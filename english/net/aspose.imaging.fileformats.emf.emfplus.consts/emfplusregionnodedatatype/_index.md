---
title: Enum EmfPlusRegionNodeDataType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusRegionNodeDataType enum. The RegionNodeDataType enumeration defines types of region node data
type: docs
weight: 5160
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
## EmfPlusRegionNodeDataType enumeration

The RegionNodeDataType enumeration defines types of region node data.

```csharp
public enum EmfPlusRegionNodeDataType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RegionNodeDataTypeAnd | `1` | Specifies a region node with child nodes. A Boolean AND operation SHOULD be applied to the left and right child nodes specified by an [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object (section 2.2.2.41). |
| RegionNodeDataTypeOr | `2` | Specifies a region node with child nodes. A Boolean OR operation SHOULD be applied to the left and right child nodes specified by an [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| RegionNodeDataTypeXor | `3` | Specifies a region node with child nodes. A Boolean XOR operation SHOULD be applied to the left and right child nodes specified by an [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| RegionNodeDataTypeExclude | `4` | Specifies a region node with child nodes. A Boolean operation, defined as "the part of region 1 that is excluded from region 2", SHOULD be applied to the left and right child nodes specified by an [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| RegionNodeDataTypeComplement | `5` | Specifies a region node with child nodes. A Boolean operation, defined as "the part of region 2 that is excluded from region 1", SHOULD be applied to the left and right child nodes specified by an [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| RegionNodeDataTypeRect | `268435456` | Specifies a region node with no child nodes. The RegionNodeData field SHOULD specify a boundary with an [`EmfPlusRectF`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/) object (section 2.2.2.39). |
| RegionNodeDataTypePath | `268435457` | Specifies a region node with no child nodes. The RegionNodeData field SHOULD specify a boundary with an [`EmfPlusRegionNodePath`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/) object (section 2.2.2.42). |
| RegionNodeDataTypeEmpty | `268435458` | Specifies a region node with no child nodes. The RegionNodeData field SHOULD NOT be present |
| RegionNodeDataTypeInfinite | `268435459` | Specifies a region node with no child nodes, and its bounds are not defined. |

## Remarks

Region node data is specified by [`EmfPlusRegionNode`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/) objects (section 2.2.2.40).

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


