---
title: EmfPlusRegionNode
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusRegionNode object specifies nodes of a graphics region.
type: docs
weight: 69
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

The EmfPlusRegionNode object specifies nodes of a graphics region.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | Gets or sets an optional, variable-length data that defines the region node data object specified in the Type field. |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | Gets or sets an optional, variable-length data that defines the region node data object specified in the Type field. |
| [getType()](#getType--) | Gets or sets 32-bit unsigned integer that specifies the type of data in the RegionNodeData field. |
| [setType(int value)](#setType-int-) | Gets or sets 32-bit unsigned integer that specifies the type of data in the RegionNodeData field. |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


Gets or sets an optional, variable-length data that defines the region node data object specified in the Type field. The content and format of the data can be different for every region node type. This field MUST NOT be present if the node type is RegionNodeDataTypeEmpty or RegionNodeDataTypeInfinite This object is generic and is used to specify different types of region node data, including: An EmfPlusRegionNodePath object (section 2.2.2.42), for a terminal node; An EmfPlusRectF object (section 2.2.2.39), for a terminal node; and An EmfPlusRegionNodeChildNodes object (section 2.2.2.41), for a non-terminal node.

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


Gets or sets an optional, variable-length data that defines the region node data object specified in the Type field. The content and format of the data can be different for every region node type. This field MUST NOT be present if the node type is RegionNodeDataTypeEmpty or RegionNodeDataTypeInfinite This object is generic and is used to specify different types of region node data, including: An EmfPlusRegionNodePath object (section 2.2.2.42), for a terminal node; An EmfPlusRectF object (section 2.2.2.39), for a terminal node; and An EmfPlusRegionNodeChildNodes object (section 2.2.2.41), for a non-terminal node.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


Gets or sets 32-bit unsigned integer that specifies the type of data in the RegionNodeData field. This value MUST be defined in the RegionNodeDataType enumeration (section 2.1.1.27).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Gets or sets 32-bit unsigned integer that specifies the type of data in the RegionNodeData field. This value MUST be defined in the RegionNodeDataType enumeration (section 2.1.1.27).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

