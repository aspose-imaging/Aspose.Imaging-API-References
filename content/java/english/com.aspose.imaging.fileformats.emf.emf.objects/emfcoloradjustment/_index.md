---
title: EmfColorAdjustment
second_title: Aspose.Imaging for Java API Reference
description: The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.
type: docs
weight: 12
url: /com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfColorAdjustment extends EmfObject
```

The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfColorAdjustment()](#EmfColorAdjustment--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Gets or sets a 16-bit unsigned integer that specifies the size in bytes of this object. |
| [setSize(short value)](#setSize-short-) | Gets or sets a 16-bit unsigned integer that specifies the size in bytes of this object. |
| [getValues()](#getValues--) | Gets or sets a 16-bit unsigned integer that specifies how to prepare the output image. |
| [setValues(int value)](#setValues-int-) | Gets or sets a 16-bit unsigned integer that specifies how to prepare the output image. |
| [getIlluminantIndex()](#getIlluminantIndex--) | Gets or sets a 16-bit unsigned integer that specifies the type of standard light source under which the image is viewed, from the Illuminant enumeration (section 2.1.19). |
| [setIlluminantIndex(int value)](#setIlluminantIndex-int-) | Gets or sets a 16-bit unsigned integer that specifies the type of standard light source under which the image is viewed, from the Illuminant enumeration (section 2.1.19). |
| [getRedGamma()](#getRedGamma--) | Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the red primary of the source colors. |
| [setRedGamma(short value)](#setRedGamma-short-) | Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the red primary of the source colors. |
| [getGreenGamma()](#getGreenGamma--) | Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the green primary of the source colors. |
| [setGreenGamma(short value)](#setGreenGamma-short-) | Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the green primary of the source colors. |
| [getBlueGamma()](#getBlueGamma--) | Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the blue primary of the source colors. |
| [setBlueGamma(short value)](#setBlueGamma-short-) | Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the blue primary of the source colors. |
| [getReferenceBlack()](#getReferenceBlack--) | Gets or sets a 16-bit unsigned integer that specifies the black reference for the source colors. |
| [setReferenceBlack(short value)](#setReferenceBlack-short-) | Gets or sets a 16-bit unsigned integer that specifies the black reference for the source colors. |
| [getReferenceWhite()](#getReferenceWhite--) | Gets or sets a 16-bit unsigned integer that specifies the white reference for the source colors. |
| [setReferenceWhite(short value)](#setReferenceWhite-short-) | Gets or sets a 16-bit unsigned integer that specifies the white reference for the source colors. |
| [getContrast()](#getContrast--) | Gets or sets a 16-bit signed integer that specifies the amount of contrast to be applied to the source object. |
| [setContrast(short value)](#setContrast-short-) | Gets or sets a 16-bit signed integer that specifies the amount of contrast to be applied to the source object. |
| [getBrightness()](#getBrightness--) | Gets or sets a 16-bit signed integer that specifies the amount of brightness to be applied to the source object. |
| [setBrightness(short value)](#setBrightness-short-) | Gets or sets a 16-bit signed integer that specifies the amount of brightness to be applied to the source object. |
| [getColorfullness()](#getColorfullness--) | Gets or sets a 16-bit signed integer that specifies the amount of colorfulness to be applied to the source object. |
| [setColorfullness(short value)](#setColorfullness-short-) | Gets or sets a 16-bit signed integer that specifies the amount of colorfulness to be applied to the source object. |
| [getRedGreenTint()](#getRedGreenTint--) | Gets or sets 16-bit signed integer that specifies the amount of red or green tint adjustment to be applied to the source object. |
| [setRedGreenTint(short value)](#setRedGreenTint-short-) | Gets or sets 16-bit signed integer that specifies the amount of red or green tint adjustment to be applied to the source object. |
### EmfColorAdjustment() {#EmfColorAdjustment--}
```
public EmfColorAdjustment()
```


### getSize() {#getSize--}
```
public short getSize()
```


Gets or sets a 16-bit unsigned integer that specifies the size in bytes of this object. This MUST be 0x0018.

**Returns:**
short
### setSize(short value) {#setSize-short-}
```
public void setSize(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the size in bytes of this object. This MUST be 0x0018.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getValues() {#getValues--}
```
public int getValues()
```


Gets or sets a 16-bit unsigned integer that specifies how to prepare the output image. This field can be set to NULL or to any combination of values in the ColorAdjustment enumeration (section 2.1.5).

**Returns:**
int
### setValues(int value) {#setValues-int-}
```
public void setValues(int value)
```


Gets or sets a 16-bit unsigned integer that specifies how to prepare the output image. This field can be set to NULL or to any combination of values in the ColorAdjustment enumeration (section 2.1.5).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getIlluminantIndex() {#getIlluminantIndex--}
```
public int getIlluminantIndex()
```


Gets or sets a 16-bit unsigned integer that specifies the type of standard light source under which the image is viewed, from the Illuminant enumeration (section 2.1.19).

**Returns:**
int
### setIlluminantIndex(int value) {#setIlluminantIndex-int-}
```
public void setIlluminantIndex(int value)
```


Gets or sets a 16-bit unsigned integer that specifies the type of standard light source under which the image is viewed, from the Illuminant enumeration (section 2.1.19).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRedGamma() {#getRedGamma--}
```
public short getRedGamma()
```


Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the red primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. A value of 10,000 means gamma correction MUST NOT be performed.

**Returns:**
short
### setRedGamma(short value) {#setRedGamma-short-}
```
public void setRedGamma(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the red primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. A value of 10,000 means gamma correction MUST NOT be performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getGreenGamma() {#getGreenGamma--}
```
public short getGreenGamma()
```


Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the green primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. A value of 10,000 means gamma correction MUST NOT be performed.

**Returns:**
short
### setGreenGamma(short value) {#setGreenGamma-short-}
```
public void setGreenGamma(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the green primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. A value of 10,000 means gamma correction MUST NOT be performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getBlueGamma() {#getBlueGamma--}
```
public short getBlueGamma()
```


Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the blue primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. A value of 10,000 means gamma correction MUST NOT be performed.

**Returns:**
short
### setBlueGamma(short value) {#setBlueGamma-short-}
```
public void setBlueGamma(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the nth power gamma correction value for the blue primary of the source colors. This value SHOULD be in the range from 2,500 to 65,000. A value of 10,000 means gamma correction MUST NOT be performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getReferenceBlack() {#getReferenceBlack--}
```
public short getReferenceBlack()
```


Gets or sets a 16-bit unsigned integer that specifies the black reference for the source colors. Any colors that are darker than this are treated as black. This value SHOULD be in the range from zero to 4,000

**Returns:**
short
### setReferenceBlack(short value) {#setReferenceBlack-short-}
```
public void setReferenceBlack(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the black reference for the source colors. Any colors that are darker than this are treated as black. This value SHOULD be in the range from zero to 4,000

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getReferenceWhite() {#getReferenceWhite--}
```
public short getReferenceWhite()
```


Gets or sets a 16-bit unsigned integer that specifies the white reference for the source colors. Any colors that are lighter than this are treated as white. This value SHOULD be in the range from 6,000 to 10,000.

**Returns:**
short
### setReferenceWhite(short value) {#setReferenceWhite-short-}
```
public void setReferenceWhite(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the white reference for the source colors. Any colors that are lighter than this are treated as white. This value SHOULD be in the range from 6,000 to 10,000.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getContrast() {#getContrast--}
```
public short getContrast()
```


Gets or sets a 16-bit signed integer that specifies the amount of contrast to be applied to the source object. This value SHOULD be in the range from \\u2013100 to 100. A value of zero means contrast adjustment MUST NOT be performed.

**Returns:**
short
### setContrast(short value) {#setContrast-short-}
```
public void setContrast(short value)
```


Gets or sets a 16-bit signed integer that specifies the amount of contrast to be applied to the source object. This value SHOULD be in the range from \\u2013100 to 100. A value of zero means contrast adjustment MUST NOT be performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getBrightness() {#getBrightness--}
```
public short getBrightness()
```


Gets or sets a 16-bit signed integer that specifies the amount of brightness to be applied to the source object. This value SHOULD be in the range from \\u2013100 to 100. A value of zero means brightness adjustment MUST NOT be performed.

**Returns:**
short
### setBrightness(short value) {#setBrightness-short-}
```
public void setBrightness(short value)
```


Gets or sets a 16-bit signed integer that specifies the amount of brightness to be applied to the source object. This value SHOULD be in the range from \\u2013100 to 100. A value of zero means brightness adjustment MUST NOT be performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getColorfullness() {#getColorfullness--}
```
public short getColorfullness()
```


Gets or sets a 16-bit signed integer that specifies the amount of colorfulness to be applied to the source object. This value SHOULD be in the range from \\u2013100 to 100. A value of zero means colorfulness adjustment MUST NOT be performed

**Returns:**
short
### setColorfullness(short value) {#setColorfullness-short-}
```
public void setColorfullness(short value)
```


Gets or sets a 16-bit signed integer that specifies the amount of colorfulness to be applied to the source object. This value SHOULD be in the range from \\u2013100 to 100. A value of zero means colorfulness adjustment MUST NOT be performed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getRedGreenTint() {#getRedGreenTint--}
```
public short getRedGreenTint()
```


Gets or sets 16-bit signed integer that specifies the amount of red or green tint adjustment to be applied to the source object. This value SHOULD be in the range from \\u2013100 to 100. Positive numbers adjust towards red and negative numbers adjust towards green. A value of zero means tint adjustment MUST NOT be performed

**Returns:**
short
### setRedGreenTint(short value) {#setRedGreenTint-short-}
```
public void setRedGreenTint(short value)
```


Gets or sets 16-bit signed integer that specifies the amount of red or green tint adjustment to be applied to the source object. This value SHOULD be in the range from \\u2013100 to 100. Positive numbers adjust towards red and negative numbers adjust towards green. A value of zero means tint adjustment MUST NOT be performed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

