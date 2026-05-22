---
title: "EmfPlusRegionNodeDataType Enumeration"
type: docs
weight: 370
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---

RegionNodeDataType 枚举定义了区域节点数据的类型。

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRegionNodeDataType

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| REGION_NODE_DATA_TYPE_AND | 指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) 对象（第 2.2.2.41 节）指定的左、右子节点执行布尔 AND 操作。 |
| REGION_NODE_DATA_TYPE_COMPLEMENT | 指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) 对象指定的左、右子节点执行布尔操作，定义为 "the part of region 2 that is excluded from region 1"。 |
| REGION_NODE_DATA_TYPE_EMPTY | 指定没有子节点的区域节点。RegionNodeData 字段不应出现。 |
| REGION_NODE_DATA_TYPE_EXCLUDE | 指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) 对象指定的左、右子节点执行布尔操作，定义为 "the part of region 1 that is excluded from region 2"。 |
| REGION_NODE_DATA_TYPE_INFINITE | 指定没有子节点的区域节点，其边界未定义。 |
| REGION_NODE_DATA_TYPE_OR | 指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) 对象指定的左、右子节点执行布尔 OR 操作。 |
| REGION_NODE_DATA_TYPE_PATH | 指定没有子节点的区域节点。RegionNodeData 字段应使用 [EmfPlusRegionNodePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/) 对象指定边界（第 2.2.2.42 节）。 |
| REGION_NODE_DATA_TYPE_RECT | 指定没有子节点的区域节点。RegionNodeData 字段应使用 [EmfPlusRectF](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/) 对象指定边界（第 2.2.2.39 节）。 |
| REGION_NODE_DATA_TYPE_XOR | 指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) 对象指定的左、右子节点执行布尔 XOR 操作。 |
