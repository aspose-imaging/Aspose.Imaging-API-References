---
title: EmfPlusPathGradientBrushData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.
type: docs
weight: 59
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. |
| [getWrapMode()](#getWrapMode--) | Gets or sets 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies whether to paint the area outside the boundary of the brush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Gets or sets 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies whether to paint the area outside the boundary of the brush. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. |
| [getCenterPointF()](#getCenterPointF--) | Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | Gets or sets array of SurroundingColorCount EmfPlusARGB objects that specify the colors for discrete points on the boundary of the brush. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | Gets or sets array of SurroundingColorCount EmfPlusARGB objects that specify the colors for discrete points on the boundary of the brush. |
| [getBoundaryData()](#getBoundaryData--) | Gets or sets the boundary of the path gradient brush, which is specified by either a path or a closed cardinal spline. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | Gets or sets the boundary of the path gradient brush, which is specified by either a path or a closed cardinal spline. |
| [getOptionalData()](#getOptionalData--) | Gets or sets an optional EmfPlusPathGradientBrushOptionalData object (section 2.2.2.30) that specifies additional data for the path gradient brush. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | Gets or sets an optional EmfPlusPathGradientBrushOptionalData object (section 2.2.2.30) that specifies additional data for the path gradient brush. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of BrushData flags (section 2.1.2.1). The following flags are relevant to a path gradient brush:

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of BrushData flags (section 2.1.2.1). The following flags are relevant to a path gradient brush:

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Gets or sets 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies whether to paint the area outside the boundary of the brush. When painting outside the boundary, the wrap mode specifies how the color gradient is repeated

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Gets or sets 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies whether to paint the area outside the boundary of the brush. When painting outside the boundary, the wrap mode specifies how the color gradient is repeated

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. The color of the brush changes gradually from the boundary color to the center color as it moves from the boundary to the center point.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. The color of the brush changes gradually from the boundary color to the center color as it moves from the boundary to the center point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. The color of the brush changes gradually from the boundary color to the center color as it moves from the boundary to the center point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. The color of the brush changes gradually from the boundary color to the center color as it moves from the boundary to the center point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


Gets or sets array of SurroundingColorCount EmfPlusARGB objects that specify the colors for discrete points on the boundary of the brush.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


Gets or sets array of SurroundingColorCount EmfPlusARGB objects that specify the colors for discrete points on the boundary of the brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


Gets or sets the boundary of the path gradient brush, which is specified by either a path or a closed cardinal spline. If the BrushDataPath flag is set in the BrushDataFlags field, this field MUST contain an EmfPlusBoundaryPathData object (section 2.2.2.6); otherwise, this field MUST contain an EmfPlusBoundaryPointData object (section 2.2.2.7).

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


Gets or sets the boundary of the path gradient brush, which is specified by either a path or a closed cardinal spline. If the BrushDataPath flag is set in the BrushDataFlags field, this field MUST contain an EmfPlusBoundaryPathData object (section 2.2.2.6); otherwise, this field MUST contain an EmfPlusBoundaryPointData object (section 2.2.2.7).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


Gets or sets an optional EmfPlusPathGradientBrushOptionalData object (section 2.2.2.30) that specifies additional data for the path gradient brush. The specific contents of this field are determined by the value of the BrushDataFlags field.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


Gets or sets an optional EmfPlusPathGradientBrushOptionalData object (section 2.2.2.30) that specifies additional data for the path gradient brush. The specific contents of this field are determined by the value of the BrushDataFlags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

