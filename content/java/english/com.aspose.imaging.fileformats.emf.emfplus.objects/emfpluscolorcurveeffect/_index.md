---
title: EmfPlusColorCurveEffect
second_title: Aspose.Imaging for Java API Reference
description: The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.
type: docs
weight: 27
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | Gets or sets a 32-bit unsigned integer that specifies the curve adjustment to apply to the colors in bitmap. |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | Gets or sets a 32-bit unsigned integer that specifies the curve adjustment to apply to the colors in bitmap. |
| [getCurveChannel()](#getCurveChannel--) | Gets or sets a 32-bit unsigned integer that specifies the color channel to which the curve adjustment applies. |
| [setCurveChannel(int value)](#setCurveChannel-int-) | Gets or sets a 32-bit unsigned integer that specifies the color channel to which the curve adjustment applies. |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | Gets or sets a 32-bit signed integer that specifies the intensity of the curve adjustment to the color channel specified by CurveChannel. |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | Gets or sets a 32-bit signed integer that specifies the intensity of the curve adjustment to the color channel specified by CurveChannel. |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


Gets or sets a 32-bit unsigned integer that specifies the curve adjustment to apply to the colors in bitmap. This value MUST be defined in the CurveAdjustments enumeration (section 2.1.1.7).

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the curve adjustment to apply to the colors in bitmap. This value MUST be defined in the CurveAdjustments enumeration (section 2.1.1.7).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


Gets or sets a 32-bit unsigned integer that specifies the color channel to which the curve adjustment applies. This value MUST be defined in the CurveChannel enumeration (section 2.1.1.8).

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the color channel to which the curve adjustment applies. This value MUST be defined in the CurveChannel enumeration (section 2.1.1.8).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


Gets or sets a 32-bit signed integer that specifies the intensity of the curve adjustment to the color channel specified by CurveChannel. The ranges of meaningful values for this field vary according to the CurveAdjustment value, as follows: Exposure adjustment range: -255 \\u2264 value < 0 As the value decreases, the exposure of the image SHOULD decrease. 0 A value of 0 specifies that the exposure MUST NOT change. 0 < value \\u2264 255 As the value increases, the exposure of the image SHOULD increase. Density adjustment range: -255 \\u2264 value < 0 As the value decreases, the density of the image SHOULD decrease, resulting in a darker image. 0 A value of 0 specifies that the density MUST NOT change. 0 < value \\u2264 255 As the value increases, the density of the image SHOULD increase. Contrast adjustment range: -100 \\u2264 value < 0 As the value decreases, the contrast of the image SHOULD decrease. 0 A value of 0 specifies that the contrast MUST NOT change. 0 < value \\u2264 100 As the value increases, the contrast of the image SHOULD increase. Highlight adjustment range: -100 \\u2264 value < 0 As the value decreases, the light areas of the image SHOULD appear darker. 0 A value of 0 specifies that the highlight MUST NOT change. 0 < value \\u2264 100 As the value increases, the light areas of the image SHOULD appear lighter. Shadow adjustment range: -100 \\u2264 value < 0 As the value decreases, the dark areas of the image SHOULD appear darker. 0 A value of 0 specifies that the shadow MUST NOT change. 0 < value \\u2264 100 As the value increases, the dark areas of the image SHOULD appear lighter. White saturation adjustment range: 0 \\u2014 255 As the value increases, the upper limit of the range of color channel intensities increases. Black saturation adjustment range: 0 \\u2014 255 As the value increases, the lower limit of the range of color channel intensities increases.

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


Gets or sets a 32-bit signed integer that specifies the intensity of the curve adjustment to the color channel specified by CurveChannel. The ranges of meaningful values for this field vary according to the CurveAdjustment value, as follows: Exposure adjustment range: -255 \\u2264 value < 0 As the value decreases, the exposure of the image SHOULD decrease. 0 A value of 0 specifies that the exposure MUST NOT change. 0 < value \\u2264 255 As the value increases, the exposure of the image SHOULD increase. Density adjustment range: -255 \\u2264 value < 0 As the value decreases, the density of the image SHOULD decrease, resulting in a darker image. 0 A value of 0 specifies that the density MUST NOT change. 0 < value \\u2264 255 As the value increases, the density of the image SHOULD increase. Contrast adjustment range: -100 \\u2264 value < 0 As the value decreases, the contrast of the image SHOULD decrease. 0 A value of 0 specifies that the contrast MUST NOT change. 0 < value \\u2264 100 As the value increases, the contrast of the image SHOULD increase. Highlight adjustment range: -100 \\u2264 value < 0 As the value decreases, the light areas of the image SHOULD appear darker. 0 A value of 0 specifies that the highlight MUST NOT change. 0 < value \\u2264 100 As the value increases, the light areas of the image SHOULD appear lighter. Shadow adjustment range: -100 \\u2264 value < 0 As the value decreases, the dark areas of the image SHOULD appear darker. 0 A value of 0 specifies that the shadow MUST NOT change. 0 < value \\u2264 100 As the value increases, the dark areas of the image SHOULD appear lighter. White saturation adjustment range: 0 \\u2014 255 As the value increases, the upper limit of the range of color channel intensities increases. Black saturation adjustment range: 0 \\u2014 255 As the value increases, the lower limit of the range of color channel intensities increases.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

