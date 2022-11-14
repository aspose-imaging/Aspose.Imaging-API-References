---
title: WmfDibCreatePatternBrush
second_title: Aspose.Imaging for Java API Reference
description: The META_DIBCREATEPATTERNBRUSH record creates a Brush Object section     2.2.1.1 with a pattern specified by a DeviceIndependentBitmap DIB     Object section 2.2.2.9.
type: docs
weight: 29
url: /java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

The META\_DIBCREATEPATTERNBRUSH record creates a Brush Object (section 2.2.1.1) with a pattern specified by a DeviceIndependentBitmap (DIB) Object (section 2.2.2.9).
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getStyle()](#getStyle--) | Gets or sets the style. |
| [setStyle(int value)](#setStyle-int-) | Gets or sets the style. |
| [getColorUsage()](#getColorUsage--) | Gets or sets the color usage. |
| [setColorUsage(int value)](#setColorUsage-int-) | Gets or sets the color usage. |
| [getSourceBitmap()](#getSourceBitmap--) | Gets or sets the source bitmap. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets the source bitmap. |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


Gets or sets the style.

Value: The legal values for this field are defined as follows: if the value is not BS\_PATTERN, BS\_DIBPATTERNPT MUST be assumed. These values are specified in the BrushStyle Enumeration (section 2.1.1.4).

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Gets or sets the style.

Value: The legal values for this field are defined as follows: if the value is not BS\_PATTERN, BS\_DIBPATTERNPT MUST be assumed. These values are specified in the BrushStyle Enumeration (section 2.1.1.4).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Gets or sets the color usage.

Value: The Colors field of a DIB Object contains explicit RGB values, or indexes into a palette.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Gets or sets the color usage.

Value: The Colors field of a DIB Object contains explicit RGB values, or indexes into a palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Gets or sets the source bitmap.

Value: Variable-bit DIB Object data that defines the pattern to use in the brush.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Gets or sets the source bitmap.

Value: Variable-bit DIB Object data that defines the pattern to use in the brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

