---
title: EmfPlusRegionNode
second_title: Aspose.Imaging لمرجع NET API
description: يحدد كائن EmfPlusRegionNode العقد الخاصة بمنطقة الرسومات.
type: docs
weight: 5720
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
## EmfPlusRegionNode class

يحدد كائن EmfPlusRegionNode العقد الخاصة بمنطقة الرسومات.

```csharp
public sealed class EmfPlusRegionNode : EmfPlusStructureObjectType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusRegionNode](emfplusregionnode)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [RegionNodeData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/regionnodedata) { get; set; } | الحصول على أو تعيين بيانات اختيارية ذات طول متغير تحدد كائن بيانات المنطقة node المحدد في حقل النوع. يمكن أن يختلف المحتوى وتنسيق للبيانات لكل نوع عقدة region . يجب ألا يكون هذا الحقل موجودًا إذا كان نوع node هو RegionNodeDataTypeEmpty أو RegionNodeDataTypeInfinite هذا الكائن عام ويستخدم لتحديد أنواع مختلفة من بيانات عقدة المنطقة ، بما في ذلك: كائن EmfPlusRegionNodePath (القسم 2.2.2.42) ، للعقدة الطرفية ؛ _x000 ؛ كائن EmfPlusRectF (القسم 2.2.2.39) ، للعقدة الطرفية ؛ and كائن EmfPlusRegionNodeChildNodes (القسم 2.2.2.41) ، للعقدة غير الطرفية. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/type) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد نوع البيانات في الحقل RegionNodeData. يجب تحديد هذه القيمة في تعداد RegionNodeDataType (القسم 2.1.1.27) . |

### أنظر أيضا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
