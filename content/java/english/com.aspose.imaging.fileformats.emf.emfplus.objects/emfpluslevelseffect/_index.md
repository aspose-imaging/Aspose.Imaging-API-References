---
title: EmfPlusLevelsEffect
second_title: Aspose.Imaging for Java API Reference
description: The LevelsEffect object specifies adjustments to the highlights midtones and shadows of an image.
type: docs
weight: 51
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getHighlight()](#getHighlight--) | Gets or sets the Specifies how much to lighten the highlights of an image. |
| [setHighlight(int value)](#setHighlight-int-) | Gets or sets the Specifies how much to lighten the highlights of an image. |
| [getMidTone()](#getMidTone--) | Gets or sets the Specifies how much to lighten or darken the midtones of an image. |
| [setMidTone(int value)](#setMidTone-int-) | Gets or sets the Specifies how much to lighten or darken the midtones of an image. |
| [getShadow()](#getShadow--) | Gets or sets the Specifies how much to darken the shadows of an image. |
| [setShadow(int value)](#setShadow-int-) | Gets or sets the Specifies how much to darken the shadows of an image. |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


Gets or sets the Specifies how much to lighten the highlights of an image. The color channel values at the high end of the intensity range are altered more than values near the middle or low ends, which means an image can be lightened without losing the contrast between the darker portions of the image. 0 \\u2264 value < Specifies that highlights with a percent of intensity above this threshold SHOULD 100 be increased. 100 Specifies that highlights MUST NOT change.

Value: The highlight.

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


Gets or sets the Specifies how much to lighten the highlights of an image. The color channel values at the high end of the intensity range are altered more than values near the middle or low ends, which means an image can be lightened without losing the contrast between the darker portions of the image. 0 \\u2264 value < Specifies that highlights with a percent of intensity above this threshold SHOULD 100 be increased. 100 Specifies that highlights MUST NOT change.

Value: The highlight.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


Gets or sets the Specifies how much to lighten or darken the midtones of an image. Color channel values in the middle of the intensity range are altered more than values near the high or low ends, which means an image can be lightened or darkened without losing the contrast between the darkest and lightest portions of the image. -100 \\u2264 value < 0 Specifies that midtones are made darker. 0 Specifies that midtones MUST NOT change. 0 < value \\u2264 100 Specifies that midtones are made lighter.

Value: The mid tone.

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


Gets or sets the Specifies how much to lighten or darken the midtones of an image. Color channel values in the middle of the intensity range are altered more than values near the high or low ends, which means an image can be lightened or darkened without losing the contrast between the darkest and lightest portions of the image. -100 \\u2264 value < 0 Specifies that midtones are made darker. 0 Specifies that midtones MUST NOT change. 0 < value \\u2264 100 Specifies that midtones are made lighter.

Value: The mid tone.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


Gets or sets the Specifies how much to darken the shadows of an image. Color channel values at the low end of the intensity range are altered more than values near the middle or high ends, which means an image can be darkened without losing the contrast between the lighter portions of the image. 0 Specifies that shadows MUST NOT change. 0 < value \\u2264 100 Specifies that shadows with a percent of intensity below this threshold are made darker.

Value: The shadow.

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


Gets or sets the Specifies how much to darken the shadows of an image. Color channel values at the low end of the intensity range are altered more than values near the middle or high ends, which means an image can be darkened without losing the contrast between the lighter portions of the image. 0 Specifies that shadows MUST NOT change. 0 < value \\u2264 100 Specifies that shadows with a percent of intensity below this threshold are made darker.

Value: The shadow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

