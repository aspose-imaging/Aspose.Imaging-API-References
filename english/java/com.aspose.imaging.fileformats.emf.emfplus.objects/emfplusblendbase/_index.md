---
title: EmfPlusBlendBase
second_title: Aspose.Imaging for Java API Reference
description: Base object for blend objects
type: docs
weight: 16
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

Base object for blend objects
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | Gets or sets blend positions An array of PositionCount 32-bit floating-point values that specify proportions of distance along the gradient line. |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | Gets or sets blend positions An array of PositionCount 32-bit floating-point values that specify proportions of distance along the gradient line. |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


Gets or sets blend positions An array of PositionCount 32-bit floating-point values that specify proportions of distance along the gradient line. Each element MUST be a number between 0.0 and 1.0 inclusive. For a linear gradient brush, 0.0 represents the starting point and 1.0 represents the ending point. For a path gradient brush, 0.0 represents the midpoint and 1.0 represents an endpoint

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


Gets or sets blend positions An array of PositionCount 32-bit floating-point values that specify proportions of distance along the gradient line. Each element MUST be a number between 0.0 and 1.0 inclusive. For a linear gradient brush, 0.0 represents the starting point and 1.0 represents the ending point. For a path gradient brush, 0.0 represents the midpoint and 1.0 represents an endpoint

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

