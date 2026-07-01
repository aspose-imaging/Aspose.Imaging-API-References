---
title: "EmfPlusRegionNodeDataType"
second_title: "Aspose.Imaging for Java API 参考"
description: "RegionNodeDataType 枚举定义区域节点数据的类型。"
type: docs
weight: 46
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

RegionNodeDataType 枚举定义区域节点数据的类型。

--------------------

区域节点数据由 [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) 对象（第 2.2.2.40 节）指定。
## 字段

| 字段 | 描述 |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | 指定具有子节点的区域节点。 |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | 指定具有子节点的区域节点。 |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | 指定具有子节点的区域节点。 |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | 指定具有子节点的区域节点。 |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | 指定具有子节点的区域节点。 |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | 指定没有子节点的区域节点。 |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | 指定没有子节点的区域节点。 |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | 指定没有子节点的区域节点。 |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | 指定没有子节点的区域节点，且其边界未定义。 |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) 对象（第 2.2.2.41 节）指定的左、右子节点应用布尔 AND 操作。

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) 对象指定的左、右子节点应用布尔 OR 操作。

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) 对象指定的左、右子节点应用布尔 XOR 操作。

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) 对象指定的左、右子节点应用布尔操作，定义为“从区域 2 中排除的区域 1 的部分”。

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


指定具有子节点的区域节点。应对由 [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) 对象指定的左、右子节点应用布尔操作，定义为“从区域 1 中排除的区域 2 的部分”。

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


指定没有子节点的区域节点。RegionNodeData 字段应使用 [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf) 对象（第 2.2.2.39 节）指定边界。

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


指定一个没有子节点的区域节点。RegionNodeData 字段 应该使用一个带有 [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath) 对象的边界（第 2.2.2.42 节）。

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


指定一个没有子节点的区域节点。RegionNodeData 字段 不应出现

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


指定没有子节点的区域节点，且其边界未定义。

