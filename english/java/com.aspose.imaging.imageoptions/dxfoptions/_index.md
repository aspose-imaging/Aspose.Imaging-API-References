---
title: DxfOptions
second_title: Aspose.Imaging for Java API Reference
description: The Dxf file format creation options.
type: docs
weight: 17
url: /java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

The Dxf file format creation options.
## Constructors

| Constructor | Description |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | Coping constructor |
## Methods

| Method | Description |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | How many points to generate when converting Bezier curves to polylines, minimum 4. |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | How many points to generate when converting Bezier curves to polylines, minimum 4. |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | Works when \#textAsLines is set to `true`. |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | Works when \#textAsLines is set to `true`. |
| [getTextAsLines()](#getTextAsLines--) | Whether text should be exported as contours consisting of polylines (default) or as editable Autocad TEXT entities. |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | Whether text should be exported as contours consisting of polylines (default) or as editable Autocad TEXT entities. |

## Example: This example demonstrates export to Dxf format

``` java

//Create Image instance and initialize it with an existing image file from disk location
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


Coping constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | The source options for coping |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


How many points to generate when converting Bezier curves to polylines, minimum 4. Used when (/) and (/) are both /// set to `true`

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


How many points to generate when converting Bezier curves to polylines, minimum 4. Used when (/) and (/) are both /// set to `true`

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


Works when \#textAsLines is set to `true`. Whether to convert Bezier curves in text contours to multipoint polylines.

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


Works when \#textAsLines is set to `true`. Whether to convert Bezier curves in text contours to multipoint polylines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


Whether text should be exported as contours consisting of polylines (default) or as editable Autocad TEXT entities. If this option set

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


Whether text should be exported as contours consisting of polylines (default) or as editable Autocad TEXT entities. If this option set

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

