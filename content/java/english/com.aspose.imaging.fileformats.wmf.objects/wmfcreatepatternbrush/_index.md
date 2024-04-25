---
title: WmfCreatePatternBrush
second_title: Aspose.Imaging for Java API Reference
description: The META_CREATEPATTERNBRUSH record creates a brush object with a pattern     specified by a bitmap.
type: docs
weight: 23
url: /com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

The META\_CREATEPATTERNBRUSH record creates a brush object with a pattern specified by a bitmap.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | WMFs the record. |
## Methods

| Method | Description |
| --- | --- |
| [getBitmap()](#getBitmap--) | Gets or sets the bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Gets or sets the bitmap. |
| [getReserved()](#getReserved--) | Gets or sets the reserved. |
| [setReserved(byte[] value)](#setReserved-byte---) | Gets or sets the reserved. |
| [getPattern()](#getPattern--) | Gets or sets the pattern. |
| [setPattern(byte[] value)](#setPattern-byte---) | Gets or sets the pattern. |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


WMFs the record.

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Gets or sets the bitmap.

Value: The bitmap that specifies the pattern for the brush.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Gets or sets the bitmap.

Value: The bitmap that specifies the pattern for the brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


Gets or sets the reserved.

Value: The reserved. This field MUST be ignored.

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


Gets or sets the reserved.

Value: The reserved. This field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


Gets or sets the pattern.

Value: A variable-length array of bytes that defines the bitmap pixel data that composes the brush pattern. The length of this field, in bytes, can be computed from bitmap parameters as follows.

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


Gets or sets the pattern.

Value: A variable-length array of bytes that defines the bitmap pixel data that composes the brush pattern. The length of this field, in bytes, can be computed from bitmap parameters as follows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

