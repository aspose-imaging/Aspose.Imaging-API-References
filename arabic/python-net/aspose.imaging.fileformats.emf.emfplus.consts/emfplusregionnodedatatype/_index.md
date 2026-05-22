---
title: "EmfPlusRegionNodeDataType Enumeration"
type: docs
weight: 370
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---

تحدد تعداد RegionNodeDataType أنواع بيانات عقد المنطقة.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRegionNodeDataType

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| REGION_NODE_DATA_TYPE_AND | يحدد عقدة منطقة تحتوي على عقد فرعية. يجب تطبيق عملية AND منطقية على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) (القسم 2.2.2.41). |
| REGION_NODE_DATA_TYPE_COMPLEMENT | يحدد عقدة منطقة تحتوي على عقد فرعية. يجب تطبيق عملية منطقية، معرفة بأنها \"الجزء من المنطقة 2 المستبعد من المنطقة 1\"، على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| REGION_NODE_DATA_TYPE_EMPTY | يحدد عقدة منطقة بدون عقد فرعية. يجب ألا يكون حقل RegionNodeData موجودًا. |
| REGION_NODE_DATA_TYPE_EXCLUDE | يحدد عقدة منطقة تحتوي على عقد فرعية. يجب تطبيق عملية منطقية، معرفة بأنها \"الجزء من المنطقة 1 المستبعد من المنطقة 2\"، على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| REGION_NODE_DATA_TYPE_INFINITE | يحدد عقدة منطقة بدون عقد فرعية، ولا يتم تعريف حدودها. |
| REGION_NODE_DATA_TYPE_OR | يحدد عقدة منطقة تحتوي على عقد فرعية. يجب تطبيق عملية OR منطقية على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| REGION_NODE_DATA_TYPE_PATH | يحدد عقدة منطقة بدون عقد فرعية. يجب أن يحدد حقل RegionNodeData حدًا باستخدام كائن [EmfPlusRegionNodePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/) object (القسم 2.2.2.42). |
| REGION_NODE_DATA_TYPE_RECT | يحدد عقدة منطقة بدون عقد فرعية. يجب أن يحدد حقل RegionNodeData حدًا باستخدام كائن [EmfPlusRectF](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/) object (القسم 2.2.2.39). |
| REGION_NODE_DATA_TYPE_XOR | يحدد عقدة منطقة تحتوي على عقد فرعية. يجب تطبيق عملية XOR منطقية على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
