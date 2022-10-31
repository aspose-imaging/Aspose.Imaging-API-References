---
title: EmfPlusStringFormatData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.
type: docs
weight: 75
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTabStops()](#getTabStops--) | Gets or sets an optional array of floating-point values that specify the optional tab stop locations for this object. |
| [setTabStops(float[] value)](#setTabStops-float---) | Gets or sets an optional array of floating-point values that specify the optional tab stop locations for this object. |
| [getCharRange()](#getCharRange--) | Gets or sets an optional array of RangeCount EmfPlusCharacterRange objects that specify the range of character positions within a string of text. |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | Gets or sets an optional array of RangeCount EmfPlusCharacterRange objects that specify the range of character positions within a string of text. |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Gets or sets an optional array of floating-point values that specify the optional tab stop locations for this object. Each tab stop value represents the number of spaces between tab stops or, for the first tab stop, the number of spaces between the beginning of a line of text and the first tab stop. This field MUST be present if the value of the TabStopCount field in the EmfPlusStringFormat object is greater than 0.

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


Gets or sets an optional array of floating-point values that specify the optional tab stop locations for this object. Each tab stop value represents the number of spaces between tab stops or, for the first tab stop, the number of spaces between the beginning of a line of text and the first tab stop. This field MUST be present if the value of the TabStopCount field in the EmfPlusStringFormat object is greater than 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


Gets or sets an optional array of RangeCount EmfPlusCharacterRange objects that specify the range of character positions within a string of text. The bounding region is defined by the area of the display that is occupied by a group of characters specified by the character range. This field MUST be present if the value of the RangeCount field in the EmfPlusStringFormat object is greater than 0.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


Gets or sets an optional array of RangeCount EmfPlusCharacterRange objects that specify the range of character positions within a string of text. The bounding region is defined by the area of the display that is occupied by a group of characters specified by the character range. This field MUST be present if the value of the RangeCount field in the EmfPlusStringFormat object is greater than 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |

