---
title: EmfPlusColorBalanceEffect
second_title: Aspose.Imaging for Java API Reference
description: The ColorBalanceEffect object specifies adjustments to the relative amounts of red green and blue in an image.
type: docs
weight: 26
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

The ColorBalanceEffect object specifies adjustments to the relative amounts of red, green, and blue in an image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | Gets or sets a 32-bit signed integer that specifies a change in the amount of red in the image. |
| [setCyanRed(int value)](#setCyanRed-int-) | Gets or sets a 32-bit signed integer that specifies a change in the amount of red in the image. |
| [getMagentaGreen()](#getMagentaGreen--) | Gets or sets a 32-bit signed integer that specifies a change in the amount of green in the image. |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | Gets or sets a 32-bit signed integer that specifies a change in the amount of green in the image. |
| [getYellowBlue()](#getYellowBlue--) | Gets or sets a 32-bit signed integer that specifies a change in the amount of blue in the image. |
| [setYellowBlue(int value)](#setYellowBlue-int-) | Gets or sets a 32-bit signed integer that specifies a change in the amount of blue in the image. |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


Gets or sets a 32-bit signed integer that specifies a change in the amount of red in the image. This value MUST be in the range -100 through 100, with effects as follows: -100 \\u2264 value < 0 As the value decreases, the amount of red in the image SHOULD decrease and the amount of cyan SHOULD increase. 0 A value of 0 specifies that the amounts of red and cyan MUST NOT change. 0 < value \\u2264 100 As the value increases, the amount of red in the image SHOULD increase and the amount of cyan SHOULD decrease.

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


Gets or sets a 32-bit signed integer that specifies a change in the amount of red in the image. This value MUST be in the range -100 through 100, with effects as follows: -100 \\u2264 value < 0 As the value decreases, the amount of red in the image SHOULD decrease and the amount of cyan SHOULD increase. 0 A value of 0 specifies that the amounts of red and cyan MUST NOT change. 0 < value \\u2264 100 As the value increases, the amount of red in the image SHOULD increase and the amount of cyan SHOULD decrease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


Gets or sets a 32-bit signed integer that specifies a change in the amount of green in the image. This value MUST be in the range -100 through 100, with effects as follows: -100 \\u2264 value < 0 As the value decreases, the amount of green in the image SHOULD decrease and the amount of magenta SHOULD increase. 0 A value of 0 specifies that the amounts of green and magenta MUST NOT change. 0 < value \\u2264 100 As the value increases, the amount of green in the image SHOULD increase and the amount of magenta SHOULD decrease.

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


Gets or sets a 32-bit signed integer that specifies a change in the amount of green in the image. This value MUST be in the range -100 through 100, with effects as follows: -100 \\u2264 value < 0 As the value decreases, the amount of green in the image SHOULD decrease and the amount of magenta SHOULD increase. 0 A value of 0 specifies that the amounts of green and magenta MUST NOT change. 0 < value \\u2264 100 As the value increases, the amount of green in the image SHOULD increase and the amount of magenta SHOULD decrease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


Gets or sets a 32-bit signed integer that specifies a change in the amount of blue in the image. This value MUST be in the range -100 through 100, with effects as follows: -100 \\u2264 value < 0 As the value decreases, the amount of blue in the image SHOULD decrease and the amount of yellow SHOULD increase. 0 A value of 0 specifies that the amounts of blue and yellow MUST NOT change. 0 < value \\u2264 100 As the value increases, the amount of blue in the image SHOULD increase and the amount of yellow SHOULD decrease.

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


Gets or sets a 32-bit signed integer that specifies a change in the amount of blue in the image. This value MUST be in the range -100 through 100, with effects as follows: -100 \\u2264 value < 0 As the value decreases, the amount of blue in the image SHOULD decrease and the amount of yellow SHOULD increase. 0 A value of 0 specifies that the amounts of blue and yellow MUST NOT change. 0 < value \\u2264 100 As the value increases, the amount of blue in the image SHOULD increase and the amount of yellow SHOULD decrease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

