---
title: EmfPlusRegionNodeDataType
second_title: Aspose.Imaging for Java API Reference
description: The RegionNodeDataType enumeration defines types of region node data.
type: docs
weight: 46
url: /java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusregionnodedatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRegionNodeDataType extends System.Enum
```

The RegionNodeDataType enumeration defines types of region node data.

--------------------

Region node data is specified by [EmfPlusRegionNode](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) objects (section 2.2.2.40).
## Fields

| Field | Description |
| --- | --- |
| [RegionNodeDataTypeAnd](#RegionNodeDataTypeAnd) | Specifies a region node with child nodes. |
| [RegionNodeDataTypeOr](#RegionNodeDataTypeOr) | Specifies a region node with child nodes. |
| [RegionNodeDataTypeXor](#RegionNodeDataTypeXor) | Specifies a region node with child nodes. |
| [RegionNodeDataTypeExclude](#RegionNodeDataTypeExclude) | Specifies a region node with child nodes. |
| [RegionNodeDataTypeComplement](#RegionNodeDataTypeComplement) | Specifies a region node with child nodes. |
| [RegionNodeDataTypeRect](#RegionNodeDataTypeRect) | Specifies a region node with no child nodes. |
| [RegionNodeDataTypePath](#RegionNodeDataTypePath) | Specifies a region node with no child nodes. |
| [RegionNodeDataTypeEmpty](#RegionNodeDataTypeEmpty) | Specifies a region node with no child nodes. |
| [RegionNodeDataTypeInfinite](#RegionNodeDataTypeInfinite) | Specifies a region node with no child nodes, and its bounds are not defined. |
### RegionNodeDataTypeAnd {#RegionNodeDataTypeAnd}
```
public static final int RegionNodeDataTypeAnd
```


Specifies a region node with child nodes. A Boolean AND operation SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) object (section 2.2.2.41).

### RegionNodeDataTypeOr {#RegionNodeDataTypeOr}
```
public static final int RegionNodeDataTypeOr
```


Specifies a region node with child nodes. A Boolean OR operation SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) object.

### RegionNodeDataTypeXor {#RegionNodeDataTypeXor}
```
public static final int RegionNodeDataTypeXor
```


Specifies a region node with child nodes. A Boolean XOR operation SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) object.

### RegionNodeDataTypeExclude {#RegionNodeDataTypeExclude}
```
public static final int RegionNodeDataTypeExclude
```


Specifies a region node with child nodes. A Boolean operation, defined as "the part of region 1 that is excluded from region 2", SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) object.

### RegionNodeDataTypeComplement {#RegionNodeDataTypeComplement}
```
public static final int RegionNodeDataTypeComplement
```


Specifies a region node with child nodes. A Boolean operation, defined as "the part of region 2 that is excluded from region 1", SHOULD be applied to the left and right child nodes specified by an [EmfPlusRegionNodeChildNodes](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodechildnodes) object.

### RegionNodeDataTypeRect {#RegionNodeDataTypeRect}
```
public static final int RegionNodeDataTypeRect
```


Specifies a region node with no child nodes. The RegionNodeData field SHOULD specify a boundary with an [EmfPlusRectF](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusrectf) object (section 2.2.2.39).

### RegionNodeDataTypePath {#RegionNodeDataTypePath}
```
public static final int RegionNodeDataTypePath
```


Specifies a region node with no child nodes. The RegionNodeData field SHOULD specify a boundary with an [EmfPlusRegionNodePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnodepath) object (section 2.2.2.42).

### RegionNodeDataTypeEmpty {#RegionNodeDataTypeEmpty}
```
public static final int RegionNodeDataTypeEmpty
```


Specifies a region node with no child nodes. The RegionNodeData field SHOULD NOT be present

### RegionNodeDataTypeInfinite {#RegionNodeDataTypeInfinite}
```
public static final int RegionNodeDataTypeInfinite
```


Specifies a region node with no child nodes, and its bounds are not defined.

