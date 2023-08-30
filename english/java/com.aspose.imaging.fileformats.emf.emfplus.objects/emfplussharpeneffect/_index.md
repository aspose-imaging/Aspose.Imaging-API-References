---
title: EmfPlusSharpenEffect
second_title: Aspose.Imaging for Java API Reference
description: The SharpenEffect object specifies an increase in the difference in intensity between pixels in an image.
type: docs
weight: 72
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

The SharpenEffect object specifies an increase in the difference in intensity between pixels in an image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Gets or sets A 32-bit floating-point number that specifies the sharpening radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. |
| [setRadius(float value)](#setRadius-float-) | Gets or sets A 32-bit floating-point number that specifies the sharpening radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. |
| [getAmount()](#getAmount--) | Gets or sets A 32-bit floating-point number that specifies the difference in intensity between a given pixel and the surrounding pixels. 0 Specifies that sharpening MUST NOT be performed. 0 < value \\u2264 100 As this value increases, the difference in intensity between pixels SHOULD increase. |
| [setAmount(float value)](#setAmount-float-) | Gets or sets A 32-bit floating-point number that specifies the difference in intensity between a given pixel and the surrounding pixels. 0 Specifies that sharpening MUST NOT be performed. 0 < value \\u2264 100 As this value increases, the difference in intensity between pixels SHOULD increase. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


Gets or sets A 32-bit floating-point number that specifies the sharpening radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. As this value increases, the number of pixels involved in the calculation increases, and the resulting bitmap SHOULD become sharper.

Value: The radius.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


Gets or sets A 32-bit floating-point number that specifies the sharpening radius in pixels, which determines the number of pixels involved in calculating the new value of a given pixel. As this value increases, the number of pixels involved in the calculation increases, and the resulting bitmap SHOULD become sharper.

Value: The radius.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


Gets or sets A 32-bit floating-point number that specifies the difference in intensity between a given pixel and the surrounding pixels. 0 Specifies that sharpening MUST NOT be performed. 0 < value \\u2264 100 As this value increases, the difference in intensity between pixels SHOULD increase.

Value: The amount.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


Gets or sets A 32-bit floating-point number that specifies the difference in intensity between a given pixel and the surrounding pixels. 0 Specifies that sharpening MUST NOT be performed. 0 < value \\u2264 100 As this value increases, the difference in intensity between pixels SHOULD increase.

Value: The amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

