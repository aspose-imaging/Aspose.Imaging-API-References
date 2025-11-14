---
title: EmfPlusRegionNodeDataType Enumeration
type: docs
weight: 370
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---

The RegionNodeDataType enumeration defines types of region node data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRegionNodeDataType

## **Members**
| **Member name** | **Description** |
| :- | :- |
| REGION_NODE_DATA_TYPE_AND | Specifies a region node with child nodes. A Boolean AND operation SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object (section 2.2.2.41). |
| REGION_NODE_DATA_TYPE_COMPLEMENT | Specifies a region node with child nodes. A Boolean operation, defined as "the part of region 2 that is excluded from region 1", SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| REGION_NODE_DATA_TYPE_EMPTY | Specifies a region node with no child nodes. The RegionNodeData field SHOULD NOT be present |
| REGION_NODE_DATA_TYPE_EXCLUDE | Specifies a region node with child nodes. A Boolean operation, defined as "the part of region 1 that is excluded from region 2", SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| REGION_NODE_DATA_TYPE_INFINITE | Specifies a region node with no child nodes, and its bounds are not defined. |
| REGION_NODE_DATA_TYPE_OR | Specifies a region node with child nodes. A Boolean OR operation SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| REGION_NODE_DATA_TYPE_PATH | Specifies a region node with no child nodes. The RegionNodeData field SHOULD specify a boundary with an [EmfPlusRegionNodePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/) object (section 2.2.2.42). |
| REGION_NODE_DATA_TYPE_RECT | Specifies a region node with no child nodes. The RegionNodeData field SHOULD specify a boundary with an [EmfPlusRectF](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/) object (section 2.2.2.39). |
| REGION_NODE_DATA_TYPE_XOR | Specifies a region node with child nodes. A Boolean XOR operation SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
