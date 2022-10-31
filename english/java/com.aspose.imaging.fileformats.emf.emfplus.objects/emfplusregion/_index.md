---
title: EmfPlusRegion
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusRegion object specifies line and curve segments that define a non rectilinear shape
type: docs
weight: 68
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

The EmfPlusRegion object specifies line and curve segments that define a non rectilinear shape
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | Gets or sets an array of RegionNodeCount+1 EmfPlusRegionNode objects (section 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | Gets or sets an array of RegionNodeCount+1 EmfPlusRegionNode objects (section 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


Gets or sets an array of RegionNodeCount+1 EmfPlusRegionNode objects (section 2.2.2.40). Regions are specified as a binary tree of region nodes, and each node MUST either be a terminal node or specify one or two child nodes. RegionNode MUST contain at least one element

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


Gets or sets an array of RegionNodeCount+1 EmfPlusRegionNode objects (section 2.2.2.40). Regions are specified as a binary tree of region nodes, and each node MUST either be a terminal node or specify one or two child nodes. RegionNode MUST contain at least one element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

