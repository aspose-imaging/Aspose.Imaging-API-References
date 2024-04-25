---
title: EmfPlusTintEffect
second_title: Aspose.Imaging for Java API Reference
description: The TintEffect object specifies an addition of black or white to a specified hue in an image.
type: docs
weight: 79
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

The TintEffect object specifies an addition of black or white to a specified hue in an image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getHue()](#getHue--) | Gets or sets a 32-bit signed integer that specifies the hue to which the tint effect is applied. |
| [setHue(int value)](#setHue-int-) | Gets or sets a 32-bit signed integer that specifies the hue to which the tint effect is applied. |
| [getAmount()](#getAmount--) | Gets or sets A 32-bit signed integer that specifies how much the hue is strengthened or weakened. |
| [setAmount(int value)](#setAmount-int-) | Gets or sets A 32-bit signed integer that specifies how much the hue is strengthened or weakened. |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


Gets or sets a 32-bit signed integer that specifies the hue to which the tint effect is applied. -180 \\u2264 value < 0 The color at a specified counter-clockwise rotation of the color wheel, starting from blue. 0 A value of 0 specifies the color blue on the color wheel. 0 < value \\u2264 180 The color at a specified clockwise rotation of the color wheel, starting from blue

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


Gets or sets a 32-bit signed integer that specifies the hue to which the tint effect is applied. -180 \\u2264 value < 0 The color at a specified counter-clockwise rotation of the color wheel, starting from blue. 0 A value of 0 specifies the color blue on the color wheel. 0 < value \\u2264 180 The color at a specified clockwise rotation of the color wheel, starting from blue

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


Gets or sets A 32-bit signed integer that specifies how much the hue is strengthened or weakened. -100 \\u2264 value < 0 Negative values specify how much the hue is weakened, which equates to the addition of black. 0 A value of 0 specifies that the tint MUST NOT change. 0 < value \\u2264 100 Positive values specify how much the hue is strengthened, which equates to the addition of white.

Value: The amount.

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


Gets or sets A 32-bit signed integer that specifies how much the hue is strengthened or weakened. -100 \\u2264 value < 0 Negative values specify how much the hue is weakened, which equates to the addition of black. 0 A value of 0 specifies that the tint MUST NOT change. 0 < value \\u2264 100 Positive values specify how much the hue is strengthened, which equates to the addition of white.

Value: The amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

