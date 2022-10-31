---
title: EmfPlusBrush
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusBrush object specifies a graphics brush for filling regions.
type: docs
weight: 24
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

The EmfPlusBrush object specifies a graphics brush for filling regions.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBrushData()](#getBrushData--) | Gets or sets the Brush data Variable-length data that defines the brush object specified in the Type field. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | Gets or sets the Brush data Variable-length data that defines the brush object specified in the Type field. |
| [getType()](#getType--) | Gets or sets the type. |
| [setType(int value)](#setType-int-) | Gets or sets the type. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


Gets or sets the Brush data Variable-length data that defines the brush object specified in the Type field. The content and format of the data can be different for every brush type. EmfPlusHatchBrushData (section 2.2.2.20) (done) EmfPlusLinearGradientBrushData object (section 2.2.2.24) (done) EmfPlusPathGradientBrushData object (section 2.2.2.29) (done) EmfPlusSolidBrushData object (section 2.2.2.43) (done) EmfPlusTextureBrushData object (section 2.2.2.45) (done)

Value: The brush data.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


Gets or sets the Brush data Variable-length data that defines the brush object specified in the Type field. The content and format of the data can be different for every brush type. EmfPlusHatchBrushData (section 2.2.2.20) (done) EmfPlusLinearGradientBrushData object (section 2.2.2.24) (done) EmfPlusPathGradientBrushData object (section 2.2.2.29) (done) EmfPlusSolidBrushData object (section 2.2.2.43) (done) EmfPlusTextureBrushData object (section 2.2.2.45) (done)

Value: The brush data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


Gets or sets the type.

Value: A 32-bit unsigned integer that specifies the type of brush, which determines the contents of the BrushData field. This value MUST be defined in the `EmfPlusBrushType` enumeration.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Gets or sets the type.

Value: A 32-bit unsigned integer that specifies the type of brush, which determines the contents of the BrushData field. This value MUST be defined in the `EmfPlusBrushType` enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

