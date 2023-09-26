---
title: EmfPlusHueSaturationLightnessEffect
second_title: Aspose.Imaging for Java API Reference
description: The HueSaturationLightnessEffect object specifies adjustments to the hue saturation and lightness of an image.
type: docs
weight: 46
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushuesaturationlightnesseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusHueSaturationLightnessEffect extends EmfPlusImageEffectsObjectType
```

The HueSaturationLightnessEffect object specifies adjustments to the hue, saturation, and lightness of an image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusHueSaturationLightnessEffect()](#EmfPlusHueSaturationLightnessEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getHueLevel()](#getHueLevel--) | Gets or sets the Specifies the adjustment to the hue. |
| [setHueLevel(int value)](#setHueLevel-int-) | Gets or sets the Specifies the adjustment to the hue. |
| [getSaturationLevel()](#getSaturationLevel--) | Gets or sets the Specifies the adjustment to the saturation. |
| [setSaturationLevel(int value)](#setSaturationLevel-int-) | Gets or sets the Specifies the adjustment to the saturation. |
| [getLightnessLevel()](#getLightnessLevel--) | Gets or sets the Specifies the adjustment to the lightness. |
| [setLightnessLevel(int value)](#setLightnessLevel-int-) | Gets or sets the Specifies the adjustment to the lightness. |
### EmfPlusHueSaturationLightnessEffect() {#EmfPlusHueSaturationLightnessEffect--}
```
public EmfPlusHueSaturationLightnessEffect()
```


### getHueLevel() {#getHueLevel--}
```
public int getHueLevel()
```


Gets or sets the Specifies the adjustment to the hue. -180 \\u2264 value < 0 Negative values specify clockwise rotation on the color wheel. 0 A value of 0 specifies that the hue MUST NOT change. 0 < value \\u2264 180 Positive values specify counter-clockwise rotation on the color wheel.

Value: The hue level.

**Returns:**
int
### setHueLevel(int value) {#setHueLevel-int-}
```
public void setHueLevel(int value)
```


Gets or sets the Specifies the adjustment to the hue. -180 \\u2264 value < 0 Negative values specify clockwise rotation on the color wheel. 0 A value of 0 specifies that the hue MUST NOT change. 0 < value \\u2264 180 Positive values specify counter-clockwise rotation on the color wheel.

Value: The hue level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaturationLevel() {#getSaturationLevel--}
```
public int getSaturationLevel()
```


Gets or sets the Specifies the adjustment to the saturation. -100 \\u2264 value < 0 Negative values specify decreasing saturation. 0 A value of 0 specifies that the saturation MUST NOT change. 0 < value \\u2264 100 Positive values specify increasing saturation.

Value: The saturation level.

**Returns:**
int
### setSaturationLevel(int value) {#setSaturationLevel-int-}
```
public void setSaturationLevel(int value)
```


Gets or sets the Specifies the adjustment to the saturation. -100 \\u2264 value < 0 Negative values specify decreasing saturation. 0 A value of 0 specifies that the saturation MUST NOT change. 0 < value \\u2264 100 Positive values specify increasing saturation.

Value: The saturation level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLightnessLevel() {#getLightnessLevel--}
```
public int getLightnessLevel()
```


Gets or sets the Specifies the adjustment to the lightness. -100 \\u2264 value < 0 Negative values specify decreasing lightness. 0 A value of 0 specifies that the lightness MUST NOT change. 0 < value \\u2264 100 Positive values specify increasing lightness.

Value: The lightness level.

**Returns:**
int
### setLightnessLevel(int value) {#setLightnessLevel-int-}
```
public void setLightnessLevel(int value)
```


Gets or sets the Specifies the adjustment to the lightness. -100 \\u2264 value < 0 Negative values specify decreasing lightness. 0 A value of 0 specifies that the lightness MUST NOT change. 0 < value \\u2264 100 Positive values specify increasing lightness.

Value: The lightness level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

