---
title: "الفئة EmfPlusRegionNode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusRegionNode class. يحدد كائن EmfPlusRegionNode عقد منطقة رسومية."
type: docs
weight: 5840
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
## EmfPlusRegionNode class

كائن EmfPlusRegionNode يحدد عقد منطقة رسومية.

```csharp
public sealed class EmfPlusRegionNode : EmfPlusStructureObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusRegionNode](emfplusregionnode/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [RegionNodeData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/regionnodedata/) { get; set; } | الحصول أو تعيين بيانات اختيارية ذات طول متغير تُعرّف كائن بيانات عقدة المنطقة المحدد في حقل Type. يمكن أن يكون محتوى البيانات وتنسيقها مختلفًا لكل نوع عقدة. يجب ألا يكون هذا الحقل موجودًا إذا كان نوع العقدة هو RegionNodeDataTypeEmpty أو RegionNodeDataTypeInfinite. هذا الكائن عام ويُستخدم لتحديد أنواع مختلفة من بيانات عقدة المنطقة، بما في ذلك: كائن EmfPlusRegionNodePath (القسم 2.2.2.42) لعقدة نهائية؛ كائن EmfPlusRectF (القسم 2.2.2.39) لعقدة نهائية؛ وكائن EmfPlusRegionNodeChildNodes (القسم 2.2.2.41) لعقدة غير نهائية. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/type/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد نوع البيانات في حقل RegionNodeData. يجب أن تكون هذه القيمة معرفة في تعداد RegionNodeDataType (القسم 2.1.1.27). |

### انظر أيضًا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


