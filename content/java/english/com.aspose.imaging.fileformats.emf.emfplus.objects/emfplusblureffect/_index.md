---
title: EmfPlusBlurEffect
second_title: Aspose.Imaging for Java API Reference
description: The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.
type: docs
weight: 19
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Gets or sets a 32-bit floating-point number that specifies the blur radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. |
| [setBlurRadius(float value)](#setBlurRadius-float-) | Gets or sets a 32-bit floating-point number that specifies the blur radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. |
| [getExpandEdge()](#getExpandEdge--) | Gets or sets a 32-bit Boolean value that specifies whether the bitmap expands by an amount equal to the value of the BlurRadius to produce soft edges. |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | Gets or sets a 32-bit Boolean value that specifies whether the bitmap expands by an amount equal to the value of the BlurRadius to produce soft edges. |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


Gets or sets a 32-bit floating-point number that specifies the blur radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. This value MUST be in the range 0.0 through 255.0.

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


Gets or sets a 32-bit floating-point number that specifies the blur radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. This value MUST be in the range 0.0 through 255.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


Gets or sets a 32-bit Boolean value that specifies whether the bitmap expands by an amount equal to the value of the BlurRadius to produce soft edges. This value MUST be one of the following: FALSE 0x00000000 The size of the bitmap MUST NOT change, and its soft edges SHOULD be clipped to the size of the BlurRadius. TRUE 0x00000001 The size of the bitmap SHOULD expand by an amount equal to the BlurRadius to produce soft edges.

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


Gets or sets a 32-bit Boolean value that specifies whether the bitmap expands by an amount equal to the value of the BlurRadius to produce soft edges. This value MUST be one of the following: FALSE 0x00000000 The size of the bitmap MUST NOT change, and its soft edges SHOULD be clipped to the size of the BlurRadius. TRUE 0x00000001 The size of the bitmap SHOULD expand by an amount equal to the BlurRadius to produce soft edges.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

