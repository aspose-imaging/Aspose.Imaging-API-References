---
title: EmfPlusTextureBrushData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.
type: docs
weight: 77
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Gets or sets a 32-bit unsigned integer that specifies the data in the OptionalData field. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Gets or sets a 32-bit unsigned integer that specifies the data in the OptionalData field. |
| [getWrapMode()](#getWrapMode--) | Gets or sets a 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies how to repeat the texture image across a shape, when the image is smaller than the area being filled. |
| [setWrapMode(int value)](#setWrapMode-int-) | Gets or sets a 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies how to repeat the texture image across a shape, when the image is smaller than the area being filled. |
| [getOptionalData()](#getOptionalData--) | Gets or sets an optional EmfPlusTextureBrushOptionalData object (section 2.2.2.46) that specifies additional data for the texture brush. |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | Gets or sets an optional EmfPlusTextureBrushOptionalData object (section 2.2.2.46) that specifies additional data for the texture brush. |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Gets or sets a 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of BrushData flags (section 2.1.2.1). The following flags are relevant to a texture brush BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of BrushData flags (section 2.1.2.1). The following flags are relevant to a texture brush BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Gets or sets a 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies how to repeat the texture image across a shape, when the image is smaller than the area being filled.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Gets or sets a 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies how to repeat the texture image across a shape, when the image is smaller than the area being filled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


Gets or sets an optional EmfPlusTextureBrushOptionalData object (section 2.2.2.46) that specifies additional data for the texture brush. The specific contents of this field are determined by the value of the BrushDataFlags field

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


Gets or sets an optional EmfPlusTextureBrushOptionalData object (section 2.2.2.46) that specifies additional data for the texture brush. The specific contents of this field are determined by the value of the BrushDataFlags field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

