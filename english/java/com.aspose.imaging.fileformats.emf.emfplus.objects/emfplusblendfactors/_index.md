---
title: EmfPlusBlendFactors
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.
type: docs
weight: 18
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
```
public final class EmfPlusBlendFactors extends EmfPlusBlendBase
```

The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBlendFactors()](#getBlendFactors--) | Gets or sets an array of PositionCount 32-bit floating point values that specify proportions of colors at the positions defined in the BlendPositions field. |
| [setBlendFactors(float[] value)](#setBlendFactors-float---) | Gets or sets an array of PositionCount 32-bit floating point values that specify proportions of colors at the positions defined in the BlendPositions field. |
### EmfPlusBlendFactors() {#EmfPlusBlendFactors--}
```
public EmfPlusBlendFactors()
```


### getBlendFactors() {#getBlendFactors--}
```
public float[] getBlendFactors()
```


Gets or sets an array of PositionCount 32-bit floating point values that specify proportions of colors at the positions defined in the BlendPositions field. Each value MUST be a number between 0.0 and 1.0 inclusive.

**Returns:**
float[]
### setBlendFactors(float[] value) {#setBlendFactors-float---}
```
public void setBlendFactors(float[] value)
```


Gets or sets an array of PositionCount 32-bit floating point values that specify proportions of colors at the positions defined in the BlendPositions field. Each value MUST be a number between 0.0 and 1.0 inclusive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

