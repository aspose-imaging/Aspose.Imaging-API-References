---
title: EmfPlusHatchBrushData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusHatchBrushData object specifies a hatch pattern for a graphics brush.
type: docs
weight: 45
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

The EmfPlusHatchBrushData object specifies a hatch pattern for a graphics brush.

Graphics brushes are specified by `EmfPlusBrush` objects (section 2.2.1.1). A hatch brush paints a background and draws a pattern of lines, dots, dashes, squares, and crosshatch lines over this background. The hatch brush defines two colors: one for the background and one for the pattern over the background. The color of the background is called the background color, and the color of the pattern is called the foreground color.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to paint the background of the hatch pattern. |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to paint the background of the hatch pattern. |
| [getForeArgb32Color()](#getForeArgb32Color--) | Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to draw the lines of the hatch pattern. |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to draw the lines of the hatch pattern. |
| [getHatchStyle()](#getHatchStyle--) | Gets or sets a 32-bit unsigned integer that specifies the brush hatch style. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Gets or sets a 32-bit unsigned integer that specifies the brush hatch style. |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to paint the background of the hatch pattern.

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to paint the background of the hatch pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to draw the lines of the hatch pattern.

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to draw the lines of the hatch pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Gets or sets a 32-bit unsigned integer that specifies the brush hatch style. It MUST be defined in the `EmfPlusHatchStyle` enumeration.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the brush hatch style. It MUST be defined in the `EmfPlusHatchStyle` enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

