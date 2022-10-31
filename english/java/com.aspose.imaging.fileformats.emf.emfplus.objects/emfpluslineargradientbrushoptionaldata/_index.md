---
title: EmfPlusLinearGradientBrushOptionalData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.
type: docs
weight: 54
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the linear gradient brush. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the linear gradient brush. |
| [getBlendPattern()](#getBlendPattern--) | Gets or sets an optional blend pattern for the linear gradient brush. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | Gets or sets an optional blend pattern for the linear gradient brush. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | Gets the blend pattern as preset colors. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | Gets the blend pattern as blend factors h. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | Gets the blend pattern as blend factors v. |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the linear gradient brush. This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusLinearGradientBrushData object.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the linear gradient brush. This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusLinearGradientBrushData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


Gets or sets an optional blend pattern for the linear gradient brush. If this field is present, it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), or one or two EmfPlusBlendFactors objects (section 2.2.2.5), but it MUST NOT contain both. The table below shows the valid combinations of EmfPlusLinearGradientBrushData BrushData flags and the corresponding blend patterns: EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


Gets or sets an optional blend pattern for the linear gradient brush. If this field is present, it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), or one or two EmfPlusBlendFactors objects (section 2.2.2.5), but it MUST NOT contain both. The table below shows the valid combinations of EmfPlusLinearGradientBrushData BrushData flags and the corresponding blend patterns: EmfPlusBlendFactors

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


Gets the blend pattern as preset colors.

Value: The blend pattern as preset colors.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


Gets the blend pattern as blend factors h.

Value: The blend pattern as blend factors h.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


Gets the blend pattern as blend factors v.

Value: The blend pattern as blend factors v.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
