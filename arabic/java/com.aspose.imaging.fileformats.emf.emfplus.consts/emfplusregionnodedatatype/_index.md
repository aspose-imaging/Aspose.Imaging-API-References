---
title: "EmfPlusRegionNodeDataType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد RegionNodeDataType أنواع بيانات عقد المنطقة."
type: docs
weight: 46
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

تحدد تعداد RegionNodeDataType أنواع بيانات عقد المنطقة.

--------------------

يتم تحديد بيانات عقدة المنطقة بواسطة كائنات [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) (القسم 2.2.2.40).
## الحقول

| حقل | الوصف |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | يحدد عقدة منطقة ذات عقد فرعية. |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | يحدد عقدة منطقة ذات عقد فرعية. |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | يحدد عقدة منطقة ذات عقد فرعية. |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | يحدد عقدة منطقة ذات عقد فرعية. |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | يحدد عقدة منطقة ذات عقد فرعية. |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | يحدد عقدة منطقة بدون عقد فرعية. |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | يحدد عقدة منطقة بدون عقد فرعية. |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | يحدد عقدة منطقة بدون عقد فرعية. |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | يحدد عقدة منطقة بدون عقد فرعية، ولا يتم تعريف حدودها. |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


يحدد عقدة منطقة ذات عقد فرعية. يجب تطبيق عملية AND منطقية على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) (القسم 2.2.2.41).

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


يحدد عقدة منطقة ذات عقد فرعية. يجب تطبيق عملية OR منطقية على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


يحدد عقدة منطقة ذات عقد فرعية. يجب تطبيق عملية XOR منطقية على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


يحدد عقدة منطقة ذات عقد فرعية. يجب تطبيق عملية منطقية، معرفة بأنها \"الجزء من المنطقة 1 المستبعد من المنطقة 2\"، على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


يحدد عقدة منطقة ذات عقد فرعية. يجب تطبيق عملية منطقية، معرفة بأنها \"الجزء من المنطقة 2 المستبعد من المنطقة 1\"، على العقد الفرعية اليسرى واليمنى المحددة بواسطة كائن [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes).

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


يحدد عقدة منطقة بدون عقد فرعية. يجب أن يحدد حقل RegionNodeData حدًا باستخدام كائن [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf) (القسم 2.2.2.39).

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


يحدد عقدة منطقة بدون عقد فرعية. يجب أن يحدد حقل RegionNodeData حدًا باستخدام كائن [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath) (القسم 2.2.2.42).

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


يحدد عقدة منطقة بدون عقد فرعية. يجب ألا يكون حقل RegionNodeData موجودًا.

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


يحدد عقدة منطقة بدون عقد فرعية، ولا يتم تعريف حدودها.

