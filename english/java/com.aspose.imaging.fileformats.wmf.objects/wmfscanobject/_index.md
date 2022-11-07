---
title: WmfScanObject
second_title: Aspose.Imaging for Java API Reference
description: The Scan Object specifies a collection of scanlines.
type: docs
weight: 69
url: /java/com.aspose.imaging.fileformats.wmf.objects/wmfscanobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfScanObject extends MetaObject
```

The Scan Object specifies a collection of scanlines.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfScanObject()](#WmfScanObject--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets or sets the count. |
| [setCount(int value)](#setCount-int-) | Gets or sets the count. |
| [getTop()](#getTop--) | Gets or sets the top. |
| [setTop(int value)](#setTop-int-) | Gets or sets the top. |
| [getBottom()](#getBottom--) | Gets or sets the bottom. |
| [setBottom(int value)](#setBottom-int-) | Gets or sets the bottom. |
| [getScanLines()](#getScanLines--) | Gets or sets the scan lines. |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | Gets or sets the scan lines. |
| [getCount2()](#getCount2--) | Gets or sets the count2. |
| [setCount2(int value)](#setCount2-int-) | Gets or sets the count2. |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


Gets or sets the count.

Value: The number of horizontal (x-axis) coordinates in the `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines` array. This value MUST be a multiple of 2, since left and right endpoints are required to specify each scanline.

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Gets or sets the count.

Value: The number of horizontal (x-axis) coordinates in the `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines` array. This value MUST be a multiple of 2, since left and right endpoints are required to specify each scanline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Gets or sets the top.

Value: The vertical (y-axis) coordinate, in logical units, of the top scanline.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Gets or sets the top.

Value: The vertical (y-axis) coordinate, in logical units, of the top scanline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Gets or sets the bottom.

Value: The vertical (y-axis) coordinate, in logical units, of the bottom scanline.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Gets or sets the bottom.

Value: The vertical (y-axis) coordinate, in logical units, of the bottom scanline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


Gets or sets the scan lines.

Value: An array of scanlines, each specified by left and right horizontal (x-axis) coordinates of its endpoints.

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


Gets or sets the scan lines.

Value: An array of scanlines, each specified by left and right horizontal (x-axis) coordinates of its endpoints.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


Gets or sets the count2.

Value: The same as the value of the `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count` field; it is present to allow upward travel in the structure.

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


Gets or sets the count2.

Value: The same as the value of the `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count` field; it is present to allow upward travel in the structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

