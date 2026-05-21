---
title: "تعداد EmfPlusRegionNodeDataType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusRegionNodeDataType. يحدد تعداد RegionNodeDataType أنواع بيانات عقد المنطقة."
type: docs
weight: 5160
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
## EmfPlusRegionNodeDataType enumeration

تحدد تعداد RegionNodeDataType أنواع بيانات عقد المنطقة.

```csharp
public enum EmfPlusRegionNodeDataType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| RegionNodeDataTypeAnd | `1` | يحدد عقدة منطقة مع عقد فرعية. يجب تطبيق عملية AND منطقية على عقد الطفل اليسرى واليمنى المحددة بواسطة كائن [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) (القسم 2.2.2.41). |
| RegionNodeDataTypeOr | `2` | يحدد عقدة منطقة مع عقد فرعية. يجب تطبيق عملية OR منطقية على عقد الطفل اليسرى واليمنى المحددة بواسطة كائن [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) . |
| RegionNodeDataTypeXor | `3` | يحدد عقدة منطقة مع عقد فرعية. يجب تطبيق عملية XOR منطقية على عقد الطفل اليسرى واليمنى المحددة بواسطة كائن [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) . |
| RegionNodeDataTypeExclude | `4` | يحدد عقدة منطقة مع عقد فرعية. يجب تطبيق عملية منطقية، معرفة بأنها "الجزء من المنطقة 1 المستبعد من المنطقة 2"، على عقد الطفل اليسرى واليمنى المحددة بواسطة كائن [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) . |
| RegionNodeDataTypeComplement | `5` | يحدد عقدة منطقة تحتوي على عقد فرعية. عملية بوليانية، معرفة بأنها "الجزء من المنطقة 2 المستبعد من المنطقة 1"، يجب تطبيقها على عقد الطفل اليسرى واليمنى المحددة بواسطة كائن [`EmfPlusRegionNodeChildNodes`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes/) object. |
| RegionNodeDataTypeRect | `268435456` | يحدد عقدة منطقة بدون عقد فرعية. يجب أن يحدد حقل RegionNodeData حدًا باستخدام كائن [`EmfPlusRectF`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf/) (القسم 2.2.2.39). |
| RegionNodeDataTypePath | `268435457` | يحدد عقدة منطقة بدون عقد فرعية. يجب أن يحدد حقل RegionNodeData حدًا باستخدام كائن [`EmfPlusRegionNodePath`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath/) (القسم 2.2.2.42). |
| RegionNodeDataTypeEmpty | `268435458` | يحدد عقدة منطقة بدون عقد فرعية. يجب ألا يكون حقل RegionNodeData موجودًا |
| RegionNodeDataTypeInfinite | `268435459` | يحدد عقدة منطقة بدون عقد فرعية، ولا يتم تعريف حدودها. |

## ملاحظات

يتم تحديد بيانات عقدة المنطقة بواسطة كائنات [`EmfPlusRegionNode`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/) (القسم 2.2.2.40).

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


