---
title: EmfPlusBrightnessContrastEffect
second_title: Aspose.Imaging for Java API Reference
description: The BrightnessContrastEffect object specifies an expansion or contraction of the lightest and darkest areas of an image.
type: docs
weight: 23
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

The BrightnessContrastEffect object specifies an expansion or contraction of the lightest and darkest areas of an image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | Gets or sets a 32-bit signed integer that specifies the brightness level. |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | Gets or sets a 32-bit signed integer that specifies the brightness level. |
| [getContrastLevel()](#getContrastLevel--) | Gets or sets a 32-bit signed integer that specifies the contrast level. |
| [setContrastLevel(int value)](#setContrastLevel-int-) | Gets or sets a 32-bit signed integer that specifies the contrast level. |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


Gets or sets a 32-bit signed integer that specifies the brightness level. This value MUST be in the range -255 through 255, with effects as follows: -255 \\u2264 value < 0 As the value decreases, the brightness of the image SHOULD decrease. 0 A value of 0 specifies that the brightness MUST NOT change. 0 < value \\u2264 255 As the value increases, the brightness of the image SHOULD increase.

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


Gets or sets a 32-bit signed integer that specifies the brightness level. This value MUST be in the range -255 through 255, with effects as follows: -255 \\u2264 value < 0 As the value decreases, the brightness of the image SHOULD decrease. 0 A value of 0 specifies that the brightness MUST NOT change. 0 < value \\u2264 255 As the value increases, the brightness of the image SHOULD increase.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


Gets or sets a 32-bit signed integer that specifies the contrast level. This value MUST be in the range -100 through 100, with effects as follows: -100 \\u2264 value < 0 As the value decreases, the contrast of the image SHOULD decrease. 0 A value of 0 specifies that the contrast MUST NOT change. 0 < value \\u2264 100 As the value increases, the contrast of the image SHOULD increase.

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


Gets or sets a 32-bit signed integer that specifies the contrast level. This value MUST be in the range -100 through 100, with effects as follows: -100 \\u2264 value < 0 As the value decreases, the contrast of the image SHOULD decrease. 0 A value of 0 specifies that the contrast MUST NOT change. 0 < value \\u2264 100 As the value increases, the contrast of the image SHOULD increase.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

