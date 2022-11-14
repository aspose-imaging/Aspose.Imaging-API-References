---
title: EmfPlusPathGradientBrushOptionalData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.
type: docs
weight: 60
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the path gradient brush. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the path gradient brush. |
| [getBlendPattern()](#getBlendPattern--) | Gets or sets an optional blend pattern for the path gradient brush. |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | Gets or sets an optional blend pattern for the path gradient brush. |
| [getFocusScaleData()](#getFocusScaleData--) | Gets or sets an optional EmfPlusFocusScaleData object (section 2.2.2.18) that specifies focus scales for the path gradient brush. |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | Gets or sets an optional EmfPlusFocusScaleData object (section 2.2.2.18) that specifies focus scales for the path gradient brush. |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the path gradient brush. This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusPathGradientBrushData object.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the path gradient brush. This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusPathGradientBrushData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


Gets or sets an optional blend pattern for the path gradient brush. If this field is present, it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), or an EmfPlusBlendFactors object (section 2.2.2.5), but it MUST NOT contain both. The table below shows the valid combinations of EmfPlusPathGradientBrushData BrushData flags and the corresponding blend patterns:

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


Gets or sets an optional blend pattern for the path gradient brush. If this field is present, it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), or an EmfPlusBlendFactors object (section 2.2.2.5), but it MUST NOT contain both. The table below shows the valid combinations of EmfPlusPathGradientBrushData BrushData flags and the corresponding blend patterns:

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


Gets or sets an optional EmfPlusFocusScaleData object (section 2.2.2.18) that specifies focus scales for the path gradient brush. This field MUST be present if the BrushDataFocusScales flag is set in the BrushDataFlags field of the EmfPlusPathGradientBrushData object.

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


Gets or sets an optional EmfPlusFocusScaleData object (section 2.2.2.18) that specifies focus scales for the path gradient brush. This field MUST be present if the BrushDataFocusScales flag is set in the BrushDataFlags field of the EmfPlusPathGradientBrushData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

