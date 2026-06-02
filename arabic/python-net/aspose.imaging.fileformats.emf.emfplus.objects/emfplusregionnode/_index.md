---
title: "فئة EmfPlusRegionNode"
type: docs
weight: 600
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---

**Summary:** The EmfPlusRegionNode object specifies nodes of a graphics region.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode__1) | ينشئ مثلاً جديداً من فئة EmfPlusRegionNode |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| region_node_data | [EmfPlusStructureObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype/) | r/w | يحصل أو يعيّن بيانات اختيارية بطول متغيّر تُعرّف كائن بيانات عقدة المنطقة المحدد في حقل Type. يمكن أن يكون المحتوى<br/>            وتنسيق البيانات مختلفين لكل نوع من أنواع عقد المنطقة. يجب ألا يكون هذا الحقل موجوداً إذا كان نوع العقدة<br/>            هو RegionNodeDataTypeEmpty أو RegionNodeDataTypeInfinite.<br/>            هذا الكائن عام ويُستخدم لتحديد أنواع مختلفة من بيانات عقد المنطقة، بما في ذلك:<br/>            كائن EmfPlusRegionNodePath (القسم 2.2.2.42)، لعقدة نهائية؛<br/>            كائن EmfPlusRectF (القسم 2.2.2.39)، لعقدة نهائية؛ و<br/>            كائن EmfPlusRegionNodeChildNodes (القسم 2.2.2.41)، لعقدة غير نهائية. |
| type | [EmfPlusRegionNodeDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/) | r/w | يحصل أو يعيّن عدد صحيح غير موقع 32‑بت يحدد نوع<br/>            البيانات في حقل RegionNodeData. يجب أن تكون هذه القيمة مُعرفة في تعداد RegionNodeDataType (القسم 2.1.1.27). |


### Constructor: EmfPlusRegionNode() {#EmfPlusRegionNode__1}


```
 EmfPlusRegionNode() 
```

ينشئ مثلاً جديداً من فئة EmfPlusRegionNode

